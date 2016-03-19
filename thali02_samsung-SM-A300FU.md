#### Test 62548124d9c0fd9_thali02_samsung-SM-A300FU Logs


```
--------- beginning of main
03-19 12:52:54.505   291   291 E SMD     : DCD OFF
--------- beginning of system
03-19 12:52:54.945  1016  1078 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-19 12:52:54.945  1016  1078 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4286, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 12:52:54.945  1016  1078 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:52:54.945  1016  1078 D BatteryService: stay LED for charging
03-19 12:52:54.945  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 12:52:54.945  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-19 12:52:54.945  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 12:52:54.955  1016  1016 I MotionRecognitionService: Plugged
03-19 12:52:54.955  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
03-19 12:52:54.955  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 12:52:54.955  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-19 12:52:54.965  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-19 12:52:54.965  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
03-19 12:52:54.975  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:52:54.975  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:52:54.975  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:52:54.975  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 12:52:54.975  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:52:55.705  1016  1096 V AlarmManager: waitForAlarm result :4
03-19 12:52:55.715  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:52:55.715  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:55.715  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
03-19 12:52:55.745  5575  5575 D AndroidRuntime: 
03-19 12:52:55.745  5575  5575 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-19 12:52:55.755  5575  5575 D AndroidRuntime: CheckJNI is OFF
03-19 12:52:55.755  5575  5575 D AndroidRuntime: readGMSProperty: start
03-19 12:52:55.755  5575  5575 D AndroidRuntime: readGMSProperty: already setted!!
03-19 12:52:55.755  5575  5575 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-19 12:52:55.755  5575  5575 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-19 12:52:55.755  5575  5575 D AndroidRuntime: readGMSProperty: end
03-19 12:52:55.755  5575  5575 D AndroidRuntime: addProductProperty: start
03-19 12:52:55.885  5575  5575 E AffinityControl: AffinityControl: registerfunction enter
03-19 12:52:55.905  5575  5575 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-19 12:52:55.915  1016  1218 E PersonaManagerService: inState():  stateMachine is null !!
03-19 12:52:55.915  1016  1218 I PersonaManagerService: PersonaId don't exist
03-19 12:52:55.915  1016  1218 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-19 12:52:55.925  5575  5575 D AndroidRuntime: Shutting down VM
03-19 12:52:55.955  1016  1337 E Watchdog: !@Sync 2
03-19 12:52:56.135  5575  5575 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-19 12:52:56.265  1016  1096 V AlarmManager: waitForAlarm result :4
,03-19 12:52:56.265  1180  1180 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
03-19 12:52:56.265  1180  1180 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
03-19 12:52:56.265  1180  1180 V KeyguardEffectViewController: *** Keyguard wallpaper service already unbounded
,03-19 12:52:56.545   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:52:56.915  1016  1049 I PowerManagerService: [PWL] Off : 5s ago,
03-19 12:52:56.915  1016  1049 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
03-19 12:52:56.915  1016  1049 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
03-19 12:52:56.915  1016  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=1791, ws=null) (elapsedTime=44853)
03-19 12:52:56.915  1016  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=1791, ws=null) (elapsedTime=32466)
,03-19 12:52:57.035  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-19 12:52:57.505   291   291 E SMD     : DCD OFF
,03-19 12:52:57.545   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:52:58.115  1016  1552 W ActivityManager: userId = 0, bbcId = -10000,
03-19 12:52:58.115  1016  1552 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:58.115  1016  1552 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,03-19 12:52:58.125  1016  1078 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:58.125  1016  1078 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:58.125  1016  1078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:58.145  1016  1552 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:58.145  1016  1552 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-19 12:52:58.145  1016  1552 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:58.165  1016  1078 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:58.165  1016  1078 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:58.165  1016  1078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-19 12:52:58.185  1016  1552 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:58.185  1016  1552 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:58.185  1016  1552 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:58.205  1016  1218 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:58.205  1016  1218 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:58.205  1016  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:58.235  1016  1502 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:58.235  1016  1502 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:58.235  1016  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-19 12:52:58.255  1016  1551 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:58.255  1016  1551 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:58.255  1016  1551 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-19 12:52:58.275  1016  3982 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:58.275  1016  3982 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:58.275  1016  3982 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-19 12:52:58.285  1016  1502 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:52:58.285  1016  1502 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:52:58.285  1016  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 12:52:58.545   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 12:52:59.545   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 12:52:59.995  1016  1096 V AlarmManager: waitForAlarm result :8
,03-19 12:53:00.505   291   291 E SMD     : DCD OFF,
,03-19 12:53:00.545   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 12:53:01.545   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,03-19 12:53:01.745  1016  2736 D SSRM:n  : SIOP:: AP = 310
,03-19 12:53:02.035  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-19 12:53:03.505   291   291 E SMD     : DCD OFF
,03-19 12:53:04.995  1016  1521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 12:53:04.995  1016  1521 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4292, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 12:53:04.995  1016  1521 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:53:04.995  1016  1521 D BatteryService: stay LED for charging
03-19 12:53:04.995  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 12:53:04.995  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-19 12:53:04.995  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 12:53:05.005  1016  1016 I MotionRecognitionService: Plugged
03-19 12:53:05.005  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false,
03-19 12:53:05.005  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-19 12:53:05.005  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 12:53:05.005  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
03-19 12:53:05.005  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
03-19 12:53:05.005  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:53:05.015  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 12:53:05.015  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:53:05.025  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-19 12:53:05.025  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:53:06.505   291   291 E SMD     : DCD OFF
,03-19 12:53:06.915  1016  1049 I PowerManagerService: [PWL] Off : 15s ago
,03-19 12:53:06.915  1016  1049 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,03-19 12:53:06.915  1016  1049 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
03-19 12:53:06.915  1016  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=1791, ws=null) (elapsedTime=54857),
03-19 12:53:06.915  1016  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=1791, ws=null) (elapsedTime=42471)
,03-19 12:53:07.035  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-19 12:53:09.505   291   291 E SMD     : DCD OFF,
,03-19 12:53:11.775  1016  2736 D SSRM:n  : SIOP:: AP = 300,
,03-19 12:53:12.045  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-19 12:53:12.515   291   291 E SMD     : DCD OFF,
,03-19 12:53:15.025   270   270 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb71377c8,
03-19 12:53:15.025   270   270 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
03-19 12:53:15.025   270   270 I rmt_storage: wakelock acquired: 1, error no: 42
03-19 12:53:15.025   270   304 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1223461576)
,03-19 12:53:15.045  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-19 12:53:15.045  1016  1218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-19 12:53:15.045  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 12:53:15.045  1016  1218 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4290, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 12:53:15.045  1016  1218 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:53:15.045  1016  1218 D BatteryService: stay LED for charging
03-19 12:53:15.045  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-19 12:53:15.045  1016  1016 I MotionRecognitionService: Plugged
03-19 12:53:15.045  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
03-19 12:53:15.045  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 12:53:15.045  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 12:53:15.065  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 12:53:15.065  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:53:15.075  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:53:15.075  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:53:15.075  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:53:15.075  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 12:53:15.075  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:53:15.095   270   304 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504,
03-19 12:53:15.095   270   304 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,03-19 12:53:15.095   270   304 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1223461576) wakelock released: 1, error no: 0
03-19 12:53:15.095   270   304 I rmt_storage: 
,03-19 12:53:15.095   270   270 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb71377c8,
,03-19 12:53:15.505   291   291 E SMD     : DCD OFF,
,03-19 12:53:18.515   291   291 E SMD     : DCD OFF,
,03-19 12:53:21.505   291   291 E SMD     : DCD OFF,
,03-19 12:53:21.725  1016  1096 V AlarmManager: waitForAlarm result :4
,03-19 12:53:21.725  1016  1016 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,03-19 12:53:21.725  1016  1016 V AlarmManagerEXT: <AppSync3 Whitelist>
,03-19 12:53:21.725  1016  1016 V AlarmManagerEXT: (AppSync) ### 0 added ###
,03-19 12:53:21.735  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-19 12:53:21.735  1180  1180 D KeyguardUpdateMonitor: handleTimeUpdate
,03-19 12:53:21.735  1180  1180 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-19 12:53:21.745  1180  1180 D SecKeyguardClockView: HomeTimezone(): 1
,03-19 12:53:21.745  1180  1180 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 12:53:21.745  1180  1180 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-19 12:53:21.745  1180  1180 I KeyguardEffectViewController: *** don't update sliding image ***
,03-19 12:53:21.785  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 12:53:21.785  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 12:53:21.795  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 12:53:21.795  1180  1180 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-19 12:53:21.815  1016  2736 D SSRM:n  : SIOP:: AP = 290
,03-19 12:53:21.815  1180  1180 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 12:53:21.915  1016  1049 I PowerManagerService: [PWL] Off : 30s ago
,03-19 12:53:21.915  1016  1049 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
03-19 12:53:21.915  1016  1049 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,03-19 12:53:21.915  1016  1049 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10011, pid=1791, ws=null) (elapsedTime=57473)
,03-19 12:53:24.505   291   291 E SMD     : DCD OFF
,03-19 12:53:25.095  1016  3992 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 12:53:25.095  1016  3992 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4316, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 12:53:25.095  1016  3992 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:53:25.095  1016  3992 D BatteryService: stay LED for charging
,03-19 12:53:25.095  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 12:53:25.095  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-19 12:53:25.095  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 12:53:25.095  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 12:53:25.095  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-19 12:53:25.095  1016  1016 I MotionRecognitionService: Plugged
03-19 12:53:25.095  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 12:53:25.105  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 12:53:25.105  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:53:25.105  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:53:25.115  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
03-19 12:53:25.115  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:53:25.115  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 12:53:25.115  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:53:25.955  1016  1337 E Watchdog: !@Sync 3
,03-19 12:53:26.545   333   333 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
03-19 12:53:26.545   333   333 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,03-19 12:53:27.335  5389  5389 D FactoryTest: Not factory mode
,03-19 12:53:27.335  5389  5389 D FactoryTest: Not factory mode. isFactoryMode() returend false
,03-19 12:53:27.335  5389  5389 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
03-19 12:53:27.335  5389  5389 D MTPRx   : still no open session command from host, so toast
,03-19 12:53:27.335  5389  5389 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
03-19 12:53:27.335  5389  5389 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,03-19 12:53:27.335  5389  5389 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:108318
03-19 12:53:27.335  1016  1551 E PersonaManagerService: inState():  stateMachine is null !!
,03-19 12:53:27.335  1016  1551 I PersonaManagerService: PersonaId don't exist
03-19 12:53:27.335  1016  1551 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,03-19 12:53:27.345  1016  1551 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,03-19 12:53:27.345  1016  1551 W ActivityManager: userId = 0, bbcId = -10000,
,03-19 12:53:27.345  1016  1551 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
,03-19 12:53:27.345  1016  1551 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings,
,03-19 12:53:27.355  1016  1551 W ActivityManager: mDVFSHelper.acquire(),
,03-19 12:53:27.365  1016  1016 V ActivityManager: Display changed displayId=0
,03-19 12:53:27.375  1016  1551 D PersonaManager: isKioskContainerExistOnDevice
,03-19 12:53:27.385  1016  1551 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
03-19 12:53:27.385  1016  1551 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,03-19 12:53:27.385  1016  1551 D InputDispatcher: Focused application set to: xxxx
03-19 12:53:27.385  1016  1551 D InputDispatcher: Focus left window: 4356
,03-19 12:53:27.385  5389  5389 E MTPRx   : started activity for popup
,03-19 12:53:27.385  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-19 12:53:27.385  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-19 12:53:27.405  5389  5389 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-19 12:53:27.415  5389  5389 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-19 12:53:27.415  5389  5389 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-19 12:53:27.415  5389  5389 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-19 12:53:27.415  5389  5389 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-19 12:53:27.415  5389  5389 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-19 12:53:27.425  5389  5389 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : false
,03-19 12:53:27.455  5389  5389 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,03-19 12:53:27.465  5389  5389 D PhoneWindow: *FMB* installDecor mIsFloating : true
,03-19 12:53:27.465  5389  5389 D PhoneWindow: *FMB* installDecor flags : 8388610
,03-19 12:53:27.475  5389  5612 D OpenGLRenderer: Render dirty regions requested: true
,03-19 12:53:27.485  1016  1078 D ActivityManager: post active user change for 0 fullscreen false record.isFloatingActivity() false
,03-19 12:53:27.485  1016  1078 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-19 12:53:27.485  1016  1078 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-19 12:53:27.485  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-19 12:53:27.485  1016  1016 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
03-19 12:53:27.485  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
,03-19 12:53:27.505  5389  5389 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,03-19 12:53:27.505  5389  5389 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-19 12:53:27.515   291   291 E SMD     : DCD OFF
,03-19 12:53:27.525   257   257 I SurfaceFlinger: id=13 createSurf (73x73),1 flag=4, TettingsRec
,03-19 12:53:27.525  1016  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-19 12:53:27.535  1016  1029 D InputDispatcher: Focus entered window: 5389
,03-19 12:53:27.535  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-19 12:53:27.535  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-19 12:53:27.535  5389  5389 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-19 12:53:27.535  5389  5612 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-19 12:53:27.535  5389  5612 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-19 12:53:27.535  5389  5612 I Adreno-EGL: Build Date: 04/06/15 Mon
03-19 12:53:27.535  5389  5612 I Adreno-EGL: Local Branch: 
03-19 12:53:27.535  5389  5612 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-19 12:53:27.535  5389  5612 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-19 12:53:27.535  5389  5612 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
03-19 12:53:27.535  5389  5612 I OpenGLRenderer: Initialized EGL, version 1.4
,03-19 12:53:27.555  5389  5612 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-19 12:53:27.555  5389  5612 D OpenGLRenderer: Enabling debug mode 0
,03-19 12:53:27.575  5389  5389 V ActivityThread: updateVisibility : ActivityRecord{2b7b83b token=android.os.BinderProxy@1337a91f {com.android.settings/com.android.settings.SettingsReceiverActivity}} show : true
,03-19 12:53:27.605  5389  5389 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1337a91f time:108583
,03-19 12:53:27.625  1016  1047 I ActivityManager: Displayed Component not be shown by security: +235ms (total +254ms)
,03-19 12:53:27.625  1016  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{182922bd u0 com.android.settings/.SettingsReceiverActivity t58} time:108596
03-19 12:53:27.625  1016  1047 W ActivityManager: mDVFSHelper.release()
,03-19 12:53:30.525   291   291 E SMD     : DCD OFF,
,03-19 12:53:31.555   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 12:53:31.835  1016  2736 D SSRM:n  : SIOP:: AP = 290,
,03-19 12:53:32.045  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-19 12:53:32.555   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 12:53:33.525   291   291 E SMD     : DCD OFF,
,03-19 12:53:33.555   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 12:53:34.545   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 12:53:35.135  1016  1932 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 12:53:35.145  1016  1932 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4295, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 12:53:35.145  1016  1932 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:53:35.145  1016  1932 D BatteryService: stay LED for charging
,03-19 12:53:35.145  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 12:53:35.145  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 12:53:35.145  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 12:53:35.145  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 12:53:35.155  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-19 12:53:35.155  1016  1016 I MotionRecognitionService: Plugged
03-19 12:53:35.155  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 12:53:35.155  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 12:53:35.155  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:53:35.175  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:53:35.175  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:53:35.175  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:53:35.175  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 12:53:35.175  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:53:35.555   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 12:53:36.525   291   291 E SMD     : DCD OFF
,03-19 12:53:36.555   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,03-19 12:53:39.525   291   291 E SMD     : DCD OFF
,03-19 12:53:41.555   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 12:53:41.865  1016  2736 D SSRM:n  : SIOP:: AP = 290,
,03-19 12:53:41.935  1016  1049 I PowerManagerService: [PWL] Off : 50s ago,
,03-19 12:53:42.525   291   291 E SMD     : DCD OFF,
,03-19 12:53:42.545   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 12:53:43.545   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 12:53:44.545   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 12:53:45.185  1016  1551 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-19 12:53:45.515   291   291 E SMD     : DCD OFF
,03-19 12:53:45.555   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 12:53:46.545   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,03-19 12:53:48.535   291   291 E SMD     : DCD OFF,
,03-19 12:53:51.535   291   291 E SMD     : DCD OFF,
,03-19 12:53:51.895  1016  2736 D SSRM:n  : SIOP:: AP = 290,
,03-19 12:53:52.045  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-19 12:53:54.535   291   291 E SMD     : DCD OFF,
,03-19 12:53:55.235  1016  3982 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-19 12:53:55.235  1016  3982 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
03-19 12:53:55.235  1016  3982 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:53:55.235  1016  3982 D BatteryService: stay LED for charging
03-19 12:53:55.235  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-19 12:53:55.245  1016  1016 I MotionRecognitionService: Plugged
03-19 12:53:55.245  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 12:53:55.245  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 12:53:55.245  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate,
03-19 12:53:55.245  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 12:53:55.245  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 12:53:55.255  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-19 12:53:55.255  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:53:55.265  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:53:55.265  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:53:55.265  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:53:55.265  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 12:53:55.265  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:53:55.955  1016  1337 E Watchdog: !@Sync 4
,03-19 12:53:56.555   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 12:53:57.535   291   291 E SMD     : DCD OFF
,03-19 12:53:57.555   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 12:53:58.555   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:53:59.555   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:53:59.995  1016  1096 V AlarmManager: waitForAlarm result :8,
,03-19 12:54:00.535   291   291 E SMD     : DCD OFF,
,03-19 12:54:00.565   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:54:01.555   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,03-19 12:54:01.925  1016  2736 D SSRM:n  : SIOP:: AP = 290
,03-19 12:54:03.535   291   291 E SMD     : DCD OFF,
,03-19 12:54:05.285  1016  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 12:54:05.285  1016  1497 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4301, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 12:54:05.285  1016  1497 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:54:05.285  1016  1497 D BatteryService: stay LED for charging,
03-19 12:54:05.285  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-19 12:54:05.285  1016  1016 I MotionRecognitionService: Plugged
03-19 12:54:05.285  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 12:54:05.295  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 12:54:05.295  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 12:54:05.295  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-19 12:54:05.295  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 12:54:05.305  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 12:54:05.305  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:54:05.315  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
03-19 12:54:05.315  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:54:05.315  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:54:05.315  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-19 12:54:05.315  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:54:06.535   291   291 E SMD     : DCD OFF,
,03-19 12:54:06.935  1016  1049 I PowerManagerService: [PWL] Off : 75s ago
,03-19 12:54:09.535   291   291 E SMD     : DCD OFF
,03-19 12:54:11.955  1016  2736 D SSRM:n  : SIOP:: AP = 290,
,03-19 12:54:12.045  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-19 12:54:12.545   291   291 E SMD     : DCD OFF,
,03-19 12:54:15.335  1016  1552 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 12:54:15.335  1016  1552 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4296, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 12:54:15.335  1016  1552 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:54:15.335  1016  1552 D BatteryService: stay LED for charging
,03-19 12:54:15.335  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 12:54:15.345  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 12:54:15.345  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 12:54:15.345  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 12:54:15.345  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 12:54:15.355  1016  1016 I MotionRecognitionService: Plugged,
03-19 12:54:15.355  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 12:54:15.355  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 12:54:15.355  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:54:15.365  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
03-19 12:54:15.365  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:54:15.365  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:54:15.365  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 12:54:15.365  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:54:15.535   291   291 E SMD     : DCD OFF
,03-19 12:54:16.565   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:54:17.555   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:54:18.545   291   291 E SMD     : DCD OFF
,03-19 12:54:18.565   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:54:19.555   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:54:20.555   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:54:21.535   291   291 E SMD     : DCD OFF
,03-19 12:54:21.555   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,03-19 12:54:21.975  1016  2736 D SSRM:n  : SIOP:: AP = 290,
,03-19 12:54:24.465  1016  1096 V AlarmManager: waitForAlarm result :4,
,03-19 12:54:24.465  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-19 12:54:24.465  1180  1180 D KeyguardUpdateMonitor: handleTimeUpdate
,03-19 12:54:24.465  1180  1180 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-19 12:54:24.475  1180  1180 D SecKeyguardClockView: HomeTimezone(): 1,
,03-19 12:54:24.485  1180  1180 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
03-19 12:54:24.485  1180  1180 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-19 12:54:24.485  1180  1180 I KeyguardEffectViewController: *** don't update sliding image ***
,03-19 12:54:24.525  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 12:54:24.525  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 12:54:24.535  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 12:54:24.545  1016  1329 W ActivityManager: userId = 0, bbcId = -10000
03-19 12:54:24.545   291   291 E SMD     : DCD OFF
,03-19 12:54:24.545  1016  1329 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:54:24.545  1016  1329 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-19 12:54:24.545  1016  3982 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:54:24.545  1016  3982 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:54:24.545  1016  3982 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-19 12:54:24.555  1180  1180 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-19 12:54:24.565  1180  1180 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,03-19 12:54:24.575  1619  5638 I VacuumService: Vacuum at: now=1458388464593 tag=VacuumService
,03-19 12:54:24.635  1016  1078 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:54:24.635  1016  1078 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:54:24.635  1016  1078 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-19 12:54:24.645  1016  1521 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:54:24.645  1016  1521 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 12:54:24.645  1016  1521 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-19 12:54:24.655  1016  1497 W ActivityManager: userId = 0, bbcId = -10000
,03-19 12:54:24.655  1016  1497 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-19 12:54:24.655  1016  1497 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-19 12:54:25.385  1016  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 12:54:25.385  1016  1028 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4301, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 12:54:25.385  1016  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:54:25.385  1016  1028 D BatteryService: stay LED for charging
03-19 12:54:25.385  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 12:54:25.385  1016  1016 I MotionRecognitionService: Plugged
,03-19 12:54:25.385  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 12:54:25.395  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 12:54:25.395  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-19 12:54:25.395  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 12:54:25.395  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 12:54:25.405  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 12:54:25.405  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:54:25.415  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:54:25.415  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:54:25.415  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:54:25.415  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-19 12:54:25.415  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:54:25.955  1016  1337 E Watchdog: !@Sync 5
,03-19 12:54:27.555   291   291 E SMD     : DCD OFF
,03-19 12:54:30.555   291   291 E SMD     : DCD OFF,
,03-19 12:54:32.005  1016  2736 D SSRM:n  : SIOP:: AP = 290,
,03-19 12:54:32.045  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-19 12:54:33.555   291   291 E SMD     : DCD OFF,
,03-19 12:54:35.435  1016  1551 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 12:54:35.435  1016  1551 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4302, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 12:54:35.435  1016  1551 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:54:35.435  1016  1551 D BatteryService: stay LED for charging
03-19 12:54:35.435  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-19 12:54:35.435  1016  1016 I MotionRecognitionService: Plugged
,03-19 12:54:35.445  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 12:54:35.435  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
03-19 12:54:35.445  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 12:54:35.445  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 12:54:35.445  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 12:54:35.455  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 12:54:35.455  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:54:35.465  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:54:35.465  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:54:35.465  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:54:35.465  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 12:54:35.465  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:54:36.555   291   291 E SMD     : DCD OFF
,03-19 12:54:36.935  1016  1049 I PowerManagerService: [PWL] Off : 105s ago,
,03-19 12:54:39.545   291   291 E SMD     : DCD OFF,
,03-19 12:54:41.565   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:54:42.035  1016  2736 D SSRM:n  : SIOP:: AP = 290,
,03-19 12:54:42.555   291   291 E SMD     : DCD OFF,
,03-19 12:54:42.555   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:54:43.555   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:54:44.565   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:54:45.485  1016  1502 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-19 12:54:45.485  1016  1502 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,03-19 12:54:45.485  1016  1502 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:54:45.485  1016  1502 D BatteryService: stay LED for charging
,03-19 12:54:45.485  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-19 12:54:45.485  1016  1016 I MotionRecognitionService: Plugged,
03-19 12:54:45.485  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
03-19 12:54:45.495  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 12:54:45.495  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 12:54:45.495  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 12:54:45.495  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 12:54:45.495  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 12:54:45.505  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:54:45.515  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:54:45.515  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:54:45.515  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:54:45.515  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 12:54:45.515  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:54:45.555   291   291 E SMD     : DCD OFF,
,03-19 12:54:45.565   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:54:46.565   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,03-19 12:54:48.565   291   291 E SMD     : DCD OFF
,03-19 12:54:51.555   291   291 E SMD     : DCD OFF,
,03-19 12:54:52.045  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-19 12:54:52.065  1016  2736 D SSRM:n  : SIOP:: AP = 290,
,03-19 12:54:54.555   291   291 E SMD     : DCD OFF,
,03-19 12:54:55.535  1016  1932 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 12:54:55.535  1016  1932 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4302, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 12:54:55.535  1016  1932 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:54:55.535  1016  1932 D BatteryService: stay LED for charging
,03-19 12:54:55.535  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 12:54:55.545  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 12:54:55.545  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 12:54:55.545  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 12:54:55.545  1016  1016 I MotionRecognitionService: Plugged
03-19 12:54:55.545  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 12:54:55.555  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 12:54:55.555  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 12:54:55.555  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
03-19 12:54:55.555  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:54:55.555  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:54:55.555  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:54:55.555  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 12:54:55.555  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:54:55.955  1016  1337 E Watchdog: !@Sync 6
,03-19 12:54:57.565   291   291 E SMD     : DCD OFF
,03-19 12:54:59.995  1016  1096 V AlarmManager: waitForAlarm result :8,
,03-19 12:55:00.555   291   291 E SMD     : DCD OFF,
,03-19 12:55:02.095  1016  2736 D SSRM:n  : SIOP:: AP = 280,
,03-19 12:55:03.565   291   291 E SMD     : DCD OFF,
,03-19 12:55:05.585  1016  1329 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 12:55:06.575   291   291 E SMD     : DCD OFF
,03-19 12:55:09.575   291   291 E SMD     : DCD OFF,
,03-19 12:55:11.575   333   333 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
03-19 12:55:11.575   333   333 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,03-19 12:55:11.955  1016  1049 I PowerManagerService: [PWL] Off : 140s ago,
,03-19 12:55:12.035  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-19 12:55:12.125  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 12:55:12.575   291   291 E SMD     : DCD OFF,
,03-19 12:55:15.575   291   291 E SMD     : DCD OFF,
,03-19 12:55:15.635  1016  1521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 12:55:18.565   291   291 E SMD     : DCD OFF
,03-19 12:55:21.575   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:55:21.575   291   291 E SMD     : DCD OFF,
,03-19 12:55:22.145  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 12:55:22.575   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:55:23.565   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:55:24.565   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:55:24.575   291   291 E SMD     : DCD OFF,
,03-19 12:55:25.575   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:55:25.685  1016  1548 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 12:55:25.685  1016  1548 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4302, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,03-19 12:55:25.685  1016  1548 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:55:25.685  1016  1548 D BatteryService: stay LED for charging
03-19 12:55:25.685  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 12:55:25.695  1016  1016 I MotionRecognitionService: Plugged
,03-19 12:55:25.695  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 12:55:25.695  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 12:55:25.695  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 12:55:25.705  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 12:55:25.705  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 12:55:25.715  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-19 12:55:25.715  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:55:25.725  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:55:25.725  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:55:25.725  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:55:25.725  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-19 12:55:25.725  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:55:25.955  1016  1337 E Watchdog: !@Sync 7
,03-19 12:55:26.575   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,03-19 12:55:27.575   291   291 E SMD     : DCD OFF
,03-19 12:55:30.585   291   291 E SMD     : DCD OFF,
,03-19 12:55:31.575   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:55:32.045  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-19 12:55:32.175  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 12:55:32.575   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:55:33.575   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:55:33.575   291   291 E SMD     : DCD OFF
,03-19 12:55:34.575   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:55:35.575   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:55:35.735  1016  1218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-19 12:55:36.575   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,03-19 12:55:36.575   291   291 E SMD     : DCD OFF
,03-19 12:55:39.575   291   291 E SMD     : DCD OFF,
,03-19 12:55:42.205  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 12:55:42.595   291   291 E SMD     : DCD OFF,
,03-19 12:55:45.585   291   291 E SMD     : DCD OFF,
,03-19 12:55:45.785  1016  3797 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 12:55:45.785  1016  3797 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4300, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 12:55:45.785  1016  3797 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:55:45.785  1016  3797 D BatteryService: stay LED for charging
,03-19 12:55:45.785  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 12:55:45.795  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 12:55:45.795  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 12:55:45.795  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 12:55:45.795  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 12:55:45.805  1016  1016 I MotionRecognitionService: Plugged
03-19 12:55:45.805  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 12:55:45.805  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 12:55:45.805  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:55:45.815  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:55:45.815  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:55:45.815  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:55:45.815  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 12:55:45.825  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:55:46.575   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:55:47.575   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:55:48.575   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:55:48.595   291   291 E SMD     : DCD OFF
,03-19 12:55:49.575   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:55:50.575   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:55:51.575   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,03-19 12:55:51.585   291   291 E SMD     : DCD OFF,
,03-19 12:55:51.965  1016  1049 I PowerManagerService: [PWL] Off : 180s ago,
,03-19 12:55:52.035  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-19 12:55:52.235  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 12:55:54.595   291   291 E SMD     : DCD OFF,
,03-19 12:55:55.835  1016  3982 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 12:55:55.835  1016  3982 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4302, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 12:55:55.835  1016  3982 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:55:55.835  1016  3982 D BatteryService: stay LED for charging
,03-19 12:55:55.835  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 12:55:55.845  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 12:55:55.845  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 12:55:55.845  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 12:55:55.845  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 12:55:55.855  1016  1016 I MotionRecognitionService: Plugged
03-19 12:55:55.855  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 12:55:55.865  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-19 12:55:55.865  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:55:55.875  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:55:55.875  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:55:55.875  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:55:55.875  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 12:55:55.875  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:55:55.945  1016  1337 E Watchdog: !@Sync 8
,03-19 12:55:57.585   291   291 E SMD     : DCD OFF,
,03-19 12:56:00.595   291   291 E SMD     : DCD OFF,
,03-19 12:56:02.265  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 12:56:03.595   291   291 E SMD     : DCD OFF,
,03-19 12:56:05.885  1016  3797 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-19 12:56:06.585   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:56:06.605   291   291 E SMD     : DCD OFF
,03-19 12:56:07.575   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:56:08.585   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:56:09.575   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:56:09.595   291   291 E SMD     : DCD OFF,
,03-19 12:56:10.585   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:56:11.585   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,03-19 12:56:12.045  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-19 12:56:12.285  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 12:56:12.605   291   291 E SMD     : DCD OFF,
,03-19 12:56:15.595   291   291 E SMD     : DCD OFF,
,03-19 12:56:15.945  1016  1329 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 12:56:18.615   291   291 E SMD     : DCD OFF
,03-19 12:56:21.615   291   291 E SMD     : DCD OFF,
,03-19 12:56:22.315  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 12:56:24.615   291   291 E SMD     : DCD OFF,
,03-19 12:56:24.675  1016  1096 V AlarmManager: waitForAlarm result :4,
,03-19 12:56:24.685  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-19 12:56:24.685  1180  1180 D KeyguardUpdateMonitor: handleTimeUpdate
03-19 12:56:24.685  1180  1180 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-19 12:56:24.685  1180  1180 D SecKeyguardClockView: HomeTimezone(): 1,
,03-19 12:56:24.695  1180  1180 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,03-19 12:56:24.705  1180  1180 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-19 12:56:24.705  1180  1180 I KeyguardEffectViewController: *** don't update sliding image ***,
,03-19 12:56:24.715  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 12:56:24.725  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 12:56:24.725  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 12:56:24.755  1180  1180 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-19 12:56:24.765  1180  1180 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 12:56:25.945  1016  1337 E Watchdog: !@Sync 9
,03-19 12:56:25.995  1016  1502 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-19 12:56:27.615   291   291 E SMD     : DCD OFF,
,03-19 12:56:30.615   291   291 E SMD     : DCD OFF
,03-19 12:56:31.595   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:56:32.045  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-19 12:56:32.345  1016  2736 D SSRM:n  : SIOP:: AP = 270
,03-19 12:56:32.595   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:56:33.585   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:56:33.615   291   291 E SMD     : DCD OFF,
,03-19 12:56:34.595   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:56:35.585   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 12:56:36.035  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 12:56:36.045  1016  1029 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 12:56:36.045  1016  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:56:36.045  1016  1029 D BatteryService: stay LED for charging
03-19 12:56:36.045  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 12:56:36.045  1016  1016 I MotionRecognitionService: Plugged
,03-19 12:56:36.045  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 12:56:36.045  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 12:56:36.045  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 12:56:36.055  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 12:56:36.055  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 12:56:36.065  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-19 12:56:36.065  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:56:36.085  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:56:36.085  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:56:36.085  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:56:36.085  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-19 12:56:36.085  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:56:36.595   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,03-19 12:56:36.625   291   291 E SMD     : DCD OFF,
,03-19 12:56:36.965  1016  1049 I PowerManagerService: [PWL] Off : 225s ago,
,03-19 12:56:39.615   291   291 E SMD     : DCD OFF,
,03-19 12:56:42.375  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 12:56:42.625   291   291 E SMD     : DCD OFF,
,03-19 12:56:45.615   291   291 E SMD     : DCD OFF,
,03-19 12:56:46.085  1016  1548 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-19 12:56:46.085  1016  1548 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4303, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 12:56:46.085  1016  1548 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:56:46.085  1016  1548 D BatteryService: stay LED for charging
03-19 12:56:46.085  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 12:56:46.095  1016  1016 I MotionRecognitionService: Plugged
,03-19 12:56:46.095  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 12:56:46.095  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 12:56:46.095  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 12:56:46.095  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 12:56:46.095  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 12:56:46.105  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:56:46.105  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:56:46.105  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-19 12:56:46.105  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:56:46.115  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:56:46.115  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 12:56:46.115  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:56:48.615   291   291 E SMD     : DCD OFF
,03-19 12:56:51.615   291   291 E SMD     : DCD OFF,
,03-19 12:56:52.045  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-19 12:56:52.405  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 12:56:53.185  1016  1087 D TimaService: TIMA: TimaService scheduler is intialized. ,
03-19 12:56:53.185  1016  1087 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,03-19 12:56:53.185  1016  1086 D TimaService: TimaServiceHandler.handleMessage what =1
,03-19 12:56:53.185  1016  1087 I TLC_TIMA_PKM_initialize: initializing...,
03-19 12:56:53.185  1016  1087 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
03-19 12:56:53.185  1016  1087 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
03-19 12:56:53.185  1016  1087 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
03-19 12:56:53.185  1016  1087 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
03-19 12:56:53.185  1016  1087 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040,
03-19 12:56:53.185  1016  1087 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040,
03-19 12:56:53.185  1016  1087 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
03-19 12:56:53.185  1016  1087 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
03-19 12:56:53.185  1016  1087 D QSEECOMAPI: : App is not loaded in QSEE
,03-19 12:56:53.215  1016  1087 D QSEECOMAPI: : Loaded image: APP id = 11
,03-19 12:56:53.225  1016  1087 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded,
,03-19 12:56:53.235  1016  1087 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,03-19 12:56:54.625   291   291 E SMD     : DCD OFF,
,03-19 12:56:55.185  1016  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-19 12:56:55.185  1016  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-19 12:56:55.185  1016  1087 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-19 12:56:55.185  1016  1087 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-19 12:56:55.965  1016  1337 E Watchdog: !@Sync 10,
,03-19 12:56:56.135  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 12:56:56.135  1016  1029 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4301, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 12:56:56.135  1016  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:56:56.135  1016  1029 D BatteryService: stay LED for charging
03-19 12:56:56.135  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 12:56:56.145  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 12:56:56.145  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 12:56:56.145  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 12:56:56.145  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 12:56:56.155  1016  1016 I MotionRecognitionService: Plugged
03-19 12:56:56.155  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 12:56:56.165  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 12:56:56.165  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:56:56.175  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:56:56.175  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:56:56.175  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:56:56.175  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 12:56:56.175  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:56:57.625   291   291 E SMD     : DCD OFF
,03-19 12:56:59.995  1016  1096 V AlarmManager: waitForAlarm result :8,
,03-19 12:57:00.635   291   291 E SMD     : DCD OFF,
,03-19 12:57:01.595   333   333 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
03-19 12:57:01.595   333   333 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,03-19 12:57:02.435  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 12:57:03.635   291   291 E SMD     : DCD OFF,
,03-19 12:57:06.185  1016  1548 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 12:57:06.185  1016  1548 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4302, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 12:57:06.185  1016  1548 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:57:06.185  1016  1548 D BatteryService: stay LED for charging
03-19 12:57:06.185  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 12:57:06.195  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 12:57:06.195  1016  1016 I MotionRecognitionService: Plugged
,03-19 12:57:06.195  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 12:57:06.195  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 12:57:06.195  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 12:57:06.195  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 12:57:06.205  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-19 12:57:06.205  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:57:06.215  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:57:06.215  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:57:06.215  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:57:06.215  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 12:57:06.215  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:57:06.635   291   291 E SMD     : DCD OFF
,03-19 12:57:09.635   291   291 E SMD     : DCD OFF,
,03-19 12:57:12.055  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-19 12:57:12.465  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 12:57:12.645   291   291 E SMD     : DCD OFF,
,03-19 12:57:15.635   291   291 E SMD     : DCD OFF,
,03-19 12:57:16.235  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 12:57:16.235  1016  1029 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4303, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 12:57:16.235  1016  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:57:16.235  1016  1029 D BatteryService: stay LED for charging
,03-19 12:57:16.235  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 12:57:16.245  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 12:57:16.245  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 12:57:16.245  1016  1016 I MotionRecognitionService: Plugged
03-19 12:57:16.245  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
03-19 12:57:16.245  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 12:57:16.245  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 12:57:16.255  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-19 12:57:16.255  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:57:16.265  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:57:16.265  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:57:16.265  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:57:16.265  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 12:57:16.265  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:57:16.595   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:57:17.595   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:57:18.595   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:57:18.645   291   291 E SMD     : DCD OFF
,03-19 12:57:19.595   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:57:20.595   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:57:21.595   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,03-19 12:57:21.645   291   291 E SMD     : DCD OFF,
,03-19 12:57:22.495  1016  2736 D SSRM:n  : SIOP:: AP = 270
,03-19 12:57:24.635   291   291 E SMD     : DCD OFF,
,03-19 12:57:25.955  1016  1337 E Watchdog: !@Sync 11,
,03-19 12:57:26.285  1016  1548 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 12:57:26.605   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:57:26.975  1016  1049 I PowerManagerService: [PWL] Off : 275s ago,
,03-19 12:57:27.605   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:57:27.635   291   291 E SMD     : DCD OFF,
,03-19 12:57:28.605   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:57:29.595   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:57:30.605   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:57:30.645   291   291 E SMD     : DCD OFF,
,03-19 12:57:31.605   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,03-19 12:57:32.055  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-19 12:57:32.525  1016  2736 D SSRM:n  : SIOP:: AP = 270
,03-19 12:57:33.655   291   291 E SMD     : DCD OFF
,03-19 12:57:36.335  1016  3982 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-19 12:57:36.645   291   291 E SMD     : DCD OFF
,03-19 12:57:39.655   291   291 E SMD     : DCD OFF,
,03-19 12:57:41.605   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:57:42.555  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 12:57:42.615   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:57:42.655   291   291 E SMD     : DCD OFF,
,03-19 12:57:43.615   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:57:44.605   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:57:45.605   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:57:45.655   291   291 E SMD     : DCD OFF,
,03-19 12:57:46.385  1016  3796 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 12:57:46.615   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,03-19 12:57:48.655   291   291 E SMD     : DCD OFF,
,03-19 12:57:51.655   291   291 E SMD     : DCD OFF,
,03-19 12:57:52.055  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-19 12:57:52.585  1016  2736 D SSRM:n  : SIOP:: AP = 290,
,03-19 12:57:54.665   291   291 E SMD     : DCD OFF,
,03-19 12:57:55.965  1016  1337 E Watchdog: !@Sync 12,
,03-19 12:57:56.435  1016  1078 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 12:57:56.435  1016  1078 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4301, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 12:57:56.435  1016  1078 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:57:56.435  1016  1078 D BatteryService: stay LED for charging
,03-19 12:57:56.435  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 12:57:56.435  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 12:57:56.445  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 12:57:56.445  1016  1016 I MotionRecognitionService: Plugged
03-19 12:57:56.445  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
03-19 12:57:56.445  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 12:57:56.445  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 12:57:56.455  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 12:57:56.455  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:57:56.465  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:57:56.465  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:57:56.465  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:57:56.465  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 12:57:56.465  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:57:57.655   291   291 E SMD     : DCD OFF
,03-19 12:58:00.665   291   291 E SMD     : DCD OFF,
,03-19 12:58:01.615   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:58:02.605   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 12:58:02.615  1016  2736 D SSRM:n  : SIOP:: AP = 270
,03-19 12:58:03.615   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 12:58:03.655   291   291 E SMD     : DCD OFF
,03-19 12:58:04.625   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:58:05.615   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:58:06.485  1016  1521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 12:58:06.485  1016  1521 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4302, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 12:58:06.485  1016  1521 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:58:06.485  1016  1521 D BatteryService: stay LED for charging
03-19 12:58:06.485  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 12:58:06.485  1016  1016 I MotionRecognitionService: Plugged
03-19 12:58:06.485  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
03-19 12:58:06.485  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 12:58:06.485  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 12:58:06.485  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-19 12:58:06.485  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,03-19 12:58:06.495  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 12:58:06.495  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:58:06.515  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:58:06.515  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:58:06.515  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:58:06.515  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 12:58:06.515  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:58:06.615   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,03-19 12:58:06.665   291   291 E SMD     : DCD OFF,
,03-19 12:58:09.675   291   291 E SMD     : DCD OFF,
,03-19 12:58:12.055  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-19 12:58:12.645  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 12:58:12.675   291   291 E SMD     : DCD OFF,
,03-19 12:58:15.665   291   291 E SMD     : DCD OFF,
,03-19 12:58:16.535  1016  1078 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 12:58:16.535  1016  1078 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4303, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 12:58:16.535  1016  1078 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:58:16.535  1016  1078 D BatteryService: stay LED for charging
03-19 12:58:16.535  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-19 12:58:16.535  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 12:58:16.535  1016  1016 I MotionRecognitionService: Plugged
03-19 12:58:16.535  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 12:58:16.535  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
03-19 12:58:16.545  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 12:58:16.545  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 12:58:16.555  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-19 12:58:16.555  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:58:16.565  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
03-19 12:58:16.565  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:58:16.565  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:58:16.565  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 12:58:16.565  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:58:18.675   291   291 E SMD     : DCD OFF,
,03-19 12:58:21.665   291   291 E SMD     : DCD OFF,
,03-19 12:58:21.975  1016  1049 I PowerManagerService: [PWL] Off : 330s ago,
,03-19 12:58:22.675  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 12:58:24.685   291   291 E SMD     : DCD OFF,
,03-19 12:58:25.965  1016  1337 E Watchdog: !@Sync 13,
,03-19 12:58:26.585  1016  1521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 12:58:26.585  1016  1521 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4301, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 12:58:26.585  1016  1521 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:58:26.585  1016  1521 D BatteryService: stay LED for charging
,03-19 12:58:26.585  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 12:58:26.585  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 12:58:26.585  1016  1016 I MotionRecognitionService: Plugged
03-19 12:58:26.585  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 12:58:26.585  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 12:58:26.595  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 12:58:26.595  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,03-19 12:58:26.595  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:58:26.595  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:58:26.595  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:58:26.595  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 12:58:26.595  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:58:26.595  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-19 12:58:26.595  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:58:26.615   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 12:58:27.615   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 12:58:27.675   291   291 E SMD     : DCD OFF,
,03-19 12:58:28.625   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:58:29.615   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:58:30.615   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:58:30.685   291   291 E SMD     : DCD OFF,
,03-19 12:58:31.625   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,03-19 12:58:32.055  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-19 12:58:32.705  1016  2736 D SSRM:n  : SIOP:: AP = 270
,03-19 12:58:33.675   291   291 E SMD     : DCD OFF,
,03-19 12:58:36.635  1016  1329 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 12:58:36.635  1016  1329 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4302, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 12:58:36.635  1016  1329 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:58:36.635  1016  1329 D BatteryService: stay LED for charging
,03-19 12:58:36.635  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 12:58:36.635  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 12:58:36.635  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 12:58:36.645  1016  1016 I MotionRecognitionService: Plugged
03-19 12:58:36.645  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 12:58:36.645  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 12:58:36.645  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 12:58:36.655  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-19 12:58:36.655  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:58:36.665  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:58:36.665  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:58:36.665  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:58:36.665  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-19 12:58:36.665  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:58:36.675   291   291 E SMD     : DCD OFF
,03-19 12:58:39.685   291   291 E SMD     : DCD OFF,
,03-19 12:58:42.685   291   291 E SMD     : DCD OFF,
,03-19 12:58:42.735  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 12:58:45.695   291   291 E SMD     : DCD OFF,
,03-19 12:58:46.685  1016  1552 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-19 12:58:48.695   291   291 E SMD     : DCD OFF
,03-19 12:58:51.695   291   291 E SMD     : DCD OFF,
,03-19 12:58:52.055  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-19 12:58:52.765  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 12:58:54.695   291   291 E SMD     : DCD OFF,
,03-19 12:58:55.965  1016  1337 E Watchdog: !@Sync 14,
,03-19 12:58:56.625   333   333 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
03-19 12:58:56.625   333   333 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,03-19 12:58:56.735  1016  1502 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 12:58:57.695   291   291 E SMD     : DCD OFF
,03-19 12:59:00.695   291   291 E SMD     : DCD OFF,
,03-19 12:59:02.795  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 12:59:03.695   291   291 E SMD     : DCD OFF,
,03-19 12:59:06.705   291   291 E SMD     : DCD OFF,
,03-19 12:59:06.785  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 12:59:09.695   291   291 E SMD     : DCD OFF
,03-19 12:59:12.055  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-19 12:59:12.705   291   291 E SMD     : DCD OFF
,03-19 12:59:12.825  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 12:59:15.695   291   291 E SMD     : DCD OFF
,03-19 12:59:16.625   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 12:59:16.835  1016  3797 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 12:59:16.835  1016  3797 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4298, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 12:59:16.835  1016  3797 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:59:16.835  1016  3797 D BatteryService: stay LED for charging
03-19 12:59:16.835  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-19 12:59:16.835  1016  1016 I MotionRecognitionService: Plugged
03-19 12:59:16.835  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 12:59:16.835  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
,03-19 12:59:16.835  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 12:59:16.835  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 12:59:16.835  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 12:59:16.845  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 12:59:16.845  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:59:16.865  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:59:16.865  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:59:16.865  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:59:16.865  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 12:59:16.865  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:59:17.625   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 12:59:18.625   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 12:59:18.705   291   291 E SMD     : DCD OFF,
,03-19 12:59:19.625   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:59:20.625   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:59:21.625   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,03-19 12:59:21.705   291   291 E SMD     : DCD OFF,
,03-19 12:59:21.985  1016  1049 I PowerManagerService: [PWL] Off : 390s ago,
,03-19 12:59:22.865  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 12:59:24.715   291   291 E SMD     : DCD OFF,
,03-19 12:59:25.965  1016  1337 E Watchdog: !@Sync 15,
,03-19 12:59:26.635   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:59:26.885  1016  3992 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 12:59:26.885  1016  3992 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4302, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 12:59:26.885  1016  3992 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:59:26.885  1016  3992 D BatteryService: stay LED for charging
03-19 12:59:26.885  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-19 12:59:26.885  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 12:59:26.895  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 12:59:26.895  1016  1016 I MotionRecognitionService: Plugged,
03-19 12:59:26.895  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
03-19 12:59:26.895  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 12:59:26.895  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 12:59:26.905  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 12:59:26.905  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:59:26.915  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:59:26.915  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:59:26.915  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:59:26.915  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 12:59:26.915  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:59:27.635   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 12:59:27.705   291   291 E SMD     : DCD OFF,
,03-19 12:59:28.635   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:59:29.625   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:59:30.625   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:59:30.705   291   291 E SMD     : DCD OFF,
,03-19 12:59:31.635   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,03-19 12:59:32.055  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-19 12:59:32.875  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 12:59:33.705   291   291 E SMD     : DCD OFF,
,03-19 12:59:36.715   291   291 E SMD     : DCD OFF,
,03-19 12:59:36.935  1016  3797 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 12:59:39.715   291   291 E SMD     : DCD OFF,
,03-19 12:59:41.635   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:59:42.635   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:59:42.715   291   291 E SMD     : DCD OFF,
,03-19 12:59:42.905  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 12:59:43.635   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:59:44.635   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:59:44.755   330   330 I bootchecker: bootchecker wake up!!,
,03-19 12:59:45.635   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 12:59:45.715   291   291 E SMD     : DCD OFF,
,03-19 12:59:46.635   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,03-19 12:59:46.985  1016  1329 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 12:59:46.985  1016  1329 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4317, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 12:59:46.985  1016  1329 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:59:46.985  1016  1329 D BatteryService: stay LED for charging
03-19 12:59:46.985  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-19 12:59:46.985  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 12:59:46.985  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 12:59:46.995  1016  1016 I MotionRecognitionService: Plugged
03-19 12:59:46.995  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
03-19 12:59:46.995  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 12:59:46.995  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,03-19 12:59:47.005  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 12:59:47.005  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:59:47.015  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:59:47.015  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:59:47.015  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:59:47.015  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 12:59:47.015  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:59:48.725   291   291 E SMD     : DCD OFF
,03-19 12:59:51.725   291   291 E SMD     : DCD OFF,
,03-19 12:59:52.055  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-19 12:59:52.935  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 12:59:54.725   291   291 E SMD     : DCD OFF,
,03-19 12:59:55.965  1016  1337 E Watchdog: !@Sync 16,
,03-19 12:59:57.035  1016  1552 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 12:59:57.035  1016  1552 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4320, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 12:59:57.035  1016  1552 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 12:59:57.035  1016  1552 D BatteryService: stay LED for charging
03-19 12:59:57.035  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
03-19 12:59:57.035  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 12:59:57.035  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 12:59:57.045  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 12:59:57.045  1016  1016 I MotionRecognitionService: Plugged
03-19 12:59:57.045  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
03-19 12:59:57.045  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 12:59:57.045  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 12:59:57.045  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 12:59:57.065  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:59:57.065  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-19 12:59:57.065  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-19 12:59:57.065  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 12:59:57.065  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 12:59:57.735   291   291 E SMD     : DCD OFF
,03-19 12:59:59.985  1016  1096 V AlarmManager: waitForAlarm result :8,
03-19 12:59:59.985  1016  1096 V AlarmManager: No more alarm at this time.nowELAPSED=500965 batch.start=515437
,03-19 13:00:00.735   291   291 E SMD     : DCD OFF,
,03-19 13:00:01.635   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 13:00:02.635   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 13:00:02.965  1016  2736 D SSRM:n  : SIOP:: AP = 260
,03-19 13:00:03.645   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 13:00:03.735   291   291 E SMD     : DCD OFF,
,03-19 13:00:04.645   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 13:00:05.635   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 13:00:06.635   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,03-19 13:00:06.735   291   291 E SMD     : DCD OFF,
,03-19 13:00:07.085  1016  1551 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:00:07.085  1016  1551 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4320, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:00:07.085  1016  1551 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:00:07.085  1016  1551 D LightsService: [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1016) 
03-19 13:00:07.085  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-19 13:00:07.085  1016  1551 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
03-19 13:00:07.085  1016  1077 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
,03-19 13:00:07.085  1016  1077 E lights  : write_int failed to open -1,
03-19 13:00:07.085  1016  1077 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,03-19 13:00:07.085  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 13:00:07.085  1016  1551 D BatteryService: turn on LED for fully charged
03-19 13:00:07.085  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 13:00:07.085  1180  1180 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 13:00:07.095  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:00:07.095  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:00:07.095  1016  1016 I MotionRecognitionService: Plugged
03-19 13:00:07.095  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:00:07.095  1016  1029 D SecContentProvider2: uri = 14 selection = getSealedState
03-19 13:00:07.095  1016  1029 D SecContentProvider2: mCursor = null
,03-19 13:00:07.105  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-19 13:00:07.105  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:00:07.115  1016  1497 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -1
,03-19 13:00:07.115  1016  1497 V ApplicationPolicy: isApplicationStateBlocked userId -1 pkgname com.android.systemui
,03-19 13:00:07.115  1016  1016 I ValidateNoPeople: skipping global notification,
03-19 13:00:07.115  1016  1016 D WindowManager: showStatusBarByNotification() mOpenByNotification=false
,03-19 13:00:07.115  1016  1548 D PowerManagerService: [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1180
,03-19 13:00:07.115  1016  1548 I PowerManagerService: !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification (14)
03-19 13:00:07.115  1016  1548 I PowerManagerService: Waking up from sleep (uid 10049)...
03-19 13:00:07.115  1016  1154 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@898a487)
,03-19 13:00:07.115  1016  1548 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
03-19 13:00:07.115  1016  1548 D PowerManagerService: [s] UserActivityState : 0 -> 1
,03-19 13:00:07.125  1180  1831 D KeyguardViewMediator: onScreenTurnedOn, seq = 2
03-19 13:00:07.125  1180  1831 D KeyguardViewMediator: notifyScreenOnLocked
,03-19 13:00:07.125  1016  1548 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
03-19 13:00:07.125  1016  1049 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
,03-19 13:00:07.125  1016  1045 D WindowOrientationListener: sensor enabled
03-19 13:00:07.125  1016  1045 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
,03-19 13:00:07.125  1016  1049 D DisplayPowerController: getFinalBrightness : Summary is 255 -> 255
03-19 13:00:07.125  1016  1049 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-19 13:00:07.125  1016  1049 D DisplayPowerController: getFinalBrightness : Summary is 255 -> 255
,03-19 13:00:07.125  1016  1049 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-19 13:00:07.135  1016  1054 I libsuspend: !@autosuspend_wakeup_count_disable
03-19 13:00:07.135  1016  1054 D DisplayManagerService: !@display_state: OFF -> ON
03-19 13:00:07.135  1016  1054 I libsuspend: !@autosuspend_wakeup_count_disable done
,03-19 13:00:07.135   257   257 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb710b690
03-19 13:00:07.135   257   257 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
03-19 13:00:07.135  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:00:07.135  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:00:07.135  1016  1045 D SensorService: [SO] changed settle time [1]
03-19 13:00:07.135  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:00:07.135  1016  1045 D SensorService: [SO] setDelay [66000000]
03-19 13:00:07.135  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:00:07.135  1016  1045 D SensorService: [SO] activate (ident=0xb7aa4890, enabled=1)
03-19 13:00:07.135  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:00:07.135  1016  1045 D SensorService: [SO] AR_init
03-19 13:00:07.135  1016  1045 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
03-19 13:00:07.135   257   257 E qdutils : int qdutils::getHDMINode(): Failed to open fb node 2
03-19 13:00:07.135   257   257 E qdutils : int qdutils::getHDMINode(): Failed to find HDMI node
,03-19 13:00:07.145  1016  1047 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 540 x 960, 60.0 fps, supportedRefreshRates [60.0], density 240, 244.928 x 243.839 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,03-19 13:00:07.145  1016  1016 V ActivityManager: Display changed displayId=0
,03-19 13:00:07.145  1016  1045 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-19 13:00:07.165  1016  1154 D PersonaManager: isKioskContainerExistOnDevice
,03-19 13:00:07.175  1180  1180 D KeyguardViewMediator: handleNotifyScreenOn
,03-19 13:00:07.175  1180  1180 D StatusBarKeyguardViewManager: onScreenTurnedOn()
,03-19 13:00:07.185  1180  1180 D SecKeyguardClockSingleView: onScreenTurnedOn
,03-19 13:00:07.185  1180  1180 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 13:00:07.205  1016  1218 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-19 13:00:07.205  1812  1812 D SamsungIME: showDlgMsgBox : false true true
,03-19 13:00:07.215  1016  1042 W ActivityManager: userId = 0, bbcId = -10000
03-19 13:00:07.215  1016  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-19 13:00:07.215  1016  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,03-19 13:00:07.215  1016  1038 D SensorService: [SO] currT = 508191223000, prevT = 72143322000, diff = 436047901000, [-0.326 0.096 9.941]
03-19 13:00:07.215  1016  1038 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-19 13:00:07.215  1463  1667 D NfcService: call the applyRouting
,03-19 13:00:07.225  1016  1016 I PalmMotion: [PALM] 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1,
03-19 13:00:07.225  1016  1016 E MotionRecognitionService:   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
03-19 13:00:07.225  1016  1016 I PalmMotion: [PALM] SURFACE_PALM_SWIPE: 1
03-19 13:00:07.225  1016  1016 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1016) 
03-19 13:00:07.225  1016  1016 D PalmMotion: [PALM] SETTINGS : [TOUCH: true] [SWEEP: true]
03-19 13:00:07.225  1016  1016 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
03-19 13:00:07.225  1016  1016 D PalmMotion: [PALM] ACCEPTED : [a3ulte_common] PALM_CNT : 2, M_TOUCH : 1000.0, M_SWEEP : 100.0, E_SWEEP : 2.0, IGNORE_M_SWEEP : false
03-19 13:00:07.225  1016  1077 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
03-19 13:00:07.225  1016  1077 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
03-19 13:00:07.225  1016  2736 D SSRM:a  : DeviceInfo:: 000000000000
03-19 13:00:07.225  1016  2736 D SSRM:a  : SettingsAirViewInfo:: 000000000
,03-19 13:00:07.235  1016  1548 W ActivityManager: userId = 0, bbcId = -10000
03-19 13:00:07.235  1016  1548 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-19 13:00:07.235  1016  1548 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,03-19 13:00:07.235  1180  1180 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
,03-19 13:00:07.235  1866  1866 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,03-19 13:00:07.245  1016  1016 D LightsService: [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 1016) 
,03-19 13:00:07.245  1016  1329 D ActivityManager: post active user change for 0 fullscreen false record.isFloatingActivity() false
03-19 13:00:07.245  1016  1329 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-19 13:00:07.245  1016  1016 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
03-19 13:00:07.245  1016  1016 D BatteryService: turn off LED
03-19 13:00:07.245  1016  1077 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
03-19 13:00:07.245  1016  1077 E lights  : write_led_info failed to open -1
03-19 13:00:07.245  1016  1077 E lights  : write_led_info failed to open -1
03-19 13:00:07.245  1016  1077 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
03-19 13:00:07.245  1016  1077 E lights  : write_led_info failed to open -1
03-19 13:00:07.245  1016  1077 E lights  : write_led_info failed to open -1
03-19 13:00:07.245  1016  1077 E lights  : write_led_info failed to open -1
03-19 13:00:07.245  1016  1077 E lights  : write_led_info failed to open -1
03-19 13:00:07.245  1016  1077 E lights  : write_led_info failed to open -1
03-19 13:00:07.245  1016  1077 E lights  : write_led_info failed to open -1
03-19 13:00:07.245  1016  1077 E lights  : write_led_info failed to open -1
,03-19 13:00:07.245  1016  1329 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-19 13:00:07.245  1016  1092 E SmartFaceService: onReceive: android.intent.action.SCREEN_ON
03-19 13:00:07.245  1180  1180 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
03-19 13:00:07.245  1016  1092 W System.err: java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
03-19 13:00:07.245  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
03-19 13:00:07.245  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-19 13:00:07.245  1016  1016 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
03-19 13:00:07.245  1016  1092 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-19 13:00:07.245  1016  1092 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-19 13:00:07.245  1016  1092 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-19 13:00:07.245  1016  1092 W System.err: 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
03-19 13:00:07.245  1016  1092 W System.err: 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
03-19 13:00:07.245  1016  1092 W System.err: 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:468)
03-19 13:00:07.245  1016  1092 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
03-19 13:00:07.245  1016  1092 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
03-19 13:00:07.245  1016  1092 E SmartFaceService: fail to set sysfs 1
03-19 13:00:07.245  1016  1092 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-19 13:00:07.245  1016  1092 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-19 13:00:07.245  1016  1092 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-19 13:00:07.245  1016  1092 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
03-19 13:00:07.245  1016  1092 W System.err: 	at libcore.io.Posix.open(Native Method)
03-19 13:00:07.245  1016  1092 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-19 13:00:07.245  1016  1092 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-19 13:00:07.245  1016  1092 W System.err: 	... 10 more
03-19 13:00:07.255  1016  3982 W ActivityManager: userId = 0, bbcId = -10000
03-19 13:00:07.255  1016  3982 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 13:00:07.255  1016  3982 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-19 13:00:07.255  1180  1180 D PersonaManager: PersonaID is invalid or persona doesn't exists. : -1
03-19 13:00:07.255  1463  1667 D SecNfcJni: RoutingManager::commitRouting
03-19 13:00:07.255  1463  2238 D SecNfcJni: RoutingManager::nfaEeCallback: NFA_EE_UPDATED_EVT
03-19 13:00:07.255  5389  5389 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1337a91f time:508237
03-19 13:00:07.255  1180  1180 D PersonaManager: isKioskContainerExistOnDevice
03-19 13:00:07.255  1180  1180 D PersonaManager: isKioskContainerExistOnDevice
03-19 13:00:07.255  1180  1180 I PhoneStatusBar: Icon Only
03-19 13:00:07.255  1180  1180 I StatusBar: Icon Only
03-19 13:00:07.255  1180  1180 D PanelView: There is/are notification(s) 
03-19 13:00:07.255  1180  1180 D PanelView: kidsfalse mQsExpansionEnabled:true
03-19 13:00:07.265  1180  1180 D PersonaManager: isKioskContainerExistOnDevice
03-19 13:00:07.265  1180  1180 I PhoneStatusBar: Icon Only
03-19 13:00:07.265  1180  1180 I StatusBar: Icon Only
03-19 13:00:07.265  1180  1180 D PanelView: There is/are notification(s) 
03-19 13:00:07.265  1180  1180 D PanelView: kidsfalse mQsExpansionEnabled:true
03-19 13:00:07.265  1180  1180 D StatusBarKeyguardViewManager: callback.onShown()
03-19 13:00:07.265  1016  1932 V KeyguardServiceDelegate: **** SHOWN CALLED ****
03-19 13:00:07.265  1180  1180 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 18 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte level=4
03-19 13:00:07.265  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 18 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
03-19 13:00:07.265  1016  1045 D DisplayPowerController: [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
03-19 13:00:07.265  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
03-19 13:00:07.265  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
03-19 13:00:07.265  1016  1218 W ActivityManager: userId = 0, bbcId = -10000
03-19 13:00:07.265  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-19 13:00:07.265  1016  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 13:00:07.265  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
03-19 13:00:07.265  1016  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
03-19 13:00:07.265  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 13:00:07.265  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 13:00:07.265  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 13:00:07.265  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 13:00:07.265  1180  1180 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 18 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte level=4
03-19 13:00:07.265  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 18 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
03-19 13:00:07.265  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
03-19 13:00:07.265  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
03-19 13:00:07.265  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-19 13:00:07.265  1016  1049 I DisplayPowerController: Unblocked screen on after 141 ms
03-19 13:00:07.265  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
03-19 13:00:07.265  1016  1049 D DisplayPowerState: !@ ColorFade exit
03-19 13:00:07.265  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 13:00:07.265  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 13:00:07.265  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 13:00:07.265  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 13:00:07.265  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
03-19 13:00:07.265  1180  1180 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
03-19 13:00:07.265   257  1162 I SurfaceFlinger: id=12 Removed DolorFade (9/9)
03-19 13:00:07.265   257   449 I SurfaceFlinger: id=12 Removed DolorFade (-2/9)
03-19 13:00:07.265  1016  1049 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
03-19 13:00:07.265  1016  1049 D DisplayPowerController: getFinalBrightness : Summary is 255 -> 255
03-19 13:00:07.265  1016  1049 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
03-19 13:00:07.265  1016  1158 D lights  : lcd : 255 +
03-19 13:00:07.265  1016  1158 D lights  : lcd : 255 -
03-19 13:00:07.265  1016  1049 D DisplayPowerController: getFinalBrightness : Summary is 255 -> 255
03-19 13:00:07.275  1016  1049 D DisplayPowerController: animation target = 255, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
03-19 13:00:07.275  1016  1049 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
03-19 13:00:07.275  1016  1049 D PowerManagerService: SecHardwareInterface.setBatteryADC : true
03-19 13:00:07.275  1016  1016 D InputMethodManagerService: [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,03-19 13:00:07.275  1463  1667 D NfcService: index : 0
03-19 13:00:07.275  1463  1667 D NfcService: index : 1
03-19 13:00:07.285  1016  1038 D SensorService: [SO] currT = 508261166000, prevT = 72143322000, diff = 436117844000, [-0.326 0.096 9.902]
03-19 13:00:07.285  1016  1038 D SensorService: [SO] -0.326 0.096 9.902
03-19 13:00:07.285  1016  1038 D SensorService: [SO] [100 -> 255]
03-19 13:00:07.285  1016  1016 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_ON
03-19 13:00:07.285  1180  1180 D BatteryMeterView: onDraw batteryColor : -1
03-19 13:00:07.285  1180  1180 D KeyguardUpdateMonitor: handleTimeUpdate
03-19 13:00:07.295  1180  1180 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
03-19 13:00:07.295  1016  1042 W ActivityManager: userId = 0, bbcId = -10000
03-19 13:00:07.295  1016  1042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 13:00:07.295  1180  1180 D SecKeyguardClockView: HomeTimezone(): 1
03-19 13:00:07.295  1016  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
03-19 13:00:07.305  1016  1125 E WifiNative-wlan0: do suspend false
03-19 13:00:07.305  1016  1104 E MotionRecognitionService:  handler : SCREEN_ON end
03-19 13:00:07.305  1016  1016 D NotificationService: ACTION_SCREEN_ON
03-19 13:00:07.305  1016  1016 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1016) 
03-19 13:00:07.305  1016  1016 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
03-19 13:00:07.305  1016  1077 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
03-19 13:00:07.305  1016  1077 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
03-19 13:00:07.305  1180  1180 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
03-19 13:00:07.305  1180  1180 I StatusBar: Icon Only
03-19 13:00:07.305  1180  1180 D PanelView: There is/are notification(s) 
03-19 13:00:07.305  1180  1180 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-19 13:00:07.305  1180  1180 I KeyguardEffectViewController: *** don't update sliding image ***
03-19 13:00:07.315   283   736 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
03-19 13:00:07.315   283   736 V voice   : voice_set_parameters: enter: screen_state=on
03-19 13:00:07.315   283   736 V voice   : voice_set_parameters: exit with code(-2)
03-19 13:00:07.315   283   736 V msm8974_platform: platform_set_parameters: enter: screen_state=on
03-19 13:00:07.315   283   736 V msm8974_platform: platform_set_parameters: exit with code(-2)
03-19 13:00:07.315   283   736 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
03-19 13:00:07.315   283   736 V audio_hw_primary: adev_set_parameters: exit
,03-19 13:00:07.325  1016  1047 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_ON
,03-19 13:00:07.325  1016  1047 D IpRemoteDisplayController: Bridge Server is not available
,03-19 13:00:07.325  1016  1041 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
03-19 13:00:07.325  1388  1388 I wpa_supplicant: reset timer : RESET_TIMER 1
03-19 13:00:07.325  1388  1388 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
03-19 13:00:07.325  1388  1388 I wpa_supplicant: P2P: Current p2p state = IDLE
,03-19 13:00:07.325  1388  1388 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,03-19 13:00:07.325  1016  1016 D PersonaManagerService: ACTION_SCREEN_ON onReceive
03-19 13:00:07.325  1016  1062 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_ON called
,03-19 13:00:07.335  1016  3796 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
,03-19 13:00:07.335  1463  1463 I NfcService: When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,03-19 13:00:07.335  1463  2341 D NfcService: call the applyRouting
,03-19 13:00:07.335  1463  2341 D NfcService: Discovery configuration equal, not updating.
03-19 13:00:07.335  1463  2341 D NfcService: index : 0
03-19 13:00:07.335  1463  2341 D NfcService: index : 1
,03-19 13:00:07.345  1180  1180 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
03-19 13:00:07.345  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.SCREEN_ON
,03-19 13:00:07.355  1717  1717 D accuweather: [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,03-19 13:00:07.355  1717  1717 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,03-19 13:00:07.355  1717  1717 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,03-19 13:00:07.355  1717  1717 D accuweather: [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,03-19 13:00:07.355  1717  1717 D accuweather: [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
03-19 13:00:07.355  1717  1717 D accuweather: [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,03-19 13:00:07.355  1717  1717 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
03-19 13:00:07.355  1717  1717 D accuweather: [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 1
,03-19 13:00:07.365  1717  1717 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,03-19 13:00:07.365   257   529 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
03-19 13:00:07.365  1717  1717 D accuweather: [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
,03-19 13:00:07.365   257   529 E qdutils : int qdutils::getHDMINode(): Failed to open fb node 2
03-19 13:00:07.365   257   529 E qdutils : int qdutils::getHDMINode(): Failed to find HDMI node
,03-19 13:00:07.365   257   257 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,03-19 13:00:07.365  1016  1054 D SurfaceControl: Excessive delay in setPowerMode(): 232ms
03-19 13:00:07.365  1016  1054 D PowerManagerService: Excessive delay in !@display_state: ON: 233ms
,03-19 13:00:07.365  1016  5787 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 1
,03-19 13:00:07.365  1016  5788 D MISC PowerHAL: sysfs_write +: /sys/class/input/event3/device/enabled: 1
,03-19 13:00:07.365  1717  1717 E accuweather: [KK AccuPhone]>>> UIM:1488 [0:0] bTM 13 00
,03-19 13:00:07.385  1016  1552 W ActivityManager: userId = 0, bbcId = -10000
,03-19 13:00:07.385  1016  1552 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 13:00:07.385  1016  1552 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,03-19 13:00:07.395  1812  1812 I SamsungIME: getNextShiftState() cursorCapsMode : 0
,03-19 13:00:07.405  1717  1717 D accuweather: [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionNETWORK_SET_TIMEZONE
,03-19 13:00:07.405  1717  1717 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,03-19 13:00:07.405  1717  1717 D accuweather: [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,03-19 13:00:07.405  1717  1717 D accuweather: [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
03-19 13:00:07.405  1717  1717 D accuweather: [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,03-19 13:00:07.405  1717  1717 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,03-19 13:00:07.415  1717  1717 D accuweather: [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 1
,03-19 13:00:07.415  1717  1717 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,03-19 13:00:07.415  1717  1717 D accuweather: [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
,03-19 13:00:07.415  1016  3796 W ActivityManager: userId = 0, bbcId = -10000
,03-19 13:00:07.415  1717  1717 E accuweather: [KK AccuPhone]>>> UIM:1488 [0:0] bTM 13 00
03-19 13:00:07.415  1016  3796 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 13:00:07.415  1016  3796 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 13:00:07.425  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 13:00:07.445  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 13:00:07.445  1016  1154 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,03-19 13:00:07.455  1016  2736 D SSRM:n  : SIOP:: AP = 290
,03-19 13:00:07.455  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 13:00:07.465  1769  1769 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-19 13:00:07.465  1016  5788 D MISC PowerHAL: sysfs_write -: /sys/class/input/event3/device/enabled: 1
03-19 13:00:07.465  1769  1769 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-19 13:00:07.465  1769  1769 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-19 13:00:07.475  1769  1769 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-19 13:00:07.475  1769  1769 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-19 13:00:07.475  1769  1769 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,03-19 13:00:07.475  1769  1769 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-19 13:00:07.475  1769  1769 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
03-19 13:00:07.475  1769  1769 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-19 13:00:07.475  1769  1769 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,03-19 13:00:07.475  1769  1769 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,03-19 13:00:07.475  1769  1769 D daemonapp: [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
03-19 13:00:07.485  1769  1769 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-19 13:00:07.485  1769  1769 D daemonapp: [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,03-19 13:00:07.485  1769  1769 D daemonapp: [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1458409920000
03-19 13:00:07.485  1769  1769 D daemonapp: [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1458388807498
,03-19 13:00:07.485  1769  1769 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-19 13:00:07.485  1769  1769 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-19 13:00:07.495  1769  1769 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-19 13:00:07.495  1769  1769 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-19 13:00:07.495  1769  1769 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-19 13:00:07.495  1769  1769 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-19 13:00:07.505  1769  1769 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-19 13:00:07.525  1016  5787 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 1
,03-19 13:00:07.525  1016  1054 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 1
,03-19 13:00:07.525  1016  1054 D PowerManagerService: Excessive delay in nativeSetInteractive(true): 158ms
03-19 13:00:07.525  1016  1054 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 1
03-19 13:00:07.525  1016  1054 D PowerManagerService: Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 394ms
03-19 13:00:07.525  1016  1054 D PowerManagerService-JNI: Excessive delay in MISC setInteractive(true) while turning screen on: 157ms
03-19 13:00:07.525  1016  1054 I QCOM PowerHAL: Got set_interactive hint
03-19 13:00:07.525  1016  1155 D lights  : button : 1 +
,03-19 13:00:07.535  1180  1180 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-19 13:00:07.555  1016  1155 D lights  : button : 1 -
,03-19 13:00:07.595  1180  1180 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 13:00:07.885  1388  1388 I wpa_supplicant: nl80211: Received scan results (17 BSSes)
,03-19 13:00:07.885  1016  1124 D WifiP2pService: InactiveState{ what=147461 }
,03-19 13:00:07.885  1016  1124 D WifiP2pService: P2pEnabledState{ what=147461 }
03-19 13:00:07.885  1016  1124 D WifiP2pService: DefaultState{ what=147461 }
,03-19 13:00:08.235  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-19 13:00:08.235  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
03-19 13:00:08.235  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 13:00:08.235  1016  2736 D SSRM:a  : DeviceInfo:: 000000000000
03-19 13:00:08.235  1016  2736 D SSRM:a  : SettingsAirViewInfo:: 000000000
,03-19 13:00:08.235  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 13:00:08.235  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 13:00:08.235  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 13:00:08.245  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch
,03-19 13:00:09.025  1016  1155 D lights  : button : 0 +
,03-19 13:00:09.055  1016  1155 D lights  : button : 0 -
,03-19 13:00:09.065  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-19 13:00:09.245  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-19 13:00:09.245  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
03-19 13:00:09.245  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 13:00:09.245  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 13:00:09.245  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 13:00:09.245  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 13:00:09.735   291   291 E SMD     : DCD OFF,
,03-19 13:00:10.205  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-19 13:00:10.655  1016  1038 D SensorService: [SO] -0.326 0.077 9.902
,03-19 13:00:11.125  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch
,03-19 13:00:11.635  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch
,03-19 13:00:12.055  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-19 13:00:12.135  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-19 13:00:12.735   291   291 E SMD     : DCD OFF
,03-19 13:00:14.195  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-19 13:00:14.455  1016  1096 V AlarmManager: waitForAlarm result :4,
,03-19 13:00:14.625  1619  3991 D GCM     : Message class com.google.e.a.a.h,
,03-19 13:00:15.105  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-19 13:00:15.245  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-19 13:00:15.245  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
03-19 13:00:15.245  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 13:00:15.255  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 13:00:15.255  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 13:00:15.255  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 13:00:15.735  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch
,03-19 13:00:15.735   291   291 E SMD     : DCD OFF,
,03-19 13:00:16.145  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch
,03-19 13:00:16.255  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-19 13:00:16.255  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
03-19 13:00:16.255  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 13:00:16.255  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 13:00:16.255  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 13:00:16.255  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 13:00:16.855  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch
,03-19 13:00:17.065  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-19 13:00:17.165  1180  1180 D PersonaManager: isKioskContainerExistOnDevice
,03-19 13:00:17.165  1180  1180 D PersonaManager: isKioskContainerExistOnDevice
03-19 13:00:17.165  1180  1180 I PhoneStatusBar: Icon Only
03-19 13:00:17.165  1180  1180 I StatusBar: Icon Only
03-19 13:00:17.165  1180  1180 D PanelView: There is/are notification(s) 
03-19 13:00:17.165  1180  1180 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-19 13:00:17.245  1180  1180 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false,
,03-19 13:00:17.265  1016  1521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 13:00:17.265  1016  1521 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4271, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:00:17.265  1016  1521 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-19 13:00:17.265  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-19 13:00:17.275  1016  1016 I MotionRecognitionService: Plugged
,03-19 13:00:17.275  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:00:17.275  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-19 13:00:17.275  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:00:17.285  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-19 13:00:17.285  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:00:17.285  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate,
03-19 13:00:17.285  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:00:17.285  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-19 13:00:17.285  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:00:17.285  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:00:17.305  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-19 13:00:17.305  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:00:17.475  1016  2736 D SSRM:n  : SIOP:: AP = 300
,03-19 13:00:18.495  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch
,03-19 13:00:18.665  1180  1180 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 18 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte level=4,
03-19 13:00:18.665  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 18 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
03-19 13:00:18.665  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
03-19 13:00:18.665  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
03-19 13:00:18.665  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-19 13:00:18.665  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
03-19 13:00:18.665  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 13:00:18.665  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 13:00:18.665  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 13:00:18.665  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 13:00:18.735   291   291 E SMD     : DCD OFF,
,03-19 13:00:19.115  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch
,03-19 13:00:19.615  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-19 13:00:19.725  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-19 13:00:20.025  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-19 13:00:20.135  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-19 13:00:20.845  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-19 13:00:21.055  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch
,03-19 13:00:21.155  1016  1038 D SensorService: [SO] -0.326 0.096 9.922,
,03-19 13:00:21.735   291   291 E SMD     : DCD OFF,
,03-19 13:00:22.185  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-19 13:00:22.485  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-19 13:00:23.105  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-19 13:00:24.125  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-19 13:00:24.635  1388  1388 E wpa_supplicant: IAPP Type:32, Func Type: 1,
03-19 13:00:24.635  1388  1388 E wpa_supplicant: Recvd CCXBcnReq token 1 scanMode 1 chan 1 dur 10
03-19 13:00:24.635  1388  1388 E wpa_supplicant: Recvd CCXBcnReq token 2 scanMode 1 chan 6 dur 10
03-19 13:00:24.635  1388  1388 E wpa_supplicant: Recvd CCXBcnReq token 3 scanMode 1 chan 11 dur 10
03-19 13:00:24.635  1388  1388 I wpa_supplicant: ccx_process_beacon_request driver command = CCXBEACONREQ 3 1 1 1 10 2 6 1 10 3 11 1 10
,03-19 13:00:24.715  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, true
,03-19 13:00:24.715  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
03-19 13:00:24.715  1016  1044 D Tethering: interfaceStatusChanged wlan0, true
03-19 13:00:24.715  1388  1388 I wpa_supplicant: IE size = 249
03-19 13:00:24.715  1388  1388 I wpa_supplicant: IE size = 0
03-19 13:00:24.715  1388  1388 I wpa_supplicant: IE size = 182
03-19 13:00:24.715  1388  1388 I wpa_supplicant: IE size = 175
,03-19 13:00:24.735   291   291 E SMD     : DCD OFF,
,03-19 13:00:24.805  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, true
,03-19 13:00:24.805  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
03-19 13:00:24.805  1016  1044 D Tethering: interfaceStatusChanged wlan0, true
03-19 13:00:24.805  1388  1388 I wpa_supplicant: IE size = 249
03-19 13:00:24.805  1388  1388 I wpa_supplicant: IE size = 0
03-19 13:00:24.805  1388  1388 I wpa_supplicant: IE size = 183
03-19 13:00:24.805  1388  1388 I wpa_supplicant: IE size = 0
,03-19 13:00:24.905  1016  1044 D Tethering: interfaceLinkStateChanged wlan0, true
,03-19 13:00:24.905  1016  1044 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
03-19 13:00:24.905  1016  1044 D Tethering: interfaceStatusChanged wlan0, true
03-19 13:00:24.905  1388  1388 I wpa_supplicant: IE size = 249
03-19 13:00:24.905  1388  1388 I wpa_supplicant: IE size = 0
03-19 13:00:24.905  1388  1388 I wpa_supplicant: IE size = 0
,03-19 13:00:25.025  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-19 13:00:25.955  1016  1337 E Watchdog: !@Sync 17,
,03-19 13:00:26.175  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-19 13:00:26.585  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-19 13:00:26.645   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 13:00:27.095  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch
,03-19 13:00:27.145  1016  3796 D PowerManagerService: [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1180 (0x0),
,03-19 13:00:27.325  1016  1552 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 13:00:27.325  1016  1552 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4278, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:00:27.325  1016  1552 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-19 13:00:27.325  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-19 13:00:27.325  1016  1016 I MotionRecognitionService: Plugged,
03-19 13:00:27.325  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:00:27.325  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-19 13:00:27.325  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:00:27.335  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:00:27.335  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:00:27.345  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:00:27.355  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:00:27.355  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:00:27.355  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:00:27.355  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:00:27.355  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-19 13:00:27.355  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:00:27.485  1016  2736 D SSRM:n  : SIOP:: AP = 300
,03-19 13:00:27.645   333   333 I ServiceManager: Waiting for service AtCmdFwd...
,03-19 13:00:27.735   291   291 E SMD     : DCD OFF,
,03-19 13:00:28.645   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 13:00:29.035  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch
,03-19 13:00:29.635   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 13:00:30.165  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-19 13:00:30.645   333   333 I ServiceManager: Waiting for service AtCmdFwd...,
,03-19 13:00:30.745   291   291 E SMD     : DCD OFF,
,03-19 13:00:31.095  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-19 13:00:31.135  1016  1049 D PowerManagerService: [s] UserActivityState : 1 -> 2,
03-19 13:00:31.135  1016  1049 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
03-19 13:00:31.135  1016  1049 D DisplayPowerController: animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
03-19 13:00:31.135  1016  1049 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,03-19 13:00:31.135  1016  1158 D lights  : lcd : 243 +,
,03-19 13:00:31.155  1016  1158 D lights  : lcd : 243 -,
03-19 13:00:31.155  1016  1158 D lights  : lcd : 209 +
,03-19 13:00:31.165  1016  1158 D lights  : lcd : 209 -,
03-19 13:00:31.165  1016  1158 D lights  : lcd : 176 +
,03-19 13:00:31.175  1016  1158 D lights  : lcd : 176 -,
03-19 13:00:31.175  1016  1158 D lights  : lcd : 143 +
,03-19 13:00:31.205  1016  1158 D lights  : lcd : 143 -,
03-19 13:00:31.205  1016  1158 D lights  : lcd : 109 +
,03-19 13:00:31.225  1016  1158 D lights  : lcd : 109 -,
03-19 13:00:31.225  1016  1158 D lights  : lcd : 76 +
,03-19 13:00:31.235  1016  1158 D lights  : lcd : 76 -,
03-19 13:00:31.235  1016  1158 D lights  : lcd : 43 +
,03-19 13:00:31.255  1016  1049 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15,
03-19 13:00:31.255  1016  1158 D lights  : lcd : 43 -
03-19 13:00:31.255  1016  1049 D DisplayPowerController: animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
03-19 13:00:31.255  1016  1158 D lights  : lcd : 15 +
,03-19 13:00:31.265  1016  1158 D lights  : lcd : 15 -,
03-19 13:00:31.265  1016  1049 D DisplayPowerController: getFinalBrightness : Summary is 15 -> 15
03-19 13:00:31.265  1016  1049 D DisplayPowerController: animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-19 13:00:31.475  1180  1180 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 18 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte level=4,
03-19 13:00:31.475  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 18 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
03-19 13:00:31.475  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
03-19 13:00:31.475  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
03-19 13:00:31.475  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-19 13:00:31.475  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
,03-19 13:00:31.475  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 13:00:31.475  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 13:00:31.475  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 13:00:31.475  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 13:00:31.645   333   333 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,03-19 13:00:31.655  1016  1038 D SensorService: [SO] -0.326 0.096 9.922,
,03-19 13:00:32.055  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-19 13:00:32.205  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-19 13:00:33.035  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-19 13:00:33.735   291   291 E SMD     : DCD OFF,
,03-19 13:00:34.165  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
,03-19 13:00:36.205  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch,
03-19 13:00:36.205  1388  1388 E wpa_supplicant: IAPP SNAP_HDR Mismatch
,03-19 13:00:36.745   291   291 E SMD     : DCD OFF,
,03-19 13:00:37.135  1016  1154 V WindowOrientationListener: WindowOrientationListener disabled
03-19 13:00:37.135  1016  1049 D PowerManagerService: [s] UserActivityState : 2 -> 4
03-19 13:00:37.135  1016  1154 D SensorService: [SO] activate (ident=0xb7aa4890, enabled=0)
03-19 13:00:37.135  1016  1049 I PowerManagerService: Nap time (uid 1000)...
,03-19 13:00:37.135  1016  1154 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
03-19 13:00:37.135  1016  1049 D PowerManagerService: handleSandman : startDreaming: false  (canDreamLocked: false  canDozeLocked: false)
03-19 13:00:37.135   257   257 I SurfaceFlinger: id=14 createSurf (540x960),-1 flag=20004, DolorFade
03-19 13:00:37.135  1016  1049 I PowerManagerService: !@[ps] Screen__Off - 1 :  dream(timeout) (2)
03-19 13:00:37.135  1016  1049 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
03-19 13:00:37.135  1016  1049 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
,03-19 13:00:37.135  1016  1049 D PowerManagerService: SecHardwareInterface.setBatteryADC : false
03-19 13:00:37.135  1016  1049 D PowerManagerService: handleSandman : startDreaming: true  (canDreamLocked: false  canDozeLocked: true)
03-19 13:00:37.135  1016  1049 D PowerManagerService: handleSandman : startDream(true)
,03-19 13:00:37.135  1016  1049 E PowerManagerService: handleSandman : startDreaming, but isDreaming false,
,03-19 13:00:37.135  1016  1154 D SensorManager: unregisterListener ::   
03-19 13:00:37.135  1016  1049 I PowerManagerService: Sleeping (uid 1000)...
,03-19 13:00:37.135  1180  1831 D KeyguardViewMediator: onScreenTurnedOff(3)
03-19 13:00:37.135  1016  1049 D PowerManagerService: [s] UserActivityState : 4 -> 0
,03-19 13:00:37.135  1180  1831 I KeyguardEffectViewController: *** KeyguardEffectView getInstanceIfExists ***
03-19 13:00:37.135  1180  1831 D KeyguardEffectViewController: changeWallpaperByScreenOff()
03-19 13:00:37.135  1180  1831 D KeyguardViewMediator: notifyScreenOffLocked
,03-19 13:00:37.155  5389  5389 V ActivityThread: updateVisibility : ActivityRecord{2b7b83b token=android.os.BinderProxy@1337a91f {com.android.settings/com.android.settings.SettingsReceiverActivity}} show : true
,03-19 13:00:37.155  1180  1831 D KeyguardViewMediator: timeout : 5000
,03-19 13:00:37.155  1180  1831 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 2
,03-19 13:00:37.155  1180  1180 D KeyguardViewMediator: handleNotifyScreenOff
03-19 13:00:37.155  1180  1180 D VolumePanel: onScreenTurnedOff()
03-19 13:00:37.155  1180  1180 D VolumePanel: mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,03-19 13:00:37.155  1180  1180 D VolumePanel: mCoverBroadcastReceiver: Screen OFF end
,03-19 13:00:37.165  1180  1180 D SecKeyguardClockSingleView: onScreenTurnedOff
,03-19 13:00:37.165  1016  1049 D PowerManagerService: Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 39ms
,03-19 13:00:37.175  1016  1016 D LightsService: [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 1016) 
,03-19 13:00:37.175  1016  1016 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
03-19 13:00:37.175  1016  1016 D BatteryService: turn on LED for fully charged
03-19 13:00:37.175  1016  1077 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
03-19 13:00:37.175  1016  1077 E lights  : write_int failed to open -1
03-19 13:00:37.175  1016  1077 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,03-19 13:00:37.185  1016  1092 E SmartFaceService: onReceive: android.intent.action.SCREEN_OFF
,03-19 13:00:37.185  1016  1092 W System.err: java.io.FileNotFoundException: /sys/class/camera/rear/rear_sensor_standby: open failed: ENOENT (No such file or directory)
,03-19 13:00:37.185  1016  1092 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-19 13:00:37.185  1016  1092 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-19 13:00:37.185  1016  1092 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
,03-19 13:00:37.185  1016  1049 D DisplayPowerController: ColorFade: onAnimationStart
03-19 13:00:37.185  1016  1049 D DisplayPowerController: getFinalBrightness : Summary is 255 -> 255
03-19 13:00:37.185  1016  1049 D DisplayPowerController: performScreenOffTransition : no brightness animation
,03-19 13:00:37.185  1016  1092 W System.err: 	at com.samsung.android.smartface.SmartFaceService.sysfsWrite(SmartFaceService.java:1150)
03-19 13:00:37.185  1016  1092 W System.err: 	at com.samsung.android.smartface.SmartFaceService.access$1800(SmartFaceService.java:95)
03-19 13:00:37.185  1016  1092 W System.err: 	at com.samsung.android.smartface.SmartFaceService$1.onReceive(SmartFaceService.java:474)
03-19 13:00:37.185  1016  1092 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
03-19 13:00:37.185  1016  1092 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
03-19 13:00:37.185  1016  1092 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-19 13:00:37.185  1016  1092 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-19 13:00:37.185  1016  1092 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-19 13:00:37.185  1016  1092 E SmartFaceService: fail to set sysfs 0
03-19 13:00:37.185  1016  1092 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
03-19 13:00:37.185  1016  1092 W System.err: 	at libcore.io.Posix.open(Native Method)
03-19 13:00:37.185  1016  1092 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-19 13:00:37.185  1016  1092 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-19 13:00:37.185  1016  1092 W System.err: 	... 10 more
,03-19 13:00:37.205  1180  1180 I StatusBar: Icon Only
,03-19 13:00:37.205  1180  1180 D PanelView: There is/are notification(s) 
,03-19 13:00:37.205  1016  1016 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_OFF
,03-19 13:00:37.205  1016  1104 E MotionRecognitionService:  handler : SCREEN_OFF end 
,03-19 13:00:37.215  1016  1016 D NotificationService: ACTION_SCREEN_OFF
03-19 13:00:37.215  1016  1016 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 1016) 
,03-19 13:00:37.215  1016  1016 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
03-19 13:00:37.215  1016  1077 D LightsService: [SvcLED] Lux failed to be updated in 0ms. -> handleForcedSvcLEDTasK
03-19 13:00:37.215  1016  1077 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,03-19 13:00:37.225  1016  1125 E WifiNative-wlan0: do suspend true
,03-19 13:00:37.225   283   283 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,03-19 13:00:37.225   283   283 V voice   : voice_set_parameters: enter: screen_state=off
03-19 13:00:37.225   283   283 V voice   : voice_set_parameters: exit with code(-2)
03-19 13:00:37.225   283   283 V msm8974_platform: platform_set_parameters: enter: screen_state=off
03-19 13:00:37.225   283   283 V msm8974_platform: platform_set_parameters: exit with code(-2)
03-19 13:00:37.225   283   283 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
03-19 13:00:37.225   283   283 V audio_hw_primary: adev_set_parameters: exit
,03-19 13:00:37.235  1180  1180 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,03-19 13:00:37.235  1016  1047 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_OFF
03-19 13:00:37.235  1016  1047 D IpRemoteDisplayController: Bridge Server is not available
,03-19 13:00:37.235  1016  1041 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,03-19 13:00:37.245  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.SCREEN_OFF
,03-19 13:00:37.245  1439  1439 V EmergencyMode: [EmergencyStateReceiver] binteractive [false] why[3]
,03-19 13:00:37.245  1016  1016 D PersonaManagerService: ACTION_SCREEN_OFF onReceive
,03-19 13:00:37.245  1016  1062 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_OFF called
,03-19 13:00:37.255  1463  2670 D NfcService: call the applyRouting
,03-19 13:00:37.255  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.SCREEN_OFF
,03-19 13:00:37.265  1717  1717 D accuweather: [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,03-19 13:00:37.265  1717  1717 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,03-19 13:00:37.265  1016  1042 W ActivityManager: userId = 0, bbcId = -10000,
03-19 13:00:37.265  1016  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 13:00:37.265  1016  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,03-19 13:00:37.275  1016  3796 W ActivityManager: userId = 0, bbcId = -10000
,03-19 13:00:37.275  1016  3796 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 13:00:37.275  1016  3796 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,03-19 13:00:37.275  1717  1717 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,03-19 13:00:37.295  1769  4277 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,03-19 13:00:37.295  1463  2670 D NfcService: index : 0
,03-19 13:00:37.295  1463  2670 D NfcService: index : 1
03-19 13:00:37.295  1717  1717 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,03-19 13:00:37.295  1717  1717 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
03-19 13:00:37.295  1717  1717 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
03-19 13:00:37.295  1717  1717 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,03-19 13:00:37.305  1016  3796 W ActivityManager: userId = 0, bbcId = -10000
,03-19 13:00:37.305  1016  3796 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 13:00:37.305  1016  3796 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 13:00:37.305  1769  1784 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-19 13:00:37.315  1885  1885 E LibSecureUISvc: svc_sock_send_message(suisvc): Error sending data, -1 vs 4: Connection refused
,03-19 13:00:37.315  1016  2736 D SSRM:n  : SIOP:: AP = 300
,03-19 13:00:37.325  1016  1154 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,03-19 13:00:37.335  1769  1778 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-19 13:00:37.345  1717  1717 D accuweather: [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,03-19 13:00:37.345  1717  1717 D accuweather: [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,03-19 13:00:37.345  1717  1717 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
03-19 13:00:37.345  1717  1717 D accuweather: [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
,03-19 13:00:37.345  1016  1552 W ActivityManager: userId = 0, bbcId = -10000
,03-19 13:00:37.345  1016  1552 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-19 13:00:37.345  1016  1552 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,03-19 13:00:37.355  1717  1717 D accuweather: [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,03-19 13:00:37.355  1717  1717 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,03-19 13:00:37.355  1717  1717 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-19 13:00:37.375  1016  3982 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:00:37.385  1016  3982 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4265, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:00:37.385  1016  3982 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:00:37.385  1016  3982 D BatteryService: stay LED for fully charged
03-19 13:00:37.385  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:00:37.385  1016  1016 I MotionRecognitionService: Plugged
03-19 13:00:37.385  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:00:37.385  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:00:37.385  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 13:00:37.385  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:00:37.385  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:00:37.395  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:00:37.395  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:00:37.395  1016  1049 D DisplayPowerState: !@ ColorFade entry
03-19 13:00:37.395  1016  1049 D DisplayPowerController: ColorFade: onAnimationEnd
,03-19 13:00:37.405  1016  1049 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
,03-19 13:00:37.405  1016  1158 D lights  : lcd : 0 +
03-19 13:00:37.405  1016  1049 D DisplayPowerController: performScreenOffTransition : no brightness animation
,03-19 13:00:37.405  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:00:37.405  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:00:37.405  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:00:37.405  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:00:37.405  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:00:37.415  1016  1158 D lights  : lcd : 0 -
,03-19 13:00:37.415  1016  1049 D DisplayPowerController: getFinalBrightness : Summary is 0 -> 0
,03-19 13:00:37.415  1016  1049 D DisplayPowerController: performScreenOffTransition : no brightness animation
03-19 13:00:37.415  1016  1049 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
03-19 13:00:37.415  1016  1049 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,03-19 13:00:37.415  1016  5807 D MISC PowerHAL: sysfs_write +: /sys/class/input/event3/device/enabled: 0
03-19 13:00:37.425  1016  5806 D MISC PowerHAL: sysfs_write +: /sys/class/input/event1/device/enabled: 0
,03-19 13:00:37.425  1016  5806 D MISC PowerHAL: sysfs_write -: /sys/class/input/event1/device/enabled: 0
,03-19 13:00:37.475  1016  5807 D MISC PowerHAL: sysfs_write -: /sys/class/input/event3/device/enabled: 0
,03-19 13:00:37.475  1016  1054 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 0
03-19 13:00:37.475  1016  1054 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 0
03-19 13:00:37.475  1016  1054 D PowerManagerService-JNI: Excessive delay in MISC setInteractive(false) while turning screen off: 54ms
03-19 13:00:37.475  1016  1054 I QCOM PowerHAL: Got set_interactive hint
,03-19 13:00:37.475  1016  1054 D PowerManagerService: Excessive delay in nativeSetInteractive(false): 56ms
03-19 13:00:37.475  1016  1054 D DisplayManagerService: !@display_state: ON -> OFF
,03-19 13:00:37.475   257   257 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb710b690
03-19 13:00:37.475   257   257 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
03-19 13:00:37.475  1016  1047 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 540 x 960, 60.0 fps, supportedRefreshRates [60.0], density 240, 244.928 x 243.839 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,03-19 13:00:37.475   257   257 E qdutils : int qdutils::getHDMINode(): Failed to open fb node 2
03-19 13:00:37.475   257   257 E qdutils : int qdutils::getHDMINode(): Failed to find HDMI node
,03-19 13:00:37.475  1016  1016 V ActivityManager: Display changed displayId=0
,03-19 13:00:37.495  1180  1180 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 18 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte level=4
,03-19 13:00:37.495  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=true ss=SignalStrength: 18 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x4 gsm|lte
03-19 13:00:37.495  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength: iconLevel=4
03-19 13:00:37.495  1180  1180 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataSignalIconId = com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_4 mContentDescriptionPhoneSignal = Full phone signal
,03-19 13:00:37.495  1180  1180 D StatusBar.NetworkController: refreshViews connected={ wifi } level=4 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel=Emergency calls only wifiLabel="Qrsqc0bra" emergencyOnly=true combinedLabel="Qrsqc0bra" mAirplaneMode=false mDataActivity=0 mPhoneSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mQSPhoneSignalIconId=0x7f020139/com.android.systemui:drawable/ic_qs_signal_4 mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x7f020504/com.android.systemui:drawable/stat_sys_signal_4_auto_rotate mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-19 13:00:37.495  1180  1180 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"Qrsqc0bra"
03-19 13:00:37.495  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 13:00:37.495  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 13:00:37.495  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-19 13:00:37.495  1180  1180 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-19 13:00:37.705   257   529 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,03-19 13:00:37.715   257   529 E qdutils : int qdutils::getHDMINode(): Failed to open fb node 2
03-19 13:00:37.715   257   529 E qdutils : int qdutils::getHDMINode(): Failed to find HDMI node
,03-19 13:00:37.715   257   257 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,03-19 13:00:37.715  1016  1054 D SurfaceControl: Excessive delay in setPowerMode(): 237ms
03-19 13:00:37.715  1016  1054 D PowerManagerService: Excessive delay in !@display_state: OFF: 239ms
03-19 13:00:37.715  1016  1054 I libsuspend: !@autosuspend_wakeup_count_enable
,03-19 13:00:37.715  1016  1054 I libsuspend: !@autosuspend_wakeup_count_enable done
03-19 13:00:37.715  1016  1049 I PowerManagerService: [PWL] Off : 0s ago
,03-19 13:00:37.715  1016  1054 D PowerManagerService: Excessive delay in DisplayManagerInternal.requestDisplayStateInternal(mRequestingState): 297ms
,03-19 13:00:39.745   291   291 E SMD     : DCD OFF,
,03-19 13:00:42.155  1016  1096 V AlarmManager: waitForAlarm result :4,
,03-19 13:00:42.175  1180  1180 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,03-19 13:00:42.175  1180  1180 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off,
03-19 13:00:42.175  1180  1180 V KeyguardEffectViewController: *** Keyguard wallpaper service already unbounded
,03-19 13:00:42.725  1016  1049 I PowerManagerService: [PWL] Off : 5s ago
,03-19 13:00:42.755   291   291 E SMD     : DCD OFF
,03-19 13:00:45.745   291   291 E SMD     : DCD OFF,
,03-19 13:00:47.365  1016  2736 D SSRM:n  : SIOP:: AP = 290,
,03-19 13:00:47.445  1016  1551 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:00:47.445  1016  1551 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4310, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:00:47.445  1016  1551 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:00:47.445  1016  1551 D BatteryService: stay LED for fully charged
,03-19 13:00:47.445  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:00:47.445  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 13:00:47.445  1016  1016 I MotionRecognitionService: Plugged
03-19 13:00:47.445  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 13:00:47.445  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:00:47.455  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:00:47.455  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:00:47.465  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:00:47.465  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:00:47.475  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:00:47.475  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:00:47.475  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:00:47.475  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:00:47.475  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:00:48.755   291   291 E SMD     : DCD OFF,
,03-19 13:00:51.745   291   291 E SMD     : DCD OFF,
,03-19 13:00:52.065  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-19 13:00:52.735  1016  1049 I PowerManagerService: [PWL] Off : 15s ago,
,03-19 13:00:54.755   291   291 E SMD     : DCD OFF,
,03-19 13:00:55.965  1016  1337 E Watchdog: !@Sync 18,
,03-19 13:00:56.645   333   333 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
03-19 13:00:56.645   333   333 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,03-19 13:00:57.415  1016  2736 D SSRM:n  : SIOP:: AP = 290,
,03-19 13:00:57.495  1016  1548 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 13:00:57.495  1016  1548 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4318, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:00:57.495  1016  1548 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-19 13:00:57.495  1016  1548 D BatteryService: stay LED for fully charged
03-19 13:00:57.495  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:00:57.505  1016  1016 I MotionRecognitionService: Plugged
03-19 13:00:57.505  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:00:57.505  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-19 13:00:57.505  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:00:57.505  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:00:57.515  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:00:57.525  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:00:57.525  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:00:57.535  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:00:57.535  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:00:57.535  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:00:57.535  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-19 13:00:57.535  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:00:57.755   291   291 E SMD     : DCD OFF,
,03-19 13:00:59.995  1016  1096 V AlarmManager: waitForAlarm result :8,
,03-19 13:01:00.765   291   291 E SMD     : DCD OFF,
,03-19 13:01:03.755   291   291 E SMD     : DCD OFF,
,03-19 13:01:06.765   291   291 E SMD     : DCD OFF,
,03-19 13:01:07.315  1016  1096 V AlarmManager: waitForAlarm result :4
,03-19 13:01:07.315  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-19 13:01:07.315  1180  1180 D KeyguardUpdateMonitor: handleTimeUpdate
,03-19 13:01:07.325  1180  1180 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-19 13:01:07.325  1180  1180 D SecKeyguardClockView: HomeTimezone(): 1
,03-19 13:01:07.325  1180  1180 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
03-19 13:01:07.335  1180  1180 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-19 13:01:07.335  1180  1180 I KeyguardEffectViewController: *** don't update sliding image ***
,03-19 13:01:07.345  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 13:01:07.375  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 13:01:07.375  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 13:01:07.375  1180  1180 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-19 13:01:07.385  1180  1180 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 13:01:07.435  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 13:01:07.565  1016  1548 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:01:07.735  1016  1049 I PowerManagerService: [PWL] Off : 30s ago,
,03-19 13:01:09.765   291   291 E SMD     : DCD OFF,
,03-19 13:01:12.065  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-19 13:01:12.765   291   291 E SMD     : DCD OFF,
,03-19 13:01:15.775   291   291 E SMD     : DCD OFF,
,03-19 13:01:17.505  1016  2736 D SSRM:n  : SIOP:: AP = 270
,03-19 13:01:17.625  1016  1329 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 13:01:17.625  1016  1329 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4320, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:01:17.625  1016  1329 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:01:17.625  1016  1329 D BatteryService: stay LED for fully charged
,03-19 13:01:17.625  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-19 13:01:17.625  1016  1016 I MotionRecognitionService: Plugged
03-19 13:01:17.625  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:01:17.625  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-19 13:01:17.635  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:01:17.635  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:01:17.635  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:01:17.645  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:01:17.645  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:01:17.655  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:01:17.655  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:01:17.655  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:01:17.655  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:01:17.655  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:01:18.775   291   291 E SMD     : DCD OFF
,03-19 13:01:21.645   333   333 I Atfwd_Daemon: Stop the daemon....,
,03-19 13:01:21.765   291   291 E SMD     : DCD OFF,
,03-19 13:01:24.765   291   291 E SMD     : DCD OFF,
,03-19 13:01:25.965  1016  1337 E Watchdog: !@Sync 19,
,03-19 13:01:27.555  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 13:01:27.685  1016  1548 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:01:27.685  1016  1548 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4321, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:01:27.685  1016  1548 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:01:27.685  1016  1548 D BatteryService: stay LED for fully charged
,03-19 13:01:27.685  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:01:27.695  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:01:27.695  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:01:27.695  1016  1016 I MotionRecognitionService: Plugged
,03-19 13:01:27.695  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:01:27.695  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:01:27.705  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:01:27.715  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:01:27.715  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:01:27.725  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:01:27.725  1016  1049 I PowerManagerService: [PWL] Off : 50s ago
03-19 13:01:27.725  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:01:27.725  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:01:27.725  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-19 13:01:27.725  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:01:27.765   291   291 E SMD     : DCD OFF
,03-19 13:01:30.775   291   291 E SMD     : DCD OFF,
,03-19 13:01:32.065  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-19 13:01:33.775   291   291 E SMD     : DCD OFF,
,03-19 13:01:36.785   291   291 E SMD     : DCD OFF,
,03-19 13:01:37.575  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:01:37.745  1016  1551 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:01:39.775   291   291 E SMD     : DCD OFF,
,03-19 13:01:42.785   291   291 E SMD     : DCD OFF,
,03-19 13:01:45.775   291   291 E SMD     : DCD OFF,
,03-19 13:01:47.625  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:01:47.815  1016  1078 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:01:47.815  1016  1078 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:01:47.815  1016  1078 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:01:47.815  1016  1078 D BatteryService: stay LED for fully charged
03-19 13:01:47.815  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:01:47.815  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:01:47.815  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:01:47.815  1016  1016 I MotionRecognitionService: Plugged
,03-19 13:01:47.825  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:01:47.825  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
03-19 13:01:47.825  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:01:47.835  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:01:47.835  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:01:47.845  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:01:47.845  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:01:47.845  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:01:47.845  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:01:47.845  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:01:48.785   291   291 E SMD     : DCD OFF
,03-19 13:01:51.785   291   291 E SMD     : DCD OFF,
,03-19 13:01:52.065  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-19 13:01:52.735  1016  1049 I PowerManagerService: [PWL] Off : 75s ago,
,03-19 13:01:53.185  1016  1087 D TimaService: TIMA: TimaService scheduler is intialized. ,
03-19 13:01:53.185  1016  1087 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
03-19 13:01:53.185  1016  1086 D TimaService: TimaServiceHandler.handleMessage what =1
,03-19 13:01:54.025  1016  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-19 13:01:54.025  1016  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-19 13:01:54.025  1016  1087 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-19 13:01:54.025  1016  1087 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-19 13:01:54.785   291   291 E SMD     : DCD OFF,
,03-19 13:01:55.965  1016  1337 E Watchdog: !@Sync 20,
,03-19 13:01:57.675  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:01:57.795   291   291 E SMD     : DCD OFF,
,03-19 13:01:57.875  1016  3797 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-19 13:01:59.995  1016  1096 V AlarmManager: waitForAlarm result :8,
,03-19 13:02:00.795   291   291 E SMD     : DCD OFF,
,03-19 13:02:03.785   291   291 E SMD     : DCD OFF,
,03-19 13:02:06.795   291   291 E SMD     : DCD OFF,
,03-19 13:02:07.695  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:02:07.935  1016  1502 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-19 13:02:09.805   291   291 E SMD     : DCD OFF,
,03-19 13:02:12.065  1016  2757 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,03-19 13:02:12.805   291   291 E SMD     : DCD OFF,
,03-19 13:02:15.805   291   291 E SMD     : DCD OFF,
,03-19 13:02:17.745  1016  2736 D SSRM:n  : SIOP:: AP = 260
,03-19 13:02:17.995  1016  3992 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:02:17.995  1016  3992 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:02:17.995  1016  3992 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:02:17.995  1016  3992 D BatteryService: stay LED for fully charged
,03-19 13:02:17.995  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:02:17.995  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:02:17.995  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:02:18.005  1016  1016 I MotionRecognitionService: Plugged
03-19 13:02:18.005  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:02:18.005  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:02:18.005  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:02:18.015  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:02:18.015  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:02:18.025  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:02:18.025  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:02:18.025  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:02:18.025  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:02:18.025  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:02:18.805   291   291 E SMD     : DCD OFF
,03-19 13:02:21.805   291   291 E SMD     : DCD OFF,
,03-19 13:02:22.745  1016  1049 I PowerManagerService: [PWL] Off : 105s ago,
,03-19 13:02:24.795   291   291 E SMD     : DCD OFF,
,03-19 13:02:25.965  1016  1337 E Watchdog: !@Sync 21,
,03-19 13:02:27.805   291   291 E SMD     : DCD OFF,
03-19 13:02:27.805  1016  2736 D SSRM:n  : SIOP:: AP = 260
,03-19 13:02:28.055  1016  1932 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:02:28.055  1016  1932 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:02:28.055  1016  1932 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:02:28.055  1016  1932 D BatteryService: stay LED for fully charged
,03-19 13:02:28.055  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:02:28.055  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:02:28.055  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:02:28.065  1016  1016 I MotionRecognitionService: Plugged,
03-19 13:02:28.065  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
03-19 13:02:28.065  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:02:28.065  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:02:28.075  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-19 13:02:28.075  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:02:28.085  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-19 13:02:28.085  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:02:28.085  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:02:28.085  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:02:28.085  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:02:30.815   291   291 E SMD     : DCD OFF,
,03-19 13:02:33.815   291   291 E SMD     : DCD OFF,
,03-19 13:02:36.815   291   291 E SMD     : DCD OFF,
,03-19 13:02:37.825  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:02:38.115  1016  3992 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-19 13:02:39.815   291   291 E SMD     : DCD OFF,
,03-19 13:02:42.825   291   291 E SMD     : DCD OFF,
,03-19 13:02:45.815   291   291 E SMD     : DCD OFF
,03-19 13:02:47.875  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:02:48.175  1016  1548 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 13:02:48.175  1016  1548 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4321, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:02:48.175  1016  1548 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:02:48.175  1016  1548 D BatteryService: stay LED for fully charged
03-19 13:02:48.175  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:02:48.175  1016  1016 I MotionRecognitionService: Plugged
03-19 13:02:48.175  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:02:48.185  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-19 13:02:48.185  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:02:48.185  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 13:02:48.185  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:02:48.195  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:02:48.195  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:02:48.205  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:02:48.205  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:02:48.205  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:02:48.205  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:02:48.205  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:02:48.825   291   291 E SMD     : DCD OFF
,03-19 13:02:51.815   291   291 E SMD     : DCD OFF,
,03-19 13:02:54.825   291   291 E SMD     : DCD OFF,
,03-19 13:02:55.965  1016  1337 E Watchdog: !@Sync 22,
,03-19 13:02:57.755  1016  1049 I PowerManagerService: [PWL] Off : 140s ago,
,03-19 13:02:57.825   291   291 E SMD     : DCD OFF,
,03-19 13:02:57.925  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:02:58.235  1016  1329 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:02:58.235  1016  1329 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:02:58.235  1016  1329 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-19 13:02:58.235  1016  1329 D BatteryService: stay LED for fully charged
03-19 13:02:58.235  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:02:58.245  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-19 13:02:58.245  1016  1016 I MotionRecognitionService: Plugged
03-19 13:02:58.245  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 13:02:58.245  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:02:58.245  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:02:58.245  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:02:58.255  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:02:58.255  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:02:58.265  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:02:58.275  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:02:58.275  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:02:58.275  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:02:58.275  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:03:00.835   291   291 E SMD     : DCD OFF,
,03-19 13:03:03.825   291   291 E SMD     : DCD OFF,
,03-19 13:03:06.835   291   291 E SMD     : DCD OFF,
,03-19 13:03:07.945  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:03:08.295  1016  1548 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:03:08.295  1016  1548 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:03:08.295  1016  1548 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:03:08.295  1016  1548 D BatteryService: stay LED for fully charged
,03-19 13:03:08.295  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:03:08.295  1016  1016 I MotionRecognitionService: Plugged
03-19 13:03:08.295  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:03:08.305  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:03:08.305  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:03:08.305  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:03:08.305  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:03:08.315  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-19 13:03:08.315  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:03:08.325  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:03:08.325  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:03:08.325  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:03:08.325  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-19 13:03:08.325  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:03:09.825   291   291 E SMD     : DCD OFF
,03-19 13:03:12.835   291   291 E SMD     : DCD OFF,
,03-19 13:03:15.835   291   291 E SMD     : DCD OFF,
,03-19 13:03:18.005  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:03:18.355  1016  1329 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-19 13:03:18.845   291   291 E SMD     : DCD OFF
,03-19 13:03:21.845   291   291 E SMD     : DCD OFF
,03-19 13:03:24.845   291   291 E SMD     : DCD OFF
,03-19 13:03:25.965  1016  1337 E Watchdog: !@Sync 23,
,03-19 13:03:27.845   291   291 E SMD     : DCD OFF
,03-19 13:03:28.035  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:03:28.415  1016  1552 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:03:28.415  1016  1552 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,03-19 13:03:28.415  1016  1552 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-19 13:03:28.415  1016  1552 D BatteryService: stay LED for fully charged
03-19 13:03:28.425  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:03:28.425  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:03:28.425  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate,
03-19 13:03:28.425  1016  1016 I MotionRecognitionService: Plugged
,03-19 13:03:28.425  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
03-19 13:03:28.425  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:03:28.425  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:03:28.435  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-19 13:03:28.435  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:03:28.445  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:03:28.445  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:03:28.445  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:03:28.445  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-19 13:03:28.445  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:03:30.845   291   291 E SMD     : DCD OFF,
,03-19 13:03:33.855   291   291 E SMD     : DCD OFF,
,03-19 13:03:36.855   291   291 E SMD     : DCD OFF
,03-19 13:03:37.755  1016  1049 I PowerManagerService: [PWL] Off : 180s ago,
,03-19 13:03:38.055  1016  2736 D SSRM:n  : SIOP:: AP = 260
,03-19 13:03:38.475  1016  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-19 13:03:38.475  1016  1497 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:03:38.475  1016  1497 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:03:38.475  1016  1497 D BatteryService: stay LED for fully charged
03-19 13:03:38.475  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:03:38.485  1016  1016 I MotionRecognitionService: Plugged
03-19 13:03:38.485  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:03:38.485  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:03:38.485  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:03:38.495  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-19 13:03:38.495  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:03:38.505  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:03:38.505  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:03:38.525  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:03:38.525  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:03:38.525  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:03:38.525  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-19 13:03:38.525  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:03:39.855   291   291 E SMD     : DCD OFF,
,03-19 13:03:42.855   291   291 E SMD     : DCD OFF,
,03-19 13:03:45.845   291   291 E SMD     : DCD OFF,
,03-19 13:03:48.115  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:03:48.535  1016  1552 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 13:03:48.535  1016  1552 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0,
03-19 13:03:48.535  1016  1552 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:03:48.535  1016  1552 D BatteryService: stay LED for fully charged
03-19 13:03:48.535  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:03:48.545  1016  1016 I MotionRecognitionService: Plugged
03-19 13:03:48.545  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:03:48.545  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:03:48.545  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:03:48.545  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:03:48.545  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:03:48.555  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:03:48.555  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:03:48.565  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:03:48.565  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:03:48.575  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:03:48.575  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-19 13:03:48.575  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:03:48.855   291   291 E SMD     : DCD OFF
,03-19 13:03:51.865   291   291 E SMD     : DCD OFF,
,03-19 13:03:54.865   291   291 E SMD     : DCD OFF,
,03-19 13:03:55.975  1016  1337 E Watchdog: !@Sync 24,
,03-19 13:03:57.855   291   291 E SMD     : DCD OFF,
,03-19 13:03:58.165  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:03:58.595  1016  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-19 13:04:00.865   291   291 E SMD     : DCD OFF,
,03-19 13:04:03.855   291   291 E SMD     : DCD OFF,
,03-19 13:04:06.865   291   291 E SMD     : DCD OFF
,03-19 13:04:08.185  1016  2736 D SSRM:n  : SIOP:: AP = 260
,03-19 13:04:08.655  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:04:08.655  1016  1029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:04:08.655  1016  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-19 13:04:08.655  1016  1029 D BatteryService: stay LED for fully charged
,03-19 13:04:08.655  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:04:08.665  1016  1016 I MotionRecognitionService: Plugged
,03-19 13:04:08.665  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:04:08.665  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:04:08.665  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:04:08.665  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:04:08.665  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:04:08.675  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:04:08.675  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:04:08.695  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:04:08.695  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:04:08.695  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:04:08.695  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-19 13:04:08.695  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:04:09.865   291   291 E SMD     : DCD OFF,
,03-19 13:04:12.865   291   291 E SMD     : DCD OFF,
,03-19 13:04:15.865   291   291 E SMD     : DCD OFF,
,03-19 13:04:18.235  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:04:18.715  1016  1218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-19 13:04:18.715  1016  1218 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:04:18.715  1016  1218 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:04:18.715  1016  1218 D BatteryService: stay LED for fully charged
03-19 13:04:18.715  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:04:18.725  1016  1016 I MotionRecognitionService: Plugged
03-19 13:04:18.725  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:04:18.725  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:04:18.725  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:04:18.725  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:04:18.735  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:04:18.745  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-19 13:04:18.745  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:04:18.755  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:04:18.755  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:04:18.755  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:04:18.755  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-19 13:04:18.755  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:04:18.865   291   291 E SMD     : DCD OFF
,03-19 13:04:21.865   291   291 E SMD     : DCD OFF,
,03-19 13:04:22.765  1016  1049 I PowerManagerService: [PWL] Off : 225s ago,
,03-19 13:04:24.875   291   291 E SMD     : DCD OFF,
,03-19 13:04:25.975  1016  1337 E Watchdog: !@Sync 25,
,03-19 13:04:27.875   291   291 E SMD     : DCD OFF,
,03-19 13:04:28.295  1016  2736 D SSRM:n  : SIOP:: AP = 260
,03-19 13:04:28.775  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-19 13:04:30.875   291   291 E SMD     : DCD OFF
,03-19 13:04:33.875   291   291 E SMD     : DCD OFF
,03-19 13:04:36.875   291   291 E SMD     : DCD OFF,
,03-19 13:04:38.315  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:04:38.835  1016  1932 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:04:39.875   291   291 E SMD     : DCD OFF
,03-19 13:04:42.885   291   291 E SMD     : DCD OFF
,03-19 13:04:45.885   291   291 E SMD     : DCD OFF
,03-19 13:04:48.365  1016  2736 D SSRM:n  : SIOP:: AP = 260
,03-19 13:04:48.885   291   291 E SMD     : DCD OFF
,03-19 13:04:48.905  1016  1329 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:04:51.895   291   291 E SMD     : DCD OFF
,03-19 13:04:54.885   291   291 E SMD     : DCD OFF,
,03-19 13:04:55.735  1016  1096 V AlarmManager: waitForAlarm result :8,
,03-19 13:04:55.735  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK,
03-19 13:04:55.735  1180  1180 D KeyguardUpdateMonitor: handleTimeUpdate
,03-19 13:04:55.735  1180  1180 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-19 13:04:55.735  1180  1180 D SecKeyguardClockView: HomeTimezone(): 1
,03-19 13:04:55.745  1180  1180 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 13:04:55.745  1180  1180 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-19 13:04:55.755  1180  1180 I KeyguardEffectViewController: *** don't update sliding image ***
,03-19 13:04:55.785  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 13:04:55.785  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 13:04:55.785  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 13:04:55.795  1180  1180 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-19 13:04:55.805  1180  1180 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 13:04:55.975  1016  1337 E Watchdog: !@Sync 26
,03-19 13:04:57.895   291   291 E SMD     : DCD OFF
,03-19 13:04:58.425  1016  2736 D SSRM:n  : SIOP:: AP = 260
,03-19 13:04:58.965  1016  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:04:59.995  1016  1096 V AlarmManager: waitForAlarm result :8
,03-19 13:05:00.905   291   291 E SMD     : DCD OFF
,03-19 13:05:03.905   291   291 E SMD     : DCD OFF,
,03-19 13:05:06.905   291   291 E SMD     : DCD OFF,
,03-19 13:05:08.445  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:05:09.025  1016  1552 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:05:09.905   291   291 E SMD     : DCD OFF,
,03-19 13:05:12.785  1016  1049 I PowerManagerService: [PWL] Off : 275s ago
,03-19 13:05:12.905   291   291 E SMD     : DCD OFF
,03-19 13:05:15.905   291   291 E SMD     : DCD OFF,
,03-19 13:05:18.505  1016  2736 D SSRM:n  : SIOP:: AP = 260
,03-19 13:05:18.915   291   291 E SMD     : DCD OFF,
,03-19 13:05:19.085  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:05:19.085  1016  1029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:05:19.085  1016  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:05:19.085  1016  1029 D BatteryService: stay LED for fully charged
03-19 13:05:19.085  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:05:19.095  1016  1016 I MotionRecognitionService: Plugged
,03-19 13:05:19.095  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:05:19.095  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 13:05:19.095  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:05:19.095  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:05:19.095  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,03-19 13:05:19.115  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:05:19.115  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:05:19.125  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:05:19.125  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:05:19.125  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:05:19.125  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-19 13:05:19.125  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:05:21.905   291   291 E SMD     : DCD OFF
,03-19 13:05:24.915   291   291 E SMD     : DCD OFF,
,03-19 13:05:25.965  1016  1337 E Watchdog: !@Sync 27,
,03-19 13:05:27.905   291   291 E SMD     : DCD OFF,
,03-19 13:05:28.555  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:05:29.145  1016  1551 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:05:29.145  1016  1551 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,03-19 13:05:29.145  1016  1551 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:05:29.145  1016  1551 D BatteryService: stay LED for fully charged
03-19 13:05:29.145  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:05:29.155  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:05:29.155  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:05:29.155  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:05:29.155  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:05:29.165  1016  1016 I MotionRecognitionService: Plugged
03-19 13:05:29.165  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:05:29.165  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-19 13:05:29.165  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:05:29.175  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-19 13:05:29.175  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:05:29.175  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:05:29.175  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:05:29.175  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:05:30.915   291   291 E SMD     : DCD OFF,
,03-19 13:05:33.915   291   291 E SMD     : DCD OFF,
,03-19 13:05:36.925   291   291 E SMD     : DCD OFF,
,03-19 13:05:38.575  1016  2736 D SSRM:n  : SIOP:: AP = 260
,03-19 13:05:39.205  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 13:05:39.205  1016  1029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:05:39.205  1016  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:05:39.205  1016  1029 D BatteryService: stay LED for fully charged,
03-19 13:05:39.205  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-19 13:05:39.205  1016  1016 I MotionRecognitionService: Plugged,
03-19 13:05:39.205  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
03-19 13:05:39.205  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 13:05:39.205  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:05:39.215  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:05:39.215  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,03-19 13:05:39.225  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-19 13:05:39.225  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:05:39.235  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-19 13:05:39.235  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:05:39.235  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:05:39.235  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:05:39.235  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:05:39.915   291   291 E SMD     : DCD OFF,
,03-19 13:05:42.925   291   291 E SMD     : DCD OFF,
,03-19 13:05:45.925   291   291 E SMD     : DCD OFF,
,03-19 13:05:48.635  1016  2736 D SSRM:n  : SIOP:: AP = 260
,03-19 13:05:48.925   291   291 E SMD     : DCD OFF,
,03-19 13:05:49.265  1016  1551 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:05:49.265  1016  1551 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,03-19 13:05:49.265  1016  1551 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:05:49.265  1016  1551 D BatteryService: stay LED for fully charged
,03-19 13:05:49.265  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:05:49.275  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-19 13:05:49.275  1016  1016 I MotionRecognitionService: Plugged,
03-19 13:05:49.275  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 13:05:49.275  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:05:49.275  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:05:49.275  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-19 13:05:49.285  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:05:49.285  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:05:49.285  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-19 13:05:49.285  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:05:49.285  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
03-19 13:05:49.285  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:05:49.285  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:05:51.935   291   291 E SMD     : DCD OFF,
,03-19 13:05:54.935   291   291 E SMD     : DCD OFF,
,03-19 13:05:55.965  1016  1337 E Watchdog: !@Sync 28,
,03-19 13:05:57.935   291   291 E SMD     : DCD OFF,
,03-19 13:05:58.695  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:05:59.325  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:06:00.935   291   291 E SMD     : DCD OFF,
,03-19 13:06:03.935   291   291 E SMD     : DCD OFF,
,03-19 13:06:06.935   291   291 E SMD     : DCD OFF,
,03-19 13:06:07.805  1016  1049 I PowerManagerService: [PWL] Off : 330s ago,
,03-19 13:06:08.715  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:06:09.385  1016  1329 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:06:09.385  1016  1329 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:06:09.385  1016  1329 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:06:09.385  1016  1329 D BatteryService: stay LED for fully charged
,03-19 13:06:09.385  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:06:09.395  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:06:09.395  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:06:09.395  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:06:09.395  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:06:09.405  1016  1016 I MotionRecognitionService: Plugged
,03-19 13:06:09.405  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:06:09.405  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:06:09.405  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:06:09.415  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:06:09.415  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:06:09.415  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:06:09.415  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:06:09.425  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:06:09.935   291   291 E SMD     : DCD OFF,
,03-19 13:06:12.945   291   291 E SMD     : DCD OFF,
,03-19 13:06:15.935   291   291 E SMD     : DCD OFF,
,03-19 13:06:18.775  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 13:06:18.945   291   291 E SMD     : DCD OFF,
,03-19 13:06:19.445  1016  3982 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:06:19.445  1016  3982 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:06:19.445  1016  3982 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:06:19.445  1016  3982 D BatteryService: stay LED for fully charged
03-19 13:06:19.445  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:06:19.455  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:06:19.455  1016  1016 I MotionRecognitionService: Plugged
03-19 13:06:19.455  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 13:06:19.455  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
03-19 13:06:19.455  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:06:19.455  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:06:19.455  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:06:19.465  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:06:19.465  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:06:19.475  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:06:19.475  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:06:19.475  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-19 13:06:19.475  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:06:21.935   291   291 E SMD     : DCD OFF,
,03-19 13:06:24.935   291   291 E SMD     : DCD OFF,
,03-19 13:06:25.975  1016  1337 E Watchdog: !@Sync 29,
,03-19 13:06:27.945   291   291 E SMD     : DCD OFF,
,03-19 13:06:28.835  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:06:29.505  1016  1329 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:06:30.955   291   291 E SMD     : DCD OFF,
,03-19 13:06:33.945   291   291 E SMD     : DCD OFF,
,03-19 13:06:36.955   291   291 E SMD     : DCD OFF,
,03-19 13:06:38.855  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:06:39.565  1016  1078 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 13:06:39.565  1016  1078 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:06:39.565  1016  1078 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:06:39.565  1016  1078 D BatteryService: stay LED for fully charged
03-19 13:06:39.565  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:06:39.565  1016  1016 I MotionRecognitionService: Plugged
03-19 13:06:39.565  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
03-19 13:06:39.575  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 13:06:39.575  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:06:39.575  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 13:06:39.575  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:06:39.585  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:06:39.585  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:06:39.595  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:06:39.595  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:06:39.595  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:06:39.595  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:06:39.595  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:06:39.945   291   291 E SMD     : DCD OFF,
,03-19 13:06:42.955   291   291 E SMD     : DCD OFF,
,03-19 13:06:45.955   291   291 E SMD     : DCD OFF,
,03-19 13:06:48.915  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:06:48.965   291   291 E SMD     : DCD OFF,
,03-19 13:06:49.625  1016  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:06:49.625  1016  1497 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:06:49.625  1016  1497 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:06:49.625  1016  1497 D BatteryService: stay LED for fully charged
,03-19 13:06:49.625  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:06:49.635  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:06:49.635  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:06:49.635  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:06:49.635  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:06:49.645  1016  1016 I MotionRecognitionService: Plugged
03-19 13:06:49.645  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:06:49.655  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:06:49.655  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:06:49.665  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:06:49.665  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:06:49.665  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:06:49.665  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:06:49.665  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:06:51.955   291   291 E SMD     : DCD OFF,
,03-19 13:06:53.175  1016  1087 D TimaService: TIMA: TimaService scheduler is intialized. 
03-19 13:06:53.175  1016  1087 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
03-19 13:06:53.185  1016  1086 D TimaService: TimaServiceHandler.handleMessage what =1
,03-19 13:06:54.955   291   291 E SMD     : DCD OFF,
,03-19 13:06:55.155  1016  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-19 13:06:55.155  1016  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-19 13:06:55.155  1016  1087 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-19 13:06:55.155  1016  1087 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-19 13:06:55.975  1016  1337 E Watchdog: !@Sync 30
,03-19 13:06:57.965   291   291 E SMD     : DCD OFF
,03-19 13:06:58.975  1016  2736 D SSRM:n  : SIOP:: AP = 260
,03-19 13:06:59.685  1016  1078 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:06:59.685  1016  1078 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:06:59.685  1016  1078 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:06:59.685  1016  1078 D BatteryService: stay LED for fully charged
03-19 13:06:59.685  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:06:59.685  1016  1016 I MotionRecognitionService: Plugged
,03-19 13:06:59.695  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:06:59.695  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:06:59.695  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:06:59.695  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:06:59.695  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:06:59.705  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:06:59.705  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:06:59.715  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:06:59.715  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:06:59.725  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:06:59.725  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:06:59.725  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:07:00.965   291   291 E SMD     : DCD OFF,
,03-19 13:07:03.975   291   291 E SMD     : DCD OFF,
,03-19 13:07:06.975   291   291 E SMD     : DCD OFF,
,03-19 13:07:07.805  1016  1049 I PowerManagerService: [PWL] Off : 390s ago,
,03-19 13:07:08.995  1016  2736 D SSRM:n  : SIOP:: AP = 260
,03-19 13:07:09.745  1016  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 13:07:09.745  1016  1497 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:07:09.745  1016  1497 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:07:09.745  1016  1497 D BatteryService: stay LED for fully charged
,03-19 13:07:09.745  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-19 13:07:09.745  1016  1016 I MotionRecognitionService: Plugged
03-19 13:07:09.745  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:07:09.755  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 13:07:09.755  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:07:09.755  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:07:09.755  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:07:09.765  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:07:09.765  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:07:09.775  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:07:09.775  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:07:09.775  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:07:09.775  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:07:09.775  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:07:09.975   291   291 E SMD     : DCD OFF,
,03-19 13:07:12.975   291   291 E SMD     : DCD OFF,
,03-19 13:07:15.975   291   291 E SMD     : DCD OFF,
,03-19 13:07:18.975   291   291 E SMD     : DCD OFF,
,03-19 13:07:19.055  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:07:19.805  1016  1078 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:07:19.805  1016  1078 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:07:19.805  1016  1078 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:07:19.805  1016  1078 D BatteryService: stay LED for fully charged
,03-19 13:07:19.815  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-19 13:07:19.815  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 13:07:19.815  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 13:07:19.815  1016  1016 I MotionRecognitionService: Plugged
03-19 13:07:19.815  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
03-19 13:07:19.815  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:07:19.815  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100,
,03-19 13:07:19.825  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-19 13:07:19.825  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:07:19.835  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:07:19.845  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:07:19.845  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:07:19.845  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-19 13:07:19.845  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:07:21.975   291   291 E SMD     : DCD OFF,
,03-19 13:07:24.985   291   291 E SMD     : DCD OFF,
,03-19 13:07:25.975  1016  1337 E Watchdog: !@Sync 31,
,03-19 13:07:27.975   291   291 E SMD     : DCD OFF,
,03-19 13:07:29.105  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:07:29.865  1016  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-19 13:07:30.975   291   291 E SMD     : DCD OFF,
,03-19 13:07:33.975   291   291 E SMD     : DCD OFF,
,03-19 13:07:36.985   291   291 E SMD     : DCD OFF,
,03-19 13:07:39.125  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:07:39.935  1016  1502 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 13:07:39.935  1016  1502 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:07:39.935  1016  1502 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:07:39.935  1016  1502 D BatteryService: stay LED for fully charged
03-19 13:07:39.935  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:07:39.935  1016  1016 I MotionRecognitionService: Plugged
03-19 13:07:39.935  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:07:39.935  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 13:07:39.935  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:07:39.935  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:07:39.935  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:07:39.945  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-19 13:07:39.945  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:07:39.965  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-19 13:07:39.965  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:07:39.965  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:07:39.965  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:07:39.965  1180  1180 D SViewCoverView: level :100 plugged : 2,
,03-19 13:07:39.995   291   291 E SMD     : DCD OFF,
,03-19 13:07:42.995   291   291 E SMD     : DCD OFF,
,03-19 13:07:45.985   291   291 E SMD     : DCD OFF,
,03-19 13:07:48.995   291   291 E SMD     : DCD OFF,
,03-19 13:07:49.185  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:07:49.995  1016  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 13:07:49.995  1016  1028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:07:49.995  1016  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:07:49.995  1016  1028 D BatteryService: stay LED for fully charged
03-19 13:07:49.995  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:07:49.995  1016  1016 I MotionRecognitionService: Plugged
03-19 13:07:49.995  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
03-19 13:07:49.995  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 13:07:49.995  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:07:49.995  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 13:07:49.995  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:07:50.005  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:07:50.015  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:07:50.025  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:07:50.025  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:07:50.025  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:07:50.025  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:07:50.025  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:07:51.995   291   291 E SMD     : DCD OFF,
,03-19 13:07:54.995   291   291 E SMD     : DCD OFF,
,03-19 13:07:55.975  1016  1337 E Watchdog: !@Sync 32,
,03-19 13:07:58.005   291   291 E SMD     : DCD OFF,
,03-19 13:07:59.245  1016  2736 D SSRM:n  : SIOP:: AP = 260
,03-19 13:07:59.995  1016  1096 V AlarmManager: waitForAlarm result :8,
03-19 13:07:59.995  1016  1096 V AlarmManager: No more alarm at this time.nowELAPSED=980966 batch.start=1201890
,03-19 13:08:00.055  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-19 13:08:00.055  1016  1502 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-19 13:08:00.055  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 13:08:00.055  1016  1502 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:08:00.055  1016  1502 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:08:00.055  1016  1502 D BatteryService: stay LED for fully charged
03-19 13:08:00.055  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
03-19 13:08:00.055  1016  1016 I MotionRecognitionService: Plugged
03-19 13:08:00.055  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
03-19 13:08:00.055  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:08:00.055  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:08:00.065  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:08:00.065  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:08:00.075  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:08:00.075  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:08:00.075  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:08:00.075  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:08:00.075  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:08:01.005   291   291 E SMD     : DCD OFF,
,03-19 13:08:04.005   291   291 E SMD     : DCD OFF,
,03-19 13:08:07.005   291   291 E SMD     : DCD OFF,
,03-19 13:08:09.275  1016  2736 D SSRM:n  : SIOP:: AP = 260
,03-19 13:08:10.005   291   291 E SMD     : DCD OFF,
,03-19 13:08:10.115  1016  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 13:08:10.115  1016  1028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:08:10.115  1016  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:08:10.115  1016  1028 D BatteryService: stay LED for fully charged
03-19 13:08:10.115  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-19 13:08:10.115  1016  1016 I MotionRecognitionService: Plugged
,03-19 13:08:10.115  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:08:10.115  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 13:08:10.115  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 13:08:10.125  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:08:10.125  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:08:10.135  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:08:10.135  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:08:10.155  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:08:10.155  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:08:10.155  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:08:10.155  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:08:10.155  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:08:12.815  1016  1049 I PowerManagerService: [PWL] Off : 455s ago
,03-19 13:08:13.005   291   291 E SMD     : DCD OFF,
,03-19 13:08:16.015   291   291 E SMD     : DCD OFF,
,03-19 13:08:19.015   291   291 E SMD     : DCD OFF,
,03-19 13:08:19.345  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 13:08:20.175  1016  1502 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:08:22.015   291   291 E SMD     : DCD OFF,
,03-19 13:08:25.015   291   291 E SMD     : DCD OFF,
,03-19 13:08:25.965  1016  1337 E Watchdog: !@Sync 33,
,03-19 13:08:28.015   291   291 E SMD     : DCD OFF,
,03-19 13:08:29.365  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:08:30.235  1016  3796 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 13:08:30.235  1016  3796 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:08:30.235  1016  3796 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:08:30.235  1016  3796 D BatteryService: stay LED for fully charged
03-19 13:08:30.235  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:08:30.235  1016  1016 I MotionRecognitionService: Plugged
03-19 13:08:30.235  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:08:30.245  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:08:30.245  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate,
03-19 13:08:30.245  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:08:30.245  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:08:30.255  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-19 13:08:30.255  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:08:30.265  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:08:30.265  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:08:30.265  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:08:30.265  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:08:30.265  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:08:31.015   291   291 E SMD     : DCD OFF
,03-19 13:08:34.015   291   291 E SMD     : DCD OFF
,03-19 13:08:37.025   291   291 E SMD     : DCD OFF,
,03-19 13:08:39.405  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:08:40.025   291   291 E SMD     : DCD OFF
,03-19 13:08:40.305  1016  1521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:08:40.305  1016  1521 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:08:40.305  1016  1521 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:08:40.305  1016  1521 D BatteryService: stay LED for fully charged
,03-19 13:08:40.305  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:08:40.315  1016  1016 I MotionRecognitionService: Plugged
,03-19 13:08:40.315  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 13:08:40.315  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 13:08:40.315  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:08:40.315  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:08:40.315  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:08:40.325  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-19 13:08:40.325  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:08:40.335  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:08:40.335  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:08:40.335  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:08:40.335  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:08:40.335  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:08:43.015   291   291 E SMD     : DCD OFF
,03-19 13:08:46.015   291   291 E SMD     : DCD OFF,
,03-19 13:08:49.025   291   291 E SMD     : DCD OFF,
,03-19 13:08:49.465  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:08:50.355  1016  3796 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:08:52.025   291   291 E SMD     : DCD OFF,
,03-19 13:08:55.035   291   291 E SMD     : DCD OFF,
,03-19 13:08:55.975  1016  1337 E Watchdog: !@Sync 34,
,03-19 13:08:58.025   291   291 E SMD     : DCD OFF,
,03-19 13:08:59.515  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:09:00.425  1016  3992 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:09:01.035   291   291 E SMD     : DCD OFF
,03-19 13:09:04.025   291   291 E SMD     : DCD OFF,
,03-19 13:09:07.035   291   291 E SMD     : DCD OFF,
,03-19 13:09:09.545  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:09:10.035   291   291 E SMD     : DCD OFF,
,03-19 13:09:10.485  1016  1548 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-19 13:09:13.035   291   291 E SMD     : DCD OFF,
,03-19 13:09:16.045   291   291 E SMD     : DCD OFF,
,03-19 13:09:19.035   291   291 E SMD     : DCD OFF,
,03-19 13:09:19.605  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:09:20.545  1016  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:09:22.045   291   291 E SMD     : DCD OFF,
,03-19 13:09:22.855  1016  1049 I PowerManagerService: [PWL] Off : 525s ago,
,03-19 13:09:25.045   291   291 E SMD     : DCD OFF,
,03-19 13:09:25.975  1016  1337 E Watchdog: !@Sync 35,
,03-19 13:09:28.045   291   291 E SMD     : DCD OFF,
,03-19 13:09:29.655  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:09:30.605  1016  1521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:09:31.045   291   291 E SMD     : DCD OFF
,03-19 13:09:34.045   291   291 E SMD     : DCD OFF
,03-19 13:09:37.055   291   291 E SMD     : DCD OFF,
,03-19 13:09:39.675  1016  2736 D SSRM:n  : SIOP:: AP = 260
,03-19 13:09:40.055   291   291 E SMD     : DCD OFF,
,03-19 13:09:40.665  1016  1932 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:09:43.045   291   291 E SMD     : DCD OFF,
,03-19 13:09:46.055   291   291 E SMD     : DCD OFF,
,03-19 13:09:49.065   291   291 E SMD     : DCD OFF,
,03-19 13:09:49.745  1016  2736 D SSRM:n  : SIOP:: AP = 260
,03-19 13:09:50.725  1016  3797 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-19 13:09:52.055   291   291 E SMD     : DCD OFF,
,03-19 13:09:55.065   291   291 E SMD     : DCD OFF,
,03-19 13:09:55.975  1016  1337 E Watchdog: !@Sync 36,
,03-19 13:09:58.065   291   291 E SMD     : DCD OFF,
,03-19 13:09:59.775  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:10:00.785  1016  1078 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:10:00.785  1016  1078 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:10:00.785  1016  1078 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:10:00.785  1016  1078 D BatteryService: stay LED for fully charged
03-19 13:10:00.785  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:10:00.795  1016  1016 I MotionRecognitionService: Plugged
03-19 13:10:00.795  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 13:10:00.795  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
03-19 13:10:00.795  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate,
,03-19 13:10:00.795  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:10:00.795  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:10:00.805  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:10:00.805  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:10:00.815  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:10:00.815  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:10:00.815  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:10:00.815  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:10:00.815  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:10:01.065   291   291 E SMD     : DCD OFF
,03-19 13:10:04.065   291   291 E SMD     : DCD OFF,
,03-19 13:10:07.075   291   291 E SMD     : DCD OFF,
,03-19 13:10:09.805  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:10:10.075   291   291 E SMD     : DCD OFF,
,03-19 13:10:10.845  1016  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-19 13:10:13.075   291   291 E SMD     : DCD OFF,
,03-19 13:10:16.075   291   291 E SMD     : DCD OFF,
,03-19 13:10:19.075   291   291 E SMD     : DCD OFF,
,03-19 13:10:19.875  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:10:20.905  1016  1552 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:10:22.075   291   291 E SMD     : DCD OFF,
,03-19 13:10:25.075   291   291 E SMD     : DCD OFF,
,03-19 13:10:25.975  1016  1337 E Watchdog: !@Sync 37,
,03-19 13:10:28.085   291   291 E SMD     : DCD OFF,
,03-19 13:10:29.935  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:10:30.965  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-19 13:10:30.965  1016  1029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:10:30.965  1016  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:10:30.965  1016  1029 D BatteryService: stay LED for fully charged
03-19 13:10:30.965  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:10:30.975  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:10:30.975  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:10:30.975  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:10:30.975  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:10:30.985  1016  1016 I MotionRecognitionService: Plugged
03-19 13:10:30.985  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false,
,03-19 13:10:30.995  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-19 13:10:30.995  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:10:31.005  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:10:31.005  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:10:31.005  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:10:31.005  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:10:31.005  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:10:31.075   291   291 E SMD     : DCD OFF
,03-19 13:10:34.085   291   291 E SMD     : DCD OFF
,03-19 13:10:37.085   291   291 E SMD     : DCD OFF,
,03-19 13:10:37.865  1016  1049 I PowerManagerService: [PWL] Off : 600s ago,
,03-19 13:10:39.965  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:10:40.085   291   291 E SMD     : DCD OFF,
,03-19 13:10:41.035  1016  1551 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 13:10:41.035  1016  1551 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:10:41.035  1016  1551 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:10:41.035  1016  1551 D BatteryService: stay LED for fully charged
03-19 13:10:41.035  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
03-19 13:10:41.035  1016  1016 I MotionRecognitionService: Plugged
03-19 13:10:41.035  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:10:41.035  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:10:41.035  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:10:41.045  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-19 13:10:41.045  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:10:41.055  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:10:41.055  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:10:41.065  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:10:41.065  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:10:41.065  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:10:41.065  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:10:41.065  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:10:43.085   291   291 E SMD     : DCD OFF
,03-19 13:10:46.095   291   291 E SMD     : DCD OFF,
,03-19 13:10:49.095   291   291 E SMD     : DCD OFF,
,03-19 13:10:50.025  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:10:51.095  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-19 13:10:52.095   291   291 E SMD     : DCD OFF,
,03-19 13:10:55.095   291   291 E SMD     : DCD OFF,
,03-19 13:10:55.975  1016  1337 E Watchdog: !@Sync 38,
,03-19 13:10:58.095   291   291 E SMD     : DCD OFF,
,03-19 13:11:00.065  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:11:01.105   291   291 E SMD     : DCD OFF,
,03-19 13:11:01.155  1016  1329 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:11:01.155  1016  1329 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:11:01.155  1016  1329 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,03-19 13:11:01.155  1016  1329 D BatteryService: stay LED for fully charged
03-19 13:11:01.155  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:11:01.165  1016  1016 I MotionRecognitionService: Plugged
,03-19 13:11:01.165  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:11:01.165  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:11:01.165  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:11:01.165  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:11:01.165  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:11:01.185  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-19 13:11:01.185  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:11:01.195  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:11:01.195  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:11:01.195  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:11:01.195  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:11:01.195  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:11:04.115   291   291 E SMD     : DCD OFF,
,03-19 13:11:07.115   291   291 E SMD     : DCD OFF,
,03-19 13:11:10.085  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:11:10.115   291   291 E SMD     : DCD OFF,
,03-19 13:11:11.215  1016  3982 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:11:11.215  1016  3982 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:11:11.215  1016  3982 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:11:11.215  1016  3982 D BatteryService: stay LED for fully charged
,03-19 13:11:11.215  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:11:11.225  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:11:11.225  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:11:11.225  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:11:11.225  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:11:11.235  1016  1016 I MotionRecognitionService: Plugged,
03-19 13:11:11.235  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false,
,03-19 13:11:11.235  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-19 13:11:11.245  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:11:11.255  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-19 13:11:11.255  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:11:11.255  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:11:11.255  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:11:11.255  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:11:13.115   291   291 E SMD     : DCD OFF
,03-19 13:11:16.105   291   291 E SMD     : DCD OFF,
,03-19 13:11:19.115   291   291 E SMD     : DCD OFF,
,03-19 13:11:20.145  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:11:21.275  1016  1329 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-19 13:11:22.125   291   291 E SMD     : DCD OFF,
,03-19 13:11:25.125   291   291 E SMD     : DCD OFF,
,03-19 13:11:25.985  1016  1337 E Watchdog: !@Sync 39,
,03-19 13:11:28.125   291   291 E SMD     : DCD OFF,
,03-19 13:11:30.205  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:11:31.125   291   291 E SMD     : DCD OFF,
,03-19 13:11:31.335  1016  1078 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:11:34.125   291   291 E SMD     : DCD OFF,
,03-19 13:11:37.125   291   291 E SMD     : DCD OFF,
,03-19 13:11:40.135   291   291 E SMD     : DCD OFF,
,03-19 13:11:40.225  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:11:40.915  1016  1096 V AlarmManager: waitForAlarm result :4,
,03-19 13:11:40.925  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-19 13:11:40.925  1180  1180 D KeyguardUpdateMonitor: handleTimeUpdate
,03-19 13:11:40.935  1180  1180 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-19 13:11:40.935  1180  1180 D SecKeyguardClockView: HomeTimezone(): 1
,03-19 13:11:40.945  1180  1180 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
03-19 13:11:40.945  1180  1180 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
03-19 13:11:40.945  1180  1180 I KeyguardEffectViewController: *** don't update sliding image ***
,03-19 13:11:40.955  1016  1548 W ActivityManager: userId = 0, bbcId = -10000
,03-19 13:11:40.955  1016  1548 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
03-19 13:11:40.955  1016  1548 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 13:11:40.975  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 13:11:40.985  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 13:11:40.985  1180  1180 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 13:11:40.995  1180  1180 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,03-19 13:11:41.005  1016  3982 W ActivityManager: userId = 0, bbcId = -10000
03-19 13:11:41.005  1016  3982 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,03-19 13:11:41.005  1016  3982 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-19 13:11:41.015  1180  1180 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-19 13:11:41.035  1791  6081 I EventLogService: Aggregate from 1458387700886 (log), 1458387700886 (data)
,03-19 13:11:41.075  1619  3991 D GCM     : Message class com.google.e.a.a.h
,03-19 13:11:41.385  1016  1078 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:11:41.385  1016  1078 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4302, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:11:41.385  1016  1078 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:11:41.385  1016  1078 D BatteryService: stay LED for fully charged
03-19 13:11:41.395  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:11:41.395  1016  1016 I MotionRecognitionService: Plugged
03-19 13:11:41.395  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:11:41.395  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:11:41.395  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:11:41.395  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:11:41.395  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:11:41.405  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:11:41.405  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:11:41.415  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:11:41.415  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:11:41.415  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:11:41.415  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:11:41.425  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:11:43.135   291   291 E SMD     : DCD OFF
,03-19 13:11:46.135   291   291 E SMD     : DCD OFF,
,03-19 13:11:49.135   291   291 E SMD     : DCD OFF,
,03-19 13:11:50.285  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:11:51.445  1016  1552 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 13:11:51.445  1016  1552 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:11:51.445  1016  1552 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:11:51.445  1016  1552 D BatteryService: stay LED for fully charged
03-19 13:11:51.445  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:11:51.455  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 13:11:51.455  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:11:51.455  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 13:11:51.455  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:11:51.465  1016  1016 I MotionRecognitionService: Plugged
03-19 13:11:51.465  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:11:51.465  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:11:51.465  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:11:51.475  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:11:51.475  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:11:51.475  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:11:51.475  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-19 13:11:51.475  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:11:52.135   291   291 E SMD     : DCD OFF,
,03-19 13:11:53.185  1016  1087 D TimaService: TIMA: TimaService scheduler is intialized. ,
03-19 13:11:53.185  1016  1087 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
03-19 13:11:53.185  1016  1086 D TimaService: TimaServiceHandler.handleMessage what =1
,03-19 13:11:53.585  1016  1041 I UsageStatsService: User[0] Flushing usage stats to disk,
,03-19 13:11:53.625  1016  1103 I ApplicationUsage: handleMessage : MSG_UPDATE_USAGE_DB
,03-19 13:11:53.625  1016  1103 I ApplicationUsage: Updating Usage Statistics in DB @ 1458389513638
,03-19 13:11:53.625  1016  1103 I ApplicationPolicy: updateDataUsageMap
,03-19 13:11:53.865  1016  1103 I NetworkDataUsageDb: ::getAppControlDB: DB is Created 
,03-19 13:11:53.865  1016  1103 I NetworkDataUsageDb: ::isTableExists: Table exists 
,03-19 13:11:53.875  1016  1103 I ApplicationUsage: Done Updating Usage Statistics in DB @ 1458389513894
,03-19 13:11:54.015  1016  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,03-19 13:11:54.015  1016  1087 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,03-19 13:11:54.025  1016  1087 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-19 13:11:54.025  1016  1087 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,03-19 13:11:55.135   291   291 E SMD     : DCD OFF,
,03-19 13:11:55.985  1016  1337 E Watchdog: !@Sync 40,
,03-19 13:11:57.865  1016  1049 I PowerManagerService: [PWL] Off : 680s ago,
,03-19 13:11:58.135   291   291 E SMD     : DCD OFF,
,03-19 13:11:59.995  1016  1096 V AlarmManager: waitForAlarm result :8,
,03-19 13:12:00.345  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:12:01.145   291   291 E SMD     : DCD OFF,
,03-19 13:12:01.505  1016  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-19 13:12:04.135   291   291 E SMD     : DCD OFF,
,03-19 13:12:07.145   291   291 E SMD     : DCD OFF,
,03-19 13:12:10.135   291   291 E SMD     : DCD OFF,
,03-19 13:12:10.365  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:12:11.575  1016  3797 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:12:11.575  1016  3797 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:12:11.575  1016  3797 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:12:11.575  1016  3797 D BatteryService: stay LED for fully charged
,03-19 13:12:11.575  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:12:11.575  1016  1016 I MotionRecognitionService: Plugged
,03-19 13:12:11.575  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
03-19 13:12:11.575  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-19 13:12:11.575  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 13:12:11.585  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:12:11.585  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:12:11.595  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:12:11.595  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:12:11.605  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:12:11.605  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:12:11.605  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:12:11.605  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:12:11.605  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:12:13.145   291   291 E SMD     : DCD OFF
,03-19 13:12:16.145   291   291 E SMD     : DCD OFF,
,03-19 13:12:19.155   291   291 E SMD     : DCD OFF,
,03-19 13:12:20.425  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:12:21.635  1016  1218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:12:21.635  1016  1218 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:12:21.635  1016  1218 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:12:21.635  1016  1218 D BatteryService: stay LED for fully charged
,03-19 13:12:21.635  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:12:21.645  1016  1016 I MotionRecognitionService: Plugged,
03-19 13:12:21.645  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-19 13:12:21.645  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
03-19 13:12:21.645  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 13:12:21.645  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-19 13:12:21.645  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:12:21.655  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:12:21.655  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:12:21.665  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:12:21.665  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:12:21.665  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:12:21.665  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:12:21.665  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:12:22.145   291   291 E SMD     : DCD OFF,
,03-19 13:12:25.155   291   291 E SMD     : DCD OFF,
,03-19 13:12:25.975  1016  1337 E Watchdog: !@Sync 41,
,03-19 13:12:28.145   291   291 E SMD     : DCD OFF,
,03-19 13:12:30.485  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:12:31.155   291   291 E SMD     : DCD OFF,
,03-19 13:12:31.695  1016  1521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 13:12:31.695  1016  1521 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:12:31.695  1016  1521 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:12:31.695  1016  1521 D BatteryService: stay LED for fully charged
03-19 13:12:31.695  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-19 13:12:31.695  1016  1016 I MotionRecognitionService: Plugged
03-19 13:12:31.695  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false,
03-19 13:12:31.695  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 13:12:31.695  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:12:31.695  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:12:31.695  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-19 13:12:31.705  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:12:31.705  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-19 13:12:31.705  2656  2855 D HeadsetStateMachine: Disconnected process message: 10,
,03-19 13:12:31.715  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-19 13:12:31.715  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:12:31.725  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-19 13:12:31.725  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:12:34.155   291   291 E SMD     : DCD OFF
,03-19 13:12:37.165   291   291 E SMD     : DCD OFF,
,03-19 13:12:40.165   291   291 E SMD     : DCD OFF,
,03-19 13:12:40.515  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:12:41.755  1016  1218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 13:12:41.755  1016  1218 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:12:41.755  1016  1218 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:12:41.755  1016  1218 D BatteryService: stay LED for fully charged
03-19 13:12:41.755  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:12:41.755  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 13:12:41.755  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:12:41.755  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 13:12:41.755  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-19 13:12:41.755  1016  1016 I MotionRecognitionService: Plugged
03-19 13:12:41.755  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:12:41.765  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-19 13:12:41.765  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:12:41.775  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:12:41.775  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:12:41.775  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:12:41.775  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
03-19 13:12:41.775  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:12:43.165   291   291 E SMD     : DCD OFF,
,03-19 13:12:46.165   291   291 E SMD     : DCD OFF,
,03-19 13:12:49.165   291   291 E SMD     : DCD OFF,
,03-19 13:12:50.565  1016  2736 D SSRM:n  : SIOP:: AP = 260
,03-19 13:12:51.805  1016  1521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:12:51.805  1016  1521 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:12:51.805  1016  1521 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:12:51.805  1016  1521 D BatteryService: stay LED for fully charged
03-19 13:12:51.805  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:12:51.815  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 13:12:51.815  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:12:51.815  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 13:12:51.815  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
03-19 13:12:51.815  1016  1016 I MotionRecognitionService: Plugged
03-19 13:12:51.815  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:12:51.825  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:12:51.825  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:12:51.835  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:12:51.835  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:12:51.835  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:12:51.835  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:12:51.835  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:12:52.165   291   291 E SMD     : DCD OFF
,03-19 13:12:55.175   291   291 E SMD     : DCD OFF,
,03-19 13:12:55.985  1016  1337 E Watchdog: !@Sync 42,
,03-19 13:12:58.175   291   291 E SMD     : DCD OFF,
,03-19 13:13:00.635  1016  2736 D SSRM:n  : SIOP:: AP = 260
,03-19 13:13:01.175   291   291 E SMD     : DCD OFF
,03-19 13:13:01.875  1016  1218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:13:04.175   291   291 E SMD     : DCD OFF,
,03-19 13:13:07.175   291   291 E SMD     : DCD OFF,
,03-19 13:13:10.175   291   291 E SMD     : DCD OFF,
,03-19 13:13:10.665  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:13:11.935  1016  1502 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:13:11.935  1016  1502 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:13:11.935  1016  1502 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:13:11.935  1016  1502 D BatteryService: stay LED for fully charged
03-19 13:13:11.935  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:13:11.935  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 13:13:11.935  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:13:11.935  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 13:13:11.935  1016  1016 I MotionRecognitionService: Plugged
03-19 13:13:11.935  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
03-19 13:13:11.935  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:13:11.955  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:13:11.955  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:13:11.965  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:13:11.965  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:13:11.965  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:13:11.965  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-19 13:13:11.965  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:13:13.175   291   291 E SMD     : DCD OFF
,03-19 13:13:16.175   291   291 E SMD     : DCD OFF
,03-19 13:13:19.175   291   291 E SMD     : DCD OFF
,03-19 13:13:20.715  1016  2736 D SSRM:n  : SIOP:: AP = 260
,03-19 13:13:21.995  1016  1029 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:13:21.995  1016  1029 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:13:21.995  1016  1029 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:13:21.995  1016  1029 D BatteryService: stay LED for fully charged
03-19 13:13:21.995  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:13:21.995  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-19 13:13:21.995  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:13:21.995  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 13:13:21.995  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:13:22.005  1016  1016 I MotionRecognitionService: Plugged
03-19 13:13:22.005  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:13:22.015  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-19 13:13:22.015  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:13:22.025  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:13:22.025  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:13:22.025  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:13:22.025  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:13:22.025  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:13:22.185   291   291 E SMD     : DCD OFF,
,03-19 13:13:22.865  1016  1049 I PowerManagerService: [PWL] Off : 765s ago,
,03-19 13:13:25.185   291   291 E SMD     : DCD OFF
,03-19 13:13:25.985  1016  1337 E Watchdog: !@Sync 43
,03-19 13:13:28.175   291   291 E SMD     : DCD OFF
,03-19 13:13:30.785  1016  2736 D SSRM:n  : SIOP:: AP = 260
,03-19 13:13:31.185   291   291 E SMD     : DCD OFF
,03-19 13:13:32.055  1016  1502 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 13:13:32.055  1016  1502 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:13:32.055  1016  1502 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:13:32.055  1016  1502 D BatteryService: stay LED for fully charged
03-19 13:13:32.055  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-19 13:13:32.055  1016  1016 I MotionRecognitionService: Plugged
,03-19 13:13:32.055  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:13:32.055  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 13:13:32.055  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:13:32.055  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 13:13:32.055  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:13:32.065  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-19 13:13:32.065  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:13:32.075  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:13:32.075  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:13:32.085  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:13:32.085  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:13:32.085  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:13:34.185   291   291 E SMD     : DCD OFF,
,03-19 13:13:37.195   291   291 E SMD     : DCD OFF,
,03-19 13:13:40.185   291   291 E SMD     : DCD OFF,
,03-19 13:13:40.805  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:13:42.105  1016  3796 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:13:42.115  1016  3796 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:13:42.115  1016  3796 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:13:42.115  1016  3796 D BatteryService: stay LED for fully charged
,03-19 13:13:42.115  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:13:42.115  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:13:42.115  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:13:42.115  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:13:42.115  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:13:42.125  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:13:42.135  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
03-19 13:13:42.135  1016  1016 I MotionRecognitionService: Plugged
03-19 13:13:42.135  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:13:42.145  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:13:42.145  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:13:42.145  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:13:42.145  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:13:42.145  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:13:43.195   291   291 E SMD     : DCD OFF
,03-19 13:13:46.195   291   291 E SMD     : DCD OFF,
,03-19 13:13:49.195   291   291 E SMD     : DCD OFF,
,03-19 13:13:50.865  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:13:52.175  1016  1521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:13:52.175  1016  1521 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:13:52.175  1016  1521 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:13:52.175  1016  1521 D BatteryService: stay LED for fully charged
03-19 13:13:52.175  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:13:52.175  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-19 13:13:52.185  1016  1016 I MotionRecognitionService: Plugged
03-19 13:13:52.175  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 13:13:52.185  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:13:52.185  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:13:52.185  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:13:52.195   291   291 E SMD     : DCD OFF
,03-19 13:13:52.195  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:13:52.195  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:13:52.205  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:13:52.205  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:13:52.205  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:13:52.205  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:13:52.205  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:13:55.205   291   291 E SMD     : DCD OFF,
,03-19 13:13:55.985  1016  1337 E Watchdog: !@Sync 44,
,03-19 13:13:58.205   291   291 E SMD     : DCD OFF,
,03-19 13:14:00.915  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:14:01.205   291   291 E SMD     : DCD OFF,
,03-19 13:14:02.235  1016  1218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:14:02.235  1016  1218 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:14:02.235  1016  1218 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:14:02.235  1016  1218 D BatteryService: stay LED for fully charged
,03-19 13:14:02.235  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:14:02.245  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:14:02.245  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:14:02.245  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:14:02.245  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:14:02.255  1016  1016 I MotionRecognitionService: Plugged
03-19 13:14:02.255  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:14:02.265  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-19 13:14:02.265  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:14:02.275  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:14:02.275  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:14:02.275  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:14:02.275  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:14:02.275  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:14:04.195   291   291 E SMD     : DCD OFF
,03-19 13:14:07.195   291   291 E SMD     : DCD OFF,
,03-19 13:14:10.215   291   291 E SMD     : DCD OFF,
,03-19 13:14:10.945  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:14:12.295  1016  1521 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:14:12.295  1016  1521 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:14:12.295  1016  1521 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:14:12.295  1016  1521 D BatteryService: stay LED for fully charged
,03-19 13:14:12.295  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:14:12.305  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:14:12.305  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:14:12.305  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:14:12.305  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:14:12.315  1016  1016 I MotionRecognitionService: Plugged,
03-19 13:14:12.315  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:14:12.325  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-19 13:14:12.325  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:14:12.335  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-19 13:14:12.335  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:14:12.335  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:14:12.335  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:14:12.335  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:14:13.215   291   291 E SMD     : DCD OFF,
,03-19 13:14:16.205   291   291 E SMD     : DCD OFF,
,03-19 13:14:19.215   291   291 E SMD     : DCD OFF,
,03-19 13:14:21.005  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:14:22.215   291   291 E SMD     : DCD OFF,
,03-19 13:14:22.355  1016  1218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-19 13:14:25.215   291   291 E SMD     : DCD OFF
,03-19 13:14:25.985  1016  1337 E Watchdog: !@Sync 45,
,03-19 13:14:28.215   291   291 E SMD     : DCD OFF,
,03-19 13:14:31.055  1016  2736 D SSRM:n  : SIOP:: AP = 270,
,03-19 13:14:31.215   291   291 E SMD     : DCD OFF,
,03-19 13:14:32.415  1016  1502 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:14:34.215   291   291 E SMD     : DCD OFF,
,03-19 13:14:37.225   291   291 E SMD     : DCD OFF,
,03-19 13:14:40.225   291   291 E SMD     : DCD OFF,
,03-19 13:14:41.085  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:14:42.485  1016  1932 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-19 13:14:43.225   291   291 E SMD     : DCD OFF
,03-19 13:14:46.235   291   291 E SMD     : DCD OFF,
,03-19 13:14:49.225   291   291 E SMD     : DCD OFF,
,03-19 13:14:51.145  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:14:52.225   291   291 E SMD     : DCD OFF
,03-19 13:14:52.535  1016  1329 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:14:52.545  1016  1329 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:14:52.545  1016  1329 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:14:52.545  1016  1329 D BatteryService: stay LED for fully charged
03-19 13:14:52.545  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:14:52.545  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:14:52.545  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:14:52.545  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:14:52.545  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:14:52.555  1016  1016 I MotionRecognitionService: Plugged
,03-19 13:14:52.555  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:14:52.555  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:14:52.555  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:14:52.575  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-19 13:14:52.575  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:14:52.575  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:14:52.575  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:14:52.575  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:14:52.865  1016  1049 I PowerManagerService: [PWL] Off : 855s ago,
,03-19 13:14:55.235   291   291 E SMD     : DCD OFF
,03-19 13:14:55.985  1016  1337 E Watchdog: !@Sync 46,
,03-19 13:14:58.235   291   291 E SMD     : DCD OFF,
,03-19 13:15:01.205  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:15:01.235   291   291 E SMD     : DCD OFF,
,03-19 13:15:02.595  1016  1078 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:15:02.595  1016  1078 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:15:02.595  1016  1078 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:15:02.595  1016  1078 D BatteryService: stay LED for fully charged
03-19 13:15:02.595  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:15:02.605  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-19 13:15:02.605  1016  1016 I MotionRecognitionService: Plugged
03-19 13:15:02.605  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 13:15:02.605  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:15:02.605  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:15:02.605  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:15:02.615  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-19 13:15:02.615  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:15:02.625  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:15:02.625  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:15:02.625  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:15:02.625  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:15:02.625  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:15:04.235   291   291 E SMD     : DCD OFF
,03-19 13:15:07.245   291   291 E SMD     : DCD OFF,
,03-19 13:15:10.235   291   291 E SMD     : DCD OFF,
,03-19 13:15:11.235  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:15:12.655  1016  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:15:12.655  1016  1028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:15:12.655  1016  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:15:12.655  1016  1028 D BatteryService: stay LED for fully charged
,03-19 13:15:12.655  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:15:12.665  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:15:12.665  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:15:12.675  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-19 13:15:12.675  1016  1016 I MotionRecognitionService: Plugged
03-19 13:15:12.675  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
03-19 13:15:12.675  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:15:12.675  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:15:12.675  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,03-19 13:15:12.675  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 13:15:12.675  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:15:12.675  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-19 13:15:12.675  1180  1180 D SViewCoverView: level :100 plugged : 2
03-19 13:15:12.675  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:15:13.245   291   291 E SMD     : DCD OFF
,03-19 13:15:16.245   291   291 E SMD     : DCD OFF,
,03-19 13:15:19.255   291   291 E SMD     : DCD OFF,
,03-19 13:15:21.285  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:15:22.255   291   291 E SMD     : DCD OFF,
,03-19 13:15:22.715  1016  1078 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-19 13:15:22.715  1016  1078 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:15:22.715  1016  1078 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:15:22.715  1016  1078 D BatteryService: stay LED for fully charged
03-19 13:15:22.715  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:15:22.725  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:15:22.725  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:15:22.725  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:15:22.725  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:15:22.735  1016  1016 I MotionRecognitionService: Plugged
03-19 13:15:22.735  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:15:22.735  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:15:22.745  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-19 13:15:22.745  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:15:22.755  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:15:22.755  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:15:22.755  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:15:22.755  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:15:25.255   291   291 E SMD     : DCD OFF,
,03-19 13:15:25.985  1016  1337 E Watchdog: !@Sync 47,
,03-19 13:15:28.255   291   291 E SMD     : DCD OFF,
,03-19 13:15:31.255   291   291 E SMD     : DCD OFF,
,03-19 13:15:31.345  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:15:32.775  1016  1028 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 13:15:32.775  1016  1028 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:15:32.775  1016  1028 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
03-19 13:15:32.785  1016  1028 D BatteryService: stay LED for fully charged
03-19 13:15:32.785  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-19 13:15:32.785  1016  1016 I MotionRecognitionService: Plugged
03-19 13:15:32.785  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false,
,03-19 13:15:32.785  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 13:15:32.785  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:15:32.785  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-19 13:15:32.785  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:15:32.795  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:15:32.795  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:15:32.815  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:15:32.815  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:15:32.815  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:15:32.815  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:15:32.815  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:15:34.255   291   291 E SMD     : DCD OFF
,03-19 13:15:37.255   291   291 E SMD     : DCD OFF,
,03-19 13:15:40.255   291   291 E SMD     : DCD OFF,
,03-19 13:15:41.375  1016  2736 D SSRM:n  : SIOP:: AP = 260
,03-19 13:15:42.835  1016  1078 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
,03-19 13:15:43.265   291   291 E SMD     : DCD OFF
,03-19 13:15:46.255   291   291 E SMD     : DCD OFF,
,03-19 13:15:49.265   291   291 E SMD     : DCD OFF,
,03-19 13:15:51.445  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:15:52.255   291   291 E SMD     : DCD OFF,
,03-19 13:15:52.895  1016  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:15:52.895  1016  1497 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:15:52.895  1016  1497 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:15:52.905  1016  1497 D BatteryService: stay LED for fully charged
,03-19 13:15:52.905  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:15:52.905  1016  1016 I MotionRecognitionService: Plugged
03-19 13:15:52.905  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:15:52.905  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:15:52.905  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:15:52.905  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:15:52.915  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:15:52.925  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-19 13:15:52.925  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:15:52.935  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:15:52.935  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:15:52.935  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:15:52.935  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,03-19 13:15:52.935  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:15:55.265   291   291 E SMD     : DCD OFF
,03-19 13:15:55.985  1016  1337 E Watchdog: !@Sync 48
,03-19 13:15:58.265   291   291 E SMD     : DCD OFF,
,03-19 13:16:01.275   291   291 E SMD     : DCD OFF
,03-19 13:16:01.495  1016  2736 D SSRM:n  : SIOP:: AP = 260
,03-19 13:16:02.955  1016  1552 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
03-19 13:16:02.955  1016  1552 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:16:02.955  1016  1552 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:16:02.955  1016  1552 D BatteryService: stay LED for fully charged
03-19 13:16:02.955  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:16:02.965  1016  1016 I MotionRecognitionService: Plugged
03-19 13:16:02.965  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:16:02.965  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
03-19 13:16:02.965  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 13:16:02.965  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
03-19 13:16:02.965  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:16:02.975  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-19 13:16:02.975  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:16:02.985  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
03-19 13:16:02.985  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:16:02.985  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:16:02.985  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:16:02.985  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:16:04.275   291   291 E SMD     : DCD OFF,
,03-19 13:16:07.275   291   291 E SMD     : DCD OFF,
,03-19 13:16:10.275   291   291 E SMD     : DCD OFF,
,03-19 13:16:11.525  1016  2736 D SSRM:n  : SIOP:: AP = 260,
,03-19 13:16:13.015  1016  1497 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:16:13.015  1016  1497 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:16:13.015  1016  1497 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:16:13.015  1016  1497 D BatteryService: stay LED for fully charged
,03-19 13:16:13.025  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
03-19 13:16:13.025  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-19 13:16:13.025  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
03-19 13:16:13.025  1016  1016 I MotionRecognitionService: Plugged,
03-19 13:16:13.025  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:16:13.025  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,03-19 13:16:13.025  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:16:13.045  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
03-19 13:16:13.045  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:16:13.055  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:16:13.055  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:16:13.055  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:16:13.055  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:16:13.055  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:16:13.275   291   291 E SMD     : DCD OFF
,03-19 13:16:16.275   291   291 E SMD     : DCD OFF,
,03-19 13:16:19.285   291   291 E SMD     : DCD OFF,
,03-19 13:16:21.585  1016  2736 D SSRM:n  : SIOP:: AP = 260
,03-19 13:16:22.285   291   291 E SMD     : DCD OFF,
,03-19 13:16:23.075  1016  1552 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-19 13:16:23.085  1016  1552 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
03-19 13:16:23.085  1016  1552 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
03-19 13:16:23.085  1016  1552 D BatteryService: stay LED for fully charged
03-19 13:16:23.085  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-19 13:16:23.085  1180  1180 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-19 13:16:23.085  1180  1180 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-19 13:16:23.085  1016  1016 I MotionRecognitionService: Plugged
,03-19 13:16:23.085  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,03-19 13:16:23.095  1439  1439 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-19 13:16:23.095  1439  1439 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-19 13:16:23.105  2656  2656 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-19 13:16:23.105  2656  2855 D HeadsetStateMachine: Disconnected process message: 10
,03-19 13:16:23.115  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,03-19 13:16:23.115  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:16:23.115  1180  1180 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
03-19 13:16:23.115  1180  1180 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
03-19 13:16:23.115  1180  1180 D SViewCoverView: level :100 plugged : 2
,03-19 13:16:25.285   291   291 E SMD     : DCD OFF,
,03-19 13:16:25.985  1016  1337 E Watchdog: !@Sync 49,
,TIME-OUT KILL (timeout was 1400000ms),03-19 13:16:26.745  6200  6200 D AndroidRuntime: 
03-19 13:16:26.745  6200  6200 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-19 13:16:26.745  6200  6200 D AndroidRuntime: CheckJNI is OFF
03-19 13:16:26.745  6200  6200 D AndroidRuntime: readGMSProperty: start
03-19 13:16:26.745  6200  6200 D AndroidRuntime: readGMSProperty: already setted!!
03-19 13:16:26.745  6200  6200 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-19 13:16:26.745  6200  6200 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-19 13:16:26.745  6200  6200 D AndroidRuntime: readGMSProperty: end
03-19 13:16:26.745  6200  6200 D AndroidRuntime: addProductProperty: start
03-19 13:16:26.875  6200  6200 E AffinityControl: AffinityControl: registerfunction enter
03-19 13:16:26.905  6200  6200 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
03-19 13:16:26.925  1016  3796 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-19 13:16:26.925  1016  3796 D PackageManager: START PACKAGE DELETE: observer{764172302}
03-19 13:16:26.925  1016  3796 D PackageManager: pkg{<packageName>}
03-19 13:16:26.925  1016  3796 D PackageManager: user{0}
03-19 13:16:26.925  1016  3796 D PackageManager: caller{2000}
03-19 13:16:26.925  1016  3796 D PackageManager: flags{2}
03-19 13:16:26.925  1016  3796 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-19 13:16:26.925  1016  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-19 13:16:26.925  1016  3796 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-19 13:16:26.925  1016  3796 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-19 13:16:26.925  1016  3796 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-19 13:16:26.925  1016  3796 I PackageManager: Package doesn't exist in get block uninstall com.test.thalitest
03-19 13:16:26.925  1016  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-19 13:16:26.925  1016  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-19 13:16:26.935  1016  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
03-19 13:16:26.935  1016  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
03-19 13:16:26.935  1016  1055 W PackageManager: Package named 'com.test.thalitest' doesn't exist.
03-19 13:16:27.075  1016  1055 I art     : Explicit concurrent mark sweep GC freed 21135(2MB) AllocSpace objects, 82(1312KB) LOS objects, 33% free, 21MB/32MB, paused 2.046ms total 136.764ms
03-19 13:16:27.075  1016  1055 D PackageManager: result of delete: -1{764172302}
03-19 13:16:27.075  6200  6200 E Pm      : Failure details: Bundle[{android.content.pm.extra.STATUS=1, android.content.pm.extra.PACKAGE_NAME=com.test.thalitest, android.content.pm.extra.LEGACY_STATUS=-1, android.content.pm.extra.STATUS_MESSAGE=DELETE_FAILED_INTERNAL_ERROR}]
03-19 13:16:27.075  6200  6200 D AndroidRuntime: Shutting down VM
03-19 13:16:27.285  6200  6200 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.

```
