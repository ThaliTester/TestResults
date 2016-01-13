#### Test 55902202f27eba5_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
I/DBG_POLICYDM( 5720): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
I/DBG_POLICYDM( 5720): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
D/Mms/MmsApp( 5646): [end]    initCountryIso consume time = 19.774583
D/Mms/MmsConfig( 5646): [start]    MmsConfig.init() consume time = 0.097657
D/Mms/MmsConfig( 5646): before partial update
--------- beginning of system
D/PowerManagerService( 1015): Excessive delay in ColorFade : createEglContext: 57ms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
D/PermissionCache(  256): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (375 us)
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
D/KeyguardViewMediator( 1175): setting alarm to turn off keyguard, seq = 1
D/KeyguardViewMediator( 1175): handleNotifyScreenOff
D/VolumePanel( 1175): onScreenTurnedOff()
D/VolumePanel( 1175): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/VolumePanel( 1175): mCoverBroadcastReceiver: Screen OFF end
D/SecKeyguardClockSingleView( 1175): onScreenTurnedOff
I/DBG_POLICYDM( 5720): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
E/SmartFaceService( 1015): onReceive: android.intent.action.SCREEN_ON
W/System.err( 1015): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1015): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1015): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1015): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1015): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1015): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1015): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1015): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1015): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1015): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1015): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1015): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1015): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1015): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1015): 	... 10 more
E/SmartFaceService( 1015): fail to set sysfs 1
D/PowerManagerService( 1015): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 39ms
D/Mms/MmsConfig( 5646): Load Resize quality : 80
D/EasySignUpManager_1.0.1( 5646): serviceId : 1, features : -1
I/DBG_POLICYDM( 5720): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
D/EasySignUpManager_1.0.1( 5646): isAuth is false
D/Mms/MmsConfig( 5646): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
I/DBG_POLICYDM( 5720): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
I/DBG_POLICYDM( 5720): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
I/DBG_POLICYDM( 5720): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
I/DBG_POLICYDM( 5720): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
I/DBG_POLICYDM( 5720): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
D/InputMethodManagerService( 1015): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
D/TP/MmsSmsProvider( 1449): query,matched:2117, calling pid = 5646
D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
D/TP/MmsSmsProvider( 1449): match 2117:Elapsed time : 1.162 ms
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/MotionRecognitionService( 1015):   mReceiver.onReceive : ACTION_SCREEN_ON
V/ActivityThread( 1476): updateVisibility : ActivityRecord{25eb9f34 token=android.os.BinderProxy@22c5037c {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
E/MotionRecognitionService( 1015):  handler : SCREEN_ON end
D/Launcher.HomeView( 1476): onStop
D/NotificationService( 1015): ACTION_SCREEN_ON
D/LightsService( 1015): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1015) 
D/LightsService( 1015): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1015): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1015): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/DBG_POLICYDM( 5720): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/01/18/12:08:32
I/DBG_POLICYDM( 5720): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/01/13/16:35:26
I/DBG_POLICYDM( 5720): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
I/DBG_POLICYDM( 5720): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
I/DBG_POLICYDM( 5720): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
D/PowerManagerService( 1015): Excessive delay in ColorFade : initGLShaders: 68ms
D/PowerManagerService( 1015): Excessive delay in ColorFade prepare: 205ms
I/DBG_POLICYDM( 5720): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
I/DBG_POLICYDM( 5720): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
D/DisplayPowerController( 1015): ColorFade: onAnimationStart
D/DisplayPowerController( 1015): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1015): performScreenOffTransition : no brightness animation
D/audio_hw_primary(  281): adev_set_parameters: enter: screen_state=on
I/DBG_POLICYDM( 5720): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
V/voice   (  281): voice_set_parameters: enter: screen_state=on
V/voice   (  281): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  281): platform_set_parameters: enter: screen_state=on
I/DBG_POLICYDM( 5720): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
V/msm8974_platform(  281): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  281): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  281): adev_set_parameters: exit
E/WifiNative-wlan0( 1015): do suspend false
I/wpa_supplicant( 1986): reset timer : RESET_TIMER 1
I/wpa_supplicant( 1986): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1986): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1986): Scan requested (ret=0) - scan timeout 30 seconds
D/EasySignUpManager_1.0.1( 5646): isAuth is false
D/EasySignUpManager_1.0.1( 5646): getServiceStatus : serviceId (1) is OFF
I/DBG_POLICYDM( 5720): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
I/DBG_POLICYDM( 5720): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
I/DBG_POLICYDM( 5720): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
V/AlarmManager( 1015): waitForAlarm result :4
E/CscParser( 5646): mps_code.dat does not exist
E/CscParser( 5646): customer_path =/system/csc/customer.xml
E/CscParser( 5646): fileName + /system/csc/customer.xml
D/IpRemoteDisplayController( 1015): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 1015): Bridge Server is not available
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.DailyHygiene; callingUser = 0; userId(target) = 0
V/AlarmManager( 1015): waitForAlarm result :8
D/Finsky  ( 5489): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
E/CscParser( 5646): mps_code.dat does not exist
E/CscParser( 5646): customer_path =/system/csc/customer.xml
E/CscParser( 5646): fileName + /system/csc/customer.xml
I/DBG_POLICYDM( 5720): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
E/PhotosPlugin( 5737): Loading PhotosPlugin
I/DBG_POLICYDM( 5720): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
D/CscParser( 5646): getInstance fileName =/system/csc/customer.xml
E/SPPClientService( 5776): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5776): [PushClientApplication] Push log off : This is Ship build version
D/Mms/MmsConfig( 5646):  enable multiwindow = true
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/SPPClientService( 5776): PushLog.txt file is not deleted.
D/SPPClientService( 5776): PushLog.txt file is not deleted.
D/SPPClientService( 5776): ============PushLog. stop!
D/GpsLocationProvider( 1015): receive broadcast intent, action: android.intent.action.SCREEN_ON
E/Zygote  ( 5811): MountEmulatedStorage()
E/Zygote  ( 5811): v2
I/libpersona( 5811): KNOX_SDCARD checking this for 10038
I/libpersona( 5811): KNOX_SDCARD not a persona
I/SELinux ( 5811): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5811): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5811): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5811 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/DBG_POLICYDM( 5720): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
E/Mms/MessageUtils( 5646): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 5646): updateCountryIso : update country iso info 
V/GLSActivity( 1819): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PersonaManagerService( 1015): ACTION_SCREEN_ON onReceive
D/TimaKeyStoreProvider( 5811): TimaSignature is unavailable
D/ActivityThread( 5811): Added TimaKeyStore provider
D/PersonaManagerServiceHandler( 1015): MSG_ACTION_SCREEN_ON called
D/CoverManagerWhiteLists( 1015): isAllowedToUse : SIGNATURE_MATCH
I/NfcService( 1435): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
W/art     ( 5646): Verification of boolean com.android.mms.ui.ConversationListFragment.onOptionsItemSelected(android.view.MenuItem) took 126.329ms
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/Mms/MmsConfig( 5646): [end]    init() consume time = 296.558229
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/Contact( 5646): [start]    init() consume time = 1.055833
V/GLSActivity( 1819): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DBG_POLICYDM( 5720): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
V/GLSActivity( 1819): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DBG_POLICYDM( 5720): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
E/Watchdog( 1015): !@Sync 2
D/NfcService( 1435): call the applyRouting
D/accuweather( 1725): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
D/accuweather( 1725): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1725): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/accuweather( 1725): [KK AccuPhone]>>> UIM:282 [0:0] update clock event, is not screen on!!
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
W/ResourcesManager( 5811): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5811): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/DisplayPowerState( 1015): !@ ColorFade entry
D/DisplayPowerController( 1015): ColorFade: onAnimationEnd
D/lights  ( 1015): lcd : 0 +
D/DisplayPowerController( 1015): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1015): performScreenOffTransition : no brightness animation
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/lights  ( 1015): lcd : 0 -
D/DisplayPowerController( 1015): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1015): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1015): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1015): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 1015): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1015): sysfs_write -: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1015): sysfs_write +: /sys/class/input/event3/device/enabled: 0
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/TP/MmsSmsProvider( 1449): query,matched:13, calling pid = 5646
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/MISC PowerHAL( 1015): sysfs_write -: /sys/class/input/event3/device/enabled: 0
D/TP/MmsSmsProvider( 1449): match 13:Elapsed time : 0.951 ms
D/MISC PowerHAL( 1015): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1015): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1015): Got set_interactive hint
D/SurfaceFlinger(  256): Set power mode=0, type=0 flinger=0xb8b6e690
D/DisplayManagerService( 1015): !@display_state: ON -> OFF
D/qdhwcomposer(  256): hwc_setPowerMode: Setting mode 0 on display: 0
I/DisplayManagerService( 1015): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
I/SamsungIME( 1784): getNextShiftState() cursorCapsMode : 0
V/ActivityManager( 1015): Display changed displayId=0
E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
D/ChimeraCfgMgr( 2027): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2027): Module APK com.google.android.play.games already loaded
D/Mms/Contact( 5646): [end]    init consume time = 125.520469
D/StatusBar.NetworkController( 1175): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 2027): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/DraftCache( 5646): [start]    rebuildCache consume time = 41.083489
D/TP/MmsSmsProvider( 1449): query,matched:12, calling pid = 5646
D/TP/MmsSmsProvider( 1449): match 12:Elapsed time : 1.893 ms
D/Mms/MethodReflector( 5646): getSubId is called
D/Mms/TelephonyUtils( 5646): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5646): getTelephonyProperty is called
D/Mms/DownloadManager( 5646): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5646): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5646): auto download without roaming -> true
D/Mms/DownloadManager( 5646): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 5646): getSubId is called
D/Mms/DraftCache( 5646): [end]    rebuildCache consume time = 19.230834
D/LightsService( 1015): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1015) 
D/LightsService( 1015): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1015): turn on LED for fully charged
E/lights  ( 1015): write_int failed to open -1
D/LightsService( 1015): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1015): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SSRM:n  ( 1015): SIOP:: AP = 330
E/SmartFaceService( 1015): onReceive: android.intent.action.SCREEN_OFF
W/System.err( 1015): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1015): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1015): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/SmartFaceService( 1015): fail to set sysfs 0
W/System.err( 1015): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1015): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1015): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1015): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1015): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1015): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1015): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1015): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1015): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1015): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1015): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1015): 	... 10 more
D/Mms/MethodReflector( 5646): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5646): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5646): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5646): getTelephonyProperty is called
D/Mms/DownloadManager( 5646): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5646): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5646): auto download without roaming -> true
D/Mms/DownloadManager( 5646): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5646): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5646): mAutoDownload ------> true
D/AsyncTaskServiceImpl( 2027): Submit a task: k
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SamsungIME( 1784): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/MotionRecognitionService( 1015):   mReceiver.onReceive : ACTION_SCREEN_OFF
D/ChimeraCfgMgr( 2027): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/MotionRecognitionService( 1015):  handler : SCREEN_OFF end 
D/NotificationService( 1015): ACTION_SCREEN_OFF
D/LightsService( 1015): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1015) 
D/LightsService( 1015): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService( 1015): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1015): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/audio_hw_primary(  281): adev_set_parameters: enter: screen_state=off
V/voice   (  281): voice_set_parameters: enter: screen_state=off
V/voice   (  281): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  281): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  281): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  281): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  281): adev_set_parameters: exit
I/BatteryStatsDumper( 1015): In refreshStats isReason Screen ON/OFF: true
D/ChimeraCfgMgr( 2027): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/k       ( 2027): Processing package: com.test.thalitest
D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/ComposerPerformance( 5646): 1452699327334 ms / [DONE] Composer constructor
E/CII     ( 5646): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 5646): ReservationManager()
I/Mms/ReservationManager( 5646): resetAfterConnected()
I/BackgroundCompactionService( 1015): Schedule Type1 BGCompaction
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/TP/MmsSmsProvider( 1449): query,matched:7, calling pid = 5646
D/TP/MmsSmsProvider( 1449): match 7:Elapsed time : 1.522 ms
D/Mms/ArtClassLoader( 5646): init [DONE] art
D/Mms/Conversation( 5646): [start]    init() consume time = 106.643854
D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/GassUtils( 2027): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
D/k       ( 2027): Found info for package com.test.thalitest in db.
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 5720): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/BatteryStatsDumper( 1015): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1015): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1015): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1015): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1015): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1015): Previous Battery Level: 0 Current Level: 100 Delta: -100
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/qdhwcomposer(  256): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  256): hwc_setPowerMode: Done setting mode 0 on display 0
D/SurfaceControl( 1015): Excessive delay in setPowerMode(): 255ms
D/PowerManagerService( 1015): Excessive delay in !@display_state: OFF: 256ms
E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
I/libsuspend( 1015): !@autosuspend_wakeup_count_enable
D/PowerManagerService( 1015): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 269ms
I/libsuspend( 1015): !@autosuspend_wakeup_count_enable done
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
I/PowerManagerService( 1015): [PWL] Off : 0s ago
I/PowerManagerService( 1015): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1015): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1015): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1015, ws=WorkSource{1000}) (elapsedTime=464)
I/PowerManagerService( 1015): [PWL]       PARTIAL_WAKE_LOCK              'SmartManager Framework Thread' (uid=1000, pid=1015, ws=null) (elapsedTime=82)
I/PowerManagerService( 1015): [PWL]   PowerManagerService.Broadcasts: ref count=1
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/TP/MmsSmsProvider( 1449): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1449): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1449): updateThread(), thread_id = 9223372036854775807
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
V/TP/MmsSmsDatabaseHelper( 1449): sUpgradeVersion = 0, db.getVersion() = 81
D/TP/MmsSmsProvider( 1449): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1449): need read changed broadcast:false
D/Mms/Conversation( 5646): [end]    init consume time = 64.514948
I/Mms/ReservationManager( 5646): getReservedSendMessageCount(): retMessageCount=0
D/IpRemoteDisplayController( 1015): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 1015): Bridge Server is not available
D/Mms/MessagingNotification( 5646): [start]    init() consume time = 3.033385
D/Mms/MmsApp( 5646): [end]    onCreate() consume time = 5.524896
D/Mms/MessagingNotification( 5646): [end]    init consume time = 1.449219
D/TP/MmsSmsProvider( 1449): query,matched:0, calling pid = 5646
V/TP/MmsSmsProvider( 1449): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1449): match 0:Elapsed time : 3.279 ms
D/Mms/Synchronizer( 5646): [start]    doSync consume time = 10.340468
D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/Mms/SpamFilter( 5646): [start]    SpamFilter fill() begin consume time = 10.085782
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/Mms/DownloadManager( 5646): Service state changed: Bundle[mParcelledData.dataSize=744]
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/DownloadManager( 5646): roaming ------> false, mSimSlot = 0
D/Mms/MethodReflector( 5646): getSubId is called
D/Mms/TelephonyUtils( 5646): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5646): getTelephonyProperty is called
D/Mms/DownloadManager( 5646): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5646): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5646): auto download without roaming -> true
D/Mms/DownloadManager( 5646): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5646): mAutoDownload ------> true
D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
D/TP/MmsSmsProvider( 1449): update, matched:300, calling pid = 5646
V/TP/MmsSmsProvider( 1449): syncDBData start
V/TP/MmsSmsProvider( 1449): syncDBData sms end
V/TP/MmsSmsProvider( 1449): syncDBData mms end
V/TP/MmsSmsProvider( 1449): syncDBData end
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5851): MountEmulatedStorage()
I/libpersona( 5851): KNOX_SDCARD checking this for 10072
E/Zygote  ( 5851): v2
I/libpersona( 5851): KNOX_SDCARD not a persona
I/SELinux ( 5851): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5851 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/Mms/Synchronizer( 5646): [end]    doSync consume time = 36.26125
I/SELinux ( 5851): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/TP/MmsSmsProvider( 1449): query,matched:400, calling pid = 5646
,E/SELinux ( 5851): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/FreeMessageStatusReceiver( 5646): onReceive, action : android.intent.action.PACKAGE_ADDED
D/Mms/SpamFilter( 5646): [end]    SpamFilter fill() finished consume time = 10.687708
D/ActivityManager( 1015): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/TimaKeyStoreProvider( 5851): TimaSignature is unavailable
D/ActivityThread( 5851): Added TimaKeyStore provider
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
W/BaseAppContext( 2027): Using Auth Proxy for data requests.
W/BaseAppContext( 2027): Using Auth Proxy for data requests.
I/DBG_POLICYDM( 5720): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
E/Zygote  ( 5866): MountEmulatedStorage()
E/Zygote  ( 5866): v2
I/libpersona( 5866): KNOX_SDCARD checking this for 10047
I/libpersona( 5866): KNOX_SDCARD not a persona
I/SELinux ( 5866): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5866): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/IcingInternalCorpora( 2027): getNumBytesRead when not calculated.
I/ActivityManager( 1015): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5866 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
D/GpsLocationProvider( 1015): receive broadcast intent, action: android.intent.action.SCREEN_OFF
E/SELinux ( 5866): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/BadgeProvider( 5851): onCreate
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/FreeMessageReceiverService( 5646): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5646): onHandleIntent: ACTION_PACKAGE_ADDED
D/TimaKeyStoreProvider( 5866): TimaSignature is unavailable
D/ActivityThread( 5866): Added TimaKeyStore provider
D/PersonaManagerService( 1015): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler( 1015): MSG_ACTION_SCREEN_OFF called
D/BadgeProvider( 5851): DatabaseHelper
I/ServiceManager(  313): Waiting for service AtCmdFwd...
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
V/EmergencyMode( 1411): [EmergencyStateReceiver] binteractive [false] why[3]
W/ResourcesManager( 5866): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5866): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5866): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/MessagingNotification( 5646): checkBadgeCount unreadCount=0 badgeCount=0
D/TP/SmsProvider( 1449): query,matched:26, calling pid = 5646
D/NfcService( 1435): call the applyRouting
I/ActivityManager( 1015): Killing 5286:com.sec.android.diagmonagent/1000 (adj 15): empty #31
D/TP/SmsProvider( 1449): match 26:Elapsed time : 6.584 ms
D/accuweather( 1725): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 1725): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
D/accuweather( 1725): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
I/System.out( 5489): Thread-952(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/System.out( 5489): Thread-952(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5489): Thread-952(ApacheHTTPLog):isShipBuild true
I/System.out( 5489): Thread-952(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5489): Thread-952(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/TP/MmsSmsProvider( 1449): query,matched:6, calling pid = 5646
D/EnterpriseController(  276): uids 10028
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 502 for uid 10028
D/TP/MmsSmsProvider( 1449): match 6:Elapsed time : 16.824 ms
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/WifiNative-wlan0( 1015): do suspend true
E/LibSecureUISvc( 1950): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
D/SSRM:n  ( 1015): SIOP:: AP = 320
I/PeopleDatabaseHelper( 2027): cleanUpNonGplusAccounts done.
W/BaseAppContext( 2027): Using Auth Proxy for data requests.
D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5893): MountEmulatedStorage()
E/Zygote  ( 5893): v2
I/libpersona( 5893): KNOX_SDCARD checking this for 10025
I/libpersona( 5893): KNOX_SDCARD not a persona
I/SELinux ( 5893): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5893): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5893): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5893 uid=10025 gids={50025, 9997} abi=armeabi-v7a
D/PowerManagerService( 1015): [PWL] sb release: PowerManagerService.Broadcasts
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5286/cgroup.procs: No such file or directory
I/SL_DEBUG( 5811): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5811): isLoggable:: SL_DEBUG_EXIST = false
D/TimaKeyStoreProvider( 5893): TimaSignature is unavailable
D/ActivityThread( 5893): Added TimaKeyStore provider
W/BaseAppContext( 2027): Using Auth Proxy for data requests.
I/ActivityManager( 1015): Killing 5301:com.android.providers.calendar/u0a42 (adj 15): empty #31
W/ResourcesManager( 5893): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/MyFiles ( 5866): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
I/TactileAssist( 1015): enable value -1
I/TactileAssist( 1015): internal enable value -1
I/TactileAssist( 1015): intensity value -1
I/TactileAssist( 1015): saveAppList value true
I/TactileAssist( 1015): List of disabled apps :
E/installd(  282): system dir 0 : /system/app/
E/installd(  282): system dir 1 : /system/priv-app/
E/installd(  282): system dir 2 : /vendor/app/
E/installd(  282): system dir 3 : /oem/app/
I/OMACP   ( 5893): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/Mms/Omacp( 5646): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
E/Zygote  ( 5911): MountEmulatedStorage()
I/libpersona( 5911): KNOX_SDCARD checking this for 10053
E/Zygote  ( 5911): v2
I/libpersona( 5911): KNOX_SDCARD not a persona
I/SELinux ( 5911): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5911): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5911): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5911 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
I/OMACP   ( 5893): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 5893): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 5893): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
W/art     ( 1015): Suspending all threads took: 7.426ms
I/OMACP   ( 5893): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 5893): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 5893): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 5893): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 5893): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 5893): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 5893): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
D/TimaKeyStoreProvider( 5911): TimaSignature is unavailable
D/ActivityThread( 5911): Added TimaKeyStore provider
I/OMACP   ( 5893): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 5893): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 5893): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
I/art     ( 1015): Explicit concurrent mark sweep GC freed 239056(15MB) AllocSpace objects, 12(4MB) LOS objects, 33% free, 28MB/42MB, paused 10.723ms total 256.528ms
D/SSRM:a  ( 1015): DeviceInfo:: 000000000000
D/SSRM:a  ( 1015): SettingsAirViewInfo:: 000000000
D/AndroidRuntime( 5885): 
D/AndroidRuntime( 5885): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
W/ResourcesManager( 5911): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/AndroidRuntime( 5885): CheckJNI is OFF
D/AndroidRuntime( 5885): readGMSProperty: start
D/AndroidRuntime( 5885): readGMSProperty: already setted!!
D/AndroidRuntime( 5885): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 5885): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 5885): readGMSProperty: end
D/AndroidRuntime( 5885): addProductProperty: start
W/BaseAppContext( 2027): Using Auth Proxy for data requests.
W/BaseAppContext( 2027): Using Auth Proxy for data requests.
D/PackageManager( 1015): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
D/Compatibility( 5911): onReceive() it will make start service
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
D/ActivityManager( 1015): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ContextImpl( 5811): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
W/libprocessgroup( 1015): failed to open /acct/uid_10042/pid_5301/cgroup.procs: No such file or directory
D/ActivityManager( 1015): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
D/Compatibility( 5911): onHandleIntent()
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/Compatibility( 5911): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10155, android.intent.extra.user_handle=0}]
D/Compatibility( 5911): found: 2
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
I/UpdateIcingCorporaServi( 5360): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
D/Compatibility( 5911): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5911): skipping ResolveInfo{1ca83ae0 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5911): considering ResolveInfo{1ed18199 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5911): default: com.sec.android.app.soundalive.SAControlPanelActivity
W/BaseAppContext( 2027): Using Auth Proxy for data requests.
D/Compatibility( 5911): enabling receiver ResolveInfo{a06fc5e com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5911): enabling receiver ResolveInfo{3492483f com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5911): enabling receiver ResolveInfo{1406250c com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/Compatibility( 5911): enabling receiver ResolveInfo{192f9e55 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 5911): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5811): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
I/UpdateIcingCorporaServi( 5360): UpdateCorporaTask done [took 115 ms] updated apps [took 115 ms] 
I/ActivityManager( 1015): Killing 5234:com.google.android.talk/u0a104 (adj 15): empty #31
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5943): MountEmulatedStorage()
E/Zygote  ( 5943): v2
I/ActivityManager( 1015): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=5943 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/libpersona( 5943): KNOX_SDCARD checking this for 10041
I/libpersona( 5943): KNOX_SDCARD not a persona
I/SELinux ( 5943): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5943): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5943): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5943): TimaSignature is unavailable
D/ActivityThread( 5943): Added TimaKeyStore provider
E/AffinityControl( 5885): AffinityControl: registerfunction enter
I/SA      ( 5943): [SSP] onCreated
D/AndroidRuntime( 5885): Calling main entry com.android.commands.am.Am
W/GAV2    ( 5737): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/PersonaManagerService( 1015): inState():  stateMachine is null !!
I/PersonaManagerService( 1015): PersonaId don't exist
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
I/SA      ( 5943): [TPM] There is no property file
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/SA      ( 5943): [SCU] isHaveSA() - false
I/SA      ( 5943): [TPM] getModelProperty : null
I/SA      ( 5943): [TPM] getCSCProperty : null
I/SA      ( 5943): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 5943): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 5943): [DM] TFT FEATURE: false
I/SA      ( 5943): [PMR] Received action : android.intent.action.PACKAGE_ADDED
W/ActivityManager( 1015): mDVFSHelper.acquire()
D/FocusedStackFrame( 1015): Set to : 0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1015): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1015): *FMB* installDecor flags : 25362712
W/libprocessgroup( 1015): failed to open /acct/uid_10104/pid_5234/cgroup.procs: No such file or directory
E/Zygote  ( 5969): MountEmulatedStorage()
I/libpersona( 5969): KNOX_SDCARD checking this for 10155
E/Zygote  ( 5969): v2
I/libpersona( 5969): KNOX_SDCARD not a persona
I/SELinux ( 5969): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5969): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5969 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1015): Focused application set to: xxxx
D/InputDispatcher( 1015): Focus left window: 1476
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
E/SELinux ( 5969): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/PhoneWindow( 1015): *FMB* isFloatingMenuEnabled return false
D/AndroidRuntime( 5885): Shutting down VM
I/SurfaceFlinger(  256): id=12 createSurf (1x1),1 flag=404, uhalitest
I/SA      ( 5943): [DM] init START
I/ActivityManager( 1015): Killing 5420:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
I/SA      ( 5943): [DM] This device is not a Vodafone
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
D/TimaKeyStoreProvider( 5969): TimaSignature is unavailable
D/ActivityThread( 5969): Added TimaKeyStore provider
W/ResourceType( 5943): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 5943): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 5943): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 5943): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 5943): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 5943): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 5943): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
V/WindowManager( 1015): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/ActivityManager( 1015): Display changed displayId=0
W/ResourceType( 5943): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 5943): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 5943): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
E/JavaBinder( 1015): !!! FAILED BINDER TRANSACTION !!!
W/ResourceType( 5943): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 5943): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
D/StatusBarManagerService( 1015): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
W/ResourceType( 5943): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 5943): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 5943): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 5943): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 5943): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 5943): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 5943): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 5943): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 5943): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 5943): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 5943): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 5943): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 5943): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
W/DisplayManagerService( 1015): Failed to notify process 5420 that displays changed, assuming it died.
W/DisplayManagerService( 1015): android.os.TransactionTooLargeException
W/DisplayManagerService( 1015): 	at android.os.BinderProxy.transactNative(Native Method)
W/DisplayManagerService( 1015): 	at android.os.BinderProxy.transact(Binder.java:511)
W/DisplayManagerService( 1015): 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
W/DisplayManagerService( 1015): 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1372)
W/DisplayManagerService( 1015): 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1170)
W/DisplayManagerService( 1015): 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:146)
W/DisplayManagerService( 1015): 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1305)
W/DisplayManagerService( 1015): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DisplayManagerService( 1015): 	at android.os.Looper.loop(Looper.java:145)
W/DisplayManagerService( 1015): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DisplayManagerService( 1015): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
E/SMD     (  286): DCD OFF
D/PersonaManager( 1015): isKioskContainerExistOnDevice
I/SA      ( 5943): [SCU] isHaveSA() - false
I/SA      ( 5943): support phone number id : false
I/SA      ( 5943): [DM] Supports Ref Jpn : true
I/SA      ( 5943): [DM] init END
I/SA      ( 5943): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 5943): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10155 extra.user_handle.:0 ]
I/ActivityManager( 1015): Killing 5451:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
I/ServiceManager(  313): Waiting for service AtCmdFwd...
I/Icing   ( 2027): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
I/SurfaceFlinger(  256): id=8 Removed Mauncher (5/9)
I/SurfaceFlinger(  256): id=8 Removed Mauncher (-2/9)
V/ActivityThread( 1476): updateVisibility : ActivityRecord{25eb9f34 token=android.os.BinderProxy@22c5037c {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1476): onTrimMemory. Level: 20
D/WindowOrientationListener( 1015):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
W/art     ( 5885): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/WebViewFactory( 5969): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,W/libprocessgroup( 1015): failed to open /acct/uid_10069/pid_5420/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5451/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5991): MountEmulatedStorage()
E/Zygote  ( 5991): v2
I/libpersona( 5991): KNOX_SDCARD checking this for 10100
I/libpersona( 5991): KNOX_SDCARD not a persona
,I/SELinux ( 5991): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5991): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5991): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=5991 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,W/art     ( 2027): Verification of void com.google.android.gms.games.broker.PlayerAgent.<init>(com.google.android.gms.games.broker.Lockable, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer) took 108.753ms
I/ActivityManager( 1015): Killing 5467:com.google.android.apps.plus/u0a120 (adj 15): empty #31
D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
,W/GAV2    ( 5737): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/LibraryLoader( 5969): Time to load native libraries: 2 ms (timestamps 9891-9893)
I/LibraryLoader( 5969): Expected native library version number "",actual native library version number ""
D/TimaKeyStoreProvider( 5991): TimaSignature is unavailable
D/ActivityThread( 5991): Added TimaKeyStore provider
,I/Icing   ( 2027): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,V/WebViewChromiumFactoryProvider( 5969): Binding Chromium to main looper Looper (main, tid 1) {a06fc5e}
,I/LibraryLoader( 5969): Expected native library version number "",actual native library version number ""
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,I/chromium( 5969): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PackageIntentReceiver( 5991): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 5991): Not GearManger package! 
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6014): MountEmulatedStorage()
,E/Zygote  ( 6014): v2
I/libpersona( 6014): KNOX_SDCARD checking this for 1000
I/libpersona( 6014): KNOX_SDCARD not a persona
I/SELinux ( 6014): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6014): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6014): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/BrowserStartupController( 5969): Initializing chromium process, singleProcess=true
,W/art     ( 5969): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5969): ApplicationContext is null in ApplicationStatus
I/ActivityManager( 1015): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6014 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,W/libprocessgroup( 1015): failed to open /acct/uid_10120/pid_5467/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1819): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider( 6014): TimaSignature is unavailable
,D/ActivityThread( 6014): Added TimaKeyStore provider
,W/chromium( 5969): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
I/chromium( 5969): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,I/chromium( 5969): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,I/Adreno-EGL( 5969): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 5969): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 5969): Build Date: 04/06/15 Mon
I/Adreno-EGL( 5969): Local Branch: 
I/Adreno-EGL( 5969): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 5969): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 5969):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6039): MountEmulatedStorage()
E/Zygote  ( 6039): v2
I/libpersona( 6039): KNOX_SDCARD checking this for 1000
I/libpersona( 6039): KNOX_SDCARD not a persona
,I/SELinux ( 6039): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6039): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6039): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6039 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 5100:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,W/AccountFeatureHelper( 5737): Write apps_features disabled false
,W/GAV2    ( 5737): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/art     (  305): Explicit concurrent mark sweep GC freed 8708(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 653us total 22.399ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 17.918ms
,D/TimaKeyStoreProvider( 6039): TimaSignature is unavailable
D/ActivityThread( 6039): Added TimaKeyStore provider
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 18.030ms
,W/ActivityManager( 1015): Activity pause timeout for ActivityRecord{3789297b u0 com.test.thalitest/.MainActivity t7}
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/AcmsPackageEventListener( 6039): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 6039): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,E/Zygote  ( 6063): MountEmulatedStorage()
,E/Zygote  ( 6063): v2
I/libpersona( 6063): KNOX_SDCARD checking this for 10120
I/libpersona( 6063): KNOX_SDCARD not a persona
,I/SELinux ( 6063): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1015): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6063 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager( 1015): Killing 4953:com.sec.android.app.music:service/u0a40 (adj 15): empty #31,
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,I/SELinux ( 6063): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6063): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/TimaKeyStoreProvider( 6063): TimaSignature is unavailable
,D/ActivityThread( 6063): Added TimaKeyStore provider
,I/wpa_supplicant( 1986): nl80211: Received scan results (6 BSSes)
,D/WifiP2pService( 1015): InactiveState{ what=147461 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=147461 }
D/WifiP2pService( 1015): DefaultState{ what=147461 }
,D/AcmsService( 6039): Enter Oncreate
,D/AcmsServiceMonitor( 6039): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 6039): creating AcmsCore
,D/AcmsCore( 6039): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6039): AcmsCore
,D/AcmsCore( 6039): init
D/AcmsCore( 6039): Looper handler is not null
D/AcmsCore( 6039): Post to AcmsCoreHandler
,D/AcmsServiceMonitor( 6039): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6039): Incrementing - Counter value: 1
D/AcmsCore( 6039): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 6039): onStartCommand
D/AcmsService( 6039): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 6039): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6039): Incrementing - Counter value: 2
D/AcmsService( 6039): Incremented Counter Value : onStartCommand
,W/chromium( 5969): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,D/AcmsCertificateMngr( 6039): AcmsCertificateMngr
D/ActivityManager( 1015): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,D/ActivityThread( 6039): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsRevocationMngr( 6039): AcmsRevocationMngr
W/ResourcesManager( 6063): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/qtaguid ( 5489): Tagging socket 44 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5489, getuid(): 10028
,D/ChimeraCfgMgr( 2027): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2027): Module APK com.google.android.play.games already loaded
,D/AcmsService( 6039): Inside handle Intent
,D/AcmsService( 6039): App added - package name: com.test.thalitest
,D/AcmsCore( 6039): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6039): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6039): Incrementing - Counter value: 3
,D/AcmsCore( 6039): Incremented Counter Value: postToAcmsCoreHandler =>2
,D/AcmsService( 6039): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 6039): Decrementing - Counter value: 2
,W/art     ( 5969): Attempt to remove local handle scope entry from IRT, ignoring
,W/libprocessgroup( 1015): failed to open /acct/uid_10150/pid_5100/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10040/pid_4953/cgroup.procs: No such file or directory
,I/qtaguid ( 5489): Tagging socket 48 with tag e8d195d100000000{3906049489,0} for uid -1, pid: 5489, getuid(): 10028
,W/AwContents( 5969): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 5969): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 5969): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 5969): CordovaWebView is running on device made by: samsung
,W/art     ( 5969): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5969): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 5969): Render dirty regions requested: true
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
,V/ActivityThread( 5969): updateVisibility : ActivityRecord{733d81a token=android.os.BinderProxy@16e2e93c {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 5969): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,D/PhoneWindow( 5969): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  256): id=13 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1015): Focus entered window: 5969
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 5969): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 5969): Initialized EGL, version 1.4
D/OpenGLRenderer( 5969): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 5969): Enabling debug mode 0
,I/Mms/MmsApp( 5646):  start initViewCache mms
D/Mms/ComposeMessageFragment( 5646): [start]    fillCache consume time = 1933.091926
D/Mms/ComposeMessageFragment( 5646): fillCache, easy = false
,D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,I/ActivityManager( 1015): Displayed Component not be shown by security: +935ms (total +1s42ms)
,W/ActivityManager( 1015): mDVFSHelper.release()
,I/Timeline( 1015): Timeline: Activity_windows_visible id: ActivityRecord{3789297b u0 com.test.thalitest/.MainActivity t7} time:80587
,I/SamsungIME( 1784): getCurrentCandidateView
,I/SurfaceFlinger(  256): id=12 Removed uhalitest (7/9)
,I/SurfaceFlinger(  256): id=12 Removed uhalitest (-2/9)
,W/IInputConnectionWrapper( 5969): showStatusIcon on inactive InputConnection
,I/Timeline( 5969): Timeline: Activity_idle id: android.os.BinderProxy@16e2e93c time:80602
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus,
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/AbsListView( 5646): Get MotionRecognitionManager
,D/MotionRecognitionService( 1015):  ssp status : false
,D/Mms/ComposeMessageFragment( 5646): [end]    fillCache consume time = 164.697031
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/splitIntent( 1015): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,W/BindingManager( 5969): Cannot call determinedVisibility() - never saw a connection for the pid: 5969
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6102): MountEmulatedStorage(),
E/Zygote  ( 6102): v2
I/libpersona( 6102): KNOX_SDCARD checking this for 10142
I/libpersona( 6102): KNOX_SDCARD not a persona
I/SELinux ( 6102): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6102): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1015): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6102 uid=10142 gids={50142, 9997, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6102): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 4453:com.google.android.music:main/u0a111 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6102): TimaSignature is unavailable
,D/ActivityThread( 6102): Added TimaKeyStore provider
,D/SamsungIME( 1784): Dismiss ExpandCandiate
,V/TaskCloserActivity( 6102): TaskCloserActivity enter()
,V/TaskCloserActivity( 6102): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,I/ActivityManager( 1015): Killing 4791:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1300): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1300): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1300): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1300): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1300): [MSC_Daemon]>>> ====================================================================================================================
,I/BatteryStatsDumper( 1015): Writing to database completed
,D/daemonapp( 1300): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1300): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1300): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 1300): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1452720840000
,D/daemonapp( 1300): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1452699329806
D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/JsMessageQueue( 5969): Set native->JS mode to OnlineEventsBridgeMode
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1300): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1300): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,I/ActivityManager( 1015): Killing 5261:com.android.calendar/u0a135 (adj 15): empty #31
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/Mms/BubbleViewCache( 5646): fillCache bubble = 1
E/daemonapp( 1300): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1725): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1725): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1725): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1725): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1725): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,W/libprocessgroup( 1015): failed to open /acct/uid_10111/pid_4453/cgroup.procs: No such file or directory
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1725): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1725): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1725): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1725): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,W/libprocessgroup( 1015): failed to open /acct/uid_10134/pid_4791/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10135/pid_5261/cgroup.procs: No such file or directory
,D/accuweather( 1725): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
I/qtaguid ( 5489): Untagging socket 44
,I/System.out( 5489): Thread-952 calls detatch()
,D/accuweather( 1725): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/jxcore_app_log( 5969): JniHelper::setJavaVM(0xb79a8450), pthread_self() = -1209025832
,D/JX-Cordova( 5969): jxcore cordova android initializing
,I/SamsungIME( 1784): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1784): getDebugLevel  : 0x4f4c
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,I/SamsungIME( 1784): KeybaordView init() : load resources
,V/GLSActivity( 1819): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 5489): Thread-953(ApacheHTTPLog):isSBSettingEnabled false
I/SamsungIME( 1784): getCurrentKeyboard
I/SamsungIME( 1784): getTextKeyboard
,I/System.out( 5489): Thread-953(ApacheHTTPLog):isShipBuild true
,I/System.out( 5489): Thread-953(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5489): Thread-953(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/SamsungIME( 1784): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/DBG_POLICYDM( 5720): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5720): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5720): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5720): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5720): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/qtaguid ( 5489): Untagging socket 44
,I/qtaguid ( 5489): Failed write_ctrl(u 44) res=-1 errno=22
,I/DBG_POLICYDM( 5720): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/qtaguid ( 5489): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5489): untagSocket(44) failed with errno -22
I/System.out( 5489): Thread-953 calls detatch()
,D/Finsky  ( 5489): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/DBG_POLICYDM( 5720): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1819): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6124): MountEmulatedStorage(),
E/Zygote  ( 6124): v2,
,I/ActivityManager( 1015): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6124 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/libpersona( 6124): KNOX_SDCARD checking this for 10012
I/libpersona( 6124): KNOX_SDCARD not a persona
,I/SELinux ( 6124): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6124): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6124): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6124): TimaSignature is unavailable
,D/ActivityThread( 6124): Added TimaKeyStore provider
,W/ResourcesManager( 6124): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6124): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/System.out( 5489): Thread-952(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5489): Thread-952(ApacheHTTPLog):isShipBuild true
I/System.out( 5489): Thread-952(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5489): Thread-952(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/MultiDex( 6124): VM with version 2.1.0 has multidex support
I/MultiDex( 6124): install
I/MultiDex( 6124): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6124): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6124): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6124): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3602c546: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6124): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1015): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1015): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1015): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1015): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 6124): Reading stored module config
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1819): callingUid 10012, callindPid: 1819
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/LocationInitializer( 2027): Restart initialization of location
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 6124): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1819): [252] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1819): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1819): No location to return for getLastLocation()
,W/FusedLocationProvider( 1819): location=null
,I/qtaguid ( 5489): Untagging socket 44
,I/qtaguid ( 5489): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5489): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5489): untagSocket(44) failed with errno -22
I/System.out( 5489): Thread-952 calls detatch()
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1819): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/NativeLibraryUtils( 6124): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 6124): Connecting to CarCallService...
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.CarCallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SamsungIME( 1784): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/art     ( 6124): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6124): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 6124): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6124): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6124): Creating a new PhoneAdapter instance
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6124): setListener: com.google.android.gms.car.dn@224444cd
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_bind
D/CAR.TEL.PhoneAdapter( 6124): Returning an existing PhoneAdapter instance.
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallServiceImpl; callingUser = 0; userId(target) = 0
D/CAR.TEL.Service( 6124): Starting CarCallService with initial phone null
W/ActivityManager( 1015): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 46862(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 2.734ms total 178.617ms
,D/CAR.SERVICE( 6124): Package validated; name: com.android.vending
,V/Finsky  ( 5489): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,W/jxcore-log( 5969): Initializing JXcore engine
,W/jxcore-log( 5969): JXcore engine is ready
,W/jxcore-log( 5969): Starting JXcore engine
,E/audit   ( 1911): type=1400 msg=audit(1452699331.387:205): avc:  denied  { ioctl } for  pid=5969 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1911):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1911): type=1300 msg=audit(1452699331.387:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=beee3d58 items=0 ppid=305 ppcomm=main pid=5969 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1911): type=1320 msg=audit(1452699331.387:205): 
,W/jxcore-log( 5969): Platform android
W/jxcore-log( 5969): 
W/jxcore-log( 5969): Process ARCH arm
W/jxcore-log( 5969): 
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,V/AlarmManager( 1015): waitForAlarm result :4
,D/KeyguardViewMediator( 1175): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1175): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1175): *** Keyguard wallpaper service already unbounded
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1819): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/System.out( 5489): Thread-953(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 5489): Thread-953(ApacheHTTPLog):isShipBuild true
I/System.out( 5489): Thread-953(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5489): Thread-953(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 5489): Untagging socket 44
,I/qtaguid ( 5489): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid ( 5489): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger( 5489): untagSocket(44) failed with errno -22
I/System.out( 5489): Thread-953 calls detatch()
,W/ResourcesManager( 5489): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5489): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/jxcore-log( 5969): JXcore Cordova bridge is ready!
I/jxcore-log( 5969): 
,W/jxcore-log( 5969): JXcore engine is started
,W/ResourcesManager( 5489): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/chromium( 5969): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Choreographer( 5969): Skipped 138 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 5969): Toggling radios to true
I/jxcore-log( 5969): 
,D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/BluetoothAdapter( 5969): enable()
,D/BluetoothAdapter( 5969): enable(): BT is already enabled..!
,D/SecContentProvider( 1015): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1015): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1015): mCursor = null
,D/WifiService( 1015): setWifiEnabled: true pid=5969, uid=10155
W/ActivityManager( 1015): Permission Denial: getCurrentUser() from pid=5969, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1015): Failed getting userId using ActivityManagerNative
W/WifiService( 1015): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5969, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1015): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24778)
W/WifiService( 1015): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1015): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1015): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1015): 	at android.os.Binder.execTransact(Binder.java:461)
D/SettingsProvider( 1015): name = wifi_on
,I/WifiService( 1015): disconnect: pid=5969, uid=10155
,I/wpa_supplicant( 1986): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,D/Finsky  ( 5489): [1] DailyHygiene.access$600: Logging device features
,I/jxcore-log( 5969): Radios toggled
I/jxcore-log( 5969): 
,I/jxcore-log( 5969): My device name is: samsung-SM-A500FU
I/jxcore-log( 5969): 
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/wpa_supplicant( 1986): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 1986): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1986): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 1986): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1986): wlan0: State: DISCONNECTED -> DISCONNECTED
E/wpa_supplicant( 1986): Cmd 35605 not handled
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1015): InitialState.processMessage what=4
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,E/WifiStateMachine( 1015): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1986): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1986): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1986): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1986): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1986): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 1986): First Scan Start
,I/wpa_supplicant( 1986): Scan requested (ret=0) - scan timeout 30 seconds
,E/Tethering( 1015): No numeric data
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1015): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1015): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1015): clearTetheredNotification()
,V/NetworkStats( 1015): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
,D/HotspotTile( 1175): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/HotspotTile( 1175): updateTetherState():false, false
,V/NetworkStats( 1015): performPollLocked() took 3ms
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
E/WifiConfigStore( 1015): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,E/WifiNative-wlan0( 1015): do suspend true
,D/WifiP2pService( 1015): InactiveState{ what=143375 }
,D/CommandListener(  276): Clearing all IP addresses on wlan0
,I/PowerManagerService( 1015): [PWL] Off : 5s ago
,I/PowerManagerService( 1015): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService( 1015): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1015): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1015, ws=WorkSource{10028}) (elapsedTime=53)
,V/NativeCrypto( 1819): Read error: ssl=0xb7f5d350: I/O error during system call, Connection timed out
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
,E/ConnectivityService( 1015): updateNetworkInfo()
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1015): updateNetworkInfo()
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/NativeCrypto( 1819): SSL shutdown failed: ssl=0xb7f5d350: I/O error during system call, Broken pipe
,D/ConnectivityService( 1015): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler },
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Forcing reevaluation
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>,
,E/WifiStateMachine( 1015): Start Disconnecting Watchdog 1,
I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false,
I/qtaguid ( 1015): Tagging socket 361 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1015, getuid(): 1000
,I/wpa_supplicant( 1986): wlan0: Setting scan request: 0 sec 0 usec
,I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
I/qtaguid ( 1015): Untagging socket 361
I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false
W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14952 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/WifiNative-wlan0( 1015): do suspend true
,D/ActivityManager( 1015): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/WifiP2pService( 1015): InactiveState{ what=143375 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/DeviceConnectionService( 1819): client connected with version: 8296000,
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/EnterpriseController(  276): uids 1000
,D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 0 for uid 1000
,D/CommandListener(  276): Clearing all IP addresses on wlan0
,D/ConnectivityService( 1015): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
,D/ConnectivityService( 1015): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Validated
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524292
D/EntConnectivity( 1015): Not allowed due to - mEnabled false - primarySimSlot false
,D/ConnectivityService( 1015): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/CSLegacyTypeTracker( 1015): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityManager.CallbackHandler( 2027): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1015): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/WIFI_P2P( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/TelephonyNetworkFactory( 1449): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,D/TelephonyNetworkFactory( 1449): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3492): Starting #8
,I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
,I/Hs20UtilService( 3492): Message received 5007
,D/WifiNetworkAgent( 1015): NetworkAgent: NetworkAgent channel lost
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NearbySettings( 1339): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1339): DMSUtil.isNetworkConnected - flag-null, state-null
,D/Finsky  ( 5489): [974] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/WIFI    ( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,D/Finsky  ( 5489): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5489): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/ConnectivityService( 1015): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): doQuit - quitNow()
,I/NearbySettings( 1339): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/Tethering( 1015): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1015): MasterInitialState.processMessage what=3
,D/EntConnectivity( 1015): Not allowed due to - mEnabled false - primarySimSlot false
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): updateIfacesLocked()
V/NetworkStats( 1015): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
,V/NetworkStats( 1015): performPollLocked() took 3ms
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,I/NearbySettings( 1339): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1339): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1339): MountReceiver.onReceive - Set preference state off
,D/StatusBar.NetworkController( 1175): EthernetConnected: false
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1175): updateDataNetType()
D/StatusBar.NetworkController( 1175): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1175): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,V/NearbySettings( 1339): MountReceiver.mPrefHandler - 7002
,D/StatusBar.NetworkController( 1175): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,V/GLSActivity( 1819): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/AcmsKeyStoreHelper( 6039):  getKeyStoreForApplication Enter,
D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/AcmsKeyStoreHelper( 6039): Key Store exist
I/AcmsKeyStoreHelper( 6039): Hence loading the keystore file
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6167): MountEmulatedStorage()
,E/Zygote  ( 6167): v2
I/libpersona( 6167): KNOX_SDCARD checking this for 10104
I/libpersona( 6167): KNOX_SDCARD not a persona
,I/SELinux ( 6167): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6167 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/SELinux ( 6167): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6167): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6167): TimaSignature is unavailable
,D/ActivityThread( 6167): Added TimaKeyStore provider
,I/System.out( 5489): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 5489): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 5489): (HTTPLog)-Static: isShipBuild true
I/System.out( 5489): (HTTPLog)-Thread-963-868097268: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 5489): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  276): uids 10028
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 0 for uid 10028
,D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/ResourcesManager( 6167): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/AcmsKeyStoreHelper( 6039):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 6039): getKeyStoreForApplication success 
D/AcmsCore( 6039): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 6039): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6039): Decrementing - Counter value: 1
D/AcmsCore( 6039): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 6039): This is NOT a valid MirrorLink app
D/AcmsCore( 6039): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 6039): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6039): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 6039): Counter value is 0: Stopping ACMS service
,D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
,D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
,D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
,D/AcmsServiceMonitor( 6039): getSvcCounter - Counter value: 0
D/AcmsService( 6039): Enter onDestroy
I/AcmsService( 6039): cleanUp(): inside service clean up
D/AcmsCore( 6039): AcmsCore: inside DeInit
D/AcmsCore( 6039): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 6039): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 6039): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 6039): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 6039): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 6039): getSvcCounter - Counter value: 0
D/AcmsService( 6039): killing acms process
I/Process ( 6039): Sending signal. PID: 6039 SIG: 9
,D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
,I/ActivityManager( 1015): Killing 5339:com.samsung.aasaservice/1000 (adj 15): empty #31
,I/ActivityManager( 1015): Killing 5121:com.google.android.gm/u0a101 (adj 15): empty #32
D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
,D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
,D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
,D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE,
,D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
,D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
,D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
,D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
,D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
,D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
,D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3,
,I/ActivityManager( 1015): Process ACMS.Process (pid 6039)(adj 0) has died(44,1142)
,W/libprocessgroup( 1015): failed to open /acct/uid_10101/pid_5121/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5339/cgroup.procs: No such file or directory
,I/Babel   ( 6167): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6167): MmsConfig.loadMmsSettings
I/Babel   ( 6167): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 6167): MmsConfig.loadFromDatabase
,E/Babel   ( 6167): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 6167): MmsConfig.loadFromResources
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
E/Babel   ( 6167): canonicalizeMccMnc: invalid mccmnc nullnull
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
I/Babel   ( 6167): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,W/Settings( 6167): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_StickerModule( 6167): App launched.
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1339): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1339): DMSUtil.isNetworkConnected - flag-null, state-null
,I/Hs20UtilService( 3492): Starting #9
I/NearbySettings( 1339): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/Hs20UtilService( 3492): Message received 5007
,I/NearbySettings( 1339): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1339): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1339): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1339): MountReceiver.mPrefHandler - 7002
,W/art     ( 6167): Suspending all threads took: 7.541ms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/QCamera2Factory(  281): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  281): getCameraInfo: X
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/QCamera2Factory(  281): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  281): getCameraInfo: X
,D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6167): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6167): Unsupported mime audio/evrc
,D/GpsLocationProvider( 1015): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3072): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/DBG_DM  ( 3072): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,W/AudioCapabilities( 6167): Unsupported mime audio/qcelp
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/ApplicationPolicy( 1015): updateDataUsageMap
,W/AudioCapabilities( 6167): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6167): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 6167): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6167): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6167): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6167): Unsupported mime audio/evrc
,W/VideoCapabilities( 6167): Unsupported mime video/wvc1
,W/VideoCapabilities( 6167): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6167): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6167): Unsupported mime video/wvc1
,W/VideoCapabilities( 6167): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6167): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6167): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6167): Unsupported mime video/mp43
,W/VideoCapabilities( 6167): Unsupported mime video/sorenson
,W/VideoCapabilities( 6167): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6167): Unsupported profile 4 for video/mp4v-es
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/PCWCLIENTTRACE_PushUtil( 5672): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5672): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5672): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5672): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1015): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,I/splitIntent( 1015): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5672): noConnectivity : true
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6213 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6213): MountEmulatedStorage()
E/Zygote  ( 6213): v2
I/libpersona( 6213): KNOX_SDCARD checking this for 10111
I/libpersona( 6213): KNOX_SDCARD not a persona
,I/SELinux ( 6213): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,I/SELinux ( 6213): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6213): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/wpa_supplicant( 1986): nl80211: Received scan results (7 BSSes)
I/wpa_supplicant( 1986): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 1986): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 1986): Trying to associate with  'G700'
I/wpa_supplicant( 1986): Re-associate with C0.AA.48
I/wpa_supplicant( 1986): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 1986): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,D/WifiMonitor( 1015): didn't find BSSID Trying to associate with SSID 'NG700'
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6213): TimaSignature is unavailable
,D/ActivityThread( 6213): Added TimaKeyStore provider
,E/Zygote  ( 6225): MountEmulatedStorage()
E/Zygote  ( 6225): v2
I/libpersona( 6225): KNOX_SDCARD checking this for 10009
I/libpersona( 6225): KNOX_SDCARD not a persona
,I/SELinux ( 6225): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6225): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1015): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6225 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6225): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1015): mCursor = null
,D/accuweather( 1725): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6243): MountEmulatedStorage(),
E/Zygote  ( 6243): v2
I/libpersona( 6243): KNOX_SDCARD checking this for 10145
,I/SELinux ( 6243): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6243): KNOX_SDCARD not a persona
,I/SELinux ( 6243): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 6243): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6243 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6225): TimaSignature is unavailable
,D/ActivityThread( 6225): Added TimaKeyStore provider
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 1725): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1725): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1725): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1725): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/TimaKeyStoreProvider( 6243): TimaSignature is unavailable
,D/ActivityThread( 6243): Added TimaKeyStore provider
,D/accuweather( 1725): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,E/wpa_supplicant( 1986): Cmd 35605 not handled
,I/wpa_supplicant( 1986): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 1986): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 1986): Associated with C0.AA.48
I/wpa_supplicant( 1986): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1986): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 1986): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false,
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false,
D/Tethering( 1015): interfaceLinkStateChanged wlan0, false
D/Tethering( 1015): interfaceStatusChanged wlan0, false
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, false,
D/accuweather( 1725): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/Tethering( 1015): interfaceLinkStateChanged wlan0, true
D/Tethering( 1015): interfaceStatusChanged wlan0, true
,I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, true
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,I/wpa_supplicant( 1986): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
E/Tethering( 1015): No numeric data
I/wpa_supplicant( 1986): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/Tethering( 1015): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1015): clearTetheredNotification()
,I/wpa_supplicant( 1986): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 1986): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 1986): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP],
I/wpa_supplicant( 1986): wlan0: State: GROUP_HANDSHAKE -> COMPLETED,
,I/wpa_supplicant( 1986): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
I/wpa_supplicant( 1986): Blacklist: Clear (temp) 
I/wpa_supplicant( 1986): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 1015): interfaceLinkStateChanged wlan0, true
D/Tethering( 1015): interfaceStatusChanged wlan0, true
D/HotspotTile( 1175): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1175): updateTetherState():false, false
I/Nat464Xlat( 1015): interfaceLinkStateChanged wlan0, true
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
V/NetworkStats( 1015): performPollLocked() took 6ms
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6243): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6243): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6243): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6243): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6243): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 1015): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6261 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
I/libpersona( 6261): KNOX_SDCARD checking this for 10081
D/SecContentProvider2( 1015): mCursor = null
I/libpersona( 6261): KNOX_SDCARD not a persona
E/Zygote  ( 6261): MountEmulatedStorage()
E/Zygote  ( 6261): v2
I/SELinux ( 6261): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6261): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6261): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/WifiNative-wlan0( 1015): callSECApiVoid - ID [50]
E/WifiConfigStore( 1015): setLastSelectedConfiguration -1
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1015): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1015): hsengiv:checkWhatTypeOfNetwork and the value is false
D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1015): updateNetworkInfo()
E/WifiConfigStore( 1015): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/TimaKeyStoreProvider( 6261): TimaSignature is unavailable
,D/ActivityThread( 6261): Added TimaKeyStore provider
,E/WifiConfigStore( 1015): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  276): Setting iface cfg
,E/WifiStateMachine( 1015): Start Dhcp Watchdog 2
D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1015): mCursor = null
,E/WifiNative-wlan0( 1015): do suspend false
,D/WifiP2pService( 1015): InactiveState{ what=143375 }
,D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
,I/MusicStore( 6213): Database version: 108
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1015): Killing 4972:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,I/KLMS-2.5.183: ( 3536): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Jan 13 16:35:33 GMT+01:00 2016
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6285): MountEmulatedStorage()
E/Zygote  ( 6285): v2
I/libpersona( 6285): KNOX_SDCARD checking this for 10113
I/libpersona( 6285): KNOX_SDCARD not a persona
,I/SELinux ( 6285): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6285): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6285): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6285 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 4703:com.samsung.android.sm/1000 (adj 15): empty #31
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3536): KLMSAbstractReciever(): onReceive().END.
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3536): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3536): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3536): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/Zygote  ( 6305): MountEmulatedStorage()
I/libpersona( 6305): KNOX_SDCARD checking this for 10034
E/Zygote  ( 6305): v2
I/libpersona( 6305): KNOX_SDCARD not a persona
,I/SELinux ( 6305): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/KLMS-2.5.183: ( 3536): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/SELinux ( 6305): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6305): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3536): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/ActivityManager( 1015): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6305 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6285): TimaSignature is unavailable
,D/ActivityThread( 6285): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3536): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3536): StateImplV2(): networkChangeListener().END
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,I/KLMS-2.5.183: ( 3536): KLMSIntentService(): onDestroy()
,D/TimaKeyStoreProvider( 6305): TimaSignature is unavailable
,D/ActivityThread( 6305): Added TimaKeyStore provider
,W/libprocessgroup( 1015): failed to open /acct/uid_10044/pid_4972/cgroup.procs: No such file or directory,
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_4703/cgroup.procs: No such file or directory
,E/dhcpcd  ( 6321): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 6321): version 5.5.6 starting
,E/dhcpcd  ( 6321): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,W/ResourcesManager( 6213): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
W/ResourcesManager( 6213): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/SO_AGENT( 6305): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,I/dhcpcd  ( 6321): wlan0: sending IPv6 Router Solicitation,
E/dhcpcd  ( 6321): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6321): if(wlan0) info get Success. (MAC : C0.AA.48),
I/dhcpcd  ( 6321): bssid match
I/dhcpcd  ( 6321): wlan0: rebinding lease of 192.168.1.129
,V/JNIHelp ( 6213): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/BadgeProvider( 5851): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/DBG_POLICYDM( 5720): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 5720): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5720): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5720): [com.policydm.XDMApplication(477/isNetworkChanged)] network not changed.... 
,E/SPPClientService( 5776): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/ActivityManager( 1015): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/BadgeProvider( 5851): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5851): sendNotify, [notify] : null
D/BadgeProvider( 5851): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5851): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5851): update, [UpdateCount] : 1
I/SA      ( 5943): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 5943): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 5943): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,D/Launcher.Model( 1476): reloadBadges entered.
,I/SA      ( 5943): [SLFUCHKMGR] constructor called
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,I/SA      ( 5943): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 5943): [OR] == isSIMCardReady false ==
W/ActivityThread( 6213): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6213): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2c2eef59: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6213): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6213): GMSCore installation verified
,I/SA      ( 5943): [SCU] == networkStateCheck == false
I/SA      ( 5943): [OR] onReceive END
,E/SPPClientService( 5776): [[SystemStateMonitorService]] No Active Internet
V/DownloadManager( 1226): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6338): MountEmulatedStorage()
I/libpersona( 6338): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6338): v2
I/libpersona( 6338): KNOX_SDCARD not a persona
,I/SELinux ( 6338): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6338): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,I/ActivityManager( 1015): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6338 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 6338): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1015): Killing 5637:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,I/art     (  305): Explicit concurrent mark sweep GC freed 8700(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 651us total 22.450ms
,D/TimaKeyStoreProvider( 6338): TimaSignature is unavailable
,I/ConfigStore( 6213): Config Database version: 1
D/ActivityThread( 6338): Added TimaKeyStore provider
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 629us total 18.411ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 16.959ms
,D/SecurityLogAgent( 6338): KnoxConfiguration : Current State = 1
,W/libprocessgroup( 1015): failed to open /acct/uid_10152/pid_5637/cgroup.procs: No such file or directory
,D/SecurityLogAgent( 6338): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6338): StateMachine : Current State = 1
,D/SecurityLogAgent( 6338): StateMachine : Changed Current State = 1
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6213): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/,
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
E/Zygote  ( 6355): MountEmulatedStorage()
E/Zygote  ( 6355): v2
I/libpersona( 6355): KNOX_SDCARD checking this for 10159
I/libpersona( 6355): KNOX_SDCARD not a persona
I/SELinux ( 6355): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6355): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6355 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6355): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,W/ContextImpl( 6213): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,I/ActivityManager( 1015): Killing 5379:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6213): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/TimaKeyStoreProvider( 6355): TimaSignature is unavailable
,D/ActivityThread( 6355): Added TimaKeyStore provider
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1015): Killing 5085:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,I/iu.Environment( 2027): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6285): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
I/iu.UploadsManager( 2027): num queued entries: 0
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
I/iu.UploadsManager( 2027): num updated entries: 0
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/iu.SyncManager( 2027): NEXT; no task
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6285): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/AudioService( 1015): getStreamVolume 3 index 0
,I/MediaRouter( 6213): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6213): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6285): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6285): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/ActivityManager( 1015): Killing 5682:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,I/ActivityManager( 1015): Killing 5698:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6380): MountEmulatedStorage(),
E/Zygote  ( 6380): v2
I/libpersona( 6380): KNOX_SDCARD checking this for 10002
,I/SELinux ( 6380): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/libpersona( 6380): KNOX_SDCARD not a persona
,W/libprocessgroup( 1015): failed to open /acct/uid_10015/pid_5379/cgroup.procs: No such file or directory
,I/SELinux ( 6380): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1015): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6380 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6380): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5085/cgroup.procs: No such file or directory
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6380): TimaSignature is unavailable
,D/ActivityThread( 6380): Added TimaKeyStore provider
,W/libprocessgroup( 1015): failed to open /acct/uid_10156/pid_5682/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5698/cgroup.procs: No such file or directory
,W/ResourcesManager( 6213): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6213): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/GHttpClientFactory( 6213): Using the GMSCore's GoogleHttpClient
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/SMD     (  286): DCD OFF
,I/ActivityManager( 1015): Killing 5402:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6412): MountEmulatedStorage(),
I/libpersona( 6412): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6412): v2
I/libpersona( 6412): KNOX_SDCARD not a persona
,I/SELinux ( 6412): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6412 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6412): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6412): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/WebViewFactory( 6285): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,D/TimaKeyStoreProvider( 6412): TimaSignature is unavailable
,D/ActivityThread( 6412): Added TimaKeyStore provider
,I/LibraryLoader( 6285): Time to load native libraries: 2 ms (timestamps 5703-5705)
,I/LibraryLoader( 6285): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6285): Binding Chromium to main looper Looper (main, tid 1) {21ad0bf6}
,I/LibraryLoader( 6285): Expected native library version number "",actual native library version number ""
,I/chromium( 6285): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,W/libprocessgroup( 1015): failed to open /acct/uid_10032/pid_5402/cgroup.procs: No such file or directory
,I/BrowserStartupController( 6285): Initializing chromium process, singleProcess=true
,W/art     ( 6285): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 6285): ApplicationContext is null in ApplicationStatus
,I/DIAGMON_AGENT( 6412): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/chromium( 6285): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 6285): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,I/chromium( 6285): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,I/Adreno-EGL( 6285): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6285): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6285): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6285): Local Branch: 
I/Adreno-EGL( 6285): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6285): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6285):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/AudioManagerAndroid( 6285): Requires BLUETOOTH permission
I/NSApplication( 6285): Starting up...
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/DIAGMON_AGENT( 6412): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6412): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6412): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6412): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6412): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6412): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,I/ActivityManager( 1015): Killing 5435:com.sec.knox.bridge/1000 (adj 15): empty #31
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6446): MountEmulatedStorage()
,E/Zygote  ( 6446): v2
I/libpersona( 6446): KNOX_SDCARD checking this for 10125
I/libpersona( 6446): KNOX_SDCARD not a persona
,I/SELinux ( 6446): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6446 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
I/SELinux ( 6446): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1015): Killing 5646:com.android.mms/u0a46 (adj 15): empty #31
,E/SELinux ( 6446): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6446): TimaSignature is unavailable
,D/ActivityThread( 6446): Added TimaKeyStore provider,
,W/ResourcesManager( 6446): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6446): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6446): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6446): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6446): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6446): PeriphStartReceiver.onReceive - no need to start
,I/splitIntent( 1015): Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1015): Killing 5866:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3492): Starting #10
,I/Hs20UtilService( 3492): Message received 5007
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/NearbySettings( 1339): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1339): DMSUtil.isNetworkConnected - flag-null, state-null
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4341, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,I/NearbySettings( 1339): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/CountryDetector( 1015): No listener is left
I/NearbySettings( 1339): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1339): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1339): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1339): MountReceiver.mPrefHandler - 7002
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_5435/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to kill pid 5866: No such process
,W/libprocessgroup( 1015): failed to open /acct/uid_10046/pid_5646/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10047/pid_5866/cgroup.procs: No such file or directory
,I/dhcpcd  ( 6321): wlan0: acknowledged 192.168.1.129 from 192.168.1.1
,I/ActivityManager( 1015): Killing 5893:com.wsomacp/u0a25 (adj 15): empty #31
,I/dhcpcd  ( 6321): wlan0: leased 192.168.1.129 for 86400 seconds
,W/libprocessgroup( 1015): failed to open /acct/uid_10025/pid_5893/cgroup.procs: No such file or directory,
,E/WifiNative-wlan0( 1015): do suspend true
,D/WifiP2pService( 1015): InactiveState{ what=143375 },
D/WifiP2pService( 1015): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 1015): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1015): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiNative-wlan0( 1015): callSECApiInt - ID [210]
,E/ConnectivityService( 1015): updateNetworkInfo()
,D/ConnectivityService( 1015): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1015): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1015): updateDnsLinkProperty: enter,
D/WifiWatchdogStateMachine.DnsPinger( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1015): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1015): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 1015): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 1015): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1015): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1015): Setting Dns servers for network 503 to [/192.168.1.1]
D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1015): LTETest block dns file not exists
,D/ConnectivityService( 1015): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/WifiStateMachine( 1015): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,E/ConnectivityService( 1015): updateNetworkInfo(),
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3492): Starting #11
,I/Hs20UtilService( 3492): Message received 5007
,E/ConnectivityService( 1015): updateNetworkInfo()
,D/ConnectivityService( 1015): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1015): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Connected
D/ConnectivityService( 1015): rematching NetworkAgentInfo [WIFI () - 503]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1015): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  276): uids 1000
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 503 for uid 1000
,I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
,D/ConnectivityService( 1015):    accepting network in place of null
,D/TelephonyNetworkFactory( 1449): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1449): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 1015): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1015): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WIFI_P2P( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NearbySettings( 1339): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1339): MountReceiver.onReceive - Keep current state
,I/WifiTrafficPoller( 1015): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1015): mBoosterFLAG : 0
D/WIFI    ( 1015): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
I/WifiTrafficPoller( 1015): current booster mode : FullMode
D/WifiNative-wlan0( 1015): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1015): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService( 1015): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 2027): CM callback handler got msg 524290
,D/Tethering( 1015): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1015): MasterInitialState.processMessage what=3
,V/NetworkStats( 1015): updateIfacesLocked()
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1015): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1015): UpdateStatsForKnox main else ---
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,V/NetworkStats( 1015): performPollLocked() took 4ms
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
V/NetworkStats( 1015): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1175): EthernetConnected: false
,D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1175): updateDataNetType()
D/StatusBar.NetworkController( 1175): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1175): updateLTEICONDataNetType:0
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
D/NtpTrustedTime( 1015): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1175): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1339): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 3492): Starting #12
,I/Hs20UtilService( 3492): Message received 5007
,V/NearbySettings( 1339): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1339): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1339): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1339): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1339): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1339): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1339): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 3492): Starting #13
,D/WifiStateMachine( 1015): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,I/Hs20UtilService( 3492): Message received 5007
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityEnabledState
D/SecContentProvider2( 1015): mCursor = null
,I/System.out( 1015): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravity
D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityXOffset
D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastGravityYOffset
D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1015): mCursor = null
,D/SecContentProvider2( 1015): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1015): mCursor = null
,I/SurfaceFlinger(  256): id=14 createSurf (1x1),1 flag=4, Uoast
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 13 Jan 2016 15:35:36 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452699336112], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452699336090]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1015): Validated
D/ConnectivityService( 1015): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1015): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1015): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1015): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 2027): CM callback handler got msg 524290
,D/PowerManagerService( 1015): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,D/SRIB_DCS( 1175): log_dcs ThreadedRenderer::initialize entered! 
,D/StatusBar.NetworkController( 1175): EthernetConnected: false
,D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 1175): updateDataNetType()
D/StatusBar.NetworkController( 1175): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1175): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1175): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/CAR.SERVICE( 6124): mConnectedToCar = false, abort
,E/ActivityThread( 6124): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@28562815 that was originally bound here
E/ActivityThread( 6124): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@28562815 that was originally bound here
E/ActivityThread( 6124): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6124): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6124): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6124): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6124): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6124): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6124): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6124): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6124): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6124): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6124): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6124): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6124): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6124): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3280)
E/ActivityThread( 6124): 	at android.app.ActivityThread.access$1900(ActivityThread.java:181)
E/ActivityThread( 6124): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1565)
E/ActivityThread( 6124): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6124): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6124): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6124): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6124): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6124): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6124): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityThread( 6124): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3ab3fa64 that was originally bound here
E/ActivityThread( 6124): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3ab3fa64 that was originally bound here
E/ActivityThread( 6124): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 6124): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 6124): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 6124): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 6124): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 6124): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6124): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6124): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6124): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6124): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6124): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6124): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6124): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
E/ActivityThread( 6124): 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
E/ActivityThread( 6124): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
E/ActivityThread( 6124): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6124): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 6124): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/ActivityThread( 6124): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6124): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6124): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 6124): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 68474(3MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 28MB/42MB, paused 2.563ms total 149.775ms
W/ActivityManager( 1015): Unbind failed: could not find connection for android.os.BinderProxy@184b0a50
,D/ConnectivityService( 1015): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1015): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3072): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/NetworkMonitor( 6213): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil( 5672): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5672): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 5672): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5672): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1015): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
I/splitIntent( 1015): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,V/MusicLeanback( 6213): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/accuweather( 1725): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/FOTA_Client( 6225): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/RCPManagerService( 1015): exchangeData() failure , invalid userId
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,I/FOTA_Client( 6225): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 6225): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,D/daemonapp( 1300): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,W/FOTA_Client( 6225): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,D/SecurityLogAgent( 6338): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6338): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6338): StateMachine : Current State = 1
,D/accuweather( 1725): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1725): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/SecurityLogAgent( 6338): StateMachine : Changed Current State = 1
,D/accuweather( 1725): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1725): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/KLMS-2.5.183: ( 3536): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Jan 13 16:35:36 GMT+01:00 2016
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3536): KLMSAbstractReciever(): onReceive().END.
,I/DIAGMON_AGENT( 6412): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6412): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6412): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 6412): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,D/accuweather( 1725): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1725): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KLMS-2.5.183: ( 3536): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3536): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3536): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/WaitQueueForNetworkActivate( 5752): notifyNetworkActivated
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.183: ( 3536): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3536): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.183: ( 3536): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3536): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.183: ( 3536): NetworkChangeOperations(): uploadRequestLog().START 
,W/ContextImpl( 5752): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/KLMS-2.5.183: ( 3536): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.183: ( 3536): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.183: ( 3536): KLMSIntentService(): onDestroy()
,I/DBG_POLICYDM( 5720): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5720): [com.policydm.XDMApplication(469/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 5720): [com.policydm.XDMApplication(471/isNetworkChanged)] network changed.... 
,E/SPPClientService( 5776): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 5943): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 5943): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 5943): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,D/QuickConnect( 6446): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6446): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6446): PeriphStartReceiver.onReceive - no need to start
,I/SA      ( 5943): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 5943): [OR] == isSIMCardReady false ==
,I/SA      ( 5943): [SCU] == networkStateCheck == true
,I/SA      ( 5943): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5943): isChinaCountryCode : false
I/SA      ( 5943): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 5943): [OR] == networkStateCheck true ==
,I/SA      ( 5943): [OR] GetMyCountryZoneTask
I/SA      ( 5943): [OR] onReceive END
,V/DownloadManager( 1226): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/ActivityManager( 1015): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/DBG_POLICYDM( 5720): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5720): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5720): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5720): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5720): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,D/SecContentProvider2( 1015): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1015): mCursor = null
,I/SA      ( 5943): [SRS] prepareGetMyCountryZone
,I/DBG_POLICYDM( 5720): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/SA      ( 5943): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 5943): [SSP] query invoked
I/DBG_POLICYDM( 5720): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5720): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,E/DBG_POLICYDM( 5720): [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,I/SA      ( 5943): [TPMU] GetMccFromDB : null
I/SA      ( 5943): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5943): [TPM] isNoProxy(default) : true
,I/DBG_POLICYDM( 5720): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,E/File    ( 5943): fail readDirectory() errno=2
,D/ActivityManager( 1015): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5752): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5752): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5752): exit::IDLE
D/InitializeManagerStateMachine( 5752): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5752): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5752): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5752): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5752): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5752): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5752): entry::SUCCESS
D/hcjo    ( 5752): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/iu.Environment( 2027): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/hcjo    ( 5752): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5752): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5752): exit::SUCCESS
D/InitializeManagerStateMachine( 5752): entry::IDLE
,I/iu.UploadsManager( 2027): num queued entries: 0
,I/iu.UploadsManager( 2027): num updated entries: 0
,I/iu.SyncManager( 2027): NEXT; no task
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1015): Queue : backgroundsplit_2 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/EnterpriseController(  276): uids 10012
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 503 for uid 10012
,D/ConnectivityService( 1015): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,I/art     ( 1819): Explicit concurrent mark sweep GC freed 35643(2MB) AllocSpace objects, 14(224KB) LOS objects, 40% free, 12MB/21MB, paused 1.263ms total 60.017ms
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,I/SA      ( 5943): [RC New] Execute method=[GET] start
,I/SA      ( 5943): [RC New] Security=[true]
,I/System.out( 5943): Thread-1035(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 5943): Thread-1035(ApacheHTTPLog):isSBSettingEnabled false
,I/System.out( 5943): Thread-1035(ApacheHTTPLog):isShipBuild true
I/System.out( 5943): Thread-1035(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 5943): Thread-1035(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  276): uids 10041
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 503 for uid 10041
,V/AlarmManager( 1015): waitForAlarm result :8
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 340
,D/ConnectivityService( 1015): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1015): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524295
D/ConnectivityService( 1015): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityManager.CallbackHandler( 2027): CM callback handler got msg 524295
D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 2027): CM callback handler got msg 524295
,I/SA      ( 5943): [RC New] [v2liruge] api execute + 656
,I/SA      ( 5943): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5943): AsyncTask #1 calls detatch()
,I/SA      ( 5943): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 5943): [OCP] update openData : PL
,I/SA      ( 5943): [TPMU] getNetworkMcc : 
,I/SA      ( 5943): [SCU] saveMccToPreferece Start
I/SA      ( 5943): [SCU] RegionMCC : 260
I/SA      ( 5943): [SSP] query invoked
,I/SA      ( 5943): [TPMU] GetMccFromDB : null
,I/SA      ( 5943): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5943): [SCU] saveMccToPreferece End
,I/SA      ( 5943): [RC New] executeRequest [v2liruge] end. 719
I/SA      ( 5943): [RC New] Execute end
,I/SA      ( 5943): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5943): [OR] GetMyCountryZoneTask Success
,I/dhcpcd  ( 6321): wlan0: sending IPv6 Router Solicitation
,D/PackageManager( 1015): [MSG] MCS_UNBIND
,I/ActivityManager( 1015): Killing 5911:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,W/libprocessgroup( 1015): failed to open /acct/uid_10053/pid_5911/cgroup.procs: No such file or directory
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/GAV4    ( 6285): Thread[GAThread,5,main]: No campaign data found.
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1819): callingUid 10012, callindPid: 1819
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 6213): Conditions not met for autocaching.
,I/MusicLeanback( 6213): Stop autocaching.
,E/GmsUtils( 6213): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 6213): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,I/SurfaceFlinger(  256): id=14 Removed Uoast (8/9)
,D/PowerManagerService( 1015): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1015) eventTime = 90678
,D/PowerManagerService( 1015): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015 (0x0)
,D/PowerManagerService( 1015): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1015, ws=WorkSource{10054}) (elapsedTime=3470)
,D/ActivityManager( 1015): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1015): waitForAlarm result :8
,E/SMD     (  286): DCD OFF
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5672): mConnectivityHandler : connected,
,W/PCWCLIENTTRACE_AccountUtil( 5672): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5672): [GetString-S]
,I/ReactiveServiceManager( 5672): Supported : 1
,D/QSEECOMAPI: ( 1015): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1015): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1015): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1015): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1015): QSEECom_shutdown_app, app_id = 11
E/terrier ( 1015): handleString: Failed to handle string(-4)
,E/terrier ( 1015): Java_com_android_server_ReactiveService_GetString: error code = [-4]
,D/PCWCLIENTTRACE_SecurePreferencesJNI( 5672): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 5672): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5672): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5672): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5672): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5672): [ensureRegistration] - No Samsung account
,I/ActivityManager( 1015): Waited long enough for: ServiceRecord{111b57cb u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,I/dhcpcd  ( 6321): wlan0: sending IPv6 Router Solicitation
,I/PowerManagerService( 1015): [PWL] Off : 15s ago
,I/jxcore-log( 5969): Test app app.js loaded
I/jxcore-log( 5969): 
,I/chromium( 5969): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/dhcpcd  ( 6321): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 6321): wlan0: no IPv6 Routers available
,V/AlarmManager( 1015): waitForAlarm result :4
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: android, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,I/BackgroundCompactionService( 1015): onStart. jobID=801
,I/BackgroundCompactionService( 1015): onStart done. jobID=801
,I/BackgroundCompactionService( 1015): Execute BGCompaction (type1). (0 times)
,I/BackgroundCompactionService( 1015): compact_memory command done
,E/SMD     (  286): DCD OFF
,D/Finsky  ( 5489): [965] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5489): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/ActivityManager( 1015): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5752): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5752): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5752): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5752): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5752): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5752): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5752): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5752): entry::IDLE
,D/SSRM:n  ( 1015): SIOP:: AP = 320
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF
,E/Watchdog( 1015): !@Sync 3
,I/PowerManagerService( 1015): [PWL] Off : 30s ago
,I/Atfwd_Sendcmd(  313): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  313): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,V/AlarmManager( 1015): waitForAlarm result :4
,D/SSRM:n  ( 1015): SIOP:: AP = 300
,E/SMD     (  286): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,V/AlarmManager( 1015): waitForAlarm result :8
,V/AlarmManager( 1015): waitForAlarm result :4
,V/AlarmManager( 1015): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1015): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1015): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1819): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1819): Vacuum at: now=1452699360727 tag=VacuumService
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeConfigurator( 1819): Scheduling Phenotype for one-off execution 8615 seconds from now (1452699361145)
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1819): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeFlagCommitter( 1819): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1819): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 1015): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ActivityManager( 1015): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1819): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1819): (HTTPLog)-Static: isSBSettingEnabled false
,I/System.out( 1819): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1819): (HTTPLog)-Thread-260-406803423: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 1819): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  276): uids 10012
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 503 for uid 10012
,I/System.out( 1819): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1819): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1819, getuid(): 10012
,I/qtaguid ( 1819): Tagging socket 87 with tag 1000120100000000{268440065,0} for uid -1, pid: 1819, getuid(): 10012
,E/SMD     (  286): DCD OFF
,D/LocationManagerService( 1015): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1819): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1819): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1819, getuid(): 10012
,D/LocationManagerService( 1015): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1819): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1819): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1819, getuid(): 10012
,D/FactoryTest( 5319): Not factory mode
,D/FactoryTest( 5319): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5319): DRIVER_TIME_OUT 60s lapsed,
D/MTPRx   ( 5319): still no open session command from host, so toast
,W/ContextImpl( 5319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 ,
W/ContextImpl( 5319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 5319): Timeline: Activity_launch_request id:com.android.settings time:112998
E/PersonaManagerService( 1015): inState():  stateMachine is null !!
I/PersonaManagerService( 1015): PersonaId don't exist
I/ActivityManager( 1015): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1015): mDVFSHelper.acquire()
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1015): Focused application set to: xxxx
D/InputDispatcher( 1015): Focus left window: 5969
,E/MTPRx   ( 5319): started activity for popup
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,W/ResourcesManager( 5319): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5319): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5319): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5319): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5319): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5319): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SettingsReceiverActivity( 5319): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1015): Focused application set to: xxxx
,D/InputDispatcher( 1015): Focus entered window: 5969
,D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
D/InputMethodManagerService( 1015): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService( 1015): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@6a4c4a4 attribute=null, token = android.os.BinderProxy@127a1410
,D/SettingsReceiverActivity( 5319): dev.kiessupport is : TRUE
,D/PhoneWindow( 5319): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5319): *FMB* installDecor flags : 8388610
,D/ActivityManager( 1015): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1015): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1015): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1015): handleActiveUserChange for user 0
,D/PersonaManagerService( 1015): getPersonasForUser(): returning null!
,V/ActivityThread( 5969): updateVisibility : ActivityRecord{733d81a token=android.os.BinderProxy@16e2e93c {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/Timeline( 5969): Timeline: Activity_idle id: android.os.BinderProxy@16e2e93c time:113194
,D/PersonaManager( 1015): isKioskContainerExistOnDevice
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ActivityManager( 1015): mDVFSHelper.release()
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
,W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000,
W/ActivityManager( 1015): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1015): [PWL] Off : 50s ago
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:n  ( 1015): SIOP:: AP = 290
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  286): DCD OFF
,E/Watchdog( 1015): !@Sync 4
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  286): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 75s ago,
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  286): DCD OFF,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,I/ClearcutLoggerApiImpl( 1819): disconnect managed GoogleApiClient
,E/Watchdog( 1015): !@Sync 5
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,V/AlarmManager( 1015): waitForAlarm result :8,
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 105s ago
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1015): !@Sync 6
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,V/AlarmManager( 1015): waitForAlarm result :4
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
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  286): DCD OFF
,I/Atfwd_Sendcmd(  313): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  313): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 140s ago
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
,I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/Watchdog( 1015): !@Sync 7
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,V/AlarmManager( 1015): waitForAlarm result :8
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1015): stay LED for fully charged
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  286): DCD OFF,
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1015): !@Sync 8,
,I/PowerManagerService( 1015): [PWL] Off : 180s ago
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
,D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1015): Plugged
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1015): !@Sync 9,
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,I/ServiceManager(  313): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1015): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,I/ServiceManager(  313): Waiting for service AtCmdFwd...,
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,W/Atfwd_Sendcmd(  313): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,I/PowerManagerService( 1015): [PWL] Off : 225s ago
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1015): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1015): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 251, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1015): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1015): stay LED for fully charged
D/BatteryService( 1015): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED,
I/MotionRecognitionService( 1015): Plugged
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
I/MotionRecognitionService( 1015): mGripSensorEnabled= false
V/EmergencyMode( 1411): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1411): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2621): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2621): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1015): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1015): Do not check CP during LCD off.
,E/SMD     (  286): DCD OFF
,I/jxcore-log( 5969): --= Surplus to requirements =--
I/jxcore-log( 5969): 
,I/jxcore-log( 5969): ****TEST TOOK:  ms ****
I/jxcore-log( 5969): 
I/jxcore-log( 5969): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5969): 
,D/AndroidRuntime( 6648): 
D/AndroidRuntime( 6648): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6648): CheckJNI is OFF
D/AndroidRuntime( 6648): readGMSProperty: start
D/AndroidRuntime( 6648): readGMSProperty: already setted!!,
D/AndroidRuntime( 6648): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6648): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6648): readGMSProperty: end
D/AndroidRuntime( 6648): addProductProperty: start
,E/AffinityControl( 6648): AffinityControl: registerfunction enter,
,D/AndroidRuntime( 6648): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1015): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1015): START PACKAGE DELETE: observer{1023722354}
D/PackageManager( 1015): pkg{<packageName>}
D/PackageManager( 1015): user{0}
D/PackageManager( 1015): caller{2000}
D/PackageManager( 1015): flags{3}
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1015): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1015): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1015): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManager( 1015): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1015): deletePackage- pkg:com.test.thalitest, edmuserId:0
,D/PackageManagerService( 1015): deletePackage- pkg:com.test.thalitest, edmuserId:-1
,D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1015): getApplicationUninstallationEnabled :  enabled true
D/PackageManager( 1015): !@killApplicatoin: 10155, uninstall pkg
I/ActivityManager( 1015): Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
I/ActivityManager( 1015): Killing 5969:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
,I/ActivityManager( 1015):   Force finishing activity ActivityRecord{3789297b u0 com.test.thalitest/.MainActivity t7}
,D/InputDispatcher( 1015): Focus left window: 5969
,I/SurfaceFlinger(  256): id=13 Removed NainActivit (6/8)
,I/SurfaceFlinger(  256): id=13 Removed NainActivit (-2/8)
,D/InputDispatcher( 1015): Focused application released
D/PointerIcon( 1015): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1015): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1015): Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,W/ActivityManager( 1015): CustomStartingWindow se packge removed so remove capture also
,W/GeofencerStateMachine( 1819): Ignoring removeGeofence because network location is disabled.
E/SamsungIME( 1784): mOCRHelper is null
,I/art     ( 4936): Explicit concurrent mark sweep GC freed 2522(147KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 975us total 38.687ms
,I/InputReader( 1015): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 5360): Explicit concurrent mark sweep GC freed 10053(608KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 896us total 66.086ms
,I/art     ( 2027): Explicit concurrent mark sweep GC freed 6482(350KB) AllocSpace objects, 1(16KB) LOS objects, 25% free, 13MB/18MB, paused 1.235ms total 93.355ms
,D/RegisteredComponentCache( 1435): Collect Tech packages for Knox
,D/PersonaManager( 1435): isKioskContainerExistOnDevice
,I/KLMS-2.5.183: ( 3536): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Jan 13 16:39:21 GMT+01:00 2016
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,W/SQLiteConnectionPool( 2027): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/KLMS-2.5.183: ( 3536): KLMSAbstractReciever(): onReceive().END.
,I/splitIntent( 1015): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
I/splitIntent( 1015): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3536): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3536): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3536): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,E/Zygote  ( 6661): MountEmulatedStorage()
I/libpersona( 6661): KNOX_SDCARD checking this for 10094
E/Zygote  ( 6661): v2
I/libpersona( 6661): KNOX_SDCARD not a persona
,I/SELinux ( 6661): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6661): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1015): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6661 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,E/SELinux ( 6661): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3536): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6668): MountEmulatedStorage()
,E/Zygote  ( 6668): v2
I/libpersona( 6668): KNOX_SDCARD checking this for 10044
I/libpersona( 6668): KNOX_SDCARD not a persona
,I/SELinux ( 6668): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6668): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1015): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6668 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/SELinux ( 6668): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3536): KLMSIntentService(): PACKAGE_REMOVED
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3536): KLMSIntentService(): listeningToPackageRemoved().START
,D/SecContentProvider2( 1015): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1015): mCursor = null
,E/Zygote  ( 6684): MountEmulatedStorage()
I/libpersona( 6684): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6684): v2
I/libpersona( 6684): KNOX_SDCARD not a persona
,I/SELinux ( 6684): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/KLMS-2.5.183: ( 3536): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/TimaKeyStoreProvider( 6661): TimaSignature is unavailable
I/SELinux ( 6684): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/ActivityThread( 6661): Added TimaKeyStore provider
E/SELinux ( 6684): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=6684 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,D/EnterpriseDeviceManagerService( 1015): Package has changed for user 0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/EnterpriseDeviceManagerService( 1015): Admin package name: com.google.android.gms
W/TextServicesManagerService( 1015): no available spell checker services found
,D/TimaKeyStoreProvider( 6668): TimaSignature is unavailable
,D/ActivityThread( 6668): Added TimaKeyStore provider
,E/Zygote  ( 6703): MountEmulatedStorage()
I/libpersona( 6703): KNOX_SDCARD checking this for 10149
E/Zygote  ( 6703): v2
I/libpersona( 6703): KNOX_SDCARD not a persona
I/SELinux ( 6703): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6703): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1015): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6703 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 6703): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/PersonaManager( 1435): isKioskContainerExistOnDevice
,D/TimaKeyStoreProvider( 6684): TimaSignature is unavailable
,D/ActivityThread( 6684): Added TimaKeyStore provider
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 65622(4MB) AllocSpace objects, 96(1537KB) LOS objects, 33% free, 28MB/42MB, paused 3.771ms total 264.272ms
,I/art     ( 1015): WaitForGcToComplete blocked for 176.012ms for cause Explicit
D/TimaKeyStoreProvider( 6703): TimaSignature is unavailable
,D/ActivityThread( 6703): Added TimaKeyStore provider
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RegisteredServicesCache( 1435): empty dynamic service
,W/ResourcesManager( 6668): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6668): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6668): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6668): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6668): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6668): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6668): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6668): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourcesManager( 6684): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KLMS-2.5.183: ( 3536): KLMSIntentService(): listeningToPackageRemoved().END
,D/elm:15183( 6661): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,I/KLMS-2.5.183: ( 3536): KLMSIntentService(): onDestroy()
,D/elm:15183( 6661): ELMEngine.ELMEngine( context ).
,D/elm:15183( 6661): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1015): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ThemeInfoUtil( 6703): getCurrentFestivalName is [null]
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
D/ThemeInfoUtil( 6703): isCurrentFestival = false
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6722): MountEmulatedStorage(),
I/libpersona( 6722): KNOX_SDCARD checking this for 10152
E/Zygote  ( 6722): v2
I/libpersona( 6722): KNOX_SDCARD not a persona
D/elm:15183( 6661): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/ActivityManager( 1015): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6722 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 5360:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31,
,I/SELinux ( 6722): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
I/SELinux ( 6722): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6722): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1015): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=6737 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/RCPManagerService( 1015): PackageReceiver onReceive()
I/HarmonyEASService( 1015): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,E/Zygote  ( 6737): MountEmulatedStorage()
I/libpersona( 6737): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6737): v2
I/libpersona( 6737): KNOX_SDCARD not a persona
I/SELinux ( 6737): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/KnoxMUMContainerPolicy( 1015): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1015): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1015): OtpDbHelper::getInstance New instance created
I/SELinux ( 6737): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/OTPFW   ( 1015): DBIntegrity::getInstance - New instance created
E/SELinux ( 6737): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/elm:15183( 6661): ElmAgentService : onCreate()
,D/TimaKeyStoreProvider( 6722): TimaSignature is unavailable
,D/ActivityThread( 6722): Added TimaKeyStore provider
,D/OTPFW   ( 1015): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,I/OTPFW   ( 1015): ProvisionData::getAllEntries Enter
,E/OTPFW   ( 1015): ProvisionData::getAllEntries Table is empty
D/BackupManagerService( 1015): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 1015): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1015): uID is 10155
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
,V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1015): uID is 10155
V/EnterpriseBillingPolicy( 1015): Removed Packageuid is0
D/TaskPersister( 1015): removeObsoleteFile: deleting file=7_task.xml
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 1015): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - personal application - profile null
D/SSRM:aZ ( 1015): MSG_TYPE_APP_REMOVED::
V/EnterpriseBillingPolicy( 1015): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1015): getBillingProfileForVpnEngine - end - null
V/AlarmManagerEXT( 1015): com.test.thalitest(10155) is removed.
,D/elm:15183( 6661): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 6661): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6661): MDMBridge.getInstance()
D/elm:15183( 6661): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:15183( 6661): MDMBridge.getAllLicenseInfoFromSDK()
,D/TimaKeyStoreProvider( 6737): TimaSignature is unavailable
,D/ActivityThread( 6737): Added TimaKeyStore provider
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:15183( 6661): ElmAgentService : onDestroy().
,I/ActivityManager( 1015): Killing 5811:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,D/AASAservice-UpdateReceiver( 6737): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,W/System.err( 6737): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,W/System.err( 6737): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
,W/System.err( 6737): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 6737): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
,W/System.err( 6737): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
,W/System.err( 6737): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
,W/System.err( 6737): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6737): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6737): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 6737): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6737): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6737): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6737): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/ActivityManager( 1015): Killing 5737:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,E/SQLiteLog( 6684): (284) automatic index on crash_info_summary(package_name_touched)
,E/SQLiteLog( 6722): (284) automatic index on shooting_modes(title_id)
,I/PCWCLIENTTRACE_PushUtil( 5672): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5672): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5672): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5672): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6757): MountEmulatedStorage()
,E/Zygote  ( 6757): v2
I/libpersona( 6757): KNOX_SDCARD checking this for 10032
I/SELinux ( 6757): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 6757): KNOX_SDCARD not a persona,
I/art     ( 6684): Explicit concurrent mark sweep GC freed 7312(355KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 783us total 106.472ms
I/ActivityManager( 1015): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6757 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 6757): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 6757): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/ResourceType( 1015): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     (  305): Explicit concurrent mark sweep GC freed 8727(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 657us total 29.452ms
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 6757): TimaSignature is unavailable
,D/ActivityThread( 6757): Added TimaKeyStore provider
,W/ResourcesManager( 1015): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1015): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 619us total 17.004ms
,D/BadgeProvider( 5851): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5851): sendNotify, [notify] : null
D/BadgeProvider( 5851): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5851): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5851): update, [UpdateCount] : 1
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 607us total 16.805ms
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     ( 1015): Explicit concurrent mark sweep GC freed 16096(901KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 28MB/42MB, paused 3.773ms total 388.632ms
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  ( 6773): MountEmulatedStorage()
E/Zygote  ( 6773): v2
I/libpersona( 6773): KNOX_SDCARD checking this for 10156
I/libpersona( 6773): KNOX_SDCARD not a persona
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/SELinux ( 6773): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=6773 uid=10156 gids={50156, 9997} abi=armeabi-v7a,
,I/SELinux ( 6773): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6773): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1015): Killing 5991:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6791): MountEmulatedStorage()
,I/libpersona( 6791): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6791): v2
I/libpersona( 6791): KNOX_SDCARD not a persona
D/NearbySource( 6668): Nearby Source Create!
I/SELinux ( 6791): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/NearbyContext( 6668): Nearby Context Create!
,I/SELinux ( 6791): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1015): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6791 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 6791): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6773): TimaSignature is unavailable
I/ActivityManager( 1015): Killing 6014:com.samsung.helphub/1000 (adj 15): empty #31
,D/ActivityThread( 6773): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 6791): TimaSignature is unavailable
,D/ActivityThread( 6791): Added TimaKeyStore provider
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1015): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1015): clearDefaults: com.test.thalitest
,I/CrashAnrDetector( 1015): onPackageRemoved : com.test.thalitest
,W/libprocessgroup( 1015): failed to open /acct/uid_10057/pid_5360/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10091/pid_5737/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10038/pid_5811/cgroup.procs: No such file or directory
,D/PackageManager( 1015): delete codoeFile: 
,I/TapandpayWidget:TapandpayAppWidgetProvider( 6773): onReceive()
,D/TapandpayWidget:TapandpayAppWidgetProvider( 6773): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/FeatureConfig( 6757): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/AASAuninstall( 1015): userId = 0, info.removedAppID = -1, info.uid = 10155, packageName = com.test.thalitest
I/AASA_removePackage( 1015): UID=10155 Target=com.test.thalitest
,I/TapandpayWidget:Utils( 6773): Clear T&P info.
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,D/PackageManager( 1015): result of delete: 1{1023722354}
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/TapandpayWidget:TapandpayAppWidgetProvider( 6773): Widget is not attached.
,W/ContextImpl( 6791): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,D/AndroidRuntime( 6648): Shutting down VM,
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_6014/cgroup.procs: No such file or directory
,W/ResourcesManager( 6757): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6757): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ContextImpl( 6668): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,W/ResourcesManager( 6757): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/SLinkSource( 6668): Samsung link source created
W/ResourcesManager( 6757): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6757): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  ( 6810): MountEmulatedStorage()
E/Zygote  ( 6810): v2
I/libpersona( 6810): KNOX_SDCARD checking this for 10035
I/libpersona( 6810): KNOX_SDCARD not a persona
,I/SELinux ( 6810): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1015): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6810 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 6810): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,W/ResourcesManager( 6757): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SELinux ( 6810): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 6102:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
W/ActivityManager( 1015): userId = 0, bbcId = -10000
D/ActivityManager( 1015): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6757): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6810): TimaSignature is unavailable
,D/ActivityThread( 6810): Added TimaKeyStore provider
,E/Zygote  ( 6826): MountEmulatedStorage()
E/Zygote  ( 6826): v2
I/libpersona( 6826): KNOX_SDCARD checking this for 10160
I/libpersona( 6826): KNOX_SDCARD not a persona
,I/SELinux ( 6826): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/ResourcesManager( 6757): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/SELinux ( 6826): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1015): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=6826 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
E/SELinux ( 6826): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Killing 6124:com.google.android.gms:car/u0a12 (adj 15): empty #31
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6841): MountEmulatedStorage()
I/libpersona( 6841): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6841): v2
I/libpersona( 6841): KNOX_SDCARD not a persona
,I/SELinux ( 6841): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6841): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6841): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6826): TimaSignature is unavailable
,D/ActivityThread( 6826): Added TimaKeyStore provider
I/ActivityManager( 1015): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6841 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,W/ResourcesManager( 6757): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6757): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/ActivityManager( 1015): Killing 6243:com.android.email/u0a145 (adj 15): empty #31
,W/ResourcesManager( 6826): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6757): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6841): TimaSignature is unavailable
,D/ActivityThread( 6841): Added TimaKeyStore provider
,W/libprocessgroup( 1015): failed to open /acct/uid_10100/pid_5991/cgroup.procs: No such file or directory
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6757): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6757): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6757): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6841): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/SPPClientService( 6810): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 6810): [PushClientApplication] Push log off : This is Ship build version
,E/Zygote  ( 6858): MountEmulatedStorage()
I/libpersona( 6858): KNOX_SDCARD checking this for 10038
E/Zygote  ( 6858): v2
I/libpersona( 6858): KNOX_SDCARD not a persona
,I/SELinux ( 6858): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6858): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6858): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1015): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=6858 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1015): Killing 6380:com.sec.android.cloudagent/u0a2 (adj 15): empty #31
,W/ResourcesManager( 6757): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/WifiDisplayAdapter( 1015): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ContactProvider( 6668): getAllContactInfoList Start
I/PackagesMonitor( 6668): PackagesMonitor onReceive :com.test.thalitest
,D/SPPClientService( 6810): PushLog.txt file is not deleted.
D/SPPClientService( 6810): PushLog.txt file is not deleted.
D/SPPClientService( 6810): ============PushLog. stop!
,D/TimaKeyStoreProvider( 6858): TimaSignature is unavailable
D/Launcher.Model( 1476): reloadBadges entered.
D/ActivityThread( 6858): Added TimaKeyStore provider
,W/art     ( 6648): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/RCPManager( 6841):  in createShortcut() for packageName: com.test.thalitest userId0
,W/ResourcesManager( 6858): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6858): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6757): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6757): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ContactProvider( 6668): getAllContactInfoList End
,I/syncContacts( 6668): thread: 1138, sync time = 114
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1015):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1015): queryAllProviders():  providerCallBack is not register for 0
,W/libprocessgroup( 1015): failed to open /acct/uid_10142/pid_6102/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10012/pid_6124/cgroup.procs: No such file or directory
,W/libprocessgroup( 1015): failed to open /acct/uid_10145/pid_6243/cgroup.procs: No such file or directory
,E/Zygote  ( 6875): MountEmulatedStorage()
I/libpersona( 6875): KNOX_SDCARD checking this for 10046
E/Zygote  ( 6875): v2
I/libpersona( 6875): KNOX_SDCARD not a persona
,I/SELinux ( 6875): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=6875 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a,
,I/SELinux ( 6875): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6875): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,W/ResourcesManager( 6757): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
I/ActivityManager( 1015): Killing 6338:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
W/ResourcesManager( 6757): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6757): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ActivityManager( 1015): startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1015): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6757): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6757): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 6891): MountEmulatedStorage(),
E/Zygote  ( 6891): v2
I/libpersona( 6891): KNOX_SDCARD checking this for 10091
,I/libpersona( 6891): KNOX_SDCARD not a persona
,I/SELinux ( 6891): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1015): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6891 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1015): Killing 6355:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
D/TimaKeyStoreProvider( 6875): TimaSignature is unavailable
,D/ActivityThread( 6875): Added TimaKeyStore provider
I/SELinux ( 6891): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,W/GalaxyFinderApplication( 6757): system/finder_cp/cpdata.xml file not found
,E/SELinux ( 6891): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/SQLiteLog( 6684): (10) unixWrite() File Descriptor : 26 gets errno : 9
D/[0]UMC:UMCContentProvider( 6826): @onCreate
,E/SQLiteLog( 6684): (10) unixWrite() File Descriptor : 26 gets errno : 9
,E/SQLiteDatabase( 6684): Error inserting name=isDevelopVersion value=false
E/SQLiteDatabase( 6684): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:186)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
E/SQLiteDatabase( 6684): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6684): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6684): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6684): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 6684): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6684): (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
E/SQLiteDatabase( 6684): Error inserting name=DBVersion value=2003
E/SQLiteDatabase( 6684): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:187)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
E/S,QLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
E/SQLiteDatabase( 6684): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6684): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6684): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6684): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 6684): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6684): (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
E/SQLiteDatabase( 6684): Error inserting name=LPCSystemVersion value=1.0.0
E/SQLiteDatabase( 6684): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:188)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
E/SQLiteDatabase( 6684): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6684): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6684): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6684): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/TimaKeyStoreProvider( 6891): TimaSignature is unavailable
,D/ActivityThread( 6891): Added TimaKeyStore provider
,E/SQLiteLog( 6684): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6684): (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
E/SQLiteDatabase( 6684): Error inserting name=UT enabled value=false
E/SQLiteDatabase( 6684): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:189)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
E/SQLiteDatabase( 6684): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6684): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6684): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6684): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 6684): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6684): (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
E/SQLiteLog( 6858): (28) failed to open "/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db" with flag (131138) and mode_t (0) due to error (30)
E/SQLiteDatabase( 6684): Error inserting name=AFP Enabled value=true
E/SQLiteDatabase( 6684): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:190)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
E/SQLiteDatabase( 6684): 	at com,.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
E/SQLiteDatabase( 6684): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6684): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6684): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6684): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 6684): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6684): (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
E/SQLiteLog( 6684): (284) automatic index on crash_info_summary(package_name_touched)
E/SQLiteDatabase( 6684): Error inserting name=SleepDetection Enabled value=false
E/SQLiteDatabase( 6684): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:191)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
E/SQLiteDatabase( 6684): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6684): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6684): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6684): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 6684): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6684): (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
E/SQLiteDatabase( 6684): Error inserting name=System Build Version Release value=5.0.2
E/SQLiteDatabase( 6684): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 6684): 	at android.database.sqli,te.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:192)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
E/SQLiteDatabase( 6684): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6684): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6684): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6684): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ResourcesManager( 6875): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
E/SQLiteLog( 6684): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 6684): (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
E/SQLiteDatabase( 6684): Error inserting name=status value=successfully initialized
E/SQLiteDatabase( 6684): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 6684): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2485)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1741)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.f(LowpowerContextEngine.java:193)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.d(LowpowerContextEngine.java:132)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:82)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:88)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:121)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver.a(LowpowerContextReceiver.java:21)
E/SQLiteDatabase( 6684): 	at com.samsung.android.sm.database.lowpowercontext.m.run(LowpowerContextReceiver.java:50)
E/SQLiteDatabase( 6684): 	at android.os.Handler.handleCallback(Handler.java:739)
E/SQLiteDatabase( 6684): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 6684): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6684): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 6858): Failed to open database '/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db'.
E/SQLiteDatabase( 6858): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6858): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6858): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 6858): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 6858): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6858): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6858): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6858): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 6858): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 6858): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 6858): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 6858): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 6858): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6858): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6858): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:471)
E/SQLiteDatabase( 6858): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteDatabase( 6858): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteDatabase( 6858): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 6858): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 6858): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 6858): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 6858): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 6858): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6858): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 6858): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 6858): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 6858): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 6858): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 6858): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/AndroidRuntime( 6858): Shutting down VM
W/ResourcesManager( 6875): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/AndroidRuntime( 6858): FATAL EXCEPTION: main
E/AndroidRuntime( 6858): Process: com.samsung.android.sdk.samsunglink, PID: 6858
E/AndroidRuntime( 6858): java.lang.RuntimeException: Unable to get provider com.mfluent.asp.datamodel.ASPMediaStoreProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6858): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
E/AndroidRuntime( 6858): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/AndroidRuntime( 6858): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/AndroidRuntime( 6858): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/AndroidRuntime( 6858): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/AndroidRuntime( 6858): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6858): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 6858): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/AndroidRuntime( 6858): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 6858): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 6858): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 6858): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 6858): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6858): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6858): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 6858): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 6858): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6858): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6858): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6858): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/AndroidRuntime( 6858): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/AndroidRuntime( 6858): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 6858): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/AndroidRuntime( 6858): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 6858): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 6858): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 6858): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:471)
E/AndroidRuntime( 6858): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/AndroidRuntime( 6858): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/AndroidRuntime( 6858): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/AndroidRuntime( 6858): 	... 11 more
W/ResourcesManager( 6875): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
V/ApplicationPolicy( 1015): isApplicationStateBlocked userId 0 pkgname com.samsung.android.sdk.samsunglink
W/ResourcesManager( 6875): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6875): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6875): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
W/libprocessgroup( 1015): failed to open /acct/uid_10002/pid_6380/cgroup.procs: No such file or directory
D/[0]UMC:Core( 6826): onCreate(): 
D/[0]UMC:Core( 6826): @isManagedProfileUser
D/[0]UMC:Core( 6826): userId: 0
E/DropBoxManagerService( 1015): Can't write: system_app_crash
E/DropBoxManagerService( 1015): java.io.FileNotFoundException: /data/system/dropbox/drop177.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1015): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1015): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1015): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1015): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1015): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15989)
E/DropBoxManagerService( 1015): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1015): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1015): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1015): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1015): 	... 5 more
D/[0]UMC:Core( 6826): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 6826): userInfo.isManagedProfile() : false
E/SQLiteLog( 5851): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 5851): (3850) statement aborts at 28: [UPDATE apps SET badgecount=? WHERE package=? AND class=?] disk I/O error
,E/DatabaseUtils( 5851): Writing exception to parcel
E/DatabaseUtils( 5851): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DatabaseUtils( 5851): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/DatabaseUtils( 5851): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
E/DatabaseUtils( 5851): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/DatabaseUtils( 5851): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/DatabaseUtils( 5851): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1714)
E/DatabaseUtils( 5851): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1660)
E/DatabaseUtils( 5851): 	at com.sec.android.provider.badge.BadgeProvider.update(BadgeProvider.java:170)
E/DatabaseUtils( 5851): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
E/DatabaseUtils( 5851): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:222)
E/DatabaseUtils( 5851): 	at android.os.Binder.execTransact(Binder.java:461)
W/libprocessgroup( 1015): failed to open /acct/uid_1000/pid_6338/cgroup.procs: No such file or directory
W/libprocessgroup( 1015): failed to open /acct/uid_10159/pid_6355/cgroup.procs: No such file or directory
I/ActivityManager( 1015): Killing 6412:com.sec.android.diagmonagent/1000 (adj 15): empty #31
I/Process ( 6858): Sending signal. PID: 6858 SIG: 9
I/SA      ( 5943): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 5943): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10155 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
D/ActivityManager( 1015): startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
D/ActivityManager( 1015): retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1015): userId = 0, bbcId = -10000
W/ActivityManager( 1015): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1015): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
D/Mms/MmsApp( 6875): [start]    onCreate() consume time = 0.0

```
