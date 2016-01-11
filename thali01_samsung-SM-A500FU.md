#### Test 5497026186051be_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/PermissionCache(  256): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1168 us)
I/DBG_POLICYDM( 5870): [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
--------- beginning of system
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
D/KeyguardViewMediator( 1178): setting alarm to turn off keyguard, seq = 1
D/KeyguardViewMediator( 1178): handleNotifyScreenOff
D/VolumePanel( 1178): onScreenTurnedOff()
D/VolumePanel( 1178): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/VolumePanel( 1178): mCoverBroadcastReceiver: Screen OFF end
D/Mms/MmsConfig( 5800): Load Resize quality : 80
D/SecKeyguardClockSingleView( 1178): onScreenTurnedOff
E/SmartFaceService( 1016): onReceive: android.intent.action.SCREEN_ON
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
D/PowerManagerService( 1016): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 30ms
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/EasySignUpManager_1.0.1( 5800): serviceId : 1, features : -1
W/System.err( 1016): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:456)
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
W/System.err( 1016): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 1016): 	at libcore.io.Posix.open(Native Method)
W/System.err( 1016): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/System.err( 1016): 	... 10 more
E/Zygote  ( 5939): MountEmulatedStorage()
E/Zygote  ( 5939): v2
I/SELinux ( 5939): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5939): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5939): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
E/SmartFaceService( 1016): fail to set sysfs 1
I/libpersona( 5939): KNOX_SDCARD checking this for 10035
I/libpersona( 5939): KNOX_SDCARD not a persona
D/EasySignUpManager_1.0.1( 5800): isAuth is false
D/Mms/MmsConfig( 5800): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
I/ActivityManager( 1016): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=5939 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/DBG_POLICYDM( 5870): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
D/TP/MmsSmsProvider( 1461): query,matched:2117, calling pid = 5800
I/DBG_POLICYDM( 5870): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
D/TP/MmsSmsProvider( 1461): match 2117:Elapsed time : 3.587 ms
D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
D/InputMethodManagerService( 1016): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
I/DBG_POLICYDM( 5870): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
D/PowerManagerService( 1016): Excessive delay in ColorFade : initGLShaders: 66ms
I/DBG_POLICYDM( 5870): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
D/PowerManagerService( 1016): Excessive delay in ColorFade prepare: 171ms
D/DisplayPowerController( 1016): ColorFade: onAnimationStart
I/DBG_POLICYDM( 5870): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 5 -> 5
D/DisplayPowerController( 1016): performScreenOffTransition : no brightness animation
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/MotionRecognitionService( 1016):   mReceiver.onReceive : ACTION_SCREEN_ON
D/TimaKeyStoreProvider( 5939): TimaSignature is unavailable
D/ActivityThread( 5939): Added TimaKeyStore provider
D/EasySignUpManager_1.0.1( 5800): isAuth is false
D/EasySignUpManager_1.0.1( 5800): getServiceStatus : serviceId (1) is OFF
E/MotionRecognitionService( 1016):  handler : SCREEN_ON end
E/CscParser( 5800): mps_code.dat does not exist
E/CscParser( 5800): customer_path =/system/csc/customer.xml
E/CscParser( 5800): fileName + /system/csc/customer.xml
E/PhotosPlugin( 5885): Loading PhotosPlugin
D/NotificationService( 1016): ACTION_SCREEN_ON
D/LightsService( 1016): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1016) 
D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
E/WifiNative-wlan0( 1016): do suspend false
D/audio_hw_primary(  281): adev_set_parameters: enter: screen_state=on
V/voice   (  281): voice_set_parameters: enter: screen_state=on
V/voice   (  281): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  281): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  281): platform_set_parameters: exit with code(-2)
I/wpa_supplicant( 2074): reset timer : RESET_TIMER 1
D/audio_hw_hfp(  281): audio_extn_hfp_set_parameters: enter
I/wpa_supplicant( 2074): wlan0: Setting scan request: 0 sec 0 usec
V/audio_hw_primary(  281): adev_set_parameters: exit
I/wpa_supplicant( 2074): P2P: Current p2p state = IDLE
I/wpa_supplicant( 2074): Scan requested (ret=0) - scan timeout 30 seconds
E/CscParser( 5800): mps_code.dat does not exist
E/CscParser( 5800): customer_path =/system/csc/customer.xml
E/CscParser( 5800): fileName + /system/csc/customer.xml
D/IpRemoteDisplayController( 1016): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 1016): Bridge Server is not available
I/DBG_POLICYDM( 5870): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
D/CscParser( 5800): getInstance fileName =/system/csc/customer.xml
D/GpsLocationProvider( 1016): receive broadcast intent, action: android.intent.action.SCREEN_ON
D/PersonaManagerService( 1016): ACTION_SCREEN_ON onReceive
D/PersonaManagerServiceHandler( 1016): MSG_ACTION_SCREEN_ON called
D/Mms/MmsConfig( 5800):  enable multiwindow = true
D/CoverManagerWhiteLists( 1016): isAllowedToUse : SIGNATURE_MATCH
I/NfcService( 1440): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
E/Mms/MessageUtils( 5800): setCountryDetector : update country detector info 
E/Mms/MessageUtils( 5800): updateCountryIso : update country iso info 
D/NfcService( 1440): call the applyRouting
D/Mms/MmsConfig( 5800): [end]    init() consume time = 246.685781
D/Mms/Contact( 5800): [start]    init() consume time = 3.347708
D/accuweather( 1706): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
D/accuweather( 1706): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1706): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/accuweather( 1706): [KK AccuPhone]>>> UIM:282 [0:0] update clock event, is not screen on!!
D/ActivityManager( 1016): startService callerProcessName:com.sec.android.widgetapp.ap.hero.accuweather, calleePkgName: com.sec.android.widgetapp.ap.hero.accuweather
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
I/DBG_POLICYDM( 5870): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
I/SamsungIME( 1786): getNextShiftState() cursorCapsMode : 0
I/DBG_POLICYDM( 5870): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
I/DBG_POLICYDM( 5870): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
I/DBG_POLICYDM( 5870): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
I/DBG_POLICYDM( 5870): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
D/Mms/Contact( 5800): [end]    init consume time = 29.360834
D/TP/MmsSmsProvider( 1461): query,matched:13, calling pid = 5800
I/DBG_POLICYDM( 5870): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
D/TP/MmsSmsProvider( 1461): match 13:Elapsed time : 2.459 ms
I/DBG_POLICYDM( 5870): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/01/18/12:08:32
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
E/SPPClientService( 5939): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 5939): [PushClientApplication] Push log off : This is Ship build version
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 5870): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/01/11/12:28:44
I/DBG_POLICYDM( 5870): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/DBG_POLICYDM( 5870): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
I/DBG_POLICYDM( 5870): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
D/Mms/DraftCache( 5800): [start]    rebuildCache consume time = 44.872291
I/DBG_POLICYDM( 5870): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
I/DBG_POLICYDM( 5870): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
I/DBG_POLICYDM( 5870): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
I/DBG_POLICYDM( 5870): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
I/DBG_POLICYDM( 5870): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
E/Zygote  ( 5967): MountEmulatedStorage()
E/Zygote  ( 5967): v2
I/libpersona( 5967): KNOX_SDCARD checking this for 10038
I/libpersona( 5967): KNOX_SDCARD not a persona
D/SPPClientService( 5939): PushLog.txt file is not deleted.
D/SPPClientService( 5939): PushLog.txt file is not deleted.
D/SPPClientService( 5939): ============PushLog. stop!
I/DBG_POLICYDM( 5870): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
I/SELinux ( 5967): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/DBG_POLICYDM( 5870): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
D/Mms/MethodReflector( 5800): getSubId is called
D/Mms/TelephonyUtils( 5800): getLongSubId from simSlot 0, return Value = -1
I/SELinux ( 5967): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5967): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
D/Mms/MethodReflector( 5800): getTelephonyProperty is called
I/ActivityManager( 1016): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=5967 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
D/Mms/DownloadManager( 5800): roaming -> false (slotId = 0)
I/ActivityManager( 1016): Killing 5364:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
D/Mms/DownloadManager( 5800): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5800): auto download without roaming -> true
D/Mms/DownloadManager( 5800): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/MethodReflector( 5800): getSubId is called
D/Mms/MethodReflector( 5800): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 5800): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 5800): getLongSubId from simSlot 1, return Value = -1000
D/Mms/MethodReflector( 5800): getTelephonyProperty is called
D/Mms/DownloadManager( 5800): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 5800): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 5800): auto download without roaming -> true
D/Mms/DownloadManager( 5800): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 5800): auto download during roaming secondary -> false
D/Mms/DownloadManager( 5800): mAutoDownload ------> true
D/DisplayPowerState( 1016): !@ ColorFade entry
I/DBG_POLICYDM( 5870): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
D/DisplayPowerController( 1016): ColorFade: onAnimationEnd
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1016): performScreenOffTransition : no brightness animation
D/TP/MmsSmsProvider( 1461): query,matched:12, calling pid = 5800
D/lights  ( 1016): lcd : 0 +
D/TimaKeyStoreProvider( 5967): TimaSignature is unavailable
D/ActivityThread( 5967): Added TimaKeyStore provider
D/TP/MmsSmsProvider( 1461): match 12:Elapsed time : 7.311 ms
D/lights  ( 1016): lcd : 0 -
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 0 -> 0
D/DisplayPowerController( 1016): performScreenOffTransition : no brightness animation
D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 1016): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/input/event1/device/enabled: 0
D/Mms/DraftCache( 5800): [end]    rebuildCache consume time = 81.873594
D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/input/event3/device/enabled: 0
D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/input/event3/device/enabled: 0
D/MISC PowerHAL( 1016): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 1016): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
I/QCOM PowerHAL( 1016): Got set_interactive hint
D/DisplayManagerService( 1016): !@display_state: ON -> OFF
D/SurfaceFlinger(  256): Set power mode=0, type=0 flinger=0xb83ad690
D/qdhwcomposer(  256): hwc_setPowerMode: Setting mode 0 on display: 0
I/DisplayManagerService( 1016): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 294.967 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
V/ActivityManager( 1016): Display changed displayId=0
W/libprocessgroup( 1016): failed to open /acct/uid_10142/pid_5364/cgroup.procs: No such file or directory
W/DisplayManagerService( 1016): Failed to notify process 5364 that displays changed, assuming it died.
W/DisplayManagerService( 1016): android.os.DeadObjectException
W/DisplayManagerService( 1016): 	at android.os.BinderProxy.transactNative(Native Method)
W/DisplayManagerService( 1016): 	at android.os.BinderProxy.transact(Binder.java:511)
W/DisplayManagerService( 1016): 	at android.hardware.display.IDisplayManagerCallback$Stub$Proxy.onDisplayEvent(IDisplayManagerCallback.java:81)
W/DisplayManagerService( 1016): 	at com.android.server.display.DisplayManagerService$CallbackRecord.notifyDisplayEventAsync(DisplayManagerService.java:1372)
W/DisplayManagerService( 1016): 	at com.android.server.display.DisplayManagerService.deliverDisplayEvent(DisplayManagerService.java:1170)
W/DisplayManagerService( 1016): 	at com.android.server.display.DisplayManagerService.access$500(DisplayManagerService.java:146)
W/DisplayManagerService( 1016): 	at com.android.server.display.DisplayManagerService$DisplayManagerHandler.handleMessage(DisplayManagerService.java:1305)
W/DisplayManagerService( 1016): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DisplayManagerService( 1016): 	at android.os.Looper.loop(Looper.java:145)
W/DisplayManagerService( 1016): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/DisplayManagerService( 1016): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
I/DBG_POLICYDM( 5870): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
D/LightsService( 1016): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1016) 
D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/StatusBar.NetworkController( 1178): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
I/ServiceManager(  317): Waiting for service AtCmdFwd...
D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
W/ResourcesManager( 5967): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5967): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
E/lights  ( 1016): write_int failed to open -1
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/BatteryService( 1016): turn on LED for fully charged
D/SSRM:n  ( 1016): SIOP:: AP = 330
E/SmartFaceService( 1016): onReceive: android.intent.action.SCREEN_OFF
W/System.err( 1016): java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
W/System.err( 1016): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/System.err( 1016): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
E/SmartFaceService( 1016): fail to set sysfs 0
W/System.err( 1016): 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
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
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
I/DBG_POLICYDM( 5870): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
D/MotionRecognitionService( 1016):   mReceiver.onReceive : ACTION_SCREEN_OFF
E/MotionRecognitionService( 1016):  handler : SCREEN_OFF end 
D/SamsungIME( 1786): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
D/NotificationService( 1016): ACTION_SCREEN_OFF
D/LightsService( 1016): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1016) 
D/LightsService( 1016): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/LightsService( 1016): [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
D/LightsService( 1016): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/audio_hw_primary(  281): adev_set_parameters: enter: screen_state=off
V/voice   (  281): voice_set_parameters: enter: screen_state=off
V/voice   (  281): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  281): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  281): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  281): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  281): adev_set_parameters: exit
D/Mms/ArtClassLoader( 5800): init [DONE] art
I/BackgroundCompactionService( 1016): Schedule Type1 BGCompaction
D/ComposerPerformance( 5800): 1452511724951 ms / [DONE] Composer constructor
E/CII     ( 5800): CommonIMSInterface: VoLTE CSC feature disabled.
I/Mms/ReservationManager( 5800): ReservationManager()
I/Mms/ReservationManager( 5800): resetAfterConnected()
I/BatteryStatsDumper( 1016): In refreshStats isReason Screen ON/OFF: true
D/TP/MmsSmsProvider( 1461): query,matched:7, calling pid = 5800
D/TP/MmsSmsProvider( 1461): match 7:Elapsed time : 1.702 ms
D/IpRemoteDisplayController( 1016): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 1016): Bridge Server is not available
D/GpsLocationProvider( 1016): receive broadcast intent, action: android.intent.action.SCREEN_OFF
D/Mms/Conversation( 5800): [start]    init() consume time = 106.270781
D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
V/EmergencyMode( 1416): [EmergencyStateReceiver] binteractive [false] why[3]
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/PersonaManagerService( 1016): ACTION_SCREEN_OFF onReceive
I/Mms/ReservationManager( 5800): getReservedSendMessageCount(): retMessageCount=0
D/PersonaManagerServiceHandler( 1016): MSG_ACTION_SCREEN_OFF called
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/MmsApp( 5800): [end]    onCreate() consume time = 53.671198
D/TP/MmsSmsProvider( 1461): deleteConversation threadId: 9223372036854775807
I/BatteryStatsDumper( 1016): Screen bin #0: time=30305 power=0.17677916666666665
I/BatteryStatsDumper( 1016): Screen bin #1: time=0 power=0.0
I/BatteryStatsDumper( 1016): Screen bin #2: time=0 power=0.0
I/BatteryStatsDumper( 1016): Screen bin #3: time=0 power=0.0
I/BatteryStatsDumper( 1016): Screen bin #4: time=0 power=0.0
I/BatteryStatsDumper( 1016): Previous Battery Level: 0 Current Level: 100 Delta: -100
D/TP/MmsSmsProvider( 1461): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
V/TP/MmsSmsDatabaseHelper( 1461): updateThread(), thread_id = 9223372036854775807
V/TP/MmsSmsDatabaseHelper( 1461): sUpgradeVersion = 0, db.getVersion() = 81
D/NfcService( 1440): call the applyRouting
D/accuweather( 1706): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 1706): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
D/TP/MmsSmsProvider( 1461): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1461): need read changed broadcast:false
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
D/Mms/Conversation( 5800): [end]    init consume time = 27.078438
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/MessagingNotification( 5800): [start]    init() consume time = 2.79
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.widgetapp.ap.hero.accuweather/com.sec.android.widgetapp.ap.hero.accuweather.WeatherClockService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
I/DBG_POLICYDM( 5870): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
D/Mms/DownloadManager( 5800): Service state changed: Bundle[mParcelledData.dataSize=744]
D/Mms/DownloadManager( 5800): roaming ------> false, mSimSlot = 0
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Mms/MethodReflector( 5800): getSubId is called
D/Mms/TelephonyUtils( 5800): getLongSubId from simSlot 0, return Value = -1
D/Mms/MethodReflector( 5800): getTelephonyProperty is called
D/Mms/DownloadManager( 5800): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 5800): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 5800): auto download without roaming -> true
D/Mms/DownloadManager( 5800): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 5800): mAutoDownload ------> true
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/accuweather( 1706): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
D/Mms/MessagingNotification( 5800): [end]    init consume time = 20.378489
I/DBG_POLICYDM( 5870): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/TP/MmsSmsProvider( 1461): query,matched:0, calling pid = 5800
V/TP/MmsSmsProvider( 1461): getSimpleConversations entered.
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TP/MmsSmsProvider( 1461): match 0:Elapsed time : 2.205 ms
D/Mms/Synchronizer( 5800): [start]    doSync consume time = 21.276198
D/Mms/SpamFilter( 5800): [start]    SpamFilter fill() begin consume time = 1.793542
D/ChimeraCfgMgr( 2013): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2013): Module APK com.google.android.play.games already loaded
D/TP/MmsSmsProvider( 1461): update, matched:300, calling pid = 5800
V/TP/MmsSmsProvider( 1461): syncDBData start
V/TP/MmsSmsProvider( 1461): syncDBData sms end
V/TP/MmsSmsProvider( 1461): syncDBData mms end
V/TP/MmsSmsProvider( 1461): syncDBData end
D/Mms/FreeMessageStatusReceiver( 5800): onReceive, action : android.intent.action.PACKAGE_ADDED
D/Mms/Synchronizer( 5800): [end]    doSync consume time = 6.458489
D/ActivityManager( 1016): startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SSRM:n  ( 1016): SIOP:: AP = 320
D/TP/MmsSmsProvider( 1461): query,matched:400, calling pid = 5800
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/qdhwcomposer(  256): hwc_setPowerMode: Done setting mode 0 on display 0
I/qdhwcomposer(  256): handle_blank_event: dpy:0 panel power state: 0
D/PowerManagerService( 1016): Excessive delay in !@display_state: OFF: 254ms
E/qdutils (  256): int qdutils::getHDMINode(): Failed to open fb node 2
D/PowerManagerService( 1016): Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 272ms
E/qdutils (  256): int qdutils::getHDMINode(): Failed to find HDMI node
I/PowerManagerService( 1016): [PWL] Off : 0s ago
D/SurfaceControl( 1016): Excessive delay in setPowerMode(): 253ms
I/PowerManagerService( 1016): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/libsuspend( 1016): !@autosuspend_wakeup_count_enable
I/PowerManagerService( 1016): [PWL]     mWakeLockSummary : 0x1
I/libsuspend( 1016): !@autosuspend_wakeup_count_enable done
I/PowerManagerService( 1016): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1016, ws=WorkSource{1000}) (elapsedTime=1078)
I/PowerManagerService( 1016): [PWL]       PARTIAL_WAKE_LOCK              'SmartManager Framework Thread' (uid=1000, pid=1016, ws=null) (elapsedTime=171)
I/PowerManagerService( 1016): [PWL]       PARTIAL_WAKE_LOCK              'SmartManager Framework Message' (uid=1000, pid=1016, ws=null) (elapsedTime=16)
I/PowerManagerService( 1016): [PWL]   PowerManagerService.Broadcasts: ref count=1
D/Mms/FreeMessageReceiverService( 5800): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5800): onHandleIntent: ACTION_PACKAGE_ADDED
E/Zygote  ( 5994): MountEmulatedStorage()
I/libpersona( 5994): KNOX_SDCARD checking this for 10047
E/Zygote  ( 5994): v2
I/libpersona( 5994): KNOX_SDCARD not a persona
I/SELinux ( 5994): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 5994): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 5994): [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5994 uid=10047 gids={50047, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/LibSecureUISvc( 1943): svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
E/Zygote  ( 6008): MountEmulatedStorage()
I/libpersona( 6008): KNOX_SDCARD checking this for 10072
E/Zygote  ( 6008): v2
I/libpersona( 6008): KNOX_SDCARD not a persona
I/SELinux ( 6008): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6008 uid=10072 gids={50072, 9997} abi=armeabi-v7a
I/SELinux ( 6008): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6008): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/Mms/SpamFilter( 5800): [end]    SpamFilter fill() finished consume time = 77.781511
W/art     ( 2013): Suspending all threads took: 11.461ms
D/PowerManagerService( 1016): [PWL] sb release: PowerManagerService.Broadcasts
D/TimaKeyStoreProvider( 5994): TimaSignature is unavailable
D/ActivityThread( 5994): Added TimaKeyStore provider
I/art     (  308): Explicit concurrent mark sweep GC freed 8741(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 655us total 28.502ms
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 17.343ms
D/TimaKeyStoreProvider( 6008): TimaSignature is unavailable
W/ResourcesManager( 5994): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ActivityThread( 6008): Added TimaKeyStore provider
W/ResourcesManager( 5994): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5994): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/ActivityManager( 1016): Killing 5379:com.android.providers.calendar/u0a42 (adj 15): empty #31
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 633us total 17.249ms
D/BadgeProvider( 6008): onCreate
D/BadgeProvider( 6008): DatabaseHelper
D/Mms/MessagingNotification( 5800): checkBadgeCount unreadCount=0 badgeCount=0
D/TP/SmsProvider( 1461): query,matched:26, calling pid = 5800
D/TP/SmsProvider( 1461): match 26:Elapsed time : 2.117 ms
D/ChimeraCfgMgr( 2013): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/TP/MmsSmsProvider( 1461): query,matched:6, calling pid = 5800
D/TP/MmsSmsProvider( 1461): match 6:Elapsed time : 1.764 ms
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6030): MountEmulatedStorage()
E/Zygote  ( 6030): v2
I/libpersona( 6030): KNOX_SDCARD checking this for 10025
I/libpersona( 6030): KNOX_SDCARD not a persona
I/SELinux ( 6030): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6030 uid=10025 gids={50025, 9997} abi=armeabi-v7a
I/SELinux ( 6030): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6030): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/IcingInternalCorpora( 2013): getNumBytesRead when not calculated.
D/AsyncTaskServiceImpl( 2013): Submit a task: k
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/TimaKeyStoreProvider( 6030): TimaSignature is unavailable
D/ActivityThread( 6030): Added TimaKeyStore provider
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1016): Killing 5297:com.google.android.talk/u0a104 (adj 15): empty #31
I/DBG_POLICYDM( 5870): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
W/libprocessgroup( 1016): failed to open /acct/uid_10042/pid_5379/cgroup.procs: No such file or directory
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 6030): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
E/WifiNative-wlan0( 1016): do suspend true
W/BaseAppContext( 2013): Using Auth Proxy for data requests.
W/BaseAppContext( 2013): Using Auth Proxy for data requests.
D/MyFiles ( 5994): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
I/TactileAssist( 1016): enable value -1
I/TactileAssist( 1016): internal enable value -1
I/TactileAssist( 1016): intensity value -1
I/TactileAssist( 1016): saveAppList value true
D/ChimeraCfgMgr( 2013): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/TactileAssist( 1016): List of disabled apps :
E/installd(  282): system dir 0 : /system/app/
E/installd(  282): system dir 1 : /system/priv-app/
E/installd(  282): system dir 2 : /vendor/app/
E/installd(  282): system dir 3 : /oem/app/
I/DBG_POLICYDM( 5870): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
W/BaseAppContext( 2013): Using Auth Proxy for data requests.
I/OMACP   ( 6030): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/ChimeraCfgMgr( 2013): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/PackageManager( 1016): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
D/k       ( 2013): Processing package: com.test.thalitest
D/Mms/Omacp( 5800): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
E/Zygote  ( 6053): MountEmulatedStorage()
E/Zygote  ( 6053): v2
I/libpersona( 6053): KNOX_SDCARD checking this for 10053
I/libpersona( 6053): KNOX_SDCARD not a persona
I/SELinux ( 6053): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=6053 uid=10053 gids={50053, 9997, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 6053): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6053): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1016): failed to open /acct/uid_10104/pid_5297/cgroup.procs: No such file or directory
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/OMACP   ( 6030): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
I/OMACP   ( 6030): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
I/OMACP   ( 6030): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
I/OMACP   ( 6030): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
I/OMACP   ( 6030): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
I/OMACP   ( 6030): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
I/OMACP   ( 6030): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/OMACP   ( 6030): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
I/OMACP   ( 6030): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
I/OMACP   ( 6030): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
I/OMACP   ( 6030): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
I/OMACP   ( 6030): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
I/OMACP   ( 6030): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
D/TimaKeyStoreProvider( 6053): TimaSignature is unavailable
D/ActivityThread( 6053): Added TimaKeyStore provider
W/BaseAppContext( 2013): Using Auth Proxy for data requests.
W/BaseAppContext( 2013): Using Auth Proxy for data requests.
W/BaseAppContext( 2013): Using Auth Proxy for data requests.
W/ResourcesManager( 6053): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/ActivityManager( 1016): Killing 5437:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Compatibility( 6053): onReceive() it will make start service
D/ActivityManager( 1016): startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
I/SL_DEBUG( 5967): isLoggable:: isProductShip = 1
I/SL_DEBUG( 5967): isLoggable:: SL_DEBUG_EXIST = false
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/SSRM:a  ( 1016): DeviceInfo:: 000000000000
D/SSRM:a  ( 1016): SettingsAirViewInfo:: 000000000
E/JavaBinder( 1016): !!! FAILED BINDER TRANSACTION !!!
W/BroadcastQueue( 1016): Exception when sending broadcast to ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver}
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
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/Compatibility( 6053): onHandleIntent()
D/Compatibility( 6053): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10175, android.intent.extra.user_handle=0}]
D/Compatibility( 6053): found: 2
E/Zygote  ( 6072): MountEmulatedStorage()
E/Zygote  ( 6072): v2
I/ActivityManager( 1016): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=6072 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
I/libpersona( 6072): KNOX_SDCARD checking this for 10057
I/libpersona( 6072): KNOX_SDCARD not a persona
I/SELinux ( 6072): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6072): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6072): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Compatibility( 6053): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6053): skipping ResolveInfo{2f8ac606 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 6053): considering ResolveInfo{351054c7 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 6053): default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 6053): enabling receiver ResolveInfo{2ab2eaf4 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
W/BaseAppContext( 2013): Using Auth Proxy for data requests.
D/Compatibility( 6053): enabling receiver ResolveInfo{1e7c921d com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/TimaKeyStoreProvider( 6072): TimaSignature is unavailable
D/ActivityThread( 6072): Added TimaKeyStore provider
D/Compatibility( 6053): enabling receiver ResolveInfo{efd3c92 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/Compatibility( 6053): enabling receiver ResolveInfo{35337663 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
D/Compatibility( 6053): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/ActivityManager( 1016): Killing 5498:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.service.bg.PeopleBackgroundTasks; callingUser = 0; userId(target) = 0
D/GassUtils( 2013): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
D/k       ( 2013): Found info for package com.test.thalitest in db.
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1016): failed to open /acct/uid_10057/pid_5437/cgroup.procs: No such file or directory
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/libprocessgroup( 1016): failed to open /acct/uid_10069/pid_5498/cgroup.procs: No such file or directory
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5967): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
I/ServiceManager(  317): Waiting for service AtCmdFwd...
D/ActivityManager( 1016): startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
E/SMD     (  286): DCD OFF
D/AndroidRuntime( 6045): 
D/AndroidRuntime( 6045): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6045): CheckJNI is OFF
D/AndroidRuntime( 6045): readGMSProperty: start
D/AndroidRuntime( 6045): readGMSProperty: already setted!!
D/AndroidRuntime( 6045): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6045): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6045): readGMSProperty: end
D/AndroidRuntime( 6045): addProductProperty: start
I/UpdateIcingCorporaServi( 6072): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5967): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.sdk.samsunglink, calleePkgName: com.samsung.android.sdk.samsunglink
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.sdk.samsunglink/com.mfluent.asp.ContentAggregatorService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.sdk.samsunglink, destAppInfo.processName = com.samsung.android.sdk.samsunglink
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/art     ( 1016): Explicit concurrent mark sweep GC freed 243880(16MB) AllocSpace objects, 14(4MB) LOS objects, 33% free, 27MB/41MB, paused 2.943ms total 218.012ms
E/Zygote  ( 6108): MountEmulatedStorage()
I/libpersona( 6108): KNOX_SDCARD checking this for 10041
E/Zygote  ( 6108): v2
I/libpersona( 6108): KNOX_SDCARD not a persona
I/SELinux ( 6108): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6108): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6108): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6108 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/TimaKeyStoreProvider( 6108): TimaSignature is unavailable
D/ActivityThread( 6108): Added TimaKeyStore provider
W/GAV2    ( 5885): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/LocationManagerService( 1016): getProviders()=[passive]
I/PeopleDatabaseHelper( 2013): cleanUpNonGplusAccounts done.
I/SA      ( 6108): [SSP] onCreated
I/ActivityManager( 1016): Killing 5529:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
I/SA      ( 6108): [TPM] There is no property file
I/SA      ( 6108): [SCU] isHaveSA() - false
I/SA      ( 6108): [TPM] getModelProperty : null
I/SA      ( 6108): [TPM] getCSCProperty : null
I/SA      ( 6108): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 6108): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 6108): [DM] TFT FEATURE: false
I/SA      ( 6108): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 6108): [DM] init START
I/SA      ( 6108): [DM] This device is not a Vodafone
W/ResourceType( 6108): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 6108): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 6108): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 6108): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 6108): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 6108): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 6108): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 6108): No package identifier when getting value for resource number 0x00000000
W/ResourceType( 6108): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 6108): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
W/ResourceType( 6108): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 6108): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
W/ResourceType( 6108): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 6108): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 6108): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 6108): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 6108): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
W/ResourceType( 6108): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 6108): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 6108): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 6108): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 6108): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 6108): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 6108): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
W/ResourceType( 6108): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
I/SA      ( 6108): [SCU] isHaveSA() - false
I/SA      ( 6108): support phone number id : false
I/SA      ( 6108): [DM] Supports Ref Jpn : true
I/SA      ( 6108): [DM] init END
I/SA      ( 6108): [SUR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 6108): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10175 extra.user_handle.:0 ]
I/ActivityManager( 1016): Killing 5545:com.google.android.apps.plus/u0a120 (adj 15): empty #31
E/AffinityControl( 6045): AffinityControl: registerfunction enter
I/BatteryStatsDumper( 1016): Writing to database completed
D/AndroidRuntime( 6045): Calling main entry com.android.commands.am.Am
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/UpdateIcingCorporaServi( 6072): UpdateCorporaTask done [took 162 ms] updated apps [took 161 ms] 
W/ActivityManager( 1016): mDVFSHelper.acquire()
D/PhoneWindow( 1016): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1016): *FMB* installDecor flags : 25362712
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled return false
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5529/cgroup.procs: No such file or directory
I/SurfaceFlinger(  256): id=13 createSurf (1x1),1 flag=404, uhalitest
E/Zygote  ( 6141): MountEmulatedStorage()
E/Zygote  ( 6141): v2
I/libpersona( 6141): KNOX_SDCARD checking this for 10175
I/libpersona( 6141): KNOX_SDCARD not a persona
I/SELinux ( 6141): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6141 uid=10175 gids={50175, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/SELinux ( 6141): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6141): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/InputDispatcher( 1016): Focused application set to: xxxx
D/InputDispatcher( 1016): Focus left window: 3129
D/AndroidRuntime( 6045): Shutting down VM
W/libprocessgroup( 1016): failed to open /acct/uid_10120/pid_5545/cgroup.procs: No such file or directory
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 6141): TimaSignature is unavailable
D/ActivityThread( 6141): Added TimaKeyStore provider
E/Zygote  ( 6159): MountEmulatedStorage()
E/Zygote  ( 6159): v2
I/libpersona( 6159): KNOX_SDCARD checking this for 10100
I/libpersona( 6159): KNOX_SDCARD not a persona
I/SELinux ( 6159): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6159): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=6159 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 5167:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
D/ActivityManager( 1016): startService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.apps.docs
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.docs/com.google.android.apps.docs.sync.syncadapter.ContentSyncService; callingUser = 0; userId(target) = 0
E/SELinux ( 6159): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.apps.docs
V/ActivityManager( 1016): Display changed displayId=0
W/GAV2    ( 5885): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/TimaKeyStoreProvider( 6159): TimaSignature is unavailable
D/PersonaManager( 1016): isKioskContainerExistOnDevice
D/ActivityThread( 6159): Added TimaKeyStore provider
D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1805): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/SurfaceFlinger(  256): id=10 Removed YUIInstallC (5/9)
I/SurfaceFlinger(  256): id=10 Removed YUIInstallC (-2/9)
V/ActivityThread( 3129): updateVisibility : ActivityRecord{f0870f7 token=android.os.BinderProxy@2fdada5a {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
D/PackageIntentReceiver( 6159): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 6159): Not GearManger package! 
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6181): MountEmulatedStorage()
I/libpersona( 6181): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6181): v2
I/libpersona( 6181): KNOX_SDCARD not a persona
I/SELinux ( 6181): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=6181 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6181): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Killing 5672:com.sec.android.app.music:service/u0a40 (adj 15): empty #31
E/SELinux ( 6181): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1016): failed to open /acct/uid_10150/pid_5167/cgroup.procs: No such file or directory
W/AccountFeatureHelper( 5885): Write apps_features disabled false
D/TimaKeyStoreProvider( 6181): TimaSignature is unavailable
D/ActivityThread( 6181): Added TimaKeyStore provider
W/art     ( 6045): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
I/WebViewFactory( 6141): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,I/LibraryLoader( 6141): Time to load native libraries: 1 ms (timestamps 412-413)
,I/LibraryLoader( 6141): Expected native library version number "",actual native library version number ""
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6198): MountEmulatedStorage(),
,E/Zygote  ( 6198): v2
I/ActivityManager( 1016): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6198 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 6198): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/libpersona( 6198): KNOX_SDCARD checking this for 1000
I/libpersona( 6198): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Killing 4517:com.google.android.music:main/u0a111 (adj 15): empty #31
,W/GAV2    ( 5885): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/SELinux ( 6198): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6198): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/WebViewChromiumFactoryProvider( 6141): Binding Chromium to main looper Looper (main, tid 1) {2ab2eaf4}
,I/LibraryLoader( 6141): Expected native library version number "",actual native library version number ""
I/chromium( 6141): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/ActivityManager( 1016): Killing 4850:com.sec.android.widgetapp.SPlannerAppWidget/u0a134 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6198): TimaSignature is unavailable
,D/ActivityThread( 6198): Added TimaKeyStore provider
,I/BrowserStartupController( 6141): Initializing chromium process, singleProcess=true
W/art     ( 6141): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6141): ApplicationContext is null in ApplicationStatus
,W/chromium( 6141): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 6141): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,I/chromium( 6141): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,I/Adreno-EGL( 6141): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6141): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6141): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6141): Local Branch: 
I/Adreno-EGL( 6141): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6141): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6141):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/Icing   ( 2013): Indexing 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28 from com.google.android.gms
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/AcmsPackageEventListener( 6198): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 6198): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,I/wpa_supplicant( 2074): nl80211: Received scan results (4 BSSes)
,D/WifiP2pService( 1016): InactiveState{ what=147461 }
,D/WifiP2pService( 1016): P2pEnabledState{ what=147461 }
D/WifiP2pService( 1016): DefaultState{ what=147461 }
,E/Zygote  ( 6220): MountEmulatedStorage(),
E/Zygote  ( 6220): v2
I/libpersona( 6220): KNOX_SDCARD checking this for 10120
I/SELinux ( 6220): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/libpersona( 6220): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6220 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 5343:com.android.calendar/u0a135 (adj 15): empty #31
,I/SELinux ( 6220): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6220): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,D/AcmsService( 6198): Enter Oncreate
W/libprocessgroup( 1016): failed to open /acct/uid_10040/pid_5672/cgroup.procs: No such file or directory
D/AcmsServiceMonitor( 6198): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 6198): creating AcmsCore
D/AcmsCore( 6198): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6198): AcmsCore
D/AcmsCore( 6198): init
D/AcmsCore( 6198): Looper handler is not null
D/AcmsCore( 6198): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6198): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6198): Incrementing - Counter value: 1
D/AcmsCore( 6198): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService( 6198): onStartCommand
D/AcmsService( 6198): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 6198): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6198): Incrementing - Counter value: 2
D/AcmsService( 6198): Incremented Counter Value : onStartCommand
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/AcmsCertificateMngr( 6198): AcmsCertificateMngr
,D/TimaKeyStoreProvider( 6220): TimaSignature is unavailable
,D/ActivityThread( 6220): Added TimaKeyStore provider
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
D/ActivityThread( 6198): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
D/AcmsRevocationMngr( 6198): AcmsRevocationMngr
,W/ResourcesManager( 6220): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup( 1016): failed to open /acct/uid_10111/pid_4517/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10134/pid_4850/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10135/pid_5343/cgroup.procs: No such file or directory
,D/AcmsService( 6198): Inside handle Intent
D/AcmsService( 6198): App added - package name: com.test.thalitest
D/AcmsCore( 6198): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6198): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6198): Incrementing - Counter value: 3
D/AcmsCore( 6198): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 6198): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 6198): Decrementing - Counter value: 2
,I/Icing   ( 2013): Indexing done 63D6F3A2ED4DA7D0617BF171863F04BCF2381A28
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ChimeraCfgMgr( 2013): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2013): Module APK com.google.android.play.games already loaded
,W/chromium( 6141): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,I/Mms/MmsApp( 5800):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 5800): [start]    fillCache consume time = 1844.322395
D/Mms/ComposeMessageFragment( 5800): fillCache, easy = false
,W/art     ( 6141): Attempt to remove local handle scope entry from IRT, ignoring
,W/ActivityManager( 1016): Activity pause timeout for ActivityRecord{310faa11 u0 com.test.thalitest/.MainActivity t3}
,W/AwContents( 6141): onDetachedFromWindow called when already detached. Ignoring
,D/PhoneWindow( 6141): *FMB* installDecor mIsFloating : false
,D/PhoneWindow( 6141): *FMB* installDecor flags : 8456448
,D/SystemWebViewEngine( 6141): CordovaWebView is running on device made by: samsung
,W/art     ( 6141): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 6141): Attempt to remove local handle scope entry from IRT, ignoring
,D/AbsListView( 5800): Get MotionRecognitionManager
,D/MotionRecognitionService( 1016):  ssp status : false
,D/Mms/ComposeMessageFragment( 5800): [end]    fillCache consume time = 111.386354
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/OpenGLRenderer( 6141): Render dirty regions requested: true
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,V/ActivityThread( 6141): updateVisibility : ActivityRecord{1468390 token=android.os.BinderProxy@2c49ee42 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,D/PhoneWindow( 6141): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 6141): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  256): id=14 createSurf (1x1),1 flag=404, NainActivit
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/InputDispatcher( 1016): Focus entered window: 6141
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 6141): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 6141): Initialized EGL, version 1.4
,D/OpenGLRenderer( 6141): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,D/OpenGLRenderer( 6141): Enabling debug mode 0
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,D/Mms/BubbleViewCache( 5800): fillCache bubble = 1
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/splitIntent( 1016): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
,W/IInputConnectionWrapper( 6141): showStatusIcon on inactive InputConnection
I/Timeline( 6141): Timeline: Activity_idle id: android.os.BinderProxy@2c49ee42 time:81022
,I/ActivityManager( 1016): Displayed Component not be shown by security: +767ms (total +885ms)
,I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{310faa11 u0 com.test.thalitest/.MainActivity t3} time:81024
W/ActivityManager( 1016): mDVFSHelper.release()
,D/daemonapp( 1318): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1318): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1318): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/SurfaceFlinger(  256): id=13 Removed uhalitest (7/9)
,I/SurfaceFlinger(  256): id=13 Removed uhalitest (-2/9)
,I/SamsungIME( 1786): getCurrentCandidateView
,D/daemonapp( 1318): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1318): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1318): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1318): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1318): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1318): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1318): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1318): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1318): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 1318): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1318): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1318): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1452533220000
D/daemonapp( 1318): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1452511727366
,D/daemonapp( 1318): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1318): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 1318): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1318): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1318): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 1318): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1318): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1706): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 1318): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 1706): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1706): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,D/accuweather( 1706): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
W/BindingManager( 6141): Cannot call determinedVisibility() - never saw a connection for the pid: 6141
D/accuweather( 1706): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
D/daemonapp( 1318): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1318): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/accuweather( 1706): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1706): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
D/accuweather( 1706): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1706): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1706): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 1706): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/SamsungIME( 1786): Dismiss ExpandCandiate
,D/JsMessageQueue( 6141): Set native->JS mode to OnlineEventsBridgeMode
,I/SamsungIME( 1786): getDebugLevel  : 0x4f4c
,I/ActivityManager( 1016): Killing 5184:com.google.android.gm/u0a101 (adj 15): empty #31
,I/SamsungIME( 1786): getDebugLevel  : 0x4f4c
,I/SamsungIME( 1786): KeybaordView init() : load resources
,D/jxcore_app_log( 6141): JniHelper::setJavaVM(0xb7e2e450), pthread_self() = -1204268016
,D/JX-Cordova( 6141): jxcore cordova android initializing
,I/SamsungIME( 1786): getCurrentKeyboard
I/SamsungIME( 1786): getTextKeyboard
,D/SamsungIME( 1786): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/libprocessgroup( 1016): failed to open /acct/uid_10101/pid_5184/cgroup.procs: No such file or directory
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/DBG_POLICYDM( 5870): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5870): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5870): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5870): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5870): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5870): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5870): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/SamsungIME( 1786): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,W/jxcore-log( 6141): Initializing JXcore engine
W/jxcore-log( 6141): JXcore engine is ready
,W/jxcore-log( 6141): Starting JXcore engine
,E/audit   ( 1908): type=1400 msg=audit(1452511729.110:205): avc:  denied  { ioctl } for  pid=6141 comm=".test.thalitest" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1908):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1908): type=1300 msg=audit(1452511729.110:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=bec7bd58 items=0 ppid=308 ppcomm=main pid=6141 auid=4294967295 uid=10175 gid=10175 euid=10175 suid=10175 fsuid=10175 egid=10175 sgid=10175 fsgid=10175 ses=4294967295 tty=(none) comm=".test.thalitest" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1908): type=1320 msg=audit(1452511729.110:205): 
,W/jxcore-log( 6141): Platform android
W/jxcore-log( 6141): 
W/jxcore-log( 6141): Process ARCH arm
W/jxcore-log( 6141): 
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardViewMediator( 1178): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 1178): doKeyguard: not showing because lockscreen is off
,V/KeyguardEffectViewController( 1178): *** Keyguard wallpaper service already unbounded
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 5
,I/jxcore-log( 6141): JXcore Cordova bridge is ready!
I/jxcore-log( 6141): 
,W/jxcore-log( 6141): JXcore engine is started
I/Choreographer( 6141): Skipped 138 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6141): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6141): Toggling radios to true
I/jxcore-log( 6141): 
,D/BluetoothAdapter( 6141): enable()
,D/BluetoothAdapter( 6141): enable(): BT is already enabled..!
,D/SecContentProvider( 1016): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2( 1016): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1016): mCursor = null
,D/WifiService( 1016): setWifiEnabled: true pid=6141, uid=10175
,W/ActivityManager( 1016): Permission Denial: getCurrentUser() from pid=6141, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1016): Failed getting userId using ActivityManagerNative
W/WifiService( 1016): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6141, uid=10175 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 1016): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:24778)
W/WifiService( 1016): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2213)
W/WifiService( 1016): 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2201)
W/WifiService( 1016): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
W/WifiService( 1016): 	at android.os.Binder.execTransact(Binder.java:461)
D/SettingsProvider( 1016): name = wifi_on
,I/WifiService( 1016): disconnect: pid=6141, uid=10175
,I/wpa_supplicant( 2074): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 6141): Radios toggled
I/jxcore-log( 6141): 
,I/jxcore-log( 6141): My device name is: samsung-SM-A500FU
I/jxcore-log( 6141): 
,I/wpa_supplicant( 2074): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1,
I/wpa_supplicant( 2074): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 2074): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
I/wpa_supplicant( 2074): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 2074): wlan0: State: DISCONNECTED -> DISCONNECTED
E/wpa_supplicant( 2074): Cmd 35605 not handled
E/WifiStateMachine( 1016): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 2074): reset timer : RESET_TIMER 0
I/wpa_supplicant( 2074): wlan0: Setting scan request: 0 sec 0 usec
D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
D/Tethering( 1016): InitialState.processMessage what=4
I/wpa_supplicant( 2074): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 2074): wlan0: State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 2074): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 2074): First Scan Start
I/wpa_supplicant( 2074): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiConfigStore( 1016): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
,E/Tethering( 1016): No numeric data
,D/Tethering( 1016): sendTetherStateChangedBroadcast 0, 0, 0
,V/NetworkStats( 1016): performPollLocked(flags=0x1)
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
,D/HotspotTile( 1178): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1178): updateTetherState():false, false
D/Tethering( 1016): clearTetheredNotification()
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
,V/NetworkStats( 1016): performPollLocked() took 7ms
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,E/WifiNative-wlan0( 1016): do suspend true
,D/WifiP2pService( 1016): InactiveState{ what=143375 }
,D/WifiP2pService( 1016): P2pEnabledState{ what=143375 }
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/CommandListener(  276): Clearing all IP addresses on wlan0
,V/NativeCrypto( 1805): Read error: ssl=0xb83e7590: I/O error during system call, Connection timed out,
V/NativeCrypto( 1805): SSL shutdown failed: ssl=0xb83e7590: I/O error during system call, Broken pipe
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1016): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler },
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
I/System.out( 1016): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1016): Tagging socket 362 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1016, getuid(): 1000
,I/qtaguid ( 1016): Untagging socket 362
,I/System.out( 1016): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  276): uids 1000
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 502 for uid 1000
,E/ConnectivityService( 1016): updateNetworkInfo()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Validated
,E/ConnectivityService( 1016): updateNetworkInfo(),
D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524290
D/ConnectivityService( 1016): Validated NetworkAgentInfo [WIFI () - 502]
D/EntConnectivity( 1016): Not allowed due to - mEnabled false - primarySimSlot false
,D/ConnectivityService( 1016): rematching NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1016): Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
D/ConnectivityService( 1016): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,D/ConnectivityManager.CallbackHandler( 2013): CM callback handler got msg 524290
,E/WifiStateMachine( 1016): Start Disconnecting Watchdog 1
,I/wpa_supplicant( 2074): wlan0: Setting scan request: 0 sec 0 usec
,I/PowerManagerService( 1016): [PWL] Off : 5s ago
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14952 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling,
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6284): MountEmulatedStorage()
E/Zygote  ( 6284): v2
I/libpersona( 6284): KNOX_SDCARD checking this for 10104
,I/libpersona( 6284): KNOX_SDCARD not a persona
,I/SELinux ( 6284): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6284 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/SELinux ( 6284): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6284): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/WifiNative-wlan0( 1016): do suspend true
,D/WifiP2pService( 1016): InactiveState{ what=143375 }
D/WifiP2pService( 1016): P2pEnabledState{ what=143375 },
D/ConnectivityService( 1016): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/ConnectivityService( 1016): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,D/CommandListener(  276): Clearing all IP addresses on wlan0
D/ConnectivityService( 1016): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker( 1016): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/CSLegacyTypeTracker( 1016): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524292
D/TelephonyNetworkFactory( 1461): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,D/TelephonyNetworkFactory( 1461): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 2013): CM callback handler got msg 524292
D/WIFI_P2P( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/ConnectivityService( 1016): nai.networkMonitor.doQuit()
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): doQuit - quitNow()
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/EntConnectivity( 1016): Not allowed due to - mEnabled false - primarySimSlot false
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/Tethering( 1016): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1016): MasterInitialState.processMessage what=3
,V/NetworkStats( 1016): updateIfacesLocked()
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
,D/TimaKeyStoreProvider( 6284): TimaSignature is unavailable
,V/NetworkStats( 1016): performPollLocked() took 5ms
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/ActivityThread( 6284): Added TimaKeyStore provider
,D/StatusBar.NetworkController( 1178): EthernetConnected: false
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1178): updateDataNetType()
D/StatusBar.NetworkController( 1178): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1178): updateLTEICONDataNetType:0
,D/WifiNetworkAgent( 1016): NetworkAgent: NetworkAgent channel lost,
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1178): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WIFI    ( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,W/ResourcesManager( 6284): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/PhoneApp( 1461): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/PhoneApp( 1461): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/PhoneApp( 1461): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/PhoneApp( 1461): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/PhoneApp( 1461): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
D/PhoneApp( 1461): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/PhoneApp( 1461): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/PhoneApp( 1461): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/PhoneApp( 1461): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/PhoneApp( 1461): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/PhoneApp( 1461): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/PhoneApp( 1461): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/PhoneApp( 1461): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/PhoneApp( 1461): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,D/PhoneApp( 1461): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1461): FileWriteThread : threadType = 3
,I/Babel   ( 6284): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 6284): MmsConfig.loadMmsSettings
I/Babel   ( 6284): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/Babel   ( 6284): MmsConfig.loadFromDatabase
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,E/Babel   ( 6284): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 6284): MmsConfig.loadFromResources
,W/Settings( 6284): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Babel   ( 6284): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6284): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,I/Babel_StickerModule( 6284): App launched.
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1295): DMSUtil.isNetworkConnected - flag-null, state-null
,W/QCamera2Factory(  281): getCameraInfo: E, camera_id = 0
,W/QCamera2Factory(  281): getCameraInfo: X
,I/Hs20UtilService( 3568): Starting #8
,W/QCamera2Factory(  281): getCameraInfo: E, camera_id = 1
,W/QCamera2Factory(  281): getCameraInfo: X
,I/Hs20UtilService( 3568): Message received 5007
,I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1295): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1295): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1295): MountReceiver.mPrefHandler - 7002
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3568): Starting #9
,I/Hs20UtilService( 3568): Message received 5007
,D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1295): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1295): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 1295): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 1295): MountReceiver.mPrefHandler - 7002
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6284): Unrecognized profile 2130706433 for video/avc
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/AudioCapabilities( 6284): Unsupported mime audio/evrc
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6284): Unsupported mime audio/qcelp
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/AudioCapabilities( 6284): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6284): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 6284): Unsupported mime audio/x-ms-wma
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/AudioCapabilities( 6284): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6284): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6284): Unsupported mime audio/evrc
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6284): Unsupported mime video/wvc1
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/VideoCapabilities( 6284): Unsupported mime video/x-ms-wmv
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/VideoCapabilities( 6284): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6284): Unsupported mime video/wvc1
,W/VideoCapabilities( 6284): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6284): Unsupported mime video/x-ms-wmv7
,D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/VideoCapabilities( 6284): Unsupported mime video/x-ms-wmv8
,I/ApplicationPolicy( 1016): updateDataUsageMap
,I/DBG_DM  ( 3129): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/DBG_DM  ( 3129): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,W/VideoCapabilities( 6284): Unsupported mime video/mp43
,I/PCWCLIENTTRACE_PushUtil( 5819): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5819): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5819): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5819): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,W/VideoCapabilities( 6284): Unsupported mime video/sorenson
,I/splitIntent( 1016): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,I/splitIntent( 1016): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/VideoCapabilities( 6284): Unsupported mime video/mp4v-esdp
,E/Zygote  ( 6327): MountEmulatedStorage()
,E/Zygote  ( 6327): v2
,I/libpersona( 6327): KNOX_SDCARD checking this for 10111
I/libpersona( 6327): KNOX_SDCARD not a persona,
,I/SELinux ( 6327): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6327): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6327 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 6327): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast,
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/art     (  308): Explicit concurrent mark sweep GC freed 8707(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 27.695ms
,D/TimaKeyStoreProvider( 6327): TimaSignature is unavailable
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5819): noConnectivity : true
,D/ActivityThread( 6327): Added TimaKeyStore provider
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 606us total 18.844ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 596us total 16.772ms
,I/ActivityManager( 1016): Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6343 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6343): MountEmulatedStorage()
I/libpersona( 6343): KNOX_SDCARD checking this for 10009
E/Zygote  ( 6343): v2
I/libpersona( 6343): KNOX_SDCARD not a persona
I/SELinux ( 6343): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6343): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6343): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/accuweather( 1706): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/TimaKeyStoreProvider( 6343): TimaSignature is unavailable
D/ActivityThread( 6343): Added TimaKeyStore provider
,E/Zygote  ( 6357): MountEmulatedStorage()
I/libpersona( 6357): KNOX_SDCARD checking this for 10145
E/Zygote  ( 6357): v2
I/libpersona( 6357): KNOX_SDCARD not a persona
I/SELinux ( 6357): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/VideoCapabilities( 6284): Unsupported profile 4 for video/mp4v-es,
I/ActivityManager( 1016): Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6357 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,I/SELinux ( 6357): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6357): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/daemonapp( 1318): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/accuweather( 1706): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1706): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1706): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,D/accuweather( 1706): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1706): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1706): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6373): MountEmulatedStorage(),
E/Zygote  ( 6373): v2
I/libpersona( 6373): KNOX_SDCARD checking this for 10081
I/libpersona( 6373): KNOX_SDCARD not a persona,
I/SELinux ( 6373): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 6373): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
I/ActivityManager( 1016): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6373 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
E/SELinux ( 6373): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6357): TimaSignature is unavailable
,D/ActivityThread( 6357): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 6373): TimaSignature is unavailable
,D/ActivityThread( 6373): Added TimaKeyStore provider
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,W/ResourcesManager( 6357): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6357): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6357): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6357): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6357): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 1016): Killing 5737:com.google.android.gms:car/u0a12 (adj 15): empty #31
,I/wpa_supplicant( 2074): nl80211: Received scan results (6 BSSes),
I/wpa_supplicant( 2074): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 2074): Trying to associate with SSID '4E47373030'
I/wpa_supplicant( 2074): Trying to associate with  'G700'
I/wpa_supplicant( 2074): Re-associate with C0.AA.48
D/WifiMonitor( 1016): didn't find BSSID Trying to associate with SSID 'NG700'
,I/wpa_supplicant( 2074): wlan0: State: SCANNING -> ASSOCIATING
I/wpa_supplicant( 2074): CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,D/GpsLocationProvider( 1016): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,E/wpa_supplicant( 2074): Cmd 35605 not handled
,I/wpa_supplicant( 2074): wlan0: State: ASSOCIATING -> ASSOCIATED
I/wpa_supplicant( 2074): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 2074): Associated with C0.AA.48
,I/wpa_supplicant( 2074): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 2074): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
I/wpa_supplicant( 2074): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
,I/wpa_supplicant( 2074): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
I/wpa_supplicant( 2074): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,I/wpa_supplicant( 2074): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
I/wpa_supplicant( 2074): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 2074): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2074): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 2074): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 2074): Blacklist: Clear (temp) 
I/wpa_supplicant( 2074): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, false
D/Tethering( 1016): interfaceStatusChanged wlan0, false
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, false
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, true
D/Tethering( 1016): interfaceStatusChanged wlan0, true
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1016): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1016): interfaceStatusChanged wlan0, true
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2( 1016): mCursor = null
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/WifiNative-wlan0( 1016): callSECApiVoid - ID [50]
,W/libprocessgroup( 1016): failed to open /acct/uid_10012/pid_5737/cgroup.procs: No such file or directory
,E/WifiConfigStore( 1016): setLastSelectedConfiguration -1
,D/ConnectivityService( 1016): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,D/ConnectivityService( 1016): hsengiv:checkWhatTypeOfNetwork and the value is false
E/ConnectivityService( 1016): updateNetworkInfo()
,D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,E/WifiConfigStore( 1016): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/WifiConfigStore( 1016): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/CommandListener(  276): Setting iface cfg
,E/WifiStateMachine( 1016): Start Dhcp Watchdog 2
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,E/WifiNative-wlan0( 1016): do suspend false
,D/SecContentProvider2( 1016): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1016): mCursor = null
,D/WifiP2pService( 1016): InactiveState{ what=143375 }
,D/WifiP2pService( 1016): P2pEnabledState{ what=143375 }
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 62553(3MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 27MB/41MB, paused 2.949ms total 207.029ms
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.apps.docs, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,E/Tethering( 1016): No numeric data
,I/Nat464Xlat( 1016): interfaceLinkStateChanged wlan0, true
,D/Tethering( 1016): sendTetherStateChangedBroadcast 1, 0, 0
D/Tethering( 1016): clearTetheredNotification()
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
,D/HotspotTile( 1178): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1178): updateTetherState():false, false
,V/NetworkStats( 1016): performPollLocked() took 3ms
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,E/Zygote  ( 6401): MountEmulatedStorage(),
E/Zygote  ( 6401): v2
I/libpersona( 6401): KNOX_SDCARD checking this for 10113
I/libpersona( 6401): KNOX_SDCARD not a persona
I/SELinux ( 6401): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6401 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
I/ActivityManager( 1016): Killing 5416:com.samsung.aasaservice/1000 (adj 15): empty #31
,I/SELinux ( 6401): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6401): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 5028:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,I/MusicStore( 6327): Database version: 108
,I/KLMS-2.5.183: ( 3588): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 11 12:28:51 GMT+01:00 2016
D/ActivityManager( 1016): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/TimaKeyStoreProvider( 6401): TimaSignature is unavailable
,D/ActivityThread( 6401): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3588): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.183: ( 3588): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3588): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3588): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,I/KLMS-2.5.183: ( 3588): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3588): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,E/Zygote  ( 6420): MountEmulatedStorage()
,I/libpersona( 6420): KNOX_SDCARD checking this for 10034
E/Zygote  ( 6420): v2
I/libpersona( 6420): KNOX_SDCARD not a persona
,I/SELinux ( 6420): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1016): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6420 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6420): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6420): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/dhcpcd  ( 6422): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
I/dhcpcd  ( 6422): version 5.5.6 starting
E/dhcpcd  ( 6422): fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
I/KLMS-2.5.183: ( 3588): KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3588): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.183: ( 3588): KLMSIntentService(): onDestroy()
,I/dhcpcd  ( 6422): wlan0: sending IPv6 Router Solicitation
E/dhcpcd  ( 6422): wlan0: sendmsg: Cannot assign requested address
I/dhcpcd  ( 6422): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 6422): bssid match
I/dhcpcd  ( 6422): wlan0: rebinding lease of 192.168.1.129
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/BadgeProvider( 6008): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 6420): TimaSignature is unavailable
,D/ActivityThread( 6420): Added TimaKeyStore provider
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5416/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10044/pid_5028/cgroup.procs: No such file or directory
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/BadgeProvider( 6008): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 6008): sendNotify, [notify] : null
,D/BadgeProvider( 6008): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 6008): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 6008): update, [UpdateCount] : 1
,D/Launcher.Model( 1478): reloadBadges entered.
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/AcmsKeyStoreHelper( 6198):  getKeyStoreForApplication Enter
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/SO_AGENT( 6420): [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available,
,E/Zygote  ( 6447): MountEmulatedStorage(),
I/libpersona( 6447): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6447): v2
I/libpersona( 6447): KNOX_SDCARD not a persona
I/SELinux ( 6447): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6447 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 6447): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6447): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6447): TimaSignature is unavailable
,D/ActivityThread( 6447): Added TimaKeyStore provider
,I/AcmsKeyStoreHelper( 6198): Key Store exist
I/AcmsKeyStoreHelper( 6198): Hence loading the keystore file
,E/SPPClientService( 5939): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,I/SA      ( 6108): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 6108): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
I/SA      ( 6108): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 6108): [SLFUCHKMGR] constructor called
,D/ActivityManager( 1016): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,I/DBG_POLICYDM( 5870): [com.policydm.XDMApplication(503/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 5870): [com.policydm.XDMApplication(513/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 5870): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable,
E/DBG_POLICYDM( 5870): [com.policydm.XDMApplication(477/isNetworkChanged)] network not changed.... ,
,I/SA      ( 6108): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 6108): [OR] == isSIMCardReady false ==
,I/SA      ( 6108): [SCU] == networkStateCheck == false
I/SA      ( 6108): [OR] onReceive END
,V/DownloadManager( 1226): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5939): [[SystemStateMonitorService]] No Active Internet
,W/ResourcesManager( 6327): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6327): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/SecurityLogAgent( 6447): KnoxConfiguration : Current State = 1
,D/SecurityLogAgent( 6447): KnoxConfiguration : Current State Mapping Found 
,D/SecurityLogAgent( 6447): StateMachine : Current State = 1
,I/ActivityManager( 1016): Killing 5785:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,D/SecurityLogAgent( 6447): StateMachine : Changed Current State = 1
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6469): MountEmulatedStorage(),
,I/ActivityManager( 1016): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6469 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 4764:com.samsung.android.sm/1000 (adj 15): empty #31
E/Zygote  ( 6469): v2
I/libpersona( 6469): KNOX_SDCARD checking this for 10159
I/libpersona( 6469): KNOX_SDCARD not a persona
I/SELinux ( 6469): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6469): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 6469): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
V/JNIHelp ( 6327): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/TimaKeyStoreProvider( 6469): TimaSignature is unavailable
,D/ActivityThread( 6469): Added TimaKeyStore provider
,I/iu.Environment( 2013): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/ActivityManager( 1016): Killing 5460:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  286): DCD OFF
,I/iu.UploadsManager( 2013): num queued entries: 0
,I/iu.UploadsManager( 2013): num updated entries: 0
,I/iu.SyncManager( 2013): NEXT; no task
,W/ActivityThread( 6327): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6327): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3b0ba087: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6327): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6327): GMSCore installation verified
,W/libprocessgroup( 1016): failed to open /acct/uid_10152/pid_5785/cgroup.procs: No such file or directory,
,D/AcmsKeyStoreHelper( 6198):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 6198): getKeyStoreForApplication success 
D/AcmsCore( 6198): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 6198): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6198): Decrementing - Counter value: 1
D/AcmsCore( 6198): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 6198): This is NOT a valid MirrorLink app
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4764/cgroup.procs: No such file or directory
D/AcmsCore( 6198): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
W/libprocessgroup( 1016): failed to open /acct/uid_10015/pid_5460/cgroup.procs: No such file or directory
D/AcmsServiceMonitor( 6198): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6198): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 6198): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 6198): getSvcCounter - Counter value: 0
D/AcmsService( 6198): Enter onDestroy
I/AcmsService( 6198): cleanUp(): inside service clean up
D/AcmsCore( 6198): AcmsCore: inside DeInit
D/AcmsCore( 6198): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 6198): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 6198): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 6198): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 6198): AppEntryInterface: Inside CleanUp
,D/AcmsServiceMonitor( 6198): getSvcCounter - Counter value: 0
D/AcmsService( 6198): killing acms process
I/Process ( 6198): Sending signal. PID: 6198 SIG: 9
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ConfigStore( 6327): Config Database version: 1
,I/ActivityManager( 1016): Process ACMS.Process (pid 6198)(adj 0) has died(41,1131)
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6327): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6327): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6401): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6327): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6401): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6401): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6401): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1016): getStreamVolume 3 index 0
,I/MediaRouter( 6327): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6327): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6497): MountEmulatedStorage(),
E/Zygote  ( 6497): v2
I/libpersona( 6497): KNOX_SDCARD checking this for 10002
I/libpersona( 6497): KNOX_SDCARD not a persona
,I/SELinux ( 6497): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6497 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
I/SELinux ( 6497): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6497): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 6497): TimaSignature is unavailable
,D/ActivityThread( 6497): Added TimaKeyStore provider
,I/GHttpClientFactory( 6327): Using the GMSCore's GoogleHttpClient
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/WebViewFactory( 6401): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,I/ActivityManager( 1016): Killing 5150:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,I/LibraryLoader( 6401): Time to load native libraries: 2 ms (timestamps 6045-6047)
,I/LibraryLoader( 6401): Expected native library version number "",actual native library version number ""
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,V/WebViewChromiumFactoryProvider( 6401): Binding Chromium to main looper Looper (main, tid 1) {a2fbd4c},
I/LibraryLoader( 6401): Expected native library version number "",actual native library version number ""
I/chromium( 6401): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,E/Zygote  ( 6530): MountEmulatedStorage()
,E/Zygote  ( 6530): v2
I/libpersona( 6530): KNOX_SDCARD checking this for 1000
I/libpersona( 6530): KNOX_SDCARD not a persona
,I/SELinux ( 6530): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6530): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,I/ActivityManager( 1016): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6530 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/SELinux ( 6530): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 250, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/BrowserStartupController( 6401): Initializing chromium process, singleProcess=true
,W/art     ( 6401): Attempt to remove local handle scope entry from IRT, ignoring
,I/MotionRecognitionService( 1016): Plugged
E/SysUtils( 6401): ApplicationContext is null in ApplicationStatus
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/TimaKeyStoreProvider( 6530): TimaSignature is unavailable
,D/ActivityThread( 6530): Added TimaKeyStore provider
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/chromium( 6401): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 6401): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,I/chromium( 6401): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,I/Adreno-EGL( 6401): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 6401): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 6401): Build Date: 04/06/15 Mon
I/Adreno-EGL( 6401): Local Branch: 
I/Adreno-EGL( 6401): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 6401): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 6401):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/DIAGMON_AGENT( 6530): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5150/cgroup.procs: No such file or directory
,W/AudioManagerAndroid( 6401): Requires BLUETOOTH permission
,I/NSApplication( 6401): Starting up...
,I/ActivityManager( 1016): Killing 5846:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,I/ActivityManager( 1016): Killing 5836:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #32
,I/dhcpcd  ( 6422): wlan0: acknowledged 192.168.1.129 from 192.168.1.1
,I/dhcpcd  ( 6422): wlan0: leased 192.168.1.129 for 86400 seconds,
,I/DIAGMON_AGENT( 6530): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0,
,I/DIAGMON_AGENT( 6530): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6530): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE,
,I/DIAGMON_AGENT( 6530): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:,
I/DIAGMON_AGENT( 6530): ./extraInfo: <unknown ssid>
W/DIAGMON_AGENT( 6530): [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,I/ActivityManager( 1016): Killing 5478:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31,
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5836/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10156/pid_5846/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6577): MountEmulatedStorage()
,E/Zygote  ( 6577): v2
I/libpersona( 6577): KNOX_SDCARD checking this for 10125
I/libpersona( 6577): KNOX_SDCARD not a persona
I/SELinux ( 6577): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6577): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 6577): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6577 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 5513:com.sec.knox.bridge/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 6577): TimaSignature is unavailable
,D/ActivityThread( 6577): Added TimaKeyStore provider
,W/ResourcesManager( 6577): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6577): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6577): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/QuickConnect( 6577): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6577): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6577): PeriphStartReceiver.onReceive - no need to start
,I/splitIntent( 1016): Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1016): Killing 5568:com.android.vending/u0a28 (adj 15): empty #31
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3568): Starting #10
,I/Hs20UtilService( 3568): Message received 5007
,D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1295): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 1295): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1295): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 1295): MountReceiver.mPrefHandler - 7002
,E/WifiNative-wlan0( 1016): do suspend true
,W/libprocessgroup( 1016): failed to open /acct/uid_10032/pid_5478/cgroup.procs: No such file or directory
,D/WifiP2pService( 1016): InactiveState{ what=143375 }
,D/WifiP2pService( 1016): P2pEnabledState{ what=143375 }
,E/WifiStateMachine( 1016): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,E/WifiStateMachine( 1016): VerifyingLinkState enter
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/WifiNative-wlan0( 1016): callSECApiInt - ID [210]
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
,E/ConnectivityService( 1016): updateNetworkInfo()
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1016): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
D/ConnectivityService( 1016): Adding iface wlan0 to network 503
,D/WifiWatchdogStateMachine( 1016): updateDnsLinkProperty: enter
,D/WifiWatchdogStateMachine.DnsPinger( 1016): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.DnsResolver( 1016): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.SingDnsChecker( 1016): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/WifiWatchdogStateMachine.CaptivePortalDnsResolver( 1016): setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1016): Adding Route [fe80::/64 -> :: wlan0] to network 503
,D/ConnectivityService( 1016): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503
,D/ConnectivityService( 1016): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
,E/ConnectivityService( 1016): Unexpected mtu value: 0, wlan0
,D/ConnectivityService( 1016): Setting Dns servers for network 503 to [/192.168.1.1]
,D/ConnectivityService( 1016): LTETest block dns file not exists
D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
W/ActivityManager( 1016): userId = 0, bbcId = -10000
,D/ConnectivityService( 1016): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,E/WifiStateMachine( 1016): VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,I/Hs20UtilService( 3568): Starting #11
,D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1295): MountReceiver.onReceive - Keep current state
I/Hs20UtilService( 3568): Message received 5007
,E/ConnectivityService( 1016): updateNetworkInfo()
,E/ConnectivityService( 1016): updateNetworkInfo()
,D/ConnectivityService( 1016): NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService( 1016): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1016): rematching NetworkAgentInfo [WIFI () - 503]
,E/WifiStateMachine( 1016): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
E/WifiStateMachine( 1016): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): DefaultState{ when=-2ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Connected
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,I/System.out( 1016): (HTTPLog)-Static: isSBSettingEnabled false
,I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling
,D/EnterpriseController(  276): uids 1000
D/ConnectivityService( 1016):    accepting network in place of null
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 503 for uid 1000
,D/WIFI    ( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1461): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
D/TelephonyNetworkFactory( 1461): Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI_P2P( 1016): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
E/CSLegacyTypeTracker( 1016): add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker( 1016): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/StatusBar.NetworkController( 1178): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:null
I/WifiTrafficPoller( 1016): evaluateTrafficStatsPolling
I/WifiTrafficPoller( 1016): mBoosterFLAG : 0
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
I/WifiTrafficPoller( 1016): current booster mode : FullMode
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiNative-wlan0( 1016): callSECApiVoid - ID [212]
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_5513/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10028/pid_5568/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,D/ConnectivityService( 1016): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 3568): Starting #12
,I/Hs20UtilService( 3568): Message received 5007
D/ConnectivityService( 1016): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
D/Tethering( 1016): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1016): MasterInitialState.processMessage what=3
,D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524290
,V/NetworkStats( 1016): updateIfacesLocked()
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): performPollLocked(flags=0x1)
,D/NetworkStatsFactory( 1016): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1016): UpdateStatsForKnox main else ---
,D/ConnectivityManager.CallbackHandler( 2013): CM callback handler got msg 524290,
V/NetworkStats( 1016): performPollLocked() took 3ms
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1178): EthernetConnected: false
,D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1178): updateDataNetType()
D/StatusBar.NetworkController( 1178): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1178): updateLTEICONDataNetType:0
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1178): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
V/NetworkStats( 1016): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1295): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1295): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 1295): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1295): MountReceiver.onReceive - Keep current state
,D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
D/NtpTrustedTime( 1016): currentTimeMillis() cache hit
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,D/NearbySettings( 1295): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1295): MountReceiver.onReceive - Keep current state
,I/Hs20UtilService( 3568): Starting #13
,I/Hs20UtilService( 3568): Message received 5007
,D/WifiStateMachine( 1016): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityXOffset
D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1016): mCursor = null
I/System.out( 1016): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/SecContentProvider2( 1016): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1016): mCursor = null
,I/SurfaceFlinger(  256): id=15 createSurf (1x1),1 flag=4, Uoast
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 11 Jan 2016 11:28:53 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1452511733073], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1452511733055]}
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Don't send network conditions - lacking user consent.
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1016): Validated
D/ConnectivityService( 1016): Validated NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityService( 1016): rematching NetworkAgentInfo [WIFI () - 503]
D/ConnectivityService( 1016): Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
D/ConnectivityService( 1016): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 2013): CM callback handler got msg 524290,
D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524290
D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PowerManagerService( 1016): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016
,D/SRIB_DCS( 1178): log_dcs ThreadedRenderer::initialize entered! 
,D/StatusBar.NetworkController( 1178): EthernetConnected: false
,D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1178): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1178): updateDataNetType()
,D/StatusBar.NetworkController( 1178): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1178): updateLTEICONDataNetType:0
,D/StatusBar.NetworkController( 1178): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1178): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ConnectivityService( 1016): updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.129/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,D/ConnectivityService( 1016): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524295
,D/ConnectivityService( 1016): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,D/ConnectivityManager.CallbackHandler( 1178): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 2013): CM callback handler got msg 524295
,D/ConnectivityManager.CallbackHandler( 2013): CM callback handler got msg 524295
,D/ConnectivityService( 1016): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider( 1016): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 3129): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/NetworkMonitor( 6327): type=WIFI subType= reason=null isConnected=true
,I/PCWCLIENTTRACE_PushUtil( 5819): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5819): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5819): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5819): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1016): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
I/splitIntent( 1016): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,V/MusicLeanback( 6327): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,D/accuweather( 1706): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/FOTA_Client( 6343): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,D/daemonapp( 1318): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
,D/accuweather( 1706): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1706): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
I/FOTA_Client( 6343): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
D/accuweather( 1706): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1706): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/FOTA_Client( 6343): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,D/SecurityLogAgent( 6447): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 6447): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 6447): StateMachine : Current State = 1
,D/SecurityLogAgent( 6447): StateMachine : Changed Current State = 1
,W/FOTA_Client( 6343): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,D/accuweather( 1706): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1706): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KLMS-2.5.183: ( 3588): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 11 12:28:53 GMT+01:00 2016
,I/DIAGMON_AGENT( 6530): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 6530): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 6530): ./extraInfo: "NG700"
I/DIAGMON_AGENT( 6530): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
D/ActivityManager( 1016): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.183: ( 3588): KLMSAbstractReciever(): onReceive().END.
,I/KLMS-2.5.183: ( 3588): KLMSIntentService(): onCreate()
,D/WaitQueueForNetworkActivate( 5903): notifyNetworkActivated
,I/KLMS-2.5.183: ( 3588): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,I/KLMS-2.5.183: ( 3588): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3588): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,I/KLMS-2.5.183: ( 3588): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,I/KLMS-2.5.183: ( 3588): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3588): StateImplV2(): networkChangeListener().START
,I/KLMS-2.5.183: ( 3588): NetworkChangeOperations(): uploadRequestLog().START 
,W/ContextImpl( 5903): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/KLMS-2.5.183: ( 3588): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.183: ( 3588): StateImplV2(): networkChangeListener().END
,I/KLMS-2.5.183: ( 3588): KLMSIntentService(): onDestroy()
,D/QuickConnect( 6577): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 6577): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,I/QuickConnect( 6577): PeriphStartReceiver.onReceive - no need to start
,E/SPPClientService( 5939): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 6108): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 6108): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 6108): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 5870): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/SA      ( 6108): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 6108): [OR] == isSIMCardReady false ==
,I/SA      ( 6108): [SCU] == networkStateCheck == true
,I/SA      ( 6108): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6108): isChinaCountryCode : false
I/SA      ( 6108): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 6108): [OR] == networkStateCheck true ==
I/DBG_POLICYDM( 5870): [com.policydm.XDMApplication(469/isNetworkChanged)] a previous network is 0, current network is 2
,I/SA      ( 6108): [OR] GetMyCountryZoneTask
,I/SA      ( 6108): [OR] onReceive END
,V/DownloadManager( 1226): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/ActivityManager( 1016): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,E/DBG_POLICYDM( 5870): [com.policydm.XDMApplication(471/isNetworkChanged)] network changed.... 
,D/SecContentProvider2( 1016): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1016): mCursor = null
,I/SA      ( 6108): [SRS] prepareGetMyCountryZone
,I/SA      ( 6108): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 6108): [SSP] query invoked
,I/SA      ( 6108): [TPMU] GetMccFromDB : null
I/SA      ( 6108): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 6108): [TPM] isNoProxy(default) : true
,I/DBG_POLICYDM( 5870): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 5870): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 5870): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 5870): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 5870): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 5870): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 5870): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 5870): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,E/File    ( 6108): fail readDirectory() errno=2
,E/DBG_POLICYDM( 5870): [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,I/DBG_POLICYDM( 5870): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,D/ActivityManager( 1016): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/hcjo    ( 5903): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5903): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5903): exit::IDLE
D/InitializeManagerStateMachine( 5903): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5903): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5903): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5903): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5903): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5903): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5903): entry::SUCCESS
D/hcjo    ( 5903): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/iu.Environment( 2013): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2013): num queued entries: 0
,I/iu.UploadsManager( 2013): num updated entries: 0
,I/iu.SyncManager( 2013): NEXT; no task
D/hcjo    ( 5903): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5903): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5903): exit::SUCCESS
D/InitializeManagerStateMachine( 5903): entry::IDLE
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1016): Queue : backgroundsplit_2 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/EnterpriseController(  276): uids 10012
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 503 for uid 10012
,D/ConnectivityService( 1016): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,I/SA      ( 6108): [RC New] Execute method=[GET] start
,I/SA      ( 6108): [RC New] Security=[true]
,I/System.out( 6108): Thread-1075(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6108): Thread-1075(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 6108): Thread-1075(ApacheHTTPLog):isShipBuild true
I/System.out( 6108): Thread-1075(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 6108): Thread-1075(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  276): uids 10041
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 503 for uid 10041
,I/SA      ( 6108): [RC New] [v2liruge] api execute + 633
E/SMD     (  286): DCD OFF
I/SA      ( 6108): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6108): AsyncTask #1 calls detatch()
,I/SA      ( 6108): [ODM] saveOpenData( GEO_IP, PL )
,V/AlarmManager( 1016): waitForAlarm result :8
,I/SA      ( 6108): [OCP] update openData : PL
,I/SA      ( 6108): [TPMU] getNetworkMcc : 
,I/SA      ( 6108): [SCU] saveMccToPreferece Start
,I/SA      ( 6108): [SCU] RegionMCC : 260
I/SA      ( 6108): [SSP] query invoked
,I/SA      ( 6108): [TPMU] GetMccFromDB : null
,I/SA      ( 6108): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6108): [SCU] saveMccToPreferece End
,I/SA      ( 6108): [RC New] executeRequest [v2liruge] end. 696
I/SA      ( 6108): [RC New] Execute end
,I/SA      ( 6108): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 6108): [OR] GetMyCountryZoneTask Success
,D/SSRM:n  ( 1016): SIOP:: AP = 340
,D/PackageManager( 1016): [MSG] MCS_UNBIND
,I/ActivityManager( 1016): Killing 5800:com.android.mms/u0a46 (adj 15): empty #31
,D/CountryDetector( 1016): No listener is left
,W/libprocessgroup( 1016): failed to open /acct/uid_10046/pid_5800/cgroup.procs: No such file or directory
,I/dhcpcd  ( 6422): wlan0: sending IPv6 Router Solicitation
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,I/SurfaceFlinger(  256): id=15 Removed Uoast (8/9)
,I/SurfaceFlinger(  256): id=15 Removed Uoast (-2/9)
,D/PowerManagerService( 1016): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1016) eventTime = 90247
,D/PowerManagerService( 1016): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016 (0x0)
,D/PowerManagerService( 1016): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1016, ws=WorkSource{10054}) (elapsedTime=3481)
,D/ActivityManager( 1016): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/GAV4    ( 6401): Thread[GAThread,5,main]: No campaign data found.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1805): callingUid 10012, callindPid: 1805
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/art     ( 1805): Explicit concurrent mark sweep GC freed 36053(2MB) AllocSpace objects, 14(224KB) LOS objects, 40% free, 12MB/21MB, paused 1.176ms total 62.163ms
,E/GmsUtils( 6327): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 6327): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 42394(2MB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 27MB/41MB, paused 2.569ms total 148.597ms
,I/MusicLeanback( 6327): Conditions not met for autocaching.
,I/MusicLeanback( 6327): Stop autocaching.
,E/SMD     (  286): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5819): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 5819): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5819): [GetString-S]
,I/ReactiveServiceManager( 5819): Supported : 1
,D/QSEECOMAPI: ( 1016): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1016): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1016): Loaded image: APP id = 11
,D/QSEECOMAPI: ( 1016): QSEECom_dealloc_memory 
,D/QSEECOMAPI: ( 1016): QSEECom_shutdown_app, app_id = 11
E/terrier ( 1016): handleString: Failed to handle string(-4)
E/terrier ( 1016): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 5819): getString is null
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 5819): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 5819): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5819): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5819): getPushTypeList : [SPP, GCM]
E/PCWCLIENTTRACE_PCWHandler( 5819): [ensureRegistration] - No Samsung account
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.ContentSyncService; callingUser = 0; userId(target) = 0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6643 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 6643): MountEmulatedStorage()
E/Zygote  ( 6643): v2
I/libpersona( 6643): KNOX_SDCARD checking this for 10028
I/libpersona( 6643): KNOX_SDCARD not a persona
,I/SELinux ( 6643): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6643): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6643): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: android, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
,I/BackgroundCompactionService( 1016): onStart. jobID=801
,I/BackgroundCompactionService( 1016): onStart done. jobID=801
,I/BackgroundCompactionService( 1016): Execute BGCompaction (type1). (0 times)
,I/BackgroundCompactionService( 1016): compact_memory command done
,I/art     (  308): Explicit concurrent mark sweep GC freed 8720(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 710us total 37.089ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 636us total 17.900ms
,D/TimaKeyStoreProvider( 6643): TimaSignature is unavailable
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 620us total 16.752ms
,D/ActivityThread( 6643): Added TimaKeyStore provider
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{2bd12ceb u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/Finsky  ( 6643): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6643): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6643): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6643): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  ( 6643): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6643): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 6643): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ActivityManager( 1016): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,D/Ads     ( 6643): Skipping gmscore version check
,D/Finsky  ( 6643): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,I/dhcpcd  ( 6422): wlan0: sending IPv6 Router Solicitation
,D/Finsky  ( 6643): [1180] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6643): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/ActivityManager( 1016): Killing 5994:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_10047/pid_5994/cgroup.procs: No such file or directory
,V/AlarmManager( 1016): waitForAlarm result :8
,I/PowerManagerService( 1016): [PWL] Off : 15s ago
,I/jxcore-log( 6141): Test app app.js loaded
I/jxcore-log( 6141): 
,I/Choreographer( 6141): Skipped 650 frames!  The application may be doing too much work on its main thread.
,I/chromium( 6141): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged,
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate,
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/dhcpcd  ( 6422): wlan0: sending IPv6 Router Solicitation
I/dhcpcd  ( 6422): wlan0: no IPv6 Routers available
,D/ActivityManager( 1016): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.preloadupdate.PreloadUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/PreloadUpdateManagerStateMachine( 5903): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5903): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5903): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5903): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 5903): AutoUpdateTriggerManager:IDLE:notifyNextTime,
D/PreloadUpdateManagerStateMachine( 5903): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5903): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 5903): entry::IDLE
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 320
,E/SMD     (  286): DCD OFF
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{27505a65 u0 com.samsung.android.app.galaxyfinder/.tag.LocationTagReadyService}
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF
,E/Watchdog( 1016): !@Sync 3
,I/Atfwd_Sendcmd(  317): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  317): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,I/PowerManagerService( 1016): [PWL] Off : 30s ago
,V/AlarmManager( 1016): waitForAlarm result :4
,V/AlarmManager( 1016): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManagerEXT( 1016): <AppSync3 Whitelist>
V/AlarmManagerEXT( 1016): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  286): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,V/AlarmManager( 1016): waitForAlarm result :4
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.store.VacuumService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1805): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1805): Vacuum at: now=1452511758599 tag=VacuumService
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.uploader.UploaderService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  286): DCD OFF
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeConfigurator( 1805): Scheduling Phenotype for one-off execution 11239 seconds from now (1452511759140)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/GetConfigurationSnapshotOperation( 1805): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/PhenotypeFlagCommitter( 1805): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1805): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 1016): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/System.out( 1805): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 1805): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 1805): (HTTPLog)-Static: isShipBuild true
I/System.out( 1805): (HTTPLog)-Thread-260-927750012: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 1805): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  276): uids 10012
D/EnterpriseController(  276): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  276): getNetworkForDns: using netid 503 for uid 10012
,I/System.out( 1805): KnoxVpnUidStorageknoxVpnSupported API value returned is false
I/qtaguid ( 1805): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1805, getuid(): 10012
,I/qtaguid ( 1805): Tagging socket 87 with tag 1000120100000000{268440065,0} for uid -1, pid: 1805, getuid(): 10012
,D/LocationManagerService( 1016): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 1805): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 1805): Tagging socket 83 with tag 1000120100000000{268440065,0} for uid -1, pid: 1805, getuid(): 10012
,D/FactoryTest( 5397): Not factory mode,
D/FactoryTest( 5397): Not factory mode. isFactoryMode() returend false
D/MTPRx   ( 5397): DRIVER_TIME_OUT 60s lapsed,
D/MTPRx   ( 5397): still no open session command from host, so toast
,W/ContextImpl( 5397): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 5397): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
I/Timeline( 5397): Timeline: Activity_launch_request id:com.android.settings time:113575
,E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,W/ActivityManager( 1016): mDVFSHelper.acquire()
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/PersonaManager( 1016): isKioskContainerExistOnDevice
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings
,D/InputDispatcher( 1016): Focused application set to: xxxx
,D/InputDispatcher( 1016): Focus left window: 6141
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,E/MTPRx   ( 5397): started activity for popup
,W/ResourcesManager( 5397): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5397): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5397): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5397): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5397): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5397): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
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
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SettingsReceiverActivity( 5397): PREF_DONT_ASK_AGAIN : true
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,D/InputDispatcher( 1016): Focused application set to: xxxx
,D/InputDispatcher( 1016): Focus entered window: 6141
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/InputMethodManagerService( 1016): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@1a5d701c attribute=null, token = android.os.BinderProxy@21b21eb0
,D/SettingsReceiverActivity( 5397): dev.kiessupport is : TRUE
,D/PhoneWindow( 5397): *FMB* installDecor mIsFloating : true
D/PhoneWindow( 5397): *FMB* installDecor flags : 8388610
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
,I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
,D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,V/ActivityThread( 6141): updateVisibility : ActivityRecord{1468390 token=android.os.BinderProxy@2c49ee42 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,I/Timeline( 6141): Timeline: Activity_idle id: android.os.BinderProxy@2c49ee42 time:113786
,D/PersonaManager( 1016): isKioskContainerExistOnDevice
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 249, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ActivityManager( 1016): mDVFSHelper.release()
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 290
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 248, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 2
,I/PowerManagerService( 1016): [PWL] Off : 50s ago,
,D/SSRM:n  ( 1016): SIOP:: AP = 270
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF
,E/Watchdog( 1016): !@Sync 4
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260,
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  286): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :8
,I/PowerManagerService( 1016): [PWL] Off : 75s ago
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 1016): !@Sync 5
,I/ClearcutLoggerApiImpl( 1805): disconnect managed GoogleApiClient
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/PowerManagerService( 1016): [PWL] Off : 105s ago
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate,
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 6,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,V/AlarmManager( 1016): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/SecKeyguardClockView( 1178): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1178): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  286): DCD OFF
,I/Atfwd_Sendcmd(  317): AtCmdFwd service not ready - Exhausted retry attempts - :6,
I/Atfwd_Daemon(  317): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,V/AlarmManager( 1016): waitForAlarm result :8,
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 247, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 140s ago
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,E/SMD     (  286): DCD OFF,
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/Watchdog( 1016): !@Sync 7
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 1
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
I/MotionRecognitionService( 1016): mGripSensorEnabled= false,
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 8
,I/PowerManagerService( 1016): [PWL] Off : 180s ago
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4346, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1016): Plugged
,I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...,
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 4,
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1016): level:100, scale:100, status:5, health:2, present:true, voltage: 4345, temperature: 246, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1016): stay LED for fully charged
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,V/EmergencyMode( 1416): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1416): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,V/HeadsetService( 2623): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2623): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 1016): !@Sync 9
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  286): DCD OFF
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,E/SMD     (  286): DCD OFF
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,I/ServiceManager(  317): Waiting for service AtCmdFwd...
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!,
,W/Atfwd_Sendcmd(  317): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  286): DCD OFF
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,E/SMD     (  286): DCD OFF
,I/PowerManagerService( 1016): [PWL] Off : 225s ago,
,E/SMD     (  286): DCD OFF
,E/SMD     (  286): DCD OFF
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 1016): SIOP:: AP = 260
,D/WifiWatchdogStateMachine.CaptivePortalHandler( 1016): Do not check CP during LCD off.
,E/SMD     (  286): DCD OFF
,I/jxcore-log( 6141): --= Surplus to requirements =--
I/jxcore-log( 6141): 
,I/jxcore-log( 6141): ****TEST TOOK:  ms ****
I/jxcore-log( 6141): 
I/jxcore-log( 6141): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6141): 
,D/AndroidRuntime( 6802): ,
D/AndroidRuntime( 6802): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6802): CheckJNI is OFF
D/AndroidRuntime( 6802): readGMSProperty: start
D/AndroidRuntime( 6802): readGMSProperty: already setted!!
D/AndroidRuntime( 6802): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 6802): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 6802): readGMSProperty: end
D/AndroidRuntime( 6802): addProductProperty: start
,E/AffinityControl( 6802): AffinityControl: registerfunction enter
,D/AndroidRuntime( 6802): Calling main entry com.android.commands.pm.Pm,
,D/PersonaManagerService( 1016): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
D/PackageManager( 1016): START PACKAGE DELETE: observer{934290843}
D/PackageManager( 1016): pkg{<packageName>}
D/PackageManager( 1016): user{0}
D/PackageManager( 1016): caller{2000}
D/PackageManager( 1016): flags{3}
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 1016): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 1016): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1016): !@killApplicatoin: 10175, uninstall pkg
D/PackageManager( 1016): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager( 1016): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManagerService( 1016): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 1016): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled,
D/ApplicationPolicy( 1016): getApplicationUninstallationEnabled :  enabled true
,I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10175 user=-1: uninstall pkg
I/ActivityManager( 1016): Killing 6141:com.test.thalitest/u0a175 (adj 0): stop com.test.thalitest cause uninstall pkg
,W/PackageSettings( 1016): Skipping PackageSetting{3440f4a5 com.example.hello/10177} due to missing metadata
,I/WindowState( 1016): WIN DEATH: Window{a50e129 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger(  256): id=14 Removed NainActivit (6/8)
,I/ActivityManager( 1016):   Force finishing activity ActivityRecord{310faa11 u0 com.test.thalitest/.MainActivity t3}
,D/InputDispatcher( 1016): Focus left window: 6141
,W/ActivityManager( 1016): mDVFSHelper.acquire()
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,W/ActivityManager( 1016): Spurious death for ProcessRecord{12576d38 6141:com.test.thalitest/u0a175}, curProc for 6141: null,
I/ActivityManager( 1016): Force stopping com.test.thalitest appid=10175 user=0: pkg removed
,I/ActivityManager( 1016):   Force finishing activity ActivityRecord{310faa11 u0 com.test.thalitest/.MainActivity t3 f}
W/ActivityManager( 1016): Duplicate finish request for ActivityRecord{310faa11 u0 com.test.thalitest/.MainActivity t3 f}
,W/ActivityManager( 1016): CustomStartingWindow se packge removed so remove capture also
,D/InputDispatcher( 1016): Focused application released
,I/DBG_DM  ( 3129): [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,I/art     ( 5651): Explicit concurrent mark sweep GC freed 2390(140KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 762us total 28.565ms
,I/DBG_DM  ( 3129): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 11
,I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
,I/DBG_DM  ( 3129): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,W/GeofencerStateMachine( 1805): Ignoring removeGeofence because network location is disabled.
I/DBG_DM  ( 3129): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3129): [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 11
,I/art     ( 2013): Explicit concurrent mark sweep GC freed 33045(2MB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 13MB/18MB, paused 1.339ms total 86.339ms
,D/RegisteredComponentCache( 1440): Collect Tech packages for Knox
I/DBG_DM  ( 3129): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,D/PersonaManager( 1440): isKioskContainerExistOnDevice
I/DBG_DM  ( 3129): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,E/SamsungIME( 1786): mOCRHelper is null
,I/DBG_DM  ( 3129): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/KLMS-2.5.183: ( 3588): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Jan 11 12:32:38 GMT+01:00 2016
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/DBG_DM  ( 3129): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,I/KLMS-2.5.183: ( 3588): KLMSAbstractReciever(): onReceive().END.
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/DBG_DM  ( 3129): [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 11
,I/DBG_DM  ( 3129): [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,I/DBG_DM  ( 3129): [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,I/DBG_DM  ( 3129): [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 3129): [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,I/splitIntent( 1016): Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
I/splitIntent( 1016): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,I/DBG_DM  ( 3129): [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/art     ( 6072): Explicit concurrent mark sweep GC freed 270(21KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 732us total 160.058ms
,E/Zygote  ( 6817): MountEmulatedStorage(),
I/libpersona( 6817): KNOX_SDCARD checking this for 10094
E/Zygote  ( 6817): v2
I/libpersona( 6817): KNOX_SDCARD not a persona
,I/SELinux ( 6817): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6817 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6817): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6817): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3588): KLMSIntentService(): onCreate()
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
,D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
,I/DBG_DM  ( 3129): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,I/KLMS-2.5.183: ( 3588): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6830): MountEmulatedStorage()
E/Zygote  ( 6830): v2
I/libpersona( 6830): KNOX_SDCARD checking this for 10044
I/libpersona( 6830): KNOX_SDCARD not a persona
,I/SELinux ( 6830): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6830 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 6830): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 6830): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
I/SurfaceFlinger(  256): id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,I/KLMS-2.5.183: ( 3588): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/TimaKeyStoreProvider( 6817): TimaSignature is unavailable
,D/ActivityThread( 6817): Added TimaKeyStore provider
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/PersonaManager( 1440): isKioskContainerExistOnDevice,
,D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/InputDispatcher( 1016): Focus entered window: 3129
,D/SRIB_DCS( 3129): log_dcs ThreadedRenderer::initialize entered! 
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,E/Zygote  ( 6846): MountEmulatedStorage()
,E/Zygote  ( 6846): v2
I/libpersona( 6846): KNOX_SDCARD checking this for 1000
I/libpersona( 6846): KNOX_SDCARD not a persona
,I/SELinux ( 6846): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6846): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1016): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=6846 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
E/SELinux ( 6846): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false,
D/TimaKeyStoreProvider( 6830): TimaSignature is unavailable
,D/ActivityThread( 6830): Added TimaKeyStore provider
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 49730(3MB) AllocSpace objects, 93(1489KB) LOS objects, 33% free, 28MB/42MB, paused 3.511ms total 244.584ms
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 1016): Got RemoteException sending setActive(false) notification to pid 6141 uid 10175
,I/art     ( 1016): WaitForGcToComplete blocked for 240.834ms for cause Explicit
,I/KLMS-2.5.183: ( 3588): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/SamsungIME( 1786): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,D/RegisteredServicesCache( 1440): empty dynamic service
,I/Timeline( 3129): Timeline: Activity_idle id: android.os.BinderProxy@2fdada5a time:312680
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,D/TimaKeyStoreProvider( 6846): TimaSignature is unavailable
,D/ActivityThread( 6846): Added TimaKeyStore provider
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3588): KLMSIntentService(): PACKAGE_REMOVED
,E/Zygote  ( 6866): MountEmulatedStorage()
E/Zygote  ( 6866): v2
I/libpersona( 6866): KNOX_SDCARD checking this for 10149
I/libpersona( 6866): KNOX_SDCARD not a persona
,I/SELinux ( 6866): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6866): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1016): Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6866 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/KLMS-2.5.183: ( 3588): KLMSIntentService(): listeningToPackageRemoved().START
E/SELinux ( 6866): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/ActivityThread( 3129): updateVisibility : ActivityRecord{f0870f7 token=android.os.BinderProxy@2fdada5a {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
D/EnterpriseDeviceManagerService( 1016): Package has changed for user 0
W/TextServicesManagerService( 1016): no available spell checker services found
D/EnterpriseDeviceManagerService( 1016): Admin package name: com.google.android.gms
,I/KLMS-2.5.183: ( 3588): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,D/TimaKeyStoreProvider( 6866): TimaSignature is unavailable
,D/ActivityThread( 6866): Added TimaKeyStore provider
,W/ResourcesManager( 6830): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6830): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6830): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6830): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ActivityManager( 1016): mDVFSHelper.release()
I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{3af8b62e u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t2} time:312752
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 1016): mCursor = null
,D/elm:15183( 6817): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,I/KLMS-2.5.183: ( 3588): KLMSIntentService(): listeningToPackageRemoved().END
,D/elm:15183( 6817): ELMEngine.ELMEngine( context ).
,D/elm:15183( 6817): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1016): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,W/ResourcesManager( 6846): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/KLMS-2.5.183: ( 3588): KLMSIntentService(): onDestroy()
,D/elm:15183( 6817): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:15183( 6817): ElmAgentService : onCreate()
,D/elm:15183( 6817): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:15183( 6817): MainReceiver.listeningToPackageRemoved()
D/elm:15183( 6817): MDMBridge.getInstance()
D/elm:15183( 6817): MDMBridge.getAllLicenseInfoFromSDK()
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.aasaservice, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/elm:15183( 6817): MDMBridge.getAllLicenseInfoFromSDK()
,E/Zygote  ( 6882): MountEmulatedStorage()
I/libpersona( 6882): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6882): v2
I/libpersona( 6882): KNOX_SDCARD not a persona
I/SELinux ( 6882): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 6882): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6882): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.samsung.aasaservice for broadcast com.samsung.aasaservice/.AASAUpdateReceiver: pid=6882 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/RCPManagerService( 1016): PackageReceiver onReceive()
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/HarmonyEASService( 1016): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/elm:15183( 6817): ElmAgentService : onDestroy().
,D/ThemeInfoUtil( 6866): getCurrentFestivalName is [null]
D/ThemeInfoUtil( 6866): isCurrentFestival = false
,D/KnoxMUMContainerPolicy( 1016): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,I/OTPFW   ( 1016): PackageRemovalReceiver::onReceive Enter
,D/OTPFW   ( 1016): OtpDbHelper::getInstance New instance created
,D/OTPFW   ( 1016): DBIntegrity::getInstance - New instance created
,D/TimaKeyStoreProvider( 6882): TimaSignature is unavailable
,D/ActivityThread( 6882): Added TimaKeyStore provider
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 1016): Killing 6030:com.wsomacp/u0a25 (adj 15): empty #31
,D/OTPFW   ( 1016): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10175 container id = 0
,I/ActivityManager( 1016): Killing 6053:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,I/OTPFW   ( 1016): ProvisionData::getAllEntries Enter
,E/OTPFW   ( 1016): ProvisionData::getAllEntries Table is empty
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/EnterpriseBillingPolicy( 1016): uID is 10175
D/JobSchedulerService( 1016): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
,V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
E/Zygote  ( 6901): MountEmulatedStorage()
E/Zygote  ( 6901): v2
I/libpersona( 6901): KNOX_SDCARD checking this for 10152
I/libpersona( 6901): KNOX_SDCARD not a persona
I/SELinux ( 6901): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6901 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
I/SELinux ( 6901): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 6901): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
V/EnterpriseBillingPolicy( 1016): uID is 10175
V/EnterpriseBillingPolicy( 1016): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1016): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1016): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 1016): getBillingProfileForVpnEngine - end - null
,D/SSRM:aZ ( 1016): MSG_TYPE_APP_REMOVED::
,I/art     ( 6846): Explicit concurrent mark sweep GC freed 3862(202KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 805us total 65.743ms
D/AASAservice-UpdateReceiver( 6882): AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,W/System.err( 6882): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 6882): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
W/System.err( 6882): 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
W/System.err( 6882): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 6882): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 6882): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 6882): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6882): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6882): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 6882): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6882): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6882): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6882): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,I/ActivityManager( 1016): Killing 6072:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,V/AlarmManagerEXT( 1016): com.test.thalitest(10175) is removed.
,I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
D/TaskPersister( 1016): removeObsoleteFile: deleting file=3_task.xml
,D/TimaKeyStoreProvider( 6901): TimaSignature is unavailable
D/TaskPersister( 1016): removeObsoleteFile: deleting file=2_task.xml
,D/ActivityThread( 6901): Added TimaKeyStore provider
,D/PersonaManager( 1016): isKioskContainerExistOnDevice
,E/SQLiteLog( 6846): (284) automatic index on crash_info_summary(package_name_touched)
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/NearbySource( 6830): Nearby Source Create!
,D/NearbyContext( 6830): Nearby Context Create!,
,I/ActivityManager( 1016): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6919 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 6919): MountEmulatedStorage()
E/Zygote  ( 6919): v2
I/libpersona( 6919): KNOX_SDCARD checking this for 1000
I/libpersona( 6919): KNOX_SDCARD not a persona
,I/SELinux ( 6919): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Killing 5967:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
I/SELinux ( 6919): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6919): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/SQLiteLog( 6901): (284) automatic index on shooting_modes(title_id)
,D/TimaKeyStoreProvider( 6919): TimaSignature is unavailable
,D/ActivityThread( 6919): Added TimaKeyStore provider
,E/Vold    (  255): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    (  255): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6830): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/SLinkSource( 6830): Samsung link source created
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,D/BadgeProvider( 6008): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider( 6008): sendNotify, [notify] : null
D/BadgeProvider( 6008): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider( 6008): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 6008): update, [UpdateCount] : 1
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
I/StatusBar( 1178): Icon Only
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 1178): Icon Only
,I/StatusBar( 1178): Icon Only
,D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/PCWCLIENTTRACE_PushUtil( 5819): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 5819): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5819): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 5819): [onReceive] - android.intent.action.PACKAGE_REMOVED
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 16740(956KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 28MB/42MB, paused 7.754ms total 461.563ms,
I/libpersona( 6935): KNOX_SDCARD checking this for 10156
E/Zygote  ( 6935): MountEmulatedStorage()
I/libpersona( 6935): KNOX_SDCARD not a persona
E/Zygote  ( 6935): v2
I/ActivityManager( 1016): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=6935 uid=10156 gids={50156, 9997} abi=armeabi-v7a
I/SELinux ( 6935): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6935): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6935): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,W/ResourceType( 1016): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/TimaKeyStoreProvider( 6935): TimaSignature is unavailable
,D/ActivityThread( 6935): Added TimaKeyStore provider
,W/ContextImpl( 6919): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,D/PanelView( 1178): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
E/Zygote  ( 6953): MountEmulatedStorage()
E/Zygote  ( 6953): v2
I/libpersona( 6953): KNOX_SDCARD checking this for 10032
I/libpersona( 6953): KNOX_SDCARD not a persona
I/SELinux ( 6953): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6953): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6953): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PackageManager( 1016): delete codoeFile: 
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1016): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6953 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/AASAuninstall( 1016): userId = 0, info.removedAppID = -1, info.uid = 10175, packageName = com.test.thalitest
I/AASA_removePackage( 1016): UID=10175 Target=com.test.thalitest
,D/PackageManager( 1016): result of delete: 1{934290843}
,D/AndroidRuntime( 6802): Shutting down VM
,I/ActivityManager( 1016): Killing 5885:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,D/TimaKeyStoreProvider( 6953): TimaSignature is unavailable
,D/ActivityThread( 6953): Added TimaKeyStore provider
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/ResourcesManager( 1016): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PackagesMonitor( 6830): PackagesMonitor onReceive :com.test.thalitest
,E/Zygote  ( 6969): MountEmulatedStorage()
E/Zygote  ( 6969): v2
I/libpersona( 6969): KNOX_SDCARD checking this for 1000
I/libpersona( 6969): KNOX_SDCARD not a persona
I/SELinux ( 6969): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 6969): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6969): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6969 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/TapandpayWidget:TapandpayAppWidgetProvider( 6935): onReceive()
,D/TapandpayWidget:TapandpayAppWidgetProvider( 6935): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager( 1016): Killing 6159:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,D/ContactProvider( 6830): getAllContactInfoList Start
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,I/TapandpayWidget:Utils( 6935): Clear T&P info.
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/TimaKeyStoreProvider( 6969): TimaSignature is unavailable
,D/ActivityThread( 6969): Added TimaKeyStore provider
E/Zygote  ( 6985): MountEmulatedStorage()
,E/Zygote  ( 6985): v2
I/libpersona( 6985): KNOX_SDCARD checking this for 10046
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/libpersona( 6985): KNOX_SDCARD not a persona,
I/SELinux ( 6985): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/SELinux ( 6985): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 6985): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TapandpayWidget:TapandpayAppWidgetProvider( 6935): Widget is not attached.
,I/ActivityManager( 1016): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=6985 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 6181:com.samsung.helphub/1000 (adj 15): empty #31
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,D/UsbSettingsManager( 1016): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 1016): onPackageRemoved : com.test.thalitest
,W/libprocessgroup( 1016): failed to open /acct/uid_10025/pid_6030/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10053/pid_6053/cgroup.procs: No such file or directory
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 6969): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/libprocessgroup( 1016): failed to open /acct/uid_10057/pid_6072/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10038/pid_5967/cgroup.procs: No such file or directory
,I/art     (  308): Explicit concurrent mark sweep GC freed 8743(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 639us total 21.146ms
,D/TimaKeyStoreProvider( 6985): TimaSignature is unavailable
,D/ActivityThread( 6985): Added TimaKeyStore provider
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 606us total 17.608ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 597us total 16.660ms
,D/RCPManager( 6969):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 1016):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 1016): queryAllProviders():  providerCallBack is not register for 0
,E/Zygote  ( 7001): MountEmulatedStorage()
E/Zygote  ( 7001): v2
I/libpersona( 7001): KNOX_SDCARD checking this for 10160,
I/libpersona( 7001): KNOX_SDCARD not a persona
I/SELinux ( 7001): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=7001 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,I/SELinux ( 7001): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Killing 6008:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,E/SELinux ( 7001): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1016): failed to open /acct/uid_10100/pid_6159/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10091/pid_5885/cgroup.procs: No such file or directory
,E/Zygote  ( 7012): MountEmulatedStorage()
E/Zygote  ( 7012): v2
,I/libpersona( 7012): KNOX_SDCARD checking this for 10091
I/libpersona( 7012): KNOX_SDCARD not a persona
I/SELinux ( 7012): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 7012): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1016): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7012 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 7001): TimaSignature is unavailable
I/ActivityManager( 1016): Killing 6357:com.android.email/u0a145 (adj 15): empty #31
D/ActivityThread( 7001): Added TimaKeyStore provider
,E/SELinux ( 7012): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/art     ( 6802): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/TimaKeyStoreProvider( 7012): TimaSignature is unavailable
,D/ActivityThread( 7012): Added TimaKeyStore provider
W/ResourcesManager( 7001): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6985): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6985): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6985): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6985): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6985): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 6985): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/FeatureConfig( 6953): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/[0]UMC:UMCContentProvider( 7001): @onCreate
,E/Zygote  ( 7033): MountEmulatedStorage()
I/libpersona( 7033): KNOX_SDCARD checking this for 10035
E/Zygote  ( 7033): v2
I/libpersona( 7033): KNOX_SDCARD not a persona
,I/SELinux ( 7033): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 7033): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 7033): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
,W/ResourcesManager( 6953): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6953): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager( 1016): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7033 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ResourcesManager( 6953): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6953): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6953): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/ActivityManager( 1016): Killing 6497:com.sec.android.cloudagent/u0a2 (adj 15): empty #31
,D/[0]UMC:Core( 7001): onCreate(): 
D/[0]UMC:Core( 7001): @isManagedProfileUser
D/[0]UMC:Core( 7001): userId: 0
,D/[0]UMC:Core( 7001): userInfo: UserInfo{0:Thali Test:13}
D/[0]UMC:Core( 7001): userInfo.isManagedProfile() : false
,D/ContactProvider( 6830): getAllContactInfoList End
,I/syncContacts( 6830): thread: 1173, sync time = 348
,W/ResourcesManager( 6953): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/ResourcesManager( 6953): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 6953): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6953): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6953): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6953): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6953): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 7033): TimaSignature is unavailable
,D/ActivityThread( 7033): Added TimaKeyStore provider
,E/SQLiteLog( 6846): (284) automatic index on crash_info_summary(package_name_touched)
D/Launcher.Model( 1478): reloadBadges entered.
D/Mms/MmsApp( 6985): [start]    onCreate() consume time = 0.0
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.sec.android.app.launcher, calleePkgName: com.sec.android.provider.badge
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/[0]UMC:DeviceInfo( 7001): USA==US==
,W/ResourcesManager( 6953): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6953): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6953): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_6181/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10072/pid_6008/cgroup.procs: No such file or directory
,E/PhotosPlugin( 7012): Loading PhotosPlugin
,E/Zygote  ( 7050): MountEmulatedStorage(),
E/Zygote  ( 7050): v2
I/libpersona( 7050): KNOX_SDCARD checking this for 10072
,I/libpersona( 7050): KNOX_SDCARD not a persona,
,I/ActivityManager( 1016): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7050 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,I/SELinux ( 7050): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/ResourcesManager( 6953): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6953): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6953): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
I/SELinux ( 7050): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 7050): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
W/libprocessgroup( 1016): failed to open /acct/uid_10145/pid_6357/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10002/pid_6497/cgroup.procs: No such file or directory
,W/ResourcesManager( 6953): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6953): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6953): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6953): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6953): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6953): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6953): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6953): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 7050): TimaSignature is unavailable
,D/ActivityThread( 7050): Added TimaKeyStore provider
,W/ResourcesManager( 6953): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6953): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6953): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/BadgeProvider( 7050): onCreate

```
