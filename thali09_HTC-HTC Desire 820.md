#### Test 579720943a29850_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [1][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): [ScoreAP] + current TXpacket:53, mTXpacketCount:18, avgLinkspeed:72,mAvgTxRate72
D/WifiStateMachine(  903): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
I/Icing   ( 2177): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
I/Icing   ( 2177): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
--------- beginning of /dev/log/system
D/PMS     (  903): releaseWL(42926338): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=4041 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
W/GAV2    ( 4041): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager(  903): Delay finish: com.google.android.gm/.MailIntentReceiver
D/PMS     (  903): acquireWL(42c7c5b8): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(42c7c5b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  903): Resuming delayed broadcast
D/Process (  903): killProcessQuiet, pid=3794
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=4066 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
I/ActivityManager(  903): Killing 3794:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/PMS     (  903): acquireWL(42820e48): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  903): Recipient 3794
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  903): acquireWL(42b713d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
D/PMS     (  903): releaseWL(42b713d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(42820e48): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
I/Gmail   ( 4041): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4041): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
I/Gmail   ( 4041): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 4041): calculateUnknownSyncRationalesAndPurgeInBackground: running
E/cutils-trace( 4050): Error opening trace file: No such file or directory (2)
I/Babel   ( 4066): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 4066): MmsConfig.loadMmsSettings
W/dalvikvm( 4066): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 4066): VFY: unable to resolve instance field 36
W/dalvikvm( 4066): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/MmsCustomizationProvider( 2697): query uri: content://htc-mms-customization/mms-ua/ua_string
V/JNIHelp ( 4066): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/MmsCustomizationProvider( 2697): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4066): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 4066): MmsConfig.loadFromDatabase
D/CustomizationManager( 4050): ====startRecUseTime====
D/htc.customization.log.level( 4050):  is 
W/CustomizationLogLevel( 4050): Level value is invalid, use default level 2
E/Babel   ( 4066): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 4066): MmsConfig.loadFromResources
E/Babel   ( 4066): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 4066): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4066, uid=10111, userID:0
W/Settings( 4066): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4066, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4066, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4066, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4066, uid=10111, userID:0
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4066, uid=10111, userID:0
D/PMS     (  903): acquireWL(427ff8b8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4066 10111 null
I/ActivityManager(  903): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
D/CustomizationManager( 4050):  Read ACC file spent 0.078 (s)
D/CIDMapFileReader( 4050): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4050): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4050): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4050): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4050): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4050): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4050): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4050): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4050): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4050): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4050): full path : /system/customize/CID/HTC__032.xml
I/ProviderInstaller( 4066): Installed default security provider GmsCore_OpenSSL
I/CustomizationCIDLoader( 4050): Parsing tag category name = system
I/CustomizationCIDLoader( 4050): Parsing tag category name = application
I/CustomizationCIDLoader( 4050): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4050): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4050): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4050): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4050): Parsing tag category name = Settings
D/CustomizationManager( 4050):  Read CID file spent 0.126 (s)
D/CustomizationManager( 4050):  All configurations done spent 0.126 (s)
W/HtcNativeFlag( 4050): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4050): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4050): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4050): Fail to get flag for type 'language', use default value: -1
D/PMS     (  903): releaseWL(427ff8b8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  903): Resuming delayed broadcast
I/ActivityManager(  903): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4050
D/PMS     (  903): acquireWL(42c48870): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4066 10111 null
D/Process (  903): killProcessQuiet, pid=3402
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3402:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
D/PMS     (  903): acquireWL(42b7f3e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1356/10029)
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  903): Recipient 3402
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023245
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023518
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023602
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023606
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023609
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023614
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025112
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360027812
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/PMS     (  903): releaseWL(42b7f3e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): acquireWL(428d73c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1356/10029)
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023245
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023518
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023602
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023606
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023609
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023614
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025112
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360027812
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): releaseWL(428d73c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(42c48870): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/Process (  903): killProcessQuiet, pid=3009
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3009:com.android.defcontainer/u0a19 (adj 15): empty #17
I/ActivityManager(  903): Recipient 3009
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/GCM     ( 1356): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
D/PMS     (  903): acquireWL(42abd948): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): acquireWL(4286b550): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
W/GCoreFlp( 1219): No location to return for getLastLocation()
W/FusedLocationProvider( 1219): location=null
D/PMS     (  903): releaseWL(4286b550): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023245
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023518
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023602
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023606
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023609
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023614
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025112
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360027812
,D/PMS     (  903): acquireWL(42b904c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1356/10029)
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023245
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023518
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023602
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023606
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023609
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023614
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025112
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360027812
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/PMS     (  903): releaseWL(42b904c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): acquireWL(42ada6d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1356/10029)
D/PMS     (  903): releaseWL(42abd948): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023245
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023518
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023602
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023606
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023609
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023614
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025112
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025123
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360027812
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): releaseWL(42ada6d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): acquireWL(42ae6e58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1356/10029)
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023245
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023518
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023602
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023606
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023609
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023614
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025112
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360027812
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): releaseWL(42ae6e58): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): acquireWL(42997e78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1356/10029)
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023245
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023518
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023602
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023606
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023609
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023614
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025112
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025123
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360027812
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/PMS     (  903): releaseWL(42997e78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42b55978): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  903): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4123 uid=10041 gids={50041}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1356/10029)
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023245
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023518
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023602
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023606
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023609
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023614
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025112
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025123
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360027812
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): releaseWL(42b55978): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42c3e0b8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4066 10111 null
D/ConnectivityService(  903): Sampling interval elapsed, updating statistics ..
,D/Process (  903): killProcessQuiet, pid=3727
D/PMS     (  903): releaseWL(42c3e0b8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  903): Killing 3727:com.htc.sense.news/u0a76 (adj 15): empty #17
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ConnectivityService(  903): Done.
D/ConnectivityService(  903): Setting timer for 720seconds
,D/WearableService( 1219): callingUid 10029, callindPid: 1219
,D/LocationInitializer( 2177): Restart initialization of location
,E/MDM     ( 1219): [104] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1356): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1356): Proximity feature is not enabled.
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  903): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,W/GCoreFlp( 1219): No location to return for getLastLocation()
,W/FusedLocationProvider( 1219): location=null
D/PMS     (  903): acquireWL(42b38468): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  903): Resuming delayed broadcast
D/PMS     (  903): releaseWL(42b38468): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023245
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023518
,D/PMS     (  903): acquireWL(42b23428): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3609 10071 null
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023602
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023606
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023609
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023614
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025112
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025123
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360027812
,D/PMS     (  903): acquireWL(42addfb0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3609 10071 null
,D/PMS     (  903): acquireWL(42ad0d58): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3609 10071 null
,D/PMS     (  903): releaseWL(42b23428): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/PMS     (  903): acquireWL(42addfb0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3609 10071 null
,E/TodoTaskNotifyService( 3609): java.lang.NullPointerException
,W/System.err( 3609): java.lang.NullPointerException
W/System.err( 3609): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3609): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3609): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3609): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3609): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  903): releaseWL(42ad0d58): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  903): acquireWL(42ab6e20): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3609 10071 null
,D/PMS     (  903): releaseWL(42addfb0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/NotifyReceiver( 3609): stopSelfResult true
E/TodoTaskNotifyService( 3609): java.lang.NullPointerException
W/System.err( 3609): java.lang.NullPointerException
W/System.err( 3609): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3609): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3609): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3609): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3609): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/WSP     ( 1339): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1339): Weather sync is On
D/PMS     (  903): acquireWL(42aaa140): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3609 10071 null
E/TodoTaskNotifyService( 3609): java.lang.NullPointerException
W/System.err( 3609): java.lang.NullPointerException
W/System.err( 3609): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3609): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3609): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3609): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3609): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/NotifyReceiver( 3609): stopSelfResult false
,E/NotifyReceiver( 3609): mStartingService is null
,W/NotifyReceiver( 3609): stopSelfResult true
,I/WSP     ( 1339): [Receiver] next auto-sync alarm event is 60 mins later, at time: Tue Feb 02 14:06:39 CET 2016
D/PMS     (  903): releaseWL(42ab6e20): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  903): releaseWL(42aaa140): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1339/10055)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.sense.hsp (1339/10055)
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (2177/10029)
,D/PMS     (  903): acquireWL(42a11338): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1339 10055 null
,D/GCM     ( 1356): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  903): acquireWL(42a05498): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4066 10111 null
,I/ActivityManager(  903): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  903): releaseWL(42a05498): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Recipient 3727
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1339): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1339): handle notify Blinkfeed plugin client changed
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/IcingCorporaProvider( 2812): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PMS     (  903): acquireWL(426e1fe0): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(426e1fe0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(427c5c38): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(427c5c38): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(4246e7a0): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(4246e7a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42851e28): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42851e28): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(424a60a0): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  903): mEventCount = 450
,D/PMS     (  903): releaseWL(424a60a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
D/PMS     (  903): acquireWL(42afaa40): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42afaa40): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(429970b0): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(429970b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/IcingCorporaProvider( 2812): UpdateCorporaTask done [took 345 ms] updated apps [took 345 ms] 
I/ActivityManager(  903): Resuming delayed broadcast
,V/AlarmManager(  903): sending alarm PendingIntent{42919468: PendingIntentRecord{42967ea0 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1454414799880, Int=0
,I/ActivityManager(  903): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  903): acquireWL(42a31f38): PARTIAL_WAKE_LOCK  AsyncService 0x1 3560 10160 null
,D/PMS     (  903): releaseWL(42a31f38): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  903): Resuming delayed broadcast
,D/PackageBroadcastService( 2177): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2177): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  903): Delay finish: com.htc.task/.TodoReceiver
,D/PMS     (  903): acquireWL(428ac238): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2177): updateResources: need to parse f{com.google.android.gms}
,D/TodoTaskshortcut( 3609): update TASK shortcut>
,I/HtcModeClient( 1517): handler message = 4011
,E/HtcModeClient( 1517): Check connection and retry 7 times.
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,I/Icing   ( 2177): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,D/Icing   ( 2177): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2177): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  903): releaseWL(428ac238): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  903): sending alarm PendingIntent{42a21fe0: PendingIntentRecord{429bbbd8 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1454414801689, Int=0
,V/AlarmManager(  903): sending alarm PendingIntent{429b7080: PendingIntentRecord{429b3230 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1454414801713, Int=0
,I/iu.UploadsManager( 2177): End new media; added: 0, uploading: 0, time: 90 ms
,I/GAV2    ( 4041): Thread[GAThread,5,main]: No campaign data found.
,I/GAV4    ( 4066): Thread[GAThread,5,main]: No campaign data found.
,D/WIFI_ICON( 1112): WifiActivity: 0
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2177, uid=10029, userID:0
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2177, uid=10029, userID:0
,I/CheckinService( 2177): Done disabling old GoogleServicesFramework version
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2177, uid=10029, userID:0
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/CalendarProvider2( 1517): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1517): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  903): Resuming delayed broadcast
D/PMS     (  903): acquireWL(42b1dbb8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 903 1000 null
D/ConnectivityService(  903): getActiveNetworkInfo called by  (903/1000)
D/PMS     (  903): acquireWL(4291bf00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 903 1000 null
D/PMS     (  903): releaseWL(42b1dbb8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  903): releaseWL(4291bf00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  903): acquireWL(42c17388): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3834 10154 null
I/ActivityManager(  903): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3834): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  903):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3834, uid=10154, userID:0
,I/MusicLeanback( 3834): Conditions not met for autocaching.
,I/MusicLeanback( 3834): Stop autocaching.
,W/ContextImpl( 3834): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  903): releaseWL(42c17388): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,I/ActivityManager(  903): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,W/MediaManager( 3813): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  903): Resuming delayed broadcast
,D/PMS     (  903): acquireWL(42b51ff8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1356/10029)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023245
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023518
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023602
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023606
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023609
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023614
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025112
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360027812
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): releaseWL(42b51ff8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): acquireWL(42bf41b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1356/10029)
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023245
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023518
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023602
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023606
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023609
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023614
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025112
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360027812
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): releaseWL(42bf41b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): acquireWL(42ad4368): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  903): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4181 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1356/10029)
,I/HtcModeClient( 1517): handler message = 4011
,E/HtcModeClient( 1517): Check connection and retry 8 times.
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023245
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023518
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023602
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023606
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023609
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023614
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025112
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360027812
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/PMS     (  903): releaseWL(42ad4368): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/SyncApplication( 4181): Loading default preferences
,W/Resources( 4181): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  903): New client listening to asynchronous messages
,D/SyncApplication( 4181): Overriding preferences with custom values
,D/SyncApplication( 4181): Updating preferences succeeded
,E/SyncApplication( 4181): Application created.
D/VolumeInfo( 4181): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4181): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
,V/VolumeInfo( 4181): Found 0 mount point(s)
,V/VolumeInfo( 4181): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4181): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4181): getNewCalendarAuthority()...
,D/VolumeInfo( 4181): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 4181): Can not create volume ID for unmounted volume null
,D/SyncApplication( 4181): enableAppOperation()+
,D/SyncApplication( 4181): enableAppOperation()-
,D/HTCUtilities( 4181): isNeorSinged() + 
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4181, uid=10008, userID:0
W/PackageManager(  903): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  903):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4181, uid=10008, userID:0
W/PackageManager(  903): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 4181): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4181): isNeorSinged() return false
,D/CDMountReceiver( 4181): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4181): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 4181): enable CD Auto-mount: true
D/HTCUtilities( 4181): enable auto-mount
,D/DotMatrix( 1590): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/HTCUtilities( 4181): enable auto-mount
,I/RemoteViews( 1112): com.nero.android.htc.sync (false,0)
,D/Process (  903): killProcessQuiet, pid=3899
I/ActivityManager(  903): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
D/MountService(  903): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  903): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  903): Resuming delayed broadcast
D/PMS     (  903): releaseWL(429a8710): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
,I/ActivityManager(  903): Killing 3899:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{42323b68 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3899
,I/RemoteViews.Performance( 1112): com.nero.android.htc.sync 1 13 5 11
,I/RemoteViews( 1112): com.nero.android.htc.sync (false,0)
D/WifiService(  903): Client connection lost with reason: 4
,I/ActivityManager(  903): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4202 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{423296d0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.nero.android.htc.sync 0 10 3 16
,D/CalendarApplication( 4202): onCreate
D/ProviderChangeReceiver( 4202): ---------------------------------------------------
,D/ProviderChangeReceiver( 4202): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4202): start to updateAlertNotification!
,D/Process (  903): killProcessQuiet, pid=3940
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  903): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4216 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  903): Killing 3940:com.htc.task.gtask/u0a68 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3940
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AlertService( 4202): No fired or scheduled alerts
D/HtcAlertUtils( 4202): -- cancelReminderNotification --
D/HtcAlertUtils( 4202): broadcastExistReminder!
D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 4216): [4216/4216] onCreate()
W/ContextImpl( 4216): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  903): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  903): Resuming delayed broadcast
,D/Process (  903): killProcessQuiet, pid=3657
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
I/ActivityManager(  903): Killing 3657:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3657
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/PMS     (  903): acquireWL(42b457d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): releaseWL(42b457d8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
,D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{42b2b380 u0 com.htc.musicenhancer/.EnhancerService}
,D/PMS     (  903): releaseWL(42a11338): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,I/SensorManager(  903): mEventCount = 600
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,I/HtcModeClient( 1517): handler message = 4011
,E/HtcModeClient( 1517): Check connection and retry 9 times.
,D/WifiDataStallTracker(  903): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  903): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  903): updateDataStallInfo: mDataStallTxRxSum={txSum=30 rxSum=28} preTxRxSum={txSum=30 rxSum=28}
D/WifiDataStallTracker(  903): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  903): onDataStallAlarm: tag=19476 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19477 delay=15s
D/PMS     (  903): acquireWL(42ab78b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{420c1d88: PendingIntentRecord{42947510 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=74473, Int=0
D/PMS     (  903): releaseWL(42ab78b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1112): WifiActivity: 0
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WifiStateMachine(  903): [ScoreAP] + current TXpacket:53, mTXpacketCount:53, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  903): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/Finsky  ( 3993): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 3993): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
D/PMS     (  903): acquireWL(42ab6dd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10074}
V/AlarmManager(  903): sending alarm PendingIntent{42a9de10: PendingIntentRecord{42a1f238 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454414813494, Int=0
D/PMS     (  903): releaseWL(42ab6dd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.android.vending (3993/10074)
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3993): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 3993): [NET] getaddrinfo-,err=8
D/libc    ( 3993): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3993): [NET] getaddrinfo-, 1
,D/libc    ( 3993): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =13f3 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3993): [NET] getaddrinfo_proxy-, success
I/global  ( 3993): call createSocket() return a new socket.
D/libc    ( 3993): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 3993): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3993): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 3993): [NET] getaddrinfo-,err=8
,D/WIFI_ICON( 1112): WifiActivity: 3
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 3993): untagSocket(69) failed with errno -22
,D/Finsky  ( 3993): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 3993): untagSocket(69) failed with errno -22
,I/HtcModeClient( 1517): handler message = 4011
,E/HtcModeClient( 1517): Check connection and retry 10 times.
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 3993): untagSocket(69) failed with errno -22
,D/ConnectivityService(  903): getNetworkInfo networkType=0 called by com.android.vending (3993/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (3993/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (3993/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (3993/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (3993/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (3993/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (3993/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (3993/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (3993/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (3993/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (3993/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (3993/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (3993/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (3993/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (3993/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (3993/10074)
,D/ConnectivityService(  903): getNetworkInfo networkType=1 called by com.android.vending (3993/10074)
,D/Finsky  ( 3993): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  903): acquireWL(42b4a710): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10074}
V/AlarmManager(  903): sending alarm PendingIntent{42aeec08: PendingIntentRecord{429ca400 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1454414815978, Int=0
D/WearableService( 1219): callingUid 10029, callindPid: 1219
,D/PMS     (  903): acquireWL(42b83cc8): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 3993 10074 null
,D/PMS     (  903): releaseWL(42b4a710): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
D/Finsky  ( 3993): [425] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/DeviceConnectionService( 1219): client connected with version: 8296000
,D/Finsky  ( 3993): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3993): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1356): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3993): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3993): [NET] getaddrinfo-,err=8
D/libc    ( 3993): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3993): [NET] getaddrinfo-, 1
,D/libc    ( 3993): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =8dbc +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 290
D/libc    (  365): [NET]res_nsend:resplen=87
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3993): [NET] getaddrinfo_proxy-, success,
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL,
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0,
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=8 [62][5][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true,
,D/PMS     (  903): releaseWL(42b83cc8): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  903): acquireWL(42a77cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42a77cb8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/ContactMessageStore( 1236): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1236): MSG_NOTIFY_CS_TO_SYNC <<
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [10][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,I/SensorManager(  903): mEventCount = 750
,I/ClockThread( 1112): now=1454414819637 next=363
,D/AutoSetting( 1339): service - has update message, not stop
,D/AutoSetting( 1339): service - mHandler: update timezone
,D/AutoSetting( 1517): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1517): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,W/ActivityManager(  903): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1517): service - onCreate()
,D/AutoSetting( 1517): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1517): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1517): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1517): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1517): service - mHandler: update timezone
,D/AutoSetting( 1517): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1517): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1517): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1517): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1590): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1590): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1112): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1112): release indeterminate drawable android.widget.OnDemandProgressBar{423972d0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1112): com.htc.htclocationservice 2 7 2 11
,I/ClockThread( 1112): now=1454414820002 next=59998
D/PMS     (  903): acquireWL(42b66540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{426ab068: PendingIntentRecord{420b4058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=83617, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42b66540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/HtcModeClient( 1517): handler message = 4011
,E/HtcModeClient( 1517): Check connection and retry 11 times.
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WIFI_ICON( 1112): WifiActivity: 0
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(42b2b8f0): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42b2b8f0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42b59628): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42b59628): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(4286d648): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(4286d648): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42b22f98): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42b22f98): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42b47d50): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42b47d50): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,I/HtcModeClient( 1517): handler message = 4011
,E/HtcModeClient( 1517): Check connection and retry 12 times.
,D/WifiDataStallTracker(  903): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  903): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  903): updateDataStallInfo: mDataStallTxRxSum={txSum=101 rxSum=91} preTxRxSum={txSum=30 rxSum=28}
D/WifiDataStallTracker(  903): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  903): onDataStallAlarm: tag=19477 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19478 delay=15s
D/PMS     (  903): acquireWL(42ad0790): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{42ab4c00: PendingIntentRecord{42947510 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=89478, Int=0
D/PMS     (  903): releaseWL(42ad0790): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1112): WifiActivity: 0
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
D/WifiStateMachine(  903): [ScoreAP] + current TXpacket:130, mTXpacketCount:53, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  903): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/HtcModeClient( 1517): handler message = 4011
,E/HtcModeClient( 1517): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1517): Don't start project servcice
,D/HtcModeClient( 1517): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1517): connectState: CONNECTION_READY = false
,D/SilentMusic( 1517): call stop
,D/HtcModeClient( 1517): close connection
,W/HtcModeClient( 1517): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1517): read the terminate packet, so break
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WIFI_ICON( 1112): WifiActivity: 0
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  903): acquireWL(42c35820): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10074}
,V/AlarmManager(  903): sending alarm PendingIntent{41fd1b28: PendingIntentRecord{428af158 com.android.vending startService}}, i=null, t=0, cnt=1, w=1454414830020, Int=0
,I/ActivityManager(  903): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4258 uid=10078 gids={50078}
,V/AlarmManager(  903): sending alarm PendingIntent{428b5480: PendingIntentRecord{428ab320 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1454414832334, Int=60000
,D/PMS     (  903): releaseWL(42c35820): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 4258): SMSBackupAgentService started
,D/SMSBackup( 4258): Checking restore status
,D/SMSBackup( 4258): Restore complete
,D/SMSBackup( 4258): cancelCheckAlarm
,D/SMSBackup( 4258): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023245
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023518
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023602
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023606
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023609
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023614
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025112
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360027812
,D/Finsky  ( 3993): [416] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3993): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  903): killProcessQuiet, pid=3879
,I/ActivityManager(  903): Killing 3879:com.htc.sdm/u0a81 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  903): Recipient 3879
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,I/ActivityManager(  903): Waited long enough for: ServiceRecord{42ade3c0 u0 com.htc.htclocationservice/.AutoSettingService}
,D/WIFI_ICON( 1112): WifiActivity: 0
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,V/LightsService(  903): setLight #0: color=#3d
,V/LightsService(  903): setLight #0: color=#3a
,V/LightsService(  903): setLight #0: color=#33
,V/LightsService(  903): setLight #0: color=#2d
,V/LightsService(  903): setLight #0: color=#26
,V/LightsService(  903): setLight #0: color=#1f
,V/LightsService(  903): setLight #0: color=#19
,V/LightsService(  903): setLight #0: color=#14
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WIFI_ICON( 1112): WifiActivity: 1
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,D/WifiDataStallTracker(  903): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  903): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  903): updateDataStallInfo: mDataStallTxRxSum={txSum=101 rxSum=91} preTxRxSum={txSum=101 rxSum=91}
D/WifiDataStallTracker(  903): updateDataStallInfo: NONE
,D/WifiDataStallTracker(  903): onDataStallAlarm: tag=19478 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19479 delay=15s
D/PMS     (  903): acquireWL(42b31230): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
V/AlarmManager(  903): sending alarm PendingIntent{42b916c0: PendingIntentRecord{42947510 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=104483, Int=0
D/PMS     (  903): releaseWL(42b31230): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1112): WifiActivity: 0
,D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/PMS     (  903): Going to sleep due to screen timeout...
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42617328
,W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  903): disable: get sensor name = CM36282 Light sensor
D/WirelessDisplayService(  903): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 2
,W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42617328, eanble = 0, strlen(mName) = 59,
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  903): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4248fea8,
W/SensorService(  903): Listener[1] = com.htc.smartdim.sensor_eye@422fbab8
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  903): mWirelessDisplayManager is null
V/LightsService(  903): setLight #2: color=#0
D/qdlights(  903): set_light_buttons_func: on=0 brightness=0
V/LightsService(  903): setLight #0: color=#0
W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/SurfaceControl(  903): Excessive delay in blankDisplay() while turning screen off: 316ms
,W/PnPMgr  (  358): Write '/proc/sys/kernel/sched_boost' failed (Invalid argument)
D/PMS     (  903): nativeSetInteractive:false
D/PMS     (  903): nativeSetInteractive:false done
D/PMS     (  903): nativeSetAutoSuspend:true
D/PMS     (  903): nativeSetAutoSuspend:true done
D/HABCtrl (  903): TPE algorithm. remove timeout.
D/PMS     (  903): OOBE c monitor 11
D/NfcService( 1252): ScreenObserver: OFF
,D/NfcService( 1252): applyRouting - 0
,D/NfcService( 1252): applyRouting -2
,V/KeyguardServiceDelegate(  903): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42c57af8)
I/InputManager(  903): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  903): screenObserver, isScreenOn=false
I/InputMethodManagerService(  903): Disable input method client, pid=1271
D/PMS     (  903): acquireWL(42c573f8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1252 1027 null
,I/IntentController( 1112): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
W/XT9_C   ( 1207): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1207): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,V/KeyguardServiceDelegate(  903): **** SHOWN CALLED ****
D/PMS     (  903): releaseWL(42c573f8): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  903): wakingUp
I/WindowManager(  903): No lock screen! windowToken=null
D/PMS     (  903): acquireWL(42b0b1e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/PMN     (  903): onScreenOn
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42b0b1e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/WirelessDisplayService(  903): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,D/MtpService( 1965): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 1965): [MTP][onReceive]-
,D/NfcService( 1252): applyRouting - 0
,D/AutoSetting( 1339): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1252): applyRouting -2
I/HtcPowerSaver(  903): << updateStatus
D/PMS     (  903): acquireWL(42c80818): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1252 1027 null
,D/AutoSetting( 1339): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 3778): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3778): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3778): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3778): Cust_ConnectToPC   : spcsc>false
D/        ( 3778): Cust_ConnectToPC   : IPT>true
D/        ( 3778): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3778): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3778): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3778): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3778): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  903): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  903): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  903): releaseWL(42c80818): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  903): batLight: Full, plugged
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
I/PSReceiver( 3778): onReceive:android.intent.action.USER_PRESENT
D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  903): startDataStallAlarm: tag=19480 delay=15s
I/SmartNS_PSService( 3778): onReceive:android.intent.action.USER_PRESENT
,D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1186): SET_SCREEN_ON:On
I/wpa_supplicant( 1186): htc_wext_set_keepalive +
I/wpa_supplicant( 1186): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1186): getPrivFuncNum +	
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
I/wpa_supplicant( 1186): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1186): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1186): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1186): htc_wext_set_TX_TRACKING (1)+
,I/wpa_supplicant( 1186): htc_wext_set_TX_TRACKING - ret = 0
W/Settings( 3778): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/AlarmManager(  903): ACTION_SCREEN_ON
I/AlarmManager(  903): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  903): [AlarmQueuing] done recovering
I/AlarmManager(  903): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  903): [AlarmQueuing] done EPS screen off alarm recovering
W/ContextImpl( 3778): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023245
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023518
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023602
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023606
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023609
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023614
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025112
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025123
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360027812
D/WifiNative-wlan0(  903):    returned true
I/SmartNS_PSService( 3778):  defaultType:0
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,I/ClockThread( 1112): stop update clock,
D/WIFI_ICON( 1112): WifiActivity: 1
D/StatusBar.NetworkController( 1112): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
V/NotificationService(  903): batLight: Full, plugged
,V/SRS_Proc(  373): ParamSet string: screen_state=on
,D/WirelessDisplayService(  903): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
V/LightsService(  903): setLight #8: color=#c8c800
D/qdlights(  903): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  903): setLight #8: color=#c800
D/qdlights(  903): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  903): [LedInfo] has indicator attribute
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  903): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  903): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  903): doBoolean: SignalStrength 97
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1186): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  903):    returned true
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/WifiStateMachine(  903): [ScoreAP] + current TXpacket:130, mTXpacketCount:130, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  903): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/NetworkPolicy(  903): updateScreenOn: false
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
I/ActivityManager(  903): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4279 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  903): acquireWL(42bf9168): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  903): releaseWL(42bf9168): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): acquireWL(42bfa788): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42bfa788): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/ContextImpl( 4279): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1782): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1782): onScreenOn: 1454414842744
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1782): onScreenOn: 1454414842744
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4248fea8
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 2
W/SensorService(  903): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  903): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4248fea8, eanble = 0, strlen(mName) = 91
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  903): Listener[0] = com.htc.smartdim.sensor_eye@422fbab8
,W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  903): goingToSleep
D/PMS     (  903): acquireWL(42bfe370): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4279 1000 null
D/PMS     (  903): acquireWL(42bfec38): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 903 1000 null
,D/PMS     (  903): releaseWL(42bfe370): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4279): isEpsOn(), nState = 0
D/AlarmManager(  903): ACTION_SCREEN_OFF
I/AlarmManager(  903): [AlarmQueuing] screen off now: 
I/AlarmManager(  903): [AlarmQueuing] data connection: true
,I/AlarmManager(  903): [AlarmQueuing] wifi connection: true
D/WifiDataStallTracker(  903): onReceive: action=android.intent.action.SCREEN_OFF
I/FeedHostManager( 1271): [onPause]
I/FeedProviderManager( 1271): onPause
D/WifiDataStallTracker(  903): stopDataStallAlarm: current tag=19480 mDataStallAlarmIntent=PendingIntent{42501248: PendingIntentRecord{42947510 android broadcastIntent}}
I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@420f1960
I/SocialFeedProvider( 1271): +onPause
,I/SocialFeedProvider( 1271): -onPause
D/WifiNative-wlan0(  903): doBoolean: SET_SCREEN_ON 0
D/WifiNative-wlan0(  903): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1186): SET_SCREEN_ON:Off
I/wpa_supplicant( 1186): htc_wext_set_keepalive +
I/wpa_supplicant( 1186): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1186): getPrivFuncNum +	
I/wpa_supplicant( 1186): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1186): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1186): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1186): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1186): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  903):    returned true
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023245
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023518
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023602
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023606
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023609
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023614
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025112
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360027812
D/PMS     (  903): acquireWL(42c40c20): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 903 1000 null
,D/PMS     (  903): releaseWL(42bfec38): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,V/SRS_Proc(  373): ParamSet string: screen_state=off
D/NetworkPolicy(  903): updateScreenOn: false
,D/ContactMessageStore( 1236): start background delete task...
D/ContactMessageStore( 1236): size: 0 , 0
,D/ContactMessageStore( 1236): Background delete complete
,D/SmartSyncUtils( 4279): getMobilePolicyEnabled, result = true
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  903): killProcessQuiet, pid=3961
,I/ActivityManager(  903): Killing 3961:com.htc.updater/u0a85 (adj 15): empty #17
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/wpa_supplicant( 1186): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  903):    returned true
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  903): releaseWL(42c40c20): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
I/ActivityManager(  903): Recipient 3961
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,W/ContextImpl( 4279): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/SmartSyncUtils( 4279): isEpsOn(), nState = 0
D/SmartSyncUtils( 4279): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4279): getMobilePolicyEnabled, result = true
D/AutoSetting( 1339): service - mHandler: cancel location update
,D/AutoSetting( 1339): service -           changes count: 0
I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@422fbab8
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  903): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  903): pid=903, uid=1000
,W/SensorService(  903): Active sensors: size = 1
W/SensorService(  903): CM36282 Proximity sensor (handle=0x00000001, connections=1)
D/WifiService(  903): New client listening to asynchronous messages
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@422fbab8, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  903): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  903): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  903): pid=903, uid=1000
W/SensorService(  903): Active sensors: size = 0
W/SensorService(  903): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@422fbab8, eanble = 0, strlen(mName) = 36
W/SensorService(  903): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  903): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  903): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@422fbab8
E/ActivityThread(  903): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4280ae78 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  903): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4280ae78 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  903): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  903): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  903): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  903): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  903): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  903): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  903): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  903): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  903): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  903): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  903): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  903): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  903): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  903): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  903): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  903): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  903): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  903): 	at dalvik.system.NativeStart.main(Native Method)
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] getTotalRam: 1873 Mb
D/PMS     (  903): acquireWL(42c727c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(42c727c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): acquireWL(42c73d10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1782): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1782): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1782): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1782): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1782): onScreenOff
D/PMS     (  903): releaseWL(42c73d10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1517): service - handleMessage() stop self
,D/AutoSetting( 1517): service - onDestroy() END
,D/AutoSetting( 1517): service - handleMessage() quit looper
,D/Process (  903): killProcessQuiet, pid=3575
,I/ActivityManager(  903): Killing 3575:com.google.android.gms.unstable/u0a29 (adj 15): empty #17
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Recipient 3575
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  903): killProcessQuiet, pid=3857
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 3857:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 3857
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(42bc5e78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  903): sending alarm PendingIntent{42ae5ba0: PendingIntentRecord{428d6330 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=122629, Int=0
,D/PMS     (  903): releaseWL(42bc5e78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42bc7c08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1356/10029)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/PMS     (  903): acquireWL(42bcda88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42bcda88): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42bc7c08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42cacd90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023245
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023518
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023602
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023606
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023609
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023614
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025112
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025123
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360027812
,D/PMS     (  903): releaseWL(42cacd90): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42cb0d28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1356/10029)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023245
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023518
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023602
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023606
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023609
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023614
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025112
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025123
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360027812
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/PMS     (  903): acquireWL(42cb96b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42cc1d20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1219): Vacuum at: now=1454414859270 tag=VacuumService
,D/PMS     (  903): releaseWL(42cb0d28): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42cb96b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42ccc4e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42cc1d20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023245
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023518
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023602
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023606
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023609
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023614
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025112
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025123
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360027812
,D/PMS     (  903): releaseWL(42ccc4e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42cd0c30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1356/10029)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023245
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023518
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023602
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023606
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023609
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023614
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025112
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025123
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360027812
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/PMS     (  903): releaseWL(42cd0c30): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): acquireWL(42cd7a80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023245
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023518
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023602
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023606
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023609
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023614
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025112
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025123
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360027812
,D/PMS     (  903): releaseWL(42cd7a80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42cdba18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1356/10029)
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023245
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023518
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023602
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL,
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023606
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023609
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023614
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025112
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360027812
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): releaseWL(42cdba18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42ce2910): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1356/10029)
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023245
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023518
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023602
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023606
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023609
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023614
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025112
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360027812
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): acquireWL(42ceb7b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42cf2900): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): releaseWL(42ce2910): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  903): releaseWL(42ceb7b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42c82ad8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023245
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023518
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023602
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023606
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023609
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023614
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025112
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025123
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360027812
,D/PMS     (  903): releaseWL(42c82ad8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1219): Scheduling Phenotype for one-off execution 13390 seconds from now (1454414860215)
,D/GetConfigurationSnapshotOperation( 1219): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1219): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1219): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1219): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1219): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1219): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1219): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  903): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
W/dalvikvm( 1219): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/libc    ( 1219): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1219): [NET] getaddrinfo-,err=8
D/libc    ( 1219): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    ( 1219): [NET] getaddrinfo-, 1
,D/libc    ( 1219): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =987a +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1219): [NET] getaddrinfo_proxy-, success
,D/libc    ( 1219): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1219): [NET] getaddrinfo-,err=8
D/libc    ( 1219): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1219): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  903): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [6][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [1][0][0]
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.google.android.gms (1219/10029)
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
,D/PMS     (  903): releaseWL(42cf2900): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(42c12610): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023245
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023518
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023602
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023606
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023609
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023614
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025112
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025123
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360027812
,D/PMS     (  903): releaseWL(42c12610): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms},
,D/PMS     (  903): acquireWL(42c122c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
,W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1186): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  903): doString: SIGNAL_POLL
W/WifiHW  (  903): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1186): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  903): getActiveNetworkInfo called by  (1356/10029)
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1186): nl80211: survey data missing!
E/wpa_supplicant( 1186): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1186): environment dirty rate=0 [0][0][0]
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023245
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023518
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023602
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023606
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023609
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023614
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025112
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025123
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360027812
,D/PMS     (  903): releaseWL(42c122c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  903): acquireWL(428aa008): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(428aa008): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(427fe520): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  903): sending alarm PendingIntent{42260af8: PendingIntentRecord{42b560a8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=136525, Int=0
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1356/10029)
,D/AutoSetting( 1339): service - handleMessage() stop self
D/PMS     (  903): releaseWL(427fe520): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1339): service - onDestroy() END
,D/Process (  903): killProcessQuiet, pid=2697
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  903): Killing 2697:com.htc.sense.mms/u0a65 (adj 15): empty #17
D/AutoSetting( 1339): service - handleMessage() quit looper
,I/ActivityManager(  903): Recipient 2697
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(42949fe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{42912310: PendingIntentRecord{4270bf20 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140970, Int=0
,D/GpsLocationProvider(  903): ALARM_XTRA_TIMEOUT
D/PMS     (  903): acquireWL(428b55d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 903 1000 null
,D/PMS     (  903): releaseWL(42949fe8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA
D/GpsLocationProvider(  903): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  903): [NET] getaddrinfo-,err=8
D/libc    (  903): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  903): [NET] getaddrinfo-, 1
,D/libc    (  903): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =aeb7 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 8
D/libc    (  365): [NET]res_nsend:resplen=238
D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  903): [NET] getaddrinfo_proxy-, success
I/global  (  903): call createSocket() return a new socket.,
D/libc    (  903): [NET] getaddrinfo+,hn 12(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  903): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  903): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  903): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  903): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  903):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  903): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/PMS     (  903): acquireWL(42895c38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{426ab068: PendingIntentRecord{420b4058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=143617, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42895c38): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): releaseWL(428b55d8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  903): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  903): acquireWL(4291e698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(4291e698): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
,D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  903): acquireWL(42ab8140): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{10027}
,V/AlarmManager(  903): sending alarm PendingIntent{42ab1618: PendingIntentRecord{42b972b0 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=173843, Int=0
,D/PMS     (  903): releaseWL(42ab8140): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1236): switchBindHtcMsgCursor: null
,D/PMS     (  903): acquireWL(429f8220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(429f8220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,I/ClearcutLoggerApiImpl( 1356): disconnect managed GoogleApiClient
,D/PMS     (  903): acquireWL(4297d8e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{426ab068: PendingIntentRecord{420b4058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=203617, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(4297d8e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(42af9dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42af9dd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  903): acquireWL(42bbdc68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{426ab068: PendingIntentRecord{420b4058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=263617, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42bbdc68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(429981c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(429981c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(42b5a900): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{426ab068: PendingIntentRecord{420b4058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=323617, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42b5a900): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  903): killProcessQuiet, pid=4123
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4123:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4123
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(42c52ec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42c52ec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  903): acquireWL(42a3caa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{426ab068: PendingIntentRecord{420b4058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=383617, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42a3caa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(42c412c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42c412c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(42b23aa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{426ab068: PendingIntentRecord{420b4058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=443617, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42b23aa0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  903): acquireWL(42b313a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42b313a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  903): acquireWL(42893528): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{426ab068: PendingIntentRecord{420b4058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=503617, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42893528): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  903): acquireWL(42888318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42888318): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  903): acquireWL(42b21710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42b21710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(429e71a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{426ab068: PendingIntentRecord{420b4058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=563617, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(429e71a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42aa7f38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42aa7f38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1236): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1236): mDeleteTask = null, bDeleting = false
,D/AccFlag ( 1236): sku_id=99
D/ContactMessageStore( 1236): start background delete task...
,D/ContactMessageStore( 1236): MSG_CHECK_DELETION <<
D/ContactMessageStore( 1236): size: 0 , 0
,D/ContactMessageStore( 1236): Background delete complete
,D/PMS     (  903): acquireWL(42800c00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{426ab068: PendingIntentRecord{420b4058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=623616, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42800c00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42a9dbd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42a9dbd8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(42c5c940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{426ab068: PendingIntentRecord{420b4058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=683617, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42c5c940): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42a48e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42a48e48): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(42cbe540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{426ab068: PendingIntentRecord{420b4058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=743617, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42cbe540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4294fb50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4294fb50): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(42afbe48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{426ab068: PendingIntentRecord{420b4058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=803617, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42afbe48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(428577a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(428577a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  903): acquireWL(42cca400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{426ab068: PendingIntentRecord{420b4058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=863616, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42cca400): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42aacc38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42aacc38): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
,D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(422fd2f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{426ab068: PendingIntentRecord{420b4058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=923617, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(422fd2f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(422fbe48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{4212cbc8: PendingIntentRecord{42907f20 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=782991, Int=0
,V/AlarmManager(  903): sending alarm PendingIntent{427ff930: PendingIntentRecord{42a48c38 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.HEARTBEAT_ALARM, t=2, cnt=1, w=948083, Int=0
,D/ConnectivityService(  903): Sampling interval elapsed, updating statistics ..
,D/PMS     (  903): acquireWL(42be5980): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  903): Done.
D/ConnectivityService(  903): Setting timer for 720seconds
,D/PMS     (  903): releaseWL(42be5980): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  903): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4333 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
,V/AlarmManager(  903): sending alarm PendingIntent{423874a8: PendingIntentRecord{42931988 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1454414947175, Int=10800000
,V/AlarmManager(  903): sending alarm PendingIntent{421411f0: PendingIntentRecord{42a732d0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1454415667594, Int=900000
,W/ContextImpl( 4279): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4279): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 4279): MY_DEBUG = false
D/PMS     (  903): releaseWL(422fbe48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/ConnectivityService(  903): getActiveNetworkInfo called by com.htc.aurora (4333/10049)
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023245
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023518
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023602
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023606
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023609
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023614
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025112
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025123
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360027812
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/PMS     (  903): acquireWL(42b01e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42b01e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,W/BatSI   (  903): Couldn't get kernel wake lock stats
,D/Process (  903): killProcessQuiet, pid=4066
,D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  903): Killing 4066:com.google.android.talk/u0a111 (adj 15): empty #17
,I/ActivityManager(  903): Recipient 4066
,I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  903): acquireWL(42daf210): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1356 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1356/10029)
,D/ConnectivityService(  903): reportInetCondition for net 1, percentage: 100 by  (1356/10029)
,D/ConnectivityService(  903): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  903): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  903): getActiveNetworkInfo called by  (1356/10029)
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023245
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023518
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023602
W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023606
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023609
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360023614
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025112
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360025123
,W/AlarmManager(  903): Converted elapesd time is over 1 year! when = 315360027812
,D/PMS     (  903): releaseWL(42daf210): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  903): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  903): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  903): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/PMS     (  903): acquireWL(42d9ff70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42d9ff70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42d7ca28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{426ab068: PendingIntentRecord{420b4058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=983616, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42d7ca28): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42d769c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,D/SmartSyncUtils( 4279): isEpsOn(), nState = 0
V/AlarmManager(  903): sending alarm PendingIntent{421b9590: PendingIntentRecord{42c0ae10 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1454415742865, Int=0
,D/PMS     (  903): releaseWL(42d769c0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42d72270): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4279 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4279): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4279): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
D/SmartSyncScreenOnOffTimeReceiver( 4279): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4279): SettingOnTime = 1454479200000, randomSettingOnTime = 1454478198000
,D/SmartSyncScreenOnOffTimeReceiver( 4279): SettingOffTime = 1454464800000, randomSettingOffTime = 1454465090000
D/SmartSyncScreenOnOffTimeReceiver( 4279): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4279): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4279): bNightModeTurnOffOnce = false
,D/PMS     (  903): releaseWL(42d72270): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  903): acquireWL(42d71280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): releaseWL(42d71280): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42d65ef8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42d65ef8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42d623b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{426ab068: PendingIntentRecord{420b4058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1043616, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42d623b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42d61db0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42d61db0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
W/ContextImpl( 4279): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 3778): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3778): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3778): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3778): Cust_ConnectToPC   : spcsc>false
D/        ( 3778): Cust_ConnectToPC   : IPT>true
,D/        ( 3778): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 3778): project = Verizon, plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 3778): Index of the first 1 = 3
,W/ContextImpl( 3778): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3778): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3778): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3778): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3778): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3778): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3778): [ACC]android_networking:tethering_guard_support=false
I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42d5f938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{426ab068: PendingIntentRecord{420b4058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1103617, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42d5f938): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42d5f638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42d5f638): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
,I/HtcPowerSaver(  903): >> updateStatus
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42d5df98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42d5df98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42d5cc78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{426ab068: PendingIntentRecord{420b4058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1163616, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42d5cc78): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(42d5c748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(42d5c748): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  903): updateBatteryInfo
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(42d5b478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/PMS     (  903): releaseWL(42d5b478): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  903): << updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  358): inotify_add_watch failed. (No such file or directory),
,D/PMS     (  903): acquireWL(42a6ab88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 903 1000 WorkSource{1000}
,V/AlarmManager(  903): sending alarm PendingIntent{426ab068: PendingIntentRecord{420b4058 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1223617, Int=0
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  903): releaseWL(42a6ab88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  903): acquireWL(4295d710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(4295d710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  903): updateBatteryInfo
,D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  903): acquireWL(421c3848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  903): n_update end
,D/PMS     (  903): releaseWL(421c3848): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  903): BroadcastReceiver::onReceive+
D/UsbnetService(  903): onReceive BATTERY_CHANGED
D/UsbnetService(  903):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  903): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  903): updateBatteryInfo
D/PMS     (  903): runPSCheck
D/HtcPowerSaver(  903): Checking...
I/HtcPowerSaver(  903): >> updateStatus
,I/HtcPowerSaver(  903): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  903): << updateStatus
I/IntentController( 1112): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1590): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1590): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1112): closing low battery warning: level=100
D/PowerUI ( 1112): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/BatteryController( 1112): status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4362): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4362): ====startRecUseTime====
D/htc.customization.log.level( 4362):  is 
W/CustomizationLogLevel( 4362): Level value is invalid, use default level 2
D/CustomizationManager( 4362):  Read ACC file spent 0.067 (s)
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4362): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4362): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4362): Parsing tag category name = system
I/CustomizationCIDLoader( 4362): Parsing tag category name = application
I/CustomizationCIDLoader( 4362): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4362): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4362): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4362): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4362): Parsing tag category name = Settings
D/CustomizationManager( 4362):  Read CID file spent 0.106 (s)
D/CustomizationManager( 4362):  All configurations done spent 0.106 (s)
W/HtcNativeFlag( 4362): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4362): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4362): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4362): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  903): deletePackageAsUser: pkg=com.test.thalitest, pid=4362, uid=2000 user=0
I/ActivityManager(  903): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
W/PackageSettings(  903): Skipping PackageSetting{425d36e8 com.example.hello/10397} due to missing metadata
W/PackageSettings(  903): Skipping PackageSetting{425d7358 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  903): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
W/PackageManager(  903): Package source /data/app/com.test.thalitest-2.apk does not exist.
W/PackageManager(  903): Couldn't delete native library directory /data/app-lib/com.test.thalitest-2
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1590): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
D/DotMatrix( 1590): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1590): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver replacing:false
W/GeofencerStateMachine( 1219): Ignoring removeGeofence because network location is disabled.
D/PMS     (  903): acquireWL(42dc7400): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1219 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  903): releaseWL(42dc7400): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1327): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/VoicemailCleanupService( 1283): Cleaning up data for package: com.test.thalitest
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
W/SystemReader( 1252): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "smsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/[PluginManager]RegisterService( 1339): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/[PluginManager]RegisterService( 1339): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1271): action: android.intent.action.PACKAGE_REMOVED
W/AccTypeManager( 1327): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1327): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "sms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
E/ExternalAccountType( 1327): Unsupported attribute readOnly
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "smsto"
I/IcingCorporaProvider( 2812): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mms"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
I/PackageManager(  903):   Action: "android.intent.action.SENDTO"
I/PackageManager(  903):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  903):   Scheme: "mmsto"
I/PackageManager(  903): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1236 :
D/PhoneApp( 1236): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  903): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4376 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/IcingCorporaProvider( 2812): UpdateCorporaTask done [took 73 ms] updated apps [took 73 ms] 
I/InputMethodManagerService(  903): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
W/PackageManager(  903): Unable to load service info ResolveInfo{42b83068 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  903): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  903): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  903): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  903): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  903): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  903): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  903): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  903): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  903): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  903): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  903): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  903): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 4376): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4376): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4376): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4376): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4376): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4376): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4376): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4376): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4376): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4376): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4376): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4376): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4376): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4376): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4376): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4376): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4376): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4376): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4376): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4376): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4376): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4376): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4376): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4376): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4376): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4376): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4376): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4376): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4376): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4376): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4376): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4376): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4376): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4376): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4376): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4376): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4376): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4376): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4376): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4376): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4376): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4376): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4376): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4376): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4376): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4376): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4376): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4376): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4376): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4376): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4376): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4376): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4376): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4376): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4376): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4376): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4376): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4376): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4376): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4376): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4376): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4376): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4376): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4376): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4376): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4376): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4376): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4376): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4376): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4376): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4376): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4376): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4376): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4376): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4376): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4376): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4376): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4376): threadid=11: thread exiting with uncaught exception (group=0x41b46e30)
E/AndroidRuntime( 4376): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4376): Process: com.google.android.apps.docs, PID: 4376
E/AndroidRuntime( 4376): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4376): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4376): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4376): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4376): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4376): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4376): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4376): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4376): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4376): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4376): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4376): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4376): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4376): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4376): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4376): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4376): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4376): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4376): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  903): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop139.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  903): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  903): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  903): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  903): 	... 5 more
E/SQLiteDatabase( 4376): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4376): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4376): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4376): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4376): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4376): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4376): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4376): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4376): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4376): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4376): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4376): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4376): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4376): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4376): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4376): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4376): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4376): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4376): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4376): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4376): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4376): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4376): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4376): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4376): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4376): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4376): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4376): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4376): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4376): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4376): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4376): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4376): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4376): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4376): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4376): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4376): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4376): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4376): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4376): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4376): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4376): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4376): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4376): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4376): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4376): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4376): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4376): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4376): Opened ClientFlag.db in read-only mode
I/ActivityManager(  903): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4394 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4376): killProcess, pid=4376
D/Process ( 4376): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  903): Recipient 4376
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Process com.google.android.apps.docs (pid 4376) has died.
D/RemoteDisplayProvider(  903): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  903): start
W/AtomicFile(  903): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  903): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/ContextImpl( 4394): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4394): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4394): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4394): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4394): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4394): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4394): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4394): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4394): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4394): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4394): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4394): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4394): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4394): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4394): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4394): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4394): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4394): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4394): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4394): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4394): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4394): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4394): threadid=11: thread exiting with uncaught exception (group=0x41b46e30)
E/ActivityManager(  903): App crashed! Process: com.android.keychain
I/ActivityManager(  903): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4408 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/AndroidRuntime( 4394): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4394): Process: com.android.keychain, PID: 4394
E/AndroidRuntime( 4394): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4394): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4394): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4394): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4394): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4394): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4394): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4394): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4394): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4394): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4394): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4394): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4394): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4394): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4394): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4394): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4394): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4394): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4394): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4394): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ErrorReport(  903): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4394): killProcess, pid=4394
D/Process ( 4394): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  903): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  903): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1454416014318.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  903): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  903): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  903): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  903): 	... 4 more
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  903): Recipient 4394
I/ActivityManager(  903): Process com.android.keychain (pid 4394) has died.
W/ActivityManager(  903): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 4408): getInstance(Context context)
D/AppTag  ( 4408): getInstance(Context context)
D/AppTag  ( 4408): onCreate()
D/PMS     (  903): acquireWL(429fd0d0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3560 10160 null
D/PMS     (  903): releaseWL(429fd0d0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
D/Process (  903): killProcessQuiet, pid=3609
W/dalvikvm( 3993): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/Process (  903): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  903): Killing 3609:com.htc.task/u0a71 (adj 15): empty #17
D/PackageBroadcastService( 2177): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2177): Clearing selected account for com.test.thalitest
I/ActivityManager(  903): Recipient 3609
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ChimeraCfgMgr( 2177): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2177): Loading module APK com.google.android.play.games
I/LocationSettingsChecker( 2177): Removing dialog suppression flag for package com.test.thalitest
W/dalvikvm( 2177): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
E/SQLiteDatabase( 2177): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 2177): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2177): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2177): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2177): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2177): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 2177): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2177): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2177): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2177): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/PhenotypeInitializer( 2177): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 2177): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/PhenotypeInitializer( 2177): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/PhenotypeInitializer( 2177): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2177): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 2177): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 2177): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 2177): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 2177): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 2177): 	at android.os.Looper.loop(Looper.java:157)
E/PhenotypeInitializer( 2177): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 2177): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
E/dalvikvm( 2177): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
W/dalvikvm( 2177): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
W/dalvikvm( 2177): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
I/GMPM-SVC( 2177): App measurement is starting up, version: 8489
I/GMPM-SVC( 2177): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
E/SQLiteLog( 2177): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2177): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5ca87880
I/ActivityManager(  903): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/DriveAsyncService( 2177): disk I/O error (code 3850)
E/DriveAsyncService( 2177): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2177): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2177): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2177): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2177): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2177): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2177): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2177): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2177): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2177): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2177): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2177): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2177): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2177): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2177): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2177): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 2177): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2177): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/pluscontacts.db, handle = 0x66611710
W/dalvikvm( 2177): threadid=48: thread exiting with uncaught exception (group=0x41b46e30)
D/ChimeraCfgMgr( 2177): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2177): Module APK com.google.android.play.games already loaded
E/SQLiteDatabase( 2177): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 2177): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2177): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2177): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2177): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 2177): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 2177): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 2177): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 2177): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2177): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2177): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2177): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 2177): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 2177): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2177): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2177): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2177): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2177): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2177): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2177): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2177): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2177): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2177): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2177): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2177): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2177): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2177): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2177): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 2177): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 2177): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 2177): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 2177): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 2177): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 2177): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 2177): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  903): App crashed! Process: com.google.android.gms
D/Process ( 2177): killProcess, pid=2177
E/SQLiteDatabase( 2177): Failed to open database '/data/data/com.google.android.gms/databases/google_app_measurement.db'.
E/SQLiteDatabase( 2177): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2177): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2177): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2177): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2177): 	at com.google.android.gms.measurement.internal.h.getWritableDatabase(SourceFile:2307)
E/SQLiteDatabase( 2177): 	at com.google.android.gms.measurement.internal.e.e(SourceFile:418)
E/SQLiteDatabase( 2177): 	at com.google.android.gms.measurement.internal.e.a(SourceFile:357)
E/SQLiteDatabase( 2177): 	at com.google.android.gms.measurement.internal.aq.s(SourceFile:1591)
E/SQLiteDatabase( 2177): 	at com.google.android.gms.measurement.internal.aq.p(SourceFile:1605)
E/SQLiteDatabase( 2177): 	at com.google.android.gms.measurement.internal.aq.c(SourceFile:306)
E/SQLiteDatabase( 2177): 	at com.google.android.gms.measurement.internal.ar.run(SourceFile:195)
E/SQLiteDatabase( 2177): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 2177): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 2177): 	at com.google.android.gms.measurement.internal.ap.run(SourceFile:294)
E/GMPM-SVC( 2177): Opening the database failed, dropping and recreating it
E/AndroidRuntime( 2177): FATAL EXCEPTION: IntentService[PeopleBackgroundTasks]
E/AndroidRuntime( 2177): Process: com.google.android.gms, PID: 2177
E/AndroidRuntime( 2177): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2177): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2177): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2177): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2177): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2177): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2177): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2177): 	at com.google.android.gms.people.c.e.a(SourceFile:110)
E/AndroidRuntime( 2177): 	at com.google.android.gms.people.sync.a.b.d(SourceFile:3165)
E/AndroidRuntime( 2177): 	at com.google.android.gms.people.service.bg.b.a(SourceFile:245)
E/AndroidRuntime( 2177): 	at com.google.android.gms.people.service.bg.PeopleBackgroundTasks.onHandleIntent(SourceFile:77)
E/AndroidRuntime( 2177): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2177): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2177): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2177): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  903): acquireWL(42c75988): PARTIAL_WAKE_LOCK  Icing 0x1 2177 10029 WorkSource{10029 com.google.android.gms}
E/DropBoxManagerService(  903): Can't write: system_app_crash
E/DropBoxManagerService(  903): java.io.FileNotFoundException: /data/system/dropbox/drop141.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  903): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  903): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  903): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  903): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  903): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  903): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  903): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  903): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  903): 	... 5 more
W/SQLiteOpenHelper( 2177): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 2177): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 2177): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/Process ( 2177): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/DisplayManagerService(  903): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  903): handleWLDeath(42c75988): PARTIAL_WAKE_LOCK  Icing 0x1
D/WifiService(  903): Client connection lost with reason: 4
I/ActivityManager(  903): Recipient 2177
I/ActivityManager(  903): Process com.google.android.gms (pid 2177) has died.
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 1000ms
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 11000ms
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.AppsMonitorIntentService in 10999ms
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 20999ms
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20999ms
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 20998ms
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 30998ms
W/ActivityManager(  903): Scheduling restart of crashed service com.google.android.gms/.icing.proxy.UpdateIcingCorporaService in 30998ms

```
