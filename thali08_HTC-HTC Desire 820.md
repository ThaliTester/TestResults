#### Test 50242285ae22b3b_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
E/Prism.WidgetManager( 1271): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1271): onLoadItems() -
I/Prism.ItemManager( 1271): loadItems() com.htc.launcher.pageview.WidgetManager@41b5aed0 -
D/PhoneApp( 1245): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1245): -- N1 =0
D/PhoneApp( 1245): -- N2 =0
D/PhoneApp( 1245): -- N3 =0
D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC <<
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [5][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
--------- beginning of /dev/log/system
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start
D/WIFI_ICON( 1117): WifiActivity: 3
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
I/GAV2    ( 3046): Thread[GAThread,5,main]: No campaign data found.
W/WeatherUtility( 1117): can't get weather sync account
I/ActivityManager(  907): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3306 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
W/WeatherRequest( 1117): request cur loc, but there is no sys cur
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
D/browser ( 3306): Browser versionCode = 760001523 versionName = 7.0.2512153020
W/SWE_UI  ( 3306): SWE using SurfaceView - Multi-Process
I/LibraryLoader( 3306): Loading: swewebviewchromium
I/LibraryLoader( 3306): Time to load native libraries: 42 ms (timestamps 2202-2244)
I/LibraryLoader( 3306): Expected native library version number "",actual native library version number ""
I/BrowserStartupController( 3306): Initializing chromium process, renderers=9
I/LibraryLoader( 3306): Expected native library version number "",actual native library version number ""
I/chromium( 3306): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
I/Adreno-EGL( 3306): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3306): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3306): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3306): Local Branch: 
I/Adreno-EGL( 3306): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3306): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3306):                  aa63bbd948f41d15fc72f585e
D/Process (  907): killProcessQuiet, pid=3014
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3014:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
V/IccIntentReceiver( 1298): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/SIMStateChangeReceiver( 1512): SIM state: ABSENT
I/SIMStateChangeReceiver( 1512): phoneType = 0
I/SIMStateChangeReceiver( 1512): remove notification
I/ActivityManager(  907): Recipient 3014
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3346 uid=10031 gids={50031, 3003, 5012}
D/Process (  907): killProcessQuiet, pid=3046
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3358 uid=10041 gids={50041, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
I/ActivityManager(  907): Killing 3046:com.google.android.gm/u0a107 (adj 15): empty #17
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3046
W/SystemReader( 2791): Cannot find message_ambs_application_id, use default value instead
D/SmsReceiver( 2791): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
D/ExchangePolicystatus( 2791): onReceive()
D/ExchangePolicystatus( 2791): onReceive(): ACTION_SIM_STATE_CHANGED
D/ExchangePolicystatus( 2791): onReceive(): else
D/Process (  907): killProcessQuiet, pid=2406
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 2406:com.android.defcontainer/u0a19 (adj 15): empty #17
D/HtcBroadcastReceiver( 1245): onReceive: android.intent.action.SIM_STATE_CHANGED
I/ActivityManager(  907): Recipient 2406
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3373 uid=10038 gids={50038}
W/AccTypeManager( 3358): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 3358): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/AccTypeManager( 3358): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  907): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=3388 uid=10091 gids={50091, 3003, 5012}
V/AlarmManager(  907): sending alarm PendingIntent{4245bf30: PendingIntentRecord{424f4cb8 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=53677, Int=0
D/Process (  907): killProcessQuiet, pid=3082
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3400 uid=10077 gids={50077}
I/ActivityManager(  907): Killing 3082:com.htc.backup/1000 (adj 15): empty #17
I/ActivityManager(  907): Recipient 3082
E/ExternalAccountType( 3358): Unsupported attribute readOnly
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WIFI_ICON( 1117): WifiActivity: 1
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
W/AccTypeManager( 3358): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 3358): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/SMSBackup( 3400): Got a database change event
D/AccTypeManager( 3358): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  907): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3415 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
D/Process (  907): killProcessQuiet, pid=3029
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/HtcModeClient( 1512): handler message = 4011
E/HtcModeClient( 1512): Check connection and retry 5 times.
I/ActivityManager(  907): Killing 3029:com.htc.cs.dm/u0a98 (adj 15): empty #17
I/ActivityManager(  907): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3427 uid=10091 gids={50091, 3003, 5012}
,E/ExternalAccountType( 3358): Unsupported attribute readOnly
D/CalendarApplication( 3415): onCreate
D/ProviderChangeReceiver( 3415): ---------------------------------------------------
D/ProviderChangeReceiver( 3415): ProviderChangeReceiver onReceive, start to update notification!
D/AlertService( 3415): start to updateAlertNotification!
W/ContextImpl( 3177): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
D/GCM     ( 1365): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AlertService( 3415): No fired or scheduled alerts
D/HtcAlertUtils( 3415): -- cancelReminderNotification --
D/HtcAlertUtils( 3415): broadcastExistReminder!
D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  907): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Recipient 3029
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1822/10178)
D/Process (  907): killProcessQuiet, pid=3105
I/ActivityManager(  907): Killing 3105:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/AdsMeasurementBroadcastReceiver( 1225): Reporting settings might have changed, alerting AdsMeasurementService
D/AdsMeasurementBroadcastReceiver( 1225): Unauthorized to start the main service
I/ActivityManager(  907): Recipient 3105
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3446 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
D/MdScBoot( 3388): [ca0.1.] 30@-145022 -> 40@-145053
D/Process (  907): killProcessQuiet, pid=3131
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/Process (  907): killProcessQuiet, pid=3148
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3131:com.htc.backupreset/1000 (adj 15): empty #17
I/ActivityManager(  907): Killing 3148:com.htc.htccupd/u0a17 (adj 15): empty #17
I/ActivityManager(  907): Recipient 3131
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3148
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=3461 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
W/WeatherUtility( 3446): can't get weather sync account
W/WeatherRequest( 3446): request cur loc, but there is no sys cur
W/Settings( 3446): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/AppWidgetHostView( 1271): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1271): com.htc.widget.weatherclock (true,33751552)
I/RemoteViews.Performance( 1271): com.htc.widget.weatherclock 1 8 17
I/MusicStore( 3461): Database version: 95
W/ContextImpl( 3461): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
W/ContextImpl( 3461): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3461): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
E/cutils-trace( 3443): Error opening trace file: No such file or directory (2)
E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3461): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3461): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3461, uid=10154, userID:0
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
D/MediaRouterService(  907): Client com.google.android.music (pid 3461): Registered
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
I/MediaRouter( 3461): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.music (3461/10154)
I/NetworkMonitor( 3461): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  907): getActiveNetworkInfo called by  (2460/10021)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
I/ActivityManager(  907): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=3489 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/MediaRouter( 3461): getSelectedRoute
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/NetworkMonitor( 3461): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (3461/10154)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/Process (  907): killProcessQuiet, pid=3163
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=3461, uid=10154, userID:0
I/ActivityManager(  907): Killing 3163:com.zoodles.kidmode/u0a149 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/CustomizationManager( 3443): ====startRecUseTime====
D/htc.customization.log.level( 3443):  is 
W/CustomizationLogLevel( 3443): Level value is invalid, use default level 2
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/ACRA    ( 3489): ACRA is enabled for com.facebook.katana, intializing...
D/ACRA    ( 3489): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
D/ACRA    ( 3489): Looking for error files in /data/data/com.facebook.katana/app_minidumps
D/CustomizationManager( 3443):  Read ACC file spent 0.063 (s)
D/CIDMapFileReader( 3443): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3443): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3443): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3443): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3443): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3443): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3443): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3443): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3443): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3443): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3443): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3443): Parsing tag category name = system
I/CustomizationCIDLoader( 3443): Parsing tag category name = application
I/CustomizationCIDLoader( 3443): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3443): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3443): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3443): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3443): Parsing tag category name = Settings
D/CustomizationManager( 3443):  Read CID file spent 0.109 (s)
D/CustomizationManager( 3443):  All configurations done spent 0.109 (s)
W/HtcNativeFlag( 3443): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3443): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3443): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3443): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  907): Recipient 3163
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/SystemClassLoaderAdder( 3489): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
V/DexLibLoader( 3489): Preparing secondary program dexes.
V/DexLibLoader( 3489): Loaded 4 raw lines of metadata.
V/DexLibLoader( 3489): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 3489): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 3489): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
V/DexLibLoader( 3489): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
W/DexLibLoader( 3489): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 3489): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 3489): Dex already copied
D/OdexVerifier( 3489): Odex verification is skipped.
V/DexLibLoader( 3489): Creating class loader
W/asset   (  907): Copying FileAsset 0x62e30470 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1111328552
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3443
D/PMS     (  907): acquireHCC(4234b3e0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(41f06c60): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
V/DexLibLoader( 3489): Finished creating class loader
V/DexLibLoader( 3489): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 3489): Dex already copied
D/OdexVerifier( 3489): Odex verification is skipped.
V/DexLibLoader( 3489): Creating class loader
I/FeedHostManager( 1271): [onPause]
I/FeedProviderManager( 1271): onPause
I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41fc8d28
I/SocialFeedProvider( 1271): +onPause
I/SocialFeedProvider( 1271): -onPause
D/PMS     (  907): acquireWL(425d0c78): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
V/DexLibLoader( 3489): Finished creating class loader
V/DexLibLoader( 3489): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 3489): Dex already copied
D/OdexVerifier( 3489): Odex verification is skipped.
V/DexLibLoader( 3489): Creating class loader
V/DexLibLoader( 3489): Finished creating class loader
V/DexLibLoader( 3489): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 3489): Dex already copied
D/OdexVerifier( 3489): Odex verification is skipped.
V/DexLibLoader( 3489): Creating class loader
I/ActivityManager(  907): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3506 uid=10356 gids={50356, 3003, 5012, 3001, 3002}
V/DexLibLoader( 3489): Finished creating class loader
V/DexLibLoader( 3489): Verifying classes from secondary dexes.
I/TrimMemoryManager( 1271): [trimMemory] 20
W/asset   ( 3506): Copying FileAsset 0x5c808428 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
V/WebViewChromiumFactoryProvider( 3506): Binding Chromium to main looper Looper (main, tid 1) {41acbd88}
I/LibraryLoader( 3506): Expected native library version number "",actual native library version number ""
I/chromium( 3506): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3506): Initializing chromium process, renderers=0
D/DexLibLoader( 3489): DexLibLoader.ensureDexLoaded took 115 ms
D/PMS     (  907): acquireWL(42536530): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42444800:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3506): 1101928320: getState(). Returning 12
D/PMS     (  907): acquireWL(423c5ba8): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  907): releaseWL(42536530): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3506): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3506): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3506): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3506): Local Branch: 
I/Adreno-EGL( 3506): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3506): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3506):                  aa63bbd948f41d15fc72f585e
W/chromium( 3506): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3506): VFY: unable to resolve virtual method 172: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3506): VFY: unable to resolve virtual method 167: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3506): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3506): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3506): VFY: unable to resolve virtual method 225: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3506): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3506): VFY: unable to resolve virtual method 183: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3506): VFY: unable to resolve virtual method 188: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3506): CordovaWebView is running on device made by: HTC
,W/AwContents( 3506): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  907): Disable input method client, pid=1271
,W/ResourceType( 3506): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3506): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b12bf0, mServedView=org.apache.cordova.engine.SystemWebView{41ad8aa0 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  907): Enable input method client, pid=3506
,I/ActivityManager(  907): Displayed com.example.hello/.MainActivity: +293ms
,W/AwContents( 3506): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1210): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1210): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1210): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  907): releaseWL(425d0c78): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,E/AndroidProtocolHandler( 3506): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/Process (  907): killProcessQuiet, pid=3192
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3192:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/chromium( 3506): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/ActivityManager(  907): Recipient 3192
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/JsMessageQueue( 3506): Set native->JS mode to OnlineEventsBridgeMode
,D/jxcore_app_log( 3506): JniHelper::setJavaVM(0x4159d048), pthread_self() = 1553311704
,D/JX-Cordova( 3506): jxcore cordova android initializing
,W/jxcore-log( 3506): Initializing JXcore engine
,W/jxcore-log( 3506): JXcore engine is ready
,W/jxcore-log( 3506): Starting JXcore engine
,F/libc    ( 3506): Fatal signal 11 (SIGSEGV) at 0x00000000 (code=1), thread 3550 (Thread-347)
,I/DEBUG   (  369): Build fingerprint: 'htc/a51ul_htc_europe/htc_a51ul:4.4.4/KTU84P/484493.2:user/release-keys'
I/DEBUG   (  369): Revision: '0'
I/DEBUG   (  369): pid: 3506, tid: 3550, name: Thread-347  >>> com.example.hello <<<
,I/DEBUG   (  369): debuggerd: checkTellHTCSettings
,V/HtcNativeCrashUtil(  907): Read id1=-1243796867 id2=-217320719, they are start flags. This is HTC header
I/DEBUG   (  369): debuggerd: buildType: user, roAaReport: com, ro.sf: 1
I/DEBUG   (  369): debuggerd: rosf: 1
I/DEBUG   (  369): debuggerd: [New ROM] isShippingROM: true
I/DEBUG   (  369): signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 00000000
,W/dalvikvm( 3489): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3489): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3489): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3489): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3489): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3489): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3489): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,I/DEBUG   (  369):     r0 00000000  r1 00000000  r2 00000000  r3 00000000
,I/DEBUG   (  369):     r4 67836fb0  r5 67836f70  r6 63efef38  r7 67836f70
I/DEBUG   (  369):     r8 00000000  r9 67836fac  sl 67838508  fp 67836f54
I/DEBUG   (  369):     ip 67698ba0  sp 67836f38  lr 6739f308  pc 400a8b7c  cpsr 600d0030
I/DEBUG   (  369):     d0  00000035020000d5  d1  513802003a373e91
I/DEBUG   (  369):     d2  0000b80c03000067  d3  88000000560a1060
I/DEBUG   (  369):     d4  07490c0000003d01  d5  0000008849000000
I/DEBUG   (  369):     d6  0a0e000000b80c0c  d7  01003a0f0000003d
I/DEBUG   (  369):     d8  0000000000000000  d9  0000000000000000
I/DEBUG   (  369):     d10 0000000000000000  d11 0000000000000000
I/DEBUG   (  369):     d12 0000000000000000  d13 0000000000000000
I/DEBUG   (  369):     d14 0000000000000000  d15 0000000000000000,
I/DEBUG   (  369):     d16 796669676e697274  d17 6b636174732e6528
,I/DEBUG   (  369):     d18 0000000000000000  d19 0000000000000000
I/DEBUG   (  369):     d20 3e92819b25c7ba0a  d21 3ec722949499b49c
I/DEBUG   (  369):     d22 3efa019fabb79d95  d23 3f2a019f8723aeaa
I/DEBUG   (  369):     d24 3f56c16c16c76a94  d25 3f81111111185da8
I/DEBUG   (  369):     d26 3fa555555555551c  d27 3fc55555555554db
I/DEBUG   (  369):     d28 3fe0000000000000  d29 0000000000000001
I/DEBUG   (  369):     d30 fff0000000000000  d31 0000000000000000
I/DEBUG   (  369):     scr 88000012
I/DEBUG   (  369): 
I/DEBUG   (  369): backtrace:
I/DEBUG   (  369):     #00  pc 00023b7c  /system/lib/libc.so (strlen+83)
I/DEBUG   (  369):     #01  pc 007da304  /data/app-lib/com.example.hello-1/libjxcore.so (MozJS::String::FromUTF8(JSContext*, char const*, int)+40)
I/DEBUG   (  369): 
I/DEBUG   (  369): stack:
I/DEBUG   (  369):          67836ef8  67a2b040  
I/DEBUG   (  369):          67836efc  63de8cc0  
I/DEBUG   (  369):          67836f00  657f43e0  
I/DEBUG   (  369):          67836f04  00000001  
I/DEBUG   (  369):          67836f08  67a49160  
I/DEBUG   (  369):          67836f0c  63efef38  
I/DEBUG   (  369):          67836f10  67a4f1c0  
I/DEBUG   (  369):          67836f14  00000000  
I/DEBUG   (  369):          67836f18  00000000  
I/DEBUG   (  369):          67836f1c  00000000  
I/DEBUG   (  369):          67836f20  00000003  
I/DEBUG   (  369):          67836f24  000000aa  
I/DEBUG   (  369):          67836f28  0000006b  
I/DEBUG   (  369):          67836f2c  0001416e  
I/DEBUG   (  369):          67836f30  e3a070ad  
I/DEBUG   (  369):          67836f34  ef9000ad  
I/DEBUG   (  369):     #00  67836f38  00000000  
I/DEBUG   (  369):          ........  ........
I/DEBUG   (  369):     #01  67836f38  00000000  
I/DEBUG   (  369):          67836f3c  67836f94  [stack:3550]
I/DEBUG   (  369):          67836f40  67836fb0  [stack:3550]
I/DEBUG   (  369):          67836f44  67836f94  [stack:3550]
I/DEBUG   (  369):          67836f48  67836f80  [stack:3550]
I/DEBUG   (  369):          67836f4c  00000000  
I/DEBUG   (  369):          67836f50  67837fcc  [stack:3550]
I/DEBUG   (  369):          67836f54  673763f0  /data/app-lib/com.example.hello-1/libjxcore.so
I/DEBUG   (  369):          67836f58  67836f88  [stack:3550]
I/DEBUG   (  369):          67836f5c  00000000  
I/DEBUG   (  369):          67836f60  67836f7c  [stack:3550]
I/DEBUG   (  369):          67836f64  671a8184  /data/app-lib/com.example.hello-1/libjxcore.so (js_fun_call(JSContext*, unsigned int, JS::Value*)+172)
I/DEBUG   (  369):          67836f68  00000000  
I/DEBUG   (  369):          67836f6c  00000000  
I/DEBUG   (  369):          67836f70  400d738c  
I/DEBUG   (  369):          67836f74  00000000  
I/DEBUG   (  369): 
I/DEBUG   (  369): memory near r4:
I/DEBUG   (  369):     67836f90 67a51d80 67a53b00 63efef38 00000000  
I/DEBUG   (  369):     67836fa0 657f42d0 657f42e0 00000001 400d002f  
I/DEBUG   (  369):     67836fb0 00001000 400d738c 00001000 63efef38  
I/DEBUG   (  369):     67836fc0 657f4378 67836fd8 67837354 67284ab0  
I/DEBUG   (  369):     67836fd0 00000002 00000000 657f4378 00000000  
I/DEBUG   (  369):     67836fe0 6768af28 00000001 67a53b00 67836fd8  
I/DEBUG   (  369):     67836ff0 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     67837000 00000000 00000000 00000040 67837450  
I/DEBUG   (  369):     67837010 678e23b8 67837450 678e2378 40096861  
I/DEBUG   (  369):     67837020 0000000e 63deccc0 67837034 67837000  
I/DEBUG   (  369):     67837030 e0000000 00000006 00000000 00000001  
I/DEBUG   (  369):     67837040 67837450 00000040 63fe5830 67a2b940  
I/DEBUG   (  369):     67837050 0000000c 678e2378 67837450 00000040  
I/DEBUG   (  369):     67837060 0000000c 671dda20 67837548 00000001  
I/DEBUG   (  369):     67837070 67b2c6d0 00000068 00000000 00000000  
I/DEBUG   (  369):     67837080 00000000 00000000 67837098 00000000  
I/DEBUG   (  369): 
I/DEBUG   (  369): memory near r5:
I/DEBUG   (  369):     67836f50 67837fcc 673763f0 67836f88 00000000  
I/DEBUG   (  369):     67836f60 67836f7c 671a8184 00000000 00000000  
I/DEBUG   (  369):     67836f70 400d738c 00000000 67837304 67284b34  
I/DEBUG   (  369):     67836f80 63efef38 63efef38 657f43e0 00000001  
I/DEBUG   (  369):     67836f90 67a51d80 67a53b00 63efef38 00000000  
I/DEBUG   (  369):     67836fa0 657f42d0 657f42e0 00000001 400d002f  
I/DEBUG   (  369):     67836fb0 00001000 400d738c 00001000 63efef38  
I/DEBUG   (  369):     67836fc0 657f4378 67836fd8 67837354 67284ab0  
I/DEBUG   (  369):     67836fd0 00000002 00000000 657f4378 00000000  
I/DEBUG   (  369):     67836fe0 6768af28 00000001 67a53b00 67836fd8  
I/DEBUG   (  369):     67836ff0 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     67837000 00000000 00000000 00000040 67837450  
I/DEBUG   (  369):     67837010 678e23b8 67837450 678e2378 40096861  
I/DEBUG   (  369):     67837020 0000000e 63deccc0 67837034 67837000  
I/DEBUG   (  369):     67837030 e0000000 00000006 00000000 00000001  
I/DEBUG   (  369):     67837040 67837450 00000040 63fe5830 67a2b940  
I/DEBUG   (  369): 
I/DEBUG   (  369): memory near r6:
I/DEBUG   (  369):     63efef18 00000001 0000001b 576f6c50 0000001c  
I/DEBUG   (  369):     63efef28 00000000 00000000 00000001 000000ab  
I/DEBUG   (  369):     63efef38 63de8cc0 67841fa0 63fe5830 67838898  
I/DEBUG   (  369):     63efef48 00000000 63de8d0c 63fe584c 00000000  
I/DEBUG   (  369):     63efef58 00000001 63dea114 63dea114 722f0000  
I/DEBUG   (  369):     63efef68 00000000 ffffff82 5f65006c 00000000  
I/DEBUG   (  369):     63efef78 00000003 00000000 6f632d00 65696b6f  
I/DEBUG   (  369):     63efef88 63efef98 00000000 00000001 65745f67  
I/DEBUG   (  369):     63efef98 6a2e7473 6c750073 63efef38 63fd0740  
I/DEBUG   (  369):     63efefa8 00000003 00000000 1e000000 67329ef8  
I/DEBUG   (  369):     63efefb8 63dc79d4 00000000 00000001 745f0073  
I/DEBUG   (  369):     63efefc8 00000002 ffffff84 70612e00 00000000  
I/DEBUG   (  369):     63efefd8 000000a8 0000001b 63ef6000 00009000  
I/DEBUG   (  369):     63efefe8 63df4fe0 00000001 00000000 00000007  
I/DEBUG   (  369):     63efeff8 00000007 00000007 00000000 00000603  
I/DEBUG   (  369):     63eff008 000005f3 00000025 00008f00 54010000  
I/DEBUG   (  369): 
I/DEBUG   (  369): memory near r7:
I/DEBUG   (  369):     67836f50 67837fcc 673763f0 67836f88 00000000  
I/DEBUG   (  369):     67836f60 67836f7c 671a8184 00000000 00000000  
I/DEBUG   (  369):     67836f70 400d738c 00000000 67837304 67284b34  
I/DEBUG   (  369):     67836f80 63efef38 63efef38 657f43e0 00000001  
I/DEBUG   (  369):     67836f90 67a51d80 67a53b00 63efef38 00000000  
I/DEBUG   (  369):     67836fa0 657f42d0 657f42e0 00000001 400d002f  
I/DEBUG   (  369):     67836fb0 00001000 400d738c 00001000 63efef38  
I/DEBUG   (  369):     67836fc0 657f4378 67836fd8 67837354 67284ab0  
I/DEBUG   (  369):     67836fd0 00000002 00000000 657f4378 00000000  
I/DEBUG   (  369):     67836fe0 6768af28 00000001 67a53b00 67836fd8  
I/DEBUG   (  369):     67836ff0 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     67837000 00000000 00000000 00000040 67837450  
I/DEBUG   (  369):     67837010 678e23b8 67837450 678e2378 40096861  
I/DEBUG   (  369):     67837020 0000000e 63deccc0 67837034 67837000  
I/DEBUG   (  369):     67837030 e0000000 00000006 00000000 00000001  
I/DEBUG   (  369):     67837040 67837450 00000040 63fe5830 67a2b940  
I/DEBUG   (  369): 
I/DEBUG   (  369): memory near r9:
I/DEBUG   (  369):     67836f8c 00000001 67a51d80 67a53b00 63efef38  
I/DEBUG   (  369):     67836f9c 00000000 657f42d0 657f42e0 00000001  
I/DEBUG   (  369):     67836fac 400d002f 00001000 400d738c 00001000  
I/DEBUG   (  369):     67836fbc 63efef38 657f4378 67836fd8 67837354  
I/DEBUG   (  369):     67836fcc 67284ab0 00000002 00000000 657f4378  
I/DEBUG   (  369):     67836fdc 00000000 6768af28 00000001 67a53b00  
I/DEBUG   (  369):     67836fec 67836fd8 00000000 00000000 00000000  
I/DEBUG   (  369):     67836ffc 00000000 00000000 00000000 00000040  
I/DEBUG   (  369):     6783700c 67837450 678e23b8 67837450 678e2378  
I/DEBUG   (  369):     6783701c 40096861 0000000e 63deccc0 67837034  
I/DEBUG   (  369):     6783702c 67837000 e0000000 00000006 00000000  
I/DEBUG   (  369):     6783703c 00000001 67837450 00000040 63fe5830  
I/DEBUG   (  369):     6783704c 67a2b940 0000000c 678e2378 67837450  
I/DEBUG   (  369):     6783705c 00000040 0000000c 671dda20 67837548  
I/DEBUG   (  369):     6783706c 00000001 67b2c6d0 00000068 00000000  
I/DEBUG   (  369):     6783707c 00000000 00000000 00000000 67837098  
I/DEBUG   (  369): 
I/DEBUG   (  369): memory near sl:
I/DEBUG   (  369):     678384e8 678388c8 67838500 6783887c 67284ab0  
I/DEBUG   (  369):     678384f8 00000008 67a3dd90 678388c8 00000001  
I/DEBUG   (  369):     67838508 6768af28 00000001 67a2f680 67838500  
I/DEBUG   (  369):     67838518 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     67838528 00000000 00000000 00000101 00000000  
I/DEBUG   (  369):     67838538 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     67838548 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     67838558 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     67838568 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     67838578 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     67838588 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     67838598 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     678385a8 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     678385b8 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     678385c8 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     678385d8 00000000 00000000 00000000 00000000  
I/DEBUG   (  369): 
I/DEBUG   (  369): memory near fp:
I/DEBUG   (  369):     67836f34 ef9000ad 00000000 67836f94 67836fb0  
I/DEBUG   (  369):     67836f44 67836f94 67836f80 00000000 67837fcc  
I/DEBUG   (  369):     67836f54 673763f0 67836f88 00000000 67836f7c  
I/DEBUG   (  369):     67836f64 671a8184 00000000 00000000 400d738c  
I/DEBUG   (  369):     67836f74 00000000 67837304 67284b34 63efef38  
I/DEBUG   (  369):     67836f84 63efef38 657f43e0 00000001 67a51d80  
I/DEBUG   (  369):     67836f94 67a53b00 63efef38 00000000 657f42d0  
I/DEBUG   (  369):     67836fa4 657f42e0 00000001 400d002f 00001000  
I/DEBUG   (  369):     67836fb4 400d738c 00001000 63efef38 657f4378  
I/DEBUG   (  369):     67836fc4 67836fd8 67837354 67284ab0 00000002  
I/DEBUG   (  369):     67836fd4 00000000 657f4378 00000000 6768af28  
I/DEBUG   (  369):     67836fe4 00000001 67a53b00 67836fd8 00000000  
I/DEBUG   (  369):     67836ff4 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     67837004 00000000 00000040 67837450 678e23b8  
I/DEBUG   (  369):     67837014 67837450 678e2378 40096861 0000000e  
I/DEBUG   (  369):     67837024 63deccc0 67837034 67837000 e0000000  
I/DEBUG   (  369): 
I/DEBUG   (  369): memory near ip:
I/DEBUG   (  369):     67698b80 40092b10 40092af0 5df48ccd 5df48dd1  
I/DEBUG   (  369):     67698b90 40092df1 5df48dff 40092ddd 5df48da3  
I/DEBUG   (  369):     67698ba0 400a8b29 5df48c51 4009a669 400ab929  
I/DEBUG   (  369):     67698bb0 4009a84d 400ac005 400abf75 4009a1d5  
I/DEBUG   (  369):     67698bc0 400a8548 400a7d64 400a2585 400ab571  
I/DEBUG   (  369):     67698bd0 400a26f9 400a7fe0 4009a189 4009a27d  
I/DEBUG   (  369):     67698be0 400ab8ad 400ac4e7 400ae8b5 400ab6b1  
I/DEBUG   (  369):     67698bf0 400ab8c5 400a87e1 400a80f1 40099155  
I/DEBUG   (  369):     67698c00 400b120d 40093ad0 40093bbc 400939cc  
I/DEBUG   (  369):     67698c10 40099a2d 400a5c3c 400a651c 400b3ac5  
I/DEBUG   (  369):     67698c20 400b3011 400a6ba8 400b5a41 4005f02d  
I/DEBUG   (  369):     67698c30 4005f0b1 4005f161 400a7908 400c1255  
I/DEBUG   (  369):     67698c40 40093e58 400a6da4 4009369c 400936f4  
I/DEBUG   (  369):     67698c50 400937a8 400936b0 400aa410 4009bc01  
I/DEBUG   (  369):     67698c60 4005efdd 40092e19 400a64dc 400a6188  
I/DEBUG   (  369):     67698c70 400a4925 40081c91 40081d25 400a694c  
I/DEBUG   (  369): 
I/DEBUG   (  369): memory near sp:
I/DEBUG   (  369):     67836f18 00000000 00000000 00000003 000000aa  
I/DEBUG   (  369):     67836f28 0000006b 0001416e e3a070ad ef9000ad  
I/DEBUG   (  369):     67836f38 00000000 67836f94 67836fb0 67836f94  
I/DEBUG   (  369):     67836f48 67836f80 00000000 67837fcc 673763f0  
I/DEBUG   (  369):     67836f58 67836f88 00000000 67836f7c 671a8184  
I/DEBUG   (  369):     67836f68 00000000 00000000 400d738c 00000000  
I/DEBUG   (  369):     67836f78 67837304 67284b34 63efef38 63efef38  
I/DEBUG   (  369):     67836f88 657f43e0 00000001 67a51d80 67a53b00  
I/DEBUG   (  369):     67836f98 63efef38 00000000 657f42d0 657f42e0  
I/DEBUG   (  369):     67836fa8 00000001 400d002f 00001000 400d738c  
I/DEBUG   (  369):     67836fb8 00001000 63efef38 657f4378 67836fd8  
I/DEBUG   (  369):     67836fc8 67837354 67284ab0 00000002 00000000  
I/DEBUG   (  369):     67836fd8 657f4378 00000000 6768af28 00000001  
I/DEBUG   (  369):     67836fe8 67a53b00 67836fd8 00000000 00000000  
I/DEBUG   (  369):     67836ff8 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     67837008 00000040 67837450 678e23b8 67837450  
I/DEBUG   (  369): 
I/DEBUG   (  369): code around pc:
I/DEBUG   (  369):     400a8b5c b31a2b01 0f04f013 800af000 3b04f851  
I/DEBUG   (  369):     400a8b6c 3c01f1a3 0c03ea2c 3c80f01c 8033f040  
I/DEBUG   (  369):     400a8b7c 2302e8f1 f040f891 3c01f1a2 0c02ea2c  
I/DEBUG   (  369):     400a8b8c 3c80f01c 800ff040 3c01f1a3 0c03ea2c  
I/DEBUG   (  369):     400a8b9c 3c80f01c 801ff040 bfeaf7ff 0000eba1  
I/DEBUG   (  369):     400a8bac 0001f1a0 eba14770 ea5f0000 f040434c  
I/DEBUG   (  369):     400a8bbc f0808009 ea5f800a f0400c4c f1a08009  
I/DEBUG   (  369):     400a8bcc 47700005 0008f1a0 f1a04770 47700007  
I/DEBUG   (  369):     400a8bdc 0006f1a0 eba14770 ea5f0000 f040434c  
I/DEBUG   (  369):     400a8bec f0808009 ea5f800a f0400c4c f1a08009  
I/DEBUG   (  369):     400a8bfc 47700001 0004f1a0 f1a04770 47700003  
I/DEBUG   (  369):     400a8c0c 0002f1a0 bf004770 f000f890 b430b501  
I/DEBUG   (  369):     400a8c1c 46054696 0404ea84 f0114608 d01d0307  
I/DEBUG   (  369):     400a8c2c 0308f1c3 7cc3ea5f f811d002 b3422b01  
I/DEBUG   (  369):     400a8c3c f013d308 d0050c02 2b01f811 f811b30a  
I/DEBUG   (  369):     400a8c4c b1f22b01 0f04f013 f851d008 f1a33b04  
I/DEBUG   (  369): 
I/DEBUG   (  369): code around lr:
I/DEBUG   (  369):     6739f2e8 e24dd008 e1a08002 e1a07000 e1a06001  
I/DEBUG   (  369):     6739f2f8 11a02003 1a000002 e1a00008 ebe8a1f5  
I/DEBUG   (  369):     6739f308 e1a02000 e3520000 da00000a e1d830d0  
I/DEBUG   (  369):     6739f318 e3530000 ba000012 e288c001 e0884002  
I/DEBUG   (  369):     6739f328 ea000002 e0dce0d1 e35e0000 ba00000c  
I/DEBUG   (  369):     6739f338 e15c0004 1afffffa e1a01008 e1a00006  
I/DEBUG   (  369):     6739f348 ebf76630 e1a02006 e3a03000 e1a01000  
I/DEBUG   (  369):     6739f358 e1a00007 ebffff2b e1a00007 e24bd014  
I/DEBUG   (  369):     6739f368 e8bd89d0 e3a00000 e24b3014 e1a01008  
I/DEBUG   (  369):     6739f378 e5230004 e1a00006 ebfff958 e51b1018  
I/DEBUG   (  369):     6739f388 e3510000 0a000006 e1a02006 e1a00007  
I/DEBUG   (  369):     6739f398 e3a03000 ebffff1b e1a00007 e24bd014  
I/DEBUG   (  369):     6739f3a8 e8bd89d0 e59f0020 e59f2020 e59f3020  
I/DEBUG   (  369):     6739f3b8 e3a01e3f e08f0000 e08f2002 e08f3003  
I/DEBUG   (  369):     6739f3c8 ebe8a299 e51b1018 eaffffee 001f6ed0  
I/DEBUG   (  369):     6739f3d8 002a3448 001f6ef8 e92d4878 e1a05001  
I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---,
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---,
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 168
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---,
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---,
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---,
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---,
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---,
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,E/ActivityManager(  907): App crashed! Process: com.example.hello
I/BootReceiver(  907): Copying /data/tombstones/tombstone_00 to DropBox (SYSTEM_TOMBSTONE)
W/ActivityManager(  907):   Force finishing activity com.example.hello/.MainActivity
,W/dalvikvm( 3489): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
I/ActivityManager(  907): mThumbnailWidth=360, mThumbnailHeight=640
,E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
W/ActivityManager(  907): Exception thrown during pause
W/ActivityManager(  907): android.os.TransactionTooLargeException
W/ActivityManager(  907): 	at android.os.BinderProxy.transact(Native Method)
W/ActivityManager(  907): 	at android.app.ApplicationThreadProxy.schedulePauseActivity(ApplicationThreadNative.java:765)
W/ActivityManager(  907): 	at com.android.server.am.ActivityStack.startPausingLocked(ActivityStack.java:862)
W/ActivityManager(  907): 	at com.android.server.am.ActivityStack.finishActivityLocked(ActivityStack.java:2792)
W/ActivityManager(  907): 	at com.android.server.am.ActivityStack.finishTopRunningActivityLocked(ActivityStack.java:2661)
W/ActivityManager(  907): 	at com.android.server.am.ActivityStackSupervisor.finishTopRunningActivityLocked(ActivityStackSupervisor.java:2278)
W/ActivityManager(  907): 	at com.android.server.am.ActivityManagerService.handleAppCrashLocked(ActivityManagerService.java:10381)
W/ActivityManager(  907): 	at com.android.server.am.ActivityManagerService.makeAppCrashingLocked(ActivityManagerService.java:10270)
W/ActivityManager(  907): 	at com.android.server.am.ActivityManagerService.crashApplication(ActivityManagerService.java:10956)
W/ActivityManager(  907): 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:10490)
W/ActivityManager(  907): 	at com.android.server.am.NativeCrashListener$NativeCrashReporter.run(NativeCrashListener.java:98)
,D/PMS     (  907): acquireWL(427e2a00): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
E/JavaBinder(  907): !!! FAILED BINDER TRANSACTION !!!
,W/ActivityManager(  907): handleTopAppChanged(): The previous AP is died unexpectedly.
W/InputDispatcher(  907): channel '4254ff60 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
W/dalvikvm( 3489): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/Zygote  (  370): Process 3506 terminated by signal (11)
,E/InputDispatcher(  907): channel '4254ff60 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
I/ActivityManager(  907): Recipient 3506
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/InputDispatcher(  907): Attempted to unregister already unregistered input channel '4254ff60 com.example.hello.MainActivity (s)'
I/WindowState(  907): WIN DEATH: Window{4254ff60 u0 com.example.hello/com.example.hello.MainActivity}
I/ActivityManager(  907): Process com.example.hello (pid 3506) has died.
I/WindowManager(  907): WINDOW DIED Window{4254ff60 u0 com.example.hello/com.example.hello.MainActivity EXITING}
,W/asset   (  907): Copying FileAsset 0x6f0849c0 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/FeedHostManager( 1271): [onResume]
,I/FeedProviderManager( 1271): onResume
I/SocialFeedProvider( 1271): +onResume
I/SocialFeedProvider( 1271): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1271): -onResume
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.launcher (1271/10075)
,D/PMS     (  907): releaseWL(427e2a00): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,E/FbInjectorInitializer( 3489): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 3489): Verify
,D/WifiService(  907): New client listening to asynchronous messages
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (3489/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 3489): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 3489): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 3489): Grow heap (frag case) to 9.517MB for 73240-byte allocation
,D/Process (  907): killProcessQuiet, pid=3222
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3222:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/PMS     (  907): acquireWL(426198e8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1225 10028 null
I/ActivityManager(  907): Recipient 3222
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  907): acquireWL(42619898): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1225 10028 null
D/PMS     (  907): releaseWL(426198e8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10028)
,D/GCM     ( 1365): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1365/10028)
D/PMS     (  907): releaseWL(42619898): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1365/10028)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1365/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/AutoSetting( 1396): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10028)
,I/ActivityManager(  907): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3565 uid=10078 gids={50078, 3003, 5012}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
D/AutoSetting( 1396): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1396): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1396): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1396): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1396): service - handleMessage() setting current location null
D/AutoSetting( 1396): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1396): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
W/fb4a(:<default>):UserScope( 3489): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 3489): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 3489): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/MobileConnectivityChangeReceiver( 3565): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 3565): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3565): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3565): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  907): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=3580 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3236
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3236:com.android.smith/u0a163 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (3565/10078)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (3565/10078)
D/PMS     (  907): acquireWL(41d2eb30): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1225 10028 null
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3489): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (3565/10078)
I/ActivityManager(  907): Recipient 3236
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/PMS     (  907): acquireWL(41df4618): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1225 10028 null
D/PMS     (  907): releaseWL(41d2eb30): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,I/CheckinService( 1225): Preparing to send checkin request
,I/EventLogService( 1225): Accumulating logs since 1452260364057
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10028)
,E/dalvikvm( 3489): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 3489): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 3489): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 3489): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 3489): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 3489): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 3489): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 3489): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 3489): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 3489): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 3489): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 3489): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 3489): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 3489): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 3489): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 3489): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 3489): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 3489): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,W/EventLogAggregator( 1225): Unknown tag: install_package_attempt
W/EventLogAggregator( 1225): Unknown tag: snet
,W/EventLogAggregator( 1225): Unknown tag: snet_gcore
,D/Process (  907): killProcessQuiet, pid=3248
I/ActivityManager(  907): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3598 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,I/ActivityManager(  907): Killing 3248:com.google.android.youtube/u0a168 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/dalvikvm-heap( 3489): Grow heap (frag case) to 9.927MB for 39954-byte allocation
,I/GoogleHttpClient( 1225): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1225): Using GMS GoogleHttpClient
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
,D/PMS     (  907): releaseHCC(4234b3e0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  907): releaseHCC(41f06c60): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/WifiService(  907): New client listening to asynchronous messages
,I/dalvikvm-heap( 3489): Grow heap (frag case) to 10.003MB for 79892-byte allocation
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3598): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3598): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,W/GAV2    ( 3598): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3598): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3598): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 3489): Grow heap (frag case) to 10.039MB for 84664-byte allocation
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  907): Recipient 3248
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  907): Client com.google.android.youtube (pid 3248): Died!
D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (1225/10028)
D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (1225/10028)
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [1][0][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (3598/10151)
,V/WebViewChromiumFactoryProvider( 3598): Binding Chromium to main looper Looper (main, tid 1) {41acec40}
,I/LibraryLoader( 3598): Expected native library version number "",actual native library version number ""
,I/chromium( 3598): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3598): Initializing chromium process, renderers=0
,E/AudioManagerAndroid( 3598): BLUETOOTH permission is missing!
D/PMS     (  907): acquireWL(4261e0a0): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  907): releaseWL(4261e0a0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 3598): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3598): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3598): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3598): Local Branch: 
I/Adreno-EGL( 3598): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3598): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3598):                  aa63bbd948f41d15fc72f585e
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,I/dalvikvm-heap( 3489): Grow heap (frag case) to 10.289MB for 75760-byte allocation
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (3489/10026)
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{425eda90 u0 ReceiverList{427d57a0 3489 com.facebook.katana/10026/u0 remote:427d56d8}}
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{425eda90 u0 ReceiverList{427d57a0 3489 com.facebook.katana/10026/u0 remote:427d56d8}}
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4234c450 u0 ReceiverList{42797900 3489 com.facebook.katana/10026/u0 remote:41bfb900}}
,I/GoogleHttpClient( 1365): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1365): Using GMS GoogleHttpClient
,I/NSApplication( 3598): Starting up...
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (3598/10151)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (3598/10151)
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,D/Process (  907): killProcessQuiet, pid=3201
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=3637 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
I/ActivityManager(  907): Killing 3201:com.android.settings/1000 (adj 15): empty #17
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3201
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (3489/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (3489/10026)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [2][0][0]
I/NotificationStore( 1365): System rebooted after Notification storage file was last written
,I/NotificationStore( 1365): Deleting the file
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (3489/10026)
,D/PMS     (  907): acquireWL(42776050): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1449 10028 null
,D/PMS     (  907): releaseWL(42776050): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1225): awaiting user notification for token
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41bf0c88 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/GCoreFlp( 1449): Unknown pending intent to remove.
,I/RemoteViews.Performance( 1117): com.google.android.gms 3 7 4 12
D/PMS     (  907): acquireWL(425a1868): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1449 10028 null
D/PMS     (  907): releaseWL(425a1868): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/ActivityManager(  907): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3656 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,I/MultiDex( 3656): install
,I/MultiDex( 3656): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 3656): loading existing secondary dex files
,I/MultiDex( 3656): load found 1 secondary dex files
,I/MultiDex( 3656): install done
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3637/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3637/10160)
,W/ContextImpl( 3489): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/PMS     (  907): acquireWL(427b75e0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3637 10160 null
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
W/ContextImpl( 3489): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,I/ProviderInstaller( 3656): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3637/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3637/10160)
,D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1822/10178)
,D/PMS     (  907): acquireWL(42589278): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3637 10160 null
,D/PMS     (  907): releaseWL(427b75e0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,I/ActivityManager(  907): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3680 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,I/DemoRecovery.RestoreReceiver( 3680): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,W/ContextImpl( 3680): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
,I/RestoreService( 3680): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
,I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): releaseWL(42589278): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,I/ActivityManager(  907): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3694 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3306
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3306:com.htc.sense.browser/u0a12 (adj 15): empty #17
,D/Process (  907): killProcessQuiet, pid=3346
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3346:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/GoogleHttpClient( 3656): Falling back to old SSLCertificateSocketFactory
I/ActivityManager(  907): Recipient 3346
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(4270d478): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3694 10070 null
,D/PMS     (  907): acquireWL(425340d8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3694 10070 null
,I/dalvikvm-heap( 3637): Grow heap (frag case) to 15.216MB for 1821008-byte allocation
D/PMS     (  907): releaseWL(4270d478): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
I/ActivityManager(  907): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3694): update TASK shortcut>
,D/libc    ( 3656): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 3656): [NET] getaddrinfo-,err=8
D/libc    ( 3656): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 3656): [NET] getaddrinfo-, 1
D/libc    ( 3656): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =e545 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,I/ActivityManager(  907): Recipient 3306
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/TodoTaskNotifyService( 3694): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): releaseWL(425340d8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 3694): stopSelfResult true
I/ActivityManager(  907): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3713 uid=10081 gids={50081, 3003, 5012}
,D/Process (  907): killProcessQuiet, pid=3358
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 90
D/libc    (  365): [NET]res_nsend:resplen=86
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3656): [NET] getaddrinfo_proxy-, success
I/ActivityManager(  907): Killing 3358:com.htc.contacts/u0a41 (adj 15): empty #17
,I/ActivityManager(  907): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3725 uid=10081 gids={50081, 3003, 5012}
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3358
,D/libc    ( 3656): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 3656): [NET] getaddrinfo-,err=8
,D/Process (  907): killProcessQuiet, pid=3373
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/AlertReceiver( 3415): beginStartingService
I/ActivityManager(  907): Killing 3373:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
,D/Process (  907): killProcessQuiet, pid=3388
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/PMS     (  907): acquireWL(425bdfa8): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3415 10013 null
I/ActivityManager(  907): Killing 3388:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/ActivityManager(  907): Recipient 3373
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3388
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SocialFeedProvider( 1271): +disConnect socialManager
,I/SocialFeedProvider( 1271): disconnect socialManager
,D/PMS     (  907): acquireWL(427e2aa0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1225 10028 null
,I/SocialFeedProvider( 1271): -disConnect socialManager
D/PMS     (  907): acquireWL(427e2a00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
D/PMS     (  907): releaseWL(427e2a00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/PMS     (  907): releaseWL(427e2aa0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/AlertService( 3415): start to updateAlertNotification!
,D/AlertService( 3415): No fired or scheduled alerts
,D/HtcAlertUtils( 3415): -- cancelReminderNotification --
,D/HtcAlertUtils( 3415): broadcastExistReminder!
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  907): releaseWL(425bdfa8): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
W/AlertReceiver( 3415): stopSelfResult true
,W/WeatherUtility( 3446): can't get weather sync account
D/PMS     (  907): acquireWL(4278ced8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3694 10070 null
,W/WeatherRequest( 1117): request cur loc, but there is no sys cur
D/PMS     (  907): acquireWL(42776050): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3694 10070 null
D/PMS     (  907): releaseWL(4278ced8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  907): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3745 uid=10090 gids={50090, 3003, 5012, 1028}
,I/TodoTaskNotifyService( 3694): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/TodoTaskshortcut( 3694): update TASK shortcut>
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
W/WeatherRequest( 3446): request cur loc, but there is no sys cur
,W/Settings( 3446): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,D/AppWidgetHostView( 1271): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1271): com.htc.widget.weatherclock (true,33751552)
,I/TodoTaskNotifyService( 3694): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/RemoteViews.Performance( 1271): com.htc.widget.weatherclock 1 8 17
,W/NotifyReceiver( 3694): stopSelfResult true
D/PMS     (  907): releaseWL(42776050): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,D/MessagingNotification( 2791): New incoming message, can't cancel notification now
,D/MessagingNotification( 2791): newMsgCnt: 0, false
,I/WorldClock.Global( 3745): isHtcDevice = true
,I/WorldClock.Global( 3745): isHtcDevice = true
W/ContextImpl( 3177): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/WorldClock.AlarmUtils( 3745): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
I/WorldClock.AlarmUtils( 3745): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 3745): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/IntentController( 1117): receive(android.intent.action.ALARM_CHANGED,1,false)
I/ActivityManager(  907): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3760 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  907): releaseWL(423c5ba8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/TimeService( 3760): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1452261057022
,D/Process (  907): killProcessQuiet, pid=3400
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/AdsMeasurementBroadcastReceiver( 1225): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 1225): Unauthorized to start the main service
I/ActivityManager(  907): Killing 3400:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
I/ActivityManager(  907): Recipient 3400
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3775 uid=10038 gids={50038}
,D/Process (  907): killProcessQuiet, pid=3427
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3788 uid=10077 gids={50077}
I/ActivityManager(  907): Killing 3427:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3427
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/SMSBackup( 3788): Got a database change event
,D/Process (  907): killProcessQuiet, pid=3461
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3800 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
I/ActivityManager(  907): Killing 3461:com.google.android.music:main/u0a154 (adj 15): empty #17
,I/ImageRamCache( 3800): create image Cache, size: 31457280.
I/ImageRamCache( 3800): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3800): create image Cache, size: 12582912.
,I/FeedSettings( 3800): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 3800): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3800): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3800): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3800): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3800): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 3800): [custom highlight] onReceive
,I/ActivityManager(  907): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
D/CustomHighlightService( 3800): [custom highlight] onHandleIntent
D/NewsDB  ( 3800): set custom highlight []
,I/ActivityManager(  907): Recipient 3461
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  907): Client com.google.android.music (pid 3461): Died!
,D/CustomHighlightService( 3800): [custom highlight] set tags 
,D/Process (  907): killProcessQuiet, pid=3489
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Killing 3489:com.facebook.katana/u0a26 (adj 15): empty #17
,D/GCM     ( 1365): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
D/MessagingShortcutReceiver( 2791): keep hiding shortcut bubble
D/MessagingShortcut( 2791): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2791): After query: 0
D/MessagingShortcut( 2791): mPresentUnreadCount: -1
D/MessagingShortcut( 2791): setMsgShortcutDrawable> 0
D/MessagingShortcut( 2791): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderNotification, total:0
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  907): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3694): update TASK shortcut>
,D/HtcBroadcastReceiver( 1245): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3817 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  907): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,I/ActivityManager(  907): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3831 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  907): Recipient 3489
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
,D/PMS     (  907): acquireWL(423c74d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1449 10028 null
,D/PMS     (  907): acquireWL(4238b0f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1449 10028 null
,D/PMS     (  907): releaseWL(423c74d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  907): releaseWL(4238b0f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/MdScBoot( 3817): [8c0.1.] 40@-145053
,D/GCM     ( 1365): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/Process (  907): killProcessQuiet, pid=3565
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Killing 3565:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/Process (  907): killProcessQuiet, pid=3580
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3580:com.android.chrome/u0a96 (adj 15): empty #17
,D/MtpReceiver( 2460): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2460): [MTP][MtpReceiver][onReceive]1-
,D/MtpReceiver( 2460): [MTP][handleMessage][startService]
I/ActivityManager(  907): Recipient 3580
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3565
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MtpReceiver( 2460): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MtpReceiver( 2460): [MTP][handleMessage]-
I/ActivityManager(  907): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3846 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/MtpService( 2460): [MTP] startForeground
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
,I/RemoteViews( 1117): com.android.providers.media (false,0)
,I/RemoteViews.Performance( 1117): com.android.providers.media 6 1 10
,I/RemoteViews( 1117): com.android.providers.media (false,0)
,D/MtpService( 2460): updating state; isCurrentUser=true, mMtpLocked=false
I/RemoteViews.Performance( 1117): com.android.providers.media 3 1 15
,D/MtpDatabase( 2460): TotalSize=1918604,MediaCacheLimit=6000
,D/MtpService( 2460): [isMtpConnected] connected: true
D/PMS     (  907): acquireWL(42365830): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 3637 10160 null
,D/SyncApplication( 3846): Loading default preferences
,W/Resources( 3846): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,I/Adreno-EGL( 3656): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3656): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3656): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3656): Local Branch: 
I/Adreno-EGL( 3656): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3656): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3656):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  907): releaseWL(42365830): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 null
,V/AlarmManager(  907): sending alarm PendingIntent{41d36030: PendingIntentRecord{424625a0 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=58355, Int=0
,D/WifiService(  907): New client listening to asynchronous messages
,D/SyncApplication( 3846): Overriding preferences with custom values
,D/SyncApplication( 3846): Updating preferences succeeded
,E/SyncApplication( 3846): Application created.
D/VolumeInfo( 3846): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3846): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3846): Found 0 mount point(s)
,V/VolumeInfo( 3846): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3846): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/Adreno-EGL( 3656): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3656): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3656): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3656): Local Branch: 
I/Adreno-EGL( 3656): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3656): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3656):                  aa63bbd948f41d15fc72f585e
,D/VolumeInfo( 3846): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
,W/VolumeInfo( 3846): Can not create volume ID for unmounted volume null
,I/CalendarDefines( 3846): getNewCalendarAuthority()...
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3846, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
,D/SyncApplication( 3846): enableAppOperation()+
,D/SyncApplication( 3846): enableAppOperation()-
,D/HTCUtilities( 3846): isNeorSinged() + 
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3846, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 3846): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3846): isNeorSinged() return false
D/CDMountReceiver( 3846): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3846): USB connected to PC
,D/FOTAReceiver( 3846): onReceive() enter 
,D/FOTAReceiver( 3846): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,I/ActivityManager(  907): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3869 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  907): killProcessQuiet, pid=3598
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3598:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,D/HtcFingerPrintQuickLaunchProvider( 3869): -onCreate()
,V/Settings:HtcSettingsApplication( 3869): [3869/3869] onCreate()
,D/TetherSettings( 3869): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3869): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3869): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3869): Cust_ConnectToPC   : spcsc>false
D/        ( 3869): Cust_ConnectToPC   : IPT>true
,D/        ( 3869): Cust_ConnectToPC   : Singel_USB>false
,D/Process (  907): killProcessQuiet, pid=3680
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/Settings( 3869): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ActivityManager(  907): Killing 3680:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
D/TetherSettings( 3869): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3869): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3869): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3869): Cust_ConnectToPC   : spcsc>false
D/        ( 3869): Cust_ConnectToPC   : IPT>true
D/        ( 3869): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3869): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3869): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 3869): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3869): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3869): usb_cable_connect = 1
,D/SmartNS_Utility( 3869): usb_denied = 0
I/ActivityManager(  907): Recipient 3680
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3598
,I/SmartNS_NSReceiver( 3869): locked:falsesecurity:falseisLocked:false
,D/SmartNS_NSReceiver( 3869): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 3869): onReceive:com.htc.intent.action.USB_CONNECT2PC
,I/SmartNS_PSService( 3869): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/ContextImpl( 3869): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3869): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3869):  defaultType:0
I/SmartNS_PSService( 3869): fail notificaiton:false
D/SmartNS_Utility( 3869): usb_cable_connect = 1
D/SmartNS_Utility( 3869): usb_denied = 0
I/SmartNS_PSService( 3869): usb notificaiton:true
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  907): bSetPropertyMultiRAB:false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.settings (3869/1000)
,I/ActivityManager(  907): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
D/SmartNS_Utility( 3869): usb_cable_connect = 1
D/SmartNS_Utility( 3869): usb_denied = 0
I/SmartNS_PSService( 3869): usb notificaiton:true
V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,V/Tethering(  907): bSetPropertyMultiRAB:false
,I/RemoteViews( 1117): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1117): com.android.settings 3 1 10
D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.settings (3869/1000)
I/ActivityManager(  907): Resuming delayed broadcast
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,D/SmartNS_Utility( 3869): usb_cable_connect = 1
,D/SmartNS_Utility( 3869): usb_denied = 0
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,W/WeatherUtility( 3446): can't get weather sync account
,I/ActivityManager(  907): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
I/RemoteViews( 1117): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1117): com.android.settings 2 0 10
I/SmartNS_PSService( 3869): KeyGuard locked:falseKeyGuard is secured:false
,D/SmartNS_PSService( 3869): USB Plugged, Set USBPlugged=  truePSenabled:false
I/ActivityManager(  907): Resuming delayed broadcast
,D/AppWidgetHostView( 1271): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
,I/RemoteViews( 1271): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1271): com.google.android.googlequicksearchbox 0 0 5,
,W/WeatherRequest( 3446): request cur loc, but there is no sys cur
,W/Settings( 3446): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1271): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider})
I/ActivityManager(  907): Delay finish: pl.k2.droidoaudioteka/.ui.widgets.BigWidgetProvider
,I/ActivityManager(  907): Resuming delayed broadcast
I/RemoteViews( 1271): pl.k2.droidoaudioteka (false,0)
I/RemoteViews.Performance( 1271): pl.k2.droidoaudioteka 1 0 8
,D/SMSBackup( 3788): Got a database change event
D/PMS     (  907): acquireWL(425a97f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
,D/PMS     (  907): releaseWL(425a97f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  907): acquireWL(424e2c48): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1512 10014 null
,D/AppWidgetHostView( 1271): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1271): com.htc.widget.weatherclock (true,33751552)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
V/AlarmManager(  907): sending alarm PendingIntent{422da210: PendingIntentRecord{42337570 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1452261057902, Int=0
,I/ActivityManager(  907): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
I/SocialManager[SocialBiLogHelper]( 3800): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3800): last commit ulog time 1452231060566
I/SocialManager[SocialBiLogHelper]( 3800): skip commit this time
I/RemoteViews.Performance( 1271): com.htc.widget.weatherclock 1 8 17
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=11 [27][3][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 240
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/PMS     (  907): releaseWL(424e2c48): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
,D/LocationManagerService(  907): getAllProviders()=[passive, gps, network]
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10028)
,D/PMS     (  907): acquireWL(423eeed8): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 1225 10028 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10028)
W/Settings( 3656): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL( 3656): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3656): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3656): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3656): Local Branch: 
I/Adreno-EGL( 3656): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3656): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3656):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (3656/10028)
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1512): handler message = 4011
,E/HtcModeClient( 1512): Check connection and retry 6 times.
D/PMS     (  907): releaseWL(423eeed8): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
,I/CheckinTask( 1225): Sending checkin request (9070 bytes)
I/ActivityManager(  907): Delay finish: com.google.android.gms/.security.snet.SnetBootCompletedReceiver
V/AlarmManager(  907): sending alarm PendingIntent{427534f0: PendingIntentRecord{427b7678 com.google.android.gms startService}}, i=null, t=0, cnt=17101, w=84918423, Int=84918423
W/ActivityThread( 1225): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager(  907): Resuming delayed broadcast
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10028)
,I/AdsMeasurementBroadcastReceiver( 1225): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 1225): Unauthorized to start the main service
D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=64 rxSum=71} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  907): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  907): onDataStallAlarm: tag=19721 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19722 delay=15s
,D/SnetService( 1225): snet destroyed
,D/libc    ( 1225): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1225): [NET] getaddrinfo-,err=8
D/libc    ( 1225): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1225): [NET] getaddrinfo-, 1
,D/libc    ( 1225): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =5be6 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/PackageBroadcastService( 1225): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PMS     (  907): acquireWL(424cc5e8): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
,D/PMS     (  907): releaseWL(424cc5e8): PARTIAL_WAKE_LOCK  Icing 0x1 null,
,I/PeopleContactsSync( 1225): CP2 sync disabled
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 100
D/libc    (  365): [NET]res_nsend:resplen=84
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1225): [NET] getaddrinfo_proxy-, success
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1225, uid=10028, userID:0
,D/libc    ( 1225): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1225): [NET] getaddrinfo-,err=8
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=3912 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  907): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{427f20d0 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/[PluginManager]RegisterService( 1396): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1396): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): acquireWL(427dc168): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
D/PMS     (  907): releaseWL(427dc168): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/ActivityManager(  907): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3928 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3713
,I/ActivityManager(  907): Killing 3713:com.htc.stock/u0a81 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 3713
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (1225/10028)
,D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (1225/10028)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=10 [19][2][0]
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3928, uid=10073, userID:0
,D/Process (  907): killProcessQuiet, pid=3725
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3725:com.htc.stock:remote/u0a81 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3725
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/RemoteViews.Performance( 1117): com.google.android.gms 2 2 12
W/CheckinRequestBuilder( 1225): awaiting user notification for token
,D/Finsky  ( 3928): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (3928/10073)
,D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (3928/10073)
,I/CheckinTask( 1225): Sending checkin request (2420 bytes)
,D/Finsky  ( 3928): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 3928): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3928): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3928, uid=10073, userID:0
,D/Process (  907): killProcessQuiet, pid=3415
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Prism.PackageStateRece_( 1271): action: android.intent.action.PACKAGE_ADDED
,D/Finsky  ( 3928): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3928): [1] 2.run: Finished loading 1 libraries.
I/ActivityManager(  907): Killing 3415:com.htc.calendar/u0a13 (adj 15): empty #17
,I/IcingCorporaProvider( 2907): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/ActivityManager(  907): Recipient 3415
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=3961 uid=10098 gids={50098, 3003, 5012}
,D/Finsky  ( 3928): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 3928): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/PMS     (  907): acquireWL(42019580): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
,I/DeviceManagement( 3961): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=3961 dbg=false s=true
,I/DeviceManagement( 3961): PackageUpdateReceiver: vvv Package added: [com.example.hello]
,I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3978 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3745
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3745:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3745
,D/PMS     (  907): releaseWL(42019580): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(424d19e0): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  907): releaseWL(424d19e0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(423b0fb0): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
,D/PMS     (  907): releaseWL(423b0fb0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(42370628): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
,D/PMS     (  907): releaseWL(42370628): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(4244de78): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
,D/PMS     (  907): releaseWL(4244de78): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(4241f660): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
,D/PMS     (  907): releaseWL(4241f660): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(424a1738): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
,D/PMS     (  907): releaseWL(424a1738): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(425051f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
,D/PMS     (  907): releaseWL(425051f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (1225/10028)
,D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (1225/10028)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [5][0][0]
,D/PMS     (  907): acquireWL(4236b060): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null,
,D/PMS     (  907): releaseWL(4236b060): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(4270abf8): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
,D/PMS     (  907): releaseWL(4270abf8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,D/PMS     (  907): acquireWL(425f1e18): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
,D/PMS     (  907): releaseWL(425f1e18): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/PMS     (  907): acquireWL(425365a8): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
D/PMS     (  907): releaseWL(425365a8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,W/CheckinRequestBuilder( 1225): awaiting user notification for token
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,I/RemoteViews.Performance( 1117): com.google.android.gms 0 2 12
,I/CheckinTask( 1225): Checkin success: https://android.clients.google.com/checkin (2 requests sent)
,W/GoogleHttpClient( 1225): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10028)
,W/asset   ( 2907): Copying FileAsset 0x63ce4de8 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/IcingCorporaProvider( 2907): UpdateCorporaTask done [took 506 ms] updated apps [took 506 ms] 
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10028)
,D/PMS     (  907): releaseWL(41df4618): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,I/ActivityManager(  907): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=3995 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (3978/10100)
,E/ActivityThread( 1225): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41dea7e8 that was originally bound here
E/ActivityThread( 1225): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41dea7e8 that was originally bound here
E/ActivityThread( 1225): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1225): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1225): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1225): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1225): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1225): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1225): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1225): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1225): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1225): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1225): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1225): 	at bks.a(SourceFile:298)
E/ActivityThread( 1225): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1225): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1225): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1225): 	at java.lang.Thread.run(Thread.java:864)
,W/GAV2    ( 3978): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (3978/10100)
,I/htcbackup-core( 3995): ModelRegistry: Loading model meta data from resources...
,W/ContextImpl( 3995): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 3995): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/DeviceManagement( 3961): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/DeviceManagement( 3961): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.htc.backupreset, com.htc.autobot.cargps.provider, com.htc.feedback, android, com.htc.htcpowermanager, com.android.location.fused, com.android.providers.settings, com.htc.mirrorlinkserver, com.htc.usage, com.android.CSDFunctionG, com.qualcomm.privinit, com.htc.backup, com.htc.cirmodule, com.htc.drive.activator, com.android.inputdevices, com.htc.lockscreen, com.android.keychain, com.htc.android.htcloglevel, com.htc.android.htcsetupwizard, com.htc.smartdim, com.htc.home.personalize, com.htc.checkinprovider, com.android.settings, com.htc.guide, com.qualcomm.timeservice]
,I/DeviceManagement( 3961): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
,D/Process (  907): killProcessQuiet, pid=3177
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=4019 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,I/ActivityManager(  907): Killing 3177:com.android.settings:remote/1000 (adj 15): empty #17
I/DeviceManagement( 3961): WorkflowService: Starting workflow service
I/DeviceManagement( 3961): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b026e8] args=[Bundle[mParcelledData.dataSize=144]]
I/DeviceManagement( 3961): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
,I/DeviceManagement( 3961): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  907): Recipient 3177
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DeviceManagement( 3961): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3961): SessionStateController: Checking invariants...
,D/HtcCupdReceiver(Provider)( 4019):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  907): acquireWL(426d4e60): PARTIAL_WAKE_LOCK  AsyncService 0x1 3637 10160 null
,D/PMS     (  907): releaseWL(426d4e60): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,I/SensorManager(  907): mEventCount = 300
,I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=4035 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,V/AlarmManager(  907): sending alarm PendingIntent{423f1188: PendingIntentRecord{426cbd50 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452261059956, Int=0
,D/Settings:HtcWirelessFeatureFlags( 3869): id/is att sku: 99/false
,W/GAV2    ( 3978): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,W/SystemReader( 3869): Cannot find devicepolicy_lower_fp_quality, use default value instead
W/ContextImpl( 4035): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 4035): call getInstance()
,I/DeviceManagement( 3961): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
W/SystemReader( 3869): Cannot find support_harman, use default value instead
,W/SystemReader( 3869): Cannot find effect_manager_id, use default value instead
V/AlarmManager(  907): sending alarm PendingIntent{41f6c498: PendingIntentRecord{4206ba60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=60780, Int=0
D/PMS     (  907): acquireWL(427fbed8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4035 1000 null
,D/PowerUsageList:PowerUsageHelper( 4035): MY_DEBUG = false
,W/WeatherUtility( 1117): can't get weather sync account
,E/Settings:HtcWrapHeaderInfo( 3869): no such activity!
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,D/WeatherUtility( 1396): Weather sync is On
W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,D/WSP     ( 1396): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,I/ActivityManager(  907): Delay finish: com.htc.widget.weatherclock/.util.WidgetReceiver
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/WeatherUtility( 3446): can't get weather sync account
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,W/BatSI   (  907): Couldn't get kernel wake lock stats
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3869): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3869): updateDevelopment, bPrefShow = true
,W/WeatherRequest( 3446): request cur loc, but there is no sys cur
,W/Settings( 3446): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Settings:HtcUmcWidgetEnabler( 3869): isSupportMusicChannel(): false
,D/AppWidgetHostView( 1271): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1271): com.htc.widget.weatherclock (true,33751552)
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3869): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3869): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3869): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3869): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3869): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3869): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3869): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3869): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3869): [supportHomeButton]support         :false
,I/RemoteViews.Performance( 1271): com.htc.widget.weatherclock 1 7 17
,I/ClockThread( 1117): now=1452261060110 next=59890
,W/FingerprintManager( 3869): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,I/ActivityManager(  907): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 3869): isSupportVoWifi: null
,I/DeviceManagement( 3961): SessionStateController: Checking invariants...
E/ActivityThread( 3869): Failed to find provider info for com.htc.vowifi
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 3928): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3928): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,I/DeviceManagement( 3961): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3961): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b026e8]
,I/DeviceManagement( 3961): WorkflowService: Stopping workflow service
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=4065 uid=10032 gids={50032, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,D/AutoSetting( 1396): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1396): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1396): service - requestNLP() NetworkLocationProvider not enabled
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3869): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3869): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3869): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3869): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3869): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3869): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3869): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3869): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3869): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3869): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3869): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3869): [supportHomeButton]support         :false
,W/FingerprintManager( 3869): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 3869): isSupportVoWifi: null
I/ActivityManager(  907): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3869): Failed to find provider info for com.htc.vowifi
,D/Process (  907): killProcessQuiet, pid=3760
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3760:com.qualcomm.timeservice/1000 (adj 15): empty #17
I/ActivityManager(  907): Recipient 3760
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=4080 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,I/MusicStore( 4080): Database version: 95
,W/ContextImpl( 4080): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4080): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4080): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/Finsky  ( 3928): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3928): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3928): [1] DailyHygiene.reschedule: Scheduling new run in 764 minutes (failures=5)
,D/Process (  907): killProcessQuiet, pid=2791
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2791:com.htc.sense.mms/u0a64 (adj 15): empty #17
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4080): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4080): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4080, uid=10154, userID:0
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/MediaRouterService(  907): Client com.google.android.music (pid 4080): Registered
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
I/MediaRouter( 4080): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/ActivityManager(  907): Recipient 2791
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/NetworkMonitor( 4080): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.music (4080/10154)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/MediaRouter( 4080): getSelectedRoute
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,I/NetworkMonitor( 4080): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4080/10154)
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
,I/ActivityManager(  907): Resuming delayed broadcast
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/Process (  907): killProcessQuiet, pid=3694
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4080, uid=10154, userID:0
I/ActivityManager(  907): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=4103 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
I/ActivityManager(  907): Killing 3694:com.htc.task/u0a70 (adj 15): empty #17
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3694
,D/DFPI.PIReciver( 4103): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 4103): onHandleIntent
,I/DFPI.ApkInstallService( 4103): Media Scan Finished Case 
D/DFPI.ApkInstallService( 4103): check CID = HTC__032
,I/DFPI.ApkInstallService( 4103): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=3817
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3817:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  907): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=4117 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
I/ActivityManager(  907): Recipient 3817
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (4117/10051)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (4117/10051)
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_MEDIA due to registered receiver BroadcastFilter{425969b8 u0 ReceiverList{42596898 4117 com.htc.musicenhancer/10051/u0 remote:42673070}}
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4117): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 312
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:124, mTXpacketCount:60, avgLinkspeed:62,mAvgTxRate72
,D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,V/AlarmManager(  907): sending alarm PendingIntent{42576d08: PendingIntentRecord{425e7a70 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1452261061038, Int=0
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=4137 uid=10080 gids={50080, 5001, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3831
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3831:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3831
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/SoundPicker( 4137): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 4137): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 4137): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 4137): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 4137): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 4137): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 4137): MODE_GSM access default DB
,I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 1, mode_cdma)
,I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
D/PMS     (  907): acquireWL(4259b290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4259b290): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 4)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 4137): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4137): MODE_GSM access default DB
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 1, mode_cdma)
,I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=3846
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3846:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,D/DFPI.PIReciver( 4103): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  907): Recipient 3846
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
,I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 4103): onHandleIntent
I/DFPI.ApkInstallService( 4103): Media Scan Finished Case 
D/DFPI.ApkInstallService( 4103): check CID = HTC__032
,I/DFPI.ApkInstallService( 4103): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Resuming delayed broadcast
,I/SoundPicker( 4137): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 4137): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 4137): SoundPickerReceiver [onReceive] startService
,I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 4137): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 4137): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 4137): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4137): MODE_GSM access default DB
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 4137): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4137): MODE_GSM access default DB
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/inte,rnal/audio/media/112 type=2
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/DFPI.PIReciver( 4103): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  907): Resuming delayed broadcast
I/DFPI.ApkInstallService( 4103): onHandleIntent
,I/DFPI.ApkInstallService( 4103): Media Scan Finished Case 
D/DFPI.ApkInstallService( 4103): check CID = HTC__032
,I/DFPI.ApkInstallService( 4103): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,I/SoundPicker( 4137): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 4137): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 4137): SoundPickerReceiver [onReceive] startService
,I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 4137): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 4137): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 4137): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4137): MODE_GSM access default DB
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 4137): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4137): MODE_GSM access default DB
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/inte,rnal/audio/media/112 type=2
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 4080): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=4159 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,D/PMS     (  907): releaseWL(427fbed8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/ActivityManager(  907): Delay finish: com.htc.task/.TodoTaskReceiver
,I/ActivityManager(  907): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=4172 uid=10063 gids={50063, 3003, 5012, 1023, 1028, 1015}
,I/ActivityManager(  907): Resuming delayed broadcast
D/DFPI.PIReciver( 4103): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/DFPI.ApkInstallService( 4103): onHandleIntent
,I/DFPI.ApkInstallService( 4103): Media Scan Finished Case 
D/DFPI.ApkInstallService( 4103): check CID = HTC__032
,I/DFPI.ApkInstallService( 4103): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,D/Process (  907): killProcessQuiet, pid=3775
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3775:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
,I/EASAppSvc( 4172): [ NA ]- onCreate()
I/ActivityManager(  907): Recipient 3775
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/EASAppSvc( 4172): [ NA ]> onUpgrade: version = 63
,D/ORMLib  ( 4159): put()
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=3788
,I/ActivityManager(  907): Killing 3788:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WifiService(  907): New client listening to asynchronous messages
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.android.mail (4172/10063)
,I/SoundPicker( 4137): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/EASAppSvc( 4172): [ NA ]- onDestroy()
,I/EASAppSvc( 4172): [ NA ]> uninitEASService
,W/ContextImpl( 4137): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/ActivityManager(  907): Recipient 3788
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.htc.android.mail (4172/10063)
D/ConnectivityService(  907): getNetworkInfo networkType=55 called by com.htc.android.mail (4172/10063)
,I/SoundPicker( 4137): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 4137): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 4137): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 4137): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4137): MODE_GSM access default DB
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 4137): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 4137): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4137): MODE_GSM access default DB
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 4137): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.fla,c
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4137): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 4137): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4137): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 4080): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/TelephonyReceiver( 1245): bind: true
I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(425f2dd8): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1512 10014 null
,I/ActivityManager(  907): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.GenericMessagesProvider: pid=4197 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  907): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  907): releaseWL(425f2dd8): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=4210 uid=10084 gids={50084, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,D/MessageFrequencyProvider( 4197): onCreate
,D/GenericMessagesProvider( 4197): query uri: content://htc-messages/wappush/count
,V/GetPrviateResource( 4197): GetPrviateResource
,V/GetPrviateResource( 4197): GetPrviateResource
E/SQLiteLog( 4197): (14) cannot open file at line 30190 of [00bb9c9ce4]
,E/SQLiteLog( 4197): (14) os_unix.c:30190: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 4197): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
,E/SQLiteConnection( 4197): DB info: errno = 2, errno message = No such file or directory
,I/EASRequestController( 4172): [ NA ]release
,E/SQLiteDatabase( 4197): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 4197): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 4197): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4197): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4197): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4197): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4197): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4197): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
E/SQLiteDatabase( 4197): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 4197): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4197): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4197): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 4197): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 4197): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 4197): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 4197): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 4197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/System.err( 4197): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/System.err( 4197): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
,W/System.err( 4197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
,W/System.err( 4197): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
,W/System.err( 4197): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
,W/System.err( 4197): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/System.err( 4197): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/System.err( 4197): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
,W/System.err( 4197): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 4197): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 4197): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 4197): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
W/System.err( 4197): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err( 4197): 	at dalvik.system.NativeStart.run(Native Method)
,I/EASAppSvc( 4172): [ NA ]< uninitEASService
,I/EASAppSvc( 4172): [ NA ]- onCreate()
,D/TelephonyReceiver( 1245): switchBindHtcMsgCursor: null
,I/EASAppSvc( 4172): [ NA ]> onUpgrade: version = 63
,I/ActivityManager(  907): Killing 3800:com.htc.sense.news/u0a75 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=3800
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.android.mail (4172/10063)
D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.htc.android.mail (4172/10063)
,D/ConnectivityService(  907): getNetworkInfo networkType=55 called by com.htc.android.mail (4172/10063)
,I/ActivityManager(  907): Recipient 3800
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ORMLib  ( 4159): put()
,D/Process (  907): killProcessQuiet, pid=3912
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/TelephonyReceiver( 1245): bind: false
,D/TelephonyReceiver( 1245): switchBindHtcMsgCursor: null
I/ActivityManager(  907): Killing 3912:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  907): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=4234 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,I/EASAppSvc( 4172): [ NA ]- onDestroy()
,I/EASAppSvc( 4172): [ NA ]> uninitEASService
,D/MessageCustFlag( 4197): sense_version=6.0
,D/BTAccessoryUtil( 4197): createReceiver
,I/EASRequestController( 4172): [ NA ]release
,D/BTAccessoryUtil( 4197): registerReceiver return intent = null
,D/MessageCustFlag( 4197): sku_id=99
,W/SystemReader( 4197): Cannot find message_ambs_application_id, use default value instead
,I/EASAppSvc( 4172): [ NA ]< uninitEASService
I/ActivityManager(  907): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=4247 uid=10067 gids={50067, 3003, 5012}
,D/Messaging( 4197): supportCMAS(SIE)/init? false/true
,D/MmsConfig( 4197): networkCode: 
,D/MessageCustFlag( 4197): sku_id=99
,D/MmsConfig( 4197): SIE smsPri: null
,D/MmsConfig( 4197): networkCode: 
,D/HtcTelephonyCapability( 4197): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4197): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4197): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4197): Cannot find qct_8960_interface, use default value instead
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/ActivityManager(  907): Recipient 3912
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ORMLib  ( 4159): put()
,W/GAV2    ( 4234): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  907): Delay finish: com.google.android.gm/.MailIntentReceiver
,D/PMS     (  907): acquireWL(425aee78): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
,D/PMS     (  907): releaseWL(425aee78): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/Process (  907): killProcessQuiet, pid=3978
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3978:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/PMS     (  907): acquireWL(41f802f8): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
,D/PMS     (  907): releaseWL(41f802f8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3978
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
D/NotificationService(  907): notification sound not played, stream=5 volume=0 always=false
,I/RemoteViews( 1117): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41e57d28 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.updater 2 6 1 10
,I/ActivityManager(  907): Resuming delayed broadcast
,I/RemoteViews( 1117): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41e77bc8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/ActivityManager(  907): Delay finish: com.google.android.gm/.GmailReceiver
I/RemoteViews.Performance( 1117): com.htc.updater 1 6 1 10
,I/Gmail   ( 4234): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4234): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4234): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4234): calculateUnknownSyncRationalesAndPurgeInBackground: running,
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.gm/.GmailReceiver
,I/NotifUtils( 4234): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
,I/NotifUtils( 4234): validateNotifications - cancelling account 61035162 / folder -317575340
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=4296 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/Process (  907): killProcessQuiet, pid=3995
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3995:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3995
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Babel   ( 4296): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4296): MmsConfig.loadMmsSettings
,E/dalvikvm( 4296): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 4296): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 4296): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 4296): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 4296): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,D/MmsCustomizationProvider( 4197): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 4197): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 4296): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4296): MmsConfig.loadFromDatabase
,E/Babel   ( 4296): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4296): MmsConfig.loadFromResources
,E/Babel   ( 4296): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4296): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4296, uid=10111, userID:0
,W/Settings( 4296): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4296, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4296, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4296, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4296, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4296, uid=10111, userID:0
,D/PMS     (  907): acquireWL(4244dc80): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4296 10111 null
,I/ActivityManager(  907): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/ProviderInstaller( 4296): Installed default security provider GmsCore_OpenSSL
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): releaseWL(4244dc80): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(424ffa20): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4296 10111 null
,I/ActivityManager(  907): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver,
,D/PMS     (  907): releaseWL(424ffa20): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/Process (  907): killProcessQuiet, pid=3961
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3961:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3961
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/HtcModeClient( 1512): handler message = 4011
E/HtcModeClient( 1512): Check connection and retry 7 times.
,D/PMS     (  907): acquireWL(4246f728): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4296 10111 null
,I/ActivityManager(  907): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  907): releaseWL(4246f728): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.talk (4296/10111)
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Babel   ( 4296): UserRecoverableAuthException.
,E/Babel   ( 4296): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/Babel   ( 4296): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4296): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:190)
E/Babel   ( 4296): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4296): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4296): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4296): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4296): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4296): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4296): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4296): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,E/Babel   ( 4296): Error getting auth token
,E/Babel   ( 4296): com.google.android.apps.babel.util.AccountsUtil$BabelAuthException
E/Babel   ( 4296): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:200)
E/Babel   ( 4296): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4296): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4296): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4296): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4296): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4296): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4296): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4296): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
,E/Babel   ( 4296): Account registration failedRedacted-21
E/Babel   ( 4296): com.google.android.apps.babel.realtimechat.RequestWriter$BabelClientException: null -- null
E/Babel   ( 4296): 	at com.google.android.apps.babel.network.c.d(SourceFile:115)
E/Babel   ( 4296): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4296): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4296): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4296): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4296): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4296): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:906)
E/Babel   ( 4296): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1094)
I/Babel   ( 4296): Account setup failed with error state:106 account:Redacted-21
,I/Babel   ( 4296): Account sign in complete with state 106account: Redacted-21
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.talk (4296/10111)
,W/GLSUser ( 1365): GoogleAccountDataService.getToken()
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1365): GLS error: BadAuthentication thalitester@gmail.com oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,W/GLSActivity( 1365): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Babel   ( 4296): Unexpected exception while authenticating.
D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,E/Babel   ( 4296): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/Babel   ( 4296): 	at com.google.android.gms.auth.a.b(Unknown Source)
E/Babel   ( 4296): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4296): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:187)
E/Babel   ( 4296): 	at com.google.android.apps.babel.network.c.cP(SourceFile:138)
E/Babel   ( 4296): 	at com.google.android.apps.babel.realtimechat.ca.run(SourceFile:5226)
E/Babel   ( 4296): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 4296): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 4296): 	at java.lang.Thread.run(Thread.java:864)
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41ec9668 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.google.android.gms 1 7 2 12
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/Messaging( 4197): mNeedToUpdateDate2 start
,D/MmsConfig( 4197): packageName: com.htc.vvm.att does not exist
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1245):  phoneType = -1
,D/MmsSmsV2Provider( 1245): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/ReportIndicatorCache( 4197): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4197): 
D/MmsAsyncWorkHandler( 4197): HM tk = 20001
,D/ReportIndicatorCache( 4197): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4197): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41ad5180
,I/Messaging( 4197): mccmnc> 
D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1245): sku_id=99
,D/DraftCache( 4197): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4197): [DraftCache/1] refresh
,D/MmsConfig( 4197): networkCode: 
,D/Messaging( 4197): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/MmsSmsV2Provider( 1245):  phoneType = -1
,D/MmsSmsV2Provider( 1245): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/DraftCache( 4197): [DraftCache/433] rebuildCache
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/MmsSmsV2Provider( 1245):  phoneType = -1
,D/MmsSmsV2Provider( 1245): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/Messaging( 4197): mNeedToUpdateDate2: false
D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
D/Jerry   ( 1245): URI_DRAFT
D/PhoneStorageUtil( 4197): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4197): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4197): createReceiver
D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
D/MmsSmsV2Provider( 1245):  phoneType = -1
,D/MmsSmsV2Provider( 1245): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
D/TelephUtils( 1245): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
V/MmsProvider( 1245): Update uri=content://mms, match=0
,V/MmsProvider( 1245): selection=st=129 AND m_type!=134
,D/DraftCache( 4197): hasDraft() = false mNeedNotifyChange = true
D/MessageCustFlag( 4197): sense_version=6.0
D/DraftCache( 4197): [DraftCache/433] rebuildCache time: 4
,D/MmsAsyncWorkHandler( 4197): 
D/MmsAsyncWorkHandler( 4197): HM tk = 20002
D/Jerry   ( 4197): start to preload cursor >>>>>>>
,D/Messaging( 4197): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4197): TransactionService is going to be woken up.
D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/MmsSmsV2Provider( 1245):  phoneType = -1
,D/Messaging( 4197): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 31
,D/AccFlag ( 1245): sku_id=99
I/ActivityManager(  907): Delaying start of: ServiceRecord{427edaa8 u0 com.htc.sense.mms/.transaction.TransactionService}
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1245): sku_id=99
D/Messaging( 4197): ViewCache CreatePreload
,D/Messaging( 4197): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Cust_MMSMS( 4197): _has_set_default_values_2=true
,D/MsgPreferenceUtils( 4197): def_index: 0
,D/MsgPreferenceUtils( 4197): globalIndex = 1
D/MsgPreferenceUtils( 4197): phone state: true
D/MsgPreferenceUtils( 4197): sd state: false
,D/MsgPreferenceUtils( 4197): vIndex = 0
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,V/AlarmManager(  907): sending alarm PendingIntent{4233e3e0: PendingIntentRecord{41bfdd38 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1452261065667, Int=0
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,V/TransactionService( 4197): 1-Creating TransactionService
,V/TransactionService( 4197): onStartCommand: 1
,D/MmsSystemEventReceiver( 4197): unRegisterForConnectionStateChanges
V/TransactionService( 4197): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4197): Loading previous transactions.
,D/TelephUtils( 1245): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
,D/AccFlag ( 1245): device_type: 1
,D/TransactionService( 4197): Force set service start id to 1
V/TransactionService( 4197): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4197): unRegisterForConnectionStateChanges
,D/TransactionService( 4197): stopSelfResult: true, mLastHandledServiceId: 1
I/ActivityManager(  907): Resuming delayed broadcast
D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,V/TransactionService( 4197): Destroying TransactionService
,V/TransactionService( 4197): 4-Handling incoming message: { when=-1ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/Process (  907): killProcessQuiet, pid=4019
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/PackageBroadcastService( 1225): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
I/ActivityManager(  907): Killing 4019:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/ConnectivityService(  907): Done.
,D/ConnectivityService(  907): Setting timer for 720seconds
,I/ActivityManager(  907): Recipient 4019
,I/PeopleContactsSync( 1225): CP2 sync disabled
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1225, uid=10028, userID:0
D/PMS     (  907): acquireWL(423bed18): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
,D/PMS     (  907): releaseWL(423bed18): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1396): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1396): handle notify Blinkfeed plugin client changed
,I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,I/IcingCorporaProvider( 2907): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/IcingCorporaProvider( 2907): UpdateCorporaTask done [took 44 ms] updated apps [took 44 ms] 
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  907): acquireWL(4204d760): PARTIAL_WAKE_LOCK  AsyncService 0x1 3637 10160 null
,D/PMS     (  907): releaseWL(4204d760): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,D/GCM     ( 1365): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1365): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  907): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(4200f150): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4159 10070 null
,D/PMS     (  907): acquireWL(425791a0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4159 10070 null
,D/PMS     (  907): releaseWL(4200f150): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  907): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
E/TodoTaskNotifyService( 4159): java.lang.NullPointerException
W/System.err( 4159): java.lang.NullPointerException
W/System.err( 4159): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4159): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4159): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4159): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4159): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4159): stopSelfResult true
D/PMS     (  907): releaseWL(425791a0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): acquireWL(425ed010): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4159 10070 null
E/TodoTaskNotifyService( 4159): java.lang.NullPointerException
,W/System.err( 4159): java.lang.NullPointerException
W/System.err( 4159): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4159): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4159): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4159): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4159): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 4159): stopSelfResult true
D/PMS     (  907): acquireWL(425baec0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4159 10070 null
I/ActivityManager(  907): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
D/PMS     (  907): releaseWL(425ed010): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  907): releaseWL(425baec0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
E/TodoTaskNotifyService( 4159): java.lang.NullPointerException
W/System.err( 4159): java.lang.NullPointerException
,W/System.err( 4159): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4159): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4159): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4159): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4159): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  907): acquireWL(425869e8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4159 10070 null
D/PMS     (  907): acquireWL(4279a0b0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4159 10070 null
I/ActivityManager(  907): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
D/PMS     (  907): releaseWL(425869e8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  907): releaseWL(4279a0b0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 4159): stopSelfResult true
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): acquireWL(42675678): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(4260d878): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/GCM     ( 1365): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  907): releaseWL(42675678): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
D/PMS     (  907): releaseWL(4260d878): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/GCM     ( 1365): GCM config loaded
,I/WSP     ( 1396): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1396): Weather sync is On
,I/WSP     ( 1396): [Receiver] next auto-sync alarm event is 60 mins later, at time: Fri Jan 08 15:51:06 CET 2016
I/ActivityManager(  907): Delay finish: com.google.android.gm/.MailIntentReceiver
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.htc.task/.TodoReceiver
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1396/10053)
,D/PMS     (  907): acquireWL(425ac928): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1396 10053 null
,D/TodoTaskshortcut( 4159): update TASK shortcut>
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/GAV2    ( 4234): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager(  907): sending alarm PendingIntent{427401d0: PendingIntentRecord{41cbe288 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1452261067520, Int=0
,I/GAV4    ( 4296): Thread[GAThread,5,main]: No campaign data found.
,I/HtcModeClient( 1512): handler message = 4011
,E/HtcModeClient( 1512): Check connection and retry 8 times.
,D/Process (  907): killProcessQuiet, pid=4035
,I/ActivityManager(  907): Killing 4035:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 4035
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  907): acquireWL(427537a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(427537a8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
,D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,I/CalendarProvider2( 1512): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1512): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/SensorManager(  907): mEventCount = 450
I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(42618768): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4080 10154 null
,I/ActivityManager(  907): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 4080): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4080): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4080, uid=10154, userID:0
,I/MusicLeanback( 4080): Conditions not met for autocaching.
,I/MusicLeanback( 4080): Stop autocaching.
D/PMS     (  907): releaseWL(42618768): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4396 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 4396): Loading default preferences
,W/Resources( 4396): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  907): New client listening to asynchronous messages
,D/SyncApplication( 4396): Overriding preferences with custom values
,D/SyncApplication( 4396): Updating preferences succeeded
,E/SyncApplication( 4396): Application created.
D/VolumeInfo( 4396): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4396): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
,V/VolumeInfo( 4396): Found 0 mount point(s)
,V/VolumeInfo( 4396): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4396): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4396): getNewCalendarAuthority()...
,D/VolumeInfo( 4396): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
,W/VolumeInfo( 4396): Can not create volume ID for unmounted volume null
,D/SyncApplication( 4396): enableAppOperation()+
,D/SyncApplication( 4396): enableAppOperation()-
,D/HTCUtilities( 4396): isNeorSinged() + 
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4396, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4396, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 4396): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4396): isNeorSinged() return false
,D/CDMountReceiver( 4396): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4396): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/CDMountReceiver( 4396): enable CD Auto-mount: true
,D/HTCUtilities( 4396): enable auto-mount
,D/HTCUtilities( 4396): enable auto-mount
,I/RemoteViews( 1117): com.nero.android.htc.sync (false,0)
I/ActivityManager(  907): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41b54e60 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/MountService(  907): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): releaseWL(42570e90): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
D/MountService(  907): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,I/RemoteViews.Performance( 1117): com.nero.android.htc.sync 1 13 3 11
,I/RemoteViews( 1117): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41f64330 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.nero.android.htc.sync 1 9 3 16
,W/MediaManager( 4065): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=3446
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3446:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3446
,I/ActivityManager(  907): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4420 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/CalendarApplication( 4420): onCreate
D/ProviderChangeReceiver( 4420): ---------------------------------------------------
,D/ProviderChangeReceiver( 4420): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4420): start to updateAlertNotification!
,I/ActivityManager(  907): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4434 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  907): killProcessQuiet, pid=4103
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  907): Killing 4103:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
D/AlertService( 4420): No fired or scheduled alerts
D/HtcAlertUtils( 4420): -- cancelReminderNotification --
D/HtcAlertUtils( 4420): broadcastExistReminder!
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  907): Recipient 4103
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/Settings:HtcSettingsApplication( 4434): [4434/4434] onCreate()
W/ContextImpl( 4434): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  907): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=4172
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4172:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4172
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/HtcModeClient( 1512): handler message = 4011
,E/HtcModeClient( 1512): Check connection and retry 9 times.
,D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=87 rxSum=89} preTxRxSum={txSum=64 rxSum=71}
D/WifiDataStallTracker(  907): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  907): onDataStallAlarm: tag=19722 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19723 delay=15s
D/PMS     (  907): acquireWL(42607928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{4273da60: PendingIntentRecord{424b4ce8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=73987, Int=0
D/PMS     (  907): releaseWL(42607928): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  907): acquireWL(42604978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10073}
,V/AlarmManager(  907): sending alarm PendingIntent{4254f110: PendingIntentRecord{425b3828 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452261075240, Int=0
,D/PMS     (  907): releaseWL(42604978): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 3928): [1] 5.onFinished: Installation state replication succeeded.
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{41f80438 u0 com.htc.musicenhancer/.EnhancerService}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:124, mTXpacketCount:124, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/PMS     (  907): releaseWL(425ac928): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,I/HtcModeClient( 1512): handler message = 4011
,E/HtcModeClient( 1512): Check connection and retry 10 times.
,I/SensorManager(  907): mEventCount = 600
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC <<
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WIFI_ICON( 1117): WifiActivity: 1
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 1512): handler message = 4011
,E/HtcModeClient( 1512): Check connection and retry 11 times.
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [1][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/SensorManager(  907): mEventCount = 750
,D/AutoSetting( 1396): service - has update message, not stop
,D/AutoSetting( 1396): service - mHandler: update timezone
,D/AutoSetting( 1512): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1512): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1512): service - onCreate()
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1512): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1512): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1512): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1512): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1512): service - mHandler: update timezone
,D/AutoSetting( 1512): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1512): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1512): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1512): service - showManualTimeZoneSelector() send notification (single)
D/DotMatrix( 1565): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1117): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41f83648 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1117): com.htc.htclocationservice 3 6 2 11
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=88 rxSum=90} preTxRxSum={txSum=87 rxSum=89}
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiDataStallTracker(  907): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  907): onDataStallAlarm: tag=19723 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19724 delay=15s
D/PMS     (  907): acquireWL(4251fe88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{425f08a8: PendingIntentRecord{424b4ce8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=88999, Int=0
,D/PMS     (  907): releaseWL(4251fe88): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
,I/HtcModeClient( 1512): handler message = 4011
,E/HtcModeClient( 1512): Check connection and retry 12 times.
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  907): acquireWL(4232b798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(4232b798): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=50 [2][1][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:128, mTXpacketCount:124, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/SensorManager(  907): mEventCount = 900
,I/HtcModeClient( 1512): handler message = 4011
,E/HtcModeClient( 1512): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1512): Don't start project servcice
,D/HtcModeClient( 1512): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1512): connectState: CONNECTION_READY = false
,D/SilentMusic( 1512): call stop
,D/HtcModeClient( 1512): close connection
,W/HtcModeClient( 1512): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1512): read the terminate packet, so break
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{42610cb8 u0 com.htc.htclocationservice/.AutoSettingService}
,I/SensorManager(  907): mEventCount = 1050
,D/PMS     (  907): acquireWL(42593f78): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
,D/PMS     (  907): releaseWL(42593f78): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/PMS     (  907): acquireWL(425cb420): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
,D/PMS     (  907): releaseWL(425cb420): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(425c2428): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
,D/PMS     (  907): releaseWL(425c2428): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(425f3830): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
,D/PMS     (  907): releaseWL(425f3830): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  907): acquireWL(4273c9a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{42596888: PendingIntentRecord{424b4ce8 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=104008, Int=0
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=89 rxSum=91} preTxRxSum={txSum=88 rxSum=90}
,D/WifiDataStallTracker(  907): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  907): onDataStallAlarm: tag=19724 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19725 delay=15s
D/PMS     (  907): releaseWL(4273c9a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ActivityManager(  907): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4459 uid=10077 gids={50077}
D/PMS     (  907): acquireWL(4261cb40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10077}
V/AlarmManager(  907): sending alarm PendingIntent{42619400: PendingIntentRecord{426d2970 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452261103309, Int=60000
,D/PMS     (  907): releaseWL(4261cb40): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/SMSBackup( 4459): SMSBackupAgentService started
,D/SMSBackup( 4459): Checking restore status
D/SMSBackup( 4459): Restore complete
,D/SMSBackup( 4459): cancelCheckAlarm
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/SMSBackup( 4459): SMSBackupAgentService completed: completed in 0.0 seconds
D/Process (  907): killProcessQuiet, pid=4137
,I/ActivityManager(  907): Killing 4137:com.htc.sdm/u0a80 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 4137
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:128, mTXpacketCount:128, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/PMS     (  907): Going to sleep due to screen timeout...
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42119da8
,W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42119da8, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420eabb0
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@4259f7c0
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/PMS     (  907): mWirelessDisplayManager is null
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
V/LightsService(  907): setLight #0: color=#0
W/BatSI   (  907): Couldn't get kernel wake lock stats
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 400ms
D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
D/NfcService( 1256): ScreenObserver: OFF
I/IntentController( 1117): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/NfcService( 1256): applyRouting - 0
,V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@426fbd88)
,D/NfcService( 1256): applyRouting -2
D/PMS     (  907): OOBE c monitor 11
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 3506 uid 10356
D/PMN     (  907): wakingUp
D/PMS     (  907): acquireWL(427fda48): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
D/PMS     (  907): releaseWL(427fda48): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  907): No lock screen! windowToken=null
D/PMN     (  907): onScreenOn
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
,D/PMS     (  907): acquireWL(425c5910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=19726 delay=15s
D/MtpService( 2460): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1256): applyRouting - 0
,D/NfcService( 1256): applyRouting -2
,D/MtpService( 2460): [MTP][onReceive]-
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(425c5910): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(4279c268): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1256 1027 null
,D/PMS     (  907): releaseWL(4279c268): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,I/ClockThread( 1117): stop update clock
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4479 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/HtcPowerSaver(  907): updateBatteryInfo
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): SET_SCREEN_ON:On
I/wpa_supplicant( 1165): htc_wext_set_keepalive +
I/wpa_supplicant( 1165): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1165): getPrivFuncNum +	
I/wpa_supplicant( 1165): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1165): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1165): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1165): BG scan when screen On
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): Match BG scan, scan!
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  907):    returned true
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/IntentController( 1117): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1117): closing low battery warning: level=100
D/PowerUI ( 1117): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1117): status:5 level:100 unsupport:false plugged:true
,V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,V/SRS_Proc(  372): ParamSet string: screen_state=on
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/NetworkPolicy(  907): updateScreenOn: false
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,W/ContextImpl( 4479): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  907): acquireWL(42720d58): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4479 1000 null
D/SmartSyncUtils( 4479): isEpsOn(), nState = 0
,D/DotMatrix( 1565): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  907): releaseWL(42720d58): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4479): getMobilePolicyEnabled, result = true
,D/AutoSetting( 1396): receiver - intent: android.intent.action.USER_PRESENT
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1795): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1795): onScreenOn: 1452261111636
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1795): onScreenOn: 1452261111637
D/PMS     (  907): acquireWL(42785138): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1449 10028 null
,D/PMS     (  907): releaseWL(42785138): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/SensorManager(  907): mEventCount = 1200
I/SensorManager(  907): mEventCount = 1200
D/TetherSettings( 3869): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3869): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3869): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3869): Cust_ConnectToPC   : spcsc>false
D/        ( 3869): Cust_ConnectToPC   : IPT>true
D/        ( 3869): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3869): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3869): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3869): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3869): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/AutoSetting( 1396): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/PSReceiver( 3869): onReceive:android.intent.action.USER_PRESENT
,W/ContextImpl( 3869): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3869): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3869): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3869):  defaultType:0
I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420eabb0
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@420eabb0, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@4259f7c0
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  907): goingToSleep
I/FeedHostManager( 1271): [onPause]
I/FeedProviderManager( 1271): onPause
,I/FeedHostManager( 1271): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41fc8d28
I/SocialFeedProvider( 1271): +onPause
,I/SocialFeedProvider( 1271): -onPause
,D/Process (  907): killProcessQuiet, pid=4210
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processNextBroadcast:696 
D/PMS     (  907): acquireWL(42780980): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
I/ActivityManager(  907): Killing 4210:com.htc.updater/u0a84 (adj 15): empty #17
,D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=19726 mDataStallAlarmIntent=PendingIntent{41ef03b8: PendingIntentRecord{424b4ce8 android broadcastIntent}}
I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
D/PMS     (  907): releaseWL(42780980): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
I/ActivityManager(  907): Recipient 4210
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  907): acquireWL(42645520): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
,W/ContextImpl( 4479): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4479): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4479): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4479): isEpsOn(), nState = 0
D/WifiService(  907): New client listening to asynchronous messages
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC <<
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): SET_SCREEN_ON:Off
I/wpa_supplicant( 1165): htc_wext_set_keepalive +
I/wpa_supplicant( 1165): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1165): getPrivFuncNum +	
I/wpa_supplicant( 1165): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1165): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1165): get_ip_address source addr = c0a80176
I/wpa_supplicant( 1165): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1165): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  907):    returned true,
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4259f7c0
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4259f7c0, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@4259f7c0, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@4259f7c0
,E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42357c18 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42357c18 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
,V/SRS_Proc(  372): ParamSet string: screen_state=off
D/NetworkPolicy(  907): updateScreenOn: false
,D/ContactMessageStore( 1245): start background delete task...
D/ContactMessageStore( 1245): size: 0 , 0
,D/ContactMessageStore( 1245): Background delete complete
,D/AutoSetting( 1396): service - mHandler: cancel location update
,D/AutoSetting( 1396): service -           changes count: 0
,D/DotMatrix( 1565): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1565): [EventService] getTotalRam: 1873 Mb
,D/PMS     (  907): acquireWL(426f5950): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1449 10028 null
,D/PMS     (  907): releaseWL(426f5950): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1795): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1795): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1795): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1795): disableBatteryAlarm: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1795): onScreenOff
,D/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(42645520): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-76
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1165): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1165): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 1165): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=9 entropy=0
D/wpa_supplicant( 1165): Add randomness: count=10 entropy=1
D/wpa_supplicant( 1165): Add randomness: count=11 entropy=2
D/wpa_supplicant( 1165): Add randomness: count=12 entropy=3
D/wpa_supplicant( 1165): Add randomness: count=13 entropy=4
D/wpa_supplicant( 1165): Add randomness: count=14 entropy=5
D/wpa_supplicant( 1165): Add randomness: count=15 entropy=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wp,a_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1165): 3: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 4: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 6: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-76
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1165): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1165): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 1165): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=16 entropy=7
D/wpa_supplicant( 1165): Add randomness: count=17 entropy=8
D/wpa_supplicant( 1165): Add randomness: count=18 entropy=9
D/wpa_supplicant( 1165): Add randomness: count=19 entropy=10
D/wpa_supplicant( 1165): Add randomness: count=20 entropy=11
D/wpa_supplicant( 1165): Add randomness: count=21 entropy=12
D/wpa_supplicant( 1165): Add randomness: count=22 entropy=13
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: DISCONNECTED -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@42601578 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@42601578 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@42601578 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
,D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1165): reply (921) for get BSS: id=0
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000000114306848
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=1
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-55
I/wpa_supplicant( 1165): tsf=0000000114306887
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=2
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-79
I/wpa_supplicant( 1165): tsf=0000000114306898
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=3
I/wpa_supplicant( 1165): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1165): freq=2437
I/wpa_supplicant( 1165): level=-76
I/wpa_supplicant( 1165): tsf=0000000114306907
,I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1165): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1165): freq=2437
I/wpa_supplicant( 1165): level=-85
I/wpa_supplicant( 1165): tsf=0000000114306917
I/wpa_supplicant( 1165): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=UPC Wi-Free
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=5
I/wpa_supplicant( 1165): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1165): freq=2437
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000000114306926
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=UPC5999698,
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-55
I/wpa_supplicant( 1165): tsf=0000000114306875
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 114306848, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 114306887, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 114306898, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -76, frequency: 2437, timestamp: 114306907, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 114306917, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 114306926, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 114306875, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 7 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  8 [-76], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (7) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/AutoSetting( 1512): service - handleMessage() stop self,
,D/AutoSetting( 1512): service - onDestroy() END
,D/AutoSetting( 1512): service - handleMessage() quit looper,
,D/Process (  907): killProcessQuiet, pid=4247
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 ,
I/ActivityManager(  907): Killing 4247:com.htc.task.gtask/u0a67 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4247
,D/PMS     (  907): acquireWL(4279f198): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41f6c498: PendingIntentRecord{4206ba60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=120780, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4279f198): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  907): killProcessQuiet, pid=4117
,I/ActivityManager(  907): Killing 4117:com.htc.musicenhancer/u0a51 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 4117
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/PMS     (  907): acquireWL(426f9d78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(426f9d78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-78
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1165): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1165): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 1165): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=23 entropy=14
D/wpa_supplicant( 1165): Add randomness: count=24 entropy=15
D/wpa_supplicant( 1165): Add randomness: count=25 entropy=16
D/wpa_supplicant( 1165): Add randomness: count=26 entropy=17
D/wpa_supplicant( 1165): Add randomness: count=27 entropy=18
D/wpa_supplicant( 1165): Add randomness: count=28 entropy=19
D/wpa_supplicant( 1165): Add randomness: count=29 entropy=20
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1165): 3: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 4: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len,=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 6: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (7 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-78
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1165): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1165): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
D/wpa_supplicant( 1165): BSS: last_scan_res_used=7/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=30 entropy=21
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1165): Add randomness: count=31 entropy=22
D/wpa_supplicant( 1165): Add randomness: count=32 entropy=23
D/wpa_supplicant( 1165): Add randomness: count=33 entropy=24
D/wpa_supplicant( 1165): Add randomness: count=34 entropy=25
D/wpa_supplicant( 1165): Add randomness: count=35 entropy=26
D/wpa_supplicant( 1165): Add randomness: count=36 entropy=27
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString,: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1165): reply (921) for get BSS: id=0
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000000114306848
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====,
I/wpa_supplicant( 1165): id=1
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-55
I/wpa_supplicant( 1165): tsf=0000000131715723
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=2
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-79
I/wpa_supplicant( 1165): tsf=0000000114306898
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=3
I/wpa_supplicant( 1165): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1165): freq=2437
I/wpa_supplicant( 1165): level=-78
I/wpa_supplicant( 1165): tsf=0000000131715741
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1165): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1165): freq=2437
I/wpa_supplicant( 1165): level=-85
I/wpa_supplicant( 1165): tsf=0000000131715752
I/wpa_supplicant( 1165): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=UPC Wi-Free
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=5
I/wpa_supplicant( 1165): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1165): freq=2437
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000000131715761
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=UPC5999698
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-55
I/wpa_supplicant( 1165): tsf=0000000131715710
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ####
,D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 114306848, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 131715723, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 114306898, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -78, frequency: 2437, timestamp: 131715741, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 131715752, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 131715761, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 131715710, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 7 to mScanResults,
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  8 [-78], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0,
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (7) end of scan result ==,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2,
,D/PMS     (  907): acquireWL(41f02fb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423dedb8: PendingIntentRecord{4230b208 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141327, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{426f6540: PendingIntentRecord{4258a4e8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=143066, Int=0
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,D/AutoSetting( 1396): service - handleMessage() stop self
D/PMS     (  907): acquireWL(41f050b0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1365/10028)
D/PMS     (  907): releaseWL(41f02fb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
D/PMS     (  907): acquireWL(427a90d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1365 10028 null
,D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =72c4 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
D/PMS     (  907): releaseWL(427a90d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/AutoSetting( 1396): service - onDestroy() END
,D/AutoSetting( 1396): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=3656
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3656:com.google.android.gms.unstable/u0a28 (adj 15): empty #17
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  365): [NET]res_nsend:resplen=238
D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  907): [NET] getaddrinfo_proxy-, success
I/global  (  907): call createSocket() return a new socket.
D/libc    (  907): [NET] getaddrinfo+,hn 14(0x35342e3233302e),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
,I/ActivityManager(  907): Recipient 3656
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/PMS     (  907): releaseWL(41f050b0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null,
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3,
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (10 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-77
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
I/wpa_supplicant( 1165): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1165): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1165): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1165): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
I/wpa_supplicant( 1165): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-91
D/wpa_supplicant( 1165): BSS: last_scan_res_used=10/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=37 entropy=28
D/wpa_supplicant( 1165): Add randomness: count=38 entropy=29
D/wpa_supplicant( 1165): Add randomness: count=39 entropy=30
D/wpa_supplicant( 1165): Add randomness: count=40 entropy=31
D/wpa_supplicant( 1165): Add randomness: count=41 entropy=32
D/wpa_supplicant( 1165): Add randomness: count=42 entropy=33
D/wpa_supplicant( 1165): Add randomness: count=43 entropy=34
D/wpa_supplicant( 1165): Add randomness: count=44 entropy=35
D/wpa_supplicant( 1165): Add randomness: count=45 entropy=36
D/wpa_supplicant( 1165): Add randomness: count=46 entropy=37
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP 64:7c:34:38:27:cc type 0 added
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1165): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1165): Start print parameters
,I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1165): 3: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 4: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 6: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 7: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 8: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 9: dc:4a:3e:0f:c2:f1 ssid='DIRECT-AD-HP DeskJet 3630 series' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (10 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-77
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-83
I/wpa_supplicant( 1165): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1165): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1165): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1165): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
I/wpa_supplicant( 1165): [NULL] dc:4a:3e:0f:c2:f1 freq=2437 level=-91
D/wpa_supplicant( 1165): BSS: last_scan_res_used=10/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=47 entropy=38
,D/wpa_supplicant( 1165): Add randomness: count=48 entropy=39
D/wpa_supplicant( 1165): Add randomness: count=49 entropy=40
D/wpa_supplicant( 1165): Add randomness: count=50 entropy=41
D/wpa_supplicant( 1165): Add randomness: count=51 entropy=42
D/wpa_supplicant( 1165): Add randomness: count=52 entropy=43
,D/wpa_supplicant( 1165): Add randomness: count=53 entropy=44
D/wpa_supplicant( 1165): Add randomness: count=54 entropy=45
D/wpa_supplicant( 1165): Add randomness: count=55 entropy=46
D/wpa_supplicant( 1165): Add randomness: count=56 entropy=47
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1165): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: Unknown Vendor Extension (Vendor ID 311)
,D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP 64:7c:34:38:27:cc type 0 added
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1165): WPS: AP dc:4a:3e:0f:c2:f1 type 0 added
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1165): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: Unknown Vendor Extension (Vendor ID 311)
I/wpa_supplicant( 1165): reply (1356) for get BSS: id=0
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000000149206383
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=1
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-55
I/wpa_supplicant( 1165): tsf=0000000149206421
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=2
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-83
I/wpa_supplicant( 1165): tsf=0000000114306898
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
,I/wpa_supplicant( 1165): id=3
I/wpa_supplicant( 1165): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1165): freq=2437
I/wpa_supplicant( 1165): level=-77
I/wpa_supplicant( 1165): tsf=0000000149206431
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1165): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1165): freq=2437
I/wpa_supplicant( 1165): level=-85
I/wpa_supplicant( 1165): tsf=0000000149206441
I/wpa_supplicant( 1165): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=UPC Wi-Free
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=5
I/wpa_supplicant( 1165): bssid=64:7c:34:12:7f:81
,I/wpa_supplicant( 1165): freq=2437
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000000149206450
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=UPC5999698
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-55
I/wpa_supplicant( 1165): tsf=0000000149206410
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=7
I/wpa_supplicant( 1165): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1165): freq=2462
I/wpa_supplicant( 1165): level=-90
I/wpa_supplicant( 1165): tsf=0000000149206470
,I/wpa_supplicant( 1165): flags=
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 149206383, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 149206421, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -83, frequency: 2412, timestamp: 114306898, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -77, frequency: 2437, timestamp: 149206431, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 149206441, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 149206450, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 149206410, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 7: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 149206470, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 8: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 149206481, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 9: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -91, frequency: 2437, timestamp: 149206492, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 10 to mScanResults
V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-83], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  8 [-77], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  67, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  0 [-91], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (10) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-77
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1165): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1165): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1165): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1165): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
D/wpa_supplicant( 1165): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=57 entropy=48
D/wpa_supplicant( 1165): Add randomness: count=58 entropy=49
D/wpa_supplicant( 1165): Add randomness: count=59 entropy=50
D/wpa_supplicant( 1165): Add randomness: count=60 entropy=51
D/wpa_supplicant( 1165): Add randomness: count=61 entropy=52
D/wpa_supplicant( 1165): Add randomness: count=62 entropy=53
D/wpa_supplicant( 1165): Add randomness: count=63 entropy=54
D/wpa_supplicant( 1165): Add randomness: count=64 entropy=55
D/wpa_supplicant( 1165): Add randomness: count=65 entropy=56
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->,reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1165): 3: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 4: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 6: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1165): 7: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 8: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-77
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1165): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1165): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1165): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1165): [NULL] 64:7c:34:38:27:cc freq=2462 level=-91
D/wpa_supplicant( 1165): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=66 entropy=57
D/wpa_supplicant( 1165): Add randomness: count=67 entropy=58
D/wpa_supplicant( 1165): Add randomness: count=68 entropy=59
D/wpa_supplicant( 1165): Add randomness: count=69 entropy=60
D/wpa_supplicant( 1165): Add randomness: count=70 entropy=61
D/wpa_supplicant( 1165): Add randomness: count=71 entropy=62
D/wpa_supplicant( 1165): Add randomness: count=72 entropy=63
D/wpa_supplicant( 1165): Add randomness: count=73 entropy=64
D/wpa_supplicant( 1165): Add randomness: count=74 entropy=65
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplica,nt( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: Unknown Vendor Extension (Vendor ID 311),
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: Unknown Vendor Extension (Vendor ID 311)
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1165): WPS: Unknown Vendor Extension (Vendor ID 311)
I/wpa_supplicant( 1165): reply (1356) for get BSS: id=0
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000000166643545
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=1
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-55
I/wpa_supplicant( 1165): tsf=0000000166643583
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=2
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-80
I/wpa_supplicant( 1165): tsf=0000000166643594
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
,I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=3
I/wpa_supplicant( 1165): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1165): freq=2437
I/wpa_supplicant( 1165): level=-77
I/wpa_supplicant( 1165): tsf=0000000166643602
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1165): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1165): freq=2437
I/wpa_supplicant( 1165): level=-85
I/wpa_supplicant( 1165): tsf=0000000166643613
I/wpa_supplicant( 1165): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=UPC Wi-Free
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=5
I/wpa_supplicant( 1165): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1165): freq=2437
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000000166643622
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=UPC5999698
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-55
I/wpa_supplicant( 1165): tsf=0000000166643572
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=7
I/wpa_supplicant( 1165): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1165): freq=2462
I/wpa_supplicant( 1165): level=-90
I/wpa_supplicant( 1165): tsf=0000000166643632
I/wpa_supplicant( 1165): flags=
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 166643545, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 166643583, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 166643594, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -77, frequency: 2437, timestamp: 166643602, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 166643613, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 166643622, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 166643572, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 7: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 166643632, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 8: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -91, frequency: 2462, timestamp: 166643642, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 9: scan result = SSID: DIRECT-AD-HP DeskJet 3630 series, BSSID: dc:4a:3e:0f:c2:f1, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -91, frequency: 2437, timestamp: 149206492, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 10 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  8 [-77], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-91], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  67, AP: DIRECT-AD-HP DeskJet 3630 series [dc:4a:3e:0f:c2:f1], Rssi:  0 [-91], Tx: 13, Freq:  4 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (10) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4,
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1225/10028)
,D/PMS     (  907): acquireWL(4283d0a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10026}
,V/AlarmManager(  907): sending alarm PendingIntent{4279d0a0: PendingIntentRecord{423a4328 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=176823, Int=0
,D/PMS     (  907): releaseWL(4283d0a0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10026}
,D/PMS     (  907): acquireWL(4283ee18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41f6c498: PendingIntentRecord{4206ba60 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=180779, Int=0
,I/IntentController( 1117): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(4283ee18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/TelephonyReceiver( 1245): switchBindHtcMsgCursor: null,
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-78
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1165): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1165): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1165): [NULL] 64:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1165): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1165): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=75 entropy=66
D/wpa_supplicant( 1165): Add randomness: count=76 entropy=67
D/wpa_supplicant( 1165): Add randomness: count=77 entropy=68
D/wpa_supplicant( 1165): Add randomness: count=78 entropy=69
D/wpa_supplicant( 1165): Add randomness: count=79 entropy=70
D/wpa_supplicant( 1165): Add randomness: count=80 entropy=71
D/wpa_supplicant( 1165): Add randomness: count=81 entropy=72
D/wpa_supplicant( 1165): Add randomness: count=82 entropy=73
D/wpa_supplicant( 1165): Add randomness: count=83 entropy=74
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s->,reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1165): 3: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 4: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 6: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 7: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 8: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-78
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1165): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1165): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1165): [NULL] 64:7c:34:38:27:cc freq=2462 level=-89
I/wpa_supplicant( 1165): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1165): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=84 entropy=75
D/wpa_supplicant( 1165): Add randomness: count=85 entropy=76
D/wpa_supplicant( 1165): Add randomness: count=86 entropy=77
D/wpa_supplicant( 1165): Add randomness: count=87 entropy=78
D/wpa_supplicant( 1165): Add randomness: count=88 entropy=79
D/wpa_supplicant( 1165): Add randomness: count=89 entropy=80
D/wpa_supplicant( 1165): Add randomness: count=90 entropy=81
D/wpa_supplicant( 1165): Add randomness: count=91 entropy=82
D/wpa_supplicant( 1165): Add randomness: count=92 entropy=83
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
,D/wpa_supplicant( 1165): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
I/wpa_supplicant( 1165): reply (1211) for get BSS: id=0
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220
I/wpa_supplicant( 1165): level=-47
I/wpa_supplicant( 1165): tsf=0000000184095495
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=1
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-55
I/wpa_supplicant( 1165): tsf=0000000184095535
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=2
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11,
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-80
I/wpa_supplicant( 1165): tsf=0000000166643594
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=3
I/wpa_supplicant( 1165): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1165): freq=2437
I/wpa_supplicant( 1165): level=-78
I/wpa_supplicant( 1165): tsf=0000000184095554
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1165): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1165): freq=2437
I/wpa_supplicant( 1165): level=-85
I/wpa_supplicant( 1165): tsf=0000000184095564
I/wpa_supplicant( 1165): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=UPC Wi-Free
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=5
I/wpa_supplicant( 1165): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1165): freq=2437
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000000184095573
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=UPC5999698
I/wpa_supplicant( 1165): ====
I/wpa_supplica,nt( 1165): id=6
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-55
I/wpa_supplicant( 1165): tsf=0000000184095523
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=7
I/wpa_supplicant( 1165): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1165): freq=2462
I/wpa_supplicant( 1165): level=-90
I/wpa_supplicant( 1165): tsf=0000000184095584
I/wpa_supplicant( 1165): flags=
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 184095495, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 184095535, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 166643594, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -78, frequency: 2437, timestamp: 184095554, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 184095564, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 184095573, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 6: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 184095523, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 7: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 184095584, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 8: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -89, frequency: 2462, timestamp: 184095614, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 9 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  8 [-78], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  4 [-89], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0,
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (9) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(428dabc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(428dabc8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
,I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
,D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1165): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1165): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1165): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-77
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1165): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1165): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1165): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1165): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1165): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=93 entropy=84
D/wpa_supplicant( 1165): Add randomness: count=94 entropy=85
D/wpa_supplicant( 1165): Add randomness: count=95 entropy=86
D/wpa_supplicant( 1165): Add randomness: count=96 entropy=87
D/wpa_supplicant( 1165): Add randomness: count=97 entropy=88
D/wpa_supplicant( 1165): Add randomness: count=98 entropy=89
D/wpa_supplicant( 1165): Add randomness: count=99 entropy=90
D/wpa_supplicant( 1165): Add randomness: count=100 entropy=91
D/wpa_supplicant( 1165): Add randomness: count=101 entropy=92
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): Selecting BSS from priority group 1
I/wpa_supplicant( 1165): Recent assoc_freq = 2412 rssi = -55
D/wpa_supplicant( 1165): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1165): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1165): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1165):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1165):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-55
I/wpa_supplicant( 1165): Start print parameters
I/wpa_supplicant( 1165): wpa_s->wpa_state is 9
I/wpa_supplicant( 1165): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1165): isConcurrentMode() is 0
I/wpa_supplicant( 1165): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1165): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1165): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1165): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1165): wpa_s,->reassociate is 0
I/wpa_supplicant( 1165): wpa_s->is_screen_on 0
I/wpa_supplicant( 1165): wpa_s->ifname wlan0
I/wpa_supplicant( 1165): End print parameters
I/wpa_supplicant( 1165): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1165): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1165): 3: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 4: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 5: 64:7c:34:12:7f:81 ssid='UPC5999698' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 6: 06:7c:34:12:7f:81 ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 7: 06:7c:34:38:27:cc ssid='UPC Wi-Free' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1165): 8: 64:7c:34:38:27:cc ssid='UPC0990019' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1165): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1165): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 1165): nl80211: Survey data missing
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1165): Sorted scan results
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-48
I/wpa_supplicant( 1165): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-55
I/wpa_supplicant( 1165): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-77
I/wpa_supplicant( 1165): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1165): [NULL] 64:7c:34:12:7f:81 freq=2437 level=-84
I/wpa_supplicant( 1165): [NULL] 06:7c:34:12:7f:81 freq=2437 level=-85
I/wpa_supplicant( 1165): [NULL] 06:7c:34:38:27:cc freq=2462 level=-90
I/wpa_supplicant( 1165): [NULL] 64:7c:34:38:27:cc freq=2462 level=-90
D/wpa_supplicant( 1165): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 1165): Add randomness: count=102 entropy=93
D/wpa_supplicant( 1165): Add randomness: count=103 entropy=94
D/wpa_supplicant( 1165): Add randomness: count=104 entropy=95
D/wpa_supplicant( 1165): Add randomness: count=105 entropy=96
D/wpa_supplicant( 1165): Add randomness: count=106 entropy=97
D/wpa_supplicant( 1165): Add randomness: count=107 entropy=98
D/wpa_supplicant( 1165): Add randomness: count=108 entropy=99
D/wpa_supplicant( 1165): Add randomness: count=109 entropy=100
D/wpa_supplicant( 1165): Add randomness: count=110 entropy=101
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: W,FA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[4] 64:7c:34:38:27:cc type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1165): WPS: AP[5] dc:4a:3e:0f:c2:f1 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1165): wpa_supplicant_pick_network+
I/wpa_supplicant( 1165): clear disabled list - type=1
I/wpa_supplicant( 1165): No suitable network found
W/wpa_supplicant( 1165): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1165): State: INACTIVE -> INACTIVE
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WirelessDisplayService(  907): getDiscoveryDongleList
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1165): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1165): reply (1211) for get BSS: id=0
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1165): freq=5220,
I/wpa_supplicant( 1165): level=-48
I/wpa_supplicant( 1165): tsf=0000000184095495
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=NG7005g
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=1
I/wpa_supplicant( 1165): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-55
I/wpa_supplicant( 1165): tsf=0000000201557775
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS][ESS],
I/wpa_supplicant( 1165): ssid=NG700
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=2
I/wpa_supplicant( 1165): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-80
I/wpa_supplicant( 1165): tsf=0000000201557795
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=Gonzos
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=3
I/wpa_supplicant( 1165): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1165): freq=2437
,I/wpa_supplicant( 1165): level=-77
I/wpa_supplicant( 1165): tsf=0000000201557812
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1165): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=4
I/wpa_supplicant( 1165): bssid=06:7c:34:12:7f:81
I/wpa_supplicant( 1165): freq=2437
I/wpa_supplicant( 1165): level=-85
I/wpa_supplicant( 1165): tsf=0000000201557832
I/wpa_supplicant( 1165): flags=[WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS]
I/wpa_supplicant( 1165): ssid=UPC Wi-Free
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=5
,I/wpa_supplicant( 1165): bssid=64:7c:34:12:7f:81
I/wpa_supplicant( 1165): freq=2437
I/wpa_supplicant( 1165): level=-84
I/wpa_supplicant( 1165): tsf=0000000201557850
I/wpa_supplicant( 1165): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS]
I/wpa_supplicant( 1165): ssid=UPC5999698
I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=6
I/wpa_supplicant( 1165): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1165): freq=2412
I/wpa_supplicant( 1165): level=-55
I/wpa_supplicant( 1165): tsf=0000000201557754
I/wpa_supplicant( 1165): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1165): ssid=01ABC
,I/wpa_supplicant( 1165): ====
I/wpa_supplicant( 1165): id=7
I/wpa_supplicant( 1165): bssid=06:7c:34:38:27:cc
I/wpa_supplicant( 1165): freq=2462
I/wpa_supplicant( 1165): level=-90
I/wpa_supplicant( 1165): tsf=0000000201557870
I/wpa_supplicant( 1165): flags=
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -48, frequency: 5220, timestamp: 184095495, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -55, frequency: 2412, timestamp: 201557775, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 201557795, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -77, frequency: 2437, timestamp: 201557812, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:12:7f:81, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -85, frequency: 2437, timestamp: 201557832, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 5: scan result = SSID: UPC5999698, BSSID: 64:7c:34:12:7f:81, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -84, frequency: 2437, timestamp: 201557850, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 6: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -55, frequency: 2412, timestamp: 201557754, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 7: scan result = SSID: UPC Wi-Free, BSSID: 06:7c:34:38:27:cc, capabilities: [WPA-EAP-CCMP+TKIP][WPA2-EAP-CCMP+TKIP][ESS], level: -90, frequency: 2462, timestamp: 201557870, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 8: scan result = SSID: UPC0990019, BSSID: 64:7c:34:38:27:cc, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][WPS][ESS], level: -90, frequency: 2462, timestamp: 201557889, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 9 to mScanResults
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -55, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-48], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-55], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  8 [-77], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                       UPC5999698 [64:7c:34:12:7f:81], Rssi:  6 [-84], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                      UPC Wi-Free [06:7c:34:12:7f:81], Rssi:  4 [-85], Tx: 13, Freq:  6 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  71, AP:                      UPC Wi-Free [06:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  71, AP:                       UPC0990019 [64:7c:34:38:27:cc], Rssi:  0 [-90], Tx: 13, Freq:  8 [2462], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (9) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,TIME-OUT KILL (timeout was 150000ms),E/cutils-trace( 4510): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4510): ====startRecUseTime====
D/htc.customization.log.level( 4510):  is 
W/CustomizationLogLevel( 4510): Level value is invalid, use default level 2
D/CustomizationManager( 4510):  Read ACC file spent 0.101 (s)
D/CIDMapFileReader( 4510): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4510): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4510): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4510): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4510): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4510): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4510): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4510): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4510): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4510): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4510): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4510): Parsing tag category name = system
I/CustomizationCIDLoader( 4510): Parsing tag category name = application
I/CustomizationCIDLoader( 4510): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4510): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4510): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4510): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4510): Parsing tag category name = Settings
D/CustomizationManager( 4510):  Read CID file spent 0.152 (s)
D/CustomizationManager( 4510):  All configurations done spent 0.152 (s)
W/HtcNativeFlag( 4510): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4510): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4510): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4510): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  907): deletePackageAsUser: pkg=com.example.hello, pid=4510, uid=2000 user=0
W/asset   (  907): Copying FileAsset 0x6c298ff0 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/ActivityManager(  907): Force stopping com.example.hello appid=10356 user=-1: uninstall pkg
W/PackageSettings(  907): Skipping PackageSetting{421d5b58 com.test.thalitest/10348} due to missing metadata
I/ActivityManager(  907): Force stopping com.example.hello appid=10356 user=0: pkg removed
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1271): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1565): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1565): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1565): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/acms    ( 1883): Unregistering com.example.hello
E/acms    ( 1883): Could not unregister removed application com.example.hello
W/AccTypeManager( 1331): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1331): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Launcher( 1271): Deferring update until onResume
D/Launcher( 1271): waitUntilResume // bindAppsRemoved
W/GeofencerStateMachine( 1449): Ignoring removeGeofence because network location is disabled.
D/PMS     (  907): acquireWL(427e2aa0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1449 10028 null
D/VoicemailCleanupService( 1298): Cleaning up data for package: com.example.hello
D/PMS     (  907): releaseWL(427e2aa0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
D/AccTypeManager( 1331): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
D/PackageBroadcastService( 1225): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/ActivityManager(  907): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4524 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
E/ExternalAccountType( 1331): Unsupported attribute readOnly
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/MultiDex( 4524): install
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/ActivityManager(  907): Delaying start of: ServiceRecord{42674f00 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/MultiDex( 4524): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/MultiDex( 4524): loading existing secondary dex files
I/MultiDex( 4524): load found 1 secondary dex files
I/MultiDex( 4524): install done
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
D/PhoneApp( 1245): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/PeopleContactsSync( 1225): CP2 sync disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1225, uid=10028, userID:0
I/ActivityManager(  907): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4543 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/Icing   ( 1225): doRemovePackageData com.example.hello
D/PMS     (  907): acquireWL(425c7e50): PARTIAL_WAKE_LOCK  Icing 0x1 1225 10028 null
I/ProviderInstaller( 4524): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/PMS     (  907): releaseWL(425c7e50): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  907): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4543): install
I/MultiDex( 4543): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4543): loading existing secondary dex files
I/MultiDex( 4543): load found 1 secondary dex files
I/MultiDex( 4543): install done
E/SQLiteDatabase( 1225): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1225): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1225): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1225): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1225): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1225): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 1225): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 1225): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 1225): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 1225): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 1225): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1225): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1225): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1225): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ClearPendingStateOp( 1225): Runtime exception while performing operation
E/ClearPendingStateOp( 1225): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 1225): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 1225): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 1225): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 1225): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 1225): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 1225): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 1225): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 1225): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 1225): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 1225): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 1225): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/ClearPendingStateOp( 1225): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1225): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 1225): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 1225): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 1225): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 1225): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 1225): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 1225): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 1225): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 1225): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 1225): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 1225): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 1225): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 1225): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ProviderInstaller( 4543): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  907): Resuming delayed broadcast
E/SharedPreferencesImpl( 1210): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
E/DropBoxManagerService(  907): Can't write: system_app_wtf
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
I/[PluginManager]RegisterService( 1396): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.example.hello
E/SQLiteLog( 1396): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1396): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5c8af010
W/[PluginManager]RegisterService( 1396): provider may killed!
W/[PluginManager]RegisterService( 1396): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1396): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1396): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1396): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1396): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1396): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1396): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1396): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1396): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1396): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1396): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1396): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1396): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1396): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1396): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 1396): handle notify Blinkfeed plugin client changed
D/Process (  907): killProcessQuiet, pid=4296
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4296:com.google.android.talk/u0a111 (adj 15): empty #17
D/Prism.PackageStateRece_( 1271): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2907): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4564 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4524): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4524): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4524): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4524): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4524): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4524): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4524): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4524): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4524): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4524): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4524): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4524): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4524): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4524): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4524): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4524): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4524): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4524): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4524): threadid=12: thread exiting with uncaught exception (group=0x41695e30)
E/ActivityManager(  907): App crashed! Process: com.google.android.gms.drive
E/AndroidRuntime( 4524): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4524): Process: com.google.android.gms.drive, PID: 4524
E/AndroidRuntime( 4524): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4524): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4524): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4524): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4524): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4524): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4524): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4524): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4524): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4524): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4524): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4524): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4524): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4524): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4524): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4524): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4524): 	at ctn.run(SourceFile:985)
D/Process ( 4524): killProcess, pid=4524
D/Process ( 4524): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
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
E/SQLiteLog( 2907): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2907): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63cc0cd0
W/dalvikvm( 2907): threadid=16: thread exiting with uncaught exception (group=0x41695e30)
E/ActivityManager(  907): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2907): killProcess, pid=2907
E/AndroidRuntime( 2907): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2907): Process: com.google.android.googlequicksearchbox:search, PID: 2907
E/AndroidRuntime( 2907): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2907): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2907): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2907): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2907): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2907): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2907): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2907): 	at cid.d(PG:186)
E/AndroidRuntime( 2907): 	at clo.g(PG:594)
E/AndroidRuntime( 2907): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2907): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2907): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2907): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2907): 	at clr.tL(PG:827)
E/AndroidRuntime( 2907): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2907): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2907): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2907): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2907): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2907): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
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
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4296
W/PackageManager(  907): Unable to load service info ResolveInfo{423987f8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/ActivityManager(  907): Recipient 4524
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.android.gms.drive (pid 4524) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 1000ms
I/wpa_supplicant( 1165): wpa_supplicant_scan enter
I/wpa_supplicant( 1165): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1165): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1165): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1165): nl80211: Event message available
D/wpa_supplicant( 1165): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
I/ActivityManager(  907): Recipient 2907
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.android.googlequicksearchbox:search (pid 2907) has died.
D/MediaRouterService(  907): Client com.google.android.googlequicksearchbox (pid 2907): Died!
D/WifiService(  907): Client connection lost with reason: 4
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start
W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
E/SQLiteDatabase( 4564): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4564): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4564): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4564): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4564): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4564): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4564): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4564): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4564): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4564): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4564): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4564): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4564): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4564): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4564): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4564): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4564): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4564): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4564): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4564): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4564): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4564): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4564): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4564): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4564): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4564): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4564): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4564): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4564): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4564): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4564): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4564): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4564): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4564): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4564): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4564): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4564): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4564): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4564): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4564): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4564): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4564): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4564): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4564): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4564): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4564): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4564): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4564): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4564): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4564): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4564): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4564): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4564): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4564): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4564): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4564): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4564): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4564): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4564): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4564): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4564): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4564): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4564): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4564): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4564): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4564): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4564): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4564): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4564): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4564): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4564): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4564): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4564): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4564): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4564): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4564): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4564): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4564): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4564): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4564): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4564): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4564): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4564): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4564): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4564): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4564): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4564): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4564): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4564): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4564): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4564): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4564): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4564): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4564): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4564): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4564): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4564): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4564): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4564): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4564): threadid=11: thread exiting with uncaught exception (group=0x41695e30)
E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4564): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4564): Process: com.google.android.apps.docs, PID: 4564
E/AndroidRuntime( 4564): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4564): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4564): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4564): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4564): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4564): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4564): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4564): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4564): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4564): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4564): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4564): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4564): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4564): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4564): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4564): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4564): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4564): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4564): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 4564): killProcess, pid=4564
D/Process ( 4564): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4582 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  907): Recipient 4564
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  907): killProcessQuiet, pid=4197
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4197:com.htc.sense.mms/u0a64 (adj 15): empty #17
I/ActivityManager(  907): Process com.google.android.apps.docs (pid 4564) has died.
I/ActivityManager(  907): Recipient 4197
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ContextImpl( 4582): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4582): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4582): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4582): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4582): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4582): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4582): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4582): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4582): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4582): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4582): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4582): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4582): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4582): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4582): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4582): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4582): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4582): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4582): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4582): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4582): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4582): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4582): threadid=10: thread exiting with uncaught exception (group=0x41695e30)
E/AndroidRuntime( 4582): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4582): Process: com.android.keychain, PID: 4582
E/AndroidRuntime( 4582): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4582): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4582): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4582): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4582): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4582): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4582): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4582): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4582): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4582): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4582): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4582): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4582): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4582): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4582): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4582): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4582): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4582): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4582): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4582): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  907): App crashed! Process: com.android.keychain
I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4595 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4582): killProcess, pid=4582
D/Process ( 4582): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452261216151.dbox_tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  907): Recipient 4582
I/ActivityManager(  907): Process com.android.keychain (pid 4582) has died.
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10643ms
D/AppTag  ( 4595): getInstance(Context context)
D/AppTag  ( 4595): getInstance(Context context)
D/AppTag  ( 4595): onCreate()
D/PMS     (  907): acquireWL(4279fba0): PARTIAL_WAKE_LOCK  AsyncService 0x1 3637 10160 null
D/PMS     (  907): releaseWL(4279fba0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4613 uid=10098 gids={50098, 3003, 5012}
I/DeviceManagement( 4613): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4613 dbg=false s=true
I/DeviceManagement( 4613): PackageUpdateReceiver: vvv Package removed: [com.example.hello]
I/DeviceManagement( 4613): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.example.hello, operation=3}]]
I/DeviceManagement( 4613): WorkflowService: Starting workflow service
I/DeviceManagement( 4613): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41af3e18] args=[Bundle[mParcelledData.dataSize=116]]
I/DeviceManagement( 4613): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4613): PackageUpdateWorkflow: Package update: package=com.example.hello, operation=REMOVE
I/DeviceManagement( 4613): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4613): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  907): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4627 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 4613): BackgroundController: *** Processing package remove for appID=com.example.hello
I/DeviceManagement( 4613): SessionStateController: Checking invariants...
D/Documents( 4627): Loading roots for com.android.providers.downloads.documents
D/Documents( 4627): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 4627): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4627): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4627): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4627): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4627): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4627): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4627): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4627): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4627): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4627): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4627): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4627): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4627): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4627): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4627): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4627): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4627): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4627): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4627): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4627): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4627): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4627): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4627): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4627): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4627): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4627): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4627): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4627): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4627): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4627): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4627): 	at dalvik.system.NativeStart.main(Native Method)

```
