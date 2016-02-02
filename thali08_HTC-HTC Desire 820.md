#### Test 5797209499148df_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1116): WifiActivity: 1
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,--------- beginning of /dev/log/main
I/HtcModeClient( 1486): handler message = 4011
E/HtcModeClient( 1486): Check connection and retry 12 times. Stop service and kill this process.
D/HtcModeClient( 1486): Don't start project servcice
D/HtcModeClient( 1486): setEject: MEDIA_EJECT_STATE = true
D/HtcModeClient( 1486): connectState: CONNECTION_READY = false
D/SilentMusic( 1486): call stop
D/HtcModeClient( 1486): close connection
W/HtcModeClient( 1486): leaveProjectMode: It does not enter ProjectMode
W/CANMesgAgentLocalSocket( 1486): read the terminate packet, so break
E/cutils-trace( 4319): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4319): ====startRecUseTime====
D/htc.customization.log.level( 4319):  is 
W/CustomizationLogLevel( 4319): Level value is invalid, use default level 2
D/CustomizationManager( 4319):  Read ACC file spent 0.051 (s)
D/CIDMapFileReader( 4319): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4319): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4319): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4319): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4319): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4319): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4319): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4319): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4319): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4319): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4319): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4319): Parsing tag category name = system
I/CustomizationCIDLoader( 4319): Parsing tag category name = application
I/CustomizationCIDLoader( 4319): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4319): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4319): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4319): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4319): Parsing tag category name = Settings
D/CustomizationManager( 4319):  Read CID file spent 0.090 (s)
D/CustomizationManager( 4319):  All configurations done spent 0.090 (s)
W/HtcNativeFlag( 4319): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4319): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4319): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4319): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4319
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1172): environment dirty rate=0 [2][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 19
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 19
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  907): mEventCount = 1200
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 38
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1172): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{425e2b68 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  907): acquireWL(4260da68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{423a7698: PendingIntentRecord{42113770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=100683, Int=0
,D/PMS     (  907): releaseWL(4260da68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1116): now=1454416560057 next=59943
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 19
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 57
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1172): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  907): acquireWL(426ae258): PARTIAL_WAKE_LOCK  Icing 0x1 2241 10028 null
,D/PMS     (  907): releaseWL(426ae258): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(4269bed0): PARTIAL_WAKE_LOCK  Icing 0x1 2241 10028 null
,D/PMS     (  907): releaseWL(4269bed0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(42778810): PARTIAL_WAKE_LOCK  Icing 0x1 2241 10028 null
,D/PMS     (  907): releaseWL(42778810): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(42691468): PARTIAL_WAKE_LOCK  Icing 0x1 2241 10028 null
,D/PMS     (  907): releaseWL(42691468): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=38 rxSum=28} preTxRxSum={txSum=37 rxSum=27}
D/WifiDataStallTracker(  907): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  907): onDataStallAlarm: tag=19813 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19814 delay=15s
D/PMS     (  907): acquireWL(42602120): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{4256b6f0: PendingIntentRecord{4259a2a0 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=102410, Int=0
D/PMS     (  907): releaseWL(42602120): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/SensorManager(  907): mEventCount = 1350
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 76
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1172): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  907): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4335 uid=10077 gids={50077}
,D/PMS     (  907): acquireWL(4273baa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10077}
,V/AlarmManager(  907): sending alarm PendingIntent{4208f2e0: PendingIntentRecord{4208f2a8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454416563743, Int=60000
,D/PMS     (  907): releaseWL(4273baa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 4335): SMSBackupAgentService started
,D/SMSBackup( 4335): Checking restore status
,D/SMSBackup( 4335): Restore complete
,D/SMSBackup( 4335): cancelCheckAlarm
,D/SMSBackup( 4335): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  907): killProcessQuiet, pid=3984
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3984:com.htc.task.gtask/u0a67 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3984
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 19
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 95
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1172): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:65, mTXpacketCount:62, avgLinkspeed:19,mAvgTxRate54
,D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 19
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1172): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true,
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/PMS     (  907): Going to sleep due to screen timeout...
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421570c8
D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
,W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
,W/SensorService(  907): pid=907, uid=1000
W/PMS     (  907): mWirelessDisplayManager is null
W/BatSI   (  907): Couldn't get kernel wake lock stats
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
,V/LightsService(  907): setLight #0: color=#0
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421570c8, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41b3a210
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@41d83f20
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,D/WIFI_ICON( 1116): WifiActivity: 0
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 408ms
,W/PnPMgr  (  358): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
,V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4277e5b8)
,I/IntentController( 1116): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
D/PMS     (  907): OOBE c monitor 11
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
D/PMN     (  907): wakingUp
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
,I/InputMethodManagerService(  907): Disable input method client, pid=1273
D/NfcService( 1255): ScreenObserver: OFF
D/NfcService( 1255): applyRouting - 0
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/NfcService( 1255): applyRouting -2
I/WindowManager(  907): No lock screen! windowToken=null
D/PMN     (  907): onScreenOn
D/PMS     (  907): acquireWL(42617338): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19815 delay=15s
W/XT9_C   ( 1208): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1208): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1208): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  907): releaseWL(42617338): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  907): acquireWL(42618f30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42618f30): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/MtpService( 2441): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2441): [MTP][onReceive]-
,D/NfcService( 1255): applyRouting - 0
,D/NfcService( 1255): applyRouting -2
D/PMS     (  907): acquireWL(42740da8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1255 1027 null
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1172): SET_SCREEN_ON:On
I/wpa_supplicant( 1172): htc_wext_set_keepalive +
I/wpa_supplicant( 1172): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1172): getPrivFuncNum +	
I/wpa_supplicant( 1172): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1172): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1172): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1172): BG scan when screen On
I/wpa_supplicant( 1172): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1172): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): Match BG scan, scan!
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  907):    returned true
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/PMS     (  907): releaseWL(42740da8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
D/PowerUI ( 1116): closing low battery warning: level=100
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,I/SensorManager(  907): mEventCount = 1500
,I/ClockThread( 1116): stop update clock
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4353 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  378): ParamSet string: screen_state=on
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/NetworkPolicy(  907): updateScreenOn: false
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,W/ContextImpl( 4353): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -59 abnormalRssiCnt = 0 newLinkSpeed = 19
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 38
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1172): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(426c5fc8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4353 1000 null
,E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/SmartSyncUtils( 4353): isEpsOn(), nState = 0
D/PMS     (  907): acquireWL(426c7aa8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1466 10028 null
,D/PMS     (  907): releaseWL(426c7aa8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1853): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1853): onScreenOn: 1454416571307
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1853): onScreenOn: 1454416571307
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41b3a210
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41b3a210, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@41d83f20
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMS     (  907): releaseWL(426c5fc8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/PMN     (  907): goingToSleep
D/PMS     (  907): acquireWL(426ec548): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
,I/FeedHostManager( 1273): [onPause]
I/FeedProviderManager( 1273): onPause
,I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41bcd510
I/SocialFeedProvider( 1273): +onPause
,I/SocialFeedProvider( 1273): -onPause
,D/AlarmManager(  907): ACTION_SCREEN_OFF
,I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=19815 mDataStallAlarmIntent=PendingIntent{42522a50: PendingIntentRecord{4259a2a0 android broadcastIntent}}
I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1172): SET_SCREEN_ON:Off
I/wpa_supplicant( 1172): htc_wext_set_keepalive +
I/wpa_supplicant( 1172): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1172): getPrivFuncNum +	
I/wpa_supplicant( 1172): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1172): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1172): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1172): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1172): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  907):    returned true
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(426dd4f8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
,D/PMS     (  907): releaseWL(426ec548): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
V/SRS_Proc(  378): ParamSet string: screen_state=off
,D/SmartSyncUtils( 4353): getMobilePolicyEnabled, result = true
D/NetworkPolicy(  907): updateScreenOn: false
,D/ContactMessageStore( 1245): start background delete task...
D/ContactMessageStore( 1245): size: 0 , 0
,D/ContactMessageStore( 1245): Background delete complete
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] getTotalRam: 1873 Mb
,D/wpa_supplicant( 1172): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1172): nl80211: survey data missing!
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1172): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(426dd4f8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/PMS     (  907): acquireWL(427c5e18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1466 10028 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1853): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1853): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1853): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1853): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1853): onScreenOff
D/PMS     (  907): releaseWL(427c5e18): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/Process (  907): killProcessQuiet, pid=4016
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4016:com.htc.updater/u0a84 (adj 15): empty #17
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/AutoSetting( 1400): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 1400): service - onCreate()
,D/AutoSetting( 1400): service - AddressCache: using context: com.htc.Weather
I/ActivityManager(  907): Recipient 4016
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TetherSettings( 4210): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4210): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4210): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4210): Cust_ConnectToPC   : spcsc>false
D/        ( 4210): Cust_ConnectToPC   : IPT>true
,D/        ( 4210): Cust_ConnectToPC   : Singel_USB>false
,D/AutoSetting( 1400): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/LocationManagerService(  907): request 425bcab8 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
,D/LocationManagerService(  907): provider request: passive ProviderRequest[ON interval=0]
,W/Settings( 4210): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4210): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4210): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4210): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 4210): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 4210): onReceive:android.intent.action.USER_PRESENT
W/Settings( 4210): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4210):  defaultType:0
W/ContextImpl( 4210): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4353): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4210): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4210): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4210): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4210): Cust_ConnectToPC   : spcsc>false
D/        ( 4210): Cust_ConnectToPC   : IPT>true
,D/        ( 4210): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4210): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4210): Index of the first 1 = -1
W/Settings( 4210): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4210): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4210): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4210): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
W/ContextImpl( 4210): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4210): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
D/SmartNS_Utility( 4210): [ACC]android_networking:tethering_guard_support=false
,W/ContextImpl( 4353): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4353): isEpsOn(), nState = 0
D/SmartSyncUtils( 4353): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4353): getMobilePolicyEnabled, result = true,
,D/WifiService(  907): New client listening to asynchronous messages
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41d83f20
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41d83f20, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@41d83f20, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@41d83f20
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4229b560 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4229b560 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  907): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  907): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  907): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  907): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  907): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  907): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  907): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  907): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  907): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  907): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  907): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  907): 	at dalvik.system.NativeStart.main(Native Method)
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC <<
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1172): Add randomness: count=8 entropy=1
D/wpa_supplicant( 1172): Add randomness: count=9 entropy=2
D/wpa_supplicant( 1172): Add randomness: count=10 entropy=3
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_,supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=4/32 last_scan_full=0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1172): Add randomness: count=11 entropy=4
D/wpa_supplicant( 1172): Add randomness: count=12 entropy=5
D/wpa_supplicant( 1172): Add randomness: count=13 entropy=6
D/wpa_supplicant( 1172): Add randomness: count=14 entropy=7
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1172): State: DISCONNECTED -> INACTIVE
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (489) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-46
,I/wpa_supplicant( 1172): tsf=0000000114771341
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=1
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000114771366
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000114771377
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
,I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000000114771387
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@422987d8 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@422987d8 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@422987d8 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 114771341, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -59, frequency: 2412, timestamp: 114771366, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 114771377, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 114771387, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,D/AutoSetting( 1486): service - handleMessage() stop self
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/AutoSetting( 1486): service - handleMessage() quit looper
D/AutoSetting( 1486): service - onDestroy() END
,I/ActivityManager(  907): Killing 3898:com.htc.musicenhancer/u0a51 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=3898
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 3898
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1400): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1400): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1400): service - requestNLP() NetworkLocationProvider not enabled
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{42775810 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(425e9868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+,
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(425e9868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=15 entropy=8
D/wpa_supplicant( 1172): Add randomness: count=16 entropy=9
D/wpa_supplicant( 1172): Add randomness: count=17 entropy=10
D/wpa_supplicant( 1172): Add randomness: count=18 entropy=11
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=4/32 ,last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=19 entropy=12
D/wpa_supplicant( 1172): Add randomness: count=20 entropy=13
D/wpa_supplicant( 1172): Add randomness: count=21 entropy=14
D/wpa_supplicant( 1172): Add randomness: count=22 entropy=15
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0,
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (489) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-46
I/wpa_supplicant( 1172): tsf=0000000133054450
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=1
,I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-58
I/wpa_supplicant( 1172): tsf=0000000133054476
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000133054487
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000000133054497
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0,
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 133054450, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 133054476, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 133054487, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 133054497, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  907): acquireWL(42353538): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{424fb158: PendingIntentRecord{424fdf08 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141367, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{4273af70: PendingIntentRecord{425a7ef0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=142198, Int=0
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  907): acquireWL(426b27d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10028)
,D/PMS     (  907): releaseWL(42353538): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/PMS     (  907): acquireWL(427673a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10028 null
,D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =f971 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE,
D/PMS     (  907): releaseWL(427673a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1400): service - handleMessage() stop self
,D/AutoSetting( 1400): service - handleMessage() quit looper
,D/AutoSetting( 1400): service - onDestroy() END
,D/Process (  907): killProcessQuiet, pid=3571
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3571:com.google.android.gms.unstable/u0a28 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3571
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=238
D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
I/global  (  907): call createSocket() return a new socket.
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  907): releaseWL(426b27d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=23 entropy=16
D/wpa_supplicant( 1172): Add randomness: count=24 entropy=17
D/wpa_supplicant( 1172): Add randomness: count=25 entropy=18
D/wpa_supplicant( 1172): Add randomness: count=26 entropy=19
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=4/3,2 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=27 entropy=20
D/wpa_supplicant( 1172): Add randomness: count=28 entropy=21
D/wpa_supplicant( 1172): Add randomness: count=29 entropy=22
D/wpa_supplicant( 1172): Add randomness: count=30 entropy=23
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0,
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (489) for get BSS: id=0,
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-46
I/wpa_supplicant( 1172): tsf=0000000133054450
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=1
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-58
I/wpa_supplicant( 1172): tsf=0000000151194598
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ====,
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000151194609
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000000151194619
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 133054450, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 151194598, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 151194609, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 151194619, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(426db1b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423a7698: PendingIntentRecord{42113770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=160683, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(426db1b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
D/wpa_supplicant( 1172): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=31 entropy=24
D/wpa_supplicant( 1172): Add randomness: count=32 entropy=25
D/wpa_supplicant( 1172): Add randomness: count=33 entropy=26
D/wpa_supplicant( 1172): Add randomness: count=34 entropy=27
D/wpa_supplicant( 1172): Add randomness: count=35 entropy=28
D/wpa_supplicant( 1172): Add randomness: count=36 entropy=29
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 5: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (6 ,BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1172): BSS: last_scan_res_used=6/32 last_scan_full=0
,D/wpa_supplicant( 1172): Add randomness: count=37 entropy=30
D/wpa_supplicant( 1172): Add randomness: count=38 entropy=31
D/wpa_supplicant( 1172): Add randomness: count=39 entropy=32
D/wpa_supplicant( 1172): Add randomness: count=40 entropy=33
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1172): Add randomness: count=41 entropy=34
D/wpa_supplicant( 1172): Add randomness: count=42 entropy=35
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (755) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-46
I/wpa_supplicant( 1172): tsf=0000000169485617
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=1
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-58
I/wpa_supplicant( 1172): tsf=0000000169485647
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
,I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000169485657
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
,I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000000169485668
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=4
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-89
I/wpa_supplicant( 1172): tsf=0000000169485916
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=5
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-90
I/wpa_supplicant( 1172): tsf=0000000169485900
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 169485617, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 169485647, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 169485657, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 169485668, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 169485916, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 169485900, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42640a80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/PMS     (  907): releaseWL(42640a80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(427727e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10026}
,V/AlarmManager(  907): sending alarm PendingIntent{426a0ef8: PendingIntentRecord{425baf50 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=174883, Int=0
,D/PMS     (  907): releaseWL(427727e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/TelephonyReceiver( 1245): switchBindHtcMsgCursor: null
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2241/10028)
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
D/wpa_supplicant( 1172): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=43 entropy=36
D/wpa_supplicant( 1172): Add randomness: count=44 entropy=37
D/wpa_supplicant( 1172): Add randomness: count=45 entropy=38
D/wpa_supplicant( 1172): Add randomness: count=46 entropy=39
D/wpa_supplicant( 1172): Add randomness: count=47 entropy=40
D/wpa_supplicant( 1172): Add randomness: count=48 entropy=41
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 5: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (6 ,BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
D/wpa_supplicant( 1172): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=49 entropy=42
D/wpa_supplicant( 1172): Add randomness: count=50 entropy=43
D/wpa_supplicant( 1172): Add randomness: count=51 entropy=44
D/wpa_supplicant( 1172): Add randomness: count=52 entropy=45
D/wpa_supplicant( 1172): Add randomness: count=53 entropy=46
D/wpa_supplicant( 1172): Add randomness: count=54 entropy=47
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0,
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (755) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-46
I/wpa_supplicant( 1172): tsf=0000000187764825
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=1
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-58
I/wpa_supplicant( 1172): tsf=0000000187764852
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000187764863
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000000187764873
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=4
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-89
I/wpa_supplicant( 1172): tsf=0000000187764882
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=5
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-90
I/wpa_supplicant( 1172): tsf=0000000187764892
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 187764825, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 187764852, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 187764863, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 187764873, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 187764882, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 187764892, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(426ea8d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(426ea8d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
,I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
,D/wpa_supplicant( 1172): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
D/wpa_supplicant( 1172): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=55 entropy=48
D/wpa_supplicant( 1172): Add randomness: count=56 entropy=49
D/wpa_supplicant( 1172): Add randomness: count=57 entropy=50
D/wpa_supplicant( 1172): Add randomness: count=58 entropy=51
D/wpa_supplicant( 1172): Add randomness: count=59 entropy=52
D/wpa_supplicant( 1172): Add randomness: count=60 entropy=53
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 5: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172),: [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1172): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=61 entropy=54
D/wpa_supplicant( 1172): Add randomness: count=62 entropy=55
D/wpa_supplicant( 1172): Add randomness: count=63 entropy=56
D/wpa_supplicant( 1172): Add randomness: count=64 entropy=57
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1172): Add randomness: count=65 entropy=58
D/wpa_supplicant( 1172): Add randomness: count=66 entropy=59
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (755) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-46
I/wpa_supplicant( 1172): tsf=0000000206056286
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=1
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-58
I/wpa_supplicant( 1172): tsf=0000000206056313
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000206056323
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
,I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000000206056333
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=4
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-89
I/wpa_supplicant( 1172): tsf=0000000206056342
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=5
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-90
I/wpa_supplicant( 1172): tsf=0000000206056352
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 206056286, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiStateMachine(  907): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 206056313, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 206056323, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 206056333, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 206056342, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 206056352, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList,
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0,
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(427043e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423a7698: PendingIntentRecord{42113770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=220683, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(427043e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=67 entropy=60
D/wpa_supplicant( 1172): Add randomness: count=68 entropy=61
D/wpa_supplicant( 1172): Add randomness: count=69 entropy=62
D/wpa_supplicant( 1172): Add randomness: count=70 entropy=63
D/wpa_supplicant( 1172): Add randomness: count=71 entropy=64
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplica,nt( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=72 entropy=65
D/wpa_supplicant( 1172): Add randomness: count=73 entropy=66
D/wpa_supplicant( 1172): Add randomness: count=74 entropy=67
D/wpa_supplicant( 1172): Add randomness: count=75 entropy=68
D/wpa_supplicant( 1172): Add randomness: count=76 entropy=69
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (755) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-46
I/wpa_supplicant( 1172): tsf=0000000224439319
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=1
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-58
I/wpa_supplicant( 1172): tsf=0000000224439346
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000224439356
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000000224439366
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=4
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-89
I/wpa_supplicant( 1172): tsf=0000000206056342
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=5
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-90
I/wpa_supplicant( 1172): tsf=0000000224439376
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 224439319, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 224439346, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 224439356, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 224439366, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 206056342, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 224439376, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=77 entropy=70
D/wpa_supplicant( 1172): Add randomness: count=78 entropy=71
D/wpa_supplicant( 1172): Add randomness: count=79 entropy=72
D/wpa_supplicant( 1172): Add randomness: count=80 entropy=73
D/wpa_supplicant( 1172): Add randomness: count=81 entropy=74
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplica,nt( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=82 entropy=75
D/wpa_supplicant( 1172): Add randomness: count=83 entropy=76
D/wpa_supplicant( 1172): Add randomness: count=84 entropy=77
D/wpa_supplicant( 1172): Add randomness: count=85 entropy=78
D/wpa_supplicant( 1172): Add randomness: count=86 entropy=79
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (755) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-46
I/wpa_supplicant( 1172): tsf=0000000242714561
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=1
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-58
I/wpa_supplicant( 1172): tsf=0000000242714587
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000242714597
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000000242714607
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=4
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-89
I/wpa_supplicant( 1172): tsf=0000000242714616
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=5
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-90
I/wpa_supplicant( 1172): tsf=0000000224439376
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ####
,D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 242714561, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 242714587, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 242714597, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 242714607, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 242714616, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 224439376, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  907): acquireWL(427e9280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(427e9280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-75
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=87 entropy=80
D/wpa_supplicant( 1172): Add randomness: count=88 entropy=81
D/wpa_supplicant( 1172): Add randomness: count=89 entropy=82
D/wpa_supplicant( 1172): Add randomness: count=90 entropy=83
D/wpa_supplicant( 1172): Add randomness: count=91 entropy=84
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplica,nt( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-75
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=92 entropy=85
D/wpa_supplicant( 1172): Add randomness: count=93 entropy=86
D/wpa_supplicant( 1172): Add randomness: count=94 entropy=87
D/wpa_supplicant( 1172): Add randomness: count=95 entropy=88
D/wpa_supplicant( 1172): Add randomness: count=96 entropy=89
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
,I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (631) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-46
I/wpa_supplicant( 1172): tsf=0000000260954713
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=1
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-58
I/wpa_supplicant( 1172): tsf=0000000260954740
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000260954750
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-75
I/wpa_supplicant( 1172): tsf=0000000260954760
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
,I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=4
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-89
I/wpa_supplicant( 1172): tsf=0000000260954769
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ####
D/WifiP2pService(  907): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 260954713, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 260954740, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 260954750, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2427, timestamp: 260954760, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 260954769, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1172): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=97 entropy=90
D/wpa_supplicant( 1172): Add randomness: count=98 entropy=91
D/wpa_supplicant( 1172): Add randomness: count=99 entropy=92
D/wpa_supplicant( 1172): Add randomness: count=100 entropy=93
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1172): BSS: last_scan_res_u,sed=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=101 entropy=94
D/wpa_supplicant( 1172): Add randomness: count=102 entropy=95
D/wpa_supplicant( 1172): Add randomness: count=103 entropy=96
D/wpa_supplicant( 1172): Add randomness: count=104 entropy=97
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (631) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-46
I/wpa_supplicant( 1172): tsf=0000000279340445
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=1
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-58
I/wpa_supplicant( 1172): tsf=0000000260954740
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000279340471
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-73
I/wpa_supplicant( 1172): tsf=0000000279340482
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=4
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-89
I/wpa_supplicant( 1172): tsf=0000000279340491
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=0 what=1474,61 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 279340445, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0,
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 260954740, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 279340471, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2427, timestamp: 279340482, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 279340491, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42820278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423a7698: PendingIntentRecord{42113770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=280683, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42820278): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-74
D/wpa_supplicant( 1172): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=105 entropy=98
D/wpa_supplicant( 1172): Add randomness: count=106 entropy=99
D/wpa_supplicant( 1172): Add randomness: count=107 entropy=100
D/wpa_supplicant( 1172): Add randomness: count=108 entropy=101
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-74
D/wpa_supplicant( 1172): BSS: last_scan_res_us,ed=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=109 entropy=102
D/wpa_supplicant( 1172): Add randomness: count=110 entropy=103
D/wpa_supplicant( 1172): Add randomness: count=111 entropy=104
D/wpa_supplicant( 1172): Add randomness: count=112 entropy=105
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (631) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-46
I/wpa_supplicant( 1172): tsf=0000000297634720
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=1
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000297634747
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000297634758
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-74
I/wpa_supplicant( 1172): tsf=0000000297634769
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=4
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-89
I/wpa_supplicant( 1172): tsf=0000000279340491
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 297634720, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -59, frequency: 2412, timestamp: 297634747, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 297634758, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2427, timestamp: 297634769, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 279340491, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(4283d4b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{41db26c0: PendingIntentRecord{424c8120 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=304695, Int=0
,D/PMS     (  907): acquireWL(4283e448): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4388 uid=10047 gids={50047, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  907): sending alarm PendingIntent{4250bf80: PendingIntentRecord{42525248 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1454416679990, Int=10800000
D/PMS     (  907): releaseWL(4283d4b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42842530): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(4283e448): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(42842530): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4388/10047)
,D/Process (  907): killProcessQuiet, pid=4076
,I/ActivityManager(  907): Killing 4076:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 4076
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(42850898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42850898): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
D/wpa_supplicant( 1172): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=113 entropy=106
D/wpa_supplicant( 1172): Add randomness: count=114 entropy=107
D/wpa_supplicant( 1172): Add randomness: count=115 entropy=108
D/wpa_supplicant( 1172): Add randomness: count=116 entropy=109
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
D/wpa_supplicant( 1172): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=117 entropy=110
D/wpa_supplicant( 1172): Add randomness: count=118 entropy=111
D/wpa_supplicant( 1172): Add randomness: count=119 entropy=112
D/wpa_supplicant( 1172): Add randomness: count=120 entropy=113
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (489) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-46
I/wpa_supplicant( 1172): tsf=0000000315874637
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=1
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000315874664
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000315874675
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-73
,I/wpa_supplicant( 1172): tsf=0000000315874684
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 315874637, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -59, frequency: 2412, timestamp: 315874664, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 315874675, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2427, timestamp: 315874684, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults,
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
D/wpa_supplicant( 1172): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=121 entropy=114
D/wpa_supplicant( 1172): Add randomness: count=122 entropy=115
D/wpa_supplicant( 1172): Add randomness: count=123 entropy=116
D/wpa_supplicant( 1172): Add randomness: count=124 entropy=117
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
D/wpa_supplicant( 1172): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=125 entropy=118
D/wpa_supplicant( 1172): Add randomness: count=126 entropy=119
D/wpa_supplicant( 1172): Add randomness: count=127 entropy=120
D/wpa_supplicant( 1172): Add randomness: count=128 entropy=121
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (489) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-46
I/wpa_supplicant( 1172): tsf=0000000334261123
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=1
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000334261149
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000334261159
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-73
I/wpa_supplicant( 1172): tsf=0000000334261169
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-46], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 334261123, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -59, frequency: 2412, timestamp: 334261149, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 334261159, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2427, timestamp: 334261169, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42880e80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{423a7698: PendingIntentRecord{42113770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=340683, Int=0
,D/PMS     (  907): releaseWL(42880e80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-88
D/wpa_supplicant( 1172): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=129 entropy=122
D/wpa_supplicant( 1172): Add randomness: count=130 entropy=123
D/wpa_supplicant( 1172): Add randomness: count=131 entropy=124
D/wpa_supplicant( 1172): Add randomness: count=132 entropy=125
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 3: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-88
D/wpa_supplicant( 1172): BSS: last_sca,n_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=133 entropy=126
D/wpa_supplicant( 1172): Add randomness: count=134 entropy=127
D/wpa_supplicant( 1172): Add randomness: count=135 entropy=128
D/wpa_supplicant( 1172): Add randomness: count=136 entropy=129
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (613) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000352514891
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=1
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000334261149
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000352514918
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-73
I/wpa_supplicant( 1172): tsf=0000000352514929
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=6
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-88
I/wpa_supplicant( 1172): tsf=0000000352514938
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 352514891, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -59, frequency: 2412, timestamp: 334261149, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 352514918, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2427, timestamp: 352514929, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 352514938, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  4 [-88], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): add 5 to mScanResults
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4289e060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10028}
,V/AlarmManager(  907): sending alarm PendingIntent{423490f0: PendingIntentRecord{42664c98 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1454416816554, Int=0
,D/PMS     (  907): releaseWL(4289e060): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,W/Uploader( 2241): No account for auth token provided
,D/libc    ( 2241): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 2241): [NET] getaddrinfo-,err=8
D/libc    ( 2241): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 2241): [NET] getaddrinfo-, 1
,D/libc    ( 2241): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =6316 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=87
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2241): [NET] getaddrinfo_proxy-, success
I/global  ( 2241): call createSocket() return a new socket.
D/libc    ( 2241): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 2241): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2241): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 2241): [NET] getaddrinfo-,err=8
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2241/10028),
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2241/10028)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2241/10028)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,W/GLSUser ( 1360): GoogleAccountDataService.getToken()
,W/GLSActivity( 1360): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1360): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1360): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DotMatrix( 1589): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,W/GLSActivity( 1360): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1360): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1360): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1360): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1360): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1360): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1360): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1360): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41be2888 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,E/PlayEventLogger( 4152): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4152): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4152): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4152): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4152): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4152): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4152): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 4152): 	at dalvik.system.NativeStart.run(Native Method)
,I/RemoteViews.Performance( 1116): com.google.android.gms 1 12 4 12
,D/libc    ( 4152): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4152): [NET] getaddrinfo-,err=8
D/libc    ( 4152): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4152): [NET] getaddrinfo-, 1
,D/libc    ( 4152): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =e70d +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4152): [NET] getaddrinfo_proxy-, success
I/global  ( 4152): call createSocket() return a new socket.
D/libc    ( 4152): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4152): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4152): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 4152): [NET] getaddrinfo-,err=8
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=137 entropy=130
D/wpa_supplicant( 1172): Add randomness: count=138 entropy=131
D/wpa_supplicant( 1172): Add randomness: count=139 entropy=132
D/wpa_supplicant( 1172): Add randomness: count=140 entropy=133
D/wpa_supplicant( 1172): Add randomness: count=141 entropy=134
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 3: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45,
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=142 entropy=135
D/wpa_supplicant( 1172): Add randomness: count=143 entropy=136
D/wpa_supplicant( 1172): Add randomness: count=144 entropy=137
D/wpa_supplicant( 1172): Add randomness: count=145 entropy=138
D/wpa_supplicant( 1172): Add randomness: count=146 entropy=139
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (642) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
,I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000370834796
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000370834822
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-73
I/wpa_supplicant( 1172): tsf=0000000370834833
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=6
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
,I/wpa_supplicant( 1172): level=-88
I/wpa_supplicant( 1172): tsf=0000000370834843
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=7
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-88
I/wpa_supplicant( 1172): tsf=0000000370834852
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList,
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0,
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 370834796, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 370834822, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2427, timestamp: 370834833, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 370834843, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 370834852, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42902c80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null,
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42902c80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
D/wpa_supplicant( 1172): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=147 entropy=140
D/wpa_supplicant( 1172): Add randomness: count=148 entropy=141
D/wpa_supplicant( 1172): Add randomness: count=149 entropy=142
D/wpa_supplicant( 1172): Add randomness: count=150 entropy=143
D/wpa_supplicant( 1172): Add randomness: count=151 entropy=144
D/wpa_supplicant( 1172): Add randomness: count=152 entropy=145
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 5: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan, results (6 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
D/wpa_supplicant( 1172): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=153 entropy=146
D/wpa_supplicant( 1172): Add randomness: count=154 entropy=147
D/wpa_supplicant( 1172): Add randomness: count=155 entropy=148
D/wpa_supplicant( 1172): Add randomness: count=156 entropy=149
D/wpa_supplicant( 1172): Add randomness: count=157 entropy=150
D/wpa_supplicant( 1172): Add randomness: count=158 entropy=151
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (755) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000389072159
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000389072198
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-73
I/wpa_supplicant( 1172): tsf=0000000389072208
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=6
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-88
,I/wpa_supplicant( 1172): tsf=0000000389072217
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=7
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-88
I/wpa_supplicant( 1172): tsf=0000000389072227
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=8
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000389072186
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ####
,D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 389072159, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 389072198, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2427, timestamp: 389072208, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 389072217, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 389072227, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -59, frequency: 2412, timestamp: 389072186, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 6 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(42922968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423a7698: PendingIntentRecord{42113770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=400683, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42922968): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-89
D/wpa_supplicant( 1172): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=159 entropy=152
D/wpa_supplicant( 1172): Add randomness: count=160 entropy=153
D/wpa_supplicant( 1172): Add randomness: count=161 entropy=154
D/wpa_supplicant( 1172): Add randomness: count=162 entropy=155
D/wpa_supplicant( 1172): Add randomness: count=163 entropy=156
D/wpa_supplicant( 1172): Add randomness: count=164 entropy=157
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 5: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan, results (6 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-89
D/wpa_supplicant( 1172): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=165 entropy=158
D/wpa_supplicant( 1172): Add randomness: count=166 entropy=159
D/wpa_supplicant( 1172): Add randomness: count=167 entropy=160
D/wpa_supplicant( 1172): Add randomness: count=168 entropy=161
D/wpa_supplicant( 1172): Add randomness: count=169 entropy=162
D/wpa_supplicant( 1172): Add randomness: count=170 entropy=163
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (755) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000389072159
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000407354842
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-73
I/wpa_supplicant( 1172): tsf=0000000407354852
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=6
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-89
I/wpa_supplicant( 1172): tsf=0000000389072217
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=7
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-88
I/wpa_supplicant( 1172): tsf=0000000407354871
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=8
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000407354832
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 389072159, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 407354842, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2427, timestamp: 407354852, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 389072217, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 407354871, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -59, frequency: 2412, timestamp: 407354832, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-89
D/wpa_supplicant( 1172): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=171 entropy=164
D/wpa_supplicant( 1172): Add randomness: count=172 entropy=165
D/wpa_supplicant( 1172): Add randomness: count=173 entropy=166
D/wpa_supplicant( 1172): Add randomness: count=174 entropy=167
D/wpa_supplicant( 1172): Add randomness: count=175 entropy=168
D/wpa_supplicant( 1172): Add randomness: count=176 entropy=169
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 5: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan, results (6 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-89
D/wpa_supplicant( 1172): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=177 entropy=170
D/wpa_supplicant( 1172): Add randomness: count=178 entropy=171
D/wpa_supplicant( 1172): Add randomness: count=179 entropy=172
D/wpa_supplicant( 1172): Add randomness: count=180 entropy=173
D/wpa_supplicant( 1172): Add randomness: count=181 entropy=174
D/wpa_supplicant( 1172): Add randomness: count=182 entropy=175
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (755) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000389072159
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000425394827
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-73
I/wpa_supplicant( 1172): tsf=0000000425394837
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=6
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-89
I/wpa_supplicant( 1172): tsf=0000000389072217
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=7
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-88
I/wpa_supplicant( 1172): tsf=0000000425394856
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=8
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000425394816
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 389072159, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 425394827, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2427, timestamp: 425394837, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 389072217, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 425394856, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -59, frequency: 2412, timestamp: 425394816, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 6 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42950838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(42950838): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42744820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(42744820): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-71
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-89
D/wpa_supplicant( 1172): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=183 entropy=176
D/wpa_supplicant( 1172): Add randomness: count=184 entropy=177
D/wpa_supplicant( 1172): Add randomness: count=185 entropy=178
D/wpa_supplicant( 1172): Add randomness: count=186 entropy=179
D/wpa_supplicant( 1172): Add randomness: count=187 entropy=180
D/wpa_supplicant( 1172): Add randomness: count=188 entropy=181
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 5: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan, results (6 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-71
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-89
D/wpa_supplicant( 1172): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=189 entropy=182
D/wpa_supplicant( 1172): Add randomness: count=190 entropy=183
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1172): Add randomness: count=191 entropy=184
D/wpa_supplicant( 1172): Add randomness: count=192 entropy=185
D/wpa_supplicant( 1172): Add randomness: count=193 entropy=186
D/wpa_supplicant( 1172): Add randomness: count=194 entropy=187
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (755) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000443674800
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000443674837
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-71
I/wpa_supplicant( 1172): tsf=0000000443674847
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=6
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-89
I/wpa_supplicant( 1172): tsf=0000000389072217
I/wpa_supplicant( 1172): flags=[WPA2-EAP,-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=7
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-88
I/wpa_supplicant( 1172): tsf=0000000443674866
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=8
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000443674827
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 443674800, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 443674837, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -71, frequency: 2427, timestamp: 443674847, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 389072217, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 443674866, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -59, frequency: 2412, timestamp: 443674827, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-71], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(42606500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423a7698: PendingIntentRecord{42113770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=460683, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42606500): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-71
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
D/wpa_supplicant( 1172): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=195 entropy=188
D/wpa_supplicant( 1172): Add randomness: count=196 entropy=189
D/wpa_supplicant( 1172): Add randomness: count=197 entropy=190
D/wpa_supplicant( 1172): Add randomness: count=198 entropy=191
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-71
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
D/wpa_supplicant( 1172): BSS: last_sca,n_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=199 entropy=192
D/wpa_supplicant( 1172): Add randomness: count=200 entropy=193
D/wpa_supplicant( 1172): Add randomness: count=201 entropy=194
D/wpa_supplicant( 1172): Add randomness: count=202 entropy=195
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (755) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
,I/wpa_supplicant( 1172): tsf=0000000462020837
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000462020863
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-71
I/wpa_supplicant( 1172): tsf=0000000462020874
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS],
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=6
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-89
I/wpa_supplicant( 1172): tsf=0000000389072217
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=7
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
,I/wpa_supplicant( 1172): level=-88
I/wpa_supplicant( 1172): tsf=0000000462020883
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=8,
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000443674827
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 462020837, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 462020863, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -71, frequency: 2427, timestamp: 462020874, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 389072217, distance: ?(cm), distanceSd: ?(cm),
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 462020883, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -59, frequency: 2412, timestamp: 443674827, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 6 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-71], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-74
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=203 entropy=196
D/wpa_supplicant( 1172): Add randomness: count=204 entropy=197
D/wpa_supplicant( 1172): Add randomness: count=205 entropy=198
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-74
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=206 entropy=199
D/wpa_supplicant( 1172): Add randomness: count=207 entropy=200
D/wpa_supplicant( 1172): Add randomness: count=208 entropy=201
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (518) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000480294690
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48,
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000480294718
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-74
I/wpa_supplicant( 1172): tsf=0000000480294729
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=7
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-88
I/wpa_supplicant( 1172): tsf=0000000462020883,
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 480294690, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 480294718, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2427, timestamp: 480294729, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 462020883, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-88], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(425fa750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(425fa750): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-74
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=209 entropy=202
D/wpa_supplicant( 1172): Add randomness: count=210 entropy=203
D/wpa_supplicant( 1172): Add randomness: count=211 entropy=204
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-74
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=212 entropy=205
D/wpa_supplicant( 1172): Add randomness: count=213 entropy=206
D/wpa_supplicant( 1172): Add randomness: count=214 entropy=207
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (376) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000498314326
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000498314352
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-74
I/wpa_supplicant( 1172): tsf=0000000498314363
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 498314326, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 498314352, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -74, frequency: 2427, timestamp: 498314363, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults,
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-74], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=215 entropy=208
D/wpa_supplicant( 1172): Add randomness: count=216 entropy=209
D/wpa_supplicant( 1172): Add randomness: count=217 entropy=210
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=218 entropy=211
D/wpa_supplicant( 1172): Add randomness: count=219 entropy=212
D/wpa_supplicant( 1172): Add randomness: count=220 entropy=213
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplic,ant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (376) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000516721484
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
,I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000516721510
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-73
I/wpa_supplicant( 1172): tsf=0000000516721521
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 516721484, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 516721510, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2427, timestamp: 516721521, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0,
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==,
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(425e3970): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423a7698: PendingIntentRecord{42113770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=520683, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(425e3970): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=221 entropy=214
D/wpa_supplicant( 1172): Add randomness: count=222 entropy=215
D/wpa_supplicant( 1172): Add randomness: count=223 entropy=216
D/wpa_supplicant( 1172): Add randomness: count=224 entropy=217
D/wpa_supplicant( 1172): Add randomness: count=225 entropy=218
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 3: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45,
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=226 entropy=219
D/wpa_supplicant( 1172): Add randomness: count=227 entropy=220
D/wpa_supplicant( 1172): Add randomness: count=228 entropy=221
D/wpa_supplicant( 1172): Add randomness: count=229 entropy=222
D/wpa_supplicant( 1172): Add randomness: count=230 entropy=223
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987,
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (643) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000535024749
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000535024776
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-73
I/wpa_supplicant( 1172): tsf=0000000535024786
,I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=9
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-88
I/wpa_supplicant( 1172): tsf=0000000535024796
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=10
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-89
,I/wpa_supplicant( 1172): tsf=0000000535024806
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 535024749, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 535024776, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0,
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2427, timestamp: 535024786, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 535024796, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 535024806, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList,
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0,
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000),
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(4290db68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4290db68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=231 entropy=224
D/wpa_supplicant( 1172): Add randomness: count=232 entropy=225
D/wpa_supplicant( 1172): Add randomness: count=233 entropy=226
D/wpa_supplicant( 1172): Add randomness: count=234 entropy=227
D/wpa_supplicant( 1172): Add randomness: count=235 entropy=228
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 3: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45,
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=236 entropy=229
D/wpa_supplicant( 1172): Add randomness: count=237 entropy=230
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1172): Add randomness: count=238 entropy=231
D/wpa_supplicant( 1172): Add randomness: count=239 entropy=232
D/wpa_supplicant( 1172): Add randomness: count=240 entropy=233
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (643) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000535024749
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000553274571
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-73
I/wpa_supplicant( 1172): tsf=0000000553274582
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=9
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-88
I/wpa_supplicant( 1172): tsf=0000000553274591
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/w,pa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=10
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-89
I/wpa_supplicant( 1172): tsf=0000000553274601
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 535024749, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 553274571, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2427, timestamp: 553274582, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 553274591, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 553274601, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=241 entropy=234
D/wpa_supplicant( 1172): Add randomness: count=242 entropy=235
D/wpa_supplicant( 1172): Add randomness: count=243 entropy=236
D/wpa_supplicant( 1172): Add randomness: count=244 entropy=237
D/wpa_supplicant( 1172): Add randomness: count=245 entropy=238
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 3: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45,
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=246 entropy=239
D/wpa_supplicant( 1172): Add randomness: count=247 entropy=240
D/wpa_supplicant( 1172): Add randomness: count=248 entropy=241
D/wpa_supplicant( 1172): Add randomness: count=249 entropy=242
D/wpa_supplicant( 1172): Add randomness: count=250 entropy=243
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (643) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000571621543
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000571621570
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-73
I/wpa_supplicant( 1172): tsf=0000000571621580
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=9
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-88
I/wpa_supplicant( 1172): tsf=0000000571621590
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=10
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-89
I/wpa_supplicant( 1172): tsf=0000000571621600
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 571621543, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 571621570, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2427, timestamp: 571621580, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 571621590, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 571621600, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/PMS     (  907): acquireWL(427471f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423a7698: PendingIntentRecord{42113770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=580683, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(427471f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=251 entropy=244
D/wpa_supplicant( 1172): Add randomness: count=252 entropy=245
D/wpa_supplicant( 1172): Add randomness: count=253 entropy=246
D/wpa_supplicant( 1172): Add randomness: count=254 entropy=247
D/wpa_supplicant( 1172): Add randomness: count=255 entropy=248
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wp,a_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=256 entropy=249
D/wpa_supplicant( 1172): Add randomness: count=257 entropy=250
D/wpa_supplicant( 1172): Add randomness: count=258 entropy=251
D/wpa_supplicant( 1172): Add randomness: count=259 entropy=252
D/wpa_supplicant( 1172): Add randomness: count=260 entropy=253
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (757) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000589924764
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000589924802
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-73
I/wpa_supplicant( 1172): tsf=0000000589924812
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=9
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-88
I/wpa_supplicant( 1172): tsf=0000000571621590
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_,supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=10
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-88
I/wpa_supplicant( 1172): tsf=0000000589924822
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=11
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000589924791
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 589924764, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 589924802, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2427, timestamp: 589924812, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 571621590, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 589924822, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiStateMachine(  907): 5: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -59, frequency: 2412, timestamp: 589924791, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1,
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-71
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=261 entropy=254
D/wpa_supplicant( 1172): Add randomness: count=262 entropy=255
D/wpa_supplicant( 1172): Add randomness: count=263 entropy=256
D/wpa_supplicant( 1172): Add randomness: count=264 entropy=257
D/wpa_supplicant( 1172): Add randomness: count=265 entropy=258
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wp,a_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-71
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=266 entropy=259
D/wpa_supplicant( 1172): Add randomness: count=267 entropy=260
D/wpa_supplicant( 1172): Add randomness: count=268 entropy=261
D/wpa_supplicant( 1172): Add randomness: count=269 entropy=262
D/wpa_supplicant( 1172): Add randomness: count=270 entropy=263
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (633) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000608309882
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000608309919
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-71
I/wpa_supplicant( 1172): tsf=0000000608309929
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=10
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-88
I/wpa_supplicant( 1172): tsf=0000000608309938
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=11
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000608309909
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 608309882, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 608309919, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -71, frequency: 2427, timestamp: 608309929, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 608309938, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -59, frequency: 2412, timestamp: 608309909, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-71], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-88], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(426f9070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(426f9070): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1245): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1245): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1245): sku_id=99
D/ContactMessageStore( 1245): start background delete task...
,D/ContactMessageStore( 1245): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1245): size: 0 , 0
,D/ContactMessageStore( 1245): Background delete complete
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=271 entropy=264
D/wpa_supplicant( 1172): Add randomness: count=272 entropy=265
D/wpa_supplicant( 1172): Add randomness: count=273 entropy=266
D/wpa_supplicant( 1172): Add randomness: count=274 entropy=267
D/wpa_supplicant( 1172): Add randomness: count=275 entropy=268
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wp,a_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=276 entropy=269
D/wpa_supplicant( 1172): Add randomness: count=277 entropy=270
D/wpa_supplicant( 1172): Add randomness: count=278 entropy=271
D/wpa_supplicant( 1172): Add randomness: count=279 entropy=272
D/wpa_supplicant( 1172): Add randomness: count=280 entropy=273
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler },
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (633) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000626584942
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000626584980
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427,
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000000626584989
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=10
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-88
I/wpa_supplicant( 1172): tsf=0000000626584998
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=11
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000626584969
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 626584942, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 626584980, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 626584989, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 626584998, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -59, frequency: 2412, timestamp: 626584969, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-88], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==,
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4282bed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423a7698: PendingIntentRecord{42113770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=640683, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4282bed8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=281 entropy=274
D/wpa_supplicant( 1172): Add randomness: count=282 entropy=275
D/wpa_supplicant( 1172): Add randomness: count=283 entropy=276
D/wpa_supplicant( 1172): Add randomness: count=284 entropy=277
D/wpa_supplicant( 1172): Add randomness: count=285 entropy=278
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45,
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=286 entropy=279
D/wpa_supplicant( 1172): Add randomness: count=287 entropy=280
D/wpa_supplicant( 1172): Add randomness: count=288 entropy=281
D/wpa_supplicant( 1172): Add randomness: count=289 entropy=282
D/wpa_supplicant( 1172): Add randomness: count=290 entropy=283
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (758) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000645020736
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000645020761
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3,
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000000645020772
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=10
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-88
I/wpa_supplicant( 1172): tsf=0000000645020792
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=11
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000626584969
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ====,
I/wpa_supplicant( 1172): id=12
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-90
I/wpa_supplicant( 1172): tsf=0000000645020782
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 645020736, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 645020761, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 645020772, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 645020792, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -59, frequency: 2412, timestamp: 626584969, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiStateMachine(  907): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 645020782, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=291 entropy=284
D/wpa_supplicant( 1172): Add randomness: count=292 entropy=285
D/wpa_supplicant( 1172): Add randomness: count=293 entropy=286
D/wpa_supplicant( 1172): Add randomness: count=294 entropy=287
D/wpa_supplicant( 1172): Add randomness: count=295 entropy=288
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45,
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=296 entropy=289
D/wpa_supplicant( 1172): Add randomness: count=297 entropy=290
D/wpa_supplicant( 1172): Add randomness: count=298 entropy=291
D/wpa_supplicant( 1172): Add randomness: count=299 entropy=292
D/wpa_supplicant( 1172): Add randomness: count=300 entropy=293
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (644) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000663322058
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000663322084
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000000663322094
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=10
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-88
I/wpa_supplicant( 1172): tsf=0000000663322114
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=12
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-90
I/wpa_supplicant( 1172): tsf=0000000663322104
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ####
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 663322058, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 663322084, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 663322094, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 663322114, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 663322104, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/Process (  907): killProcessQuiet, pid=4003
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4003:com.htc.sense.mms/u0a64 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4003
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(42869a68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42869a68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
,D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=301 entropy=294
D/wpa_supplicant( 1172): Add randomness: count=302 entropy=295
D/wpa_supplicant( 1172): Add randomness: count=303 entropy=296
D/wpa_supplicant( 1172): Add randomness: count=304 entropy=297
D/wpa_supplicant( 1172): Add randomness: count=305 entropy=298
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 3: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 4: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45,
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=306 entropy=299
D/wpa_supplicant( 1172): Add randomness: count=307 entropy=300
D/wpa_supplicant( 1172): Add randomness: count=308 entropy=301
D/wpa_supplicant( 1172): Add randomness: count=309 entropy=302
D/wpa_supplicant( 1172): Add randomness: count=310 entropy=303
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (644) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000681574748
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000681574775
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000000681574785
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=10
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-88
I/wpa_supplicant( 1172): tsf=0000000681574804
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=12
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462,
I/wpa_supplicant( 1172): level=-90
I/wpa_supplicant( 1172): tsf=0000000681574794
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ####
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 681574748, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 681574775, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 681574785, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 681574804, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 681574794, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=311 entropy=304
D/wpa_supplicant( 1172): Add randomness: count=312 entropy=305
D/wpa_supplicant( 1172): Add randomness: count=313 entropy=306
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=314 entropy=307
D/wpa_supplicant( 1172): Add randomness: count=315 entropy=308
D/wpa_supplicant( 1172): Add randomness: count=316 entropy=309
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (644) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000699969702
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000699969728
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000000699969739
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=10
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-88
I/wpa_supplicant( 1172): tsf=0000000681574804
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=12
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-90
I/wpa_supplicant( 1172): tsf=0000000681574794
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 699969702, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 699969728, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 699969739, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 681574804, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 681574794, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42851bb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423a7698: PendingIntentRecord{42113770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=700684, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42851bb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=317 entropy=310
D/wpa_supplicant( 1172): Add randomness: count=318 entropy=311
D/wpa_supplicant( 1172): Add randomness: count=319 entropy=312
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=320 entropy=313
D/wpa_supplicant( 1172): Add randomness: count=321 entropy=314
D/wpa_supplicant( 1172): A,dd randomness: count=322 entropy=315
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (376) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000718231801
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000718231828
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000000718231839
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 718231801, distance: ?(cm), distanceSd: ?(cm)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 718231828, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 718231839, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/PMS     (  907): acquireWL(42886698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42886698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=323 entropy=316
D/wpa_supplicant( 1172): Add randomness: count=324 entropy=317
D/wpa_supplicant( 1172): Add randomness: count=325 entropy=318
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=326 entropy=319
D/wpa_supplicant( 1172): Add randomness: count=327 entropy=320
D/wpa_supplicant( 1172): Add randomness: count=328 entropy=321
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (376) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000736432033
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000736432061
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000000736432071
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ####
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 736432033, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 736432061, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 736432071, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=329 entropy=322
D/wpa_supplicant( 1172): Add randomness: count=330 entropy=323
D/wpa_supplicant( 1172): Add randomness: count=331 entropy=324
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=332 entropy=325
D/wpa_supplicant( 1172): Add randomness: count=333 entropy=326
D/wpa_supplicant( 1172): Add randomness: count=334 entropy=327
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (376) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000754462012
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000754462040
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000000754462050
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ####
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 754462012, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 754462040, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 754462050, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4290b788): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423a7698: PendingIntentRecord{42113770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=760683, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4290b788): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=335 entropy=328
D/wpa_supplicant( 1172): Add randomness: count=336 entropy=329
D/wpa_supplicant( 1172): Add randomness: count=337 entropy=330
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=338 entropy=331
D/wpa_supplicant( 1172): Add randomness: count=339 entropy=332
D/wpa_supplicant( 1172): Add randomness: count=340 entropy=333
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (376) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
,I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000772704795
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000772704822
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000000772704833
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 772704795, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 772704822, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 772704833, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0,
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=341 entropy=334
D/wpa_supplicant( 1172): Add randomness: count=342 entropy=335
D/wpa_supplicant( 1172): Add randomness: count=343 entropy=336
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=344 entropy=337
D/wpa_supplicant( 1172): Add randomness: count=345 entropy=338
D/wpa_supplicant( 1172): Add randomness: count=346 entropy=339
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
D/WirelessDisplayService(  907): getDiscoveryDongleList
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (376) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000791029186
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412,
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000791029212
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000000791029223
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ####
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 791029186, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 791029212, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 791029223, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42801608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42801608): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
D/wpa_supplicant( 1172): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=347 entropy=340
D/wpa_supplicant( 1172): Add randomness: count=348 entropy=341
D/wpa_supplicant( 1172): Add randomness: count=349 entropy=342
D/wpa_supplicant( 1172): Add randomness: count=350 entropy=343
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 3: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
D/wpa_supplicant( 1172): BSS: last_sca,n_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=351 entropy=344
D/wpa_supplicant( 1172): Add randomness: count=352 entropy=345
D/wpa_supplicant( 1172): Add randomness: count=353 entropy=346
D/wpa_supplicant( 1172): Add randomness: count=354 entropy=347
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (501) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000809284644
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000809284672
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000000809284684
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS],
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=13
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-90
I/wpa_supplicant( 1172): tsf=0000000809284694
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ####
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): P2pEnabledState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-9ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 809284644, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 809284672, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 809284684, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 809284694, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(429191d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423a7698: PendingIntentRecord{42113770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=820683, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(429191d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
D/wpa_supplicant( 1172): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=355 entropy=348
D/wpa_supplicant( 1172): Add randomness: count=356 entropy=349
D/wpa_supplicant( 1172): Add randomness: count=357 entropy=350
D/wpa_supplicant( 1172): Add randomness: count=358 entropy=351
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 3: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
D/wpa_supplicant( 1172): BSS: last_sca,n_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=359 entropy=352
D/wpa_supplicant( 1172): Add randomness: count=360 entropy=353
D/wpa_supplicant( 1172): Add randomness: count=361 entropy=354
D/wpa_supplicant( 1172): Add randomness: count=362 entropy=355
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (501) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000827359136
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000827359163
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000000827359174
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=13
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-90
I/wpa_supplicant( 1172): tsf=0000000827359183
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 827359136, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 827359163, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 827359174, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 827359183, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-70
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
D/wpa_supplicant( 1172): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=363 entropy=356
D/wpa_supplicant( 1172): Add randomness: count=364 entropy=357
D/wpa_supplicant( 1172): Add randomness: count=365 entropy=358
D/wpa_supplicant( 1172): Add randomness: count=366 entropy=359
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 3: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-70
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-90
D/wpa_supplicant( 1172): BSS: last_sca,n_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=367 entropy=360
D/wpa_supplicant( 1172): Add randomness: count=368 entropy=361
D/wpa_supplicant( 1172): Add randomness: count=369 entropy=362
D/wpa_supplicant( 1172): Add randomness: count=370 entropy=363
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (501) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000845761086
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000845761112
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-70
I/wpa_supplicant( 1172): tsf=0000000845761123
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=13
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-90
I/wpa_supplicant( 1172): tsf=0000000845761132
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$600,0:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 845761086, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 845761112, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -70, frequency: 2427, timestamp: 845761123, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 845761132, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-70], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0,
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(428e3f50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(428e3f50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1116): closing low battery warning: level=100
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1589): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1589): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(427892b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(427892b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-70
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=371 entropy=364
D/wpa_supplicant( 1172): Add randomness: count=372 entropy=365
D/wpa_supplicant( 1172): Add randomness: count=373 entropy=366
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-70
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=374 entropy=367
D/wpa_supplicant( 1172): Add randomness: count=375 entropy=368
D/wpa_supplicant( 1172): Add randomness: count=376 entropy=369
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (501) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
,I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000863974655
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000863974681
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-70
I/wpa_supplicant( 1172): tsf=0000000863974691,
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=13
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-90
I/wpa_supplicant( 1172): tsf=0000000845761132
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free,
I/wpa_supplicant( 1172): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 863974655, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 863974681, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -70, frequency: 2427, timestamp: 863974691, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 845761132, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-70], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  0 [-90], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(427a2188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{423a7698: PendingIntentRecord{42113770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=880683, Int=0
,D/PMS     (  907): releaseWL(427a2188): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-70
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=377 entropy=370
D/wpa_supplicant( 1172): Add randomness: count=378 entropy=371
D/wpa_supplicant( 1172): Add randomness: count=379 entropy=372
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-70
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=380 entropy=373
D/wpa_supplicant( 1172): Add randomness: count=381 entropy=374
D/wpa_supplicant( 1172): Add randomness: count=382 entropy=375
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
D/WirelessDisplayService(  907): getDiscoveryDongleList
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (376) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000882318286
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000882318312
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-70
I/wpa_supplicant( 1172): tsf=0000000882318322
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ####
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 882318286, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 882318312, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -70, frequency: 2427, timestamp: 882318322, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-70], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=383 entropy=376
D/wpa_supplicant( 1172): Add randomness: count=384 entropy=377
D/wpa_supplicant( 1172): Add randomness: count=385 entropy=378
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=386 entropy=379
D/wpa_supplicant( 1172): Add randomness: count=387 entropy=380
D/wpa_supplicant( 1172): A,dd randomness: count=388 entropy=381
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (376) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000900601852
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000900601878
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000000900601889
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiP2pService(  907): InactiveState{ when=-5ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-9ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-10ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 900601852, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 900601878, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 900601889, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(429682f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(429682f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=389 entropy=382
D/wpa_supplicant( 1172): Add randomness: count=390 entropy=383
D/wpa_supplicant( 1172): Add randomness: count=391 entropy=384
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=392 entropy=385
D/wpa_supplicant( 1172): Add randomness: count=393 entropy=386
D/wpa_supplicant( 1172): Add randomness: count=394 entropy=387
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (376) for get BSS: id=0
,I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000918844653
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000918844680,
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000000918844691
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 918844653, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 918844680, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 918844691, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0,
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700,
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=395 entropy=388
D/wpa_supplicant( 1172): Add randomness: count=396 entropy=389
D/wpa_supplicant( 1172): Add randomness: count=397 entropy=390
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=398 entropy=391
D/wpa_supplicant( 1172): Add randomness: count=399 entropy=392
D/wpa_supplicant( 1172): Add randomness: count=400 entropy=393
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelem,ent id=0 len=1
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (376) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000937198891
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====,
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000937198917
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000000937198927
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ####
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 937198891, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 937198917, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 937198927, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4271bd18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423a7698: PendingIntentRecord{42113770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=940683, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4271bd18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=401 entropy=394
D/wpa_supplicant( 1172): Add randomness: count=402 entropy=395
D/wpa_supplicant( 1172): Add randomness: count=403 entropy=396
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=404 entropy=397
D/wpa_supplicant( 1172): Add randomness: count=405 entropy=398
D/wpa_supplicant( 1172): Add randomness: count=406 entropy=399
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (376) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000955474916
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000955474943
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====,
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000000955474953
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 955474916, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 955474943, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 955474953, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults,
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (3) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000),
D/WirelessDisplayService(  907): getDiscoveryDongleList
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(42692768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42692768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=407 entropy=400
D/wpa_supplicant( 1172): Add randomness: count=408 entropy=401
D/wpa_supplicant( 1172): Add randomness: count=409 entropy=402
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=410 entropy=403
D/wpa_supplicant( 1172): Add randomness: count=411 entropy=404
D/wpa_supplicant( 1172): Add randomness: count=412 entropy=405
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (376) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000000973889399
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000973889427
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000000973889437
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 973889399, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 973889427, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 973889437, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 3 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=413 entropy=406
D/wpa_supplicant( 1172): Add randomness: count=414 entropy=407
D/wpa_supplicant( 1172): Add randomness: count=415 entropy=408
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=416 entropy=409
D/wpa_supplicant( 1172): Add randomness: count=417 entropy=410
D/wpa_supplicant( 1172): Add randomness: count=418 entropy=411
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplic,ant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (376) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
,I/wpa_supplicant( 1172): tsf=0000000992157488
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000000992157525
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000000992157536
,I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiP2pService(  907): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 992157488, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 992157525, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 992157536, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42777868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423a7698: PendingIntentRecord{42113770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1000683, Int=0
I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42777868): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-71
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=419 entropy=412
D/wpa_supplicant( 1172): Add randomness: count=420 entropy=413
D/wpa_supplicant( 1172): Add randomness: count=421 entropy=414
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-71
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=422 entropy=415
D/wpa_supplicant( 1172): Add randomness: count=423 entropy=416
D/wpa_supplicant( 1172): Add randomness: count=424 entropy=417
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (376) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000001010435017
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000001010435044
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-71
I/wpa_supplicant( 1172): tsf=0000001010435055
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
,I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0,
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1010435017, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 1010435044, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000),
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -71, frequency: 2427, timestamp: 1010435055, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 3 to mScanResults,
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-71], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (3) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4243d5d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000},
V/AlarmManager(  907): sending alarm PendingIntent{41de5440: PendingIntentRecord{42466998 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=785034, Int=0
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..,
V/AlarmManager(  907): sending alarm PendingIntent{42473460: PendingIntentRecord{423b29c8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=928530, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{42680de0: PendingIntentRecord{42555e90 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454417400183, Int=900000
,V/AlarmManager(  907): sending alarm PendingIntent{42610b40: PendingIntentRecord{426e96a0 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454417471653, Int=0
,D/PMS     (  907): acquireWL(423b6668): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1360 10028 null
,D/PMS     (  907): releaseWL(423b6668): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null
D/ConnectivityService(  907): Done.
,D/ConnectivityService(  907): Setting timer for 720seconds
,D/PMS     (  907): acquireWL(425ede90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10028 null
,W/ContextImpl( 4353): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  907): releaseWL(425ede90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PowerUsageService( 4353): call getInstance()
,D/SmartSyncUtils( 4353): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4353): MY_DEBUG = false
,D/PMS     (  907): acquireWL(4283d308): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1360 10028 null
,D/PMS     (  907): releaseWL(4243d5d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(429665e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4353 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4353): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4353): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 2, nStart = 1, nEnd = 2, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4353): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4353): SettingOnTime = 1454461200000, randomSettingOnTime = 1454460154000
,D/SmartSyncScreenOnOffTimeReceiver( 4353): SettingOffTime = 1454457600000, randomSettingOffTime = 1454458060000
,W/BatSI   (  907): Couldn't get kernel wake lock stats
D/SmartSyncScreenOnOffTimeReceiver( 4353): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4353): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4353): bNightModeTurnOffOnce = false
D/PMS     (  907): releaseWL(429665e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/GCM     ( 1360): Message class mow
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10028)
,I/dalvikvm-heap(  907): Grow heap (frag case) to 17.720MB for 146872-byte allocation
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1360/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1360/10028)
D/PMS     (  907): acquireWL(42849c38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1360 10028 null
D/PMS     (  907): releaseWL(42849c38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  907): releaseWL(4283d308): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-71
D/wpa_supplicant( 1172): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=425 entropy=418
D/wpa_supplicant( 1172): Add randomness: count=426 entropy=419
D/wpa_supplicant( 1172): Add randomness: count=427 entropy=420
D/wpa_supplicant( 1172): Add randomness: count=428 entropy=421
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-71
D/wpa_supplicant( 1172): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=429 entropy=422
D/wpa_supplicant( 1172): Add randomness: count=430 entropy=423
D/wpa_supplicant( 1172): Add randomness: count=431 entropy=424
D/wpa_supplicant( 1172): Add randomness: count=432 entropy=425
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (490) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000001028734698
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000001028734726
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-71
I/wpa_supplicant( 1172): tsf=0000001028734748
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
,I/wpa_supplicant( 1172): id=14
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000001028734737
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1028734698, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 1028734726, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -71, frequency: 2427, timestamp: 1028734748, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -59, frequency: 2412, timestamp: 1028734737, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-71], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4271bd48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4271bd48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-71
D/wpa_supplicant( 1172): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=433 entropy=426
D/wpa_supplicant( 1172): Add randomness: count=434 entropy=427
D/wpa_supplicant( 1172): Add randomness: count=435 entropy=428
D/wpa_supplicant( 1172): Add randomness: count=436 entropy=429
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-71
D/wpa_supplicant( 1172): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=437 entropy=430
D/wpa_supplicant( 1172): Add randomness: count=438 entropy=431
D/wpa_supplicant( 1172): Add randomness: count=439 entropy=432
D/wpa_supplicant( 1172): Add randomness: count=440 entropy=433
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (490) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000001047061783
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000001047061820
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-71
I/wpa_supplicant( 1172): tsf=0000001047061830
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=14
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000001047061810
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0,
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1047061783, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 1047061820, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -71, frequency: 2427, timestamp: 1047061830, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -59, frequency: 2412, timestamp: 1047061810, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0,
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-71], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0,
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42755e78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423a7698: PendingIntentRecord{42113770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1060683, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42755e78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=441 entropy=434
D/wpa_supplicant( 1172): Add randomness: count=442 entropy=435
D/wpa_supplicant( 1172): Add randomness: count=443 entropy=436
D/wpa_supplicant( 1172): Add randomness: count=444 entropy=437
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=445 entropy=438
D/wpa_supplicant( 1172): Add randomness: count=446 entropy=439
D/wpa_supplicant( 1172): Add randomness: count=447 entropy=440
D/wpa_supplicant( 1172): Add randomness: count=448 entropy=441
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,D/WirelessDisplayService(  907): getDiscoveryDongleList
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (490) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000001065284815
,I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000001065284853
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000001065284863
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=14
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000001065284842
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ####
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1065284815, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 1065284853, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 1065284863, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -59, frequency: 2412, timestamp: 1065284842, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults,
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=449 entropy=442
D/wpa_supplicant( 1172): Add randomness: count=450 entropy=443
D/wpa_supplicant( 1172): Add randomness: count=451 entropy=444
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=452 entropy=445
D/wpa_supplicant( 1172): Add randomness: count=453 entropy=446
D/wpa_supplicant( 1172): Add randomness: count=454 entropy=447
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
,D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (490) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45,
I/wpa_supplicant( 1172): tsf=0000001083670678
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000001083670705
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000001083670715
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos,
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=14
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000001065284842
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1083670678, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 1083670705, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 1083670715, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -59, frequency: 2412, timestamp: 1065284842, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42691768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42691768): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=455 entropy=448
D/wpa_supplicant( 1172): Add randomness: count=456 entropy=449
D/wpa_supplicant( 1172): Add randomness: count=457 entropy=450
D/wpa_supplicant( 1172): Add randomness: count=458 entropy=451
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
D/wpa_supplicant( 1172): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=459 entropy=452
D/wpa_supplicant( 1172): Add randomness: count=460 entropy=453
D/wpa_supplicant( 1172): Add randomness: count=461 entropy=454
D/wpa_supplicant( 1172): Add randomness: count=462 entropy=455
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (490) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000001101935087
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000001101935126
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000001101935136
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=14
,I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000001101935114
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1101935087, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 1101935126, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 1101935136, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -59, frequency: 2412, timestamp: 1101935114, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000),
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-71
D/wpa_supplicant( 1172): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=463 entropy=456
D/wpa_supplicant( 1172): Add randomness: count=464 entropy=457
D/wpa_supplicant( 1172): Add randomness: count=465 entropy=458
D/wpa_supplicant( 1172): Add randomness: count=466 entropy=459
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-71
D/wpa_supplicant( 1172): BSS: last_scan_res_,used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=467 entropy=460
D/wpa_supplicant( 1172): Add randomness: count=468 entropy=461
D/wpa_supplicant( 1172): Add randomness: count=469 entropy=462
D/wpa_supplicant( 1172): Add randomness: count=470 entropy=463
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (490) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000001120311427
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000001120311465
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-71
I/wpa_supplicant( 1172): tsf=0000001120311475
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=14
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000001120311454
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1120311427, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 1120311465, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -71, frequency: 2427, timestamp: 1120311475, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -59, frequency: 2412, timestamp: 1120311454, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList,
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-71], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(427413b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423a7698: PendingIntentRecord{42113770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1120683, Int=0,
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(427413b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] 8c:04:ff:b9:af:25 freq=2462 level=-90
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=471 entropy=464
D/wpa_supplicant( 1172): Add randomness: count=472 entropy=465
D/wpa_supplicant( 1172): Add randomness: count=473 entropy=466
D/wpa_supplicant( 1172): Add randomness: count=474 entropy=467
D/wpa_supplicant( 1172): Add randomness: count=475 entropy=468
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 4: 8c:04:ff:b9:af:25 ssid='SALVADOR' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa,_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] 8c:04:ff:b9:af:25 freq=2462 level=-90
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=476 entropy=469
D/wpa_supplicant( 1172): Add randomness: count=477 entropy=470
D/wpa_supplicant( 1172): Add randomness: count=478 entropy=471
D/wpa_supplicant( 1172): Add randomness: count=479 entropy=472
D/wpa_supplicant( 1172): Add randomness: count=480 entropy=473
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (631) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000001138585211
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000001138585249
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000001138585258
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=14
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-55
I/wpa_supplicant( 1172): tsf=0000001138585238
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=15
I/wpa_supplicant( 1172): bssid=8c:04:ff:b9:af:25
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-90
I/wpa_supplicant( 1172): tsf=0000001138585268
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid,=SALVADOR
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1138585211, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 1138585249, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 1138585258, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1138585238, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: SALVADOR, BSSID: 8c:04:ff:b9:af:25, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 1138585268, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList,
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                         SALVADOR [8c:04:ff:b9:af:25], Rssi:  0 [-90], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42789468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42789468): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-70
I/wpa_supplicant( 1172): [NULL] 8c:04:ff:b9:af:25 freq=2462 level=-90
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=481 entropy=474
D/wpa_supplicant( 1172): Add randomness: count=482 entropy=475
D/wpa_supplicant( 1172): Add randomness: count=483 entropy=476
D/wpa_supplicant( 1172): Add randomness: count=484 entropy=477
D/wpa_supplicant( 1172): Add randomness: count=485 entropy=478
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 4: 8c:04:ff:b9:af:25 ssid='SALVADOR' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa,_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-70
I/wpa_supplicant( 1172): [NULL] 8c:04:ff:b9:af:25 freq=2462 level=-90
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=486 entropy=479
D/wpa_supplicant( 1172): Add randomness: count=487 entropy=480
D/wpa_supplicant( 1172): Add randomness: count=488 entropy=481
D/wpa_supplicant( 1172): Add randomness: count=489 entropy=482
D/wpa_supplicant( 1172): Add randomness: count=490 entropy=483
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
,D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (631) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000001156631891
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000001156631929
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-70
I/wpa_supplicant( 1172): tsf=0000001156631939
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=14
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-55
I/wpa_supplicant( 1172): tsf=0000001156631917
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=15
I/wpa_supplicant( 1172): bssid=8c:04:ff:b9:af:25
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-90
I/wpa_supplicant( 1172): tsf=0000001156631949
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=SALVADOR
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1156631891, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 1156631929, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -70, frequency: 2427, timestamp: 1156631939, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1156631917, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: SALVADOR, BSSID: 8c:04:ff:b9:af:25, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 1156631949, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-70], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                         SALVADOR [8c:04:ff:b9:af:25], Rssi:  0 [-90], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] 8c:04:ff:b9:af:25 freq=2462 level=-90
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=491 entropy=484
D/wpa_supplicant( 1172): Add randomness: count=492 entropy=485
D/wpa_supplicant( 1172): Add randomness: count=493 entropy=486
D/wpa_supplicant( 1172): Add randomness: count=494 entropy=487
D/wpa_supplicant( 1172): Add randomness: count=495 entropy=488
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 4: 8c:04:ff:b9:af:25 ssid='SALVADOR' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x1411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa,_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] 8c:04:ff:b9:af:25 freq=2462 level=-90
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=496 entropy=489
D/wpa_supplicant( 1172): Add randomness: count=497 entropy=490
D/wpa_supplicant( 1172): Add randomness: count=498 entropy=491
D/wpa_supplicant( 1172): Add randomness: count=499 entropy=492
D/wpa_supplicant( 1172): Add randomness: count=500 entropy=493
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (631) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000001156631891
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000001175010612
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000001175010622
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=14
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-55
I/wpa_supplicant( 1172): tsf=0000001175010602
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=15
I/wpa_supplicant( 1172): bssid=8c:04:ff:b9:af:25
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-90
I/wpa_supplicant( 1172): tsf=0000001175010632
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid,=SALVADOR
I/wpa_supplicant( 1172): ####
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-3ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1156631891, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 1175010612, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 1175010622, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1175010602, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: SALVADOR, BSSID: 8c:04:ff:b9:af:25, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 1175010632, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                         SALVADOR [8c:04:ff:b9:af:25], Rssi:  0 [-90], Tx: 13, Freq: 10 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(4275f200): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423a7698: PendingIntentRecord{42113770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1180683, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4275f200): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=501 entropy=494
D/wpa_supplicant( 1172): Add randomness: count=502 entropy=495
D/wpa_supplicant( 1172): Add randomness: count=503 entropy=496
D/wpa_supplicant( 1172): Add randomness: count=504 entropy=497
D/wpa_supplicant( 1172): Add randomness: count=505 entropy=498
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 3: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45,
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=506 entropy=499
D/wpa_supplicant( 1172): Add randomness: count=507 entropy=500
D/wpa_supplicant( 1172): Add randomness: count=508 entropy=501
D/wpa_supplicant( 1172): Add randomness: count=509 entropy=502
D/wpa_supplicant( 1172): Add randomness: count=510 entropy=503
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (899) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000001193314690
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000001193314717
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000001193314727
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=14
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-55
I/wpa_supplicant( 1172): tsf=0000001175010602
,I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=15
I/wpa_supplicant( 1172): bssid=8c:04:ff:b9:af:25
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-90
I/wpa_supplicant( 1172): tsf=0000001175010632
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=SALVADOR
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=16
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-88
I/wpa_supplicant( 1172): tsf=0000001193314737
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=17
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-89
I/wpa_supplicant( 1172): tsf=0000001193314749
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1193314690, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 1193314717, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 1193314727, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 1175010602, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: SALVADOR, BSSID: 8c:04:ff:b9:af:25, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 1175010632, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiStateMachine(  907): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 1193314737, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 1193314749, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 7 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList,
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  4 [-88], Tx: 13, Freq:  6 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq:  6 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  69, AP:                         SALVADOR [8c:04:ff:b9:af:25], Rssi:  0 [-90], Tx: 13, Freq:  6 [2462], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (7) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=511 entropy=504
D/wpa_supplicant( 1172): Add randomness: count=512 entropy=505
D/wpa_supplicant( 1172): Add randomness: count=513 entropy=506
D/wpa_supplicant( 1172): Add randomness: count=514 entropy=507
D/wpa_supplicant( 1172): Add randomness: count=515 entropy=508
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 3: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45,
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=516 entropy=509
D/wpa_supplicant( 1172): Add randomness: count=517 entropy=510
D/wpa_supplicant( 1172): Add randomness: count=518 entropy=511
D/wpa_supplicant( 1172): Add randomness: count=519 entropy=512
D/wpa_supplicant( 1172): Add randomness: count=520 entropy=513
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (644) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000001211691822
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000001211691849
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000001211691859
I/wpa_supplican,t( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=16
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-88
I/wpa_supplicant( 1172): tsf=0000001211691869
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=17
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-89
I/wpa_supplicant( 1172): tsf=0000001211691878
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1211691822, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 1211691849, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 1211691859, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 1211691869, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 1211691878, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42931a98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42931a98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=521 entropy=514
D/wpa_supplicant( 1172): Add randomness: count=522 entropy=515
D/wpa_supplicant( 1172): Add randomness: count=523 entropy=516
D/wpa_supplicant( 1172): Add randomness: count=524 entropy=517
D/wpa_supplicant( 1172): Add randomness: count=525 entropy=518
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 3: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45,
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-72
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-89
D/wpa_supplicant( 1172): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=526 entropy=519
D/wpa_supplicant( 1172): Add randomness: count=527 entropy=520
D/wpa_supplicant( 1172): Add randomness: count=528 entropy=521
D/wpa_supplicant( 1172): Add randomness: count=529 entropy=522
D/wpa_supplicant( 1172): Add randomness: count=530 entropy=523
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (644) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000001229994641
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000001229994668
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-72
I/wpa_supplicant( 1172): tsf=0000001229994678
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=16
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-88
I/wpa_supplicant( 1172): tsf=0000001229994688
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=17
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-89
I/wpa_supplicant( 1172): tsf=0000001229994698
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_suppl,icant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1229994641, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 1229994668, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -72, frequency: 2427, timestamp: 1229994678, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 1229994688, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 1229994698, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-72], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/PMS     (  907): acquireWL(4285fb48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423a7698: PendingIntentRecord{42113770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1240683, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4285fb48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-76
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=531 entropy=524
D/wpa_supplicant( 1172): Add randomness: count=532 entropy=525
D/wpa_supplicant( 1172): Add randomness: count=533 entropy=526
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-76
D/wpa_supplicant( 1172): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=534 entropy=527
D/wpa_supplicant( 1172): Add randomness: count=535 entropy=528
D/wpa_supplicant( 1172): Add randomness: count=536 entropy=529
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelem,ent id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (644) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000001248054464
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000001248054491
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-76
I/wpa_supplicant( 1172): tsf=0000001248054502
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=16
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-88
I/wpa_supplicant( 1172): tsf=0000001229994688
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=17
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-89
I/wpa_supplicant( 1172): tsf=0000001229994698
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1248054464, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 1248054491, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -76, frequency: 2427, timestamp: 1248054502, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
D/WifiStateMachine(  907): 3: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 1229994688, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 1229994698, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  98, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq: 10 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-76], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
D/wpa_supplicant( 1172): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=537 entropy=530
D/wpa_supplicant( 1172): Add randomness: count=538 entropy=531
D/wpa_supplicant( 1172): Add randomness: count=539 entropy=532
D/wpa_supplicant( 1172): Add randomness: count=540 entropy=533
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
D/WifiStateMachine(  907): [MLHD] enter hand,leMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1172): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=541 entropy=534
D/wpa_supplicant( 1172): Add randomness: count=542 entropy=535
D/wpa_supplicant( 1172): Add randomness: count=543 entropy=536
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1172): Add randomness: count=544 entropy=537
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (490) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000001266430738
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS],
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000001266430775
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-73
I/wpa_supplicant( 1172): tsf=0000001266430786
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=18
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-58
I/wpa_supplicant( 1172): tsf=0000001266430764
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ####
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1266430738, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 1266430775, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2427, timestamp: 1266430786, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 1266430764, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42762c48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42762c48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-89
D/wpa_supplicant( 1172): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=545 entropy=538
D/wpa_supplicant( 1172): Add randomness: count=546 entropy=539
D/wpa_supplicant( 1172): Add randomness: count=547 entropy=540
D/wpa_supplicant( 1172): Add randomness: count=548 entropy=541
D/wpa_supplicant( 1172): Add randomness: count=549 entropy=542
D/wpa_supplicant( 1172): Add randomness: count=550 entropy=543
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 5: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan, results (6 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-73
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-89
D/wpa_supplicant( 1172): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=551 entropy=544
D/wpa_supplicant( 1172): Add randomness: count=552 entropy=545
D/wpa_supplicant( 1172): Add randomness: count=553 entropy=546
D/wpa_supplicant( 1172): Add randomness: count=554 entropy=547
D/wpa_supplicant( 1172): Add randomness: count=555 entropy=548
D/wpa_supplicant( 1172): Add randomness: count=556 entropy=549
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1172): reply (758) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000001266430738
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000001284714939
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-73
I/wpa_supplicant( 1172): tsf=0000001284714949,
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=18
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-58
I/wpa_supplicant( 1172): tsf=0000001284714928
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=19
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-88
I/wpa_supplicant( 1172): tsf=0000001284714969
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS],
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=20
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-89
I/wpa_supplicant( 1172): tsf=0000001284714959
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1266430738, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 1284714939, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -73, frequency: 2427, timestamp: 1284714949, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 1284714928, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 1284714969, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 1284714959, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 6 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  85, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi: 12 [-73], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1172): wpa_supplicant_scan enter
I/wpa_supplicant( 1172): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1172): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1172): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1172): nl80211: Event message available
,D/wpa_supplicant( 1172): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(42792ef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423a7698: PendingIntentRecord{42113770 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1300683, Int=0
,I/IntentController( 1116): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42792ef8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/wpa_supplicant( 1172): nl80211: Event message available
D/wpa_supplicant( 1172): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1172): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1172): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1172): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan results (6 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-75
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-89
D/wpa_supplicant( 1172): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=557 entropy=550
D/wpa_supplicant( 1172): Add randomness: count=558 entropy=551
D/wpa_supplicant( 1172): Add randomness: count=559 entropy=552
D/wpa_supplicant( 1172): Add randomness: count=560 entropy=553
D/wpa_supplicant( 1172): Add randomness: count=561 entropy=554
D/wpa_supplicant( 1172): Add randomness: count=562 entropy=555
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): Selecting BSS from priority group 1
I/wpa_supplicant( 1172): Recent assoc_freq = 2412 rssi = -59
D/wpa_supplicant( 1172): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 1: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1172): 2: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1172): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1172):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1172):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-59
I/wpa_supplicant( 1172): Start print parameters
I/wpa_supplicant( 1172): wpa_s->wpa_state is 9
I/wpa_supplicant( 1172): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1172): isConcurrentMode() is 0
I/wpa_supplicant( 1172): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1172): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1172): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1172): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1172): wpa_s->reassociate is 0
I/wpa_supplicant( 1172): wpa_s->is_screen_on 0
I/wpa_supplicant( 1172): wpa_s->ifname wlan0
I/wpa_supplicant( 1172): End print parameters
I/wpa_supplicant( 1172): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1172): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1172): 4: fc:94:e3:11:35:3a ssid='UPC0039325' wpa_ie_len=28 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1172): 5: fe:94:e3:11:35:3c ssid='UPC Wi-Free' wpa_ie_len=0 rsn_ie_len=24 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1172): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1172): nl80211: Received scan, results (6 BSSes)
D/wpa_supplicant( 1172): nl80211: Survey data missing
E/wpa_supplicant( 1172): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1172): Sorted scan results
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-45
I/wpa_supplicant( 1172): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1172): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-59
I/wpa_supplicant( 1172): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-75
I/wpa_supplicant( 1172): [NULL] fc:94:e3:11:35:3a freq=2462 level=-88
I/wpa_supplicant( 1172): [NULL] fe:94:e3:11:35:3c freq=2462 level=-89
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1172): BSS: last_scan_res_used=6/32 last_scan_full=0
D/wpa_supplicant( 1172): Add randomness: count=563 entropy=556
D/wpa_supplicant( 1172): Add randomness: count=564 entropy=557
D/wpa_supplicant( 1172): Add randomness: count=565 entropy=558
D/wpa_supplicant( 1172): Add randomness: count=566 entropy=559
D/wpa_supplicant( 1172): Add randomness: count=567 entropy=560
D/wpa_supplicant( 1172): Add randomness: count=568 entropy=561
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1172): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1172): wpa_supplicant_pick_network+
I/wpa_supplicant( 1172): clear disabled list - type=1
I/wpa_supplicant( 1172): No suitable network found
W/wpa_supplicant( 1172): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1172): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1172): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1172): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1172): reply (758) for get BSS: id=0
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1172): freq=5220
I/wpa_supplicant( 1172): level=-45
I/wpa_supplicant( 1172): tsf=0000001303010658
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG7005g
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=2
I/wpa_supplicant( 1172): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-59
I/wpa_supplicant( 1172): tsf=0000001303010694
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1172): ssid=NG700
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=3
I/wpa_supplicant( 1172): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1172): freq=2427
I/wpa_supplicant( 1172): level=-75,
I/wpa_supplicant( 1172): tsf=0000001303010703
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=Gonzos
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=18
I/wpa_supplicant( 1172): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1172): freq=2412
I/wpa_supplicant( 1172): level=-58
I/wpa_supplicant( 1172): tsf=0000001303010683
I/wpa_supplicant( 1172): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1172): ssid=01ABC
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=19
I/wpa_supplicant( 1172): bssid=fc:94:e3:11:35:3a
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-88
I/wpa_supplicant( 1172): tsf=0000001303010723
I/wpa_supplicant( 1172): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC0039325
I/wpa_supplicant( 1172): ====
I/wpa_supplicant( 1172): id=20
I/wpa_supplicant( 1172): bssid=fe:94:e3:11:35:3c
I/wpa_supplicant( 1172): freq=2462
I/wpa_supplicant( 1172): level=-89
I/wpa_supplicant( 1172): tsf=0000001303010713
I/wpa_supplicant( 1172): flags=[WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1172): ssid=UPC Wi-Free
I/wpa_supplicant( 1172): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -45, frequency: 5220, timestamp: 1303010658, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -59, frequency: 2412, timestamp: 1303010694, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -75, frequency: 2427, timestamp: 1303010703, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -59, 0
,D/WifiStateMachine(  907): 3: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -58, frequency: 2412, timestamp: 1303010683, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC0039325, BSSID: fc:94:e3:11:35:3a, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2462, timestamp: 1303010723, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC Wi-Free, BSSID: fe:94:e3:11:35:3c, capabilities: [WPA2-EAP-CCMP+TKIP][ESS], level: -89, frequency: 2462, timestamp: 1303010713, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 6 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-59], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-45], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-58], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  81, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-75], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0039325 [fc:94:e3:11:35:3a], Rssi:  4 [-88], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                      UPC Wi-Free [fe:94:e3:11:35:3c], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (6) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4421): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4421): ====startRecUseTime====
D/htc.customization.log.level( 4421):  is 
W/CustomizationLogLevel( 4421): Level value is invalid, use default level 2
D/CustomizationManager( 4421):  Read ACC file spent 0.068 (s)
D/CIDMapFileReader( 4421): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4421): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4421): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4421): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4421): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4421): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4421): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4421): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4421): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4421): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4421): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4421): Parsing tag category name = system
I/CustomizationCIDLoader( 4421): Parsing tag category name = application
I/CustomizationCIDLoader( 4421): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4421): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4421): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4421): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4421): Parsing tag category name = Settings
D/CustomizationManager( 4421):  Read CID file spent 0.112 (s)
D/CustomizationManager( 4421):  All configurations done spent 0.112 (s)
W/HtcNativeFlag( 4421): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4421): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4421): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4421): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=4421, uid=2000 user=0
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10189 user=-1: uninstall pkg
W/PackageSettings(  907): Skipping PackageSetting{4224d8b0 com.test.thalitest/10189} due to missing metadata
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10189 user=0: pkg removed
W/PackageManager(  907): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  907): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/acms    ( 1915): Unregistering com.test.thalitest
E/acms    ( 1915): Could not unregister removed application com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.test.thalitest
D/DotMatrix( 1589): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1589): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1589): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
D/PMS     (  907): acquireWL(42932198): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1466 10028 null
W/GeofencerStateMachine( 1466): Ignoring removeGeofence because network location is disabled.
W/AccTypeManager( 1333): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1333): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  907): releaseWL(42932198): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/VoicemailCleanupService( 1299): Cleaning up data for package: com.test.thalitest
W/SystemReader( 1255): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
D/AccTypeManager( 1333): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
D/PackageBroadcastService( 2241): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
E/ExternalAccountType( 1333): Unsupported attribute readOnly
I/ActivityManager(  907): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4436 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
D/PhoneApp( 1245): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/MultiDex( 4436): install
I/MultiDex( 4436): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4436): loading existing secondary dex files
I/PeopleContactsSync( 2241): CP2 sync disabled
I/MultiDex( 4436): load found 1 secondary dex files
I/ActivityManager(  907): Delaying start of: ServiceRecord{4259a250 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/MultiDex( 4436): install done
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2241, uid=10028, userID:0
D/PMS     (  907): acquireWL(423a3c30): PARTIAL_WAKE_LOCK  Icing 0x1 2241 10028 null
I/Icing   ( 2241): doRemovePackageData com.test.thalitest
I/ProviderInstaller( 4436): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  907): releaseWL(423a3c30): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  907): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4457 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ActivityManager(  907): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
E/SQLiteDatabase( 2241): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 2241): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2241): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2241): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2241): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2241): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2241): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2241): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2241): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2241): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2241): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2241): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2241): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2241): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2241): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2241): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 2241): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 2241): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 2241): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 2241): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 2241): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2241): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2241): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2241): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ClearPendingStateOp( 2241): Runtime exception while performing operation
E/ClearPendingStateOp( 2241): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 2241): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 2241): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 2241): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 2241): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 2241): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 2241): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 2241): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 2241): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 2241): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 2241): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 2241): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 2241): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 2241): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 2241): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 2241): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 2241): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 2241): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 2241): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 2241): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 2241): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 2241): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 2241): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/ClearPendingStateOp( 2241): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 2241): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 2241): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 2241): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 2241): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 2241): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 2241): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 2241): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 2241): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 2241): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 2241): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 2241): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 2241): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 2241): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 2241): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 2241): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 2241): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 2241): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 2241): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 2241): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 2241): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 2241): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 2241): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 2241): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 4457): install
I/MultiDex( 4457): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4457): loading existing secondary dex files
I/MultiDex( 4457): load found 1 secondary dex files
I/MultiDex( 4457): install done
E/DropBoxManagerService(  907): Can't write: system_app_wtf
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop136.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
I/ProviderInstaller( 4457): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  907): Resuming delayed broadcast
E/SharedPreferencesImpl( 1208): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
I/[PluginManager]RegisterService( 1400): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
E/SQLiteLog( 1400): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1400): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5ca2da78
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
W/[PluginManager]RegisterService( 1400): provider may killed!
W/[PluginManager]RegisterService( 1400): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1400): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1400): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1400): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1400): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1400): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1400): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1400): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1400): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1400): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1400): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1400): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1400): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1400): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1400): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 1400): handle notify Blinkfeed plugin client changed
E/SQLiteDatabase( 4436): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4436): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4436): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4436): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4436): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4436): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4436): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4436): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4436): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4436): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4436): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4436): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4436): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4436): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4436): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4436): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4436): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4436): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4436): threadid=12: thread exiting with uncaught exception (group=0x416f9e30)
E/AndroidRuntime( 4436): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4436): Process: com.google.android.gms.drive, PID: 4436
E/AndroidRuntime( 4436): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4436): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4436): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4436): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4436): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4436): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4436): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4436): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4436): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4436): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4436): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4436): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4436): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4436): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4436): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4436): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4436): 	at ctn.run(SourceFile:985)
E/ActivityManager(  907): App crashed! Process: com.google.android.gms.drive
I/ActivityManager(  907): Resuming delayed broadcast
D/Process ( 4436): killProcess, pid=4436
D/Process ( 4436): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop137.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
D/Prism.PackageStateRece_( 1273): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2875): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
E/SQLiteLog( 2875): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2875): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63602088
W/dalvikvm( 2875): threadid=14: thread exiting with uncaught exception (group=0x416f9e30)
E/AndroidRuntime( 2875): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2875): Process: com.google.android.googlequicksearchbox:search, PID: 2875
E/AndroidRuntime( 2875): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2875): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2875): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2875): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2875): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2875): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2875): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2875): 	at cid.d(PG:186)
E/AndroidRuntime( 2875): 	at clo.g(PG:594)
E/AndroidRuntime( 2875): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2875): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2875): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2875): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2875): 	at clr.tL(PG:827)
E/AndroidRuntime( 2875): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2875): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2875): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2875): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2875): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2875): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  907): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2875): killProcess, pid=2875
D/Process ( 2875): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop138.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
W/PackageManager(  907): Unable to load service info ResolveInfo{42790718 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  907): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  907): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  907): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  907): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  907): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  907): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  907): Recipient 4436
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.android.gms.drive (pid 4436) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
I/ActivityManager(  907): Resuming delayed broadcast
W/BroadcastQueue(  907): Exception when sending broadcast to ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.GelStubAppWatcher}
W/BroadcastQueue(  907): android.os.TransactionTooLargeException
W/BroadcastQueue(  907): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue(  907): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:966)
W/BroadcastQueue(  907): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:246)
W/BroadcastQueue(  907): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:974)
W/BroadcastQueue(  907): 	at com.android.server.am.BroadcastQueue.backgroundServicesFinishedLocked(BroadcastQueue.java:442)
W/BroadcastQueue(  907): 	at com.android.server.am.ActivityManagerService.backgroundServicesFinishedLocked(ActivityManagerService.java:15042)
W/BroadcastQueue(  907): 	at com.android.server.am.ActiveServices$ServiceMap.rescheduleDelayedStarts(ActiveServices.java:237)
W/BroadcastQueue(  907): 	at com.android.server.am.ActiveServices$ServiceMap.ensureNotStartingBackground(ActiveServices.java:191)
W/BroadcastQueue(  907): 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1711)
W/BroadcastQueue(  907): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2185)
W/BroadcastQueue(  907): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:13536)
W/BroadcastQueue(  907): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:3943)
W/BroadcastQueue(  907): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:4128)
W/BroadcastQueue(  907): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1146)
W/BroadcastQueue(  907): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/BroadcastQueue(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
I/ActivityManager(  907): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/.GelStubAppWatcher: pid=4481 uid=10085 gids={50085, 3003, 5012, 3001, 1028, 3002, 1015}
E/SQLiteDatabase( 2241): Failed to open database '/data/data/com.google.android.gms/databases/games_3a3529a.db'.
E/SQLiteDatabase( 2241): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2241): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2241): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2241): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2241): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2241): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2241): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2241): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2241): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2241): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2241): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2241): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2241): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2241): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2241): 	at bxi.query(SourceFile:181)
E/SQLiteDatabase( 2241): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 2241): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 2241): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 2241): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 2241): 	at dtr.a(SourceFile:81)
E/SQLiteDatabase( 2241): 	at dug.g(SourceFile:3454)
E/SQLiteDatabase( 2241): 	at dug.d(SourceFile:3122)
E/SQLiteDatabase( 2241): 	at ezc.a(SourceFile:26)
E/SQLiteDatabase( 2241): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteDatabase( 2241): 	at bpu.run(SourceFile:101)
E/SQLiteDatabase( 2241): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2241): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2241): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteOpenHelper( 2241): Couldn't open games_3a3529a.db for writing (will try read-only):
E/SQLiteOpenHelper( 2241): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2241): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2241): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2241): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2241): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2241): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2241): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2241): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2241): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2241): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2241): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2241): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2241): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2241): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2241): 	at bxi.query(SourceFile:181)
E/SQLiteOpenHelper( 2241): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 2241): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 2241): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 2241): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 2241): 	at dtr.a(SourceFile:81)
E/SQLiteOpenHelper( 2241): 	at dug.g(SourceFile:3454)
E/SQLiteOpenHelper( 2241): 	at dug.d(SourceFile:3122)
E/SQLiteOpenHelper( 2241): 	at ezc.a(SourceFile:26)
E/SQLiteOpenHelper( 2241): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteOpenHelper( 2241): 	at bpu.run(SourceFile:101)
E/SQLiteOpenHelper( 2241): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 2241): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 2241): 	at java.lang.Thread.run(Thread.java:864)
W/SQLiteOpenHelper( 2241): Opened games_3a3529a.db in read-only mode
W/dalvikvm( 2241): threadid=10: thread exiting with uncaught exception (group=0x416f9e30)
E/ActivityManager(  907): App crashed! Process: com.google.android.gms
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
D/MediaRouterService(  907): Client com.google.android.googlequicksearchbox (pid 2875): Died!
E/AndroidRuntime( 2241): FATAL EXCEPTION: GamesProviderWorker
E/AndroidRuntime( 2241): Process: com.google.android.gms, PID: 2241
E/AndroidRuntime( 2241): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2241): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 2241): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 2241): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 2241): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 2241): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/AndroidRuntime( 2241): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
E/AndroidRuntime( 2241): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
E/AndroidRuntime( 2241): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 2241): 	at eoj.a(SourceFile:136)
E/AndroidRuntime( 2241): 	at eoj.<init>(SourceFile:65)
E/AndroidRuntime( 2241): 	at eob.b(SourceFile:105)
E/AndroidRuntime( 2241): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1598)
E/AndroidRuntime( 2241): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1579)
E/AndroidRuntime( 2241): 	at elo.handleMessage(SourceFile:1523)
E/AndroidRuntime( 2241): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2241): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2241): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process (  907): killProcessQuiet, pid=2241
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.handleAppCrashLocked:10375 
W/ActivityManager(  907): Process com.google.android.gms has crashed too many times: killing!
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
I/ActivityManager(  907): Killing 2241:com.google.android.gms/u0a28 (adj 6): crash
I/IcingCorporaProvider( 4481): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4496 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start
I/ActivityManager(  907): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4510 uid=10031 gids={50031, 3003, 5012}
D/LocationManagerService(  907): getProviders()=[passive]
W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
I/ActivityManager(  907): Start proc com.google.android.gms for service com.google.android.gms/.icing.service.IndexService: pid=4527 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/Process (  907): killProcessQuiet, pid=3938
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  907): Killing 3938:com.htc.task/u0a70 (adj 15): empty #17
I/MultiDex( 4527): install
I/MultiDex( 4527): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4527): loading existing secondary dex files
I/MultiDex( 4527): load found 1 secondary dex files
I/MultiDex( 4527): install done
I/ProviderInstaller( 4527): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  907): Recipient 3938
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  907): acquireWL(42765f30): PARTIAL_WAKE_LOCK  Icing 0x1 4527 10028 null
E/SQLiteDatabase( 4527): Failed to open database '/data/data/com.google.android.gms/databases/plus.db'.
E/SQLiteDatabase( 4527): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4527): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4527): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4527): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4527): 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:310)
E/SQLiteDatabase( 4527): 	at ijp.a(SourceFile:146)
E/SQLiteDatabase( 4527): 	at ijp.doInBackground(SourceFile:143)
E/SQLiteDatabase( 4527): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4527): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4527): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4527): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4527): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4527): 	at java.lang.Thread.run(Thread.java:864)
W/dalvikvm( 4527): threadid=14: thread exiting with uncaught exception (group=0x416f9e30)
I/Icing   ( 4527): Storage manager: low false usage 1.49MB avail 7.46GB capacity 7.85GB
E/ActivityManager(  907): App crashed! Process: com.google.android.gms
D/Process ( 4527): killProcess, pid=4527
D/Process ( 4527): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/AndroidRuntime( 4527): FATAL EXCEPTION: AsyncTask #1
E/AndroidRuntime( 4527): Process: com.google.android.gms, PID: 4527
E/AndroidRuntime( 4527): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime( 4527): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime( 4527): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime( 4527): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime( 4527): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime( 4527): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime( 4527): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 4527): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 4527): 	at java.lang.Thread.run(Thread.java:864)
E/AndroidRuntime( 4527): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4527): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4527): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4527): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4527): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4527): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4527): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4527): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4527): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4527): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4527): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4527): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4527): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4527): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4527): 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:310)
E/AndroidRuntime( 4527): 	at ijp.a(SourceFile:146)
E/AndroidRuntime( 4527): 	at ijp.doInBackground(SourceFile:143)
E/AndroidRuntime( 4527): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime( 4527): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime( 4527): 	... 4 more
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4527
I/ActivityManager(  907): Process com.google.android.gms (pid 4527) has died.
D/PMS     (  907): handleWLDeath(42765f30): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10998ms
E/SQLiteDatabase( 4496): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4496): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4496): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4496): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4496): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4496): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4496): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4496): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4496): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4496): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4496): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4496): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4496): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4496): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4496): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4496): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4496): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4496): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4496): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4496): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4496): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4496): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4496): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4496): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4496): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4496): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4496): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4496): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4496): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4496): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4496): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4496): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4496): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4496): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4496): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4496): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4496): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4496): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4496): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4496): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4496): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4496): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4496): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4496): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4496): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4496): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4496): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4496): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4496): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4496): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4496): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4496): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4496): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4496): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4496): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4496): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4496): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4496): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4496): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4496): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4496): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4496): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4496): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4496): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4496): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4496): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4496): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4496): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4496): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4496): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4496): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4496): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4496): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4496): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4496): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4496): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4496): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4496): threadid=11: thread exiting with uncaught exception (group=0x416f9e30)
E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4496): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4496): Process: com.google.android.apps.docs, PID: 4496
E/AndroidRuntime( 4496): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4496): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4496): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4496): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4496): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4496): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4496): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4496): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4496): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase,.java:829)
E/AndroidRuntime( 4496): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4496): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4496): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4496): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4496): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4496): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4496): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4496): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4496): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4496): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
E/SQLiteDatabase( 4496): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4496): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4496): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4496): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4496): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4496): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4496): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4496): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4496): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4496): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4496): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4496): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4496): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4496): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4496): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4496): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4496): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4496): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4496): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4496): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4496): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4496): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4496): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4496): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4496): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4496): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4496): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4496): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4496): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4496): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4496): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4496): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4496): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4496): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4496): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4496): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4496): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4496): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4496): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4496): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4496): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4496): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4496): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4496): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4496): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4496): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4496): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4496): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4496): Opened ClientFlag.db in read-only mode
D/Process ( 4496): killProcess, pid=4496

```
