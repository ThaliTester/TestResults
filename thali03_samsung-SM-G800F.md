#### Test 58135655c662d33_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/main,
I/qtaguid ( 5093): Failed write_ctrl(u 68) res=-1 errno=22
I/qtaguid ( 5093): Untagging socket 68 failed errno=-22
W/NetworkManagementSocketTagger( 5093): untagSocket(68) failed with errno -22
I/System.out( 5093): Thread-367 calls detatch()
--------- beginning of /dev/log/system
V/AlarmManager( 2421): waitForAlarm result :4
D/KeyguardViewMediator( 2582): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
D/LockPatternUtils( 2582): isPcwEnable = 10
V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/KeyguardViewMediator( 2582): in doKeyguardLocked mIsRollUp false null
D/PersonaManager( 2582): isKioskContainerExistOnDevice
D/LockPatternUtils( 2582): isPcwEnable = 10
D/LockPatternUtils( 2582): isPcwEnable = 10
D/KeyguardViewMediator( 2582): doKeyguard: not showing because lockscreen is off
I/PowerManagerService( 2421): [PWL] Off : 5s ago
D/AndroidRuntime( 6135): 
D/AndroidRuntime( 6135): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6135): CheckJNI is OFF
D/AndroidRuntime( 6135): setted country_code = Poland
D/AndroidRuntime( 6135): setted countryiso_code = PL
D/AndroidRuntime( 6135): setted sales_code = PLS
D/AndroidRuntime( 6135): readGMSProperty: start
D/AndroidRuntime( 6135): readGMSProperty: already setted!!
D/AndroidRuntime( 6135): readGMSProperty: end
D/AndroidRuntime( 6135): addProductProperty: start
D/dalvikvm( 6135): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6135): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6135): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6135): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6135): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 6135): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6135): failed to load memtrack module: -2
D/dalvikvm( 6135): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/Finsky  ( 5093): [1] DailyHygiene.access$600: Logging device features
V/AlarmManager( 2421): waitForAlarm result :4
V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/AndroidRuntime( 6135): Calling main entry com.android.commands.am.Am
D/WearableService( 2735): callingUid 10012, callindPid: 2735
D/DeviceConnectionService( 2735): client connected with version: 8296000
D/Finsky  ( 5093): [390] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5093): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 5093): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 6135): Shutting down VM
D/dalvikvm( 6135): GC_CONCURRENT freed 99K, 13% free 714K/816K, paused 1ms+1ms, total 6ms
I/System.out( 5093): Thread-377(HTTPLog):isShipBuild true
I/System.out( 5093): Thread-377(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 5936): GC_EXPLICIT freed 884K, 30% free 10010K/14104K, paused 4ms+9ms, total 50ms
,D/dalvikvm( 2832): GC_EXPLICIT freed 339K, 28% free 10305K/14164K, paused 5ms+7ms, total 49ms
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
D/dalvikvm( 5936): GC_EXPLICIT freed 871K, 29% free 10016K/14104K, paused 3ms+9ms, total 45ms
,D/dalvikvm( 2832): GC_EXPLICIT freed 351K, 28% free 10309K/14164K, paused 4ms+7ms, total 46ms,
,D/dalvikvm( 2421): GC_EXPLICIT freed 769K, 14% free 25240K/29312K, paused 8ms+20ms, total 222ms,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4347, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3367): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3367): Disconnected process message: 10,
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 5936): GC_EXPLICIT freed 874K, 29% free 10015K/14104K, paused 4ms+9ms, total 45ms,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 350, Delta = 0,
,D/dalvikvm( 2832): GC_EXPLICIT freed 348K, 28% free 10313K/14164K, paused 5ms+7ms, total 47ms
,D/dalvikvm( 5936): GC_EXPLICIT freed 872K, 29% free 10014K/14104K, paused 3ms+9ms, total 45ms
,D/dalvikvm( 2832): GC_EXPLICIT freed 354K, 28% free 10320K/14164K, paused 4ms+7ms, total 47ms
,D/PackageManager( 2421): [MSG] MCS_UNBIND
,I/PackageManager( 2421): calling disconnectService()
,D/PackageManager( 2421): Trying to unbind to DefaultContainerService
,I/ActivityManager( 2421): Killing 5232:com.vlingo.midas/u0a34 (adj 15): empty #43
,D/dalvikvm( 5936): GC_EXPLICIT freed 871K, 30% free 10012K/14104K, paused 3ms+9ms, total 47ms
,D/AmoledAdjustTimer( 2421): prevTemp = 300, currTemp = 301, prevStep = 4, currStep = 4
,D/dalvikvm( 2832): GC_EXPLICIT freed 363K, 28% free 10332K/14164K, paused 4ms+7ms, total 46ms
,D/dalvikvm( 5936): GC_CONCURRENT freed 1474K, 26% free 10499K/14104K, paused 2ms+10ms, total 36ms
,I/PowerManagerService( 2421): [PWL] Off : 15s ago
,I/SettingSearch/SearchIntentReceiver( 2832): InitTitleDBThread end --> mDoingInitTitleDB : false,
,I/SettingSearch/SearchIntentReceiver( 2832): LOCALE_CHANGED call search setting db finish!!,
,I/SettingSearch/SearchIntentReceiver( 2832): InitTitleDBThread start --> mDoingInitTitleDB : true,
,I/SettingSearch/SearchIntentReceiver( 2832): InitTitleDBThread end --> mDoingInitTitleDB : false,
,I/SettingSearch/SearchIntentReceiver( 2832): LOCALE_CHANGED call search setting db finish!!,
,V/AlarmManager( 2421): waitForAlarm result :4,
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4371, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 3367): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3367): Disconnected process message: 10
D/Finsky  ( 5093): [379] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 5093): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 340, Delta = -10,
,E/Watchdog( 2421): !@Sync 3,
,D/AmoledAdjustTimer( 2421): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4,
,D/dalvikvm( 2421): GC_EXPLICIT freed 695K, 14% free 25267K/29312K, paused 11ms+18ms, total 230ms,
,I/Icing   ( 3263): Indexing 6245F4AA15572483160DEB38E2CBB6FB536E377A from com.google.android.music,
,I/Icing   ( 3263): Indexing done 6245F4AA15572483160DEB38E2CBB6FB536E377A,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4351, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2421): stay LED for fully charged,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3367): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3367): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2421): [PWL] Off : 30s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = -10,
,V/AlarmManager( 2421): waitForAlarm result :4,
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/Headlines( 5458): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5458): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5458): Breath 52402 latestRequest time : 1454523160885 current time : 1454523213287,
,D/FactoryTest( 5175): Not factory mode,
,D/FactoryTest( 5175): Not factory mode. isFactoryMode() returend false,
D/MTPRx   ( 5175): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 5175): still no open session command from host, so toast,
W/ContextImpl( 5175): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1398 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 android.os.Handler.dispatchMessage:102 
W/ContextImpl( 5175): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1410 android.app.ContextImpl.startActivity:1399 android.content.ContextWrapper.startActivity:323 android.content.ContextWrapper.startActivity:323 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:767 
,V/ApplicationPolicy( 2421): isApplicationStateBlocked userId 0 pkgname com.android.settings,
,D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@4,
,W/ActivityManager( 2421): mDVFSHelper.acquire(),
,D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1,
,E/MTPRx   ( 5175): started activity for popup,
,I/SQLiteSecureOpenHelper( 3555): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3555): getDatabaseLocked(b,b,pwd)...
,E/SettingsReceiverActivity( 5175): PREF_DONT_ASK_AGAIN : true
D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
,W/InputMethodManagerService( 2421): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@42fd63f0 attribute=android.view.inputmethod.EditorInfo@43254850, token = android.os.BinderProxy@4387fb20
,D/SettingsReceiverActivity( 5175): dev.kiessupport is : TRUE
,I/DBG_DM  ( 4239): [3.19.140541][Line:408][onResume] 
,I/DBG_DM  ( 4239): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 38
,I/DBG_DM  ( 4239): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4239): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4239): [3.19.140541][Line:418][onResume] Postpone Count : 38
,I/DBG_DM  ( 4239): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4239): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4239): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2421): sendNotification(2) - 4
I/DBG_DM  ( 4239): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 38
,I/DBG_DM  ( 4239): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4239): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4239): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4239): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4239): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4239): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/Activity( 4239): setTransGradationMode to true
,D/PhoneStatusBar( 2582): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,I/DBG_DM  ( 4239): [3.19.140541][Line:400][onPause] 
D/StatusBarManagerService( 2421): semi p:4239,o:t
,D/AmoledAdjustTimer( 2421): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4
,D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2421): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@8
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3367): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 3367): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4352, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3367): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3367): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2421): [PWL] Off : 50s ago,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 330, Delta = 0,
,V/AlarmManager( 2421): waitForAlarm result :4,
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/Headlines( 5458): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5458): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5458): Breath 72644 latestRequest time : 1454523160885 current time : 1454523233530,
,I/VacuumService( 2735): Vacuum at: now=1454523233776 tag=VacuumService,
,E/Watchdog( 2421): !@Sync 4,
,D/AmoledAdjustTimer( 2421): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4,
,V/AlarmManager( 2421): waitForAlarm result :8,
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
V/HeadsetService( 3367): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3367): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2421): waitForAlarm result :8,
,D/Headlines( 5458): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5458): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5458): Breath 90024 latestRequest time : 1454523160885 current time : 1454523250909,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4381, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
D/BatteryService( 2421): stay LED for fully charged,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3367): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3367): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2421): [PWL] Off : 75s ago,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2421): stay LED for fully charged,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3367): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3367): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2421): !@Sync 5,
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3367): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3367): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4381, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
V/HeadsetService( 3367): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
D/HeadsetStateMachine( 3367): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2421): [PWL] Off : 105s ago,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3367): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3367): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,V/AlarmManager( 2421): waitForAlarm result :4,
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/Headlines( 5458): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5458): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
D/Headlines( 5458): Breath 132681 latestRequest time : 1454523160885 current time : 1454523293566
,D/Headlines( 5458): stop 
,D/Headlines( 5458): Breath.onDestroy : 
I/ActivityManager( 2421): Killing 5375:com.policydm/1000 (adj 15): empty #43
,I/PhenotypeConfigurator( 2735): Scheduling Phenotype for one-off execution 5180 seconds from now (1454523293957)
,D/GetConfigurationSnapshotOperation( 2735): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2735): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 2735): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2735): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2735): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 2735): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 2735): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2735): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 2735): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 2421): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/dalvikvm( 2735): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
,W/dalvikvm( 2735): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2735): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 2735): Thread-113(HTTPLog):isShipBuild true
,I/System.out( 2735): Thread-113(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/Watchdog( 2421): !@Sync 6
,D/dalvikvm( 2735): GC_CONCURRENT freed 1714K, 22% free 11805K/15120K, paused 9ms+8ms, total 82ms
,D/dalvikvm( 2735): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/LocationManagerService( 2421): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,V/AlarmManager( 2421): waitForAlarm result :8,
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3367): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3367): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2421): [PWL] Off : 140s ago,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2421): !@Sync 7,
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3367): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3367): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,

```
