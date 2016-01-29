#### Test 575312430087a60_thali06_HTC-HTC One M8s Logs


```
--------- beginning of main
E/WifiTrafficPoller(  996): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  996):  packet count Tx=152 Rx=213
E/WifiStateMachine(  996): handleMessage: E msg.what=131155
E/WifiStateMachine(  996): processMsg: ConnectedState
E/WifiStateMachine(  996):  ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:1150] from screen [on:0 period:-1901927942] gl hn u24 rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  996): processMsg: L2ConnectedState
E/WifiStateMachine(  996):  L2ConnectedState !CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=1.0, 0.0, 0.0  rx=1.7 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1901927941] gl hn u24 rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  996):  get link layer stats 0
W/WifiHW  (  996): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1326): wlan0: Control interface command 'SIGNAL_POLL'
I/wpa_supplicant( 1326): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  996): fetchRssiLinkSpeedAndFrequencyNative RSSI = -61 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  996): fetchRssiLinkSpeedAndFrequencyNative rssi=-61 linkspeed=72
E/WifiConfigStore(  996): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-61 "NG700"WPA_PSK
E/WifiStateMachine(  996): calculateWifiScore freq=2412 speed=72 score=60 highRSSI  -> txbadrate=0.00 txgoodrate=0.51 txretriesrate=0.00 rxrate=0.84 userTriggerdPenalty0
E/WifiStateMachine(  996):  good link -> stuck count =0
--------- beginning of system
D/WIFI_ICON( 1216): updateWifiState: RSSI_CHANGED 3 -> 3
E/WifiStateMachine(  996):  badRSSI count0 lowRSSI count0 --> score 56
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/WifiStateMachine(  996):  isHighRSSI       ---> score=61
D/WifiWatchdogStateMachine(  996): RSSI current: 3 new: -61, 3
E/WifiStateMachine(  996): handleMessage: X
D/Process (  996): killProcessQuiet, pid=5853
I/ActivityManager(  996): Killing 5853:com.google.android.partnersetup/u0a27 (adj 15): empty #17
D/Process (  996): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
E/WifiTrafficPoller(  996): TRAFFIC_STATS_POLL true Token 11 num clients 6
E/WifiTrafficPoller(  996):  packet count Tx=152 Rx=213
I/ActivityManager(  996): Recipient 5853
,I/PMS     (  996): Going to sleep due to screen timeout (uid 1000)...
I/SensorManager(  996): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3e9f47bc
W/SensorService(  996): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  996): disable: get sensor name = Accelerometer Sensor
D/ActivityManager(  996): getTaskThumbnailLocked mainThumbnail is null, TaskRecord{9d36793 #7 A=.Prism U=0 sz=1}
W/PMS     (  996): mWirelessDisplayManager is null
W/PMS     (  996): mWirelessDisplayManager is still null
W/SensorService(  996): pid=996, uid=1000
W/SensorService(  996): Active sensors: size = 4
W/SensorService(  996): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  996): CM32181 Light sensor (handle=0x00000003, connections=1)
W/SensorService(  996): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  996): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  996): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@3e9f47bc, eanble = 0, strlen(mName) = 91
W/SensorService(  996): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  996): Listener[0] = com.android.server.display.AutomaticBrightnessController$1@377718ed
W/SensorService(  996): Listener[1] = com.htc.smartdim.sensor_eye@142f0631
W/SensorService(  996): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMN     (  996): goingToSleep
D/PMS     (  996): acquireWL(74413d0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 996 1000 null
W/PMN     (  996): goingToSleep done
I/PMS     (  996): Sleeping (uid 1000)...
D/XAN-DPS (  996): prepareColorFade 1
W/HtcLockScreen( 1216): KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
I/ActivityManager(  996): Start proc com.htc.bgp for broadcast com.htc.flexnet/.SystemIntentReceiver: pid=6376 uid=10011 gids={50011, 9997, 1028, 1015, 5001, 5011, 2001, 3003} abi=arm64-v8a
D/AlarmManager(  996): ACTION_SCREEN_ON
E/cutils-trace( 6374): Error opening trace file: Permission denied (13)
I/Adreno-EGL(  996): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL(  996): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL(  996): Build Date: 03/09/15 Mon
I/Adreno-EGL(  996): Local Branch: 
I/Adreno-EGL(  996): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL(  996): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL(  996):                  d74aa161a12b9c6fc6332151
I/AlarmManager(  996): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  996): [AlarmQueuing] done recovering
I/AlarmManager(  996): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  996): [AlarmQueuing] done EPS screen off alarm recovering
I/FeedHostManager( 1631): [onPause]
E/WifiTrafficPoller(  996): ENABLE_TRAFFIC_STATS_POLL true Token 11
E/WifiTrafficPoller(  996):  packet count Tx=152 Rx=214
E/WifiTrafficPoller(  996): notifying of data activity 1
E/WifiDataStallTracker(  996): ENABLE_DATA_MONITOR_POLL true Token 1
E/WifiStateMachine(  996): handleMessage: E msg.what=131167
E/WifiStateMachine(  996): processMsg: ConnectedState
E/WifiStateMachine(  996):  ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  996): processMsg: L2ConnectedState
E/WifiStateMachine(  996):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  996): processMsg: ConnectModeState
D/WifiDataStallTracker(  996): updateDataStallInfo: mDataStallTxRxSum={txSum=135 rxSum=116} preTxRxSum={txSum=135 rxSum=116}
D/WifiDataStallTracker(  996): updateDataStallInfo: NONE
D/WifiDataStallTracker(  996): onDataStallAlarm: Sent 0 pkts since last received, < watchdogTrigger=5
E/WifiStateMachine(  996):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  996): processMsg: DriverStartedState
E/WifiStateMachine(  996):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  996): processMsg: SupplicantStartedState
E/WifiStateMachine(  996):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  996): processMsg: DefaultState
V/SRS_Proc(  401): ParamSet string: screen_state=on
E/audio_a2dp_hw(  401): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  996):  DefaultState !CMD_SCREEN_STATE_CHANGED 1 0
E/WifiStateMachine(  996):  handleScreenStateChanged Enter: screenOn=true mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
W/WifiHW  (  996): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
D/wpa_supplicant( 1326): wlan0: Control interface command 'SET_SCREEN_ON 1'
I/wpa_supplicant( 1326): SET_SCREEN_ON:On
I/wpa_supplicant( 1326): htc_wext_set_keepalive +
I/wpa_supplicant( 1326): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1326): getPrivFuncNum +	
I/wpa_supplicant( 1326): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1326): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1326): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1326): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1326): htc_wext_set_TX_TRACKING - ret = 0
I/FeedProviderManager( 1631): onPause
D/WifiController(  996): handleMessage: E msg.what=155650
D/WifiController(  996): processMsg: DeviceActiveState
D/WifiController(  996): processMsg: StaEnabledState
D/WifiController(  996): processMsg: DefaultState
D/WifiController(  996): handleMessage: X
E/WifiStateMachine(  996): setScanAlarm true period 20000 initial delay 200mAlarmEnabledtrue
D/WifiDisplayAdapter(  996): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  996):     Client/Owner: Client
D/WifiDisplayAdapter(  996):     GroupId: 
D/WifiDisplayAdapter(  996):     Passphrase: 
D/WifiDisplayAdapter(  996):     SessionId: 0
D/WifiDisplayAdapter(  996):     IP Address: }
D/WifiStateMachine(  996): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  996): handleScreenStateChanged Exit: true
E/WifiStateMachine(  996): handleMessage: X
E/WifiStateMachine(  996): handleMessage: E msg.what=131154
E/WifiStateMachine(  996): processMsg: ConnectedState
E/WifiStateMachine(  996):  ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
E/WifiStateMachine(  996): processMsg: L2ConnectedState
E/WifiStateMachine(  996):  L2ConnectedState !CMD_ENABLE_RSSI_POLL 1 0
W/WifiHW  (  996): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/wpa_supplicant( 1326): wlan0: Control interface command 'SIGNAL_POLL'
D/WIFI_ICON( 1216): WifiActivity: 1
I/wpa_supplicant( 1326): environment dirty rate=0 [0][0][0]
E/WifiStateMachine(  996): fetchRssiLinkSpeedAndFrequencyNative RSSI = -61 abnormalRssiCnt = 0 newLinkSpeed = 72
E/WifiStateMachine(  996): fetchRssiLinkSpeedAndFrequencyNative rssi=-61 linkspeed=72
E/WifiConfigStore(  996): updateConfiguration freq=2412 BSSID=c0:ff:d4:d3:aa:48 RSSI=-61 "NG700"WPA_PSK
E/WifiStateMachine(  996): handleMessage: X
E/WifiStateMachine(  996): handleMessage: E msg.what=131127
I/FeedHostManager( 1631): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@27b985a5
E/WifiStateMachine(  996): processMsg: ConnectedState
E/WifiStateMachine(  996):  ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  996): processMsg: L2ConnectedState
E/WifiStateMachine(  996):  L2ConnectedState !CMD_ENABLE_ALL_NETWORKS 0 0
E/WifiStateMachine(  996): processMsg: ConnectModeState
E/WifiStateMachine(  996):  ConnectModeState !CMD_ENABLE_ALL_NETWORKS 0 0
D/StatusBar.NetworkController( 1216): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/WifiStateMachine(  996): handleMessage: X
E/WifiStateMachine(  996): handleMessage: E msg.what=131129
E/WifiStateMachine(  996): processMsg: ConnectedState
D/NetworkPolicy(  996): updateScreenOn: false
E/WifiStateMachine(  996):  ConnectedState !CMD_CLEAR_BLACKLIST 0 0
V/NetworkPolicy(  996): updateIfacesLocked()
E/WifiStateMachine(  996): processMsg: L2ConnectedState
E/WifiStateMachine(  996):  L2ConnectedState !CMD_CLEAR_BLACKLIST 0 0
E/WifiStateMachine(  996): processMsg: ConnectModeState
E/WifiStateMachine(  996):  ConnectModeState !CMD_CLEAR_BLACKLIST 0 0
W/WifiHW  (  996): QCOM Debug wifi_send_command "IFNAME=wlan0 BLACKLIST clear"
I/SocialFeedProvider( 1631): +onPause
I/SocialFeedProvider( 1631): -onPause
D/wpa_supplicant( 1326): wlan0: Control interface command 'BLACKLIST clear'
E/wpa_supplicant( 1326): wlan0: BLACKLIST CLEAR 
D/WifiMonitor(  996): Event [IFNAME=wlan0 BLACKLIST CLEAR ]
D/NetworkManagementService(  996): isBandwidthControlEnabled: doneSignal.getCount()= 0
E/WifiMonitor(  996): WifiMonitor:wlan0 cnt=34 dispatchEvent: BLACKLIST CLEAR 
E/WifiStateMachine(  996): handleMessage: X
W/HtcSystemUPManager(  996): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
D/PMS     (  996): releaseWL(74413d0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
W/ResourcesManager( 6376): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/GpsLocationProvider(  996): receive broadcast intent, action: android.intent.action.SCREEN_ON
I/IntentController( 1216): receive(android.intent.action.SCREEN_ON,1,false)
D/CustomizationManager( 6374): ====startRecUseTime====
D/htc.customization.log.level( 6374):  is 
W/CustomizationLogLevel( 6374): Level value is invalid, use default level 2
D/PMS     (  996): acquireWL(2e9e9cfc): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
I/CalendarProvider2( 6376): Created com.android.providers.calendar.CalendarAlarmManager@efcb48f(com.htc.providers.calendar.HtcCalendarProvider@1636a31c)
D/PMS     (  996): acquireWL(14b68ce8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  996): releaseWL(2e9e9cfc): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
D/PMS     (  996): releaseWL(14b68ce8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms}
D/CalendarProvider2( 6376): wait start:true
D/AlarmManager(  996): ACTION_SCREEN_OFF
I/AlarmManager(  996): [AlarmQueuing] screen off now: 
I/AlarmManager(  996): [AlarmQueuing] data connection: true
I/AlarmManager(  996): [AlarmQueuing] wifi connection: true
E/WifiTrafficPoller(  996): ENABLE_TRAFFIC_STATS_POLL false Token 12
D/WifiDataStallTracker(  996): stopDataStallAlarm 
E/WifiDataStallTracker(  996): ENABLE_DATA_MONITOR_POLL false Token 2
E/WifiStateMachine(  996): handleMessage: E msg.what=131167
E/WifiStateMachine(  996): processMsg: ConnectedState
E/WifiStateMachine(  996):  ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  996): processMsg: L2ConnectedState
E/WifiStateMachine(  996):  L2ConnectedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  996): processMsg: ConnectModeState
E/WifiStateMachine(  996):  ConnectModeState !CMD_SCREEN_STATE_CHANGED 0 0
V/SRS_Proc(  401): ParamSet string: screen_state=off
E/WifiStateMachine(  996): processMsg: DriverStartedState
E/audio_a2dp_hw(  401): adev_set_parameters: ERROR: set param called even when stream out is null
E/WifiStateMachine(  996):  DriverStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  996): processMsg: SupplicantStartedState
E/WifiStateMachine(  996):  SupplicantStartedState !CMD_SCREEN_STATE_CHANGED 0 0
E/WifiStateMachine(  996): processMsg: DefaultState
E/WifiStateMachine(  996):  DefaultState !CMD_SCREEN_STATE_CHANGED 0 0
D/WifiController(  996): handleMessage: E msg.what=155651
D/XAN-DPS (  996): prepareColorFade done
D/WifiController(  996): processMsg: DeviceActiveState
D/WifiController(  996): processMsg: StaEnabledState
D/XAN-DPS (  996): setBrightness to 0
D/WifiController(  996): processMsg: DefaultState
D/NetworkPolicy(  996): updateScreenOn: false
D/WifiController(  996): handleMessage: X
V/NetworkPolicy(  996): updateIfacesLocked()
E/WifiStateMachine(  996):  handleScreenStateChanged Enter: screenOn=false mCurrentScanAlarmMs = 20000 mUserWantsSuspendOpt=false state ConnectedState suppState:CompletedState
D/WifiDisplayAdapter(  996): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  996):     Client/Owner: Client
D/WifiDisplayAdapter(  996):     GroupId: 
D/WifiDisplayAdapter(  996):     Passphrase: 
D/WifiDisplayAdapter(  996):     SessionId: 0
D/WifiDisplayAdapter(  996):     IP Address: }
W/WifiHW  (  996): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
D/NetworkManagementService(  996): isBandwidthControlEnabled: doneSignal.getCount()= 0
D/wpa_supplicant( 1326): wlan0: Control interface command 'SET_SCREEN_ON 0'
I/wpa_supplicant( 1326): SET_SCREEN_ON:Off
I/wpa_supplicant( 1326): htc_wext_set_keepalive +
I/wpa_supplicant( 1326): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1326): getPrivFuncNum +	
I/wpa_supplicant( 1326): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1326): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1326): get_ip_address source addr = c0a80182
I/wpa_supplicant( 1326): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1326): htc_wext_set_keepalive - ret = 0
E/WifiStateMachine(  996): setScanAlarm false period 20000 initial delay 0mAlarmEnabledtrue
D/WifiStateMachine(  996): backgroundScan enabled=true startBackgroundScanIfNeeded:false
E/WifiStateMachine(  996): handleScreenStateChanged Exit: false
E/WifiStateMachine(  996): handleMessage: X
E/WifiStateMachine(  996): handleMessage: E msg.what=131154
E/WifiStateMachine(  996): processMsg: ConnectedState
E/WifiStateMachine(  996):  ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  996): processMsg: L2ConnectedState
E/WifiStateMachine(  996):  L2ConnectedState CMD_ENABLE_RSSI_POLL 0 0
E/WifiStateMachine(  996): handleMessage: X
I/SensorManager(  996): unregisterListenerImpl++: listener = com.android.server.display.AutomaticBrightnessController$1@377718ed
W/SensorService(  996): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  996): disable: get sensor name = CM32181 Light sensor
I/DisplayManagerService(  996): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 442.451 x 443.345 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/DotMatrix( 1327): [EventService]  onDisplayChanged: 0
V/ActivityManager(  996): Display changed displayId=0
D/DotMatrix( 1327): [EventService] mbHDMIConnect: false, mCoverOn:false
W/SensorService(  996): pid=996, uid=1000
W/SensorService(  996): Active sensors: size = 3
W/SensorService(  996): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  996): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  996): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  996): SensorService::listenerSensor++: mName = com.android.server.display.AutomaticBrightnessController$1@377718ed, eanble = 0, strlen(mName) = 67
W/SensorService(  996): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  996): Listener[0] = com.htc.smartdim.sensor_eye@142f0631
W/SensorService(  996): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/CustomizationManager( 6374):  Read ACC file spent 0.038 (s)
E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
D/CIDMapFileReader( 6374): Parsing tag item name = HTC__001
D/CIDMapFileReader( 6374): Parsing tag item name = HTC__102
D/CIDMapFileReader( 6374): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 6374): Parsing tag item name = HTC__032
D/CIDMapFileReader( 6374): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 6374): Parsing tag item name = HTC__002
D/CIDMapFileReader( 6374): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 6374): full path : /system/customize/CID/HTC__102.xml
I/CustomizationCIDLoader( 6374): Parsing tag category name = system
I/CustomizationCIDLoader( 6374): Parsing tag category name = application
I/CustomizationCIDLoader( 6374): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 6374): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 6374): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 6374): Parsing tag category name = Settings
I/CustomizationCIDLoader( 6374): Parsing tag category name = ACC
I/CustomizationCIDLoader( 6374): add string-array item, value = 42507
I/CustomizationCIDLoader( 6374): add string-array item, value = 21902
I/CustomizationCIDLoader( 6374): add string-array item, value = 26006:26001.26002.26003
I/CustomizationCIDLoader( 6374): add string-array item, value = 23420
I/CustomizationCIDLoader( 6374): add string-array item, value = 22299
I/CustomizationCIDLoader( 6374): add string-array item, value = 24002
I/CustomizationCIDLoader( 6374): add string-array item, value = 23210
I/CustomizationCIDLoader( 6374): add string-array item, value = 23205
I/CustomizationCIDLoader( 6374): add string-array item, value = 23806
I/CustomizationCIDLoader( 6374): add string-array item, value = 23430
I/CustomizationCIDLoader( 6374): add string-array item, value = 23408
I/CustomizationCIDLoader( 6374): add string-array item, value = 27205
I/CustomizationCIDLoader( 6374): add string-array item, value = 42507:C:1:0
I/CustomizationCIDLoader( 6374): add string-array item, value = 21902:C:1:0
I/CustomizationCIDLoader( 6374): add string-array item, value = 26006:D:1:0
I/CustomizationCIDLoader( 6374): add string-array item, value = 23420:D:0:0
I/CustomizationCIDLoader( 6374): add string-array item, value = 22299:D:0:0
I/CustomizationCIDLoader( 6374): add string-array item, value = 24002:D:0:0
I/CustomizationCIDLoader( 6374): add string-array item, value = 23210:D:2:0
I/CustomizationCIDLoader( 6374): add string-array item, value = 23205:D:0:0
I/CustomizationCIDLoader( 6374): add string-array item, value = 23806:D:0:0
I/CustomizationCIDLoader( 6374): add string-array item, value = 23430:C:1:0
I/CustomizationCIDLoader( 6374): add string-array item, value = 23408:C:1:0
I/CustomizationCIDLoader( 6374): add string-array item, value = 27205:C:1:0
D/CustomizationManager( 6374):  Read CID file spent 0.091 (s)
D/CustomizationManager( 6374):  All configurations done spent 0.092 (s)
D/CalendarProvider2( 6376): wait end:false
I/ActivityManager(  996): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=6421 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 5001, 5011, 3006, 1007, 1023, 5006} abi=arm64-v8a
I/SensorManager( 1216): registerListenerImpl: listener = com.htc.sense.easyaccessservice.SensorHubService@3974f32e, sensor = {Sensor name="hTC Gesture Motion HIDI", vendor="hTC Corp.", version=1, type=10, maxRange=200.0, resolution=1.0, power=0.2, minDelay=0}, delay = 200000, handler = null
W/SensorService(  996): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  996): enable: get sensor name = hTC Gesture Motion HIDI
W/SensorService(  996): pid=1216, uid=10041
W/SensorService(  996): Active sensors: size = 4
W/SensorService(  996): Accelerometer Sensor (handle=0x00000000, connections=1)
W/SensorService(  996): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  996): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  996): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  996): SensorService::listenerSensor++: mName = com.htc.sense.easyaccessservice.SensorHubService@3974f32e, eanble = 1, strlen(mName) = 57
W/SensorService(  996): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  996): Listener[0] = com.htc.smartdim.sensor_eye@142f0631
W/SensorService(  996): Listener[1] = com.htc.sense.easyaccessservice.SensorHubService@3974f32e
W/SensorService(  996): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  996): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6374 on display 0
W/asset   (  996): Copying FileAsset 0x558de113b0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
D/PMS     (  996): acquireHCC(17282cdf): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 996 1000 null
D/PMS     (  996): acquireHCC(2d413d2c): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 996 1000 null
I/ActivityManager(  996): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6444 uid=10366 gids={50366, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/art     (  416): Explicit concurrent mark sweep GC freed 8687(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 230us total 16.351ms
I/art     (  416): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 222us total 14.058ms
I/art     (  416): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 208us total 13.652ms
D/DotMatrix( 1327): [EventService] getTotalRam: 1842 Mb
E/WifiTrafficPoller(  996): TRAFFIC_STATS_POLL false Token 13 num clients 6
E/qdutils (  385): int qdutils::getHDMINode(): Failed to open fb node 2
D/PMS     (  996): Setting HAL interactive mode to false
E/qdutils (  385): int qdutils::getHDMINode(): Failed to find HDMI node
D/PMS     (  996): Setting HAL interactive mode to false done
D/SurfaceControl(  996): Excessive delay in setPowerMode(): 294ms
D/PMS     (  996): Setting HAL auto-suspend mode to true
W/HtcSystemUPManager(  996): HtcSystemUPHandler The policy is disabled. AppId: UTD_BI, category: C0006
D/PMS     (  996): Setting HAL auto-suspend mode done
I/InputMethodManagerService(  996): screenObserver, isScreenOn=false
D/StatusBarManagerService(  996): swetImeWindowStatus vis=0 backDisposition=0
I/InputMethodManagerService(  996): Disable input method client, pid=1631
D/HABCtrl (  996): TPE algorithm. remove timeout.
D/PMS     (  996): OOBE c monitor 11
D/PMS     (  996): acquireWL(2d8cb7fb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 996 1000 null
I/BatteryService(  996): n_update end
D/PMS     (  996): releaseWL(2d8cb7fb): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  996): updateBatteryInfo
D/UsbnetService(  996): BroadcastReceiver::onReceive+
D/NotificationService(  996): plugged=true pluggin=true
D/UsbnetService(  996): onReceive BATTERY_CHANGED
D/PMS     (  996): runPSCheck
D/UsbnetService(  996):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  996): Checking...
D/UsbnetService(  996): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  996): >> updateStatus
D/WifiController(  996): handleMessage: E msg.what=155652
I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1216): closing low battery warning: level=100
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/WifiController(  996): battery changed pluggedType: 2
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3072): Disconnected process message: 10, size: 0
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  996): processMsg: DeviceActiveState
D/WifiController(  996): processMsg: StaEnabledState
D/WifiController(  996): processMsg: DefaultState
D/WifiController(  996): handleMessage: X
I/HtcPowerSaver(  996): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  996): << updateStatus
I/PhoneStatusBar( 1216): setImeWindowStatus(false,false)
,D/NfcService( 1583): ScreenObserver: OFF
,D/NfcService( 1583): applyRouting - 0
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true
,I/art     (  996): Explicit concurrent mark sweep GC freed 42608(2MB) AllocSpace objects, 4(272KB) LOS objects, 33% free, 17MB/25MB, paused 1.333ms total 173.026ms
D/NfcService( 1583): applyRouting -2
D/PMS     (  996): acquireWL(c1b0018): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1583 1027 null
D/NfcService( 1583): applyRouting
D/PMS     (  996): releaseWL(c1b0018): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/NfcService( 1583): Ignore this applyRouting...
V/ActivityManager(  996): Display changed displayId=0
D/DotMatrix( 1327): [EventService]  onDisplayChanged: 0
D/DotMatrix( 1327): [EventService] mbHDMIConnect: false, mCoverOn:false
,I/TrimMemoryManager( 1631): [trimMemory] 20,
,D/GpsLocationProvider(  996): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,W/ContextImpl( 6421): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/ContactMessageStore( 1564): start background delete task...
,I/IntentController( 1216): receive(android.intent.action.SCREEN_OFF,1,false)
,D/ContactMessageStore( 1564): size: 0 , 0,
D/ContactMessageStore( 1564): Background delete complete
,W/ContextImpl( 6421): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
,D/PowerUsageList:PowerUsageHelper( 6421): MY_DEBUG = false
,W/asset   ( 6444): Copying FileAsset 0xaca009b8 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
,D/PMS     (  996): acquireWL(15e4d8d7): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  996): releaseWL(15e4d8d7): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10024 com.google.android.gms}
,D/SmartSyncUtils( 6421): isEpsOn(), nState = 0
D/PMS     (  996): acquireWL(19cc05c4): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1833 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  996): releaseWL(19cc05c4): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  996): acquireWL(1f385cad): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6421 1000 null
,I/InputManager(  996): Cancel all due to getting PMS screen off broadcast. ActualScreenOn=false,
I/IntentController( 1216): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/PMS     (  996): releaseWL(1f385cad): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl(  996): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2712 
,D/SmartDim(  996): Init customizeScreenOffDelayClass error
,I/RemoteViews( 1216): setHTCTheme(com.htc.updater,true,33751145)
,W/ContextImpl( 6421): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,I/RemoteViews( 1216): apply : com.htc.updater 0 8 1 36
W/ContextImpl( 6421): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:22 android.app.ActivityThread.handleReceiver:2712 
D/SmartSyncUtils( 6421): isEpsOn(), nState = 0
D/SmartSyncUtils( 6421): isEpsOn(), nState = 0
W/ContextImpl( 6421): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2712 
W/ContextImpl(  996): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2712 
I/SensorManager(  996): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@142f0631
W/SensorService(  996): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  996): disable: get sensor name = Accelerometer Sensor
,W/SensorService(  996): pid=996, uid=1000
W/SensorService(  996): Active sensors: size = 3
W/SensorService(  996): CM36686 Proximity sensor (handle=0x00000004, connections=1)
W/SensorService(  996): Significant Motion (handle=0x0000000d, connections=1),
W/SensorService(  996): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  996): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@142f0631, eanble = 0, strlen(mName) = 36
W/SensorService(  996): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  996): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@3974f32e
W/SensorService(  996): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  996): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  996): disable: get sensor name = CM36686 Proximity sensor
,W/SensorService(  996): pid=996, uid=1000
W/SensorService(  996): Active sensors: size = 2
W/SensorService(  996): Significant Motion (handle=0x0000000d, connections=1)
W/SensorService(  996): hTC Gesture Motion HIDI (handle=0x00000013, connections=1)
W/SensorService(  996): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@142f0631, eanble = 0, strlen(mName) = 36
W/SensorService(  996): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  996): Listener[0] = com.htc.sense.easyaccessservice.SensorHubService@3974f32e
W/SensorService(  996): void android::SensorService::listenerSensor(const char*, int32_t)--:,
I/ClockController( 1216): stop clock update:screen off
,I/SensorManager(  996): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@142f0631
,I/ActivityManager(  996): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=6477 uid=10046 gids={50046, 9997, 3003} abi=arm64-v8a
,E/ActivityThread(  996): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@26cec116 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  996): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@26cec116 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  996): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
E/ActivityThread(  996): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
E/ActivityThread(  996): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
E/ActivityThread(  996): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
E/ActivityThread(  996): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:495)
E/ActivityThread(  996): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  996): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  996): 	at android.app.Service.onStartCommand(Service.java:458)
E/ActivityThread(  996): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3072)
E/ActivityThread(  996): 	at android.app.ActivityThread.access$2100(ActivityThread.java:144)
E/ActivityThread(  996): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1470)
E/ActivityThread(  996): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  996): 	at android.os.Looper.loop(Looper.java:155)
E/ActivityThread(  996): ,	at com.android.server.SystemServer.run(SystemServer.java:324)
E/ActivityThread(  996): 	at com.android.server.SystemServer.main(SystemServer.java:225)
E/ActivityThread(  996): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(  996): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(  996): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1029)
E/ActivityThread(  996): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:824)
,I/PowerUsageList:PowerUsageHelper( 6421): PowerProfile::POWER_SCREEN_FULL = 154.8
,I/WebViewFactory( 6444): Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,D/PowerUsageList:BatterySipperExt( 6421): gen(), null == sipper.uidObj, userId = 0
,D/SmartSyncUtils( 6421): getMobilePolicyEnabled, result = true
D/Process (  996): killProcessQuiet, pid=6154
I/ActivityManager(  996): Killing 6154:com.htc.cs.dm/u0a99 (adj 15): empty #17
D/Process (  996): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.removeContentProvider:10141 
,E/WifiTrafficPoller(  996): ADD_CLIENT: 7,
D/WifiService(  996): New client listening to asynchronous messages
,I/LibraryLoader( 6444): Time to load native libraries: 10 ms (timestamps 3845-3855),
,I/LibraryLoader( 6444): Expected native library version number "",actual native library version number "",
,V/WebViewChromiumFactoryProvider( 6444): Binding Chromium to main looper Looper (main, tid 1) {efcb48f},
I/LibraryLoader( 6444): Expected native library version number "",actual native library version number ""
,I/chromium( 6444): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6444): Initializing chromium process, singleProcess=true,
,W/art     ( 6444): Attempt to remove local handle scope entry from IRT, ignoring,
,E/SysUtils( 6444): ApplicationContext is null in ApplicationStatus,
,I/ActivityManager(  996): Recipient 6154
,W/chromium( 6444): [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,E/libEGL  ( 6444): validate_display:255 error 3008 (EGL_BAD_DISPLAY),
E/libEGL  ( 6444): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6444): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
I/Adreno-EGL( 6444): OpenGL ES Shader Compiler Version: E031.25.03.01
I/Adreno-EGL( 6444): Build Date: 03/09/15 Mon
I/Adreno-EGL( 6444): Local Branch: ,
I/Adreno-EGL( 6444): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
I/Adreno-EGL( 6444): Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
I/Adreno-EGL( 6444):                  d74aa161a12b9c6fc6332151
,D/PowerUsageList:PowerUsageHelper( 6421): MY_DEBUG = false,
,W/System.err(  996): java.lang.Throwable: stack dump
W/System.err(  996): 	at java.lang.Thread.dumpStack(Thread.java:490)
W/System.err(  996): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
,W/System.err(  996): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  996): 	at android.os.Binder.execTransact(Binder.java:454)
D/BluetoothManagerService(  996): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  996): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20da9f48:true
,D/BluetoothAdapter( 6444): 538577579: getState(). Returning 12,
,E/WifiTrafficPoller(  996): TRAFFIC_STATS_POLL false Token 13 num clients 7,
,W/art     ( 6444): Attempt to remove local handle scope entry from IRT, ignoring,
,W/AwContents( 6444): onDetachedFromWindow called when already detached. Ignoring,
I/ActivityManager(  996): Killing 6181:com.htc.providers.settings:remote/u0a13 (adj 15): empty #17
D/Process (  996): killProcessQuiet, pid=6181
D/Process (  996): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,D/SystemWebViewEngine( 6444): CordovaWebView is running on device made by: HTC
,I/ActivityManager(  996): Recipient 6181
,W/ActivityManager(  996): Activity pause timeout for ActivityRecord{3fa90f7e u0 com.test.thalitest/.MainActivity t8}
,W/HtcSystemUPManager(  996): HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,W/art     ( 6444): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6444): Attempt to remove local handle scope entry from IRT, ignoring
,I/CalendarProvider2( 6376): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 6376): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  996): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=6525 uid=10010 gids={50010, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  996): Killing 5947:com.google.android.gms:car/u0a24 (adj 15): empty #17
D/Process (  996): killProcessQuiet, pid=5947
,D/Process (  996): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  996): Recipient 5947
,W/ResourcesManager( 6525): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/chromium( 6444): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/CalendarApplication( 6525): onCreate
,D/ProviderChangeReceiver( 6525): ---------------------------------------------------
D/ProviderChangeReceiver( 6525): ProviderChangeReceiver onReceive, start HtcAlertService to update notification!
,D/Process (  996): killProcessQuiet, pid=6210,
,I/ActivityManager(  996): Killing 6210:com.google.android.apps.docs/u0a101 (adj 15): empty #17
D/Process (  996): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.BroadcastQueue.processNextBroadcast:706 
,D/HtcAlertService( 6525): start to updateAlertNotification!
,D/StatusBarManagerService(  996): setSystemUiVisibility(0xc0000000)
,D/StatusBarManagerService(  996): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  996): hiding MENU key
D/StatusBarManagerService(  996): setSystemUiVisibility(0x0)
D/StatusBarManagerService(  996): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  996): hiding MENU key
,D/FindExtension( 6444): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,I/InputMethodManager( 6444): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@801a811, mServedView=org.apache.cordova.engine.SystemWebView{380fed76 VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@18663f77,
E/WifiStateMachine(  996): handleMessage: E msg.what=131155,
E/WifiStateMachine(  996): processMsg: ConnectedState
I/InputMethodManagerService(  996): Disable input method client, pid=1631
E/WifiStateMachine(  996):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2999] from screen [on:0 period:-1901924924] gl hn u24 rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0,
,D/StatusBarManagerService(  996): swetImeWindowStatus vis=0 backDisposition=0
E/WifiStateMachine(  996): processMsg: L2ConnectedState
I/PhoneStatusBar( 1216): setImeWindowStatus(false,false)
E/WifiStateMachine(  996):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1901924922] gl hn u24 rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  996): handleMessage: X
,W/IInputConnectionWrapper( 6444): reportFullscreenMode on inactive InputConnection
,I/ActivityManager(  996): Recipient 6210
W/BindingManager( 6444): Cannot call determinedVisibility() - never saw a connection for the pid: 6444
,W/XT9_C   ( 1395): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1395): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1395): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1395): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,D/PMS     (  996): releaseWL(238db8b): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,D/JsMessageQueue( 6444): Set native->JS mode to OnlineEventsBridgeMode,
,I/ActivityManager(  996): Displayed com.test.thalitest/.MainActivity: +1s86ms (total +1s413ms)
,D/HtcAlertService( 6525): No fired or scheduled alerts
D/HtcAlertUtils( 6525): -- cancelReminderNotification --
,D/HtcAlertUtils( 6525): broadcastExistReminder!
,D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/jxcore_app_log( 6444): JniHelper::setJavaVM(0xab8948f8), pthread_self() = -1398167224,
,I/chromium( 6444): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41),
,D/PMS     (  996): releaseHCC(17282cdf): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
D/PMS     (  996): releaseHCC(2d413d2c): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,E/WifiDataStallTracker(  996): DATA_MONITOR_POLL false Token 3,
,W/jxcore-log( 6444): Initializing JXcore engine
,W/jxcore-log( 6444): JXcore engine is ready
,W/jxcore-log( 6444): Starting JXcore engine
,W/jxcore-log( 6444): Platform android,
W/jxcore-log( 6444): 
W/jxcore-log( 6444): Process ARCH arm
W/jxcore-log( 6444): 
,I/jxcore-log( 6444): JXcore Cordova bridge is ready!,
I/jxcore-log( 6444): 
W/jxcore-log( 6444): JXcore engine is started
,E/jxcore  ( 6444): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 6444): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 6444): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37),
,D/Process (  996): killProcessQuiet, pid=5584,
I/ActivityManager(  996): Killing 5584:com.android.defcontainer/u0a15 (adj 15): empty #17
D/Process (  996): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,E/WifiStateMachine(  996): handleMessage: E msg.what=131155
E/WifiStateMachine(  996): processMsg: ConnectedState
,E/WifiStateMachine(  996):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1481] from screen [on:0 period:-1901923441] gl hn u24 rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
E/WifiStateMachine(  996): processMsg: L2ConnectedState
,E/WifiStateMachine(  996):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" c0:ff:d4:d3:aa:48 rssi=-61 f=2412 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1901923439] gl hn u24 rssi=-56 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,E/WifiStateMachine(  996): handleMessage: X
,I/ActivityManager(  996): Recipient 5584
,W/PluginManager( 6444): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 133ms. Plugin should use CordovaInterface.getThreadPool().
,D/HtcUPManager( 1216): HtcUPServiceProxy onTrimMemory() has been called. Memory Level: 60
,E/WifiDataStallTracker(  996): DATA_MONITOR_POLL false Token 3,
,D/ContactMessageStore( 1564): MSG_NOTIFY_CS_TO_SYNC >>,
D/ContactMessageStore( 1564): MSG_NOTIFY_CS_TO_SYNC <<
,W/Atfwd_Sendcmd(  463): AtCmdFwd service not published, waiting... retryCnt : 1,
,W/Atfwd_Sendcmd(  463): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/Process (  996): killProcessQuiet, pid=5490
I/ActivityManager(  996): Killing 5490:com.htc.musicenhancer/u0a49 (adj 15): empty #17
,D/Process (  996): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  996): Recipient 5490
,D/PMS     (  996): acquireWL(1ce5b58d): PARTIAL_WAKE_LOCK  *alarm* 0x1 996 1000 WorkSource{10024},
V/AlarmManager(  996): sending alarm PendingIntent{32d7342: PendingIntentRecord{1a845f53 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143684, Int=0
,D/PMS     (  996): releaseWL(1ce5b58d): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024},
,W/Atfwd_Sendcmd(  463): AtCmdFwd service not published, waiting... retryCnt : 3
,D/GpsLocationProvider(  996): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  996): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  996): acquireWL(2c9a1090): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 996 1000 null,
,D/libc    (  996): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
D/libc    (  996): [NET] android_getaddrinfofornet-, err=8
D/libc    (  996): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
,D/libc    (  996): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    (  996): [NET] android_getaddrinfo_proxy+
D/libc    (  996): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS,
D/libc    (  996): [NET] android_getaddrinfo_proxy-, success
,D/libc    (  996): [NET] android_getaddrinfofornet+,hn 13(0x35342e3233302e),sn(),hints(known),family 0,flags 4
,D/libc    (  996): [NET] android_getaddrinfofornet-, SUCCESS
,D/GpsLocationProvider(  996): [handleDownloadXtraData] calling native_inject_xtra_data,
,D/GpsLocationProvider(  996): [reportHTCStatus] eventMask = 3 , status = 0,
D/GpsLocationProvider(  996): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
D/PMS     (  996): acquireWL(3e37a5bc): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 996 1000 null
D/GpsLocationProvider(  996):  [handleDownloadXtraData]inject done.
D/GpsLocationProvider(  996): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
D/PMS     (  996): releaseWL(2c9a1090): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null
D/PMS     (  996): releaseWL(3e37a5bc): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  996): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,W/Atfwd_Sendcmd(  463): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/PMS     (  996): acquireWL(1d990945): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 996 1000 null
I/BatteryService(  996): n_update end
I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  996): releaseWL(1d990945): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/NotificationService(  996): plugged=true pluggin=true
D/UsbnetService(  996): BroadcastReceiver::onReceive+
D/HtcPowerSaver(  996): updateBatteryInfo
D/UsbnetService(  996): onReceive BATTERY_CHANGED
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  996): runPSCheck
D/UsbnetService(  996):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  996): Checking...
D/UsbnetService(  996): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  996): >> updateStatus
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  996): battery changed pluggedType: 2
D/WifiController(  996): handleMessage: E msg.what=155652
D/PowerUI ( 1216): closing low battery warning: level=100
D/WifiController(  996): processMsg: DeviceActiveState
D/WifiController(  996): processMsg: StaEnabledState
I/HtcPowerSaver(  996): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  996): processMsg: DefaultState
I/HtcPowerSaver(  996): << updateStatus
D/WifiController(  996): handleMessage: X
D/HeadsetStateMachine( 3072): Disconnected process message: 10, size: 0
,D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1564): switchBindHtcMsgCursor: null
,W/Atfwd_Sendcmd(  463): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  996): acquireWL(2b5a289a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 996 1000 WorkSource{1000}
,V/AlarmManager(  996): sending alarm PendingIntent{27a5aab2: PendingIntentRecord{13381a03 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=146209, Int=0
V/AlarmManager(  996): sending alarm PendingIntent{2ede65cb: PendingIntentRecord{3db761a8 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1454092041107, Int=0
V/AlarmManager(  996): sending alarm PendingIntent{16c5f4c1: PendingIntentRecord{11223466 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=202811, Int=0
V/AlarmManager(  996): sending alarm PendingIntent{246b93a7: PendingIntentRecord{22f4f054 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=191232, Int=0
D/PMS     (  996): acquireWL(387c1bfd): PARTIAL_WAKE_LOCK  *backup* 0x1 996 1000 null
,D/PMS     (  996): acquireWL(d30f2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1872 10024 WorkSource{10024 com.google.android.gms}
,W/BackupManagerService(  996): Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
,E/BackupManagerService(  996): Requested init for com.google.android.gms.backup.BackupTransportService but not found
,D/PMS     (  996): releaseWL(387c1bfd): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,D/PMS     (  996): releaseWL(2b5a289a): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1216): Weather sync is On,
W/WeatherTimeKeeper( 1216): [refreshWeatherData] no weather data
,D/PMS     (  996): acquireWL(17b3c343): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1872 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  996): releaseWL(d30f2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/PMS     (  996): releaseWL(17b3c343): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  996): acquireWL(2de7cdb5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1872 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  996): releaseWL(2de7cdb5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,D/PMS     (  996): acquireWL(3b5dec4a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1872 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  996): releaseWL(3b5dec4a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  996): acquireWL(303857bb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1872 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  996): acquireWL(85a84d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1872 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  996): acquireWL(35968316): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1872 10024 WorkSource{10024 com.google.android.gms},
,D/PMS     (  996): releaseWL(303857bb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,I/VacuumService( 1872): Vacuum at: now=1454092076841 tag=VacuumService
,I/GoogleURLConnFactory( 1872): Using platform SSLCertificateSocketFactory,
,D/PMS     (  996): releaseWL(85a84d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
D/PMS     (  996): acquireWL(395f1684): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1872 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  996): releaseWL(395f1684): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  996): acquireWL(1470fe6d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1872 10024 WorkSource{10024 com.google.android.gms}
,W/Uploader( 1872): No account for auth token provided,
,D/PMS     (  996): releaseWL(1470fe6d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/libc    ( 1872): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1872): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 1872): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 1872): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 1872): [NET] android_getaddrinfo_proxy+
D/libc    ( 1872): [NET] android_getaddrinfo_proxy get netid:0
D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
,D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
D/libc    ( 1872): [NET] android_getaddrinfo_proxy-, success
,D/libc    ( 1872): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
D/libc    ( 1872): [NET] android_getaddrinfofornet-, err=8
,D/libc    ( 1872): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
D/libc    ( 1872): [NET] android_getaddrinfofornet-, err=8
,W/Uploader( 1872): No account for auth token provided,
,W/Uploader( 1872): No account for auth token provided,
,W/Uploader( 1872):  no longer exists, so no auth token.
,W/Uploader( 1872): No account for auth token provided,
,I/GLSUser ( 1872): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1872): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1872): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1872): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Uploader( 1872): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1872): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1872): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1872): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1872): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1872): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1872): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1872): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1872): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1872): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1872): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1872): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1872): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,D/DotMatrix( 1327): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1327): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1216): reapply : com.google.android.gms 3 40
,D/PMS     (  996): releaseWL(35968316): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  996): acquireWL(3ed3ddc6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1872 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  996): releaseWL(3ed3ddc6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/PMS     (  996): acquireWL(1aebf187): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1872 10024 WorkSource{10024 com.google.android.gms}
,D/PMS     (  996): releaseWL(1aebf187): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,D/HtcUPManager( 1216): HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,D/HtcUPManager( 1216): HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
,D/HtcAppUPService( 1544): HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@3aff2986
I/ActivityManager(  996): Killing 5339:com.htc.mediamanager/u0a28 (adj 15): empty #17
D/Process (  996): killProcessQuiet, pid=5339
,D/Process (  996): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  996): Recipient 5339
,W/Atfwd_Sendcmd(  463): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  996): acquireWL(2f7728b4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 996 1000 null
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
I/BatteryService(  996): n_update end
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  996): releaseWL(2f7728b4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  996): updateBatteryInfo
D/UsbnetService(  996): BroadcastReceiver::onReceive+
D/UsbnetService(  996): onReceive BATTERY_CHANGED
D/NotificationService(  996): plugged=true pluggin=true
D/UsbnetService(  996):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1216): closing low battery warning: level=100
D/UsbnetService(  996): BroadcastReceiver::onReceive-
D/PMS     (  996): runPSCheck
I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  996): Checking...
D/WifiController(  996): handleMessage: E msg.what=155652
I/HtcPowerSaver(  996): >> updateStatus
D/HeadsetStateMachine( 3072): Disconnected process message: 10, size: 0
D/WifiController(  996): battery changed pluggedType: 2
D/WifiController(  996): processMsg: DeviceActiveState
,D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  996): processMsg: StaEnabledState
I/HtcPowerSaver(  996): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  996): processMsg: DefaultState
I/HtcPowerSaver(  996): << updateStatus
D/WifiController(  996): handleMessage: X
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  463): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  463): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  463): AtCmdFwd service not published, waiting... retryCnt : 4
,D/wpa_supplicant( 1326): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1326): wlan0: BSS: Remove id 3 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 1326): wlan0: BSS: Remove id 2 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/WifiMonitor(  996): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
E/WifiMonitor(  996): WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a
D/WifiMonitor(  996): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 c2:ff:d4:d3:aa:48]
E/WifiMonitor(  996): WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 c2:ff:d4:d3:aa:48
D/WifiMonitor(  996): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97]
E/WifiMonitor(  996): WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 a0:c5:62:7a:49:97
,W/Atfwd_Sendcmd(  463): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  463): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  463): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  996): acquireWL(335b5cdd): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 996 1000 WorkSource{1000}
V/AlarmManager(  996): sending alarm PendingIntent{27a5aab2: PendingIntentRecord{13381a03 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=206209, Int=0
,V/AlarmManager(  996): sending alarm PendingIntent{180c1f23: PendingIntentRecord{26b81c20 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1454092233502, Int=0
,D/PMS     (  996): releaseWL(335b5cdd): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,D/WeatherUtility( 1216): Weather sync is On
W/WeatherTimeKeeper( 1216): [refreshWeatherData] no weather data
,D/PMS     (  996): acquireWL(35b5e9d9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 996 1000 null,
I/BatteryService(  996): n_update end
,D/PMS     (  996): releaseWL(35b5e9d9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PowerUI ( 1216): closing low battery warning: level=100
D/HeadsetStateMachine( 3072): Disconnected process message: 10, size: 0
D/NotificationService(  996): plugged=true pluggin=true
D/UsbnetService(  996): BroadcastReceiver::onReceive+
D/WifiController(  996): battery changed pluggedType: 2
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/HtcPowerSaver(  996): updateBatteryInfo,
D/UsbnetService(  996): onReceive BATTERY_CHANGED
D/PMS     (  996): runPSCheck
D/UsbnetService(  996):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  996): Checking...
D/UsbnetService(  996): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  996): >> updateStatus
D/WifiController(  996): handleMessage: E msg.what=155652
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  996): processMsg: DeviceActiveState
I/HtcPowerSaver(  996): updateStatus (8000,100,-1,false,false,false,-1),
D/WifiController(  996): processMsg: StaEnabledState
I/HtcPowerSaver(  996): << updateStatus
D/WifiController(  996): processMsg: DefaultState
D/WifiController(  996): handleMessage: X
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  463): AtCmdFwd service not published, waiting... retryCnt : 3
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1872): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1872): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1872): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1872): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DotMatrix( 1327): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1327): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1216): reapply : com.google.android.gms 4 40
,W/GLSActivity( 1872): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1872): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1872): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1872): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1872): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1872): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1872): 	at android.os.Binder.execTransact(Binder.java:454)
,E/PlayEventLogger( 5906): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5906): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 5906): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/PlayEventLogger( 5906): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 5906): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/PlayEventLogger( 5906): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 5906): 	at android.os.Binder.execTransact(Binder.java:454)
,W/System  ( 5906): Ignoring header User-Agent because its value was null.
,D/libc    ( 5906): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
,D/libc    ( 5906): [NET] android_getaddrinfofornet-, err=8
D/libc    ( 5906): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
D/libc    ( 5906): [NET] android_getaddrinfofornet-, pass to proxy
D/libc    ( 5906): [NET] android_getaddrinfo_proxy+
D/libc    ( 5906): [NET] android_getaddrinfo_proxy get netid:0
,D/libc    (  394): [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,D/libc    (  394): [NET] _dns_getaddrinfo+, netid:100, mark:917604
D/libc    (  394): [NET] _dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  394): [NET] android_getaddrinfofornet-, SUCCESS
,D/libc    ( 5906): [NET] android_getaddrinfo_proxy-, success
,W/Atfwd_Sendcmd(  463): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  463): AtCmdFwd service not published, waiting... retryCnt : 5
,W/Atfwd_Sendcmd(  463): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  463): AtCmdFwd service not published, waiting... retryCnt : 2
,W/Atfwd_Sendcmd(  463): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  996): acquireWL(d31713): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 996 1000 null
I/BatteryService(  996): n_update end
D/PMS     (  996): releaseWL(d31713): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  996): BroadcastReceiver::onReceive+
D/NotificationService(  996): plugged=true pluggin=true
D/UsbnetService(  996): onReceive BATTERY_CHANGED
D/WifiController(  996): battery changed pluggedType: 2
D/UsbnetService(  996):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1216): closing low battery warning: level=100
D/UsbnetService(  996): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  996): updateBatteryInfo
D/WifiController(  996): handleMessage: E msg.what=155652
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  996): processMsg: DeviceActiveState
D/PMS     (  996): runPSCheck
D/WifiController(  996): processMsg: StaEnabledState
D/HtcPowerSaver(  996): Checking...
D/WifiController(  996): processMsg: DefaultState
I/HtcPowerSaver(  996): >> updateStatus
D/WifiController(  996): handleMessage: X
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HeadsetStateMachine( 3072): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  996): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  996): << updateStatus
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true,
,W/Atfwd_Sendcmd(  463): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  463): AtCmdFwd service not published, waiting... retryCnt : 5
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1564): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1564): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1564): sku_id=118
D/ContactMessageStore( 1564): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1564): start background delete task...
,D/ContactMessageStore( 1564): size: 0 , 0,
D/ContactMessageStore( 1564): Background delete complete
,D/PMS     (  996): acquireWL(169acd50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 996 1000 null
I/BatteryService(  996): n_update end
D/PMS     (  996): releaseWL(169acd50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  996): updateBatteryInfo
,I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/NotificationService(  996): plugged=true pluggin=true
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  996): runPSCheck
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/WifiController(  996): battery changed pluggedType: 2
D/HeadsetStateMachine( 3072): Disconnected process message: 10, size: 0
D/HtcPowerSaver(  996): Checking...
D/UsbnetService(  996): BroadcastReceiver::onReceive+
I/HtcPowerSaver(  996): >> updateStatus
D/UsbnetService(  996): onReceive BATTERY_CHANGED,
D/PowerUI ( 1216): closing low battery warning: level=100
D/UsbnetService(  996):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  996): BroadcastReceiver::onReceive-
D/WifiController(  996): handleMessage: E msg.what=155652
D/WifiController(  996): processMsg: DeviceActiveState
D/WifiController(  996): processMsg: StaEnabledState
D/WifiController(  996): processMsg: DefaultState
I/HtcPowerSaver(  996): updateStatus (8000,100,-1,false,false,false,-1)
D/WifiController(  996): handleMessage: X
I/HtcPowerSaver(  996): << updateStatus
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  996): acquireWL(2657fb49): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 996 1000 null
I/BatteryService(  996): n_update end
D/PMS     (  996): releaseWL(2657fb49): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  996): updateBatteryInfo
,D/UsbnetService(  996): BroadcastReceiver::onReceive+
D/NotificationService(  996): plugged=true pluggin=true
D/UsbnetService(  996): onReceive BATTERY_CHANGED
D/PMS     (  996): runPSCheck
D/UsbnetService(  996):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/HtcPowerSaver(  996): Checking...
D/UsbnetService(  996): BroadcastReceiver::onReceive-
I/HtcPowerSaver(  996): >> updateStatus
I/IntentController( 1216): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/WifiController(  996): battery changed pluggedType: 2
D/WifiController(  996): handleMessage: E msg.what=155652
D/PowerUI ( 1216): closing low battery warning: level=100
,D/WifiController(  996): processMsg: DeviceActiveState
D/WifiController(  996): processMsg: StaEnabledState
D/PowerUI ( 1216): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/WifiController(  996): processMsg: DefaultState
D/WifiController(  996): handleMessage: X
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1327): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HeadsetStateMachine( 3072): Disconnected process message: 10, size: 0
,I/HtcPowerSaver(  996): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  996): << updateStatus
,I/BatteryController( 1216): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  996): acquireWL(57c6c4e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 996 1000 WorkSource{1000}
,V/AlarmManager(  996): sending alarm PendingIntent{27a5aab2: PendingIntentRecord{13381a03 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=386209, Int=0
V/AlarmManager(  996): sending alarm PendingIntent{114e116f: PendingIntentRecord{12676e7c com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=942338, Int=0
I/bt-btm  ( 3072): Received oneshot timer event complete
I/bt-btm  ( 3072): btm_ble_timeout
I/bt-btm  ( 3072): btm_gen_resolvable_private_addr
,D/PMS     (  996): acquireWL(99c0305): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3072 1002 null
,D/bt-btm  ( 3072): btm_ble_rand_enc_complete,
D/PMS     (  996): releaseWL(57c6c4e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
I/bt-btm  ( 3072): btm_gen_resolve_paddr_low
D/bt-smp  ( 3072): smp_encrypt_data
W/bt-smp  ( 3072): Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
W/bt-smp  ( 3072): Plain text(LSB ~ MSB) = 82 a8 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
D/WeatherUtility( 1216): Weather sync is On
W/bt-smp  ( 3072): Encrypted text(LSB ~ MSB) = de 58 e8 53 d6 41 8e c4 b8 f5 74 a2 22 08 c5 49 
I/bt-btm  ( 3072): btm_gen_resolve_paddr_cmpl
W/bt-btm  ( 3072): Stopping oneshot timer
D/bt-btm  ( 3072): Starting oneshot timer type:103 timeout:900s
W/WeatherTimeKeeper( 1216): [refreshWeatherData] no weather data
,D/PMS     (  996): releaseWL(99c0305): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,D/Finsky  ( 5906): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/PMS     (  996): acquireWL(11d4558b): PARTIAL_WAKE_LOCK  *alarm* 0x1 996 1000 WorkSource{10072},
V/AlarmManager(  996): sending alarm PendingIntent{3dfaf668: PendingIntentRecord{ed1a13f com.android.vending startService}}, i=null, t=0, cnt=1, w=1454092602182, Int=0
V/AlarmManager(  996): sending alarm PendingIntent{175eca81: PendingIntentRecord{35d5b726 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=938587, Int=0
,I/ActivityManager(  996): Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6573 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
V/AlarmManager(  996): sending alarm PendingIntent{2abd1114: PendingIntentRecord{172c8dbd com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1454092545366, Int=0
,V/AlarmManager(  996): sending alarm PendingIntent{3f97f6c7: PendingIntentRecord{5cee4f4 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=806892, Int=0
,V/AlarmManager(  996): sending alarm PendingIntent{3e0284fe: PendingIntentRecord{b8c016a com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454092842060, Int=0
,D/PMS     (  996): acquireWL(31948b9): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1872 10024 WorkSource{10024 com.google.android.gms}
D/PMS     (  996): releaseWL(31948b9): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 6421): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,D/PMS     (  996): releaseWL(11d4558b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,D/PowerUsageList:PowerUsageHelper( 6421): MY_DEBUG = false
,D/PowerUsageService( 6421): repeat time = 1454093742138
,D/PMS     (  996): acquireWL(2e9035d6): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1872 10024 WorkSource{10024 com.google.android.gms}
,D/GCM     ( 1872): Message class com.google.f.a.a.i
,D/PMS     (  996): releaseWL(2e9035d6): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,I/GLSUser ( 1872): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1872): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1872): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1872): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5906): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/StatusBarManagerService(  996): setSystemUiVisibility(0x700)
D/StatusBarManagerService(  996): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  996): hiding MENU key,
D/StatusBarManagerService(  996): setSystemUiVisibility(0xc0000700)
D/StatusBarManagerService(  996): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService(  996): hiding MENU key
,D/FindExtension( 1631): FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,I/ThreadedRenderer( 1631): Defer allocateBuffers to drawing time
,I/InputMethodManagerService(  996): Disable input method client, pid=6444
,D/StatusBarManagerService(  996): swetImeWindowStatus vis=0 backDisposition=0
W/IInputConnectionWrapper( 6444): Do restartInputUnchecked, ic=null
I/InputMethodManager( 6444): com.test.thalitest called restartInputUnchecked(msg=100) from com.android.internal.view.IInputConnectionWrapper.executeMessage(IInputConnectionWrapper.java:213)
W/IInputConnectionWrapper( 6444): reportFullscreenMode on inactive InputConnection
,I/PhoneStatusBar( 1216): setImeWindowStatus(false,false)
,I/PowerUsageList:PowerUsageHelper( 6421): PowerProfile::POWER_SCREEN_FULL = 154.8,
,D/PowerUsageList:BatterySipperExt( 6421): gen(), null == sipper.uidObj, userId = 0,
,E/cutils-trace( 6596): Error opening trace file: Permission denied (13),
I/dex2oat ( 6596): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 6596): dex2oat: override thread count:4
,I/art     (  996): Explicit concurrent mark sweep GC freed 30247(1657KB) AllocSpace objects, 11(1864KB) LOS objects, 33% free, 16MB/25MB, paused 2.002ms total 169.589ms,
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1872): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1872): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1872): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1872): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1872): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
I/GLSUser ( 1872): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1872): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1872): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 5906): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/dex2oat ( 6596): dex2oat took 601.652ms (threads: 4),
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PushClient( 6573): ApplicationMonitor {3f2b54a1}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,I/PushClient( 6573): ApplicationMonitor {3f2b54a1}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
I/PushClient( 6573): ApplicationMonitor {3f2b54a1}: logBasicAppInfo(): VersionName:             1.2.853019
I/PushClient( 6573): ApplicationMonitor {3f2b54a1}: logBasicAppInfo(): VersionCode:             148001224
I/PushClient( 6573): ApplicationMonitor {3f2b54a1}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,I/PushClient( 6573): ApplicationMonitor {3f2b54a1}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
I/PushClient( 6573): ApplicationMonitor {3f2b54a1}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
I/PushClient( 6573): ApplicationMonitor {3f2b54a1}: logBasicAppInfo(): Htc_DEBUG_flag:          false
,I/PushClient( 6573): ApplicationMonitor {3f2b54a1}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,I/GLSUser ( 1872): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
I/PushClient( 6573): PnsModel {598d508}: update(): Update registration caused by: alarm
,I/GLSUser ( 1872): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1872): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1872): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1872): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/PushClient( 6573): PnsConfigModel {28b9df7f}: <init>(): Use dm-client for provisioning.
,W/Finsky  ( 5906): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 5906): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 5906): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5906): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,W/System.err( 6573): SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".,
W/System.err( 6573): SLF4J: Defaulting to no-operation (NOP) logger implementation
W/System.err( 6573): SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
D/DeviceConnectionService( 1833): client connected with version: 7571000
,W/ContextImpl( 6573): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/ActivityManager(  996): Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6607 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a,
,I/DeviceManagement( 6607): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6607 dbg=false s=true
,I/DeviceManagement( 6607): ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
,I/DeviceManagement( 6607): ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns],
,I/DeviceManagement( 6607): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,I/DeviceManagement( 6607): WorkflowService: Starting workflow service
,I/DeviceManagement( 6607): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@598d508] args=[Bundle[mParcelledData.dataSize=88]]
,I/DeviceManagement( 6607): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,I/DeviceManagement( 6607): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 6607): ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,I/DeviceManagement( 6607): SessionStateController: Checking invariants...
,I/DeviceManagement( 6607): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,I/DeviceManagement( 6607): SessionStateController: Checking invariants...,
,I/DeviceManagement( 6607): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false,
,I/DeviceManagement( 6607): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@598d508],
,I/DeviceManagement( 6607): WorkflowService: Stopping workflow service
,D/Process (  996): killProcessQuiet, pid=6307,
I/ActivityManager(  996): Killing 6307:com.google.android.setupwizard/u0a77 (adj 15): empty #17
D/Process (  996): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  996): Recipient 6307,
,I/PushClient( 6573): PnsModel {598d508}: update(): The registration record has not expired yet. No need to update.,
,D/Process (  996): killProcessQuiet, pid=6263
I/ActivityManager(  996): Killing 6263:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
D/Process (  996): com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,I/ActivityManager(  996): Recipient 6263,
,D/PMS     (  996): acquireWL(3b29f9e6): PARTIAL_WAKE_LOCK  *alarm* 0x1 996 1000 WorkSource{10072},
V/AlarmManager(  996): sending alarm PendingIntent{28e7ab27: PendingIntentRecord{7f3f1d4 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454092857528, Int=0
D/PMS     (  996): releaseWL(3b29f9e6): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,D/Finsky  ( 5906): [587] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
D/Finsky  ( 5906): [1] 5.onFinished: Installation state replication succeeded.
,D/PMS     (  996): acquireWL(1484bf7d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 996 1000 WorkSource{1000},
V/AlarmManager(  996): sending alarm PendingIntent{27a5aab2: PendingIntentRecord{13381a03 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=986209, Int=0
V/AlarmManager(  996): sending alarm PendingIntent{68bce72: PendingIntentRecord{99d2c3 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454092887532, Int=0
,D/SmartSyncUtils( 6421): isEpsOn(), nState = 0
,D/PMS     (  996): acquireWL(25885740): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6421 1000 null
,D/PMS     (  996): releaseWL(1484bf7d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
D/WeatherUtility( 1216): Weather sync is On
,W/WeatherTimeKeeper( 1216): [refreshWeatherData] no weather data
,D/SmartSyncScreenOnOffTimeReceiver( 6421): [updateNmRange] bManual = false,
,D/SmartSyncScreenOnOffTimeReceiver( 6421): [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true,
,D/SmartSyncScreenOnOffTimeReceiver( 6421): AlarmOnTime = -1,
,D/SmartSyncScreenOnOffTimeReceiver( 6421): SettingOnTime = 1454133600000, randomSettingOnTime = 1454132232000
,D/SmartSyncScreenOnOffTimeReceiver( 6421): SettingOffTime = 1454112000000, randomSettingOffTime = 1454116653000,
D/SmartSyncScreenOnOffTimeReceiver( 6421): bDayMode = false
,D/SmartSyncScreenOnOffTimeReceiver( 6421): bNightMode = true
D/SmartSyncScreenOnOffTimeReceiver( 6421): bNightModeTurnOffOnce = false
,D/PMS     (  996): releaseWL(25885740): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,E/PNP_UPDATERD(  386): inotify_add_watch failed. (No such file or directory)
,I/UsageStatsService(  996): User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1200000ms)
```
