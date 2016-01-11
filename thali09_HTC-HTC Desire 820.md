#### Test 5497026186051be_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/PMS     (  907): Going to sleep due to screen timeout...
--------- beginning of /dev/log/main
D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42231aa8
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42231aa8, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4204b138
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@426b1bb0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  907): mWirelessDisplayManager is null
W/BatSI   (  907): Couldn't get kernel wake lock stats
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
V/LightsService(  907): setLight #0: color=#0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:152, mTXpacketCount:152, avgLinkspeed:72,mAvgTxRate72
D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 343ms
W/PnPMgr  (  356): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@435d8190)
D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
D/PMS     (  907): OOBE c monitor 11
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
D/PMN     (  907): wakingUp
D/NfcService( 1256): ScreenObserver: OFF
D/NfcService( 1256): applyRouting - 0
V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
I/InputMethodManagerService(  907): Disable input method client, pid=1274
I/WindowManager(  907): No lock screen! windowToken=null
D/NfcService( 1256): applyRouting -2
I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
W/XT9_C   ( 1210): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1210): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMN     (  907): onScreenOn
D/PMS     (  907): acquireWL(43756980): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/PMS     (  907): releaseWL(43756980): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMS     (  907): acquireWL(43583b78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(43583b78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/NfcService( 1256): applyRouting - 0
D/MtpService( 2690): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/MtpService( 2690): [MTP][onReceive]-
D/NfcService( 1256): applyRouting -2
D/PowerUI ( 1115): closing low battery warning: level=99
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
D/PMS     (  907): acquireWL(437514d0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
D/PMS     (  907): releaseWL(437514d0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/AutoSetting( 1330): receiver - intent: android.intent.action.USER_PRESENT
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
D/AutoSetting( 1330): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3712): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3712): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3712): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3712): Cust_ConnectToPC   : spcsc>false
D/        ( 3712): Cust_ConnectToPC   : IPT>true
D/        ( 3712): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3712): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3712): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3712): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/SmartNS_NSReceiver( 3712): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19834 delay=15s
V/NotificationService(  907): batLight: plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c80000
D/qdlights(  907): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
I/PSReceiver( 3712): onReceive:android.intent.action.USER_PRESENT
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): SET_SCREEN_ON:On
I/wpa_supplicant( 1180): htc_wext_set_keepalive +
I/wpa_supplicant( 1180): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1180): getPrivFuncNum +	
I/wpa_supplicant( 1180): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1180): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1180): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING - ret = 0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/WifiNative-wlan0(  907):    returned true
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/ClockThread( 1115): stop update clock
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023890
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024047
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024215
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024219
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024223
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025539
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028434
W/ContextImpl( 3712): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3712): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3712): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3712):  defaultType:0
V/NotificationService(  907): batLight: plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c80000
D/qdlights(  907): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  373): ParamSet string: screen_state=on
I/BatteryController( 1115): status:2 level:99 unsupport:false plugged:true
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
D/NetworkPolicy(  907): updateScreenOn: false
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4351 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  907): acquireWL(436a40a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(436a40a8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(4267f1b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1759): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1759): onScreenOn: 1452511743453
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1759): onScreenOn: 1452511743453
I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4204b138
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4204b138, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@426b1bb0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMS     (  907): releaseWL(4267f1b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMN     (  907): goingToSleep
D/PMS     (  907): acquireWL(441064c8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
I/FeedHostManager( 1274): [onPause]
I/FeedProviderManager( 1274): onPause
I/FeedHostManager( 1274): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42166500
I/SocialFeedProvider( 1274): +onPause
I/SocialFeedProvider( 1274): -onPause
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=19834 mDataStallAlarmIntent=PendingIntent{44104870: PendingIntentRecord{42379a00 android broadcastIntent}}
D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
W/ContextImpl( 4351): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023890
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024047
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024215
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024219
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024223
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025539
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028434
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): SET_SCREEN_ON:Off
I/wpa_supplicant( 1180): htc_wext_set_keepalive +
I/wpa_supplicant( 1180): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1180): getPrivFuncNum +	
I/wpa_supplicant( 1180): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1180): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1180): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1180): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1180): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  907):    returned true
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(4317e170): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
D/PMS     (  907): releaseWL(441064c8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
V/SRS_Proc(  373): ParamSet string: screen_state=off
D/SmartSyncUtils( 4351): isEpsOn(), nState = 0
D/NetworkPolicy(  907): updateScreenOn: false
D/PMS     (  907): acquireWL(4338a0d0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4351 1000 null
D/ContactMessageStore( 1241): start background delete task...
D/ContactMessageStore( 1241): size: 0 , 0
D/ContactMessageStore( 1241): Background delete complete
D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(4317e170): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/SmartSyncUtils( 4351): getMobilePolicyEnabled, result = true
D/PMS     (  907): releaseWL(4338a0d0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
E/cutils-trace( 4349): Error opening trace file: No such file or directory (2)
D/Process (  907): killProcessQuiet, pid=3767
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3767:com.google.android.music:main/u0a154 (adj 15): empty #17
W/ContextImpl( 4351): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  907): Recipient 3767
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/SmartSyncUtils( 4351): isEpsOn(), nState = 0
D/SmartSyncUtils( 4351): getMobilePolicyEnabled, result = true
D/SmartSyncUtils( 4351): isEpsOn(), nState = 0
D/MediaRouterService(  907): Client com.google.android.music (pid 3767): Died!
D/AutoSetting( 1330): service - mHandler: cancel location update
D/AutoSetting( 1330): service -           changes count: 0
D/WifiService(  907): New client listening to asynchronous messages
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426b1bb0
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426b1bb0, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@426b1bb0, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@426b1bb0
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1590): [EventService] getTotalRam: 1873 Mb
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@426b2110 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@426b2110 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
D/PMS     (  907): acquireWL(43fdedb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(43fdedb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(440e8d98): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(440e8d98): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1759): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1759): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1759): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1759): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1759): onScreenOff
D/CustomizationManager( 4349): ====startRecUseTime====
D/htc.customization.log.level( 4349):  is 
W/CustomizationLogLevel( 4349): Level value is invalid, use default level 2
D/CustomizationManager( 4349):  Read ACC file spent 0.120 (s)
D/CIDMapFileReader( 4349): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4349): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4349): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4349): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4349): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4349): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4349): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4349): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4349): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4349): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4349): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4349): Parsing tag category name = system
I/CustomizationCIDLoader( 4349): Parsing tag category name = application
I/CustomizationCIDLoader( 4349): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4349): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4349): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4349): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4349): Parsing tag category name = Settings
D/CustomizationManager( 4349):  Read CID file spent 0.179 (s)
D/CustomizationManager( 4349):  All configurations done spent 0.179 (s)
W/HtcNativeFlag( 4349): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4349): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4349): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4349): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
D/PMS     (  907): acquireHCC(43623d50): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(43670f58): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4349
W/asset   (  907): Copying FileAsset 0x6cdbbe78 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1129864448
I/ActivityManager(  907): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4384 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
W/asset   ( 4384): Copying FileAsset 0x5c72d428 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/TrimMemoryManager( 1274): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 4384): Binding Chromium to main looper Looper (main, tid 1) {41aaa768}
I/LibraryLoader( 4384): Expected native library version number "",actual native library version number ""
I/chromium( 4384): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4384): Initializing chromium process, renderers=0
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@423cfd08:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  907): acquireWL(43bdb2e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  907): acquireWL(43fc89e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
D/PMS     (  907): releaseWL(43bdb2e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 4384): 1101791712: getState(). Returning 12
I/Adreno-EGL( 4384): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4384): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4384): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4384): Local Branch: 
I/Adreno-EGL( 4384): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4384): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4384):                  aa63bbd948f41d15fc72f585e
W/chromium( 4384): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4384): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4384): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4384): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4384): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4384): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4384): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4384): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4384): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4384): CordovaWebView is running on device made by: HTC
,W/AwContents( 4384): nativeOnDraw failed; clearing to background color.
,W/ResourceType( 4384): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 4384): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41af1890, mServedView=org.apache.cordova.engine.SystemWebView{41ab74f8 VFEDH.C. .F...... 0,0-720,1134 #64}
,W/IInputConnectionWrapper( 4384): reportFullscreenMode on inactive InputConnection
I/InputMethodManagerService(  907): Disable input method client, pid=1274
,I/ActivityManager(  907): Displayed com.test.thalitest/.MainActivity: +262ms (total +299ms)
,D/JsMessageQueue( 4384): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 4384): JniHelper::setJavaVM(0x4157c048), pthread_self() = 1662266240
,D/JX-Cordova( 4384): jxcore cordova android initializing
,I/dalvikvm-heap( 4384): Grow heap (frag case) to 11.592MB for 95956-byte allocation
,I/dalvikvm-heap( 4384): Grow heap (frag case) to 11.671MB for 143930-byte allocation
,I/dalvikvm-heap( 4384): Grow heap (frag case) to 11.791MB for 215890-byte allocation
,I/dalvikvm-heap( 4384): Grow heap (frag case) to 11.966MB for 323830-byte allocation
,I/dalvikvm-heap( 4384): Grow heap (frag case) to 12.225MB for 485740-byte allocation
,I/dalvikvm-heap( 4384): Grow heap (frag case) to 13.233MB for 1092904-byte allocation
,I/dalvikvm-heap( 4384): Grow heap (frag case) to 14.130MB for 1639352-byte allocation
,I/dalvikvm-heap( 4384): Grow heap (frag case) to 15.462MB for 2459024-byte allocation
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
D/PMS     (  907): releaseHCC(43623d50): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  907): releaseHCC(43670f58): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/dalvikvm-heap( 4384): Grow heap (frag case) to 17.574MB for 3688532-byte allocation
,W/jxcore-log( 4384): Initializing JXcore engine
,W/jxcore-log( 4384): JXcore engine is ready
,W/jxcore-log( 4384): Starting JXcore engine
,W/jxcore-log( 4384): Platform android
W/jxcore-log( 4384): 
,W/jxcore-log( 4384): Process ARCH arm
W/jxcore-log( 4384): 
,D/PMS     (  907): releaseWL(43fc89e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/jxcore-log( 4384): JXcore Cordova bridge is ready!
I/jxcore-log( 4384): 
,W/jxcore-log( 4384): JXcore engine is started
,I/chromium( 4384): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4384): Toggling radios to true
I/jxcore-log( 4384): 
,D/BluetoothAdapter( 4384): enable(): BT is already enabled..!
,D/WifiManager( 4384): setWifiEnabled: Base Package Name=com.test.thalitest, uid=10389
W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 2
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 918
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:105)
W/System.err(  907): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  907): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  907): 
W/Settings:Agent(  907): << traceCallingStack(): 1(ms)
D/WifiManager( 4384): disconnect: Base Package Name=com.test.thalitest, uid=10389
D/WifiService(  907): setWifiEnabled: true pid=4384, uid=10389
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  907): isSprintWifiRestricted(): false
I/WifiService(  907): isMdmWifiRestricted(): false
D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/WifiNative-wlan0(  907): doBoolean: DISCONNECT
D/WifiManager( 4384): reconnect: Base Package Name=com.test.thalitest, uid=10389
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DISCONNECT"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): TDLS: Tear down peers
I/wpa_supplicant( 1180): wpa_driver_nl80211_disconnect(reason_code=3)
I/jxcore-log( 4384): Radios toggled
I/jxcore-log( 4384): 
,I/jxcore-log( 4384): My device name is: HTC-HTC Desire 820,
I/jxcore-log( 4384): 
D/WifiService(  907): New client listening to asynchronous messages
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 48
,I/wpa_supplicant( 1180): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1180): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,I/wpa_supplicant( 1180): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1180): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1180): send_and_recv error -67 - cmd 12,
,D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/Tethering(  907): [isWifi] getHotspotEnabled: false
E/wpa_supplicant( 1180): send_and_recv error -67 - cmd 12
D/HTCRequest(  907): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
,D/HTCRequest(  907): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1180): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1180): send_and_recv error -67 - cmd 12
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7c8dbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1180):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1180): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
,D/wpa_supplicant( 1180): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING (0)+
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1180): EAPOL: External notification - portEnabled=0
,D/HTCRequest(  907): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1180): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: SUPP_BE entering state INITIALIZE
,D/HTCRequest(  907): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - portValid=0
,D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  907): WifiMonitor:getReasonFromEventString() 3
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - EAP success=0
,D/HTCRequest(  907): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1180): State: DISCONNECTED -> DISCONNECTED
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 1180): netlink: Operstate: linkmode=-1, operstate=5
D/Tethering(  907): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1180): EAPOL: External notification - portEnabled=0
,D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - portValid=0
,D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  907): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/wpa_supplicant( 1180): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1180): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1180): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1180): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
,D/wpa_supplicant( 1180): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1180): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1180): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1180): nl80211: Ignore disconnect event triggered during reassociation
D/WifiNative-wlan0(  907):    returned true
D/WifiPerfLock(  907): release()
D/WifiStateMachine(  907): PerfLock released for exiting ConnectedState
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): Power_Mode_Type mode = 0
I/wpa_supplicant( 1180): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 61
D/ConnectivityService(  907): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  907): acquireWL(43c88a78): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 907 1000 null
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
,D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023890
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024047
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024215
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024219
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024223
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025539
,D/DhcpStateMachine(  907): [RunningState] Stop DHCP
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiNative-wlan0(  907): doBoolean: RECONNECT
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 RECONNECT"
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=19835 mDataStallAlarmIntent=null
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): Fast associate: Old scan results
I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 33
,I/wpa_supplicant( 1180): Scan req (ret=0) - timeout 30 secs
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): Enter handleNetworkDisconnect
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028434
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): Power_Mode_Type mode = 0
I/wpa_supplicant( 1180): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 61
D/UsbnetStateTracker(  907): isAvailable+-
D/UsbnetStateTracker(  907): reconnect
D/UsbnetStateTracker(  907): isAvailable+-
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  907): Provision feature enable=false
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  907): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  907): default: reconnect()
D/MDST    (  907): default: setTeardownRequested(false)
D/MDST    (  907): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): Exit handleNetworkDisconnect
D/WifiNative-wlan0(  907): doBoolean: SET pno 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): CTRL_IFACE SET 'pno'='1'
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  907): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  907): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 3712): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3712): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  907): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiService(  907): New client listening to asynchronous messages
D/WISPrService( 3712): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3712): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1180): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/WifiNative-wlan0(  907):    returned true
D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1180): Got an original EVENT_SCAN_RESULTS
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Received scan results (1 BSSes)
D/wpa_supplicant( 1180): nl80211: Survey data missing
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1180): Sorted scan results
I/wpa_supplicant( 1180): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-54
D/wpa_supplicant( 1180): BSS: last_scan_res_used=1/32 last_scan_full=0
D/wpa_supplicant( 1180): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1180): WPS: AP[0] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1180): wpa_supplicant_pick_network+
I/wpa_supplicant( 1180): Selecting BSS from priority group 1
I/wpa_supplicant( 1180): Recent assoc_freq = 0 rssi = 0
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/wpa_supplicant( 1180): 0: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1180): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1180):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1180):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-54
I/wpa_supplicant( 1180): Start print parameters
I/wpa_supplicant( 1180): wpa_s->wpa_state is 3
I/wpa_supplicant( 1180): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1180): isConcurrentMode() is 0
I/wpa_supplicant( 1180): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1180): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1180): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1180): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1180): wpa_s->reassociate is 1
I/wpa_supplicant( 1180): wpa_s->is_screen_on 0
I/wpa_supplicant( 1180): wpa_s->ifname wlan0
I/wpa_supplicant( 1180): End print parameters
I/wpa_supplicant( 1180): selected network = 2
D/wpa_supplicant( 1180): wlan0: Considering connect request: reassociate: 1  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb7c8f4e8  current_ssid=0x0
D/wpa_supplicant( 1180): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1180): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1180): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1180): check if in concurrent case
I/wpa_supplicant( 1180): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302,e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '33 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 33 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
V/NativeCrypto( 1366): Read error: ssl=0x6608ecf8: I/O error during system call, Connection timed out
D/wpa_supplicant( 1180): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1180): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1180): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1180): RSN: PMKSA cache search - network_ctx=0xb7c8f4e8 try_opportunistic=0
D/wpa_supplicant( 1180): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1180): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1180): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1180): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1180): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1180): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1180): nl80211: Unsubscribe mgmt frames handle 0xb7c8e718 (mode change)
D/wpa_supplicant( 1180): nl80211: Subscribe to mgmt frames with non-AP handle 0xb7c8e718
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb7c8e718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb7c8e718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb7c8e718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb7c8e718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb7c8e718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb7c8e718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb7c8e718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb7c8e718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb7c8e718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Register frame type=0xd0 nl_handle=0xb7c8e718
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1180): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1180):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1180):   * freq=2412
D/wpa_supplicant( 1180):   * Auth Type 0
D/wpa_supplicant( 1180):   * WPA Versions 0x2
V/NativeCrypto( 1366): SSL shutdown failed: ssl=0x6608ecf8: I/O error during system call, Broken pipe
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1180): nl80211: Connect request send successfully
D/wpa_supplicant( 1180): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/libc    (  363): [NET] entry_id:3   entry:0xb8cd4108  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb8cd42f0  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb8cd4428  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb8cd3fd8  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb8cd44f0  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb8ccff88  removed 
D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '34 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 34 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/ConnectivityService(  907): resetConnections(wlan0, 3)
D/PMS     (  907): acquireWL(43897e00): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023890
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024047
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024215
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024219
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024223
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025539
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028434
D/ConnectivityService(  907): flush DNS cache for net 1(wlan0)
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1180): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1180): reply (489) for get BSS: id=0
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1180): freq=5220
I/wpa_supplicant( 1180): level=-46
I/wpa_supplicant( 1180): tsf=0000000021879950
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG7005g
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=1
I/wpa_supplicant( 1180): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-54
I/wpa_supplicant( 1180): tsf=0000000021879962
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1180): ssid=01ABC
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=2
I/wpa_supplicant( 1180): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): freq=2412
I/wpa_supplicant( 1180): level=-54
I/wpa_supplicant( 1180): tsf=0000000111767637
I/wpa_supplicant( 1180): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1180): ssid=NG700
I/wpa_supplicant( 1180): ====
I/wpa_supplicant( 1180): id=3
I/wpa_supplicant( 1180): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1180): freq=2452
I/wpa_supplicant( 1180): level=-82
I/wpa_supplicant( 1180): tsf=0000000021879970
I/wpa_supplicant( 1180): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1180): ssid=Gonzos
I/wpa_supplicant( 1180): ####
I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:1
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 21879950, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
D/WifiStateMachine(  907): 1: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -54, frequency: 2412, timestamp: 21879962, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -54, frequency: 2412, timestamp: 111767637, distance: ?(cm), distanceSd: ?(cm)
D/PMS     (  907): acquireWL(4378e390): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/WifiStateMachine(  907): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -82, frequency: 2452, timestamp: 21879970, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  907): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1366/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiManager( 1224): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
I//system/bin/ip(  363): RTNETLINK answers: No such process
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
D/PMS     (  907): releaseWL(43897e00): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
D/WifiNative-wlan0(  907): doBoolean: SET pno 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1180): nl80211: Sched scan stop sent (ret=0)
D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: SCAN
I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  907): getDiscoveryDongleList
I/wpa_supplicant( 1180): wpa_supplicant_scan enter
I/wpa_supplicant( 1180): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1180): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1180): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1180): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1180): Failed to initiate AP scan
I/wpa_supplicant( 1180): Failed to initiate AP scan, Failed_to_scan_counter:1
D/WifiNative-wlan0(  907):    returned true
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/BatSI   (  907): WIFI scan started for: 450a0300 uid:1000
,D/PMS     (  907): releaseWL(4378e390): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
,D/wpa_supplicant( 1180): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1180): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1180): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1180): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1180): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1180): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1180): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1180): nl80211: Event message available
D/wpa_supplicant( 1180): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1180): nl80211: Connect event
D/wpa_supplicant( 1180): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1180): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1180): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1180): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1180): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1180): Add randomness: count=8 entropy=1
I/wpa_supplicant( 1180): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1180): TDLS: Remove peers on association
D/wpa_supplicant( 1180): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Unauthorized
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1180): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1180): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1180): EAPOL: enable timer tick
D/wpa_supplicant( 1180): EAPOL: SUPP_BE entering state IDLE
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
I/wpa_supplicant( 1180): htc_wext_set_keepalive +
I/wpa_supplicant( 1180): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1180): getPrivFuncNum +	
I/wpa_supplicant( 1180): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1180): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiMonitor(  907): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  907): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
I/wpa_supplicant( 1180): htc_wext_set_keepalive - ret = 0
D/HTCRequest(  907): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
I/wpa_supplicant( 1180): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1180): Get randomness: len=32 entropy=2
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/HTCRequest(  907): WifiMonitor:,getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  907): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/WifiMonitor(  907): handleAssociatedWithEvent. bLFR =false
D/WifiMonitor(  907): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/WifiStateMachine(  907): Enter handleAssociatedWithEvent
D/WifiStateMachine(  907): Associated
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
D/WifiStateMachine(  907): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  907): Exit handleAssociatedWithEvent
D/WifiStateMachine(  907): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
D/Tethering(  907): interfaceStatusChanged wlan0, true
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
,D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  907): This record is existed, only update it...
I/wpa_supplicant( 1180): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb7c8e9f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 1180):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 11
D/WifiApDatabaseHandler(  907): updateConnectedAP...
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1180): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1180): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6efab4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1180):    broadcast key
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 11
,I/wpa_supplicant( 1180): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1180): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1180): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1180): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
E/wpa_supplicant( 1180): wlan0: Connect to SSID: NG700
D/wpa_supplicant( 1180): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
,D/wpa_supplicant( 1180): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1180): set send_ind_to_ndc = 0
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1180): htc_wext_set_TX_TRACKING - ret = 0,
D/wpa_supplicant( 1180): EAPOL: External notification - portValid=1
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/wpa_supplicant( 1180): EAPOL: External notification - EAP success=1
,D/wpa_supplicant( 1180): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1180): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1180): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1180): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1180): EAPOL: Supplicant port status: Authorized
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
,D/wpa_supplicant( 1180): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1180): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1180): EAPOL authentication completed successfully
I/wpa_supplicant( 1180): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 79
,D/wpa_supplicant( 1180): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1180): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1180): nl80211: if_removed already cleared - ignore event
D/Tethering(  907): interfaceLinkStateChanged wlan0, true
,D/Tethering(  907): interfaceStatusChanged wlan0, true
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,D/WifiStateMachine(  907): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  907): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiApDatabaseHandler(  907): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  907): This record is existed, only update it...
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  907): updateConnectedAP...
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  907): Provision feature enable=false
,D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  907): updateConnectedAP...
D/WISPrService( 3712): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3712): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiNative-wlan0(  907): doBoolean: SET pno 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  907):    returned true
D/DhcpStateMachine(  907): [StoppedState] Start DHCP
,D/WifiStateMachine(  907): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): Power_Mode_Type mode = 1
I/wpa_supplicant( 1180): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
D/WifiStateMachine(  907): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  907): acquireWL(42a29da8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
,D/WifiStateMachine(  907): handlePreDhcpSetup mBluetoothConnectionActive: false
D/wpa_supplicant( 1180): nl80211: Event message available
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/wpa_supplicant( 1180): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1180): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  907):    returned null
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  907):    returned null
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4250ab68 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@4250ab68 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1115): receive.wifiConnect:false wifiAPname:null elapse:1
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): Power_Mode_Type mode = 0
I/wpa_supplicant( 1180): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1180): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  907): releaseWL(42a29da8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [3][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WIFI_ICON( 1115): updateWifiState: RSSI_CHANGED -1 -> 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1180): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): gateway: /192.168.1.1
D/WifiNative-wlan0(  907): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1180): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1180): htc_wext_set_keepalive +
I/wpa_supplicant( 1180): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1180): getPrivFuncNum +	
I/wpa_supplicant( 1180): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1180): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1180): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1180): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1180): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  907): VerifyingLinkState enter
D/WifiStateMachine(  907): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  907): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  907): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -54, Link speed: 72, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
,D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/ConnectivityService(  907): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
,D/ConnectivityService(  907): Provision feature enable=false
,D/ConnectivityService(  907): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
,V/ConnectivityService(  907): Policy requires mobile/UNKNOWN teardown quickly
,D/MDST    (  907): default: teardown()
,D/MDST    (  907): default: setTeardownRequested(true)
,D/MDST    (  907): default: setEnableApn apnType =default , enable=false
,D/WifiWatchdogStateMachine(  907): WAN detection
,I/IntentController( 1115): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
V/NetworkPolicy(  907): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WIFI_ICON( 1115): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/MDST    (  907): default: setTeardownRequested(true)
D/ConnectivityService(  907): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  907): Unexpected mtu value: android.net.wifi.WifiStateTracker@4242d848
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=false resetMask=0
,D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3712): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  907): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/ConnectivityService(  907): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  907): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  907): syncGetConfiguredNetworks
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  363): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/ConnectivityService(  907): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  907): acquireWL(433ee268): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/WirelessDisplayService(  907): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  907):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
,I//system/bin/ip(  363): RTNETLINK answers: No such file or directory
,I/logwrapper(  363): /system/bin/ip terminated by exit(254)
,I/QuickSettingWifi( 1115): receive.wifiConnect:true wifiAPname:NG700 elapse:1
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
,D/ConnectivityService(  907): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): releaseWL(433ee268): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  907): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4477 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
,D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  907): acquireWL(43898f78): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/PMS     (  907): releaseWL(43898f78): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/CaptivePortalTracker(  907): NoActiveNetworkState
I/Tethering(  907): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  907): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  907): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): Found interface wlan0
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1274): [onReceive] WIFI(1): CONNECTED
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1602/10029)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1274/10076)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4160/10100)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(440ffa00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/PMS     (  907): releaseWL(440ffa00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023890
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024047
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024215
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024219
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024223
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025522
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4160/10100)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025539
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028434
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,I/MusicStore( 4477): Database version: 95
,W/ContextImpl( 4477): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4477): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/wpa_supplicant( 1180): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1180): EAPOL: disable timer tick
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4477): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4477): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4477): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4477, uid=10154, userID:0
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/MediaRouterService(  907): Client com.google.android.music (pid 4477): Registered
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
I/MediaRouter( 4477): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (2690/10021)
,I/NetworkMonitor( 4477): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.music (4477/10154)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
I/ActivityManager(  907): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4500 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 4477): getSelectedRoute
,I/NetworkMonitor( 4477): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4477/10154)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/ACRA    ( 4500): ACRA is enabled for com.facebook.katana, intializing...
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4477, uid=10154, userID:0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(440c2128): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/Process (  907): killProcessQuiet, pid=4018
D/ACRA    ( 4500): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/ACRA    ( 4500): Looking for error files in /data/data/com.facebook.katana/app_minidumps
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
I/ActivityManager(  907): Killing 4018:com.google.android.talk/u0a111 (adj 15): empty #17
D/PMS     (  907): releaseWL(440c2128): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/SystemClassLoaderAdder( 4500): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4500): Preparing secondary program dexes.
V/DexLibLoader( 4500): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 4500): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4500): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4500): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4500): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 4500): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4500): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 4500): Dex already copied
D/OdexVerifier( 4500): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4500): Creating class loader
,V/DexLibLoader( 4500): Finished creating class loader
V/DexLibLoader( 4500): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 4500): Dex already copied
D/OdexVerifier( 4500): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4500): Creating class loader
,V/DexLibLoader( 4500): Finished creating class loader
V/DexLibLoader( 4500): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4500): Dex already copied
D/OdexVerifier( 4500): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4500): Creating class loader
,V/DexLibLoader( 4500): Finished creating class loader
V/DexLibLoader( 4500): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4500): Dex already copied
D/OdexVerifier( 4500): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 4500): Creating class loader
D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
V/DexLibLoader( 4500): Finished creating class loader
,V/DexLibLoader( 4500): Verifying classes from secondary dexes.
,D/DexLibLoader( 4500): DexLibLoader.ensureDexLoaded took 17 ms
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4018
,D/AutoSetting( 1515): service - handleMessage() stop self
,D/AutoSetting( 1515): service - onDestroy() END
,D/AutoSetting( 1515): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4129
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4129:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4129
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): releaseWL(43c88a78): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  907): NetTransition Wakelock for ConnectedState released by timeout
,W/dalvikvm( 4500): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
W/dalvikvm( 4500): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4500): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4500): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
,W/dalvikvm( 4500): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/CaptivePortalTracker(  907): NoActiveNetworkState
W/dalvikvm( 4500): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: true
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(42b7e568): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
W/dalvikvm( 4500): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,I/Tethering(  907): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/PMS     (  907): acquireWL(4406ceb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023890
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024047
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024213
D/PMS     (  907): releaseWL(4406ceb8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024215
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024219
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024223
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025522
D/PMS     (  907): releaseWL(42b7e568): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025539
I/Tethering(  907): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/Tethering(  907): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  907): Found interface wlan0
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,I/ConnectivityHelper( 1274): [onReceive] WIFI(1): CONNECTED
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028434
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4477/10154)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1274/10076)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4160/10100)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.backuptransport (1602/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3813/10053)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/NetworkMonitor( 4477): type=WIFI subType= reason=null isConnected=true
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4160/10100)
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 4500): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4500): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4500): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 4500): Verify
,D/WifiService(  907): New client listening to asynchronous messages
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4500): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4500): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4500): Grow heap (frag case) to 9.511MB for 73240-byte allocation
,D/Process (  907): killProcessQuiet, pid=4160
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4160:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/AutoSetting( 1330): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1330/10055)
,D/AutoSetting( 1330): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,I/ActivityManager(  907): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4522 uid=10079 gids={50079, 3003, 5012}
,D/AutoSetting( 1330): service - onStartCommand() screen is off, don't request location
,D/AutoSetting( 1330): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1330): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1330/10055)
,W/fb4a(:<default>):UserScope( 4500): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4500): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/MobileConnectivityChangeReceiver( 4522): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4522): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4522): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4522): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,W/fb4a(:<default>):UserScope( 4500): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4522/10079)
,I/ActivityManager(  907): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4536 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=4184
,I/ActivityManager(  907): Killing 4184:com.htc.backup/1000 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4522/10079)
I/ActivityManager(  907): Recipient 4184
D/PMS     (  907): acquireWL(43c1b5a8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4160
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (4522/10079)
D/PMS     (  907): acquireWL(437c0408): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43c1b5a8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2189): Checkin interval check for package: unspecified last checkin: 1452511693706 min interval config: 0 actual interval: 56675
,I/CheckinService( 2189): Checking schedule, now: 1452511750390 next: 1452511723655
,I/CheckinService( 2189): active receiver: enabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2189, uid=10029, userID:0
,I/ActivityManager(  907): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4551 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=4147
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/CheckinService( 2189): Preparing to send checkin request
,I/EventLogService( 2189): Accumulating logs since 1452511689236
I/ActivityManager(  907): Killing 4147:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,I/ActivityManager(  907): Recipient 4147
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4500): Grow heap (frag case) to 9.954MB for 84664-byte allocation
,I/CheckinRequestBuilder( 2189): Checkin reason type: 8 attempt count: 1
E/dalvikvm( 4500): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4500): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 4500): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 4500): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4500): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4500): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
,E/ActivityThread( 2189): Failed to find provider info for com.google.android.wearable.settings
E/dalvikvm( 4500): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 4500): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4500): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 4500): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 4500): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4500): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 4500): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4500): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4500): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4500): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/dalvikvm( 4500): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 4500): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,W/ContextImpl( 4551): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4551): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 4551): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4551): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4551): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4500): Grow heap (frag case) to 10.035MB for 39954-byte allocation
,I/dalvikvm-heap( 4500): Grow heap (frag case) to 10.111MB for 79892-byte allocation
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2189/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4551/10151)
,V/WebViewChromiumFactoryProvider( 4551): Binding Chromium to main looper Looper (main, tid 1) {41aa1618}
,I/LibraryLoader( 4551): Expected native library version number "",actual native library version number ""
,I/chromium( 4551): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4551): Initializing chromium process, renderers=0
,D/PMS     (  907): acquireWL(42493018): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
,D/PMS     (  907): acquireWL(4243bf50): PARTIAL_WAKE_LOCK  AudioMix 0x1 373 1013 null
,E/AudioManagerAndroid( 4551): BLUETOOTH permission is missing!
D/PMS     (  907): releaseWL(42493018): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4551): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4551): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4551): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4551): Local Branch: 
I/Adreno-EGL( 4551): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4551): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4551):                  aa63bbd948f41d15fc72f585e
,I/dalvikvm-heap( 4500): Grow heap (frag case) to 10.277MB for 75760-byte allocation
,I/ActivityManager(  907): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4585 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/NSApplication( 4551): Starting up...
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4551/10151)
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{426b4780 u0 ReceiverList{428ed680 4500 com.facebook.katana/10027/u0 remote:42d14240}}
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{426b4780 u0 ReceiverList{428ed680 4500 com.facebook.katana/10027/u0 remote:42d14240}}
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42509618 u0 ReceiverList{4250d4c8 4500 com.facebook.katana/10027/u0 remote:42680e68}}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4551/10151)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/Process (  907): killProcessQuiet, pid=4201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023890
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024047
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024215
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024219
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024223
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025539
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028434
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3523/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3523/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
,I/ActivityManager(  907): Killing 4201:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
W/dalvikvm( 4585): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
W/dalvikvm( 4585): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4585): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4585): install
,I/MultiDex( 4585): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,I/MultiDex( 4585): loading existing secondary dex files
,I/MultiDex( 4585): load found 3 secondary dex files
,I/MultiDex( 4585): install done
I/ActivityManager(  907): Recipient 4201
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
W/dalvikvm( 4585): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4585): VFY: unable to resolve instance field 36
,W/dalvikvm( 4585): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4585): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2690/10021)
D/PMS     (  907): acquireWL(42b52eb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42b52eb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1330): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4522): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4522): onReceive CONNECTIVITY_CHANGE networkType=1
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1330/10055)
D/AutoSetting( 1330): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1330): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1330): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1330): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1330/10055)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (4551/10151)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3523/10160)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3523/10160)
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4500): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2189, uid=10029, userID:0
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4500): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl( 4500): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,I/ProviderInstaller( 4585): Installed default security provider GmsCore_OpenSSL
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WearableService( 1224): callingUid 10029, callindPid: 1224
,W/dalvikvm( 4585): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4585): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,E/MDM     ( 1224): [115] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 2189): Restart initialization of location
,W/dalvikvm( 4585): Link of class 'Lcom/google/android/gms/common/j/c;' failed
D/AuthorizationBluetoothService( 1366): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1366): Proximity feature is not enabled.
E/dalvikvm( 4585): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4585): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4585): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4585): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,W/GCoreFlp( 1224): No location to return for getLastLocation()
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/FusedLocationProvider( 1224): location=null
D/PMS     (  907): acquireWL(4363a810): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4363a810): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023890
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024047
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024215
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024219
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024223
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025539
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028434
,I/WVCdm   (  373): Level3 Library Nov 20 2013 18:09:31
,W/WVCdm   (  373): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  373): CdmEngine::OpenSession
,I/WVCdm   (  373): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  373): CdmEngine::GenerateKeyRequest
,D/NativeLibraryUtils( 4585): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  373): PrepareKeyRequest: nonce=3788726838
,I/WVCdm   (  373): CdmEngine::CloseSession
,D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =2935 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,W/Settings( 4585): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  363): [NET]res_nsend:resplen=172
D/libc    (  363): [NET]res_queryN: exit 3, ancount=4
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  907): Find DNS Address www.htc.com/104.81.130.175
,I/Adreno-EGL( 4585): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4585): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4585): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4585): Local Branch: 
I/Adreno-EGL( 4585): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4585): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4585):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4585): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4585): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4585): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4585): Local Branch: 
I/Adreno-EGL( 4585): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4585): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4585):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (4585/10029)
,I/Adreno-EGL( 4585): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4585): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4585): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4585): Local Branch: 
I/Adreno-EGL( 4585): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4585): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4585):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  373): CdmEngine::OpenSession
,I/WVCdm   (  373): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  373): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  373): PrepareKeyRequest: nonce=3413970203
,I/WVCdm   (  373): CdmEngine::CloseSession
,I/CheckinRequestBuilder( 2189): Classify the device as Phone.
,D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2189): [NET] getaddrinfo-,err=8
,D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2189): [NET] getaddrinfo-, 1
D/libc    ( 2189): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =84e0 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/WifiStateMachine(  907): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 105
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2189): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2189): [NET] getaddrinfo-,err=8
,D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2189): [NET] getaddrinfo-,err=8
D/libc    ( 2189): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2189): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2189): Sending checkin request (12076 bytes)
,I/CheckinRequestBuilder( 2189): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2189): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2189/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=9 [21][2][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,I/CheckinRequestBuilder( 2189): Classify the device as Phone.
,I/CheckinTask( 2189): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2189): Checking schedule, now: 1452511752890 next: 1453034689882
,I/CheckinService( 2189): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2189, uid=10029, userID:0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023890
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024047
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024213
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024215
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024219
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024223
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025539
,D/CheckinService( 2189): Recording last checkin time for package unspecified as 1452511752924
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028434
,D/PMS     (  907): releaseWL(437c0408): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2189/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
,D/PMS     (  907): acquireWL(42659f10): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
D/GCM     ( 1366): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc    ( 1366): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1366): [NET] getaddrinfo-,err=8
D/libc    ( 1366): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1366): [NET] getaddrinfo-, 1
D/libc    ( 1366): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =649 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
,W/fb4a(:<default>):UserScope( 4500): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):UserScope( 4500): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=79
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1366): [NET] getaddrinfo_proxy-, success
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
D/libc    ( 1366): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1366): [NET] getaddrinfo-,err=8
,D/libc    ( 1366): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1366): [NET] getaddrinfo-,err=8
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
,E/fb4a(:<default>):LocalFbBroadcastManager( 4500): Called registerBroadcastReceiver twice.
,D/PMS     (  907): acquireWL(43c0d618): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
,D/PMS     (  907): releaseWL(42659f10): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1366/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/PMS     (  907): releaseWL(43c0d618): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(437f6970): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1366/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1366/10029)
,D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
,D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023890
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024047
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024215
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024219
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024223
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025539
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028434
,D/PMS     (  907): releaseWL(437f6970): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027),
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (4500/10027)
,D/PMS     (  907): releaseWL(4243bf50): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  907): acquireWL(431f0348): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4477 10154 null
,W/ContextImpl( 4477): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4477, uid=10154, userID:0
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,I/MusicLeanback( 4477): Conditions not met for autocaching.
,I/MusicLeanback( 4477): Stop autocaching.
,D/PMS     (  907): releaseWL(431f0348): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
W/ContextImpl( 4477): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [8][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/Process (  907): killProcessQuiet, pid=3813
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3813:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3813
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/GAV2    ( 4551): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4384): Test app app.js loaded
I/jxcore-log( 4384): 
,I/chromium( 4384): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/Process (  907): killProcessQuiet, pid=4233
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4233:com.htc.mediamanager/u0a34 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4233
,D/PMS     (  907): acquireWL(4357de00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{426039f8: PendingIntentRecord{4294d3c8 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=122588, Int=0
,D/PMS     (  907): releaseWL(4357de00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43b9de40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=22 [9][2][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(43fce170): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43fce170): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43b9de40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(434cdbf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023890
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024047
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024213
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024215
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024219
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024223
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025522
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025539
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028434
,D/PMS     (  907): releaseWL(434cdbf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(435d66e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023890
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024047
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024215
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024219
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024223
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025539
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028434
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  907): acquireWL(4418cc40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4410c348): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1224): Vacuum at: now=1452511758658 tag=VacuumService
D/PMS     (  907): releaseWL(435d66e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4418cc40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(44037728): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023890
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024047
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024215
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024219
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024223
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025539
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028434
,D/PMS     (  907): releaseWL(4410c348): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(44037728): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(44030068): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023890
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024047
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024213
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024215
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024219
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024223
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025539
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028434
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(44030068): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(43c7a638): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023890
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024047
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024213
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024215
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024219
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024223
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025522
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025539
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028434
,D/PMS     (  907): releaseWL(43c7a638): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43c7a428): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023890
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024047
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024213
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024215
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024219
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024223
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025522
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025539
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028434
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(43c7a428): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(43c56678): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023890
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024047
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024215
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024219
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024223
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025539
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028434
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(43188208): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43188208): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42431b08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43c56678): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(41db5f70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023890
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024047
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024215
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024219
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024223
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025539
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028434
,D/PMS     (  907): releaseWL(41db5f70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1224): Scheduling Phenotype for one-off execution 788 seconds from now (1452511759276)
,D/GetConfigurationSnapshotOperation( 1224): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1224): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1224): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1224): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1224): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1224): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1224): Using platform SSLCertificateSocketFactory
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  907): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  907): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
W/dalvikvm( 1224): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1224): [NET] getaddrinfo-,err=8
D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1224): [NET] getaddrinfo-, 1
,D/libc    ( 1224): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =17e4 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 260
D/libc    (  363): [NET]res_nsend:resplen=87
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
,D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1224): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1224): [NET] getaddrinfo-,err=8
D/libc    ( 1224): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1224): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=8 [12][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=50 [2][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(42431b08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42d85f70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023890
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024047
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024215
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024219
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024223
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025539
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028434
,D/PMS     (  907): releaseWL(42d85f70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(43b824b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023890
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024047
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024215
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024219
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024223
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025539
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028434
,D/PMS     (  907): releaseWL(43b824b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1344): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  907): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4657 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1274): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/Launcher( 1274): Deferring update until onResume
,D/Launcher( 1274): waitUntilResume // bindAppsUpdated
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,W/AccTypeManager( 1344): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1344): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,E/ExternalAccountType( 1344): Unsupported attribute readOnly
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4657): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4657): MmsConfig.loadMmsSettings
,W/dalvikvm( 4657): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4657): VFY: unable to resolve instance field 36
,W/dalvikvm( 4657): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4657): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  907): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4680 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4657, uid=10111, userID:0
,W/Settings( 4657): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MessageFrequencyProvider( 4680): onCreate
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4657, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4657, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4657, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4657, uid=10111, userID:0
,V/GetPrviateResource( 4680): GetPrviateResource
,V/GetPrviateResource( 4680): GetPrviateResource
,D/MmsCustomizationProvider( 4680): query uri: content://htc-mms-customization/mms-ua/ua_string
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4657, uid=10111, userID:0
D/PMS     (  907): acquireWL(436129a8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4657 10111 null
,I/[PluginManager]RegisterService( 1330): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1330): handle notify Blinkfeed plugin client changed
,D/MmsCustomizationProvider( 4680): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/IcingCorporaProvider( 2788): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/Babel   ( 4657): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4657): MmsConfig.loadFromDatabase
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  907): acquireWL(43bc8088): PARTIAL_WAKE_LOCK  Icing 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,W/PackageManager(  907): Unable to load service info ResolveInfo{42574990 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
D/PMS     (  907): acquireWL(42686718): PARTIAL_WAKE_LOCK  AsyncService 0x1 3523 10160 null
D/PMS     (  907): releaseWL(43bc8088): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Babel   ( 4657): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 4657): MmsConfig.loadFromResources
E/Babel   ( 4657): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 4657): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
D/MessageCustFlag( 4680): sense_version=6.0
D/PMS     (  907): releaseWL(42686718): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/PMS     (  907): acquireWL(438ac568): PARTIAL_WAKE_LOCK  Icing 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
D/BTAccessoryUtil( 4680): createReceiver
D/BTAccessoryUtil( 4680): registerReceiver return intent = null
D/MessageCustFlag( 4680): sku_id=99
W/SystemReader( 4680): Cannot find message_ambs_application_id, use default value instead
D/PMS     (  907): releaseWL(436129a8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
D/Messaging( 4680): supportCMAS(SIE)/init? false/true
I/ProviderInstaller( 4657): Installed default security provider GmsCore_OpenSSL
D/MmsConfig( 4680): networkCode: 
D/MessageCustFlag( 4680): sku_id=99
D/MmsConfig( 4680): SIE smsPri: null
D/MmsConfig( 4680): networkCode: 
D/HtcTelephonyCapability( 4680): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4680): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4680): getRATByHtcTelephonyCapability:1
W/SystemReader( 4680): Cannot find qct_8960_interface, use default value instead
,D/Process (  907): killProcessQuiet, pid=4252
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4252:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver,
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PackageBroadcastService( 2189): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager(  907): Recipient 4252
,D/WifiService(  907): Client connection lost with reason: 4
I/PackageBroadcastService( 2189): Null package name or gms related package.  Ignoreing.
,I/ActivityManager(  907): Resuming delayed broadcast
,I/Icing   ( 2189): updateResources: need to parse f{com.google.android.gms}
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
,I/GCoreNlp( 1224): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PMS     (  907): acquireWL(440b4838): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(440b4838): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(421ae800): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(421ae800): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  907): applying state to connected service
,D/LocationProviderProxy(  907): applying state to connected service
D/PMS     (  907): acquireWL(4314c540): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(423de678): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4314c540): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(423de678): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2788): UpdateCorporaTask done [took 518 ms] updated apps [took 518 ms] 
,I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@41b37db0 +
,I/Prism.WidgetManager( 1274): onLoadItems() +
,I/Icing   ( 2189): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2189): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  907): releaseWL(438ac568): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1274): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1274): onLoadItems() -
,I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@41b37db0 -
,D/PhoneApp( 1241): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1241): -- N1 =0
,D/PhoneApp( 1241): -- N2 =0
,D/PhoneApp( 1241): -- N3 =0
,D/Messaging( 4680): mNeedToUpdateDate2 start
,D/MmsConfig( 4680): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4680): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4680): 
D/MmsAsyncWorkHandler( 4680): HM tk = 20001
D/ReportIndicatorCache( 4680): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4680): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41ab0288
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,I/Messaging( 4680): mccmnc> 
D/DraftCache( 4680): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4680): [DraftCache/1] refresh
,D/MmsConfig( 4680): networkCode: 
,D/Messaging( 4680): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1241): sku_id=99
,D/PhoneStorageUtil( 4680): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4680): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4680): createReceiver
,D/MessageCustFlag( 4680): sense_version=6.0
,D/Jerry   ( 4680): start to preload cursor >>>>>>>
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/DraftCache( 4680): [DraftCache/460] rebuildCache
,D/TelephUtils( 1241): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
V/MmsProvider( 1241): Update uri=content://mms, match=0
,V/MmsProvider( 1241): selection=st=129 AND m_type!=134
,D/Messaging( 4680): mNeedToUpdateDate2: false
,D/Messaging( 4680): Reset downloading state: 0
V/MmsSystemEventReceiver( 4680): TransactionService is going to be woken up.
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,V/TransactionService( 4680): 1-Creating TransactionService
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
V/TransactionService( 4680): onStartCommand: 1
,D/MmsSystemEventReceiver( 4680): unRegisterForConnectionStateChanges
V/TransactionService( 4680): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 4680): Loading previous transactions.
,D/Jerry   ( 1241): URI_DRAFT
D/Messaging( 4680): ViewCache CreatePreload
,D/Messaging( 4680): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Cust_MMSMS( 4680): _has_set_default_values_2=true
D/DraftCache( 4680): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4680): [DraftCache/460] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4680): 
D/MmsAsyncWorkHandler( 4680): HM tk = 20002
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1241): device_type: 1
D/TransactionService( 4680): Force set service start id to 1
V/TransactionService( 4680): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4680): unRegisterForConnectionStateChanges
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 74
D/TransactionService( 4680): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4680): Destroying TransactionService
,D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,V/TransactionService( 4680): 4-Handling incoming message: { when=-3ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/MsgPreferenceUtils( 4680): def_index: 0
,D/MsgPreferenceUtils( 4680): globalIndex = 1
,D/Messaging( 4680): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/MsgPreferenceUtils( 4680): phone state: true
D/MsgPreferenceUtils( 4680): sd state: false
,D/MsgPreferenceUtils( 4680): vIndex = 0
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1241): sku_id=99
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 74
,D/AccFlag ( 1241): sku_id=99
,I/GAV4    ( 4657): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  907): acquireWL(435e0868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(435e0868): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=99
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(4362dab0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{42e407a0: PendingIntentRecord{42c647d0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137956, Int=0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
,D/PMS     (  907): releaseWL(4362dab0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42e13e00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423662d0: PendingIntentRecord{4248cdd8 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141302, Int=0
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  907): acquireWL(42e0fd38): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =f74a +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/PMS     (  907): releaseWL(42e13e00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  363): [NET]res_nsend:resplen=238
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=10
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo_proxy-, success
I/global  (  907): call createSocket() return a new socket.
D/libc    (  907): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/PMS     (  907): acquireWL(4352d540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/BatteryService(  907): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=99
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/PMS     (  907): releaseWL(4352d540): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/HtcPowerSaver(  907): updateStatus (8000,99,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
,I/BatteryController( 1115): status:2 level:99 unsupport:false plugged:true
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/AutoSetting( 1330): service - mHandler: update timezone
,D/AutoSetting( 1515): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1515): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1515): service - onCreate()
,D/AutoSetting( 1515): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1515): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
D/DotMatrix( 1590): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1590): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  907): batLight: plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c80000
D/qdlights(  907): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1515): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1515): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1515): service - mHandler: update timezone
,D/AutoSetting( 1515): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1515): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1515): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1515): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1590): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1590): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/PhoneStatusBar( 1115): removeNotification.gc:55
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41b05150 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.htclocationservice 2 6 2 11
,D/AutoSetting( 1330): service - mHandler: update timezone
,D/AutoSetting( 1515): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1515): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
D/AutoSetting( 1515): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1515): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/DotMatrix( 1590): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1590): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  907): batLight: plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c80000
D/qdlights(  907): set_color_led color=13107200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=1c80000,len=7
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1515): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1515): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1515): service - mHandler: update timezone
,D/AutoSetting( 1515): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1515): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1515): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1515): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1590): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1590): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1330): service - handleMessage() stop self
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41e355a0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.htclocationservice 3 8 3 11
,D/AutoSetting( 1330): service - handleMessage() quit looper
,D/AutoSetting( 1330): service - onDestroy() END
,D/PMS     (  907): releaseWL(42e0fd38): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/Process (  907): killProcessQuiet, pid=4275
,I/ActivityManager(  907): Killing 4275:com.htc.calendar/u0a13 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 4275
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{42c682b0 u0 com.htc.htclocationservice/.AutoSettingService}
,D/PMS     (  907): acquireWL(4317b3c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=164319, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4317b3c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(428434c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10027}
,V/AlarmManager(  907): sending alarm PendingIntent{42f4bb20: PendingIntentRecord{43c7dc78 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=173980, Int=0
,D/PMS     (  907): releaseWL(428434c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/AutoSetting( 1515): service - handleMessage() stop self
,D/AutoSetting( 1515): service - onDestroy() END
,D/AutoSetting( 1515): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=4289
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4289:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4289
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
,D/PMS     (  907): acquireWL(43c7d6d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43c7d6d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=99
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,99,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:2 level:99 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(43576148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43576148): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
,D/PowerUI ( 1115): closing low battery warning: level=100
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1590): [EventService] reorderNotification, total:0
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/HeadsetPhoneState( 1644): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,W/ContextImpl( 4351): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,D/TetherSettings( 3712): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3712): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3712): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3712): Cust_ConnectToPC   : spcsc>false
D/        ( 3712): Cust_ConnectToPC   : IPT>true
D/        ( 3712): Cust_ConnectToPC   : Singel_USB>false
,D/SmartNS_NSReceiver( 3712): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3712): Index of the first 1 = -1
W/ContextImpl( 3712): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3712): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3712): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3712): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3712): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3712): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/SmartNS_Utility( 3712): [ACC]android_networking:tethering_guard_support=false
,D/PMS     (  907): acquireWL(4375f950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=224319, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4375f950): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(43585210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  907): releaseWL(43585210): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(43433d58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43433d58): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(43c56e78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=284319, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43c56e78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(43610920): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43610920): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/jxcore-log( 4384): TAP version 13
I/jxcore-log( 4384): 
,I/jxcore-log( 4384): # setup
I/jxcore-log( 4384): 
,I/jxcore-log( 4384): # multiplex can send data
I/jxcore-log( 4384): 
,I/jxcore-log( 4384): # teardown
I/jxcore-log( 4384): 
,I/jxcore-log( 4384): ok 1 String should be length:200
I/jxcore-log( 4384): 
,I/jxcore-log( 4384): # setup
I/jxcore-log( 4384): 
,I/jxcore-log( 4384): # muxServerBridge
I/jxcore-log( 4384): 
,I/jxcore-log( 4384): # teardown
I/jxcore-log( 4384): 
,I/jxcore-log( 4384): server bridge: new client socket
I/jxcore-log( 4384): 
,I/jxcore-log( 4384): client bridge: new client socket
I/jxcore-log( 4384): 
,I/jxcore-log( 4384): client bridge: socket closed
I/jxcore-log( 4384): 
,D/PMS     (  907): acquireWL(43c58ad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(43c58ad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(4358a878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=344319, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4358a878): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(42904d48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/UsbnetService(  907): BroadcastReceiver::onReceive+
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): releaseWL(42904d48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(437ed588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(437ed588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(4261dac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=404319, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4261dac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(4267b388): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4267b388): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43bfa7a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43bfa7a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(44071718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=464319, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(44071718): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(437f1550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(437f1550): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): acquireWL(435bf290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(435bf290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(44073f48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=524318, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(44073f48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(431e1158): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(431e1158): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43515d10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=584319, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43515d10): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4268d8e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4268d8e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1241): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1241): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1241): sku_id=99
D/ContactMessageStore( 1241): start background delete task...
,D/ContactMessageStore( 1241): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1241): size: 0 , 0
,D/ContactMessageStore( 1241): Background delete complete
,D/Process (  907): killProcessQuiet, pid=3991
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3991:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3991
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(4291b348): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=644318, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4291b348): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4377e850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4377e850): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(42ccebf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=704319, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42ccebf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4269f110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4269f110): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(42bd6f40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41cf1ec8: PendingIntentRecord{4249e3f8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=740322, Int=0
,D/PMS     (  907): acquireWL(436a7720): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,I/ActivityManager(  907): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4773 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  907): sending alarm PendingIntent{4245eaa8: PendingIntentRecord{424ece68 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1452511846433, Int=10800000
,D/PMS     (  907): releaseWL(42bd6f40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10049}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(43fd0918): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null,
,D/PMS     (  907): releaseWL(436a7720): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  907): releaseWL(43fd0918): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.aurora (4773/10049)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023890
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024047
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024215
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024219
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024223
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025539
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028434
,D/Process (  907): killProcessQuiet, pid=4323
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4323:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4323
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(43c56808): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=764319, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43c56808): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43c565b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  907): sending alarm PendingIntent{41d3abf8: PendingIntentRecord{42438000 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=782757, Int=0
,D/PMS     (  907): releaseWL(43c565b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  907): Done.
,D/ConnectivityService(  907): Setting timer for 720seconds
,D/PMS     (  907): acquireWL(438aeaa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(438aeaa0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(437e5c48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=824319, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(437e5c48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(437cbda0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(437cbda0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(437c0408): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=884319, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(437c0408): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43779cb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43779cb0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4376ee50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=944319, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4376ee50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4376ecc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4376ecc0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4370e298): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1004319, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4370e298): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4370b628): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{4233a1f8: PendingIntentRecord{4231ea78 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452512566765, Int=900000
,V/AlarmManager(  907): sending alarm PendingIntent{42492230: PendingIntentRecord{440b7508 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1452512643580, Int=0
,W/ContextImpl( 4351): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4351): call getInstance()
,D/SmartSyncUtils( 4351): isEpsOn(), nState = 0
,D/PowerUsageList:PowerUsageHelper( 4351): MY_DEBUG = false
,D/SmartSyncScreenOnOffTimeReceiver( 4351): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4351): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/PMS     (  907): releaseWL(4370b628): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(436f8c48): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4351 1000 null
D/SmartSyncScreenOnOffTimeReceiver( 4351): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4351): SettingOnTime = 1452578400000, randomSettingOnTime = 1452576805000
D/SmartSyncScreenOnOffTimeReceiver( 4351): SettingOffTime = 1452564000000, randomSettingOffTime = 1452569215000
D/SmartSyncScreenOnOffTimeReceiver( 4351): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4351): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4351): bNightModeTurnOffOnce = false
D/PMS     (  907): releaseWL(436f8c48): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/PMS     (  907): acquireWL(4294fec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{42bbee48: PendingIntentRecord{42bef1a0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1017534, Int=0
,D/PMS     (  907): acquireWL(42559758): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42559758): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4294fec0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(435c3390): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1366/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023890
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024047
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024213
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024215
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024219
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024223
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025539
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028434
,D/PMS     (  907): releaseWL(435c3390): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=6 [245][15][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(43bfa4b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43bfa4b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(435cc550): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1064319, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(435cc550): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(436dc430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(436dc430): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4352b0b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4352b0b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 99, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(43471420): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1124319, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,I/dalvikvm-heap( 1274): Grow heap (frag case) to 12.642MB for 50416-byte allocation
,D/PMS     (  907): releaseWL(43471420): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43fc96f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43fc96f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(437695a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1184319, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(437695a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(41f49a40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(41f49a40): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  907): acquireWL(432fe7c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1244319, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(432fe7c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43fdc580): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43fdc580): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(43fc4ee0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1304319, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(43fc4ee0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43fcac10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43fcac10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(435c45f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1364320, Int=0
,D/PMS     (  907): releaseWL(435c45f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(435a4590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(435a4590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(425b2648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1424319, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(425b2648): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43770588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43770588): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(435ba020): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1484318, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(435ba020): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(4315b410): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4315b410): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4408de60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1544319, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4408de60): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43757dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43757dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(435d4478): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1604319, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(435d4478): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(426718d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(426718d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(436fb940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1664318, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(436fb940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42b52cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42b52cc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4403b320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1724319, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4403b320): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(43386e50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43386e50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(437ed760): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1784319, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(437ed760): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/PMS     (  907): acquireWL(43fd6e18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(43fd6e18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  356): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  907): acquireWL(4361b4f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1844319, Int=0
,I/ProcessStatsService(  907): Prepared write state in 42ms
I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,I/ProcessStatsService(  907): Pruning old procstats: /data/system/procstats/state-2016-01-10-12-23-31.bin
,D/PMS     (  907): releaseWL(4361b4f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(435863d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,V/AlarmManager(  907): sending alarm PendingIntent{41d3abf8: PendingIntentRecord{42438000 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1502778, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{41f53d80: PendingIntentRecord{4258ba08 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=1820828, Int=1800000
,V/AlarmManager(  907): sending alarm PendingIntent{436b4640: PendingIntentRecord{436dd180 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.common.receiver.LOG_CORE_ANALYTICS, t=3, cnt=1, w=1849293, Int=0
V/AlarmManager(  907): sending alarm PendingIntent{4319f260: PendingIntentRecord{42956668 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452513325790, Int=1800000
,D/PMS     (  907): acquireWL(426f9a10): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
,V/AlarmManager(  907): sending alarm PendingIntent{4233a1f8: PendingIntentRecord{4231ea78 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1452513466765, Int=900000
,D/ConnectivityService(  907): Done.
,D/ConnectivityService(  907): Setting timer for 720seconds
,D/PMS     (  907): releaseWL(426f9a10): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/LocationManagerService(  907): getAllProviders()=[passive, gps, network]
D/PMS     (  907): acquireWL(43155550): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4351e680): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(43155550): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/EventLogService( 2189): Aggregate from 1452511750445 (log), 1452511525745 (data)
W/ContextImpl( 4351): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  907): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
W/BatSI   (  907): Couldn't get kernel wake lock stats
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1366): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023890
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024047
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024215
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024219
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024223
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025522
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025539
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028434
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): releaseWL(435863d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): releaseWL(4351e680): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/PMS     (  907): acquireWL(4418be98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(4418be98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(42e61aa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e02ee0: PendingIntentRecord{41daebc8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1904319, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42e61aa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(440b9170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{41e653b8: PendingIntentRecord{42bef1a0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=1917619, Int=0
,D/PMS     (  907): acquireWL(424b9508): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(424b9508): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/Process (  907): killProcessQuiet, pid=4551
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
D/Process (  907): killProcessQuiet, pid=4536
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
,D/Process (  907): killProcessQuiet, pid=4522
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  907): Killing 4551:com.google.android.apps.magazines/u0a151 (adj 15): empty for 1802s
I/ActivityManager(  907): Killing 4536:com.android.chrome/u0a96 (adj 15): empty for 1802s
D/PMS     (  907): releaseWL(440b9170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Killing 4522:com.google.android.setupwizard/u0a79 (adj 15): empty for 1802s
,I/ActivityManager(  907): Recipient 4522
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4536
,D/PMS     (  907): acquireWL(4406dc18): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1366 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
,D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1366/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1366/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023890
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024047
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024213
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024215
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024219
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024223
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025522
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025539
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028434
,D/PMS     (  907): releaseWL(4406dc18): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4551
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1180): environment dirty rate=15 [169][27][0]
,I/wpa_supplicant( 1180): Change stage from stage0 to stage3
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1180): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1180): nl80211: survey data missing!
E/wpa_supplicant( 1180): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1180): environment dirty rate=0 [0][0][0]
,TIME-OUT KILL (timeout was 1800000ms),E/cutils-trace( 4805): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4805): ====startRecUseTime====
D/htc.customization.log.level( 4805):  is 
W/CustomizationLogLevel( 4805): Level value is invalid, use default level 2
D/CustomizationManager( 4805):  Read ACC file spent 0.055 (s)
D/CIDMapFileReader( 4805): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4805): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4805): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4805): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4805): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4805): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4805): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4805): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4805): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4805): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4805): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4805): Parsing tag category name = system
I/CustomizationCIDLoader( 4805): Parsing tag category name = application
I/CustomizationCIDLoader( 4805): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4805): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4805): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4805): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4805): Parsing tag category name = Settings
D/CustomizationManager( 4805):  Read CID file spent 0.103 (s)
D/CustomizationManager( 4805):  All configurations done spent 0.104 (s)
W/HtcNativeFlag( 4805): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4805): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4805): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4805): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  907): deletePackageAsUser: pkg=com.test.thalitest, pid=4805, uid=2000 user=0
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  907): killProcessQuiet, pid=4384
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  907): handleTopAppChanged(): The previous AP is died unexpectedly.
D/Process (  907): killProcessQuiet, pid=4477
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16976 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5102 
I/ActivityManager(  907): Killing 4384:com.test.thalitest/u0a389 (adj 0): stop com.test.thalitest
I/ActivityManager(  907): Killing 4477:com.google.android.music:main/u0a154 (adj 15): empty for 1801s
I/ActivityManager(  907):   Force finishing activity ActivityRecord{439db0a8 u0 com.test.thalitest/.MainActivity t2}
D/MediaRouterService(  907): Client com.google.android.music (pid 4477): Died!
I/ActivityManager(  907): Recipient 4477
W/asset   (  907): Copying FileAsset 0x6409af40 (zip:/data/app/com.test.thalitest-2.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  907): Skipping PackageSetting{421682a0 com.example.hello/10397} due to missing metadata
I/ActivityManager(  907): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 4384 uid 10389
E/JavaBinder( 1210): !!! FAILED BINDER TRANSACTION !!!
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1590): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1590): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1590): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
W/GeofencerStateMachine( 1224): Ignoring removeGeofence because network location is disabled.
D/PMS     (  907): acquireWL(437d59c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(437d59c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1344): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  907): WIN DEATH: Window{4355f5a0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/InputDispatcher(  907): channel '4355f5a0 com.test.thalitest.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  907): channel '4355f5a0 com.test.thalitest.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher(  907): Attempted to unregister already unregistered input channel '4355f5a0 com.test.thalitest.MainActivity (s)'
D/VoicemailCleanupService( 1301): Cleaning up data for package: com.test.thalitest
D/WifiService(  907): Client connection lost with reason: 4
I/WindowManager(  907): WINDOW DIED Window{4355f5a0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/AccTypeManager( 1344): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1344): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/Launcher( 1274): Deferring update until onResume
D/Launcher( 1274): waitUntilResume // bindAppsRemoved
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/[PluginManager]RegisterService( 1330): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1330): handle notify Blinkfeed plugin client changed
E/ExternalAccountType( 1344): Unsupported attribute readOnly
D/Prism.PackageStateRece_( 1274): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/IcingCorporaProvider( 2788): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4820 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/PMS     (  907): acquireWL(437895f0): PARTIAL_WAKE_LOCK  Icing 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(437895f0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(43779728): PARTIAL_WAKE_LOCK  Icing 0x1 2189 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2788): UpdateCorporaTask done [took 190 ms] updated apps [took 189 ms] 
W/PackageManager(  907): Unable to load service info ResolveInfo{4241abc8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/SQLiteDatabase( 4820): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4820): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4820): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4820): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4820): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4820): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4820): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4820): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4820): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4820): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4820): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4820): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4820): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4820): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4820): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4820): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4820): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4820): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4820): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4820): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4820): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4820): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4820): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4820): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4820): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4820): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4820): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4820): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4820): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4820): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4820): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4820): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4820): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4820): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4820): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4820): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4820): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4820): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4820): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4820): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4820): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4820): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4820): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4820): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4820): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4820): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4820): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4820): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4820): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4820): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4820): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4820): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4820): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4820): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4820): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4820): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4820): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4820): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4820): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4820): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4820): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4820): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4820): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4820): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4820): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4820): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4820): threadid=11: thread exiting with uncaught exception (group=0x41674e30)
E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4820): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4820): Process: com.google.android.apps.docs, PID: 4820
E/AndroidRuntime( 4820): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4820): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4820): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4820): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4820): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4820): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4820): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4820): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4820): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4820): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4820): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4820): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4820): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4820): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4820): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4820): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4820): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4820): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4820): 	at aho.run(AbstractDatabaseInstance.java:455)
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
E/SQLiteDatabase( 4820): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4820): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4820): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4820): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4820): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4820): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4820): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4820): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4820): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4820): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4820): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4820): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4820): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4820): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4820): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4820): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4820): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4820): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4820): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4820): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4820): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4820): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4820): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4820): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4820): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4820): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4820): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4820): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4820): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4820): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4820): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4820): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4820): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4820): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4820): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4820): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4820): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4820): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4820): Opened ClientFlag.db in read-only mode
D/Process ( 4820): killProcess, pid=4820
D/Process ( 4820): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4838 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  907): Recipient 4820
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.android.apps.docs (pid 4820) has died.
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start
W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/ContextImpl( 4838): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4838): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4838): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4838): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4838): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4838): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4838): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4838): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4838): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4838): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4838): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4838): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4838): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4838): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4838): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4838): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4838): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4838): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4838): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4838): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4838): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4838): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4838): threadid=10: thread exiting with uncaught exception (group=0x41674e30)
I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4851 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/ActivityManager(  907): App crashed! Process: com.android.keychain
E/AndroidRuntime( 4838): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4838): Process: com.android.keychain, PID: 4838
E/AndroidRuntime( 4838): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4838): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4838): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4838): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4838): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4838): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4838): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4838): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4838): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4838): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4838): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4838): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4838): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4838): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4838): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4838): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4838): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4838): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4838): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4838): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452513555922.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  907): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  907): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  907): 	... 4 more
D/Process ( 4838): killProcess, pid=4838
D/Process ( 4838): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Recipient 4838
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.android.keychain (pid 4838) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 4851): getInstance(Context context)
D/AppTag  ( 4851): getInstance(Context context)
D/AppTag  ( 4851): onCreate()
D/PMS     (  907): acquireWL(435b9cb8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3523 10160 null
D/PMS     (  907): releaseWL(435b9cb8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 3952): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2189): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2189): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2189): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2189): Module APK com.google.android.play.games already loaded
I/ActivityManager(  907): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
D/ChimeraCfgMgr( 2189): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2189): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 2189): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 2189): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 2189): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2189): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x66d7f658
E/SQLiteDBG( 2189): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x655f4460
W/dalvikvm( 2189): threadid=47: thread exiting with uncaught exception (group=0x41674e30)
E/DriveAsyncService( 2189): disk I/O error (code 3850)
E/DriveAsyncService( 2189): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2189): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2189): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2189): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2189): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2189): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2189): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2189): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2189): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2189): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2189): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2189): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2189): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2189): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2189): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2189): 	at java.lang.Thread.run(Thread.java:864)
E/AndroidRuntime( 2189): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2189): Process: com.google.android.gms, PID: 2189
E/AndroidRuntime( 2189): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2189): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2189): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2189): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2189): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2189): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2189): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2189): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2189): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2189): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2189): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2189): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2189): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2189): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2189): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2189): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2189): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2189): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2189): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  907): App crashed! Process: com.google.android.gms
D/Process ( 2189): killProcess, pid=2189
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 2189): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  907): Recipient 2189
I/ActivityManager(  907): Process com.google.android.gms (pid 2189) has died.
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
D/PMS     (  907): handleWLDeath(43779728): PARTIAL_WAKE_LOCK  Icing 0x1
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 21000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 21000ms
I/ActivityManager(  907): Resuming delayed broadcast
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20996ms
E/SQLiteLog( 1366): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1366): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63fbe9e8
W/dalvikvm( 1366): threadid=1: thread exiting with uncaught exception (group=0x41674e30)
E/ActivityManager(  907): App crashed! Process: com.google.process.gapps
E/AndroidRuntime( 1366): FATAL EXCEPTION: main
E/AndroidRuntime( 1366): Process: com.google.process.gapps, PID: 1366
E/AndroidRuntime( 1366): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1366): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1366): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1366): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1366): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1366): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1366): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1366): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1366): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1366): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1366): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1366): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1366): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1366): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1366): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1366): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1366): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1366): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1366): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1366): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1366): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1366): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1366): 	... 10 more
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 1366): killProcess, pid=1366
D/Process ( 1366): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4881 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 4881): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4881 dbg=false s=true
I/DeviceManagement( 4881): PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
I/DeviceManagement( 4881): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
I/DeviceManagement( 4881): WorkflowService: Starting workflow service
I/DeviceManagement( 4881): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41adab78] args=[Bundle[mParcelledData.dataSize=120]]
I/DeviceManagement( 4881): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4881): PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
I/DeviceManagement( 4881): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4881): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  907): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4895 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 4881): BackgroundController: *** Processing package remove for appID=com.test.thalitest
I/DeviceManagement( 4881): SessionStateController: Checking invariants...
D/Documents( 4895): Loading roots for com.android.providers.downloads.documents
I/ActivityManager(  907): Recipient 1366
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.process.gapps (pid 1366) has died.
E/SQLiteDatabase( 4895): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4895): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4895): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4895): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4895): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4895): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4895): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4895): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4895): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4895): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4895): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4895): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4895): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4895): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4895): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4895): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4895): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4895): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4895): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4895): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4895): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4895): threadid=1: thread exiting with uncaught exception (group=0x41674e30)
D/Documents( 4895): Loading roots for com.android.externalstorage.documents
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20796ms
D/WifiService(  907): Client connection lost with reason: 4
E/AndroidRuntime( 4895): FATAL EXCEPTION: main
E/AndroidRuntime( 4895): Process: com.android.documentsui, PID: 4895
E/AndroidRuntime( 4895): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4895): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4895): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4895): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4895): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4895): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4895): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4895): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4895): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4895): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4895): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4895): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4895): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4895): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4895): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4895): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4895): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4895): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4895): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4895): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4895): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4895): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4895): 	... 10 more
E/ActivityManager(  907): App crashed! Process: com.android.documentsui
I/ActivityManager(  907): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=4909 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452513556471.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  907): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  907): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  907): 	... 4 more
I/ActivityManager(  907): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4922 uid=10023 gids={50023, 1028, 1015, 1023}
D/Process ( 4895): killProcess, pid=4895
D/Process ( 4895): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Recipient 4895
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.android.documentsui (pid 4895) has died.
D/ExternalStorage( 4922): After updating volumes, found 1 active roots
W/dalvikvm( 4909): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
W/dalvikvm( 4909): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
E/SQLiteDatabase( 4881): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4881): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4881): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4881): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4881): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4881): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4881): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4881): 	at android.content.ContentProvider.query(ContentProvider,.java:869)
E/SQLiteDatabase( 4881): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4881): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4881): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4881): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4881): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4881): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4881): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4881): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4881): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4881): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4881): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4881): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4881): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4881): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4881): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4881): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4881): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4881): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4881): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
E/SQLiteDatabase( 4881): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4881): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4881): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4881): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4881): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4881): 	at java.lang.Thread.run(Thread.java:864)
I/MultiDex( 4909): VM with version 1.6.0 does not have multidex support
I/MultiDex( 4909): install
I/DeviceManagement( 4881): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4881): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4881): BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
I/Prism.ItemManager( 1274): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/MultiDex( 4909): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
I/Prism.ItemManager( 1274): loadItems() com.htc.launcher.pageview.WidgetManager@41b37db0 +
I/Prism.WidgetManager( 1274): onLoadItems() +
E/SQLiteDatabase( 4881): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4881): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4881): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4881): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4881): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4881): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4881): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
E/SQLiteDatabase( 4881): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
E/SQLiteDatabase( 4881): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 4881): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
E/SQLiteDatabase( 4881): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
E/SQLiteDatabase( 4881): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4881): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4881): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
E/SQLiteDatabase( 4881): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
E/SQLiteDatabase( 4881): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
E/SQLiteDatabase( 4881): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
E/SQLiteDatabase( 4881): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
E/SQLiteDatabase( 4881): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
E/SQLiteDatabase( 4881): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4881): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4881): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4881): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4881): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4881): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MultiDex( 4909): loading existing secondary dex files
I/MultiDex( 4909): load found 3 secondary dex files
W/DeviceManagement( 4881): WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@41adab78]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/DeviceManagement( 4881): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/DeviceManagement( 4881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/DeviceManagement( 4881): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/DeviceManagement( 4881): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/DeviceManagement( 4881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/DeviceManagement( 4881): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/DeviceManagement( 4881): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/DeviceManagement( 4881): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/DeviceManagement( 4881): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/DeviceManagement( 4881): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
W/DeviceManagement( 4881): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
W/DeviceManagement( 4881): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/DeviceManagement( 4881): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/DeviceManagement( 4881): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
W/DeviceManagement( 4881): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
W/DeviceManagement( 4881): 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
W/DeviceManagement( 4881): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
W/DeviceManagement( 4881): 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:235)
W/DeviceManagement( 4881): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
W/DeviceManagement( 4881): 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
W/DeviceManagement( 4881): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
W/DeviceManagement( 4881): 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
W/DeviceManagement( 4881): 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
W/DeviceManagement( 4881): 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
W/DeviceManagement( 4881): 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
W/DeviceManagement( 4881): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
W/DeviceManagement( 4881): 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
W/DeviceManagement( 4881): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
W/DeviceManagement( 4881): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
W/DeviceManagement( 4881): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/DeviceManagement( 4881): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/DeviceManagement( 4881): 	at android.os.Looper.loop(Looper.java:157)
W/DeviceManagement( 4881): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/DeviceManagement( 4881): WorkflowService: Stopping workflow service

```
