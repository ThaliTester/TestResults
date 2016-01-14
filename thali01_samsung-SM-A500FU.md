#### Test 55613145c131883_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
E/Zygote  ( 5885): MountEmulatedStorage()
E/Zygote  ( 5885): v2
I/SELinux ( 5885): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5885): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
--------- beginning of system
I/libpersona( 5885): KNOX_SDCARD checking this for 10035
I/libpersona( 5885): KNOX_SDCARD not a persona
E/SELinux ( 5885): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=5885 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/TP/MmsSmsProvider( 1466): query,matched:2117, calling pid = 5752
E/PhotosPlugin( 5841): Loading PhotosPlugin
D/TP/MmsSmsProvider( 1466): match 2117:Elapsed time : 1.383 ms
D/TimaKeyStoreProvider( 5885): TimaSignature is unavailable
D/ActivityThread( 5885): Added TimaKeyStore provider
D/EasySignUpManager_1.0.1( 5752): isAuth is false
D/EasySignUpManager_1.0.1( 5752): getServiceStatus : serviceId (1) is OFF
E/CscParser( 5752): mps_code.dat does not exist
E/CscParser( 5752): customer_path =/system/csc/customer.xml
E/CscParser( 5752): fileName + /system/csc/customer.xml
I/DBG_POLICYDM( 5825): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
V/WindowOrientationListener( 1018): WindowOrientationListener disabled
D/SensorService( 1018): [SO] activate (ident=0xb79091a8, enabled=0)
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
I/SurfaceFlinger(  258): id=12 createSurf (720x1280),-1 flag=20004, DolorFade
I/DBG_POLICYDM( 5825): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
D/PowerManagerService( 1018): [s] UserActivityState : 2 -> 4
I/PowerManagerService( 1018): Nap time (uid 1000)...
D/PowerManagerService( 1018): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
I/PowerManagerService( 1018): !@[ps] Screen__Off - 0 :  dream(timeout) (2)
I/PowerManagerService( 1018): Going to sleep due to screen timeout (uid 1000)...
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1018): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1018): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 1018): SecHardwareInterface.setBatteryADC : false
D/PowerManagerService( 1018): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
D/PowerManagerService( 1018): handleSandman : startDream(true)
E/PowerManagerService( 1018): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 1018): Sleeping (uid 1000)...
D/PowerManagerService( 1018): [s] UserActivityState : 4 -> 0
I/DBG_POLICYDM( 5825): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
I/DBG_POLICYDM( 5825): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
I/DBG_POLICYDM( 5825): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
D/PowerManagerService( 1018): Excessive delay in ColorFade : createSurface: 16ms
D/SensorManager( 1018): unregisterListener ::   
I/Adreno-EGL( 1018): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1018): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1018): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1018): Local Branch: 
I/Adreno-EGL( 1018): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1018): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1018):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
D/KeyguardViewMediator( 1175): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1175): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1175): changeWallpaperByScreenOff()
E/CscParser( 5752): mps_code.dat does not exist
E/CscParser( 5752): customer_path =/system/csc/customer.xml
E/CscParser( 5752): fileName + /system/csc/customer.xml
D/KeyguardViewMediator( 1175): notifyScreenOffLocked
D/KeyguardViewMediator( 1175): timeout : 5000
I/DBG_DM  ( 3093): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
D/CscParser( 5752): getInstance fileName =/system/csc/customer.xml
D/Mms/MmsConfig( 5752):  enable multiwindow = true
D/PowerManagerService( 1018): Excessive delay in ColorFade : createEglContext: 30ms
E/Mms/MessageUtils( 5752): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 5752): updateCountryIso : update country iso info 
W/art     ( 2010): Suspending all threads took: 12.557ms
D/PermissionCache(  258): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (530 us)
D/Mms/MmsConfig( 5752): [end]    init() consume time = 189.850729
D/Mms/Contact( 5752): [start]    init() consume time = 1.086667
D/PowerManagerService( 1018): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 24ms
I/DBG_POLICYDM( 5825): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
V/ActivityThread( 3093): updateVisibility : ActivityRecord{22f83fb6 token=android.os.BinderProxy@7003bc5 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/KeyguardViewMediator( 1175): setting alarm to turn off keyguard, seq = 1
D/KeyguardViewMediator( 1175): handleNotifyScreenOff
D/VolumePanel( 1175): onScreenTurnedOff()
D/VolumePanel( 1175): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/VolumePanel( 1175): mCoverBroadcastReceiver: Screen OFF end
D/TP/MmsSmsProvider( 1466): query,matched:13, calling pid = 5752
I/DBG_POLICYDM( 5825): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
D/TP/MmsSmsProvider( 1466): match 13:Elapsed time : 2.127 ms
D/SecKeyguardClockSingleView( 1175): onScreenTurnedOff
D/Mms/Contact( 5752): [end]    init consume time = 52.491041
I/DBG_POLICYDM( 5825): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
I/DBG_POLICYDM( 5825): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
E/SmartFaceService( 1018): onReceive: android.intent.action.SCREEN_ON
I/DBG_POLICYDM( 5825): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
D/PowerManagerService( 1018): Excessive delay in ColorFade : initGLShaders: 62ms
D/PowerManagerService( 1018): Excessive delay in ColorFade prepare: 155ms
D/DisplayPowerController( 1018): ColorFade: onAnimationStart
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
D/Mms/DraftCache( 5752): [start]    rebuildCache consume time = 31.142448
W/System.err( 1018): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
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
E/SmartFaceService( 1018): fail to set sysfs 1
I/DBG_POLICYDM( 5825): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/DBG_POLICYDM( 5825): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
D/Mms/MethodReflector( 5752): getSubId is called
D/InputMethodManagerService( 1018): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
D/PanelView( 1175): There is/are notification(s) 
D/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_SCREEN_ON
D/Mms/TelephonyUtils( 5752): getLongSubId from simSlot 0, return Value = -1
D/TP/MmsSmsProvider( 1466): query,matched:12, calling pid = 5752
D/TP/MmsSmsProvider( 1466): match 12:Elapsed time : 1.037 ms
I/DBG_POLICYDM( 5825): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
I/DBG_POLICYDM( 5825): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
I/DBG_POLICYDM( 5825): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
I/DBG_POLICYDM( 5825): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
I/DBG_POLICYDM( 5825): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
E/MotionRecognitionService( 1018):  handler : SCREEN_ON end
D/NotificationService( 1018): ACTION_SCREEN_ON
D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
I/DBG_POLICYDM( 5825): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
D/audio_hw_primary(  286): adev_set_parameters: enter: screen_state=on
V/voice   (  286): voice_set_parameters: enter: screen_state=on
V/voice   (  286): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  286): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  286): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  286): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  286): adev_set_parameters: exit
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5825): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5825): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
E/WifiNative-wlan0( 1018): do suspend false
D/Mms/MethodReflector( 5752): getTelephonyProperty is called
D/Mms/DownloadManager( 5752): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5752): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5752): auto download without roaming -> true
D/Mms/DownloadManager( 5752): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 5752): getSubId is called
I/wpa_supplicant( 2075): reset timer : RESET_TIMER 1
I/wpa_supplicant( 2075): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2075): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2075): Scan requested (ret=0) - scan timeout 30 seconds
I/DBG_POLICYDM( 5825): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/01/18/12:08:32
I/DBG_POLICYDM( 5825): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/01/14/13:17:11
I/DBG_POLICYDM( 5825): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
I/DBG_POLICYDM( 5825): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
E/SPPClientService( 5885): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5885): [PushClientApplication] Push log off : This is Ship build version
E/Zygote  ( 5919): MountEmulatedStorage()
I/libpersona( 5919): KNOX_SDCARD checking this for 10038
E/Zygote  ( 5919): v2
I/libpersona( 5919): KNOX_SDCARD not a persona
I/SELinux ( 5919): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5919 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
D/Mms/MethodReflector( 5752): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5752): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5752): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5752): getTelephonyProperty is called
D/Mms/DownloadManager( 5752): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5752): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5752): auto download without roaming -> true
D/Mms/DownloadManager( 5752): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5752): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5752): mAutoDownload ------> true
I/SELinux ( 5919): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5919): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/Mms/DraftCache( 5752): [end]    rebuildCache consume time = 70.984323
D/SPPClientService( 5885): PushLog.txt file is not deleted.
D/SPPClientService( 5885): PushLog.txt file is not deleted.
D/SPPClientService( 5885): ============PushLog. stop!
I/DBG_POLICYDM( 5825): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
D/IpRemoteDisplayController( 1018): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 1018): Bridge Server is not available
D/GpsLocationProvider( 1018): receive broadcast intent, action: android.intent.action.SCREEN_ON
D/PersonaManagerService( 1018): ACTION_SCREEN_ON onReceive
D/PersonaManagerServiceHandler( 1018): MSG_ACTION_SCREEN_ON called
D/TimaKeyStoreProvider( 5919): TimaSignature is unavailable
D/ActivityThread( 5919): Added TimaKeyStore provider
W/art     ( 2010): Verification of void com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0(android.content.Context, com.google.android.gms.common.app.BaseApplicationContext) took 227.963ms
I/DBG_POLICYDM( 5825): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
D/ComposerPerformance( 5752): 1452773832025 ms / [DONE] Composer constructor
E/CII     ( 5752): CommonIMSInterface: VoLTE CSC feature disabled.
D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
I/NfcService( 1448): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
D/NfcService( 1448): call the applyRouting
I/DBG_POLICYDM( 5825): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
D/accuweather( 1729): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
D/accuweather( 1729): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1729): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1729): [KK AccuPhone]>>> UIM:282 [0:0] update clock event, is not screen on!!
I/Mms/ReservationManager( 5752): ReservationManager()
D/ActivityManager( 1018): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
I/Mms/ReservationManager( 5752): resetAfterConnected()
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
D/TP/MmsSmsProvider( 1466): query,matched:7, calling pid = 5752
D/Mms/Conversation( 5752): [start]    init() consume time = 97.777813
W/ResourcesManager( 5919): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5919): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/TP/MmsSmsProvider( 1466): match 7:Elapsed time : 4.722 ms
I/SamsungIME( 1767): getNextShiftState() cursorCapsMode : 0
D/TP/MmsSmsProvider( 1466): deleteConversation threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1466): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1466): updateThread(), thread_id = 9223372036854775807
V/TP/MmsSmsDatabaseHelper( 1466): sUpgradeVersion = 0, db.getVersion() = 81
I/ServiceManager(  330): Waiting for service AtCmdFwd...
D/TP/MmsSmsProvider( 1466): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1466): need read changed broadcast:false
D/Mms/Conversation( 5752): [end]    init consume time = 33.188906
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/DisplayPowerState( 1018): !@ ColorFade entry
D/DisplayPowerController( 1018): ColorFade: onAnimationEnd
D/Mms/MessagingNotification( 5752): [start]    init() consume time = 15.201354
D/lights  ( 1018): lcd : 0 +
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 0 -> 0
I/Mms/ReservationManager( 5752): getReservedSendMessageCount(): retMessageCount=0
D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
D/Mms/MmsApp( 5752): [end]    onCreate() consume time = 7.055677
D/Mms/MessagingNotification( 5752): [end]    init consume time = 4.142448
D/TP/MmsSmsProvider( 1466): query,matched:0, calling pid = 5752
V/TP/MmsSmsProvider( 1466): getSimpleConversations entered.
D/TP/MmsSmsProvider( 1466): match 0:Elapsed time : 1.986 ms
D/Mms/Synchronizer( 5752): [start]    doSync consume time = 13.028177
D/Mms/SpamFilter( 5752): [start]    SpamFilter fill() begin consume time = 1.019115
D/lights  ( 1018): lcd : 0 -
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1018): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event3/device/enabled: 0
D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event3/device/enabled: 0
D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1018): Got set_interactive hint
D/TP/MmsSmsProvider( 1466): update, matched:300, calling pid = 5752
V/TP/MmsSmsProvider( 1466): syncDBData start
V/TP/MmsSmsProvider( 1466): syncDBData sms end
V/TP/MmsSmsProvider( 1466): syncDBData mms end
V/TP/MmsSmsProvider( 1466): syncDBData end
D/TP/MmsSmsProvider( 1466): query,matched:400, calling pid = 5752
D/Mms/DownloadManager( 5752): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/Synchronizer( 5752): [end]    doSync consume time = 12.684583
D/Mms/DownloadManager( 5752): roaming ------> false, mSimSlot = 0
D/Mms/MethodReflector( 5752): getSubId is called
D/Mms/TelephonyUtils( 5752): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5752): getTelephonyProperty is called
D/Mms/DownloadManager( 5752): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5752): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5752): auto download without roaming -> true
D/Mms/DownloadManager( 5752): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5752): mAutoDownload ------> true
D/DisplayManagerService( 1018): !@display_state: ON -> OFF
I/DisplayManagerService( 1018): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  258): Set power mode=0, type=0 flinger=0xb820d690
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 0 on display: 0
E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
D/Mms/ArtClassLoader( 5752): init [DONE] art
D/Mms/SpamFilter( 5752): [end]    SpamFilter fill() finished consume time = 26.281875
V/ActivityManager( 1018): Display changed displayId=0
D/ActivityManager( 1018): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
I/DBG_POLICYDM( 5825): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5941): MountEmulatedStorage()
I/libpersona( 5941): KNOX_SDCARD checking this for 10072
E/Zygote  ( 5941): v2
I/libpersona( 5941): KNOX_SDCARD not a persona
I/SELinux ( 5941): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/Mms/FreeMessageStatusReceiver( 5752): onReceive, action : android.intent.action.PACKAGE_ADDED
D/StatusBar.NetworkController( 1175): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
I/ActivityManager( 1018): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5941 uid=10072 gids={50072, 9997} abi=armeabi-v7a
D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ActivityManager( 1018): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
D/SSRM:n  ( 1018): SIOP:: AP = 330
I/SELinux ( 5941): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5941): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5825): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
D/TimaKeyStoreProvider( 5941): TimaSignature is unavailable
I/libpersona( 5961): KNOX_SDCARD checking this for 10047
D/ActivityThread( 5941): Added TimaKeyStore provider
I/libpersona( 5961): KNOX_SDCARD not a persona
E/Zygote  ( 5961): MountEmulatedStorage()
E/Zygote  ( 5961): v2
I/SELinux ( 5961): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/BatteryStatsDumper( 1018): In refreshStats isReason Screen ON/OFF: true
I/SELinux ( 5961): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5961): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/TimaKeyStoreProvider( 5961): TimaSignature is unavailable
D/ActivityThread( 5961): Added TimaKeyStore provider
D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
I/ActivityManager( 1018): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5961 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
D/LightsService( 1018): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 10, onMS = 0, offMS = 0,  (uid: 1000 pid: 1018) 
D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x10 | SvcLED(id=3) set On
D/BatteryService( 1018): turn on LED for charging
E/lights  ( 1018): write_int failed to open -1
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
E/SmartFaceService( 1018): onReceive: android.intent.action.SCREEN_OFF
W/System.err( 1018): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1018): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1018): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1018): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1018): 	at android.os.Looper.loop(Looper.java:145)
E/SmartFaceService( 1018): fail to set sysfs 0
W/System.err( 1018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1018): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1018): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1018): 	... 10 more
D/Mms/FreeMessageReceiverService( 5752): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5752): onHandleIntent: ACTION_PACKAGE_ADDED
W/ResourcesManager( 5961): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/BatteryStatsDumper( 1018): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1018): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1018): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1018): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1018): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1018): Previous Battery Level: 0 Current Level: 100 Delta: -100
W/ResourcesManager( 5961): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5961): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/ActivityManager( 1018): Killing 5202:com.google.android.talk/u0a104 (adj 15): empty #31
I/ActivityManager( 1018): Killing 5349:com.android.providers.calendar/u0a42 (adj 15): empty #32
D/PanelView( 1175): There is/are notification(s) 
D/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_SCREEN_OFF
D/SamsungIME( 1767): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/BadgeProvider( 5941): onCreate
D/BadgeProvider( 5941): DatabaseHelper
I/DBG_POLICYDM( 5825): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
E/MotionRecognitionService( 1018):  handler : SCREEN_OFF end 
D/NotificationService( 1018): ACTION_SCREEN_OFF
D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x10 | SvcLED(id=4) set Off
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/DBG_POLICYDM( 5825): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 0 on display 0
D/audio_hw_primary(  286): adev_set_parameters: enter: screen_state=off
V/voice   (  286): voice_set_parameters: enter: screen_state=off
V/voice   (  286): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  286): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  286): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  286): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  286): adev_set_parameters: exit
D/SurfaceControl( 1018): Excessive delay in setPowerMode(): 261ms
E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
D/PowerManagerService( 1018): Excessive delay in !@display_state: OFF: 263ms
I/libsuspend( 1018): !@autosuspend_wakeup_count_enable
I/libsuspend( 1018): !@autosuspend_wakeup_count_enable done
D/PowerManagerService( 1018): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 282ms
I/PowerManagerService( 1018): [PWL] Off : 0s ago
I/PowerManagerService( 1018): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1018): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1018, ws=WorkSource{1000}) (elapsedTime=1237)
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              'SmartManager Framework Thread' (uid=1000, pid=1018, ws=null) (elapsedTime=175)
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              'Icing' (uid=10012, pid=2010, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=1)
I/PowerManagerService( 1018): [PWL]   PowerManagerService.Broadcasts: ref count=1
D/Mms/MessagingNotification( 5752): checkBadgeCount unreadCount=0 badgeCount=0
I/BackgroundCompactionService( 1018): Schedule Type1 BGCompaction
D/TP/SmsProvider( 1466): query,matched:26, calling pid = 5752
D/TP/SmsProvider( 1466): match 26:Elapsed time : 1.102 ms
W/libprocessgroup( 1018): failed to open /acct/uid_10042/pid_5349/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10104/pid_5202/cgroup.procs: No such file or directory
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/IpRemoteDisplayController( 1018): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 1018): Bridge Server is not available
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TP/MmsSmsProvider( 1466): query,matched:6, calling pid = 5752
D/GpsLocationProvider( 1018): receive broadcast intent, action: android.intent.action.SCREEN_OFF
D/TP/MmsSmsProvider( 1466): match 6:Elapsed time : 2.896 ms
D/PersonaManagerService( 1018): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler( 1018): MSG_ACTION_SCREEN_OFF called
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
V/EmergencyMode( 1420): [EmergencyStateReceiver] binteractive [false] why[3]
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/MyFiles ( 5961): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
D/accuweather( 1729): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 1729): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
D/NfcService( 1448): call the applyRouting
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
D/accuweather( 1729): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
D/ActivityManager( 1018): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
E/installd(  287): system dir 0 : /system/app/
E/installd(  287): system dir 1 : /system/priv-app/
E/installd(  287): system dir 2 : /vendor/app/
E/installd(  287): system dir 3 : /oem/app/
D/ChimeraCfgMgr( 2010): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2010): Module APK com.google.android.play.games already loaded
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/TactileAssist( 1018): enable value -1
I/TactileAssist( 1018): internal enable value -1
I/TactileAssist( 1018): intensity value -1
I/TactileAssist( 1018): saveAppList value true
I/TactileAssist( 1018): List of disabled apps :
D/ChimeraCfgMgr( 2010): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/PackageManager( 1018): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
E/Zygote  ( 5984): MountEmulatedStorage()
E/Zygote  ( 5984): v2
I/libpersona( 5984): KNOX_SDCARD checking this for 10025
I/libpersona( 5984): KNOX_SDCARD not a persona
I/SELinux ( 5984): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5984 uid=10025 gids={50025, 9997} abi=armeabi-v7a
D/AsyncTaskServiceImpl( 2010): Submit a task: k
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/SELinux ( 5984): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5984): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6001): MountEmulatedStorage()
E/Zygote  ( 6001): v2
I/libpersona( 6001): KNOX_SDCARD checking this for 10053
I/libpersona( 6001): KNOX_SDCARD not a persona
I/SELinux ( 6001): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=6001 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
D/TimaKeyStoreProvider( 5984): TimaSignature is unavailable
D/ActivityThread( 5984): Added TimaKeyStore provider
I/SELinux ( 6001): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6001): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 5407:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 6001): TimaSignature is unavailable
D/ActivityThread( 6001): Added TimaKeyStore provider
W/ResourcesManager( 5984): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ChimeraCfgMgr( 2010): Loading module com.google.android.gms.gass from APK com.google.android.gms
W/ResourcesManager( 6001): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/ChimeraCfgMgr( 2010): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/SSRM:n  ( 1018): SIOP:: AP = 330
D/Compatibility( 6001): onReceive() it will make start service
D/k       ( 2010): Processing package: com.test.thalitest
D/ActivityManager( 1018): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Compatibility( 6001): onHandleIntent()
D/Compatibility( 6001): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10155, android.intent.extra.user_handle=0}]
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
D/Compatibility( 6001): found: 2
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6023): MountEmulatedStorage()
I/libpersona( 6023): KNOX_SDCARD checking this for 10057
E/Zygote  ( 6023): v2
I/libpersona( 6023): KNOX_SDCARD not a persona
I/SELinux ( 6023): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6023 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
I/OMACP   ( 5984): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
I/SELinux ( 6023): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6023): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/GassUtils( 2010): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
D/k       ( 2010): Found info for package com.test.thalitest in db.
D/Mms/Omacp( 5752): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/Compatibility( 6001): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
E/LibSecureUISvc( 1946): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Compatibility( 6001): skipping ResolveInfo{198d6a1 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 6001): considering ResolveInfo{20fea0c6 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 6001): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6001): enabling receiver ResolveInfo{8af887 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1018): failed to open /acct/uid_10057/pid_5407/cgroup.procs: No such file or directory
I/OMACP   ( 5984): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
E/WifiNative-wlan0( 1018): do suspend true
I/OMACP   ( 5984): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
D/TimaKeyStoreProvider( 6023): TimaSignature is unavailable
I/OMACP   ( 5984): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
D/Compatibility( 6001): enabling receiver ResolveInfo{124f23b4 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/ActivityThread( 6023): Added TimaKeyStore provider
I/OMACP   ( 5984): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 5984): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 5984): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
I/OMACP   ( 5984): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
I/OMACP   ( 5984): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 5984): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 5984): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/Compatibility( 6001): enabling receiver ResolveInfo{39cb3bdd com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
I/OMACP   ( 5984): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 5984): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 5984): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Compatibility( 6001): enabling receiver ResolveInfo{31b40352 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/Compatibility( 6001): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
I/ActivityManager( 1018): Killing 5467:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
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
D/PowerManagerService( 1018): [PWL] sb release: PowerManagerService.Broadcasts
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/BaseAppContext( 2010): Using Auth Proxy for data requests.
W/BaseAppContext( 2010): Using Auth Proxy for data requests.
W/libprocessgroup( 1018): failed to open /acct/uid_10069/pid_5467/cgroup.procs: No such file or directory
D/ActivityManager( 1018): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
I/SL_DEBUG( 5919): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5919): isLoggable:: SL_DEBUG_EXIST = false
D/SSRM:a  ( 1018): DeviceInfo:: 000000000000
D/SSRM:a  ( 1018): SettingsAirViewInfo:: 000000000
I/UpdateIcingCorporaServi( 6023): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
E/SMD     (  302): DCD OFF
I/ServiceManager(  330): Waiting for service AtCmdFwd...
I/art     ( 1018): Explicit concurrent mark sweep GC freed 243126(16MB) AllocSpace objects, 12(4MB) LOS objects, 33% free, 28MB/42MB, paused 2.986ms total 238.723ms
I/PeopleDatabaseHelper( 2010): cleanUpNonGplusAccounts done.
D/AndroidRuntime( 6018): 
D/AndroidRuntime( 6018): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6018): CheckJNI is OFF
D/AndroidRuntime( 6018): readGMSProperty: start
D/AndroidRuntime( 6018): readGMSProperty: already setted!!
D/AndroidRuntime( 6018): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6018): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6018): readGMSProperty: end
D/AndroidRuntime( 6018): addProductProperty: start
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5919): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/BaseAppContext( 2010): Using Auth Proxy for data requests.
W/BaseAppContext( 2010): Using Auth Proxy for data requests.
D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
W/BaseAppContext( 2010): Using Auth Proxy for data requests.
W/BaseAppContext( 2010): Using Auth Proxy for data requests.
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5919): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/LocationManagerService( 1018): getProviders()=[passive]
W/BaseAppContext( 2010): Using Auth Proxy for data requests.
D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/GAV2    ( 5841): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/Zygote  ( 6067): MountEmulatedStorage()
E/Zygote  ( 6067): v2
I/libpersona( 6067): KNOX_SDCARD checking this for 10041
I/libpersona( 6067): KNOX_SDCARD not a persona
I/SELinux ( 6067): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6067 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6067): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6067): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6067): TimaSignature is unavailable
D/ActivityThread( 6067): Added TimaKeyStore provider
I/UpdateIcingCorporaServi( 6023): UpdateCorporaTask done [took 121 ms] updated apps [took 121 ms] 
I/ActivityManager( 1018): Killing 5498:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
I/SA      ( 6067): [SSP] onCreated
I/SA      ( 6067): [TPM] There is no property file
I/SA      ( 6067): [SCU] isHaveSA() - false
I/SA      ( 6067): [TPM] getModelProperty : null
I/SA      ( 6067): [TPM] getCSCProperty : null
I/SA      ( 6067): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 6067): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 6067): [DM] TFT FEATURE: false
I/SA      ( 6067): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 6067): [DM] init START
I/SA      ( 6067): [DM] This device is not a Vodafone
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5498/cgroup.procs: No such file or directory
W/ResourceType( 6067): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 6067): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 6067): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 6067): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 6067): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 6067): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 6067): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 6067): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 6067): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 6067): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 6067): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 6067): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 6067): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 6067): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 6067): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 6067): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 6067): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 6067): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 6067): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 6067): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 6067): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 6067): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 6067): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 6067): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 6067): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 6067): [SCU] isHaveSA() - false
I/SA      ( 6067): support phone number id : false
I/SA      ( 6067): [DM] Supports Ref Jpn : true
I/SA      ( 6067): [DM] init END
I/ActivityManager( 1018): Killing 5514:com.google.android.apps.plus/u0a120 (adj 15): empty #31
I/SA      ( 6067): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 6067): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10155 extra.user_handle.:0 ]
I/ActivityManager( 1018): Killing 5096:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
E/AffinityControl( 6018): AffinityControl: registerfunction enter
W/libprocessgroup( 1018): failed to open /acct/uid_10120/pid_5514/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10150/pid_5096/cgroup.procs: No such file or directory
D/AndroidRuntime( 6018): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/BatteryStatsDumper( 1018): Writing to database completed
W/ActivityManager( 1018): mDVFSHelper.acquire()
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1018): *FMB* installDecor flags : 25362712
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6094): MountEmulatedStorage()
E/Zygote  ( 6094): v2
I/libpersona( 6094): KNOX_SDCARD checking this for 10155
I/libpersona( 6094): KNOX_SDCARD not a persona
I/SELinux ( 6094): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  258): id=13 createSurf (1x1),1 flag=404, uhalitest
I/SELinux ( 6094): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6094 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
E/SELinux ( 6094): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/art     (  319): Explicit concurrent mark sweep GC freed 8692(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 674us total 20.044ms
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 3093
D/AndroidRuntime( 6018): Shutting down VM
I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 16.586ms
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 6094): TimaSignature is unavailable
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/ActivityThread( 6094): Added TimaKeyStore provider
I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.706ms total 18.754ms
E/Zygote  ( 6112): MountEmulatedStorage()
E/Zygote  ( 6112): v2
I/libpersona( 6112): KNOX_SDCARD checking this for 10100
I/libpersona( 6112): KNOX_SDCARD not a persona
I/SELinux ( 6112): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6112): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6112 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
E/SELinux ( 6112): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/ActivityManager( 1018): Display changed displayId=0
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1018): isKioskContainerExistOnDevice
D/TimaKeyStoreProvider( 6112): TimaSignature is unavailable
D/ActivityThread( 6112): Added TimaKeyStore provider
D/ActivityManager( 1018): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
W/GAV2    ( 5841): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1823): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/SurfaceFlinger(  258): id=10 Removed YUIInstallC (5/9)
I/SurfaceFlinger(  258): id=10 Removed YUIInstallC (-2/9)
V/ActivityThread( 3093): updateVisibility : ActivityRecord{22f83fb6 token=android.os.BinderProxy@7003bc5 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
D/PackageIntentReceiver( 6112): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 6112): Not GearManger package! 
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6134): MountEmulatedStorage()
E/Zygote  ( 6134): v2
I/libpersona( 6134): KNOX_SDCARD checking this for 1000
I/libpersona( 6134): KNOX_SDCARD not a persona
I/SELinux ( 6134): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6134 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 4989:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
I/Icing   ( 2010): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
W/art     ( 2010): Verification of void com.google.android.gms.games.broker.PlayerAgent.<init>(com.google.android.gms.games.broker.Lockable, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer, com.google.android.gms.common.server.BaseApiaryServer) took 129.257ms
I/SELinux ( 6134): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6134): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/AccountFeatureHelper( 5841): Write apps_features disabled false
D/TimaKeyStoreProvider( 6134): TimaSignature is unavailable
D/ActivityThread( 6134): Added TimaKeyStore provider
W/art     ( 6018): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/GAV2    ( 5841): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager( 1018): Killing 4487:com.google.android.music:main/u0a111 (adj 15): empty #31
,I/WebViewFactory( 6094): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,I/LibraryLoader( 6094): Time to load native libraries: 2 ms (timestamps 517-519)
,I/LibraryLoader( 6094): Expected native library version number "",actual native library version number ""
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6152): MountEmulatedStorage()
,E/Zygote  ( 6152): v2
I/libpersona( 6152): KNOX_SDCARD checking this for 1000
I/libpersona( 6152): KNOX_SDCARD not a persona
,I/SELinux ( 6152): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6152): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6152 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 6152): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 4822:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
V/WebViewChromiumFactoryProvider( 6094): Binding Chromium to main looper Looper (main, tid 1) {8af887}
I/LibraryLoader( 6094): Expected native library version number "",actual native library version number ""
I/chromium( 6094): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,D/TimaKeyStoreProvider( 6152): TimaSignature is unavailable
,D/ActivityThread( 6152): Added TimaKeyStore provider
,I/Icing   ( 2010): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,W/libprocessgroup( 1018): failed to open /acct/uid_10040/pid_4989/cgroup.procs: No such file or directory
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/BrowserStartupController( 6094): Initializing chromium process, singleProcess=true
,W/art     ( 6094): Attempt to remove local handle scope entry from IRT, ignoring
W/libprocessgroup( 1018): failed to open /acct/uid_10111/pid_4487/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10134/pid_4822/cgroup.procs: No such file or directory
,E/SysUtils( 6094): ApplicationContext is null in ApplicationStatus
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,W/chromium( 6094): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 6094): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,I/chromium( 6094): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/Adreno-EGL( 6094): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
I/Adreno-EGL( 6094): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6094): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6094): Local Branch: 
I/Adreno-EGL( 6094): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6094): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6094):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/AcmsPackageEventListener( 6152): Received: android.intent.action.PACKAGE_ADDED,
,W/ContextImpl( 6152): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,E/Zygote  ( 6172): MountEmulatedStorage()
,I/libpersona( 6172): KNOX_SDCARD checking this for 10120
E/Zygote  ( 6172): v2
I/libpersona( 6172): KNOX_SDCARD not a persona
I/SELinux ( 6172): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6172): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1018): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6172 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 5328:com.android.calendar/u0a135 (adj 15): empty #31
D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,E/SELinux ( 6172): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/AcmsService( 6152): Enter Oncreate
D/AcmsServiceMonitor( 6152): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 6152): creating AcmsCore
D/AcmsCore( 6152): AcmsCore.getAcmsCore() - Enter
,D/AcmsCore( 6152): AcmsCore
,D/AcmsCore( 6152): init
,D/AcmsCore( 6152): Looper handler is not null
D/AcmsCore( 6152): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6152): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsServiceMonitor( 6152): Incrementing - Counter value: 1
D/AcmsCore( 6152): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 6152): onStartCommand
D/AcmsService( 6152): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 6152): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6152): Incrementing - Counter value: 2
D/AcmsService( 6152): Incremented Counter Value : onStartCommand
,D/ActivityManager( 1018): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/TimaKeyStoreProvider( 6172): TimaSignature is unavailable
D/ActivityThread( 6172): Added TimaKeyStore provider
I/ServiceManager(  330): Waiting for service AtCmdFwd...
D/ActivityThread( 6152): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsCertificateMngr( 6152): AcmsCertificateMngr,
,W/ResourcesManager( 6172): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Mms/MmsApp( 5752):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5752): [start]    fillCache consume time = 1945.150364
D/Mms/ComposeMessageFragment( 5752): fillCache, easy = false
,D/AcmsRevocationMngr( 6152): AcmsRevocationMngr
,D/AcmsService( 6152): Inside handle Intent
D/AcmsService( 6152): App added - package name: com.test.thalitest
D/AcmsCore( 6152): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6152): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6152): Incrementing - Counter value: 3
D/AcmsCore( 6152): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 6152): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 6152): Decrementing - Counter value: 2
,W/libprocessgroup( 1018): failed to open /acct/uid_10135/pid_5328/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2010): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2010): Module APK com.google.android.play.games already loaded
,I/wpa_supplicant( 2075): nl80211: Received scan results (5 BSSes)
,D/WifiP2pService( 1018): InactiveState{ what=147461 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147461 }
D/WifiP2pService( 1018): DefaultState{ what=147461 }
,W/chromium( 6094): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,D/AbsListView( 5752): Get MotionRecognitionManager
,D/MotionRecognitionService( 1018):  ssp status : false
,D/Mms/ComposeMessageFragment( 5752): [end]    fillCache consume time = 127.275781
,W/ActivityManager( 1018): Activity pause timeout for ActivityRecord{2bd5e537 u0 com.test.thalitest/.MainActivity t8}
,W/art     ( 6094): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 6094): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6094): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 6094): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6094): CordovaWebView is running on device made by: samsung
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/art     ( 6094): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6094): Attempt to remove local handle scope entry from IRT, ignoring
,D/OpenGLRenderer( 6094): Render dirty regions requested: true
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,V/ActivityThread( 6094): updateVisibility : ActivityRecord{9674e13 token=android.os.BinderProxy@2937d64d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6094): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6094): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  258): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/InputDispatcher( 1018): Focus entered window: 6094
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 6094): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 6094): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6094): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6094): Enabling debug mode 0
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,D/Mms/BubbleViewCache( 5752): fillCache bubble = 1
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/Timeline( 6094): Timeline: Activity_idle id: android.os.BinderProxy@2937d64d time:81068
,D/PanelView( 1175): There is/are notification(s) 
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 6094): showStatusIcon on inactive InputConnection
,I/ActivityManager( 1018): Displayed Component not be shown by security: +752ms (total +879ms)
,I/SamsungIME( 1767): getCurrentCandidateView
,W/ActivityManager( 1018): mDVFSHelper.release()
,I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{2bd5e537 u0 com.test.thalitest/.MainActivity t8} time:81096
,I/SurfaceFlinger(  258): id=13 Removed uhalitest (7/9)
,I/SurfaceFlinger(  258): id=13 Removed uhalitest (-2/9)
,I/splitIntent( 1018): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/daemonapp( 1301): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1301): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1301): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1301): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1301): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1301): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1301): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1301): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1301): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1301): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1301): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1452795360000
D/daemonapp( 1301): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1452773834567
,D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1301): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,W/BindingManager( 6094): Cannot call determinedVisibility() - never saw a connection for the pid: 6094
,D/daemonapp( 1301): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1301): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1301): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1301): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/SamsungIME( 1767): Dismiss ExpandCandiate
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
D/accuweather( 1729): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1729): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1729): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1729): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1729): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1729): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1729): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1729): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1729): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/JsMessageQueue( 6094): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager( 1018): Killing 5156:com.google.android.gm/u0a101 (adj 15): empty #31
,I/SamsungIME( 1767): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1767): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1767): KeybaordView init() : load resources
,D/jxcore_app_log( 6094): JniHelper::setJavaVM(0xb712f450), pthread_self() = -1217844224
,D/JX-Cordova( 6094): jxcore cordova android initializing
,I/SamsungIME( 1767): getCurrentKeyboard
I/SamsungIME( 1767): getTextKeyboard
,D/SamsungIME( 1767): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/libprocessgroup( 1018): failed to open /acct/uid_10101/pid_5156/cgroup.procs: No such file or directory
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/AcmsKeyStoreHelper( 6152):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 6152): Key Store exist
,I/AcmsKeyStoreHelper( 6152): Hence loading the keystore file
,I/DBG_POLICYDM( 5825): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5825): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5825): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5825): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5825): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5825): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5825): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/AcmsKeyStoreHelper( 6152):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 6152): getKeyStoreForApplication success 
D/AcmsCore( 6152): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 6152): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6152): Decrementing - Counter value: 1
D/AcmsCore( 6152): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 6152): This is NOT a valid MirrorLink app
D/AcmsCore( 6152): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 6152): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6152): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 6152): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 6152): getSvcCounter - Counter value: 0
,D/AcmsService( 6152): Enter onDestroy
I/AcmsService( 6152): cleanUp(): inside service clean up
,D/AcmsCore( 6152): AcmsCore: inside DeInit
,D/AcmsCore( 6152): AcmsCore: mLooperHandler is not null and making it null
,D/AcmsCertificateMngr( 6152): AcmsCertificateMngr: inside cleanup
,D/AcmsRevocationMngr( 6152): AcmsRevocationMngr: inside cleanup
,D/AcmsKeyStoreHelper( 6152): KeyStoreHelper: inside cleanup
,D/AcmsAppEntryInterface( 6152): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 6152): getSvcCounter - Counter value: 0
,D/AcmsService( 6152): killing acms process
I/Process ( 6152): Sending signal. PID: 6152 SIG: 9
,D/SamsungIME( 1767): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/ActivityManager( 1018): Process ACMS.Process (pid 6152)(adj 0) has died(43,1162)
,E/SMD     (  302): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/jxcore-log( 6094): Initializing JXcore engine
W/jxcore-log( 6094): JXcore engine is ready
,W/jxcore-log( 6094): Starting JXcore engine
,E/audit   ( 1914): type=1400 msg=audit(1452773836.191:205): avc:  denied  { ioctl } for  pid=6094 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1914):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1914): type=1300 msg=audit(1452773836.191:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=bebd4d58 items=0 ppid=319 ppcomm=main pid=6094 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1914): type=1320 msg=audit(1452773836.191:205): 
,W/jxcore-log( 6094): Platform android
W/jxcore-log( 6094): 
W/jxcore-log( 6094): Process ARCH arm
W/jxcore-log( 6094): 
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardViewMediator( 1175): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1175): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1175): *** Keyguard wallpaper service already unbounded
,I/jxcore-log( 6094): JXcore Cordova bridge is ready!
I/jxcore-log( 6094): 
,W/jxcore-log( 6094): JXcore engine is started
,I/chromium( 6094): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6094): Toggling radios to true
I/jxcore-log( 6094): 
,D/BluetoothAdapter( 6094): enable()
,D/BluetoothAdapter( 6094): enable(): BT is already enabled..!
,D/SecContentProvider( 1018): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1018): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1018): mCursor = null
,D/WifiService( 1018): setWifiEnabled: true pid=6094, uid=10155
,W/ActivityManager( 1018): Permission Denial: getCurrentUser() from pid=6094, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 1018): Failed getting userId using ActivityManagerNative
W/WifiService( 1018): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6094, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1018): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24778)
W/WifiService( 1018): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1018): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1018): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1018): 	at android.os.Binder.execTransact(Binder.java:461)
,D/SettingsProvider( 1018): name = wifi_on
,I/WifiService( 1018): disconnect: pid=6094, uid=10155
,I/wpa_supplicant( 2075): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 6094): Radios toggled
I/jxcore-log( 6094): 
,I/jxcore-log( 6094): My device name is: samsung-SM-A500FU
I/jxcore-log( 6094): 
,I/wpa_supplicant( 2075): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1,
I/wpa_supplicant( 2075): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 2075): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 2075): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 2075): wlan0: State: DISCONNECTED -> DISCONNECTED
E/wpa_supplicant( 2075): Cmd 35605 not handled
,E/WifiStateMachine( 1018): WifiStateMachine: Leaving Connected state
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 2075): reset timer : RESET_TIMER 0
I/wpa_supplicant( 2075): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2075): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2075): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 2075): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 2075): First Scan Start
I/wpa_supplicant( 2075): Scan requested (ret=0) - scan timeout 30 seconds
,D/Tethering( 1018): InitialState.processMessage what=4
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceStatusChanged wlan0, false
,E/Tethering( 1018): No numeric data
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
,V/NetworkStats( 1018): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1018): clearTetheredNotification()
,E/WifiNative-wlan0( 1018): do suspend true
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
D/HotspotTile( 1175): onReceive : android.net.conn.TETHER_STATE_CHANGED
,D/Tethering( 1018): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/HotspotTile( 1175): updateTetherState():false, false
,D/CommandListener(  278): Clearing all IP addresses on wlan0
,V/NetworkStats( 1018): performPollLocked() took 10ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,V/NativeCrypto( 1823): Read error: ssl=0xb7723810: I/O error during system call, Connection timed out
,E/ConnectivityService( 1018): updateNetworkInfo(),
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
E/WifiStateMachine( 1018): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 2075): wlan0: Setting scan request: 0 sec 0 usec
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14952 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,E/WifiNative-wlan0( 1018): do suspend true
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/ConnectivityService( 1018): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524292
D/ConnectivityService( 1018): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/WifiP2pService( 1018): InactiveState{ what=143375 }
D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
D/ConnectivityService( 1018): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/TelephonyNetworkFactory( 1466): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/CSLegacyTypeTracker( 1018): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 1018): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory( 1466): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/ConnectivityService( 1018): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): doQuit - quitNow()
D/ConnectivityManager.CallbackHandler( 2010): CM callback handler got msg 524292
,D/CommandListener(  278): Clearing all IP addresses on wlan0
,D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
,D/WifiNetworkAgent( 1018): NetworkAgent: NetworkAgent channel lost
,I/Hs20UtilService( 3559): Starting #8
,D/Tethering( 1018): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,D/Tethering( 1018): MasterInitialState.processMessage what=3
,D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,V/NetworkStats( 1018): updateIfacesLocked()
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,I/Hs20UtilService( 3559): Message received 5007
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked() took 4ms
D/StatusBar.NetworkController( 1175): EthernetConnected: false
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1175): updateDataNetType()
D/StatusBar.NetworkController( 1175): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1175): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1175): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,I/art     ( 1823): Explicit concurrent mark sweep GC freed 34805(2MB) AllocSpace objects, 14(224KB) LOS objects, 40% free, 12MB/21MB, paused 1.959ms total 98.402ms
,D/NearbySettings( 1368): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1368): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1368): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1368): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1368): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1368): MountReceiver.onReceive - Set preference state off
,V/NativeCrypto( 1823): SSL shutdown failed: ssl=0xb7723810: I/O error during system call, Broken pipe
,V/NearbySettings( 1368): MountReceiver.mPrefHandler - 7002
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3559): Starting #9
,I/Hs20UtilService( 3559): Message received 5007
,D/NearbySettings( 1368): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1368): DMSUtil.isNetworkConnected - flag-null, state-null
,I/PowerManagerService( 1018): [PWL] Off : 5s ago
,I/PowerManagerService( 1018): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1018): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1018, ws=null) (elapsedTime=96)
,I/NearbySettings( 1368): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1368): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1368): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1368): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1368): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0,
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6236 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,E/Zygote  ( 6236): MountEmulatedStorage()
E/Zygote  ( 6236): v2
I/libpersona( 6236): KNOX_SDCARD checking this for 10104
I/libpersona( 6236): KNOX_SDCARD not a persona
,I/SELinux ( 6236): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6236): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6236): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6236): TimaSignature is unavailable
,D/ActivityThread( 6236): Added TimaKeyStore provider
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
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
D/PhoneApp( 1466): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/ResourcesManager( 6236): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,D/PhoneApp( 1466): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,D/PhoneApp( 1466): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,D/PhoneApp( 1466): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
D/PhoneApp( 1466): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
D/PhoneApp( 1466): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1466): FileWriteThread : threadType = 3
,I/Babel   ( 6236): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6236): MmsConfig.loadMmsSettings
,I/Babel   ( 6236): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/Babel   ( 6236): MmsConfig.loadFromDatabase
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,E/Babel   ( 6236): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6236): MmsConfig.loadFromResources
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/Babel   ( 6236): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6236): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,W/Settings( 6236): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/ApplicationPolicy( 1018): updateDataUsageMap
,I/Babel_StickerModule( 6236): App launched.
,I/DBG_DM  ( 3093): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/DBG_DM  ( 3093): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,W/QCamera2Factory(  286): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  286): getCameraInfo: X
,W/QCamera2Factory(  286): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  286): getCameraInfo: X
,W/VideoCapabilities( 6236): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6236): Unsupported mime audio/evrc
,W/AudioCapabilities( 6236): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6236): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6236): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 6236): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6236): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6236): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6236): Unsupported mime audio/evrc
,W/VideoCapabilities( 6236): Unsupported mime video/wvc1
,W/VideoCapabilities( 6236): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6236): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6236): Unsupported mime video/wvc1
,W/VideoCapabilities( 6236): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6236): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6236): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6236): Unsupported mime video/mp43
,W/VideoCapabilities( 6236): Unsupported mime video/sorenson
,W/VideoCapabilities( 6236): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6236): Unsupported profile 4 for video/mp4v-es
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/ActivityManager( 1018): Killing 5690:com.google.android.gms:car/u0a12 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10012/pid_5690/cgroup.procs: No such file or directory
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
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/PCWCLIENTTRACE_PushUtil( 5776): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5776): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5776): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5776): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1018): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,I/splitIntent( 1018): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
I/PCWCLIENTTRACE_SYSTEMReceiver( 5776): noConnectivity : true
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6279 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6279): MountEmulatedStorage()
E/Zygote  ( 6279): v2
I/libpersona( 6279): KNOX_SDCARD checking this for 10111
I/libpersona( 6279): KNOX_SDCARD not a persona
,I/SELinux ( 6279): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,I/SELinux ( 6279): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6279): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6287): MountEmulatedStorage(),
I/libpersona( 6287): KNOX_SDCARD checking this for 10009
E/Zygote  ( 6287): v2
I/libpersona( 6287): KNOX_SDCARD not a persona
I/SELinux ( 6287): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6287): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6287): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6287 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast,
D/accuweather( 1729): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6279): TimaSignature is unavailable
,D/ActivityThread( 6279): Added TimaKeyStore provider
,E/Zygote  ( 6308): MountEmulatedStorage()
,E/Zygote  ( 6308): v2
I/libpersona( 6308): KNOX_SDCARD checking this for 10145
I/libpersona( 6308): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6308 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/SELinux ( 6308): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6308): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6308): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 9
D/TimaKeyStoreProvider( 6287): TimaSignature is unavailable
,D/ActivityThread( 6287): Added TimaKeyStore provider
,D/accuweather( 1729): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1729): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1729): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1729): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1729): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1729): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 6308): TimaSignature is unavailable
,D/ActivityThread( 6308): Added TimaKeyStore provider
,I/wpa_supplicant( 2075): nl80211: Received scan results (7 BSSes)
,I/libpersona( 6324): KNOX_SDCARD checking this for 10081
I/wpa_supplicant( 2075): wlan0: Setting scan request: 8 sec 0 usec
I/libpersona( 6324): KNOX_SDCARD not a persona
I/wpa_supplicant( 2075): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 2075): Trying to associate with  'G700'
I/wpa_supplicant( 2075): Re-associate with C0.AA.48
I/wpa_supplicant( 2075): wlan0: State: SCANNING -> ASSOCIATING
,I/wpa_supplicant( 2075): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
E/Zygote  ( 6324): MountEmulatedStorage()
E/Zygote  ( 6324): v2
I/SELinux ( 6324): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6324): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/WifiMonitor( 1018): didn't find BSSID Trying to associate with SSID 'NG700'
,E/SELinux ( 6324): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6324 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
,W/ResourcesManager( 6308): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6308): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6308): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ResourcesManager( 6308): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6308): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6324): TimaSignature is unavailable
,D/ActivityThread( 6324): Added TimaKeyStore provider
,E/wpa_supplicant( 2075): Cmd 35605 not handled
,I/wpa_supplicant( 2075): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 2075): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 2075): Associated with C0.AA.48
I/wpa_supplicant( 2075): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 2075): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 2075): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 2075): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 2075): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 2075): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 2075): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 2075): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2075): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2075): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 2075): Blacklist: Clear (temp) 
I/wpa_supplicant( 2075): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1018): mCursor = null
,I/MusicStore( 6279): Database version: 108
,D/WifiNative-wlan0( 1018): callSECApiVoid - ID [50]
,E/WifiConfigStore( 1018): setLastSelectedConfiguration -1
,D/ConnectivityService( 1018): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1018): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  278): Setting iface cfg
,E/WifiStateMachine( 1018): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1018): mCursor = null
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): interfaceStatusChanged wlan0, true
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, true
D/Tethering( 1018): interfaceStatusChanged wlan0, true
,E/Tethering( 1018): No numeric data
I/ActivityManager( 1018): Killing 5387:com.samsung.aasaservice/1000 (adj 15): empty #31
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1018): sendTetherStateChangedBroadcast 1, 0, 0
,V/NetworkStats( 1018): performPollLocked(flags=0x1)
,D/HotspotTile( 1175): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1175): updateTetherState():false, false
,D/Tethering( 1018): clearTetheredNotification()
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/SecContentProvider2( 1018): mCursor = null
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,E/WifiNative-wlan0( 1018): do suspend false
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,V/NetworkStats( 1018): performPollLocked() took 16ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,I/KLMS-2.5.183: ( 3618): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 14 13:17:18 GMT+01:00 2016
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/KLMS-2.5.183: ( 3618): KLMSAbstractReciever(): onReceive().END.
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/KLMS-2.5.183: ( 3618): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3618): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/Zygote  ( 6350): MountEmulatedStorage(),
E/Zygote  ( 6350): v2
I/libpersona( 6350): KNOX_SDCARD checking this for 10034,
I/libpersona( 6350): KNOX_SDCARD not a persona
,I/SELinux ( 6350): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6350): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6350): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6350 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,I/KLMS-2.5.183: ( 3618): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/TimaKeyStoreProvider( 6350): TimaSignature is unavailable
D/ActivityThread( 6350): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3618): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3618): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.183: ( 3618): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3618): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.183: ( 3618): KLMSIntentService(): onDestroy()
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5387/cgroup.procs: No such file or directory
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/SO_AGENT( 6350): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6279): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6279): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Zygote  ( 6371): MountEmulatedStorage()
,E/Zygote  ( 6371): v2
I/libpersona( 6371): KNOX_SDCARD checking this for 10113
I/libpersona( 6371): KNOX_SDCARD not a persona
,I/SELinux ( 6371): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6371): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6371): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6371 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  319): Explicit concurrent mark sweep GC freed 8738(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 28.775ms
,D/TimaKeyStoreProvider( 6371): TimaSignature is unavailable
,D/ActivityThread( 6371): Added TimaKeyStore provider
,E/dhcpcd  ( 6389): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,I/dhcpcd  ( 6389): version 5.5.6 starting
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 620us total 23.362ms
,E/dhcpcd  ( 6389): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 638us total 18.850ms,
,D/BadgeProvider( 5941): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/DBG_POLICYDM( 5825): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false,
,I/DBG_POLICYDM( 5825): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5825): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 5825): [com.policydm.XDMApplication(477/isNetworkChanged)] network not changed.... 
,E/SPPClientService( 5885): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,D/ActivityManager( 1018): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/SA      ( 6067): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ],
I/SA      ( 6067): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 6067): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6067): [SLFUCHKMGR] constructor called
,I/dhcpcd  ( 6389): wlan0: sending IPv6 Router Solicitation
,E/dhcpcd  ( 6389): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6389): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 6389): bssid match
D/RCPManagerService( 1018): exchangeData() failure , invalid userId
I/dhcpcd  ( 6389): wlan0: rebinding lease of 192.168.1.129
,D/Launcher.Model( 1482): reloadBadges entered.
,D/BadgeProvider( 5941): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5941): sendNotify, [notify] : null
D/BadgeProvider( 5941): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 5941): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5941): update, [UpdateCount] : 1
,E/SPPClientService( 5885): [[SystemStateMonitorService]] No Active Internet
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/SA      ( 6067): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6067): [OR] == isSIMCardReady false ==
,I/SA      ( 6067): [SCU] == networkStateCheck == false
,I/SA      ( 6067): [OR] onReceive END
,V/DownloadManager( 1228): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,V/JNIHelp ( 6279): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,W/art     ( 6308): Verification of void com.android.email.activity.MessageListItemOuterContainer.reverseSwiping() took 107.046ms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6400): MountEmulatedStorage()
E/Zygote  ( 6400): v2
I/libpersona( 6400): KNOX_SDCARD checking this for 1000
I/libpersona( 6400): KNOX_SDCARD not a persona
,I/SELinux ( 6400): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6400): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6400 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 5007:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,E/SELinux ( 6400): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6400): TimaSignature is unavailable
,D/ActivityThread( 6400): Added TimaKeyStore provider
,D/SecurityLogAgent( 6400): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6400): KnoxConfiguration : Current State Mapping Found 
,W/ActivityThread( 6279): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6279): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2e258386: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6279): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6279): GMSCore installation verified
D/SecurityLogAgent( 6400): StateMachine : Current State = 1
,D/SecurityLogAgent( 6400): StateMachine : Changed Current State = 1
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1018): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6418 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6418): MountEmulatedStorage()
E/Zygote  ( 6418): v2
I/libpersona( 6418): KNOX_SDCARD checking this for 10159
I/libpersona( 6418): KNOX_SDCARD not a persona
,I/SELinux ( 6418): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 69237(3MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 28MB/42MB, paused 2.830ms total 208.192ms
,I/SELinux ( 6418): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6418): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 4756:com.samsung.android.sm/1000 (adj 15): empty #31
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ConfigStore( 6279): Config Database version: 1
,I/ActivityManager( 1018): Killing 5426:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6418): TimaSignature is unavailable
,D/ActivityThread( 6418): Added TimaKeyStore provider
,E/SMD     (  302): DCD OFF
,I/iu.Environment( 2010): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,W/libprocessgroup( 1018): failed to open /acct/uid_10044/pid_5007/cgroup.procs: No such file or directory
,I/ActivityManager( 1018): Killing 5742:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6279): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_4756/cgroup.procs: No such file or directory
,I/iu.UploadsManager( 2010): num queued entries: 0
,I/iu.UploadsManager( 2010): num updated entries: 0
,I/iu.SyncManager( 2010): NEXT; no task
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6279): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6279): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/libprocessgroup( 1018): failed to open /acct/uid_10015/pid_5426/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10152/pid_5742/cgroup.procs: No such file or directory
,I/AudioService( 1018): getStreamVolume 3 index 0
,I/MediaRouter( 6279): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6279): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6371): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6371): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6371): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4323, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for charging
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,W/ContextImpl( 6371): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ActivityManager( 1018): Killing 5080:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6459): MountEmulatedStorage(),
I/libpersona( 6459): KNOX_SDCARD checking this for 10002
,E/Zygote  ( 6459): v2
I/libpersona( 6459): KNOX_SDCARD not a persona
I/SELinux ( 6459): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1018): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6459 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0,
W/ActivityManager( 1018): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 6459): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6459): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5080/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6459): TimaSignature is unavailable
,D/ActivityThread( 6459): Added TimaKeyStore provider
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 6279): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6279): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/GHttpClientFactory( 6279): Using the GMSCore's GoogleHttpClient
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/WebViewFactory( 6371): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,I/LibraryLoader( 6371): Time to load native libraries: 2 ms (timestamps 6073-6075)
,I/LibraryLoader( 6371): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6371): Binding Chromium to main looper Looper (main, tid 1) {4d3353f}
,I/LibraryLoader( 6371): Expected native library version number "",actual native library version number ""
,I/chromium( 6371): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6480): MountEmulatedStorage()
E/Zygote  ( 6480): v2
I/libpersona( 6480): KNOX_SDCARD checking this for 1000
I/libpersona( 6480): KNOX_SDCARD not a persona
,I/SELinux ( 6480): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/BrowserStartupController( 6371): Initializing chromium process, singleProcess=true,
,I/SELinux ( 6480): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1018): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6480 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
W/art     ( 6371): Attempt to remove local handle scope entry from IRT, ignoring
E/SELinux ( 6480): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/SysUtils( 6371): ApplicationContext is null in ApplicationStatus
I/dhcpcd  ( 6389): wlan0: acknowledged 192.168.1.129 from 192.168.1.1
,D/TimaKeyStoreProvider( 6480): TimaSignature is unavailable
,D/ActivityThread( 6480): Added TimaKeyStore provider
,W/chromium( 6371): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 6371): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,I/chromium( 6371): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,I/Adreno-EGL( 6371): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6371): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6371): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6371): Local Branch: 
I/Adreno-EGL( 6371): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6371): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6371):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/dhcpcd  ( 6389): wlan0: leased 192.168.1.129 for 86400 seconds,
,I/DIAGMON_AGENT( 6480): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/AudioManagerAndroid( 6371): Requires BLUETOOTH permission,
I/NSApplication( 6371): Starting up...
,I/DIAGMON_AGENT( 6480): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/ActivityManager( 1018): Killing 5807:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,I/DIAGMON_AGENT( 6480): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/ActivityManager( 1018): Killing 5792:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #32
,I/DIAGMON_AGENT( 6480): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6480): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6480): ./extraInfo: <unknown ssid>
,W/DIAGMON_AGENT( 6480): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,I/ActivityManager( 1018): Killing 5449:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6536): MountEmulatedStorage()
E/Zygote  ( 6536): v2
I/libpersona( 6536): KNOX_SDCARD checking this for 10125
I/libpersona( 6536): KNOX_SDCARD not a persona
,I/SELinux ( 6536): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6536): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1018): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6536 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux ( 6536): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 5482:com.sec.knox.bridge/1000 (adj 15): empty #31
,E/WifiNative-wlan0( 1018): do suspend true
,D/TimaKeyStoreProvider( 6536): TimaSignature is unavailable
,D/ActivityThread( 6536): Added TimaKeyStore provider
,W/libprocessgroup( 1018): failed to open /acct/uid_10156/pid_5807/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5792/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10032/pid_5449/cgroup.procs: No such file or directory
,W/ResourcesManager( 6536): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6536): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6536): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/WifiP2pService( 1018): InactiveState{ what=143375 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 1018): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
E/WifiStateMachine( 1018): VerifyingLinkState enter
,D/WifiNative-wlan0( 1018): callSECApiInt - ID [210]
D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/ConnectivityService( 1018): updateNetworkInfo()
,D/QuickConnect( 6536): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService( 1018): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,D/ConnectivityService( 1018): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1018): updateDnsLinkProperty: enter,
D/WifiWatchdogStateMachine.DnsPinger( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.DnsResolver( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.SingDnsChecker( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1018): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1018): Adding Route [fe80::/64 -> :: wlan0] to network 503,
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/QuickConnect( 6536): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1018): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,E/WifiStateMachine( 1018): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,D/ConnectivityService( 1018): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1018): Unexpected mtu value: 0, wlan0
D/ConnectivityService( 1018): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 1018): LTETest block dns file not exists
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,I/QuickConnect( 6536): PeriphStartReceiver.onReceive - no need to start
,E/WifiStateMachine( 1018): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1018): mBoosterFLAG : 0
I/WifiTrafficPoller( 1018): current booster mode : FullMode
,D/StatusBar.NetworkController( 1175): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiNative-wlan0( 1018): callSECApiVoid - ID [212]
,E/WifiStateMachine( 1018): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,I/splitIntent( 1018): Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1018): Killing 5536:com.android.vending/u0a28 (adj 15): empty #31
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
E/ConnectivityService( 1018): updateNetworkInfo()
E/ConnectivityService( 1018): updateNetworkInfo()
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1018): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): rematching NetworkAgentInfo [WIFI () - 503]
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Connected
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
,D/ConnectivityService( 1018):    accepting network in place of null
,D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/TelephonyNetworkFactory( 1466): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1466): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/CSLegacyTypeTracker( 1018): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/EnterpriseController(  278): uids 1000
D/CSLegacyTypeTracker( 1018): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 1000
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,D/ConnectivityService( 1018): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService( 1018): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 2010): CM callback handler got msg 524290
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524290
,D/Tethering( 1018): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1018): MasterInitialState.processMessage what=3
,V/NetworkStats( 1018): updateIfacesLocked()
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,D/StatusBar.NetworkController( 1175): EthernetConnected: false
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1175): updateDataNetType()
D/StatusBar.NetworkController( 1175): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1175): updateLTEICONDataNetType:0
,V/NetworkStats( 1018): performPollLocked() took 4ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/StatusBar.NetworkController( 1175): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3559): Starting #10
,I/Hs20UtilService( 3559): Message received 5007
D/NearbySettings( 1368): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1368): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1368): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,I/NearbySettings( 1368): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1368): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1368): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3559): Starting #11
,I/Hs20UtilService( 3559): Message received 5007
,D/NearbySettings( 1368): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1368): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1368): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/Hs20UtilService( 3559): Starting #12
I/Hs20UtilService( 3559): Message received 5007
,V/NearbySettings( 1368): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1368): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1368): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1368): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1368): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3559): Starting #13
,I/Hs20UtilService( 3559): Message received 5007
,I/System.out( 1018): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/NearbySettings( 1368): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1368): MountReceiver.onReceive - Keep current state
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
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 14 Jan 2016 12:17:20 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452773840094], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452773840076]}
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Validated
,D/ConnectivityService( 1018): Validated NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1018): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1018): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524290
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/ConnectivityManager.CallbackHandler( 2010): CM callback handler got msg 524290
,I/SurfaceFlinger(  258): id=15 createSurf (1x1),1 flag=4, Uoast
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_5482/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10028/pid_5536/cgroup.procs: No such file or directory
,D/PowerManagerService( 1018): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018
,D/SRIB_DCS( 1175): log_dcs ThreadedRenderer::initialize entered! 
,D/StatusBar.NetworkController( 1175): EthernetConnected: false
,D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1175): getUpdateDataNetType(): mDataTypeBrand = LTE
,D/StatusBar.NetworkController( 1175): updateDataNetType()
D/StatusBar.NetworkController( 1175): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1175): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1175): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3093): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/NetworkMonitor( 6279): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil( 5776): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5776): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5776): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5776): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1018): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
I/splitIntent( 1018): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,V/MusicLeanback( 6279): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/accuweather( 1729): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/FOTA_Client( 6287): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
,I/FOTA_Client( 6287): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,D/accuweather( 1729): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1729): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1729): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
I/FOTA_Client( 6287): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,W/FOTA_Client( 6287): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,D/SecurityLogAgent( 6400): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6400): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6400): StateMachine : Current State = 1
,D/SecurityLogAgent( 6400): StateMachine : Changed Current State = 1
,D/accuweather( 1729): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1729): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/DIAGMON_AGENT( 6480): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6480): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6480): ./extraInfo: "NG700"
I/DIAGMON_AGENT( 6480): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,I/KLMS-2.5.183: ( 3618): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 14 13:17:20 GMT+01:00 2016
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/WaitQueueForNetworkActivate( 5857): notifyNetworkActivated
,I/KLMS-2.5.183: ( 3618): KLMSAbstractReciever(): onReceive().END.
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.183: ( 3618): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3618): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3618): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3618): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3618): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,D/QuickConnect( 6536): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6536): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 6536): PeriphStartReceiver.onReceive - no need to start
,I/KLMS-2.5.183: ( 3618): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
W/ContextImpl( 5857): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/DBG_POLICYDM( 5825): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 5825): [com.policydm.XDMApplication(469/isNetworkChanged)] a previous network is 0, current network is 2
E/DBG_POLICYDM( 5825): [com.policydm.XDMApplication(471/isNetworkChanged)] network changed.... 
,I/KLMS-2.5.183: ( 3618): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.183: ( 3618): NetworkChangeOperations(): uploadRequestLog().START 
,E/SPPClientService( 5885): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6067): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 6067): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6067): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6067): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 6067): [OR] == isSIMCardReady false ==
,I/SA      ( 6067): [SCU] == networkStateCheck == true
,I/SA      ( 6067): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6067): isChinaCountryCode : false
I/SA      ( 6067): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6067): [OR] == networkStateCheck true ==
,I/SA      ( 6067): [OR] GetMyCountryZoneTask
,I/SA      ( 6067): [OR] onReceive END
,I/KLMS-2.5.183: ( 3618): NetworkChangeOperations(): uploadRequestLog().END 
,V/DownloadManager( 1228): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,I/KLMS-2.5.183: ( 3618): StateImplV2(): networkChangeListener().END
,D/ActivityManager( 1018): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/SA      ( 6067): [SRS] prepareGetMyCountryZone
,I/KLMS-2.5.183: ( 3618): KLMSIntentService(): onDestroy()
,D/SecContentProvider2( 1018): uri = 15 selection = getAppBlockDownloadState
,D/SecContentProvider2( 1018): mCursor = null
,I/DBG_POLICYDM( 5825): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5825): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/SA      ( 6067): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6067): [SSP] query invoked
I/DBG_POLICYDM( 5825): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5825): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5825): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5825): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5825): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5825): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/SA      ( 6067): [TPMU] GetMccFromDB : null
,E/DBG_POLICYDM( 5825): [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,I/SA      ( 6067): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6067): [TPM] isNoProxy(default) : true
,E/File    ( 6067): fail readDirectory() errno=2
,I/DBG_POLICYDM( 5825): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/ActivityManager( 1018): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5857): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5857): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5857): exit::IDLE
D/InitializeManagerStateMachine( 5857): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5857): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5857): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5857): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5857): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5857): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5857): entry::SUCCESS
D/hcjo    ( 5857): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/iu.Environment( 2010): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2010): num queued entries: 0
,I/iu.UploadsManager( 2010): num updated entries: 0
,I/iu.SyncManager( 2010): NEXT; no task
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
D/hcjo    ( 5857): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5857): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/InitializeManagerStateMachine( 5857): exit::SUCCESS
D/InitializeManagerStateMachine( 5857): entry::IDLE
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1018): Queue : backgroundsplit_2 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10012
,D/ConnectivityService( 1018): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,I/SA      ( 6067): [RC New] Execute method=[GET] start
,I/SA      ( 6067): [RC New] Security=[true]
,I/System.out( 6067): Thread-1050(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6067): Thread-1050(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6067): Thread-1050(ApacheHTTPLog):isShipBuild true
,I/System.out( 6067): Thread-1050(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6067): Thread-1050(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController(  278): uids 10041
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10041
,D/ConnectivityService( 1018): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524295
,D/ConnectivityService( 1018): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1175): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 2010): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 2010): CM callback handler got msg 524295
,I/SA      ( 6067): [RC New] [v2liruge] api execute + 627
,I/SA      ( 6067): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6067): AsyncTask #1 calls detatch()
,I/SA      ( 6067): [ODM] saveOpenData( GEO_IP, PL )
,I/SA      ( 6067): [OCP] update openData : PL
,I/SA      ( 6067): [TPMU] getNetworkMcc : 
,I/SA      ( 6067): [SCU] saveMccToPreferece Start
,I/SA      ( 6067): [SCU] RegionMCC : 260
I/SA      ( 6067): [SSP] query invoked
,I/SA      ( 6067): [TPMU] GetMccFromDB : null
,I/SA      ( 6067): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6067): [SCU] saveMccToPreferece End
,I/SA      ( 6067): [RC New] executeRequest [v2liruge] end. 690
I/SA      ( 6067): [RC New] Execute end
,I/SA      ( 6067): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6067): [OR] GetMyCountryZoneTask Success
,E/SMD     (  302): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,D/PackageManager( 1018): [MSG] MCS_UNBIND
,I/ActivityManager( 1018): Killing 5752:com.android.mms/u0a46 (adj 15): empty #31
,D/CountryDetector( 1018): No listener is left
,D/SSRM:n  ( 1018): SIOP:: AP = 340
,W/libprocessgroup( 1018): failed to open /acct/uid_10046/pid_5752/cgroup.procs: No such file or directory
,I/dhcpcd  ( 6389): wlan0: sending IPv6 Router Solicitation
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): Do not check CP during LCD off.
,I/SurfaceFlinger(  258): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger(  258): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 1018): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1018) eventTime = 90195
,D/PowerManagerService( 1018): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018 (0x0)
,D/PowerManagerService( 1018): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1018, ws=WorkSource{10054}) (elapsedTime=3473)
,D/ActivityManager( 1018): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/GAV4    ( 6371): Thread[GAThread,5,main]: No campaign data found.
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1823): callingUid 10012, callindPid: 1823
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/MusicLeanback( 6279): Conditions not met for autocaching.
I/MusicLeanback( 6279): Stop autocaching.
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/GmsUtils( 6279): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 6279): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/SMD     (  302): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :8
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5776): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5776): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5776): [GetString-S]
,I/ReactiveServiceManager( 5776): Supported : 1
,D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1018): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1018): QSEECom_shutdown_app, app_id = 11
,E/terrier ( 1018): handleString: Failed to handle string(-4)
E/terrier ( 1018): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 5776): getString is null
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5776): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5776): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5776): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5776): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5776): [ensureRegistration] - No Samsung account
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6596): MountEmulatedStorage(),
E/Zygote  ( 6596): v2
I/libpersona( 6596): KNOX_SDCARD checking this for 10028
I/libpersona( 6596): KNOX_SDCARD not a persona,
I/ActivityManager( 1018): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6596 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6596): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/SELinux ( 6596): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6596): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: android, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,I/BackgroundCompactionService( 1018): onStart. jobID=801
,I/BackgroundCompactionService( 1018): onStart done. jobID=801
,I/BackgroundCompactionService( 1018): Execute BGCompaction (type1). (0 times)
,I/BackgroundCompactionService( 1018): compact_memory command done
,D/TimaKeyStoreProvider( 6596): TimaSignature is unavailable
,D/ActivityThread( 6596): Added TimaKeyStore provider
,D/Finsky  ( 6596): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{3d8d6e23 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/Finsky  ( 6596): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6596): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6596): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 6596): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6596): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 6596): Skipping gmscore version check
,D/Finsky  ( 6596): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1018): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 6596): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/dhcpcd  ( 6389): wlan0: sending IPv6 Router Solicitation
,D/Finsky  ( 6596): [1155] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6596): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager( 1018): Killing 5961:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,W/libprocessgroup( 1018): failed to open /acct/uid_10047/pid_5961/cgroup.procs: No such file or directory
,I/PowerManagerService( 1018): [PWL] Off : 15s ago
,E/SMD     (  302): DCD OFF
,I/jxcore-log( 6094): Test app app.js loaded
I/jxcore-log( 6094): 
,I/chromium( 6094): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/LightsService( 1018): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1018) 
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
D/BatteryService( 1018): turn on LED for fully charged
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
,E/lights  ( 1018): write_int failed to open -1
,D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecContentProvider2( 1018): uri = 14 selection = getSealedState
D/SecContentProvider2( 1018): mCursor = null
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId -1 pkgname com.android.systemui
,I/ValidateNoPeople( 1018): skipping global notification
D/WindowManager( 1018): showStatusBarByNotification() mOpenByNotification=false
,D/PowerManagerService( 1018): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1175
,I/PowerManagerService( 1018): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification (14)
,I/PowerManagerService( 1018): Waking up from sleep (uid 10054)...
V/KeyguardServiceDelegate( 1018): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@31652667)
,D/PowerManagerService( 1018): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 1018): [s] UserActivityState : 0 -> 1
D/PowerManagerService( 1018): [PWL] sb acquire: PowerManagerService.Display
,I/DisplayPowerController( 1018): Blocking screen on until initial contents have been drawn.
,D/WindowOrientationListener( 1018): sensor enabled
D/KeyguardViewMediator( 1175): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1175): notifyScreenOnLocked
I/Sensors ( 1018): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1018): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1018): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SensorService( 1018): [SO] changed settle time [1]
D/SensorService( 1018): [SO] setDelay [66000000]
,I/libsuspend( 1018): !@autosuspend_wakeup_count_disable
I/libsuspend( 1018): !@autosuspend_wakeup_count_disable done
D/DisplayManagerService( 1018): !@display_state: OFF -> ON
D/SensorService( 1018): [SO] activate (ident=0xb7b7f410, enabled=1)
D/SensorService( 1018): [SO] AR_init
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SurfaceFlinger(  258): Set power mode=2, type=0 flinger=0xb820d690
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 2 on display: 0
,E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
,I/DisplayManagerService( 1018): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
,V/ActivityManager( 1018): Display changed displayId=0
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SensorManager( 1018): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,D/KeyguardViewMediator( 1175): handleNotifyScreenOn
,D/StatusBarKeyguardViewManager( 1175): onScreenTurnedOn()
,D/SecKeyguardClockSingleView( 1175): onScreenTurnedOn
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
,I/PalmMotion( 1018): [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
I/PalmMotion( 1018): [PALM] SURFACE_PALM_SWIPE: 1
D/PalmMotion( 1018): [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
E/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/PalmMotion( 1018): [PALM] ACCEPTED : [default] PALM_CNT : 3, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRM:a  ( 1018): DeviceInfo:: 000000000000
D/SSRM:a  ( 1018): SettingsAirViewInfo:: 000000000
,D/NfcService( 1448): call the applyRouting
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,D/SensorService( 1018): [SO] currT = 96210125535, prevT = 78320091011, diff = 17890034524, [0.096 0.096 10.094]
,D/SensorService( 1018): [SO] Reset Rotation Old [100], Init [1]
D/SamsungIME( 1767): showDlgMsgBox : false true true
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,D/KnoxNotification( 1175): ----- inflateViews : modified publicViewLocal -----
,D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 1018) 
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService( 1018): turn off LED
,D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
,D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
E/lights  ( 1018): write_led_info failed to open -1
,W/System.err( 1018): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,E/SmartFaceService( 1018): onReceive: android.intent.action.SCREEN_ON
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/SmartFaceService( 1018): fail to set sysfs 1
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150),
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
W/System.err( 1018): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
W/System.err( 1018): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 1018): 	,at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1018): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1018): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1018): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186),
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1018): ,	... 10 more
,D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 2 on display 0
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 1
E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
D/KnoxNotification( 1175): ----- inflateViews : modified KnoxViewLocal -----
D/PowerManagerService( 1018): Excessive delay in !@display_state: ON: 120ms
D/SurfaceControl( 1018): Excessive delay in setPowerMode(): 119ms,
D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event1/device/enabled: 1
D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event3/device/enabled: 1
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1175): PersonaID is invalid or persona doesn't exists. : -1
,D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1175): Icon Only
D/StatusBarKeyguardViewManager( 1175): callback.onShown()
I/StatusBar( 1175): Icon Only
D/DisplayPowerController( 1018): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
D/PanelView( 1175): There is/are notification(s) 
I/DisplayPowerController( 1018): Unblocked screen on after 145 ms
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
D/DisplayPowerState( 1018): !@ ColorFade exit
D/StatusBar.NetworkController( 1175): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/BatteryMeterView( 1175): onDraw batteryColor : -1
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
V/KeyguardServiceDelegate( 1018): **** SHOWN CALLED ****
D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:d,rawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
I/SurfaceFlinger(  258): id=12 Removed DolorFade (8/8)
,I/SurfaceFlinger(  258): id=12 Removed DolorFade (-2/8)
,E/libEGL  ( 1018): call to OpenGL ES API with no current context (logged once per thread)
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 5 -> 5
D/lights  ( 1018): lcd : 5 +
D/DisplayPowerController( 1018): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/SensorService( 1018): [SO] currT = 96280105379, prevT = 78320091011, diff = 17960014368, [0.077 0.077 10.056]
D/SensorService( 1018): [SO] 0.077 0.077 10.056
D/SensorService( 1018): [SO] [100 -> 255]
,D/InputMethodManagerService( 1018): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,V/UserPresentBroadcastReceiver( 1823): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_SCREEN_ON
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,D/lights  ( 1018): lcd : 5 -
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1018): animation target = 5, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1018): SecHardwareInterface.setBatteryADC : true
,I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/MotionRecognitionService( 1018):  handler : SCREEN_ON end
,I/Timeline( 6094): Timeline: Activity_idle id: android.os.BinderProxy@2937d64d time:96309
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/NotificationService( 1018): ACTION_SCREEN_ON
D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event3/device/enabled: 1
,D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/WifiNative-wlan0( 1018): do suspend false
,D/audio_hw_primary(  286): adev_set_parameters: enter: screen_state=on
,V/voice   (  286): voice_set_parameters: enter: screen_state=on
V/voice   (  286): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  286): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  286): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  286): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  286): adev_set_parameters: exit
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/wpa_supplicant( 2075): reset timer : RESET_TIMER 1
I/wpa_supplicant( 2075): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 2075): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 2075): Scan requested (ret=0) - scan timeout 30 seconds
,D/IpRemoteDisplayController( 1018): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 1018): Bridge Server is not available
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/PersonaManagerService( 1018): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 1018): MSG_ACTION_SCREEN_ON called
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
,I/NfcService( 1448): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/accuweather( 1729): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1729): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/NfcService( 1448): call the applyRouting
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1729): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event1/device/enabled: 1
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 1018): Excessive delay in MISC setInteractive(true) while turning screen on: 159ms
I/QCOM PowerHAL( 1018): Got set_interactive hint
,D/PowerManagerService( 1018): Excessive delay in nativeSetInteractive(true): 162ms
,D/accuweather( 1729): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/lights  ( 1018): button : 1 +
D/accuweather( 1729): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 1729): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 13 17,
D/PowerManagerService( 1018): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 288ms
,D/ActivityManager( 1018): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,I/SamsungIME( 1767): getNextShiftState() cursorCapsMode : 0
,D/lights  ( 1018): button : 1 -
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PowerManagerService( 1018): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:n  ( 1018): SIOP:: AP = 330
,D/daemonapp( 1301): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1301): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1301): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1301): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1301): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1301): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1301): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1301): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1301): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1301): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1301): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1452795360000
D/daemonapp( 1301): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1452773849940
,D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1301): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1301): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1301): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1301): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1301): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,I/BatteryStatsDumper( 1018): In refreshStats isReason Screen ON/OFF: true
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
,I/BatteryStatsDumper( 1018): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1018): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1018): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1018): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1018): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1018): Previous Battery Level: 100 Current Level: 100 Delta: 0
,I/BatteryStatsDumper( 1018): Writing to database completed
,D/SSRM:a  ( 1018): DeviceInfo:: 000000000000
,D/SSRM:a  ( 1018): SettingsAirViewInfo:: 000000000
,D/ActivityManager( 1018): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5857): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5857): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5857): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5857): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,I/dhcpcd  ( 6389): wlan0: sending IPv6 Router Solicitation,
I/dhcpcd  ( 6389): wlan0: no IPv6 Routers available
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  302): DCD OFF
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 72573(4MB) AllocSpace objects, 13(684KB) LOS objects, 33% free, 28MB/42MB, paused 2.495ms total 167.479ms
,D/hcjo    ( 5857): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/PreloadUpdateManagerStateMachine( 5857): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5857): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5857): entry::IDLE
,D/lights  ( 1018): button : 0 +
,D/lights  ( 1018): button : 0 -
,I/wpa_supplicant( 2075): nl80211: Received scan results (4 BSSes)
,D/WifiP2pService( 1018): InactiveState{ what=147461 }
,D/WifiP2pService( 1018): P2pEnabledState{ what=147461 }
,D/WifiP2pService( 1018): DefaultState{ what=147461 }
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SensorService( 1018): [SO] 0.077 0.096 10.036
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  302): DCD OFF
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  302): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 257, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1175): Icon Only
,I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
,D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate,
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/SSRM:n  ( 1018): SIOP:: AP = 310
,E/SMD     (  302): DCD OFF,
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/Watchdog( 1018): !@Sync 3
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/Atfwd_Sendcmd(  330): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  330): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): [checkCaptivePortal] - callbackHandler=Handler (com.android.server.wifi.WifiWatchdogStateMachine$CaptivePortalHandler) {10d1e9c5}
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  302): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): start check captive portal 
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1018): result = 0, mCaptivePortalCheckMode = 11, mCouldNotIdentifyCaptivePortalState = true
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SensorService( 1018): [SO] 0.077 0.077 10.036
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1823): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1823): Vacuum at: now=1452773865314 tag=VacuumService
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeConfigurator( 1823): Scheduling Phenotype for one-off execution 468 seconds from now (1452773865725)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1823): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeFlagCommitter( 1823): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1823): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 1018): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1823): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  278): uids 10012
D/EnterpriseController(  278): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  278): getNetworkForDns: using netid 503 for uid 10012
,E/SMD     (  302): DCD OFF
,I/System.out( 1823): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 1823): Tagging socket 88 with tag 3000120100000000{805310977,0} for uid -1, pid: 1823, getuid(): 10012
,I/qtaguid ( 1823): Tagging socket 91 with tag 3000120100000000{805310977,0} for uid -1, pid: 1823, getuid(): 10012
,D/LocationManagerService( 1018): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1823): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1823): Tagging socket 88 with tag 3000120100000000{805310977,0} for uid -1, pid: 1823, getuid(): 10012
,D/LocationManagerService( 1018): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1823): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1823): Tagging socket 88 with tag 3000120100000000{805310977,0} for uid -1, pid: 1823, getuid(): 10012
,D/LocationManagerService( 1018): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1823): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1823): Tagging socket 88 with tag 3000120100000000{805310977,0} for uid -1, pid: 1823, getuid(): 10012
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ServiceManager(  330): Waiting for service AtCmdFwd...,
,D/FactoryTest( 5367): Not factory mode
,D/FactoryTest( 5367): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 5367): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5367): still no open session command from host, so toast
W/ContextImpl( 5367): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5367): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,I/Timeline( 5367): Timeline: Activity_launch_request id:com.android.settings time:113777
,E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1018): mDVFSHelper.acquire()
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings,
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 6094
,E/MTPRx   ( 5367): started activity for popup
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,V/ActivityManager( 1018): Display changed displayId=0
,W/ResourcesManager( 5367): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 5367): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5367): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5367): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5367): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5367): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 5367): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.android.settings
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/InputDispatcher( 1018): Focused application set to: xxxx
,D/InputDispatcher( 1018): Focus entered window: 6094
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1018): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@15dc4512 attribute=null, token = android.os.BinderProxy@3ac718a5
,E/ActivityManager( 1018): Invalid thumbnail dimensions: 650x650
,D/SettingsReceiverActivity( 5367): dev.kiessupport is : TRUE
,D/PhoneWindow( 5367): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5367): *FMB* installDecor flags : 8388610
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
,D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,I/Timeline( 6094): Timeline: Activity_idle id: android.os.BinderProxy@2937d64d time:113974
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  302): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PowerManagerService( 1018): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10054 pid=1175 (0x0)
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2624): Disconnected process message: 10,
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 1018): SIOP:: AP = 310
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1018): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/SMD     (  302): DCD OFF,
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PowerManagerService( 1018): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 1 -> 1
D/DisplayPowerController( 1018): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 1 -> 1
,D/lights  ( 1018): lcd : 1 +
,D/DisplayPowerController( 1018): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1018): lcd : 1 -
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 1 -> 1
,D/DisplayPowerController( 1018): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
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
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SensorService( 1018): [SO] 0.077 0.077 10.036
,E/SMD     (  302): DCD OFF
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  302): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/PowerManagerService( 1018): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 1018): Nap time (uid 1000)...
D/PowerManagerService( 1018): handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
I/PowerManagerService( 1018): !@[ps] Screen__Off - 1 :  dream(timeout) (2)
I/PowerManagerService( 1018): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService( 1018): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 1018): SecHardwareInterface.setBatteryADC : false
,V/WindowOrientationListener( 1018): WindowOrientationListener disabled
D/SensorService( 1018): [SO] activate (ident=0xb7b7f410, enabled=0)
D/PowerManagerService( 1018): handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/PowerManagerService( 1018): handleSandman : startDream(true)
E/PowerManagerService( 1018): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 1018): Sleeping (uid 1000)...
D/PowerManagerService( 1018): [s] UserActivityState : 4 -> 0
,I/SurfaceFlinger(  258): id=16 createSurf (720x1280),-1 flag=20004, DolorFade
,D/SensorManager( 1018): unregisterListener ::   
,D/KeyguardViewMediator( 1175): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1175): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1175): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1175): notifyScreenOffLocked
,D/KeyguardViewMediator( 1175): timeout : 5000
,V/ActivityThread( 6094): updateVisibility : ActivityRecord{9674e13 token=android.os.BinderProxy@2937d64d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PowerManagerService( 1018): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 38ms
,D/LightsService( 1018): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1018) 
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1018): write_int failed to open -1
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService( 1018): turn on LED for fully charged
,D/KeyguardViewMediator( 1175): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1175): handleNotifyScreenOff
D/VolumePanel( 1175): onScreenTurnedOff()
D/VolumePanel( 1175): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,W/System.err( 1018): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,E/SmartFaceService( 1018): onReceive: android.intent.action.SCREEN_OFF
,W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/SmartFaceService( 1018): fail to set sysfs 0
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
D/VolumePanel( 1175): mCoverBroadcastReceiver: Screen OFF end
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
W/System.err( 1018): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
W/System.err( 1018): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
,W/System.err( 1018): 	at android.os.Handler.handleCallback(Handler.java:739)
D/PowerManagerService( 1018): Excessive delay in ColorFade : initGLShaders: 13ms
W/System.err( 1018): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 1018): ,	at android.os.Looper.loop(Looper.java:145)
W/System.err( 1018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 1018): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1018): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1018): 	... 10 more
D/SecKeyguardClockSingleView( 1175): onScreenTurnedOff
D/DisplayPowerController( 1018): ColorFade: onAnimationStart
D/DisplayPowerController( 1018): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
,I/StatusBar( 1175): Icon Only
,D/PanelView( 1175): There is/are notification(s) 
,D/MotionRecognitionService( 1018):   mReceiver.onReceive : ACTION_SCREEN_OFF
E/MotionRecognitionService( 1018):  handler : SCREEN_OFF end 
,D/NotificationService( 1018): ACTION_SCREEN_OFF
D/LightsService( 1018): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1018) 
,D/LightsService( 1018): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService( 1018): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1018): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/WifiNative-wlan0( 1018): do suspend true
,D/audio_hw_primary(  286): adev_set_parameters: enter: screen_state=off
V/voice   (  286): voice_set_parameters: enter: screen_state=off
V/voice   (  286): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  286): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  286): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  286): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  286): adev_set_parameters: exit
,I/BackgroundCompactionService( 1018): Schedule Type1 BGCompaction
,D/IpRemoteDisplayController( 1018): intent received android.intent.action.SCREEN_OFF,
D/IpRemoteDisplayController( 1018): Bridge Server is not available
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/PersonaManagerService( 1018): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 1018): MSG_ACTION_SCREEN_OFF called
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,V/EmergencyMode( 1420): [EmergencyStateReceiver] binteractive [false] why[3]
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/NfcService( 1448): call the applyRouting
,D/accuweather( 1729): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1729): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/accuweather( 1729): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1729): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1729): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,E/LibSecureUISvc( 1946): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,D/daemonapp( 1301): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SSRM:n  ( 1018): SIOP:: AP = 300
,D/PowerManagerService( 1018): [PWL] sb release: PowerManagerService.Broadcasts
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1729): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1729): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1729): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 1729): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1729): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/DisplayPowerState( 1018): !@ ColorFade entry
,D/DisplayPowerController( 1018): ColorFade: onAnimationEnd
,D/lights  ( 1018): lcd : 0 +
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 0 -> 0
,D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
,D/lights  ( 1018): lcd : 0 -
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1018): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1018): [PWL] sb release: PowerManagerService.Display
,D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,D/MISC PowerHAL( 1018): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1018): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1018): Got set_interactive hint
,D/DisplayManagerService( 1018): !@display_state: ON -> OFF
,I/DisplayManagerService( 1018): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SurfaceFlinger(  258): Set power mode=0, type=0 flinger=0xb820d690
D/qdhwcomposer(  258): hwc_setPowerMode: Setting mode 0 on display: 0
,V/ActivityManager( 1018): Display changed displayId=0
,E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
,E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
,I/BatteryStatsDumper( 1018): In refreshStats isReason Screen ON/OFF: true
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
,D/StatusBar.NetworkController( 1175): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1175): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
I/rmt_storage(  269): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb84c77c8
I/rmt_storage(  269): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
D/StatusBar.NetworkController( 1175): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1175): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/rmt_storage(  269): wakelock acquired: 1, error no: 42
D/StatusBar.NetworkController( 1175): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1202948808)
,I/BatteryStatsDumper( 1018): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1018): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1018): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1018): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1018): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1018): Previous Battery Level: 100 Current Level: 100 Delta: 0
,I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1202948808) wakelock released: 1, error no: 0
I/rmt_storage(  269): 
,I/rmt_storage(  269): rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb84c77c8
,V/AlarmManager( 1018): waitForAlarm result :8
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/qdhwcomposer(  258): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  258): hwc_setPowerMode: Done setting mode 0 on display 0
,D/SurfaceControl( 1018): Excessive delay in setPowerMode(): 256ms
E/qdutils (  258): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  258): int qdutils::getHDMINode(): Failed to find HDMI node
,D/PowerManagerService( 1018): Excessive delay in !@display_state: OFF: 258ms
I/libsuspend( 1018): !@autosuspend_wakeup_count_enable
I/libsuspend( 1018): !@autosuspend_wakeup_count_enable done
D/PowerManagerService( 1018): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 266ms
,I/PowerManagerService( 1018): [PWL] Off : 0s ago
I/PowerManagerService( 1018): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 1018): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 1018): [PWL]       PARTIAL_WAKE_LOCK              'SmartManager Framework Thread' (uid=1000, pid=1018, ws=null) (elapsedTime=243)
,I/BatteryStatsDumper( 1018): Writing to database completed
,E/SMD     (  302): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  302): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,V/AlarmManager( 1018): ___SyncScheduler (v3) ACTIVATED___
,D/KeyguardViewMediator( 1175): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/KeyguardViewMediator( 1175): doKeyguard: not showing because lockscreen is off
V/AlarmManagerEXT( 1018): <AppSync3 Whitelist>
V/KeyguardEffectViewController( 1175): *** Keyguard wallpaper service already unbounded
V/AlarmManagerEXT( 1018): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/PowerManagerService( 1018): [PWL] Off : 5s ago
,E/SMD     (  302): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1018): waitForAlarm result :8
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 255, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/SSRM:n  ( 1018): SIOP:: AP = 290
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  302): DCD OFF
,E/Watchdog( 1018): !@Sync 4
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,V/AlarmManager( 1018): waitForAlarm result :8
,E/SMD     (  302): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...,
,I/PowerManagerService( 1018): [PWL] Off : 15s ago
,E/SMD     (  302): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  302): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10,
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  302): DCD OFF
,E/SMD     (  302): DCD OFF
,E/SMD     (  302): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 1018): waitForAlarm result :4
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: android, action: null
,D/ActivityManager( 1018): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,I/BackgroundCompactionService( 1018): onStart. jobID=801
,I/BackgroundCompactionService( 1018): onStart done. jobID=801
,I/BackgroundCompactionService( 1018): Execute BGCompaction (type1). (1 times)
,I/BackgroundCompactionService( 1018): compact_memory command done
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 254, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 1018): [PWL] Off : 30s ago
,E/SMD     (  302): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  302): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...,
,I/ServiceManager(  330): Waiting for service AtCmdFwd...,
,E/SMD     (  302): DCD OFF
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 4
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 253, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 1018): stay LED for fully charged
,I/MotionRecognitionService( 1018): Plugged
,I/MotionRecognitionService( 1018): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
,V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  302): DCD OFF
,E/Watchdog( 1018): !@Sync 5,
,E/SMD     (  302): DCD OFF
,E/SMD     (  302): DCD OFF
,E/SMD     (  302): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1018): SIOP:: AP = 270
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 1018): [PWL] Off : 50s ago
,E/SMD     (  302): DCD OFF,
,E/SMD     (  302): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  302): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,V/AlarmManager( 1018): waitForAlarm result :8,
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  302): DCD OFF
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  302): DCD OFF
,E/SMD     (  302): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  302): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 6
,E/SMD     (  302): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 75s ago
,E/SMD     (  302): DCD OFF
,E/SMD     (  302): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  302): DCD OFF
,E/SMD     (  302): DCD OFF,
,I/Atfwd_Sendcmd(  330): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  330): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  302): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ClearcutLoggerApiImpl( 1823): disconnect managed GoogleApiClient
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!,
D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 252, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): stay LED for fully charged
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1175): handleBatteryUpdate
V/EmergencyMode( 1420): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1420): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2624): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2624): Disconnected process message: 10
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1175): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  302): DCD OFF
,E/SMD     (  302): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...,
,E/SMD     (  302): DCD OFF,
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,E/SMD     (  302): DCD OFF
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/Watchdog( 1018): !@Sync 7
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  302): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 105s ago
,E/SMD     (  302): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  302): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  302): DCD OFF
,E/SMD     (  302): DCD OFF
,E/SMD     (  302): DCD OFF
,V/AlarmManager( 1018): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1175): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1175): handleTimeUpdate
,D/SecKeyguardClockView( 1175): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1175): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1175): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1175): *** don't update sliding image ***
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1175): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/AlarmManager( 1018): waitForAlarm result :8
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  302): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...,
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  302): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 3,
,E/SMD     (  302): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  302): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 8
,E/SMD     (  302): DCD OFF
,E/SMD     (  302): DCD OFF,
,E/SMD     (  302): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 140s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  302): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  302): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  302): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 1018): SIOP:: AP = 260,
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  302): DCD OFF
,E/SMD     (  302): DCD OFF
,E/SMD     (  302): DCD OFF,
,E/SMD     (  302): DCD OFF
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 9
,E/SMD     (  302): DCD OFF
,E/SMD     (  302): DCD OFF
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,E/SMD     (  302): DCD OFF
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,I/ServiceManager(  330): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  330): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  302): DCD OFF
,E/SMD     (  302): DCD OFF
,E/SMD     (  302): DCD OFF
,I/PowerManagerService( 1018): [PWL] Off : 180s ago
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  302): DCD OFF
,E/SMD     (  302): DCD OFF
,E/SMD     (  302): DCD OFF
,D/TimaService( 1018): TIMA: TimaService scheduler is intialized. 
D/TimaService( 1018): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 1018): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 1018): initializing...
I/TLC_TIMA_PKM_initialize( 1018): root = /firmware/image, root_strlen = 15
I/TLC_TIMA_PKM_initialize( 1018): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1018): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1018): process = tima_pkm, process_strlen = 8
I/TZ: qc_tlc_communication( 1018): aligned max_sendmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1018): aligned max_recvmsg_size = 262208 = 0x40040
I/TZ: qc_tlc_communication( 1018): max_message_size = 524416 = 0x80080
D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x80080
D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 12
,I/TZ: qc_tlc_communication( 1018): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize( 1018): Trustlet response is completed
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  302): DCD OFF
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 1018): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 1018): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 1018): SIOP:: AP = 260
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1018): !@Sync 10
,E/SMD     (  302): DCD OFF
,I/jxcore-log( 6094): --= Surplus to requirements =--
I/jxcore-log( 6094): 
,I/jxcore-log( 6094): ****TEST TOOK:  ms ****
I/jxcore-log( 6094): 
I/jxcore-log( 6094): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6094): 
,E/SMD     (  302): DCD OFF
,D/AndroidRuntime( 6776): 
D/AndroidRuntime( 6776): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6776): CheckJNI is OFF
,D/AndroidRuntime( 6776): readGMSProperty: start
D/AndroidRuntime( 6776): readGMSProperty: already setted!!
D/AndroidRuntime( 6776): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6776): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6776): readGMSProperty: end
D/AndroidRuntime( 6776): addProductProperty: start
,E/AffinityControl( 6776): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6776): Calling main entry com.android.commands.pm.Pm
,D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 1018): START PACKAGE DELETE: observer{840543552}
D/PackageManager( 1018): pkg{<packageName>}
D/PackageManager( 1018): user{0}
D/PackageManager( 1018): caller{2000}
D/PackageManager( 1018): flags{3}
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
,D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager( 1018): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/PackageManager( 1018): !@killApplicatoin: 10155, uninstall pkg
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled :  enabled true
,I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,I/ActivityManager( 1018): Killing 6094:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
,I/SurfaceFlinger(  258): id=14 Removed NainActivit (6/8)
,I/WindowState( 1018): WIN DEATH: Window{24e5f47a u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger(  258): id=14 Removed NainActivit (-2/8)
,D/InputDispatcher( 1018): Focus left window: 6094
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,I/ActivityManager( 1018):   Force finishing activity ActivityRecord{2bd5e537 u0 com.test.thalitest/.MainActivity t8}
,W/ActivityManager( 1018): mDVFSHelper.acquire()
,V/ActivityManager( 1018): Display changed displayId=0
,W/ActivityManager( 1018): Spurious death for ProcessRecord{27387479 6094:com.test.thalitest/u0a155}, curProc for 6094: null
,I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,I/ActivityManager( 1018):   Force finishing activity ActivityRecord{2bd5e537 u0 com.test.thalitest/.MainActivity t8 f}
W/ActivityManager( 1018): Duplicate finish request for ActivityRecord{2bd5e537 u0 com.test.thalitest/.MainActivity t8 f}
,W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
,D/InputDispatcher( 1018): Focused application released
,I/DBG_DM  ( 3093): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,I/DBG_DM  ( 3093): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 14
,I/DBG_DM  ( 3093): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/DBG_DM  ( 3093): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/art     ( 5620): Explicit concurrent mark sweep GC freed 2390(140KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 767us total 52.228ms
,I/DBG_DM  ( 3093): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 14
,I/DBG_DM  ( 3093): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,E/SamsungIME( 1767): mOCRHelper is null
,I/art     ( 6023): Explicit concurrent mark sweep GC freed 274(21KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 717us total 69.425ms
,W/GeofencerStateMachine( 1823): Ignoring removeGeofence because network location is disabled.
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,I/DBG_DM  ( 3093): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,D/RegisteredComponentCache( 1448): Collect Tech packages for Knox
D/PersonaManager( 1448): isKioskContainerExistOnDevice
,I/DBG_DM  ( 3093): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 3093): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/KLMS-2.5.183: ( 3618): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jan 14 13:21:16 GMT+01:00 2016
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3618): KLMSAbstractReciever(): onReceive().END.
,I/art     ( 2010): Explicit concurrent mark sweep GC freed 35340(2MB) AllocSpace objects, 7(112KB) LOS objects, 24% free, 13MB/18MB, paused 1.337ms total 140.897ms
,I/splitIntent( 1018): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
I/splitIntent( 1018): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
W/SQLiteConnectionPool( 2010): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,E/Zygote  ( 6789): MountEmulatedStorage(),
E/Zygote  ( 6789): v2
I/libpersona( 6789): KNOX_SDCARD checking this for 10094
,I/libpersona( 6789): KNOX_SDCARD not a persona
,I/DBG_DM  ( 3093): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 14
,I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6789 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6789): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/DBG_DM  ( 3093): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
I/SELinux ( 6789): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6789): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3093): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3093): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3093): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] ,
,I/DBG_DM  ( 3093): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false],
E/Zygote  ( 6798): MountEmulatedStorage()
E/Zygote  ( 6798): v2
I/libpersona( 6798): KNOX_SDCARD checking this for 10044,
I/libpersona( 6798): KNOX_SDCARD not a persona
I/SELinux ( 6798): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6798): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6798): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6798 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
I/KLMS-2.5.183: ( 3618): KLMSIntentService(): onCreate()
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3618): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 84409(5MB) AllocSpace objects, 98(3MB) LOS objects, 33% free, 29MB/44MB, paused 3.016ms total 210.619ms
D/TimaKeyStoreProvider( 6789): TimaSignature is unavailable
,D/ActivityThread( 6789): Added TimaKeyStore provider
,I/art     ( 1018): WaitForGcToComplete blocked for 200.231ms for cause Explicit
,E/Zygote  ( 6816): MountEmulatedStorage()
I/libpersona( 6816): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6816): v2
I/libpersona( 6816): KNOX_SDCARD not a persona
,I/SELinux ( 6816): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6816): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6816): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3618): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/ActivityManager( 1018): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=6816 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
I/DBG_DM  ( 3093): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,I/KLMS-2.5.183: ( 3618): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/SurfaceFlinger(  258): id=17 createSurf (720x1280),1 flag=404, YUIInstallC
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,D/TimaKeyStoreProvider( 6798): TimaSignature is unavailable
,D/ActivityThread( 6798): Added TimaKeyStore provider
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/KLMS-2.5.183: ( 3618): KLMSIntentService(): PACKAGE_REMOVED
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
,E/Zygote  ( 6834): MountEmulatedStorage()
,E/Zygote  ( 6834): v2
I/libpersona( 6834): KNOX_SDCARD checking this for 10149
I/libpersona( 6834): KNOX_SDCARD not a persona
,I/SELinux ( 6834): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6834 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 6834): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6834): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3618): KLMSIntentService(): listeningToPackageRemoved().START
,I/Atfwd_Sendcmd(  330): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  330): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/KLMS-2.5.183: ( 3618): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/TimaKeyStoreProvider( 6816): TimaSignature is unavailable
,D/ActivityThread( 6816): Added TimaKeyStore provider
,D/InputDispatcher( 1018): Focus entered window: 3093
,D/SRIB_DCS( 3093): log_dcs ThreadedRenderer::initialize entered! 
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/TimaKeyStoreProvider( 6834): TimaSignature is unavailable
,D/ActivityThread( 6834): Added TimaKeyStore provider
D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
,D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
,W/TextServicesManagerService( 1018): no available spell checker services found
,V/ActivityThread( 3093): updateVisibility : ActivityRecord{22f83fb6 token=android.os.BinderProxy@7003bc5 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ResourcesManager( 6798): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6798): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6798): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6798): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6798): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6798): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6798): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6798): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 1018): Got RemoteException sending setActive(false) notification to pid 6094 uid 10155
,I/Timeline( 3093): Timeline: Activity_idle id: android.os.BinderProxy@7003bc5 time:323779
,D/SamsungIME( 1767): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PersonaManager( 1448): isKioskContainerExistOnDevice
,I/KLMS-2.5.183: ( 3618): KLMSIntentService(): listeningToPackageRemoved().END
,D/RegisteredServicesCache( 1448): empty dynamic service
,W/ActivityManager( 1018): mDVFSHelper.release()
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{fee264a u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t7} time:323809
,D/elm:15183( 6789): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1018): mCursor = null
,W/ResourcesManager( 6816): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/elm:15183( 6789): ELMEngine.ELMEngine( context ).
,I/KLMS-2.5.183: ( 3618): KLMSIntentService(): onDestroy()
,D/elm:15183( 6789): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1018): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15183( 6789): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/elm:15183( 6789): ElmAgentService : onCreate()
D/elm:15183( 6789): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15183( 6789): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6789): MDMBridge.getInstance()
D/elm:15183( 6789): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  ( 6853): MountEmulatedStorage()
E/Zygote  ( 6853): v2
I/libpersona( 6853): KNOX_SDCARD checking this for 1000
I/libpersona( 6853): KNOX_SDCARD not a persona
,I/SELinux ( 6853): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6853): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1018): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=6853 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SELinux ( 6853): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:15183( 6789): MDMBridge.getAllLicenseInfoFromSDK()
I/art     (  319): Explicit concurrent mark sweep GC freed 8724(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 646us total 23.498ms
,D/TimaKeyStoreProvider( 6853): TimaSignature is unavailable
,D/ActivityThread( 6853): Added TimaKeyStore provider
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 608us total 17.208ms
,D/ThemeInfoUtil( 6834): getCurrentFestivalName is [null]
,D/ThemeInfoUtil( 6834): isCurrentFestival = false
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,I/art     (  319): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 630us total 17.688ms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1018): PackageReceiver onReceive()
I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,I/OTPFW   ( 1018): PackageRemovalReceiver::onReceive Enter
D/OTPFW   ( 1018): OtpDbHelper::getInstance New instance created
,D/OTPFW   ( 1018): DBIntegrity::getInstance - New instance created
,D/OTPFW   ( 1018): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,I/OTPFW   ( 1018): ProvisionData::getAllEntries Enter
E/Zygote  ( 6870): MountEmulatedStorage()
E/Zygote  ( 6870): v2
I/libpersona( 6870): KNOX_SDCARD checking this for 10152
I/libpersona( 6870): KNOX_SDCARD not a persona
E/OTPFW   ( 1018): ProvisionData::getAllEntries Table is empty
I/SELinux ( 6870): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6870 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 5984:com.wsomacp/u0a25 (adj 15): empty #31
D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/SELinux ( 6870): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6870): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/JobSchedulerService( 1018): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10155
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10155
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
V/AlarmManagerEXT( 1018): com.test.thalitest(10155) is removed.
,I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/elm:15183( 6789): ElmAgentService : onDestroy().
,I/ActivityManager( 1018): Killing 6001:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
E/SQLiteLog( 6816): (284) automatic index on crash_info_summary(package_name_touched)
D/TaskPersister( 1018): removeObsoleteFile: deleting file=8_task.xml
D/TaskPersister( 1018): removeObsoleteFile: deleting file=7_task.xml
D/TaskPersister( 1018): removeObsoleteFile: deleting file=8_task_thumbnail.png
,D/AASAservice-UpdateReceiver( 6853): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,W/System.err( 6853): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,W/System.err( 6853): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
W/System.err( 6853): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 6853): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 6853): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 6853): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 6853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6853): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6853): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 6853): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6853): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6853): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6853): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/TimaKeyStoreProvider( 6870): TimaSignature is unavailable
,D/ActivityThread( 6870): Added TimaKeyStore provider
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,I/art     ( 6816): Explicit concurrent mark sweep GC freed 8898(423KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 953us total 37.421ms
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 15836(826KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 29MB/44MB, paused 23.477ms total 402.359ms
,D/BadgeProvider( 5941): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5941): sendNotify, [notify] : null
D/BadgeProvider( 5941): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5941): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5941): update, [UpdateCount] : 1
,D/StatusBar( 1175): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1175): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1175): Icon Only
I/StatusBar( 1175): Icon Only
D/PanelView( 1175): There is/are notification(s) 
D/PanelView( 1175): kidsfalse mQsExpansionEnabled:true
,I/PCWCLIENTTRACE_PushUtil( 5776): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5776): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5776): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5776): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6889): MountEmulatedStorage()
E/Zygote  ( 6889): v2
I/libpersona( 6889): KNOX_SDCARD checking this for 1000
I/libpersona( 6889): KNOX_SDCARD not a persona
,I/SELinux ( 6889): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6889): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6889): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6889 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 6023:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/PanelView( 1175): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,E/Zygote  ( 6904): MountEmulatedStorage()
I/libpersona( 6904): KNOX_SDCARD checking this for 10032
E/Zygote  ( 6904): v2
I/libpersona( 6904): KNOX_SDCARD not a persona
I/SELinux ( 6904): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,E/SQLiteLog( 6870): (284) automatic index on shooting_modes(title_id)
,I/ActivityManager( 1018): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6904 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
D/TimaKeyStoreProvider( 6889): TimaSignature is unavailable
I/ActivityManager( 1018): Killing 5919:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,D/ActivityThread( 6889): Added TimaKeyStore provider
,I/SELinux ( 6904): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6904): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/NearbySource( 6798): Nearby Source Create!
,D/NearbyContext( 6798): Nearby Context Create!
,W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/TimaKeyStoreProvider( 6904): TimaSignature is unavailable
,D/ActivityThread( 6904): Added TimaKeyStore provider
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6920): MountEmulatedStorage()
I/libpersona( 6920): KNOX_SDCARD checking this for 10156
E/Zygote  ( 6920): v2
I/libpersona( 6920): KNOX_SDCARD not a persona
,I/SELinux ( 6920): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6920): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6920): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=6920 uid=10156 gids={50156, 9997} abi=armeabi-v7a
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager( 1018): delete codoeFile: 
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,I/AASA_removePackage( 1018): UID=10155 Target=com.test.thalitest
D/AASAuninstall( 1018): userId = 0, info.removedAppID = -1, info.uid = 10155, packageName = com.test.thalitest
,W/ContextImpl( 6798): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 6798): Samsung link source created
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager( 1018): result of delete: 1{840543552}
,D/TimaKeyStoreProvider( 6920): TimaSignature is unavailable
,D/ActivityThread( 6920): Added TimaKeyStore provider
,I/ActivityManager( 1018): Killing 5841:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,D/AndroidRuntime( 6776): Shutting down VM
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ContextImpl( 6889): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6936): MountEmulatedStorage(),
I/libpersona( 6936): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6936): v2
,I/libpersona( 6936): KNOX_SDCARD not a persona
I/SELinux ( 6936): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/TapandpayWidget:TapandpayAppWidgetProvider( 6920): onReceive()
D/TapandpayWidget:TapandpayAppWidgetProvider( 6920): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10,
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 6936): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 6936): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/TapandpayWidget:Utils( 6920): Clear T&P info.
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/TapandpayWidget:TapandpayAppWidgetProvider( 6920): Widget is not attached.
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1018): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6936 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 6936): TimaSignature is unavailable
,D/ActivityThread( 6936): Added TimaKeyStore provider
,D/UsbSettingsManager( 1018): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1018): onPackageRemoved : com.test.thalitest
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,W/libprocessgroup( 1018): failed to open /acct/uid_10025/pid_5984/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10053/pid_6001/cgroup.procs: No such file or directory
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1018): failed to open /acct/uid_10057/pid_6023/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10038/pid_5919/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10091/pid_5841/cgroup.procs: No such file or directory
,I/FeatureConfig( 6904): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,W/ResourcesManager( 6936): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 6954): MountEmulatedStorage()
E/Zygote  ( 6954): v2
I/libpersona( 6954): KNOX_SDCARD checking this for 10160
I/libpersona( 6954): KNOX_SDCARD not a persona
,I/SELinux ( 6954): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6954): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,I/ActivityManager( 1018): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=6954 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,E/SELinux ( 6954): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1018): Killing 6112:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,W/ResourcesManager( 6904): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6904): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/ActivityManager( 1018): Killing 6134:com.samsung.helphub/1000 (adj 15): empty #31
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
W/ResourcesManager( 6904): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 6904): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/RCPManager( 6936):  in createShortcut() for packageName: com.test.thalitest userId0
,D/TimaKeyStoreProvider( 6954): TimaSignature is unavailable
,D/ActivityThread( 6954): Added TimaKeyStore provider
,D/RCPManagerService( 1018):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1018): queryAllProviders():  providerCallBack is not register for 0
,E/Zygote  ( 6971): MountEmulatedStorage(),
E/Zygote  ( 6971): v2
I/libpersona( 6971): KNOX_SDCARD checking this for 10035
I/libpersona( 6971): KNOX_SDCARD not a persona,
I/SELinux ( 6971): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6971): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6971): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,W/ResourcesManager( 6904): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager( 1018): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6971 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 6308:com.android.email/u0a145 (adj 15): empty #31
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6904): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 6971): TimaSignature is unavailable
,D/ActivityThread( 6971): Added TimaKeyStore provider
,E/Zygote  ( 6986): MountEmulatedStorage()
I/libpersona( 6986): KNOX_SDCARD checking this for 10091
E/Zygote  ( 6986): v2
I/libpersona( 6986): KNOX_SDCARD not a persona
,I/SELinux ( 6986): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6986): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6986): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6986 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 6459:com.sec.android.cloudagent/u0a2 (adj 15): empty #31
,W/ResourcesManager( 6904): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 6904): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/ResourcesManager( 6954): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
D/ContactProvider( 6798): getAllContactInfoList Start
W/art     ( 6776): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/PackagesMonitor( 6798): PackagesMonitor onReceive :com.test.thalitest
,D/TimaKeyStoreProvider( 6986): TimaSignature is unavailable
D/ActivityThread( 6986): Added TimaKeyStore provider
,W/ResourcesManager( 6904): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6904): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/libprocessgroup( 1018): failed to open /acct/uid_10100/pid_6112/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_6134/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10145/pid_6308/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10002/pid_6459/cgroup.procs: No such file or directory
,D/ContactProvider( 6798): getAllContactInfoList End
,I/syncContacts( 6798): thread: 1148, sync time = 134
,W/ResourcesManager( 6904): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/SPPClientService( 6971): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6971): [PushClientApplication] Push log off : This is Ship build version
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6904): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6904): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/Zygote  ( 7005): MountEmulatedStorage()
E/Zygote  ( 7005): v2
I/libpersona( 7005): KNOX_SDCARD checking this for 10038
I/libpersona( 7005): KNOX_SDCARD not a persona
I/SELinux ( 7005): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1018): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=7005 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 7005): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1018): Killing 6400:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
E/SELinux ( 7005): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/SPPClientService( 6971): PushLog.txt file is not deleted.
D/SPPClientService( 6971): PushLog.txt file is not deleted.
D/SPPClientService( 6971): ============PushLog. stop!
,E/SQLiteLog( 6816): (284) automatic index on crash_info_summary(package_name_touched)
,D/Launcher.Model( 1482): reloadBadges entered.
,E/PhotosPlugin( 6986): Loading PhotosPlugin
,E/Zygote  ( 7018): MountEmulatedStorage()
E/Zygote  ( 7018): v2
I/libpersona( 7018): KNOX_SDCARD checking this for 10046
I/libpersona( 7018): KNOX_SDCARD not a persona
,W/ResourcesManager( 6904): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/ActivityManager( 1018): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=7018 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a,
D/[0]UMC:UMCContentProvider( 6954): @onCreate
,I/ActivityManager( 1018): Killing 6480:com.sec.android.diagmonagent/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 7005): TimaSignature is unavailable
D/ActivityThread( 7005): Added TimaKeyStore provider
,W/ResourcesManager( 6904): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6904): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/[0]UMC:Core( 6954): onCreate(): 
D/[0]UMC:Core( 6954): @isManagedProfileUser
D/[0]UMC:Core( 6954): userId: 0
,D/[0]UMC:Core( 6954): userInfo: UserInfo{0:Thali Test:13}
,D/[0]UMC:Core( 6954): userInfo.isManagedProfile() : false
,W/GalaxyFinderApplication( 6904): system/finder_cp/cpdata.xml file not found
,W/ResourcesManager( 7005): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7005): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/SELinux ( 7018): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 7018): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7018): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/BadgeProvider( 5941): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 5941): sendNotify, [notify] : null
D/BadgeProvider( 5941): update, [uri] : content://com.sec.badge/apps
,D/Launcher.Model( 1482): reloadBadges entered.
,D/BadgeProvider( 5941): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 5941): update, [UpdateCount] : 1
,D/[0]UMC:DeviceInfo( 6954): USA==US==
,D/TimaKeyStoreProvider( 7018): TimaSignature is unavailable
,D/ActivityThread( 7018): Added TimaKeyStore provider
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_6400/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_6480/cgroup.procs: No such file or directory
,W/ResourcesManager( 7018): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7018): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 7018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7018): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 7018): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/SQLiteLog( 7005): (28) failed to open "/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 7005): Failed to open database '/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db'.
E/SQLiteDatabase( 7005): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7005): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7005): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 7005): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 7005): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7005): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7005): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7005): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 7005): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 7005): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 7005): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 7005): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 7005): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7005): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7005): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:471)
E/SQLiteDatabase( 7005): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/SQLiteDatabase( 7005): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/SQLiteDatabase( 7005): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/SQLiteDatabase( 7005): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/SQLiteDatabase( 7005): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/SQLiteDatabase( 7005): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/SQLiteDatabase( 7005): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/SQLiteDatabase( 7005): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7005): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 7005): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/SQLiteDatabase( 7005): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 7005): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 7005): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 7005): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/Mms/MmsApp( 7018): [start]    onCreate() consume time = 0.0
D/AndroidRuntime( 7005): Shutting down VM
,E/AndroidRuntime( 7005): FATAL EXCEPTION: main
E/AndroidRuntime( 7005): Process: com.samsung.android.sdk.samsunglink, PID: 7005
,E/AndroidRuntime( 7005): java.lang.RuntimeException: Unable to get provider com.mfluent.asp.datamodel.ASPMediaStoreProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7005): 	,at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
E/AndroidRuntime( 7005): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
E/AndroidRuntime( 7005): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
E/AndroidRuntime( 7005): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
E/AndroidRuntime( 7005): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
E/AndroidRuntime( 7005): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7005): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 7005): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
E/AndroidRuntime( 7005): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 7005): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 7005): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/AndroidRuntime( 7005): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/AndroidRuntime( 7005): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7005): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7005): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 7005): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 7005): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7005): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7005): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7005): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/AndroidRuntime( 7005): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/AndroidRuntime( 7005): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/AndroidRuntime( 7005): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/AndroidRuntime( 7005): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 7005): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 7005): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 7005): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:471)
E/AndroidRuntime( 7005): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
E/AndroidRuntime( 7005): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
E/AndroidRuntime( 7005): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
E/AndroidRuntime( 7005): 	... 11 more
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.samsung.android.sdk.samsunglink
,E/DropBoxManagerService( 1018): Can't write: system_app_crash
E/DropBoxManagerService( 1018): java.io.FileNotFoundException: /data/system/dropbox/drop182.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService( 1018): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService( 1018): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService( 1018): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService( 1018): 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15989)
E/DropBoxManagerService( 1018): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 1018): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 1018): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService( 1018): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService( 1018): 	... 5 more
,I/Process ( 7005): Sending signal. PID: 7005 SIG: 9
,I/SA      ( 6067): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 6067): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10155 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,I/ActivityManager( 1018): Killing 6418:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,D/ActivityManager( 1018): startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,E/lowmemorykiller(  255): Error writing /proc/7005/oom_score_adj; errno=22
,D/ActivityManager( 1018): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder

```
