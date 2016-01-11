#### Test 5563415007e42e9_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
D/CountryDetector(  856): The first listener is added
E/ActivityThread( 3185): Failed to find provider info for com.lge.ims.provider.uc
--------- beginning of main
I/LOG_TAG ( 3185): registerContactDBChangeObserver
D/LocationManagerService(  856): getProviders()=[passive]
D/LocationManagerService(  856): request 2317a9ea passive Request[POWER_NONE passive fastest=0] from android(1000)
D/LocationManagerService(  856): provider request: passive ProviderRequest[ON interval=0]
I/MmsApp  ( 3185): handleBootCompleted
V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.SIM_STATE_CHANGED flg=0x20000010 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): [LGE Remove Code] INTENT_VALUE_ICC_ABSENT received
I/SmsReceiverService( 3185): smsBootCompleted
V/LGMediaProvider( 3206): Attached volume: external
I/ActivityManager(  856): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=3262 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
V/DownloadManager( 3206): DownloadService onCreate
,I/DownloadManager( 3206): in removeSpuriousFiles
I/NotificationManager( 3206): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3206): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3206): created cursor android.database.sqlite.SQLiteCursor@e4446b6 on behalf of 3206
V/DownloadManager( 3206): DownloadService onStartCommand
V/DownloadManager( 3206): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3206): created cursor android.database.sqlite.SQLiteCursor@4461842 on behalf of 3206
I/DownloadManager( 3206): in trimDatabase
V/DownloadManager( 3206): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3206): created cursor android.database.sqlite.SQLiteCursor@3248a053 on behalf of 3206
D/SwitchedService( 3185): Mms SwitchedService ACTION_USER_SWITCHED registerReceiver
D/MmsConfig( 3185): MediaScanner - scannerConnected
W/ResourcesManager( 3262): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3262): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 3262): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 3262): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 3262): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/MmsSystemEventReceiver( 3185): mmsBootComplete
V/DownloadManager( 3206): DownloadService onDestroy
W/ResourcesManager( 3185): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/MmsConfig( 3185): getUserModeNotAllowedSms:sUserModeNotAllowedSms:false
D/MmsConfig( 3185): isNotAllowedSms: currentUser:0
D/MmsConfig( 3185): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3185): isUserMode:false
I/IndexDatabaseHelper( 3262): Using schema version: 115
I/IndexDatabaseHelper( 3262): Index is fine
V/LEDService( 1883): stopInternal(), pkg=com.android.mms, id=123
D/MessagingNotification( 3185): disalbleEmotionalLED id= 123
I/NotificationManager( 3185): com.android.mms: cancel(123) by com.android.mms
V/LEDService( 1883): stopInternal(), pkg=com.android.mms, id=946
D/MessagingNotification( 3185): disalbleEmotionalLED id= 946
I/NotificationManager( 3185): com.android.mms: cancel(946) by com.android.mms
D/MessagingNotification( 3185): unread_count:0, thread_count:0, thread_id:-100
D/MessagingNotification( 3185): toLockscreenWithUnreadMsgCnt - count = 0
D/QuickCoverActivity( 3185): lockscreensettings ret = true
I/MessagingNotification( 3185): repeat count :0
D/KeyguardModel( 1390): mReceiver, received action: lge.intent.action.UNREAD_MESSAGES, sendingUserId:0
D/SmartCoverUpdateMonitor( 1348): received broadcast lge.intent.action.UNREAD_MESSAGES
I/NfcP2pLinkManager( 1859): LLCP deactivated.
I/NfcP2pLinkManager( 1859): Duplicate onLlcpDectivated()
D/KeyguardModel( 1390): putNotificationIntoList Number: 0 Id: 1 UserId: 0
V/WifiInternetCheck(  856): Single check msg out of sync, ignoring.
I/QuickCircle( 1348): onReceive :Intent { act=lge.intent.action.UNREAD_MESSAGES flg=0x10 (has extras) }, sComponents:[com.coremobility.app.vnotes.CM_VnoteInbox, com.android.contacts.activities.DialtactsActivity, com.android.contacts.DialtactsRecentCallsEntryActivity, com.lge.vvm.authmanager.VvmAuthManagerActivity, com.lge.email.ui.setupwizard.Welcome, com.skt.prod.dialer.activities.main.MainActivity, com.android.mms.ui.ConversationList, com.lge.message.ui.ConversationList, com.lge.message.activity.MainMenuActivity, com.skt.skaf.A000Z00040.A000Z00040, com.lge.updatecenter.UpdateCenterPrfActivity]
D/SmartCoverUpdateMonitor( 1348): MSG_BIGNOTI_XXX
D/ConnectivityService(  856): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  856): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  856): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/[SystemUI]QuickSettingsHandler( 1390): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/libc-netbsd(  856): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  856): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  856): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  856): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/LocSvc_java(  856): onReceive
D/LocSvc_java(  856): got connectivity action
D/libc-netbsd(  856): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  856): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  856): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  856): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/LocSvc_java(  856): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  856): Sending msg: 4 arg1:1 arg2:1
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/LocSvc_java(  856): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  856): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  856): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  856): Sending msg: 5 arg1:0 arg2:1
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  856): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  856): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  856): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  856): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
E/GpsLocationProvider(  856): No APN found to select.
D/AndroidRuntime( 3284): 
D/AndroidRuntime( 3284): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out(  856): propertyValue:false
I/System.out(  856): propertyValue:false
V/WiFiOffLoadBroadcast( 3262): WiFiOffLoadBroadcast: android.intent.action.SIM_STATE_CHANGED
D/AndroidRuntime( 3284): CheckJNI is OFF
I/System.out(  856): propertyValue:false
V/WiFiOffLoadBroadcast( 3262): Sim absent, removing wifis
D/LgeGpsConstants(  856): Can't find 'ext_gps.conf'!!
D/libc-netbsd(  856): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  856): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  856): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  856): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/LocSvc_java(  856): NTP server returned: 1452527787970 (Mon Jan 11 16:56:27 GMT+01:00 2016) reference: 42972 certainty: 18 system time offset: 581
D/LocSvc_java(  856): Sending msg: 10 arg1:0 arg2:1
D/AlarmManagerService(  856): Setting time of day to sec=1452527787
W/AlarmManagerService(  856): Unable to set rtc to 1452527787: Invalid argument
W/ActivityManager(  856): getTasks: caller 10024 is using old GET_TASKS but privileged; allowing
I/[SystemUI]Clock( 1390): onReceive = android.intent.action.TIME_SET
I/LgeClockWidgetControlView( 1390): time changed, timezoneChanged : false
D/WeatherService( 2715): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 16:56:27
D/WeatherService( 2715): 2 : requestRefreshAppWidget, isUpdateStart : false
I/[LGHome]LGDateChangeReceiver( 1966): [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=11 currentDate=-1 dayofweek=2 currentDayOfWeek=-1
I/[LGHome]LGCalendarIcon( 1966): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Mon date= 11
D/UpdateThreadPoolManager( 2715): 2 : This is isUpdating : false
D/WeatherService( 2715): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2715): 2 : buildUpdate, appWidgetId: 2
D/KeyguardUpdateMonitor( 1390): handleTimeUpdate
I/[LGHome]LGCalendarIcon( 1966): [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Mon date= 11
D/WiFiOffLoadUpdatePriority( 3262): remove : truetruetrue
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
D/WeatherTheme( 2715): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
I/System.out(  856): propertyValue:false
D/WeatherTheme( 2715): 2 : Fixed theme : optimus
D/WeatherReflect( 2715): 2 : Map key string is -2
D/lim     ( 2715): 2 : time = 16:56
I/WeatherReflect( 2715): Model Name : LG-D722
D/WeatherTheme( 2715): 2 : exactly same view!
D/WeatherTheme( 2715): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
D/WeatherService( 2715): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 16:56:28
I/ActivityManager(  856): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=3308 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
D/WiFiOffLoadUpdatePriority( 3262): remove1
V/WiFiOffLoadSharedPrefsUtils( 3262): save remove
D/LgeGpsLocationProvider(  856): NTP server: europe.pool.ntp.org
D/LgeGpsLocationProvider(  856): NTP server returned: 1452527788065 (Mon Jan 11 16:56:28 GMT+01:00 2016) reference: 43068 certainty: 30 system time offset: 1
D/UsbSettingsReceiver( 3262): [AUTORUN] onReceive() : action = android.intent.action.SIM_STATE_CHANGED
D/UsbSettingsReceiver( 3262): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 3262): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 3262): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 3262): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/ActivityManager(  856): enqueue in BackgroundQueue #66 Intent=Intent { act=com.lge.qremote.action.wait_loading flg=0x14 cmp=com.lge.qremote/.appwidget.RemoteAppWidgetProvider (has extras) }
D/UsbSettingsReceiver( 3262): android.intent.action.SIM_STATE_CHANGED
D/UsbSettingsReceiver( 3262): Target OperatorOPEN
D/UsbSettingsReceiver( 3262): Target CountryEU
D/UsbSettingsReceiver( 3262): stateExtraABSENT
D/UsbSettingsReceiver( 3262): INTENT_VALUE_ICC_IMSIIMSI
D/StoreModeReceiver( 3262): intent.getAction() : android.intent.action.SIM_STATE_CHANGED
D/StoreModeReceiver( 3262): sim state :ABSENT
D/StoreModeReceiver( 3262): Back LED don't supported.
D/AndroidRuntime( 3284): Calling main entry com.android.commands.am.Am
I/ActivityManager(  856): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ALBootInit( 3308): ====action==>android.intent.action.TIME_SET
D/ALBootInit( 3308): Alarm ALBootInit: TIME_SET
D/Alarms  ( 3308): [setNextAlert] start
D/ActivityManager(  856): setTaskToReturnTo : TaskRecord{24805190 #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  856): setTaskToReturnTo : TaskRecord{24805190 #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  856): AppWindowTokenEx init.. 
D/ContextHelper(  856): convertTheme. context->name=com.example.hello themeResourceId=16973833
D/InputDispatcher(  856): Focus left window: Window{17bfa701 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[LGHome]EVENT( 1966): [Launcher.java:986:onPause()]onPause
D/AndroidRuntime( 3284): Shutting down VM
D/SplitWindow(  856): check instance of lgWin Window{2666619a u0 Starting com.example.hello}
D/Alarms  ( 3308): [setNextAlert] (1)
D/Alarms  ( 3308):  minTime  = 0
D/Alarms  ( 3308):  -- OK multi -- 0
E/jeny.kim( 3308): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 3308): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/ActivityManager(  856): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3331 uid=10317 gids={50317, 9997, 3003} abi=armeabi-v7a
I/[LGHome]EVENT( 1966): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 2054): Closing mic
I/MicrophoneInputStream( 2054): mic_close com.google.android.apps.gsa.speech.audio.u@1912f737
V/AudioRecord( 2054): stop()
D/AudioRecord( 2054): AudioRecord->stop()
V/AudioFlinger(  284): RecordHandle::stop()
V/AudioFlinger(  284): RecordThread::stop
V/AudioFlinger(  284): Record stopped OK
V/AudioPolicyManager(  284): stopInput() input 17
V/AudioPolicyService(  284): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  284): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  284): AudioCommandThread() waking up
V/AudioPolicyService(  284): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  284): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  284): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  284): ThreadBase::setParameters() routing=0
V/AudioFlinger(  284): sendConfigEvent_l() num events 1 event 2
I/CommonUtil( 3308): BUILD Operator: OPEN
V/AudioFlinger(  284): processConfigEvents_l() remaining events 1
V/AudioFlinger(  284): processConfigEvents_l() DONE thread 0xb4127000
D/audio_hw_primary(  284): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
D/Alarms  ( 3308): broadcastToWidgetProvider : false
I/art     (  856): Explicit concurrent mark sweep GC freed 36567(1835KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 3.566ms total 186.747ms
D/Alarms  ( 3308): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/SettingsProvider(  856): call_put(system:emotional_led_back_led=0) for 0 calling package = com.android.settings
V/SettingsProvider(  856): call_put(system:emotional_led_back_incoming_call=0) for 0 calling package = com.android.settings
V/SettingsProvider(  856): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
V/audio_hw_primary(  284): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  284): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  284): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  284): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  284): disable_audio_route: exit
E/audio_hw_primary(  284): disable_snd_device: enter 144
D/hardware_info(  284): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  284): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/SettingsProvider(  856): call_put(system:emotional_led_back_alarm=0) for 0 calling package = com.android.settings
V/audio_hw_primary(  284): stop_input_stream: exit: status(0)
V/audio_hw_primary(  284): in_standby: exit:  status(0)
V/AudioFlinger(  284): RecordThread: loop stopping
I/SearchBackgroundTaskFac( 2054): refreshing internal icing corpora
V/AudioPolicyService(  284): AudioCommandThread() going to sleep
V/AudioPolicyManager(  284): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  284): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  284): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  284): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  284): AudioCommandThread() waking up
V/AudioPolicyService(  284): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  284): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  284): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  284): AudioCommandThread() going to sleep
V/AudioPolicyService(  284): AudioCommandThread() waking up
V/AudioPolicyService(  284): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  284): setParameters(): io 17, keyvalue hotword_active=0, calling pid 284
V/AudioFlinger(  284): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  284): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  284): RecordThread: loop starting
V/AudioFlinger(  284): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  284): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  284): in_set_parameters: exit: status(0)
V/AudioFlinger(  284): processConfigEvents_l() DONE thread 0xb4127000
V/AudioFlinger(  284): RecordThread: loop stopping
V/AudioPolicyService(  284): AudioCommandThread() going to sleep
V/AudioRecord( 2054): stop()
V/AudioRecord( 2054): stop()
V/AudioRecord( 2054): stop()
V/AudioFlinger(  284): RecordHandle::stop()
V/AudioFlinger(  284): releasing 16 from 2054 for -1
V/AudioFlinger(  284):  decremented refcount to 0
V/AudioFlinger(  284): purging stale effects
W/BackupManagerService(  856): dataChanged but no participant pkg='com.android.providers.settings' uid=10010
I/HotwordRecognitionRnr( 2054): Stopping hotword detection.
V/AudioFlinger(  284): RecordThread::stop
V/AudioPolicyManager(  284): releaseInput() 17
V/AudioPolicyManager(  284): closeInput(17)
V/AudioFlinger(  284): closeInput() 17
V/AudioSystem(  284): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2730): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  284): ThreadBase::exit
V/AudioSystem( 2054): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  284): RecordThread: loop starting
V/AudioSystem(  856): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1390): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1795): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3185): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  284): RecordThread 0xb4127000 exiting
I/DigitalAppWidgetProvider( 3308): onReceive: android.intent.action.TIME_SET
D/audio_hw_primary(  284): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  284): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  284): in_standby: exit:  status(0)
V/AudioPolicyService(  284): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  284): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  284): AudioCommandThread() waking up
V/AudioPolicyService(  284): AudioCommandThread() processing update audio port list
V/AudioPolicyManager(  284): releaseInput() exit
V/AudioFlinger(  284): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  284): removeClient_l() pid 2054, calling pid 284
V/AudioPolicyService(  284): AudioCommandThread() going to sleep
I/HotwordRecognitionRnr( 2054): Hotword detection finished
V/DigitalAppWidgetProvider( 3308): cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@35cf39d5
I/[LGHome]EVENT( 1966): [Launcher.java:5214:onStop()]onStop
V/DigitalAppWidgetProvider( 3308): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@35cf39d5
V/SettingsProvider(  856): call_put(system:emotional_led_back_missed_call=0) for 0 calling package = com.android.settings
I/WindowStateAnimator(  856): Starting window displayed
I/SystemUI[Framework](  856): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
D/PhoneStatusBar( 1390): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  856): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  856): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  856): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  856): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@215eb15c,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  856): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1390): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1390):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1390): , Keyguard show=false, IME shown=false, Panel expanded=false
V/SettingsProvider(  856): call_put(system:emotional_led_back_missed_messages=0) for 0 calling package = com.android.settings
D/QuickCoverProvider( 3308): onReceiver
,V/SettingsProvider(  856): call_put(system:emotional_led_back_missed_emails=0) for 0 calling package = com.android.settings
D/MessagingNotification( 3185): observerLED
D/BarTransitions( 1390): draw background and invalidate : color = 1d000000
D/BarTransitions( 1390): draw background and invalidate : color = 1f1e1e1e
V/SettingsProvider(  856): call_put(system:emotional_led_back_calendar_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  856): call_put(system:emotional_led_back_voice_recording=0) for 0 calling package = com.android.settings
D/MessagingNotification( 3185): observerLED LED ON
I/ActivityManager(  856): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=3352 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  856): Killing 2878:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
V/SettingsProvider(  856): call_put(system:emotional_led_back_camera_timer_noti=0) for 0 calling package = com.android.settings
D/MmsConfig( 3185): getUserModeNotAllowedSms:sUserModeNotAllowedSms:false
V/SettingsProvider(  856): call_put(system:emotional_led_back_camera_face_detecting_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  856): call_put(system:notification_light_pulse_back=0) for 0 calling package = com.android.settings
I/LEDService( 1883): getCurrentHighestLGLedRecord() start. size = 1
V/LEDService( 1883): startInternal : pkg=batteryinfo, recordId=0 : LGLedRecord{3b55a108 flags=0 patternId=0 color=0 priority=-1 recordId=0 pkg=batteryinfo infinite=true mExceptional=false mNativeNotification=false whichLedPlay=1 patternFilePath=null}
I/LEDService( 1883): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1883): set_light_notifications: 0,0,0,0,3
I/LEDService( 1883): updateLightsLocked : turn off led
D/qdlights( 1883): set_light_notifications: 0,0,0,0,3
W/libprocessgroup(  856): failed to open /acct/uid_10069/pid_2878/cgroup.procs: No such file or directory
D/MmsConfig( 3185): isNotAllowedSms: currentUser:0
D/MmsConfig( 3185): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3185): isUserMode:false
D/MessagingNotification( 3185): unreadMessageHandler
D/ContextHelper( 3331): convertTheme. context->name=com.example.hello themeResourceId=16973833
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
D/StoreModeReceiver( 3262): SystemProperty Default brightness value [0-255] : 143
D/StoreModeReceiver( 3262): Default brightness[0-255] : 143
W/ResourcesManager( 3262): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 3352): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/StoreModeReceiver( 3262): Default Screen off timeout value : 30000
D/StoreModeReceiver( 3262): SystemProperty Default brightness Mode value[true/false] : false
D/StoreModeReceiver( 3262): BRIGHTNESS_MODE - 0
D/StoreModeReceiver( 3262): Default brightness Mode [0/1] : 0
D/StoreModeReceiver( 3262): Default NIGHT_MODE : 0
D/StoreModeReceiver( 3262): Set MaxBrightness : 255
E/PhoneInterfaceManager( 1795): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/StoreModeReceiver( 3262): getPhoneNumber is empty
I/UpdateIcingCorporaServi( 2054): Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
D/SettingBootReceiver( 3262): onReceive
D/SettingBootReceiver( 3262): [Extra] : ABSENT == 'LOADED' ??
I/DualIMSIApnProfileReceiver( 3262): intentName == android.intent.action.SIM_STATE_CHANGED
I/DualIMSIApnProfileReceiver( 3262): IMSI not available :: return 
I/ActivityManager(  856): Killing 2565:com.lge.qremote/u0a106 (adj 15): empty #11
I/WebViewFactory( 3331): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
E/LGDMClient( 3102): [DmServiceProcessor.java] [isNeededToRegenerate()] : [195] : SIM information is not readed right. so reconfig is needed regardless SIM serial number
W/libprocessgroup(  856): failed to open /acct/uid_10106/pid_2565/cgroup.procs: No such file or directory
I/LGDMClient( 3102): [DmCAConfigParser.java] [getInstance()] : [73] : DmsCAConfigParser sInstance null
D/CalendarApplication( 3352): CalendarApplication.onCreate()
D/PreferenceKeysParser( 3352): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 3352): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@3e1c7c60, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@32466519, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@251cd9de, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@375e97bf, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@23cfe8c, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@35cf39d5, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@1c98b5ea, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@116ef0db, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@1e017778, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@17d69e51, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@e4446b6, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@761bfb7, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@2b929324, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@2815ce8d, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@4461842, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@3248a053, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@1cf7bd90, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@3e9dc689, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@12a1768e, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@20b2eeaf, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@3b4322bc, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@9934245, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@38426d9a, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@10c9c6cb, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@2c7daea8, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3aaabdc1, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@4c9c966, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@302c04a7, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@2c530d54, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@106474fd, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@f1915f2, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@3d8a4443, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@237daac0, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@370863f9, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@89e9f3e, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@2802e19f, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@9f2b2ec, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@3d6246b5, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3961714a, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@83df8bb, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@3fce11d8, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@193d9931
D/GeneralPreferenceUtils( 3352): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 3352): [init]
D/LGDMClient( 3102): [DmPhoneSpecificInfo.java] [getPhoneSpecificInfo()] : [204] : Current MultiSimEnabled is false
I/Config  ( 3352): LGCalendar ver.4.40.17
I/Config  ( 3352): start check model
I/Config  ( 3352): start check native_ca
I/Config  ( 3352): Config Operator=OPEN, Country=EU
D/Config  ( 3352): [setDefaultValuesToPref]
D/Config  ( 3352): [parseProfiles]
D/ProfilesParser( 3352): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 3352): [debug_displayParseInfos] profile.operator = null
D/Config  ( 3352): [updateProfiletoCountryInfo]
D/GeneralPreference( 3352): [checkAndMigrateOldPreference]
I/LibraryLoader( 3331): Time to load native libraries: 2 ms (timestamps 3746-3748)
I/LibraryLoader( 3331): Expected native library version number "",actual native library version number ""
I/ActivityManager(  856): Start proc com.android.contacts for broadcast com.android.contacts/com.lge.contacts.sim.SimPhonebookStateReceiver: pid=3378 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/QCNEJ   ( 1929): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/QCNEJ   ( 1929): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:56:28.77 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/LGDMClient( 3102): [DmPhoneSpecificInfo.java] [getPhoneSpecificInfo()] : [239] : getPhoneSpecificInfo: sim mccmnc(),spn(),gid(null),imsi(null)
V/WebViewChromiumFactoryProvider( 3331): Binding Chromium to main looper Looper (main, tid 1) {375e97bf}
I/LibraryLoader( 3331): Expected native library version number "",actual native library version number ""
E/AgendaWidgetManager( 3352): [updateWidgets] 
I/chromium( 3331): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/LGDMClient( 3102): [DmCAConfigParser.java] [parse()] : [108] : parse
D/LGDMClient( 3102): [DmCAConfigParser.java] [setDefaultProfile()] : [490] : setDefaultProfile
D/LGDMClient( 3102): [DmCAConfigParser.java] [setDefaultProfile()] : [493] : filename : fota_dm_settings.xml
D/LGDMClient( 3102): [DmCAConfigParser.java] [setDefaultProfile()] : [506] : [UI4.1] Search [fota_dm_settings.xml]
I/BrowserStartupController( 3331): Initializing chromium process, singleProcess=true
W/art     ( 3331): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3331): ApplicationContext is null in ApplicationStatus
D/LGDMClient( 3102): [DmCAConfigParser.java] [parse()] : [134] : [UI4.1] Search [fota_dm_settings.xml]
W/chromium( 3331): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 3331): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3331): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3331): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3331): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 3331): Build Date: 03/02/15 Mon
I/Adreno-EGL( 3331): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 3331): Remote Branch: 
I/Adreno-EGL( 3331): Local Patches: 
I/Adreno-EGL( 3331): Reconstruct Branch: 
W/ResourcesManager( 3378): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3378): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 3378): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 3378): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 3378): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  856): Killing 2911:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
V/AudioPolicyService(  284): registerClient() client 0xb551c800, uid 10317
W/AudioManagerAndroid( 3331): Requires BLUETOOTH permission
I/InitNotificationRingtoneService( 3352): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3352): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
D/libc-netbsd(  856): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  856): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  856): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  856): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
W/HolidayIntentService( 3352): onHandleIntent
D/MonthWidgetProvider( 3352): [onReceive]
D/CalendarWidgetProvider( 3352): [onReceive]
D/HolidayDataLoader( 3352): readJsonAsset : holiday.json
D/CalendarWidgetProvider( 3352): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 3352): [onUpdateAndInitCalendarTime]
W/ResourcesManager( 2054): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/HolidayIntentService( 3352): onHandleIntent:holiday data empty
,W/ResourcesManager( 2054): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out(  856): propertyValue:false
,D/libc-netbsd(  856): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  856): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  856): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  856): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out(  856): propertyValue:false
V/WifiInternetCheck(  856): isHttpConnectionAvailable - We got a valid response : 204
,W/libprocessgroup(  856): failed to open /acct/uid_10089/pid_2911/cgroup.procs: No such file or directory
,D/WeekWidgetProvider( 3352): [onReceive]
D/CalendarWidgetProvider( 3352): [onReceive]
D/CalendarWidgetProvider( 3352): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 3352): [onUpdateAndInitCalendarTime]
D/WeatherAncestor( 2715): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 16:56:29
,D/UpdateThreadPoolManager( 2715): 2 : This is isUpdating : false
I/Icing   ( 2279): Storage manager: low false usage 1.70MB avail 2.43GB capacity 4.06GB
,I/SystemConfig( 3378): BUILD Country: EU
,I/SystemConfig( 3378): BUILD Operator: OPEN
D/Weather_cast( 2715): 2 : set auto-update time : 1/11 19:56
D/WeatherAncestor( 2715): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 16:56:29
D/WeatherService( 2715): 2 : onStartCommand, intent!=null, action: android.intent.action.TIME_SET
I/ActivityManager(  856): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3422 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/ActivityManager(  856): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2715): 2 : Utils getTopActivity com.lge.launcher2 / true
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 351us total 21.792ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 20.756ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 20.797ms
,D/WeatherService( 2715): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2715): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/AlertUtils( 3352): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,W/SIMContacts( 3378): SimPhonebookStateReceiver|onReceive: ACTION_SIM_STATE_CHANGED
D/SIMContacts( 3378): SimConfig|ENABLE_MULTI_SIM_MODE : false
D/SIMContacts( 3378): SimConfig|Slot count : 1
W/SIMContacts( 3378): SimPhonebookStateReceiver|PhoneCount = 1
I/AlertUtils( 3352): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
D/TimeService( 3422): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1452527789404
D/        ( 3422): TimeServiceNative: User Time to be set is 1452527789405
D/QC-time-services( 3422): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 3422): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 3422): Lib:time_genoff_operation: pargs->ts_val = 1452527789405
D/QC-time-services( 3422): Lib:time_genoff_operation: Send to server  passed!!
,D/QC-time-services(  360): Daemon: Connection accepted:time_genoff
D/QC-time-services(  360): Daemon:Received base = 2, unit = 1, operation = 0,value = 1452527789405
D/QC-time-services(  360): Daemon:genoff_opr: Base = 2, val = 1452527789405, operation = 0
I/AlertUtils( 3352): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
D/QC-time-services(  360): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS4/24/70 19:58:6
D/QC-time-services(  360): Daemon:Value read from RTC seconds = 12427086000
D/QC-time-services(  360): Daemon:new time 1452527789405 
D/QC-time-services(  360): Daemon: delta 1440100703405 genoff 1440100703405 
D/QC-time-services(  360): Daemon:genoff_persistent_update: Writing genoff = 1440100703405 to memory
D/QC-time-services(  360): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  360): Daemon:time_persistent_memory_opr:Genoff write operation 
I/AlertUtils( 3352): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
D/PhoneInterfaceManager( 1795): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
I/AlertUtils( 3352): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,W/SIMContacts( 3378): SimPhonebookStateReceiver|SIM slot is empty... start clear sim contact
I/AlertUtils( 3352): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 3352): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/SystemConfig( 3378): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 3378): existFile = false
I/SystemConfig( 3378): canReadFile = false
I/SystemConfig( 3378): systemFeature RCS result false
D/SystemConfig( 3378): refreshRcsSupport() :false
I/AlertUtils( 3352): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,W/art     ( 3331): Attempt to remove local handle scope entry from IRT, ignoring
I/AlertUtils( 3352): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 3352): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3352): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,I/AlertUtils( 3352): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
D/SIMContacts( 3378): SimPhonebookManager||clearSimContacts:BEGIN : 0
D/QC-time-services(  360): Updating the TOD offset
D/QC-time-services(  360): Daemon:genoff_persistent_update: Writing genoff = 1440100703405 to memory
D/QC-time-services(  360): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  360): Daemon:time_persistent_memory_opr:Genoff write operation 
D/SIMContacts( 3378): CancelableTaskScheduler|| task={com.lge.contacts.sim.ClearSimContactsTask@1c98b5ea} is registered
I/AlertUtils( 3352): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,V/SIMContacts( 3378): CancelableTaskScheduler|requestStartLocked {com.lge.contacts.sim.ClearSimContactsTask@1c98b5ea}
E/QC-time-services(  360): Daemon:Update to modem bit set
D/QC-time-services(  360): Daemon:genoff_send_modem: Sending data to MODEM !
E/QC-time-services( 3422): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
D/QC-time-services(  360): Daemon: Base = 2, Value being sent to MODEM = 1124135903405
D/SIMContacts( 3378): SimPhonebookManager||clearSimContacts:END
E/QC-time-services(  360): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  360): Daemon: Time-services: Waiting to acceptconnection
D/SIMContacts( 3378): CancelableTaskScheduler|start background task {20}
I/AlertUtils( 3352): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,W/AwContents( 3331): onDetachedFromWindow called when already detached. Ignoring
D/PowerManagerServiceEx(  856): acquireWakeLockInternal: lock=281413614, flags=0x20000001, tag="CancelableTaskScheduler", ws=null, historyTag=null, uid=10018, pid=3378
I/AlertUtils( 3352): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 3352): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
,D/SettingsProviderInitializer(  856): [Extra] : ABSENT == 'LOADED' ??
I/AlertUtils( 3352): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
V/LGSC    ( 2756): [105] 501
D/SystemWebViewEngine( 3331): CordovaWebView is running on device made by: LGE
V/LGSC    ( 1795): [101] 102, action=android.intent.action.SIM_STATE_CHANGED, iccState=ABSENT
,I/AlertUtils( 3352): set default noti to content://media/internal/audio/media/38
W/art     ( 3331): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3331): Attempt to remove local handle scope entry from IRT, ignoring
I/Contacts_Profile( 3378): support PRI : true
I/Contacts_Profile( 3378): setDefault : phone
I/InitNotificationRingtoneService( 3352): End InitializeAlertRingtoneService.onHandleIntent
I/ActivityManager(  856): Start proc com.lge.hiddenmenu for broadcast com.lge.hiddenmenu/.wcdma_only.log_service.FactorySIMReceiver: pid=3454 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  856): Killing 3011:com.android.cellbroadcastreceiver/u0a16 (adj 15): empty #11
I/ActivityManager(  856): Killing 3083:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,W/libprocessgroup(  856): failed to open /acct/uid_10016/pid_3011/cgroup.procs: No such file or directory
,I/Activity( 3331): Activity.onPostResume() called 
W/libprocessgroup(  856): failed to open /acct/uid_10009/pid_3083/cgroup.procs: No such file or directory
D/OpenGLRenderer( 3331): Render dirty regions requested: true
I/OpenGLRenderer( 3331): Initialized EGL, version 1.4
,I/CheckinService( 2279): Checkin interval check for package: unspecified last checkin: 1452525992039 min interval config: 0 actual interval: 1797641
D/OpenGLRenderer( 3331): Enabling debug mode 0
,D/Atlas   ( 3331): Validating map...
D/SplitWindow(  856): check instance of lgWin Window{144c0687 u0 com.example.hello/com.example.hello.MainActivity}
W/chromium( 3331): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,W/ResourcesManager( 3454): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 3454): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ActivityManager(  856): Unable to start service Intent { act=com.lge.ime.intent.ANDROID_CONTACT_DB_UPDATED pkg=com.lge.ime } U=0: not found
I/LOG_TAG ( 3185): sendMessageToComposeMessageActivy + null
I/ValidateNoPeople(  856): mEvictionCount: 0
I/art     ( 2078): Explicit concurrent mark sweep GC freed 2528(98KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 473us total 40.525ms
,D/InputDispatcher(  856): Focus entered window: Window{144c0687 u0 com.example.hello/com.example.hello.MainActivity}
,I/ActivityManager(  856): Killing 3102:com.lge.lgdmsclient/1000 (adj 15): empty #11
,V/LogService( 3454): FactorySIMReceiver.operatorNumeric : 
V/LogService( 3454): FactorySIMReceiver.factory.enable : 0
V/LogService( 3454): FactorySIMReceiver.factory.enable : 
,W/InputMethodManagerService(  856): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/Timeline( 3331): Timeline: Activity_idle id: android.os.BinderProxy@3b4322bc time:44864
,W/libprocessgroup(  856): failed to open /acct/uid_1000/pid_3102/cgroup.procs: No such file or directory
,D/PowerManagerServiceEx(  856): releaseWakeLockInternal: lock=281413614 [CancelableTaskScheduler], flags=0x0
D/SIMContacts( 3378): CancelableTaskScheduler|background task is finished {20}, time=420.092604 msec
W/BindingManager( 3331): Cannot call determinedVisibility() - never saw a connection for the pid: 3331
I/ActivityManager(  856): Start proc com.android.providers.partnerbookmarks for broadcast com.android.providers.partnerbookmarks/com.lge.provider.BookmarksProviderReceiver: pid=3485 uid=10071 gids={50071, 9997} abi=armeabi-v7a
,I/ActivityManager(  856): Killing 3122:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #11
I/chromium( 3331): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
W/libprocessgroup(  856): failed to open /acct/uid_10011/pid_3122/cgroup.procs: No such file or directory
,I/ActivityManager(  856): Displayed com.example.hello/.MainActivity: +1s810ms
I/Timeline(  856): Timeline: Activity_windows_visible id: ActivityRecord{8dcca89 u0 com.example.hello/.MainActivity t220} time:45042
,D/JsMessageQueue( 3331): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 3331): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/AccountTypeManager( 3378): Registering 1 extension packages
E/ExternalAccountType( 3378): Unsupported attribute readOnly
,I/Icing   ( 2279): updateResources: need to parse f{com.google.android.gms}
D/AccountTypeManager( 3378): Registering extension package account type=com.google, dataSet=plus, packageName=com.google.android.apps.plus
I/SIMContacts( 3378): SimPhonebookManager|[0]SIM loading status : false
I/AccountTypeManager( 3378): Loaded meta-data for 4 account types, 3 accounts in 120ms(wall) 40ms(cpu)
,D/AccountTypeManager( 3378): Registering 1 extension packages
D/PARTNER_SimInfo( 3485): FlexData mcc/mnc is null 
E/ExternalAccountType( 3378): Unsupported attribute readOnly
,D/AccountTypeManager( 3378): Registering extension package account type=com.google, dataSet=plus, packageName=com.google.android.apps.plus
I/SIMContacts( 3378): SimPhonebookManager|[0]SIM loading status : false
I/AccountTypeManager( 3378): Loaded meta-data for 4 account types, 3 accounts in 23ms(wall) 12ms(cpu)
I/BookmarksProviderReceiver( 3485): BookmarksProviderReceiver onReceive = [ android.intent.action.SIM_STATE_CHANGED ]
I/BookmarksProviderReceiver( 3485): SIM_STATE_CHANGED event stateExtra : [ ABSENT ]
,E/PARTNER_SimInfo( 3485): setSimState:NOT_READY
I/ActivityManager(  856): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=3507 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  856): Killing 3145:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_10011/pid_3145/cgroup.procs: No such file or directory
,V/AudioFlinger(  284): thread 0xb5651000 type 0 TID 1314 going to sleep
,V/AudioFlinger(  284): thread 0xb56eb000 type 0 TID 1315 going to sleep
V/AudioFlinger(  284): thread 0xb5735000 type 0 TID 1317 going to sleep
,D/SIMObserver( 3507): action:android.intent.action.SIM_STATE_CHANGED
D/SIMObserver( 3507): state : ABSENT
D/EULA::SimManager( 3507): SimManager getInstance.
,I/EULA::SimManager( 3507): TelephonyManager will be used!
I/EULA::SimManager( 3507): SubscriptionManager will be used!
I/Icing   ( 2279): Internal init done: storage state 0
,I/EULA::SimManager( 3507): sSimInstance : android.telephony.TelephonyManager@540d863
I/EULA::SimManager( 3507): sIsMultiSimEnabled : false
I/EULA::SimManager( 3507): sSIMCount : 1
I/EULA::SimManager( 3507): TelephonyManager will be used!
I/EULA::SimManager( 3507): SubscriptionManager will be used!
I/EULA::SimManager( 3507): sSimInstance : android.telephony.TelephonyManager@540d863
I/EULA::SimManager( 3507): sIsMultiSimEnabled : false
I/EULA::SimManager( 3507): sSIMCount : 1
I/NotificationManager( 2054): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/Icing   ( 2279): Post-init done
,D/SIMObserver( 3507): simState : 1
I/LicenseContentProvider( 3507): start selecting data
D/EULA::SimManager( 3507): SimManager getInstance.
I/EULA::SimManager( 3507): TelephonyManager will be used!
I/EULA::SimManager( 3507): SubscriptionManager will be used!
I/EULA::SimManager( 3507): sSimInstance : android.telephony.TelephonyManager@540d863
I/EULA::SimManager( 3507): sIsMultiSimEnabled : false
I/EULA::SimManager( 3507): sSIMCount : 1
D/SIMObserver( 3507): simInfo1
,I/Icing   ( 2279): Query from com.google.android.googlequicksearchbox package restrict com.google.android.googlequicksearchbox start 0 num 1000
I/ActivityManager(  856): Killing 3163:com.android.browser/u0a12 (adj 15): empty #11
,E/Icing   ( 2279): No scoring data for corpus [22]
,I/NotificationManager( 2279): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/FotaManager( 3507): Fingerprint is same, do nothing
D/FotaManager( 3507): enable_notification_eula_flag : 1
D/SIMObserver( 3507): EULA has not been agreed, we need to show it on notification bar
,I/Icing   ( 2279): Query from com.google.android.googlequicksearchbox package restrict com.google.android.googlequicksearchbox start 0 num 1000
W/libprocessgroup(  856): failed to open /acct/uid_10012/pid_3163/cgroup.procs: No such file or directory
,W/FotaManager( 3507): topActivity.getClassName() : com.example.hello.MainActivity
D/FotaManager( 3507): baseActivity : com.example.hello / com.example.hello.MainActivity
I/ApplicationLogger( 2054): logBytes() : Old Hash = 441496333 : New Hash = -906548067
,V/NotificationService(  856): enqueueNotificationInternal: pkg=com.lge.eula id=262082 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/ZenLog  (  856): intercepted: 0|com.lge.eula|262082|null|1000,none
V/NotificationService(  856): pkg=com.lge.eula canInterrupt=false intercept=true
I/NotificationServiceEx(  856): LED remove() : mLights=0|com.lge.eula|262082|null|1000
,I/ActivityManager(  856): Killing 3055:com.lge.email/u0a21 (adj 15): empty #11
D/NotificationServiceEx(  856): updateLightListLocked :r=0|com.lge.eula|262082|null|1000, action=2
D/NotificationServiceEx(  856): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/BluetoothManagerService(  856): Auto-enabling Bluetooth.
,D/BluetoothManagerService(  856): Message: 1
D/BluetoothManagerService(  856): MESSAGE_ENABLE: mBluetooth = null
D/SmartCoverUpdateMonitor( 1348): onNotificationPosted() : StatusBarNotification(pkg=com.lge.eula user=UserHandle{0} id=262082 tag=null score=0 key=0|com.lge.eula|262082|null|1000: Notification(pri=0 contentView=com.lge.eula/0x1090079 vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE))
,D/SmartCoverUpdateMonitor( 1348): addNotification() qcn.getKey() : 0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1348): addNotification() : 0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1348): filterAndSort()
W/libprocessgroup(  856): failed to open /acct/uid_10021/pid_3055/cgroup.procs: No such file or directory
D/LgeQuickCoverNotificationData( 1348): isNotificationForCurrentUser : true
,D/BluetoothAdapterService(292483291)( 2100): onBind()
D/LgeQuickCoverNotificationData( 1348): isNotificationForCurrentUser : true
,D/BluetoothManagerService(  856): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
D/BluetoothManagerService(  856): Message: 40
D/BluetoothManagerService(  856): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,D/LgeQuickCoverNotificationData( 1348): showAll2
D/LgeQuickCoverNotificationData( 1348): showAll() Key : 0|com.lge.eula|262082|null|1000 , GroupKey : 0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1348): showAll() Key : 0|com.android.systemui|2130839020|null|10025 , GroupKey : 0|com.android.systemui|2130839020|null|10025
I/UpdateIcingCorporaServi( 2054): UpdateCorporaTask done [took 2194 ms] updated apps [took 2084 ms] updated contacts [took 110 ms]
,D/SmartCoverUpdateMonitor( 1348): received broadcast android.intent.action.BOOT_COMPLETED
I/[SystemUI]PhoneStatusBar( 1390): updateMediaMetaData(false): mMediaMetadata = null
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/bluedroid( 2100): config_hci_snoop_log
D/BluetoothManagerService(  856): Calling onBluetoothServiceUp callbacks
D/BluetoothManagerService(  856): Broadcasting onBluetoothServiceUp() to 7 receivers.
I/[SystemUI]BOOT( 1390): SystemUIService, BOOT_COMPLETED received
,V/LGMDMManagerInternal( 2100): Create singleton instance
I/ActivityManager(  856): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=3539 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/SystemUIService( 1390): com.lge.systemui.LGSystemUI@17d69e51.onBootCompleted(), mBootCompleted: true
I/SystemUIService( 1390): com.android.systemui.keyguard.KeyguardViewMediator@2c530d54.onBootCompleted(), mBootCompleted: true
,D/LNfcService( 1859): action : android.intent.action.USER_PRESENT
I/SystemUIService( 1390): com.android.systemui.recent.Recents@117eaf1c.onBootCompleted(), mBootCompleted: true
I/SystemUIService( 1390): com.android.systemui.volume.VolumeUI@7ce626f.onBootCompleted(), mBootCompleted: true
I/SystemUIService( 1390): com.android.systemui.statusbar.SystemBars@16f73c05.onBootCompleted(), mBootCompleted: true
I/SystemUIService( 1390): com.android.systemui.usb.LGStorageNotification@3e88b68b.onBootCompleted(), mBootCompleted: true
I/SystemUIService( 1390): com.lge.power.LGPowerUI@3b95e6bd.onBootCompleted(), mBootCompleted: true
I/SystemUIService( 1390): com.android.systemui.media.RingtonePlayer@3e4f04b2.onBootCompleted(), mBootCompleted: true
I/[SystemUI]LGStorageNotification( 1390): connected=false
D/NfcServiceNXP( 1859): mScreenState : 3, mInProvisionMode : false
,D/NfcServiceNXP( 1859): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1859): isRequireNfcCRouting() return true
D/LNfcService( 1859): isHCERoutingtoHost() return : true
D/NfcService( 1859): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1859): mEnableLPD: true
D/NfcService( 1859): mEnableReader: false
D/NfcService( 1859): mEnableHostRouting: true
D/NfcService( 1859): newParams.techmask= mTechMask: default
D/NfcService( 1859): mEnableLPD: true
D/NfcService( 1859): mEnableReader: false
D/NfcService( 1859): mEnableHostRouting: true
D/NfcService( 1859): screenState= 3
D/NfcService( 1859): Discovery configuration equal, not updating.
I/ActivityManager(  856): Start proc com.android.gallery3d for service com.android.gallery3d/com.lge.gallery.picasa.PicasaService: pid=3558 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/BluetoothAdapterService(292483291)( 2100): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e9dc689
,D/BluetoothAdapterService(292483291)( 2100): enable() - Enable called with quiet mode status =  false
D/BluetoothAdapterState( 2100): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
D/BluetoothAdapterProperties( 2100): Setting state to 11
I/BluetoothAdapterState( 2100): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService(292483291)( 2100): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService(  856): Message: 60
D/BluetoothManagerService(  856): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  856): Bluetooth State Change Intent: 10 -> 11
I/RecoverySystem(  856): No recovery log file
D/BluetoothAdapterService(292483291)( 2100): processStart()
D/BluetoothAdapterService(292483291)( 2100): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e9dc689
,D/BluetoothAdapterService(292483291)( 2100): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e9dc689
I/[SystemUI]QuickSettingsHandler( 1390): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
D/LauncherStateReceiver2( 3378): .activities.CallLogSearchResolverActivity enable(1)/disable(2) : 2
I/[SystemUI]BluetoothHandler( 1390): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
D/LauncherStateReceiver2( 3378): .DialtactsRecentCallsEntryActivity enable(1)/disable(2) : 2
D/LauncherStateReceiver2( 3378): .alias.SpeedDialListActivity enable(1)/disable(2) : 2
,D/BtSettings.ProfileConfig( 2100): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,D/LGBluetoothAPIService( 1883): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BtSettings.ProfileConfig( 2100): Unable to read settings
D/BtSettings.ProfileConfig( 2100): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2100): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 2100): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 2100): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 2100): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:672)
D/BtSettings.ProfileConfig( 2100): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 2100): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 2100): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 2100): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 2100): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 2100): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/BluetoothPbapReceiver( 2100): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 2100): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 2100): ***********state = 11
W/BluetoothAdapterService( 2100): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2100): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 2100): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2100): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 2100): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2100): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 2100): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2100): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 2100): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2100): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 2100): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2100): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
I/WifiServerServiceExt(  856): ACTION_BOOT_COMPLETED
W/ResourcesManager( 3558): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3558): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3558): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/BluetoothAdapterService( 2100): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2100): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 2100): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 2100): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 2100): isProfileEnabled(): profile not found com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 2100): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 2100): isProfileEnabled(): profile not found com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(292483291)( 2100): processStart() - Make Bond State Machine
,D/ConnectivityService(  856): Got NetworkFactory Messenger for WIFI
D/ConnectivityService(  856): NetworkFactory connected
D/WIFI    (  856): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
D/WIFI    (  856):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/BluetoothBondStateMachine( 2100): make
D/BluetoothAdapterService( 2100): setAdapterService() - set to: null
D/BluetoothAdapterService( 2100): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@116ef0db
D/LGBluetoothServiceAdapter( 2100): [BTUI] check adapter is available - true : set adapter available.
I/BluetoothBondStateMachine( 2100): StableState(): Entering Off State
,D/BluetoothAdapterService( 2100): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2100): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2100): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2100): Unable to read settings
D/BtSettings.ProfileConfig( 2100): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2100): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 2100): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 2100): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 2100): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 2100): 	at com.android.bluetooth.btservice.AdapterService.processStart(AdapterService.java:712)
D/BtSettings.ProfileConfig( 2100): 	at com.android.bluetooth.btservice.AdapterState$OffState.processMessage(AdapterState.java:232)
D/BtSettings.ProfileConfig( 2100): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 2100): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 2100): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 2100): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 2100): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 2100): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(292483291)( 2100): setProfileServiceState() - Starting service com.android.bluetooth.hfp.HeadsetService
,I/BootReceiver(  856): Copying audit failures to DropBox
I/BootReceiver(  856): Checking for fsck errors
I/NotificationManager(  856): android: cancelAsUser(17039631) by android
V/TelephonyAutoProfiling( 1795): [getValue] PROFILE key : VMS, value : null, phoneId : 0
D/BluetoothAdapterService( 2100): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2100): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2100): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 2100): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(292483291)( 2100): setProfileServiceState() - Starting service com.android.bluetooth.a2dp.A2dpService
,V/AudioPolicyManager(  284): setDeviceConnectionState() device: 4, state 0, address 
W/AudioPolicyManager(  284): setDeviceConnectionState() device not connected: 4
V/AudioPolicyManager(  284): setDeviceConnectionState() device: 8, state 0, address 
W/AudioPolicyManager(  284): setDeviceConnectionState() device not connected: 8
D/BluetoothPermissionRequest( 3262): onReceive
D/HeadsetService( 2100): Received start request. Starting profile...
I/LGBluetoothHeadsetServiceJni( 2100): classInitNative: succeeds
,D/BluetoothHeadset( 1795): Proxy object connected
D/BluetoothHeadset(  856): Proxy object connected
D/CHFeatures( 3378): serviceContry: EU
D/CHFeatures( 3378): serviceProvider: OPEN
D/CHFeatures( 3378): serviceCountryIndex: 2
D/CHFeatures( 3378): serviceProviderIndex: 4
D/LGSDEncService( 1883): action=android.intent.action.BOOT_COMPLETED
D/BluetoothHeadset( 1795): Proxy object connected
D/BluetoothAdapterService(292483291)( 2100): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e9dc689
D/BluetoothHeadset( 1795): Proxy object connected
D/BluetoothAdapterService( 2100): getQuietmodeRadioCount = 0
,W/BluetoothAdapterService( 2100): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2100): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 2100): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(292483291)( 2100): setProfileServiceState() - Starting service com.android.bluetooth.hid.HidService
I/QCNEJ   ( 1929): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
D/LGBluetoothAPIService( 1883): [BTUI] onReceive action : android.intent.action.BOOT_COMPLETED
D/LGBluetoothFeatureConfig( 2100): isPrivacyLogsEnabled : true
I/BluetoothHeadsetServiceJni( 2100): classInitNative: succeeds
D/LGBluetoothFeatureConfig( 1883): isSupportPan() :  mTargetOp=OPEN
D/LGBluetoothFeatureConfig( 1883):  get() - isFeatureLoaded : false
D/LGBluetoothFeatureConfig( 3262):  get() - isFeatureLoaded : false
D/BluetoothAdapterService( 2100): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2100): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2100): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 2100): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(292483291)( 2100): setProfileServiceState() - Starting service com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 2100): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2100): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2100): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 2100): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(292483291)( 2100): setProfileServiceState() - Starting service com.android.bluetooth.pan.PanService
D/HeadsetStateMachine( 2100): make
I/LGSDEncService( 1883): MediaExceptionType=BDMB/MID/EC3/OGV/JPEG/WEBM/QCP/JPS/RA/MXMF/JPG/WAV/RV/PNG/M3U8/WPL/3GP/3GPP/OTA/SMF/AMR/MP4/BMP/OGG/MKV/TP/DCI/M4V/WMV/WEBP/3GPP2/DTS/ADTS/MPO/OGA/RMVB/OGM/3G2/3GA/MKA/MPD/TS/MP2/FLAC/MPGA/JPE/RM/M2TS/PLS/MIDI/WBMP/RAM/ASF/MPG/RTX/K3G/IMY/AWB/MPEG/AC3/F4V/DIVX/XMF/FLV/MP3/RTTTL/AVI/GIF/AAC/M3U/M4A/SKM/WMA/MTS/DMB/
D/        ( 1883): android_net_LGSDEnc_sysCallMediaExt:33:: propertyVal = (379), extList = (BDMB/MID/EC3/OGV/JPEG/WEBM/QCP/JPS/RA/MXMF/JPG/WAV/RV/PNG/M3U8/WPL/3GP/3GPP/OTA/SMF/AMR/MP4/BMP/OGG/MKV/TP/DCI/M4V/WMV/WEBP/3GPP2/DTS/ADTS/MPO/OGA/RMVB/OGM/3G2/3GA/MKA/MPD/TS/MP2/FLAC/MPGA/JPE/RM/M2TS/PLS/MIDI/WBMP/RAM/ASF/MPG/RTX/K3G/IMY/AWB/MPEG/AC3/F4V/DIVX/XMF/FLV/MP3/RTTTL/AVI/GIF/AAC/M3U/M4A/SKM/WMA/MTS/DMB/) 
D/        ( 1883): android_net_LGSDEnc_sysCallMediaProperty:61:: propertyVal = (378), enable=(0) rc=(1)
D/BluetoothAdapterService( 2100): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2100): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2100): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 2100): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(292483291)( 2100): setProfileServiceState() - Starting service com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 2100): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2100): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2100): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 2100): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(292483291)( 2100): setProfileServiceState() - Starting service com.android.bluetooth.map.BluetoothMapService
I/LGSDEncService( 1883): BOOT_BroadcastReceiver Media SystemCall :: getMediaProperty = 0
D/LGSDEncService( 1883): Initializing Encryption start
D/BluetoothAdapterService( 2100): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2100): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 2100): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 2100): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(292483291)( 2100): setProfileServiceState() - Starting service com.broadcom.bt.service.sap.SapService
,V/WifiSapService( 1883): WifiSapService [ACTION_BOOT_COMPLETED]
,D/BluetoothManagerService(  856): Message: 20
D/BluetoothManagerService(  856): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3face9e0:true
,D/HeadsetStateMachine( 2100): max_hf_connections = 1
I/bluedroid( 2100): get_profile_interface handsfree
I/bt-btif ( 2100): btif_hf_get_interface
I/bt-btif ( 2100): init
D/bt-btif ( 2100): max_hf_clients = 1
D/bt-btif ( 2100): btif_max_hf_clients = 1
D/bt-btif ( 2100): btif_enable_service: current services:0xa0667330
D/BluetoothAdapterService( 2100): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2100): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BtSettings.ProfileConfig( 2100): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 2100): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(292483291)( 2100): setProfileServiceState() - Starting service com.broadcom.bt.service.ftp.FTPService
V/ToneGenerator( 2100): ToneGenerator constructor: streamType=8, volume=1.000000
,D/BluetoothAdapterService( 2100): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2100): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BtSettings.ProfileConfig( 2100): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 2100): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(292483291)( 2100): setProfileServiceState() - Starting service com.broadcom.bt.service.opp.OppService
,E/DefaultVoicemailNotifier( 3378): No voicemails to notify about: clear the notification.
I/NotificationManager( 3378): com.android.contacts: cancel(1) by com.android.contacts
V/LGMDMManager( 2100): Create singleton instance
V/AudioPolicyService(  284): registerClient() client 0xb40277c0, uid 1002
V/AudioPolicyManager(  284): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerEx(  284): AudioPolicyManagerEx: getOutputForDevice
V/AudioPolicyManagerEx(  284): getOutput() returns output 2
,I/BluetoothAdapterState( 2100): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
E/ActivityThread( 2279): Failed to find provider info for com.android.contacts.metadata
V/AudioFlinger(  284): registerClient() client 0xb40330e8, pid 2100
V/AudioFlinger(  284): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  284): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  284): thread 0xb5651000 type 0 TID 1314 waking up
V/AudioFlinger(  284): thread 0xb56eb000 type 0 TID 1315 waking up
I/LogService_Receiver( 3454): getAction is : android.intent.action.BOOT_COMPLETED
E/LogService_Receiver( 3454): Log Enable Check Value :0
E/LogService_Receiver( 3454): Log Enable Check Value :0
E/LogService_Receiver( 3454): Log Enable Check Value :0
E/LogService_Receiver( 3454): Log Enable Check Value :0
E/LogService_Receiver( 3454): Log Enable Check Value :0
E/LogService_Receiver( 3454): Log Enable Check Value :0
V/AudioFlinger(  284): processConfigEvents_l() remaining events 1
V/AudioFlinger(  284): PlaybackThread::audioConfigChanged, thread 0xb5651000, event 0, param 0
V/AudioSystem(  284): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  284): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1390): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  856): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1390): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  856): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1795): ioConfigChanged() event 0, ioHandle 2
V/AudioFlinger(  284): processConfigEvents_l() DONE thread 0xb5651000
V/AudioSystem( 1795): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 3185): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2054): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 3185): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2054): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 2100): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 2100): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
V/AudioSystem( 2730): ioConfigChanged() event 0, ioHandle 2
,V/AudioSystem( 2730): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  284): processConfigEvents_l() remaining events 1
V/AudioFlinger(  284): PlaybackThread::audioConfigChanged, thread 0xb56eb000, event 0, param 0
V/AudioSystem(  284): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  284): ioConfigChanged() opening already existing output! 4
V/AudioSystem(  856): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem(  856): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 1390): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1390): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2054): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 1795): ioConfigChanged() event 0, ioHandle 4
V/AudioFlinger(  284): processConfigEvents_l() DONE thread 0xb56eb000
V/AudioSystem( 1795): ioConfigChanged() opening already existing output! 4
V/AudioSystem( 2054): ioConfigChanged() opening already existing output! 4
V/AudioFlinger(  284): sendConfigEvent_l() num events 1 event 0
V/AudioFlinger(  284): thread 0xb5735000 type 0 TID 1317 waking up
V/AudioSystem( 2100): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2100): ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
V/ToneGenerator( 2100): Create Track: 0xb4909480
V/AudioTrack( 2100): set(): streamType 8, sampleRate 48000, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
V/AudioTrack( 2100): set() streamType 8, sampleRate 48000, format 1, frameCount 0, flags 0004
I/AudioFlinger(  284): isAudioPlaybackHookOn() false
D/AudioTrack( 2100): TrackOffload: AudioTrack Offload disabled by property, returning false
V/AudioSystem( 2730): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 2730): ioConfigChanged() opening already existing output! 4
V/AudioPolicyManager(  284): getOutputForAttr() usage=3, content=4, tag= flags=00000000
V/AudioPolicyManager(  284): getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
V/AudioSystem( 3185): ioConfigChanged() event 0, ioHandle 4
V/AudioSystem( 3185): ioConfigChanged() opening already existing output! 4
V/AudioFlinger(  284): processConfigEvents_l() remaining events 1
V/AudioPolicyManagerEx(  284): AudioPolicyManagerEx: getOutputForDevice
V/AudioFlinger(  284): PlaybackThread::audioConfigChanged, thread 0xb5735000, event 0, param 0
V/AudioSystem(  284): ioConfigChanged() event 0, ioHandle 6
,V/AudioPolicyManagerEx(  284): getOutput() returns output 2
V/AudioSystem(  284): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 2100): getLatency() output 2, latency 50
V/AudioSystem( 2100): getFrameCount() output 2, frameCount 960
V/AudioTrack( 2100): createTrack_l() output 2 afLatency 50
V/AudioTrack( 2100): Create normal PCM 0x1 Track
V/AudioSystem( 2054): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 2054): ioConfigChanged() opening already existing output! 6
V/AudioFlinger(  284): processConfigEvents_l() DONE thread 0xb5735000
V/AudioSystem( 1795): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1795): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 2100): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 2100): ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 1152 latency 112
V/AudioSystem(  856): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem(  856): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 1390): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 1390): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 2730): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 2730): ioConfigChanged() opening already existing output! 6
V/AudioSystem( 3185): ioConfigChanged() event 0, ioHandle 6
V/AudioSystem( 3185): ioConfigChanged() opening already existing output! 6
V/AudioFlinger(  284): createTrack() lSessionId: 22
V/AudioFlinger(  284): AUDIO_OUTPUT_FLAG_FAST accepted: frameCount=480 mFrameCount=240
V/AudioFlinger(  284): sendConfigEvent_l() num events 1 event 1
V/AudioFlinger(  284): processConfigEvents_l() remaining events 1
V/AudioFlinger(  284): processConfigEvents_l() DONE thread 0xb5651000
V/AudioTrack( 2100): Flags here  0x4 
V/AudioTrack( 2100): AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
V/AudioFlinger(  284): acquiring 22 from 2100, for 2100
V/AudioFlinger(  284):  added new entry for 22
V/ToneGenerator( 2100): ToneGenerator INIT OK, time: 46313
D/BluetoothAdapterService( 2100): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@116ef0db
D/HeadsetStateMachine( 2100): Enter Disconnected: -2, size: 0
D/HeadsetPhoneState( 2100): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 2100): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 2100): [BTUI] change sampling rate to 8000 when device is disconnected
V/AudioFlinger(  284): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 2100
D/audio_hw_primary(  284): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  284): voice_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  284): voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
V/compress_voip(  284): voice_extn_compress_voip_set_parameters: exit
V/voice   (  284): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  284): LGE_platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  284): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  284): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  284): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  284): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  284): adev_set_parameters: exit with code(0)
V/ToneGenerator( 2100): ToneGenerator destructor
V/ToneGenerator( 2100): stopTone
V/ToneGenerator( 2100): Delete Track: 0xb4909480
,V/AudioTrack( 2100): ~AudioTrack, releasing session id from 2100 on behalf of 2100
V/AudioFlinger(  284): remove track (4099) and delete from mixer
V/AudioPolicyService(  284): AudioCommandThread() adding release output 2
V/AudioFlinger(  284): releasing 22 from 2100 for 2100
V/AudioFlinger(  284):  decremented refcount to 0
V/AudioFlinger(  284): purging stale effects
V/AudioPolicyService(  284): inserting command: 6 at index 0, num commands 0
V/AudioFlinger(  284): PlaybackThread::Track destructor
V/AudioPolicyService(  284): AudioCommandThread() waking up
V/AudioFlinger(  284): removeClient_l() pid 2100, calling pid 284
V/AudioPolicyService(  284): AudioCommandThread() processing release output 2
V/AudioPolicyManager(  284): releaseOutput() 2
V/AudioPolicyService(  284): AudioCommandThread() going to sleep
I/ActivityManager(  856): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3591 uid=10008 gids={50008, 9997} abi=armeabi-v7a
,D/BluetoothAdapterService( 2100): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@116ef0db
D/SyncManager(  856): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 35355, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager(  856): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 77226, reason: UserStart
,I/NotificationManager(  856): android: cancelAsUser(716319171) by android
D/BluetoothA2dp(  856): Proxy object connected
D/A2dpService( 2100): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 2100): classInitNative: succeeds
V/Avrcp   ( 2100): make
D/Avrcp   ( 2100): [BTUI] Use Native AVRCP : init jni
I/bluedroid( 2100): get_profile_interface avrcp
I/bt-btif ( 2100): btif_rc_get_interface
I/bt-btif ( 2100): ## init ##
D/BluetoothAdapterService(292483291)( 2100): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e9dc689
I/LGBluetoothAvrcpServiceJni( 2100): classInitNative: succeeds
,I/LGBluetoothAvrcpAdapter( 2100): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
I/LGBluetoothAvrcpServiceJni( 2100): initNative: succeeds
I/BluetoothAvrcpBrcmAdapterJni( 2100): classInitBrcmNative
I/BluetoothAvrcpBrcmAdapterJni( 2100): initBrcmNative
I/AppConfig( 3558): Total System Memory = 906309632
,I/GalleryUtils( 3558): Application Heap = 96 MB
I/AppConfig( 3558): App Tier : NOT_DEF
,D/SystemHelper( 3558): region [EU], country [EU], operator [OPEN], sub-operator []
,D/AccountTypeManager( 3378): Registering 1 extension packages
,E/ExternalAccountType( 3378): Unsupported attribute readOnly
,I/ActivityManager(  856): Killing 3308:com.lge.clock/u0a10 (adj 15): empty #11
I/art     (  856): Explicit concurrent mark sweep GC freed 26431(1308KB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 22MB/34MB, paused 3.766ms total 279.798ms
,V/AudioService(  856): updateRemoteControllerOnExistingMediaPlayers: size of Player list: 0
E/AudioService(  856): No RCC entry present to update
E/RemoteController( 2100): Cannot set synchronization mode on an unregistered RemoteController
I/BluetoothA2dpServiceJni( 2100): classInitNative
I/BluetoothA2dpServiceJni( 2100): classInitNative: succeeds
D/A2dpStateMachine( 2100): make
,I/bluedroid( 2100): get_profile_interface a2dp
I/bt-btif ( 2100): btif_av_get_src_interface
I/bt-btif ( 2100): init
D/bt-btif ( 2100): btif_enable_service: current services:0xa0667330
I/LGBluetoothA2dpServiceJni( 2100): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 2100): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/LGBluetoothPowerControlManager( 2100): [BTUI] getInstance
D/LGBluetoothPowerControlManager( 2100): [BTUI] init
D/AccountTypeManager( 3378): Registering extension package account type=com.google, dataSet=plus, packageName=com.google.android.apps.plus
I/SIMContacts( 3378): SimPhonebookManager|[0]SIM loading status : false
I/AccountTypeManager( 3378): Loaded meta-data for 4 account types, 3 accounts in 137ms(wall) 14ms(cpu)
,V/OneTimeInitializerReceiver( 3591): OneTimeInitializerReceiver.onReceive
,D/LGBluetoothPowerControlManager( 2100): [BTUI] init : getProfileProxy
D/BluetoothManagerService(  856): Message: 30
W/libprocessgroup(  856): failed to open /acct/uid_10010/pid_3308/cgroup.procs: No such file or directory
D/BluetoothAdapterService( 2100): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@116ef0db
D/A2dpStateMachine( 2100): Enter Disconnected: -2
I/BluetoothHidServiceJni( 2100): classInitNative: succeeds
D/HidService( 2100): Received start request. Starting profile...
,I/bluedroid( 2100): get_profile_interface hidhost
I/bt-btif ( 2100): btif_hh_get_interface
I/bt-btif ( 2100): init
D/bt-btif ( 2100): btif_enable_service: current services:0xa0667330
D/BluetoothAdapterService( 2100): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@116ef0db
I/BluetoothHealthServiceJni( 2100): classInitNative: succeeds
,D/HealthService( 2100): Received start request. Starting profile...
I/bluedroid( 2100): get_profile_interface health
I/bt-btif ( 2100): btif_hl_get_interface
I/bt-btif ( 2100): init
D/bt-btif ( 2100): Process name (droid.bluetooth)
D/bt-btif ( 2100): btif_hl_soc_thread_init
D/bt-btif ( 2100): create_thread: entered
D/bt-btif ( 2100): create_thread: thread created successfully
D/bt-btif ( 2100): entered btif_hl_select_thread
D/bt-btif ( 2100): btif_hl_select_wakeup_init
D/bt-btif ( 2100): btif_hl_select_wakeup_init signal_fds[0]=55 signal_fds[1]=56
D/bt-btif ( 2100): max_s=55 
D/bt-btif ( 2100): set curr_set = org_set 
I/LGBluetoothHealthServiceJni( 2100): classInitNative: succeeds
D/BluetoothAdapterService( 2100): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@116ef0db
V/OneTimeService( 3591): OneTimeService.onHandleIntent
I/BluetoothPanServiceJni( 2100): classInitNative(L105): succeeds
D/PanService( 2100): Received start request. Starting profile...
D/BluetoothPanServiceJni( 2100): initializeNative(L110): pan
I/bluedroid( 2100): get_profile_interface pan
D/bt-btif ( 2100): stack_initialized = 0, btpan_cb.enabled:0
,I/ActivityManager(  856): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=3618 uid=10016 gids={50016, 9997} abi=armeabi-v7a
,I/LGBluetoothPanAdapter( 2100): [BTUI] getInstance : create [LGBluetoothPanAdapter]
D/BluetoothAdapterService( 2100): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@116ef0db
I/BtGatt.JNI( 2100): classInitNative(L901): classInitNative: Success!
D/BtGatt.DebugUtils( 2100): handleDebugAction() action=null
I/NotificationManager(  856): android: cancelAsUser(-1597574061) by android
D/BtGatt.GattService( 2100): Received start request. Starting profile...
D/BtGatt.GattService( 2100): start()
I/bluedroid( 2100): get_profile_interface gatt
,D/BtGatt.AdvertiseManager( 2100): advertise manager created
I/ActivityManager(  856): Killing 3352:com.android.calendar/u0a13 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_10013/pid_3352/cgroup.procs: No such file or directory
,I/ActivityManager(  856): Killing 3422:com.qualcomm.timeservice/1000 (adj 15): empty #11
I/LGBluetoothGattAdapter( 2100): [BTUI] getInstance : create [LGBluetoothGattAdapter]
D/LGBluetoothGattAdapter( 2100): setGattService:  set to: null
D/BluetoothAdapterService( 2100): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@116ef0db
D/BluetoothAdapterService( 2100): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@116ef0db
I/LGBluetoothMapAdapter( 2100): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 2100): BluetoothMapBinder()
D/BluetoothMapService( 2100): Received start request. Starting profile...
D/BluetoothMapService( 2100): start()
,I/Icing   ( 2279): Indexing 0A5267A505F47CB39AEB664724AACA2991DAA8A8 from com.google.android.googlequicksearchbox
,D/CellBroadcastReceiverApp( 3618): CellBroadcastReceiverApp, onCreate()
,D/MultiSimWrapper( 3618): [MessageUtils] isTripleSimEnabled=false
D/MultiSimWrapper( 3618): [isMultiSimEnabled] = false
D/MultiSimWrapper( 3618): [MessageUtils] isTripleSimEnabled=false
D/CellBroadcastReceiver( 3618): startInit() started. iccLoaded=false init_complete=false
W/libprocessgroup(  856): failed to open /acct/uid_1000/pid_3422/cgroup.procs: No such file or directory
,D/BluetoothMapEmailSettingsLoader( 2100): Found 0 applications
D/BluetoothMapEmailAppObserver( 2100): createReceiver()
D/BluetoothMapEmailAppObserver( 2100): initObservers()
D/BluetoothMapEmailAppObserver( 2100): getEnabledAccountItems()
,D/BluetoothAdapterService( 2100): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@116ef0db
I/BluetoothSAPServiceJni( 2100): classInitNative(L170): succeeds
D/SapService( 2100): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 2100): initializeNative(L175): sap
I/bluedroid( 2100): get_profile_interface sap
,I/bt-btif ( 2100): btif_sc_get_interface
I/bt-btif ( 2100): init
D/bt-btif ( 2100): btif_enable_service: current services:0xa0667330
I/LGBluetoothSapAdapter( 2100): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 2100): [BTUI] Create LGBluetoothSapManager Instance
D/LGBluetoothSapManager( 2100): [BTUI] initSapManager
I/QCNEJ   ( 1929): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
D/BluetoothAdapterService( 2100): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@116ef0db
D/HeadsetStateMachine( 2100): Proxy object connected
I/QCNEJ   ( 1929): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:56:31.775 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/LgeBluetoothSimManager( 1795): [BTUI] SAP_ENABLE_EVT
,D/LGBluetoothHfpAdapter( 2100): [BTUI] queryPhoneState
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/BluetoothFTPServiceJni( 2100): classInitNative
D/CommonUtil( 3618): spn is empty. use default value as ""
,D/CommonUtil( 3618): getRuntimeImsiCode[]
I/BluetoothFTPServiceJni( 2100): classInitNative(L271): succeeds
D/BluetoothAdapterService( 2100): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@116ef0db
D/BluetoothFTPService( 2100): BluetoothFtpBinder()
D/**BluetoothFTPService( 2100): Received start request. Starting profile...
V/BluetoothFTPService( 2100): FTP-Server Service start
D/BluetoothFTPServiceJni( 2100): initFtpNativeDataNative(L275): FTP
I/bluedroid( 2100): get_profile_interface ftp
I/bt-btif ( 2100): btif_fts_get_interface
I/bt-btif ( 2100): init
D/bt-btif ( 2100): btif_enable_service: current services:0xa0667330
D/BluetoothFTPServiceJni( 2100): initFtpNativeDataNative(L317): FTP init done
D/BluetoothAdapterService( 2100): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@116ef0db
D/LGBluetoothOppAdapter( 2100): [BTUI] getInstance : create [LGBluetoothOppAdapter]
D/LGBluetoothFeatureConfig( 2100): isPrivacyLogsEnabled : true
E/BluetoothOPPServiceJni( 2100): classInitNative
I/BluetoothOPPServiceJni( 2100): classInitNative(L373): succeeds
V/OppService( 2100): Opp initBinder
,D/**OppService( 2100): Received start request. Starting profile...
D/OppService( 2100): Starting OppService 
D/CommonUtil( 3618): spn is empty. use default value as ""
D/CommonUtil( 3618): getRuntimeImsiCode[]
D/CommonUtil( 3618): simOperator =
D/CommonUtil( 3618): getRuntimeMccCode[0]
D/CellBroadcastReceiver( 3618): single sim : imsiCode= MccCode=0
E/CellBroadcastReceiver( 3618): IMSI value is NOT available yet. DO NOT PROCESS NEXT STEP.
I/NotificationManager( 2100): com.android.bluetooth: cancelAll by com.android.bluetooth
D/CellBroadcastReceiver( 3618): onReceive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.cellbroadcastreceiver/.CellBroadcastReceiver (has extras) }
V/BluetoothOppNotification( 2100): send message
D/CellBroadcastReceiver( 3618): ACTION_BOOT_COMPLETED received.
D/BluetoothOppPreference( 2100): Dumping Names:  
,D/BluetoothOppPreference( 2100): {}
D/BluetoothOppPreference( 2100): Dumping Channels:  
D/BluetoothOppPreference( 2100): {}
D/OppService( 2100): Start()
W/BluetoothOPPServiceJni( 2100): initOppNative
D/BluetoothOPPServiceJni( 2100): initOppNative(L383): OPP
I/bluedroid( 2100): get_profile_interface opp
I/bt-btif ( 2100): btif_op_get_interface
D/BluetoothOPPServiceJni( 2100): initOppNative(L411): mOppCallbacksObj 3147002
D/BluetoothOPPServiceJni( 2100): initOppNative(L413): calling OPP init
I/bt-btif ( 2100): btif_opp_init
D/bt-btif ( 2100): btif_enable_service: current services:0xa0667330
D/BluetoothOPPServiceJni( 2100): initOppNative(L429): OPC and OPS init Succesful
D/BluetoothOPPServiceJni( 2100): initOppNative(L430): mOppCallbacksObj 3147002
V/OppService( 2100): setOppService(): set to: com.broadcom.bt.service.opp.OppService@30f352d9
D/BluetoothAdapterService( 2100): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@116ef0db
D/BluetoothAdapterService(292483291)( 2100): handleMessage() - Message: 1
D/BluetoothAdapterService(292483291)( 2100): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(292483291)( 2100): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
D/BluetoothAdapterState( 2100): isTurningOnRadio()=false
D/BluetoothAdapterState( 2100): isTurningOffRadio()=false
D/BluetoothAdapterState( 2100): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2100): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2100): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/OppService( 2100): pendingUpdate is :  true
D/BluetoothAdapterService( 2100): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothA2dp( 2100): Proxy object connected
,D/LGBluetoothPowerControlManager( 2100): [BTUI] onServiceConnected : Got BluetoothA2dp: android.bluetooth.BluetoothA2dp@27ae949e
D/BluetoothAdapterService(292483291)( 2100): handleMessage() - Message: 1
D/BluetoothAdapterService(292483291)( 2100): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(292483291)( 2100): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/BluetoothAdapterState( 2100): isTurningOnRadio()=false
D/BluetoothAdapterState( 2100): isTurningOffRadio()=false
D/BluetoothAdapterState( 2100): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2100): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2100): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/HeadsetStateMachine( 2100): Disconnected process message: 10, size: 0
D/HeadsetPhoneState( 2100): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/BluetoothAdapterService( 2100): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(292483291)( 2100): handleMessage() - Message: 1
D/BluetoothAdapterService(292483291)( 2100): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(292483291)( 2100): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
D/BluetoothAdapterState( 2100): isTurningOnRadio()=false
D/BluetoothAdapterState( 2100): isTurningOffRadio()=false
D/BluetoothAdapterState( 2100): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2100): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2100): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/HeadsetStateMachine( 2100): Disconnected process message: 11, size: 0
V/OppService( 2100): Deleted complete outbound shares, number =  0
,D/BluetoothAdapterService( 2100): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(292483291)( 2100): handleMessage() - Message: 1
D/BluetoothAdapterService(292483291)( 2100): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(292483291)( 2100): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
D/BluetoothAdapterState( 2100): isTurningOnRadio()=false,
D/BluetoothAdapterState( 2100): isTurningOffRadio()=false
D/BluetoothAdapterState( 2100): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2100): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2100): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/OppService( 2100): Deleted complete inbound failed shares, number = 0
,V/BluetoothOppProvider( 2100): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
D/BluetoothAdapterService( 2100): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothOppProvider( 2100): created cursor android.database.sqlite.SQLiteCursor@3bbd4395 on behalf of 
D/BluetoothAdapterService(292483291)( 2100): handleMessage() - Message: 1
D/BluetoothAdapterService(292483291)( 2100): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
V/BluetoothOppProvider( 2100): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/BluetoothAdapterService(292483291)( 2100): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
D/BluetoothAdapterState( 2100): isTurningOnRadio()=false
D/BluetoothAdapterState( 2100): isTurningOffRadio()=false
D/BluetoothAdapterState( 2100): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2100): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2100): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/CellBroadcastAlertService( 3618): myUid on onStartCommand() =0
V/BluetoothOppProvider( 2100): created cursor android.database.sqlite.SQLiteCursor@346b5caa on behalf of 
V/BluetoothOppNotification( 2100): update too frequent, put in queue
D/CellBroadcastAlertService( 3618): [MmsConfig] isSupportEmotionalLED=true
D/BluetoothAdapterService( 2100): Profile still not running:com.broadcom.bt.service.opp.OppService
V/PanService( 2100): [BTUI] SIM Extra State :ABSENT
D/BluetoothAdapterService(292483291)( 2100): handleMessage() - Message: 1
D/BluetoothAdapterService(292483291)( 2100): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(292483291)( 2100): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=true
D/BluetoothAdapterState( 2100): isTurningOnRadio()=false
D/BluetoothAdapterState( 2100): isTurningOffRadio()=false
D/BluetoothAdapterState( 2100): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2100): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2100): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
V/OppService( 2100): pendingUpdate is :  false
D/BluetoothAdapterService( 2100): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 2100): Handler(): got msg=1
E/OppService( 2100): UpdateThread is Completed
D/BluetoothAdapterService(292483291)( 2100): handleMessage() - Message: 1
D/BluetoothAdapterService(292483291)( 2100): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(292483291)( 2100): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
D/BluetoothAdapterState( 2100): isTurningOnRadio()=false
D/BluetoothAdapterState( 2100): isTurningOffRadio()=false
D/BluetoothAdapterState( 2100): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2100): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2100): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 2100): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(292483291)( 2100): handleMessage() - Message: 1
D/BluetoothAdapterService(292483291)( 2100): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(292483291)( 2100): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState( 2100): isTurningOnRadio()=false
D/BluetoothAdapt,erState( 2100): isTurningOffRadio()=false
D/BluetoothAdapterState( 2100): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2100): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2100): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 2100): Profile still not running:com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(292483291)( 2100): handleMessage() - Message: 1
D/BluetoothAdapterService(292483291)( 2100): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(292483291)( 2100): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, doUpdate=true
D/BluetoothAdapterState( 2100): isTurningOnRadio()=false
D/BluetoothAdapterState( 2100): isTurningOffRadio()=false
D/BluetoothAdapterState( 2100): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2100): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2100): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService( 2100): Profile still not running:com.broadcom.bt.service.opp.OppService
V/BluetoothOppNotification( 2100): new notify threadi!
V/BluetoothOppNotification( 2100): send delay message
D/BluetoothAdapterService(292483291)( 2100): handleMessage() - Message: 1
D/BluetoothAdapterService(292483291)( 2100): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(292483291)( 2100): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=12, doUpdate=true
D/BluetoothAdapterState( 2100): isTurningOnRadio()=false
D/BluetoothAdapterState( 2100): isTurningOffRadio()=false
D/BluetoothAdapterState( 2100): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2100): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2100): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=12, Bluetooth isTurningOff=false,Bluetooth isTurningOn=true
D/BluetoothAdapterService(292483291)( 2100): onProfileServiceStateChange() - All profile services started.
V/OppService( 2100): ContentObserver received notification
D/BluetoothAdapterState( 2100): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 2100): enable
V/OppService( 2100): ContentObserver received notification
I/bt-btif ( 2100): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 2100): VERSION AFBT-LREL-30_00.06 (BTE: BTE0322_00.20.00)
V/BluetoothOppProvider( 2100): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/OppService( 2100): pendingUpdate is :  true
V/BluetoothOppProvider( 2100): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 2100): created cursor android.database.sqlite.SQLiteCursor@1d6e709b on behalf of 
I/GKI_LINUX( 2100): gki_task_entry task_id=0 [BTU] starting
I/bt-btu  ( 2100): btu_task pending for preload complete event
I/bt_hci_bdroid( 2100): init
I/bt_vendor( 2100): init
I/bt_vnd_conf( 2100): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 2100): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
I/bt-btif ( 2100): libbt-hci init returns 0
V/BluetoothOppNotification( 2100): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 2100): created cursor android.database.sqlite.SQLiteCursor@21375c38 on behalf of 
V/OppService( 2100): pendingUpdate is :  false
E/OppService( 2100): UpdateThread is Completed
V/BluetoothOppProvider( 2100): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 2100): created cursor android.database.sqlite.SQLiteCursor@dfb8411 on behalf of 
V/BluetoothOppNotification( 2100): outbound: succ-0  fail-0
I/ActivityManager(  856): Start proc com.lge.email for broadcast com.lge.email/.ui.widget.EmailWidgetProvider: pid=3652 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/NotificationManager( 2100): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothSapReceiver( 2100): [BTUI] checkServiceStart
V/BluetoothOppNotification( 2100): outbound notification was removed.
D/CellBroadcastAlertService( 3618): [CB] getEmotionalLEDEffectEnabled= true
V/BluetoothOppProvider( 2100): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
D/LGBluetoothStateChangeReceiver( 2100): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
I/CellBroadcastAlertService( 3618): startEmotionalLedService 
I/CellBroadcastAlertService( 3618): registerLEDObserver
I/CellBroadcastAlertService( 3618): registerLEDObserver REGISTER
V/BluetoothOppProvider( 2100): created cursor android.database.sqlite.SQLiteCursor@c7a9976 on behalf of 
V/BluetoothOppNotification( 2100): inbound: succ-0  fail-0
D/CellBroadcastAlertService( 3618): make mBroadcastDb
I/NotificationManager( 2100): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 2100): inbound notification was removed.
V/BluetoothOppProvider( 2100): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 2100): created cursor android.database.sqlite.SQLiteCursor@12397b77 on behalf of 
,D/CellBroadcastAlertService( 3618): after ACTION_BOOT_COMPLETED cursor, Db closed!!
I/bt_userial_vendor( 2100): userial vendor open: opening /dev/ttyHS99
,D/bt_userial_vendor( 2100): userial_vendor_open():UART is setup
I/bt_userial_vendor( 2100): device fd = 67 open
I/ActivityManager(  856): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=3669 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/Scheduler( 1761): Use legacy PeriodicScheduler
,D/bt_hwcfg( 2100): hw_config_cback opcode:0x0c03
D/bt_hwcfg( 2100): hw_config_cback state=1
D/bt_hwcfg( 2100): hw_config_cback opcode:0x0c14
D/bt_hwcfg( 2100): hw_config_cback state=4
D/bt_hwcfg( 2100): Chipset Name: BCM4334B0
D/bt_hwcfg( 2100): Chipset BCM4334B0
D/bt_hwcfg( 2100): Target name = [BCM4334B0]
I/bt_hwcfg( 2100): Found patchfile: /system/bin//BCM4334B0_002.001.013.1820.2163.hcd
,D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 2100): hw_config_cback state=2
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 2100): hw_config_cback state=3
I/bt_hwcfg( 2100): bt vendor lib: set UART baud 4000000
W/ResourcesManager( 3652): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3652): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 3652): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/InstanceID/Rpc( 1761): Found 10006
I/ApplicationLogger( 2054): logEvent(): Logged 1852 bytes in 3599 ms
,D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc2e
D/bt_hwcfg( 2100): hw_config_cback state=5
I/art     ( 2279): Explicit concurrent mark sweep GC freed 36682(2MB) AllocSpace objects, 35(560KB) LOS objects, 24% free, 12MB/16MB, paused 926us total 119.558ms
,I/Icing   ( 2279): Indexing done 0A5267A505F47CB39AEB664724AACA2991DAA8A8
W/ResourcesManager( 3669): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/ActivityManager(  856): Killing 3485:com.android.providers.partnerbookmarks/u0a71 (adj 15): empty #11
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
,D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/LGBluetoothProfileConnectionReceiver_EasySetting( 3669): [BTUI] STATE_OFF or STATE_TURNING_ON : reset connected device information EasySettings
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
,D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
,D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
W/libprocessgroup(  856): failed to open /acct/uid_10071/pid_3485/cgroup.procs: No such file or directory
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/AuthorizationBluetoothService( 1761): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
I/LGEmail ( 3652): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
,D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
I/ActivityManager(  856): Killing 3507:com.lge.eula/1000 (adj 15): empty #11
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/LGEmail ( 3652): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
,D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
,D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
,D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
W/libprocessgroup(  856): failed to open /acct/uid_1000/pid_3507/cgroup.procs: No such file or directory
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
E/ConnectivityChangeReceiver( 2279): Ignoring connectivity change
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
,D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
,D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/ConnectivityService(  856): listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  856): dumpNetworkRequest
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/ConnectivityService(  856):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityService(  856):     Requests:
D/ConnectivityService(  856):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  856):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/ConnectivityService(  856):     Lingered:
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/ConnectivityService(  856): handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  856): apparently satisfied.  currentScore=60
D/ConnectivityService(  856): sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/ConnectivityManager.CallbackHandler( 2279): CM callback handler got msg 524290
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
,D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
,D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
,D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
,D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
,D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
,D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
,D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
,D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
I/ActivityManager(  856): Start proc com.lge.mlt for broadcast com.lge.mlt/.MptOnBootReceiver: pid=3694 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
I/ActivityManager(  856): Killing 2412:com.android.defcontainer/u0a4 (adj 15): empty #11
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
,D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4c
D/bt_hwcfg( 2100): hw_config_cback state=6
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc4e
D/bt_hwcfg( 2100): hw_config_cback state=6
W/libprocessgroup(  856): failed to open /acct/uid_10004/pid_2412/cgroup.procs: No such file or directory
,W/DriveInitializer( 2279): Awaiting to be initialized
,W/DriveInitializer( 2279): Background init thread started
I/bt_hwcfg( 2100): bt vendor lib: set UART baud 115200
D/bt_hwcfg( 2100): Settlement delay -- 100 ms
I/bt_hwcfg( 2100): Setting fw settlement delay to 100 
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.gms/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2279): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc45
D/bt_hwcfg( 2100): hw_config_cback state=2
,D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc18
D/bt_hwcfg( 2100): hw_config_cback state=7
I/bt_hwcfg( 2100): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 2100): Setting local bd addr to F8:95:C7:87:85:54
D/bt_hwcfg( 2100): hw_config_cback opcode:0xfc01
D/bt_hwcfg( 2100): hw_config_cback state=8
I/bt_hwcfg( 2100): vendor lib fwcfg completed
I/bt-btif ( 2100): HC preload_cb 0 [0:SUCCESS 1:FAIL]
,I/bt-btu  ( 2100): btu_task received preload complete event
I/        ( 2100): BTE_InitTraceLevels -- TRC_HCI,2
I/        ( 2100): BTE_InitTraceLevels -- TRC_L2CAP,2
I/        ( 2100): BTE_InitTraceLevels -- TRC_RFCOMM,2
I/        ( 2100): BTE_InitTraceLevels -- TRC_OBEX,2
I/        ( 2100): BTE_InitTraceLevels -- TRC_AVCT,2
I/        ( 2100): BTE_InitTraceLevels -- TRC_AVDT,2
I/        ( 2100): BTE_InitTraceLevels -- TRC_AVRC,2
I/        ( 2100): BTE_InitTraceLevels -- TRC_AVDT_SCB,2
I/        ( 2100): BTE_InitTraceLevels -- TRC_A2D,2
I/        ( 2100): BTE_InitTraceLevels -- TRC_BNEP,2
I/        ( 2100): BTE_InitTraceLevels -- TRC_BTM,2
I/        ( 2100): BTE_InitTraceLevels -- TRC_GAP,2
I/        ( 2100): BTE_InitTraceLevels -- TRC_PAN,2
I/        ( 2100): BTE_InitTraceLevels -- TRC_SAP,2
I/        ( 2100): BTE_InitTraceLevels -- TRC_SDP,2
I/        ( 2100): BTE_InitTraceLevels -- TRC_GATT,2
I/        ( 2100): BTE_InitTraceLevels -- TRC_SMP,2
,I/        ( 2100): BTE_InitTraceLevels -- TRC_BTAPP,3
I/        ( 2100): BTE_InitTraceLevels -- TRC_BTIF,3
I/        ( 2100): BTE_InitTraceLevels -- TRC_PROTOCOL,0
W/ContextImpl( 3694): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.mlt.MptOnBootReceiver.onReceive:107 android.app.ActivityThread.handleReceiver:2663 
W/DriveInitializer( 2279): Background init thread ended
,I/ActivityManager(  856): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3726 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 304us total 21.377ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 21.926ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 20.435ms
E/MPT MptOnPowerWatcher( 3694): MptOnPowerWatcher
,E/dbFlushManager( 3694): Handler is not ready.
E/dbFlushManager( 3694): It's going to sleep routine until the message handler is generated.
,E/bt-btif ( 2100): bta_dm_ctrl_features_rd_cmpl_cback Ctrl BLE feature read failed: status :1
I/GKI_LINUX( 2100): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 2100): warning : media task started media_task_refcnt 1 
E/bt-btif ( 2100): Calling BTA_HhEnable
E/bt-btif ( 2100): btif_storage_get_adapter_property service_mask:0x1201c8
I/bt-btif ( 2100): HAL bt_hal_cbacks->adapter_properties_cb
W/bt-smp  ( 2100): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 2100): Plain text(LSB ~ MSB) = c5 7c 71 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2100): Encrypted text(LSB ~ MSB) = de b7 7f 0f 03 bc a8 20 fb 7a fd 5e 03 e2 09 c1 
D/BT_PROF_AUDIO( 2100): created moving average (N=100)
D/BT_PROF_AUDIO( 2100): reset rate average
W/bt-btif ( 2100): overflow 0, enter 0, exit 0
W/bt-btm  ( 2100): Stopping oneshot timer
D/BluetoothAdapterProperties( 2100): Address is:F8:95:C7:87:85:54
D/BluetoothAdapterProperties( 2100): Name is: G3s-1
D/BluetoothManagerService(  856): Bluetooth Adapter name changed to G3s-1
D/BluetoothManagerService(  856): Stored Bluetooth name: G3s-1
D/BluetoothAdapterProperties( 2100): Scan Mode:20
D/BluetoothAdapterProperties( 2100): Discoverable Timeout:120
E/bt-btif ( 2100): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
E/bt-btif ( 2100): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
E/bt-btif ( 2100): btif_sock_init: !radio_req && !rfc_init
,I/bt-btif ( 2100): BTA_JvEnable
E/bt-btif ( 2100): btsock_vendor_hci_init: !vhci_init
D/bt-btif ( 2100): btsock_ctrl_hci_init(L191): poll handle:6
D/bt-btif ( 2100): init_hci_slots(L136): in
D/IOP_DB_BT( 2100): db_open: file /etc/bluetooth/iop_bt.db
D/IOP_DB_BT( 2100): db_open: db_open : handle 2691110876l, read 11046 bytes onto local cache
D/IOP_DB_BT( 2100): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 2100): db_query: result 1
I/        ( 2100): iop_db_open: iop_db_open status 0
,E/bt-btif ( 2100): btif_sock_init, radio_req:0, rfc_init:1, vhci_init:1
D/bt-btif ( 2100): btsock_ctrl_hci_init(L191): poll handle:6
I/bt-btif ( 2100): bta_pan_co_init
D/bte_conf( 2100): Device ID record 1 : primary
D/bte_conf( 2100):   vendorId            = 00c4
D/bte_conf( 2100):   vendorIdSource      = 0001
D/bte_conf( 2100):   product             = 13a1
D/bte_conf( 2100):   version             = 1000
D/bte_conf( 2100):   clientExecutableURL = 
D/bte_conf( 2100):   serviceDescription  = 
D/bte_conf( 2100):   documentationURL    = 
D/bte_conf( 2100): bte_load_did_conf no section named DID2.
I/bt-btif ( 2100): HAL bt_hal_cbacks->adapter_state_changed_cb
E/bt-btif ( 2100): btif_hf_upstreams_evt: wrong handle = 12346 
I/bt-btif ( 2100): HAL bt_op_callbacks->opc_state_cb
D/BluetoothOPPServiceJni( 2100): opc_state_cb(L140):  opc_state_cb state:0
D/OppService( 2100): onOpcStateChange()
I/bt-btif ( 2100): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 2100): ops_state_cb(L223):  ops_state_cb state:0
D/OppService( 2100): onOpsStateChange() :0
I/bt-btif ( 2100): HAL bt_fts_callbacks->operation_cmpl_cb
D/BluetoothFTPServiceJni( 2100): operation_cmpl_callback(L192):  oper:3 status:0
I/BluetoothFTPService( 2100): onFtpServerEnabled: /storage
D/BluetoothPanServiceJni( 2100): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan,
D/BluetoothAdapterState( 2100): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 2100): ScanMode =  20
D/BluetoothAdapterProperties( 2100): State =  11
D/BluetoothAdapterProperties( 2100): mDiscoverableTimeout = 120
D/BluetoothAdapterProperties( 2100): Setting state to 12
I/BluetoothAdapterState( 2100): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService(292483291)( 2100): updateAdapterState() - Broadcasting state to 1 receivers.
I/bt-btif ( 2100): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterState( 2100): Entering On State
D/BluetoothManagerService(  856): Message: 60
D/BluetoothManagerService(  856): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
I/BluetoothAdapterState( 2100): Entering On State from state = 11
D/BluetoothManagerService(  856): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothAdapterProperties( 2100): Scan Mode:21
I/bt-btif ( 2100): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothAdapterProperties( 2100): Discoverable Timeout:120
D/BluetoothA2dp(  856): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1795): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1795): onBluetoothStateChange: up=true
D/BluetoothA2dp( 2100): onBluetoothStateChange: up=true
,D/BluetoothAdapterService(292483291)( 2100): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e9dc689,
D/BluetoothAdapterService(292483291)( 2100): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(292483291)( 2100): autoConnect() - Initiate auto connection on BT on...
D/BluetoothAdapterService( 2100): [BTUI] autoConnect() : not allowed,
D/BluetoothHeadset( 1795): onBluetoothStateChange: up=true
D/BluetoothHeadset(  856): onBluetoothStateChange: up=true
,D/LGBluetoothServiceAdapter( 2100): [BTUI] OnState
D/LGBluetoothServiceAdapter( 2100): [BTUI]         global_name: G3s-1
D/LGBluetoothServiceAdapter( 2100): [BTUI]         local_name: G3s-1
D/OppService( 2100): Recieved MESSAGE_OPC_ENABLE,
D/BluetoothAdapterService(292483291)( 2100): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e9dc689
D/BluetoothAdapterService(292483291)( 2100): isQuetModeEnabled() - Enabled = false
D/BluetoothAdapterService(292483291)( 2100): autoConnect() - Initiate auto connection on BT on...
,D/BluetoothAdapterService( 2100): [BTUI] autoConnect() : not allowed
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
D/LGBluetoothFeatureConfig( 2100): isPrivacyLogsEnabled : true
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/OppService( 2100): Recieved MESSAGE_OPS_ENABLE
E/BluetoothManagerService(  856): Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
,D/BluetoothManagerService(  856): Bluetooth State Change Intent: 11 -> 12
D/BluetoothManagerService(  856): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  856): Message: 40
,D/BluetoothManagerService(  856): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/LGBluetoothAPIService( 1883): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/bt_h4   ( 2100): vendor lib postload completed
,D/LGBluetoothAPIService( 1883): Message: 1
D/LGBluetoothAPIService( 1883): MESSAGE_BOOT_COMPLETED
,I/LGBluetoothAPIService( 1883): [BTUI] LGBluetoothAPIService Binding Success
D/BluetoothAdapterService(292483291)( 2100): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e9dc689
I/BluetoothMapService( 2100): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 2100): STATE_ON
W/ContextImpl( 3262): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/LGBluetoothAPIServer( 2100): [BTUI] onCreate()
,D/LGBluetoothAPIServer( 2100): [BTUI] onBind()
D/BluetoothAdapterService(292483291)( 2100): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e9dc689
D/BluetoothAdapterService(292483291)( 2100): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e9dc689
D/LGBluetoothAPIService( 1883): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1883): Message: 100
D/LGBluetoothAPIService( 1883): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
I/[SystemUI]QuickSettingsHandler( 1390): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1390): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
E/MPT MptOnPowerWatcher( 3694): startListen
,D/BluetoothAdapterService( 2100): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@116ef0db
V/BluetoothPbapService( 2100): Pbap Service onCreate
V/BluetoothPbapService( 2100): Starting PBAP service
D/BluetoothAdapterService(292483291)( 2100): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e9dc689
D/LGBluetoothPbapAdapter( 2100): [BTUI] getInstance : create
V/BluetoothMapService( 2100): Handler(): got msg=1
D/BluetoothMapMasInstance( 2100): Map Service startRfcommSocketListener
V/BluetoothPbapService( 2100): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 2100): state: 12
D/BluetoothMapMasInstance( 2100): MAS initSocket()
D/BluetoothMapMasInstance( 2100):   masId = 00
D/BluetoothMapMasInstance( 2100):   msgTypes = 0e
D/BluetoothMapMasInstance( 2100):   masName = SMS/MMS
D/BluetoothMapMasInstance( 2100):   SDP string = 000eSMS/MMS
V/BluetoothPbapReceiver( 2100): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 2100): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 2100): ***********state = 12
D/BluetoothManagerService(  856): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,V/BluetoothPbapService( 2100): Handler(): got msg=1
V/BluetoothPbapService( 2100): Pbap Service startRfcommSocketListener
,V/BluetoothPbapService( 2100): Pbap Service initSocket
W/BluetoothAdapter( 2100): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothAdapterService(292483291)( 2100): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e9dc689
D/BluetoothManagerService(  856): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 2100): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 2100): BTA_JvCreateRecordByUser
D/LGBluetoothServiceAdapter( 2100): [BTUI] createSocketChannel FD=83 mFd=0
I/bt-btif ( 2100): BTA_JvRfcommStartServer
V/BluetoothMapMasInstance( 2100): Succeed to create listening socket 
I/bt-btif ( 2100): BTA_JvCreateRecordByUser
D/BluetoothMapMasInstance( 2100): Accepting socket connection...
I/bt-btif ( 2100): BTA_JvRfcommStartServer
D/LGBluetoothServiceAdapter( 2100): [BTUI] createSocketChannel FD=85 mFd=83
D/LocalBluetoothProfileManager( 3262): Adding local A2DP profile
V/BluetoothPbapService( 2100): Succeed to create listening socket 
V/BluetoothPbapService( 2100): Accepting socket connection...
V/BluetoothOppNotification( 2100): new notify threadi!
V/BluetoothOppNotification( 2100): send delay message
,V/BluetoothOppProvider( 2100): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
D/BluetoothManagerService(  856): Message: 30
I/NotificationManager(  856): android: cancelAsUser(353845882) by android
D/LocalBluetoothProfileManager( 3262): Adding local HEADSET profile
V/BluetoothOppProvider( 2100): created cursor android.database.sqlite.SQLiteCursor@96ed702 on behalf of 
,D/BluetoothManagerService(  856): Message: 30
V/BluetoothOppNotification( 2100): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 2100): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,D/BluetoothManagerService(  856): Message: 30
V/BluetoothOppProvider( 2100): created cursor android.database.sqlite.SQLiteCursor@17405813 on behalf of 
V/BluetoothOppNotification( 2100): outbound: succ-0  fail-0
I/NotificationManager( 2100): com.android.bluetooth: cancel(-1000005) by com.android.bluetooth
V/BluetoothOppNotification( 2100): outbound notification was removed.
V/BluetoothOppProvider( 2100): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 2100): created cursor android.database.sqlite.SQLiteCursor@32ed7a50 on behalf of 
V/BluetoothOppNotification( 2100): inbound: succ-0  fail-0
I/NotificationManager( 2100): com.android.bluetooth: cancel(-1000006) by com.android.bluetooth
V/BluetoothOppNotification( 2100): inbound notification was removed.
V/BluetoothOppProvider( 2100): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 2100): created cursor android.database.sqlite.SQLiteCursor@3441a449 on behalf of 
,I/ActivityManager(  856): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=3770 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/BluetoothManagerService(  856): Message: 30
,D/LocalBluetoothProfileManager( 3262): Adding local MAP profile
D/BluetoothMap( 3262): Create BluetoothMap proxy object
D/BluetoothManagerService(  856): Message: 30
,D/BluetoothManagerService(  856): Message: 30
D/LocalBluetoothProfileManager( 3262): LocalBluetoothProfileManager construction complete
V/BluetoothPbapService( 2100): Pbap Service onBind
D/LGBluetoothUserBindClient( 3262): [BTUI] initUserBindClient
,W/ContextImpl( 3262): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,D/DockEventReceiver( 3262): finishStartingService: stopping service
D/BluetoothA2dp( 3262): Proxy object connected
D/A2dpProfile( 3262): Bluetooth service connected
,D/BluetoothAdapterService(292483291)( 2100): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e9dc689
D/BluetoothHeadset( 3262): Proxy object connected
D/HeadsetProfile( 3262): Bluetooth service connected
D/BluetoothAdapterService(292483291)( 2100): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e9dc689
D/BluetoothInputDevice( 3262): Proxy object connected
D/HidProfile( 3262): Bluetooth service connected
D/BluetoothAdapterService(292483291)( 2100): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e9dc689
D/BluetoothPan( 3262): BluetoothPAN Proxy object connected
,D/PanProfile( 3262): Bluetooth service connected
D/BluetoothAdapterService(292483291)( 2100): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e9dc689
D/BluetoothMap( 3262): Proxy object connected
D/MapProfile( 3262): Bluetooth service connected
D/BluetoothMap( 3262): getConnectedDevices()
D/BluetoothAdapterService(292483291)( 2100): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e9dc689
,V/BluetoothMapService( 2100): getConnectedDevices()
D/BluetoothPbap( 3262): Proxy object connected
D/PbapServerProfile( 3262): Bluetooth service connected
D/LGBluetoothUserBindClient( 3262): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 3262): onReceive
D/LGBluetoothFeatureConfig( 3262): isPrivacyLogsEnabled : true
,V/BluetoothOppReceiver( 2100): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
V/BluetoothOppManager( 2100): restoreApplicationData! falsefalsenullnull
,W/ResourcesManager( 3770): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
V/BluetoothSapReceiver( 2100): [BTUI] checkServiceStart
D/LGBluetoothStateChangeReceiver( 2100): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
D/AuthorizationBluetoothService( 1761): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/art     ( 2078): Explicit concurrent mark sweep GC freed 3057(120KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 706us total 41.661ms
,I/RlzPingService( 3726): Setting next ping for 1453132593134
,I/art     (  856): Explicit concurrent mark sweep GC freed 15355(741KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.170ms total 150.868ms
D/CalendarProvider2( 3770): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@3f3ae692
I/ActivityManager(  856): Killing 3378:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  856): failed to open /acct/uid_10018/pid_3378/cgroup.procs: No such file or directory
,D/CalendarProvider2( 3770): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 3770): Created com.android.providers.calendar.CalendarAlarmManager@375e97bf(com.android.providers.calendar.CalendarProvider2@3f3ae692)
D/CalendarReceiver( 3770): [onReceive] intent = Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.providers.calendar/.CalendarReceiver (has extras) }
D/CalendarReceiver( 3770): [onReceive] WakeLock new : CalendarReceiver_Provider, ReferenceCounted = true
,D/CalendarReceiver( 3770): [onReceive] WakeLock acquire : CalendarReceiver_Provider
D/CalendarReceiver( 3770): [onReceive] android.intent.action.BOOT_COMPLETED
D/CalendarProvider2( 3770): Scheduling check of next Alarm
D/CalendarProvider2( 3770): SCHEDULE_ALARM_REMOVE
D/CalendarReceiver( 3770): [onReceive] WakeLock release : CalendarReceiver_Provider
,I/ActivityManager(  856): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.receiver.DmReceiver: pid=3801 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
E/LAlarm  (  856): Service started flags 0 startId 3
V/AlarmManager(  856): RTC_WAKEUP set : Alarm{85fb8d8 type 0 when 1452527793319 com.google.android.googlequicksearchbox} when 1452527793319
,W/ContextImpl( 3801): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmNotiService.bootCompleted:575 com.lge.lgdmsclient.receiver.DmReceiver.onReceive:94 
,E/LGDMClient( 3801): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 3801): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 3801): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_BOOTUP_COMPLETE
D/LGDMClient( 3801): [DmUtil.java] [removeSilenceBootFile()] : [894] : Try to remove a Silence file
,D/LGDMClient( 3801): [DmNotiService.java] [actionSystemBootComplete()] : [459] : CHECK_AUTO_UPDATE_PROCESS : 0 Call removeSilenceBootFile() 
I/LGDMClient( 3801): [DmNotiService.java] [actionSystemBootComplete()] : [467] : DM Service on boot completed
,D/LGDMClient( 3801): [DmClientController.java] [startService()] : [400] : startService(), DownloadService will be started in order to follow the start of DmClientController
W/ContextImpl( 3801): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.controller.DmClientController.startService:404 com.lge.lgdmsclient.dmclient.controller.DmClientController.getInstance:345 com.lge.lgdmsclient.service.DmNotiService.actionSystemBootComplete:474 
,I/ActivityManager(  856): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=3825 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
D/LGDMClient( 3801): [DmAgent.java] [<init>()] : [164] : DmAgent is started -> DmConstants.DMAgentState.mDmaState = 0
,D/LGDMClient( 3801): [DmClientController.java] [run()] : [178] : LooperSTART
I/LGDMClient( 3801): [DmCAConfigParser.java] [getInstance()] : [73] : DmsCAConfigParser sInstance null
,D/LGDMClient( 3801): [DmPhoneSpecificInfo.java] [getPhoneSpecificInfo()] : [204] : Current MultiSimEnabled is false
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
D/LGDMClient( 3801): [DmPhoneSpecificInfo.java] [getPhoneSpecificInfo()] : [239] : getPhoneSpecificInfo: sim mccmnc(),spn(),gid(null),imsi(null)
I/LGDMClient( 3801): [DmCAConfigParser.java] [parse()] : [108] : parse
D/LGDMClient( 3801): [DmCAConfigParser.java] [setDefaultProfile()] : [490] : setDefaultProfile
D/LGDMClient( 3801): [DmCAConfigParser.java] [setDefaultProfile()] : [493] : filename : fota_dm_settings.xml
D/LGDMClient( 3801): [DmCAConfigParser.java] [setDefaultProfile()] : [506] : [UI4.1] Search [fota_dm_settings.xml]
D/LGDMClient( 3801): [DmCAConfigParser.java] [parse()] : [134] : [UI4.1] Search [fota_dm_settings.xml]
,D/ALBootInit( 3825): ====action==>android.intent.action.BOOT_COMPLETED
D/LGDMClient( 3801): [DmAgentUtil.java] [setAutoAgentSchedule()] : [117] : IN setAutoAgentSchedule()
D/ALBootInit( 3825): Alarm ALBootInit: BOOT_COMPLETED
,I/ALProvider( 3825): delete where======= time <= 1452527793590  and  aindex > 0
D/LGDMClient( 3801): [DmAgentUtil.java] [setAutoAgentSchedule()] : [126] :  cursor != null setAutoAgentSchedule()
,D/Alarms  ( 3825):  --- disableExpiredAlarms!!! isBooting : true
D/LGDMClient( 3801): [DmAgentUtil.java] [setAutoAgentSchedule()] : [167] : SET ALARM setAutoAgentSchedule() = 20160114T212428
D/LGDMClient( 3801): [DmAgentUtil.java] [setAutoAgentSchedule()] : [185] : OUT setAutoAgentSchedule()
D/LGDMClient( 3801): [DmAgent.java] [checkPostponed()] : [2062] : DMAGentState is: DmConstants.DMAgentState.mDmaState = 0
V/LGDMClient( 3801): [DmClientController.java] [handleMessage()] : [181] : DmClientController: run() - msg.what=31
D/LGDMClient( 3801): [DmAgent.java] [processRestartHandler()] : [1241] : DMAGentState is: DmConstants.DMAgentState.mDmaState = 0
D/Alarms  ( 3825): count ===>0
E/LGDMClient( 3801): [DmDownloadService.java] [onCreate()] : [56] : DmDownloadService.onCreate()
D/LGDMClient( 3801): [DmDownloadService.java] [onStartCommand()] : [92] : DmDownloadService.onStartCommand()
,D/LGDMClient( 3801): [DmDownloadService.java] [handleStart()] : [103] : DmDownloadService  intend : Intent { cmp=com.lge.lgdmsclient/.service.DmDownloadService }
D/Alarms  ( 3825): snoozeActivating scount==>0
D/Alarms  ( 3825): [setNextAlert] start
E/[LGE_FOTA] ( 3801): FOTA JNI_OnLoad
E/[LGE_FOTA] ( 3801):  FOTAJNI_GetUAResult in
E/[LGE_FOTA] ( 3801): FOTAFS_Open /cache/fota/usd.dat, 0, handle : 1c
E/[LGE_FOTA] ( 3801): enUpdateState                : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.enState             : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgOffset[0]     : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgSize[0]       : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgOffset[1]     : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgSize[1]       : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgOffset[2]     : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgSize[2]       : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgOffset[3]     : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgSize[3]       : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgOffset[4]     : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgSize[4]       : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgOffset[5]     : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgSize[5]       : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgOffset[6]     : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgSize[6]       : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgOffset[7]     : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgSize[7]       : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgOffset[8]     : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgSize[8]       : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgOffset[9]     : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgSize[9]       : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgOffset[10]     : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgSize[10]       : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgOffset[11]     : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgSize[11]       : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgOffset[12]     : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgSize[12]       : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgOffset[13]     : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgSize[13]       : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgOffset[14]     : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgSize[14]       : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgOffset[15]     : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiPkgSize[15]       : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiCurrSection       : 0x00000000
E/[LGE_FOTA] ( 3801): stFWInfo.uiResult            : 0x00000000
E/[LGE_FOTA] ( 3801): stFSInfo.enState             : 0x00000000
E/[LGE_FOTA] ( 3801): stFSInfo.uiFilePackageOffset : 0xa0a637d4
E/[LGE_FOTA] ( 3801): stFSInfo.uiFilePackageSize   : 0xa0a637f4
E/[LGE_FOTA] ( 3801): stFSInfo.uiResult            : 0x00000000
D/Alarms  ( 3825): [setNextAlert] (1)
E/[LGE_FOTA] ( 3801): stPkgInfo.enPackageType      : 0x00000000
E/[LGE_FOTA] ( 3801): stPkgInfo.uiSize             : 0x00000000
E/[LGE_FOTA] ( 3801): stPkgInfo.uiWrittenAddr      : 0x00000000
E/[LGE_FOTA] ( 3801): stPkgInfo.uiWrittenSize      : 0x00000000
E/[LGE_FOTA] ( 3801): stPkgInfo.szPackagePath      : 
E/[LGE_FOTA] ( 3801): stCommand.enCommand	 		: 0x00000000
E/[LGE_FOTA] ( 3801): uiBackupBufferAddr			: 0x00000000
E/[LGE_FOTA] ( 3801): uiLanguage					: 0x00000000
E/[LGE_FOTA] ( 3801): stDebug.uiResetCount			: 0x00000000
E/[LGE_FOTA] ( 3801): stDebug.uiRetryCount			: 0x00000000
E/[LGE_FOTA] ( 3801): FOTAFS_Close 1c
E/[LGE_FOTA] ( 3801): FOTAJNI_GetConvertedUAResult : 450
E/[LGE_FOTA] ( 3801): FOTAJNI_GetUAResult : 450
D/LGDMClient( 3801): [SwUpdate.java] [getSwUpdateStatus()] : [244] : Software update result:450
D/LGDMClient( 3801): [DmAgent.java] [restartIdleSession()] : [1084] : skymymy is: iSwUpdateStatus = 450, isUpgradedByLGUP() = false
D/LGDMClient( 3801): [DmAgent.java] [clearContext()] : [1774] : [Enter] clearContext
D/Alar,ms  ( 3825):  minTime  = 0
D/Alarms  ( 3825):  -- OK multi -- 0
,E/jeny.kim( 3825): [setNextAlert] setNextAlert  temp_Alarmlink + 
E/jeny.kim( 3825): [setNextAlert]setNextAlert temp_AlarmLinkText + 
I/LGDMClient( 3801): [DmAgent.java] [setState()] : [1875] : Setting Agent State and State is : DmConstants.DMAgentState.mDmaState = 0
D/LGDMClient( 3801): [DmAgent.java] [clearContext()] : [1791] : [Exit] clearContext
,V/LGDMClient( 3801): [DmClientController.java] [handleMessage()] : [181] : DmClientController: run() - msg.what=33
D/LGDMClient( 3801): [DmClientController.java] [stopService()] : [408] : stopDownloadService(), DownloadService will be stopped in order to follow the end of DmClientController
W/ContextImpl( 3801): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1804 android.content.ContextWrapper.stopService:520 com.lge.lgdmsclient.dmclient.controller.DmClientController.stopService:412 com.lge.lgdmsclient.dmclient.controller.DmClientController.clearController:383 com.lge.lgdmsclient.dmclient.controller.DmClientController.access$200:68 
D/LGDMClient( 3801): [DmDownloadService.java] [onDestroy()] : [117] : DmDownloadService.onDestroy()
I/ActivityManager(  856): Killing 3539:com.android.keychain/1000 (adj 15): empty #11
I/CommonUtil( 3825): BUILD Operator: OPEN
W/libprocessgroup(  856): failed to open /acct/uid_1000/pid_3539/cgroup.procs: No such file or directory
D/Alarms  ( 3825): broadcastToWidgetProvider : false
,D/Alarms  ( 3825): Enter formatDayAndTime(final Context context, long timeInMiliSec)
V/SettingsProvider(  856): call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,D/CommonUtil( 3825): Enter deleteUnnecessaryToneItem() enter excepted tone uri value is null, preferparent value is  ALARM
D/CommonUtil( 3825): deleteUnnecessaryToneItem() -> Alarm Surviv Count is 0
D/CommonUtil( 3825): Exit deleteUnnecessaryToneItem()
,I/CommonUtil( 3825): BUILD Country: EU
I/TimerReceiver( 3825): onReceiveIntent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.lge.clock/.timer.TimerReceiver (has extras) }
D/TimerReceiver( 3825): onReceive() : android.intent.action.BOOT_COMPLETED
,I/TimerReceiver( 3825): setTimerDone
,D/TimerObj( 3825): --------------------- getTimersFromSharedPrefs
V/TimerObj( 3825): --------------------- timers list is empty
I/ActivityManager(  856): Start proc com.lge.appbox.client:SingleBinaryService for broadcast com.lge.appbox.client/com.lge.appbox.singlebinary.SimChangeReceiver: pid=3850 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  856): Killing 3454:com.lge.hiddenmenu/1000 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_1000/pid_3454/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/AppUp4:AppBoxApplication( 3850): AppBoxApplication onCreate()
,D/AppUp4:SingleBinary( 3850): /cust/OPEN_EU/config/app-enabled-conf.json is selected!!
,D/AppUp4:SingleBinary( 3850):  Starting isFingerChanged 
,I/ActivityManager(  856): Start proc com.lge.appbox.client for content provider com.lge.appbox.client/com.lge.appbox.databases.AppBoxContentProvider: pid=3873 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/AppUp4:AppBoxCP( 3873): onCreate
W/AppUp4:DB( 3873):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 3873):  setFingerPrint start
I/AppUp4:DB( 3873):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 3873):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 3873):  SDK version = 0
I/AppUp4:DB( 3873):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 3873): AppBoxApplication onCreate()
,D/AppUp4:SingleBinary( 3850):  The value of isFingerChanged null
D/AppUp4:SingleBinary( 3850): Device : jagnm
D/AppUp4:SingleBinary( 3850): First Boot - ignore boot completed
,D/AppUp4:NTCodeSingleBinary( 3850): Starting isFingerChanged 
D/AppUp4:NTCodeSingleBinary( 3850): The value of isFingerChanged lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
,D/AppUp4:SingleBinary( 3850): Device : jagnm
D/AppUp4:SingleBinary( 3850): Config file is not exist - nothing
I/ActivityManager(  856): Killing 3591:com.google.android.onetimeinitializer/u0a8 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_10008/pid_3591/cgroup.procs: No such file or directory
,I/AppUp4:SDKReflector( 3873): +myUserId : 0
D/AppUp4:BootUpPollingReceiver( 3873): onReceive on user ID : 0
V/AppUp4:FotaPlusService( 3873):  isFotaPlusTriedOnce : true
,D/AppUp4:BootUpPollingReceiver( 3873): Starting getSdkVersion 
D/AppUp4:BootUpPollingReceiver( 3873): SDK version is : 0
D/AppUp4:BootUpPollingReceiver( 3873): currentSdkVersion : 0
D/AppUp4:BootUpPollingReceiver( 3873): isSdkVersionChanged : true
V/AppUp4:FotaPlusService( 3873):  setFotaPlusCompleted : false
D/AppUp4:BootUpPollingReceiver( 3873): isFotaPlusNeeded : true
D/AppUp4:BootUpPollingReceiver( 3873): Fota Plus already tried once, show notification
V/NotificationService(  856): enqueueNotificationInternal: pkg=com.lge.appbox.client id=22319582 notification=Notification(pri=0 contentView=null vibrate=default sound=default defaults=0x3 flags=0x2 color=0x00000000 vis=PRIVATE)
,D/ZenLog  (  856): intercepted: 0|com.lge.appbox.client|22319582|null|10011,none
V/NotificationService(  856): pkg=com.lge.appbox.client canInterrupt=false intercept=true
I/NotificationServiceEx(  856): LED remove() : mLights=0|com.lge.appbox.client|22319582|null|10011
D/NotificationServiceEx(  856): updateLightListLocked :r=0|com.lge.appbox.client|22319582|null|10011, action=2
D/NotificationServiceEx(  856): notification=Notification(pri=0 contentView=null vibrate=default sound=default defaults=0x3 flags=0x2 color=0x00000000 vis=PRIVATE)
D/AppUp4:BootUpPollingReceiver( 3873): isFotaPlusRunning after : true
D/AppUp4:BootUpPollingReceiver( 3873):  installPreloadedValuePackIfNeeded 
D/AppUp4:BootUpPollingReceiver( 3873):  file is : /system/apps/bootup
D/AppUp4:BootUpPollingReceiver( 3873): file false
D/AppUp4:BootUpPollingReceiver( 3873): [BootUpPollingReceiver] No preload installation.
D/SmartCoverUpdateMonitor( 1348): onNotificationPosted() : StatusBarNotification(pkg=com.lge.appbox.client user=UserHandle{0} id=22319582 tag=null score=0 key=0|com.lge.appbox.client|22319582|null|10011: Notification(pri=0 contentView=com.lge.appbox.client/0x1090079 vibrate=default sound=default defaults=0x3 flags=0x2 color=0x00000000 vis=PRIVATE))
,D/SmartCoverUpdateMonitor( 1348): onNotificationPosted() !qcn.isEnableToShowNotification()
,D/AppUp4:dwnld( 3873): [removeAllIncompletedDownload] ... 
,V/AppUp4:BootUpPollingReceiver( 3873): [BootUpPollingReceiver] start bootup Polling.
,D/AppUp4  ( 3873): getUpdatePollingPeriod
D/AppUp4  ( 3873): getUpdatePollingPeriod
,I/[SystemUI]PhoneStatusBar( 1390): updateMediaMetaData(false): mMediaMetadata = null
D/AppUp4:BackgroundPollingService ( 3873): register polling alarm when : 2016/01/14 21:32:00
D/AppUp4:LightWeightPollingService ( 3873):  [buildRemotePollingIntent]
D/AppUp4:LightWeightPollingService ( 3873): This means remote config is N, so skip it
I/ActivityManager(  856): Killing 3558:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_10023/pid_3558/cgroup.procs: No such file or directory
,I/ActivityManager(  856): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3905 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/MmsConfig( 3185): isNotAllowedSms: currentUser:0
D/MmsConfig( 3185): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3185): isUserMode:false
D/SmsReceiverService( 3185): handleMessage isUserMode:false
W/ResourcesManager( 3185): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
V/SmsReceiverService( 3185): handleMessage action: android.intent.action.BOOT_COMPLETED error: 0
,W/ResourcesManager( 3905): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/AudioFlinger(  284): thread 0xb5651000 type 0 TID 1314 going to sleep
V/AudioFlinger(  284): thread 0xb56eb000 type 0 TID 1315 going to sleep
V/AudioFlinger(  284): thread 0xb5735000 type 0 TID 1317 going to sleep
,I/CalendarProvider2( 3770): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 3770): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  856): Killing 3618:com.android.cellbroadcastreceiver/u0a16 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_10016/pid_3618/cgroup.procs: No such file or directory
,D/CalendarApplication( 3905): CalendarApplication.onCreate()
D/PreferenceKeysParser( 3905): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 3905): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@3e1c7c60, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@32466519, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@251cd9de, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@375e97bf, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@23cfe8c, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@35cf39d5, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@1c98b5ea, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@116ef0db, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@1e017778, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@17d69e51, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@e4446b6, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@761bfb7, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@2b929324, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@2815ce8d, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@4461842, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@3248a053, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@1cf7bd90, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@3e9dc689, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@12a1768e, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@20b2eeaf, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@3b4322bc, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@9934245, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@38426d9a, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@10c9c6cb, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@2c7daea8, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3aaabdc1, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@4c9c966, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@302c04a7, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@2c530d54, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@106474fd, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@f1915f2, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@3d8a4443, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@237daac0, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@370863f9, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@89e9f3e, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@2802e19f, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@9f2b2ec, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@3d6246b5, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3961714a, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@83df8bb, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@3fce11d8, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@193d9931
D/GeneralP,referenceUtils( 3905): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 3905): [init]
,I/Config  ( 3905): LGCalendar ver.4.40.17
I/Config  ( 3905): start check model
I/Config  ( 3905): start check native_ca
,I/Config  ( 3905): Config Operator=OPEN, Country=EU
D/Config  ( 3905): [setDefaultValuesToPref]
D/Config  ( 3905): [parseProfiles]
D/ProfilesParser( 3905): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 3905): [debug_displayParseInfos] profile.operator = null
D/Config  ( 3905): [updateProfiletoCountryInfo]
D/GeneralPreference( 3905): [checkAndMigrateOldPreference]
D/AlertReceiver( 3905): onReceive: a=android.intent.action.BOOT_COMPLETED Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.calendar/.alerts.AlertReceiver (has extras) }
,D/UsbSettingsReceiver( 3262): [AUTORUN] onReceive() : action = android.intent.action.BOOT_COMPLETED
D/UsbSettingsReceiver( 3262): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 3262): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 3262): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 3262): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 3262): [AUTORUN] setTetherStatus() : status=false
D/UsbSettingsReceiver( 3262): [AUTORUN] onReceive() : android.intent.action.BOOT_COMPLETED
D/UsbSettingsReceiver( 3262): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 3262): [AUTORUN] sys.usb.state = ptp_only,adb
,D/UsbSettingsReceiver( 3262): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/StoreModeReceiver( 3262): intent.getAction() : android.intent.action.BOOT_COMPLETED
D/StoreModeReceiver( 3262): sim state :null
D/StoreModeReceiver( 3262): Back LED don't supported.
V/SettingsProvider(  856): call_put(system:emotional_led_back_led=0) for 0 calling package = com.android.settings
V/SettingsProvider(  856): call_put(system:emotional_led_back_incoming_call=0) for 0 calling package = com.android.settings
V/SettingsProvider(  856): call_put(system:emotional_led_back_alarm=0) for 0 calling package = com.android.settings
V/SettingsProvider(  856): call_put(system:emotional_led_back_missed_call=0) for 0 calling package = com.android.settings
,V/SettingsProvider(  856): call_put(system:emotional_led_back_missed_messages=0) for 0 calling package = com.android.settings
V/SettingsProvider(  856): call_put(system:emotional_led_back_missed_emails=0) for 0 calling package = com.android.settings
V/SettingsProvider(  856): call_put(system:emotional_led_back_calendar_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  856): call_put(system:emotional_led_back_voice_recording=0) for 0 calling package = com.android.settings
V/SettingsProvider(  856): call_put(system:emotional_led_back_camera_timer_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  856): call_put(system:emotional_led_back_camera_face_detecting_noti=0) for 0 calling package = com.android.settings
V/SettingsProvider(  856): call_put(system:notification_light_pulse_back=0) for 0 calling package = com.android.settings
D/StoreModeReceiver( 3262): SystemProperty Default brightness value [0-255] : 143
D/StoreModeReceiver( 3262): Default brightness[0-255] : 143
W/ResourcesManager( 3262): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/StoreModeReceiver( 3262): Default Screen off timeout value : 30000
D/StoreModeReceiver( 3262): SystemProperty Default brightness Mode value[true/false] : false
D/StoreModeReceiver( 3262): BRIGHTNESS_MODE - 0
D/StoreModeReceiver( 3262): Default brightness Mode [0/1] : 0
D/StoreModeReceiver( 3262): Default NIGHT_MODE : 0
D/StoreModeReceiver( 3262): Set MaxBrightness : 255
,E/PhoneInterfaceManager( 1795): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
D/StoreModeReceiver( 3262): getPhoneNumber is empty
D/StoreModeReceiver( 3262): go to StoreModeCheck()
D/StoreModeReceiver( 3262): isStoremode not null
D/PhoneInterfaceManager( 1795): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
V/SettingsProvider(  856): call_put(system:shop_mode_check=1) for 0 calling package = com.android.settings
D/StoreModeReceiver( 3262): product_name : jagnm_global_com
,D/StoreModeReceiver( 3262): Store mode start!
V/SettingsProvider(  856): call_put(system:shop_mode=1) for 0 calling package = com.android.settings
V/SettingsProvider(  856): call_put(system:shop_mode_check=1) for 0 calling package = com.android.settings
I/PowerManagerService(  856): ALS enabled for SRE
D/PowerManagerServiceEx(  856): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x1, nextTimeout=120000 (in 70531 ms)
D/StoreModeReceiver( 3262): setBrightness() : NoMultiALC=255
W/ContextImpl( 3262): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.StoreModeReceiver.sendBroadcast:500 com.android.settings.StoreModeReceiver.setMode:473 
V/SettingsProvider(  856): call_put(system:screen_brightness_mode=0) for 0 calling package = com.android.settings
D/SettingsProvider(  856): Set screen_off_timeout in entry value : 120000
V/SettingsProvider(  856): call_put(system:screen_off_timeout=120000) for 0 calling package = com.android.settings
V/SettingsProvider(  856): call_put(system:screen_brightness=255) for 0 calling package = com.android.settings
V/SettingsProvider(  856): call_put(system:check_night_mode=0) for 0 calling package = com.android.settings
,D/SettingBootReceiver( 3262): onReceive
,D/SettingBootReceiver( 3262): Boot Completed intent received, action=android.intent.action.BOOT_COMPLETED
D/SettingBootReceiver( 3262): setStyle()
I/[SystemUI]LGBootReceiver( 1390): onReceive = android.intent.action.BOOT_COMPLETED
,I/[SystemUI]LGPowerUI( 1390): onReceive = com.lge.statusbar.bootcompleted
D/SettingBootReceiver( 3262): SettingStyle=1
I/[SystemUI]PhoneStatusBar( 1390): got ACTION_STICKY_BOOT_COMPLETED
,I/BOOT    ( 1390): got ACTION_STICKY_BOOT_COMPLETED
D/SettingBootReceiver( 3262): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
D/SettingBootReceiver( 3262): setAccountMenu()
D/TAG     ( 3262): setKidsMode
D/TAG     ( 3262): mIsOwner, setKidsMode
D/SettingBootReceiver( 3262): setAccountMenu()
,D/SettingBootReceiver( 3262): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
D/SettingBootReceiver( 3262): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
D/YSY     ( 3262): not support Quiet mode notification
I/InitNotificationRingtoneService( 3905): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 3905): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
W/HolidayIntentService( 3905): onHandleIntent
D/HolidayDataLoader( 3905): readJsonAsset : holiday.json
I/ActivityManager(  856): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3931 uid=10111 gids={50111, 9997, 1028, 3003} abi=armeabi-v7a
,V/SettingsProvider(  856): call_put(system:gentle_vibration_status=1) for 0 calling package = com.android.settings
,D/AlertService( 3905): 0 Action = android.intent.action.BOOT_COMPLETED
D/AlertService( 3905): [Widget]com.android.calendar.widget.CalendarAppWidgetProvider enabled
I/AlertUtils( 3905): [getCalendarNotiSoundURIFromCursor] getCount()= 21
V/SettingsProvider(  856): call_put(system:smart_ringtone=0) for 0 calling package = com.android.settings
D/Feature ( 3905): MemoryLevel - 5:NOT_DEF:Not UI4.2 LOS
,D/AlertService( 3905): [Widget]com.android.calendar.widget.MonthWidgetProvider enabled
D/AlertService( 3905): [Widget]com.android.calendar.widget.WeekWidgetProvider enabled
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
D/SettingBootReceiver( 3262): timezoneID is null
,I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/SettingBootReceiver( 3262): disable au
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/TAG     ( 3262): disable WirelessSettingsActivity
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/TAG     ( 3262): disable SKTPhoneMode
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
D/AlertService( 3905): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
E/HolidayIntentService( 3905): onHandleIntent:holiday data empty
,I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,D/SettingBootReceiver( 3262): [Nightmode] Enter receiver
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
D/AlarmScheduler( 3905): No events found starting within 1 week.
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
D/SettingBootReceiver( 3262): [Nightmode] BOOT_COMPLETED
,D/NightModeInfo( 3262): [Nightmode] setNightNodeTabSettings
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3905): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,D/NightModeInfo( 3262): [Nightmode] getAlreadyNightModeDB() : 0
D/NightModeInfo( 3262): [Nightmode] getUserBrightnessChange() : 0
I/AlertUtils( 3905): set default noti to content://media/internal/audio/media/38
D/NightModeInfo( 3262): [Nightmode] getUserBrightnessChangeNoNight() : 0
V/SettingsProvider(  856): call_put(system:already_night_mode=0) for 0 calling package = com.android.settings
,V/SettingsProvider(  856): call_put(system:user_change_brightness=0) for 0 calling package = com.android.settings
V/SettingsProvider(  856): call_put(system:user_change_brightness_no_night=0) for 0 calling package = com.android.settings
V/SettingsProvider(  856): call_put(system:night_mode_enabled=0) for 0 calling package = com.android.settings
D/NightModeInfo( 3262): [Nightmode] setTabNightCheck : 0
V/SettingsProvider(  856): call_put(system:save_tab_night_check=0) for 0 calling package = com.android.settings
I/InitNotificationRingtoneService( 3905): End InitializeAlertRingtoneService.onHandleIntent
,D/NightModeInfo( 3262): [Nightmode] cancelPendingIntent
V/DownloadManager( 3206): Received broadcast intent for android.intent.action.BOOT_COMPLETED
V/DownloadManager( 3206): DownloadService onCreate
,D/NightModeInfo( 3262): [Nightmode] requestPendingIntent
D/NightModeInfo( 3262): [Nightmode] setAlarmStart~!!~!!~!!
I/DownloadManager( 3206): in removeSpuriousFiles
D/NightModeInfo( 3262): [Nightmode] currentHour > 6
V/DownloadManager( 3206): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/NightModeInfo( 3262): [Nightmode] currentHour > 6
I/NotificationManager( 3206): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3206): created cursor android.database.sqlite.SQLiteCursor@3b4322bc on behalf of 3206
I/NightModeInfo( 3262): JW getStartTime201601120000
D/NightModeInfo( 3262): [Nightmode] setAlarmEnd~!!~!!~!!
I/DownloadManager( 3206): in trimDatabase
V/DownloadManager( 3206): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/NightModeInfo( 3262): [Nightmode] currentHour > 6
D/NightModeInfo( 3262): [Nightmode] currentHour > 6
V/DownloadManager( 3206): created cursor android.database.sqlite.SQLiteCursor@9934245 on behalf of 3206
I/NightModeInfo( 3262): JW getEndTime201601120600
D/NightModeInfo( 3262): [Nightmode] currentHour > 6
I/NightModeInfo( 3262): getStartTime201601120000
D/NightModeInfo( 3262): [Nightmode] currentHour > 6
I/NightModeInfo( 3262): getEndTime201601120600
D/jw      ( 3262): Only VZW Supported end return
V/DownloadManager( 3206): DownloadService onStartCommand
,V/DownloadManager( 3206): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/ActivityManager(  856): Killing 3652:com.lge.email/u0a21 (adj 15): empty #11
D/MediaScannerReceiver( 3206): [MediaScanner] ACTION_BOOT_COMPLETED scan INTERNAL_VOLUME, EXTERNAL_VOLUME
V/DownloadManager( 3206): created cursor android.database.sqlite.SQLiteCursor@2c7daea8 on behalf of 3206
,W/libprocessgroup(  856): failed to open /acct/uid_10021/pid_3652/cgroup.procs: No such file or directory
,V/DownloadManager( 3206): DownloadService onDestroy
D/MediaScannerService( 3206): [MediaScanner] start scanning volume internal: [/system/media, /oem/media, /cust/OPEN_EU/media]
V/LGMediaProvider( 3206): insertInternal: content://media/none/media_scanner, initValues=volume=internal
,D/MediaScannerService( 3206): [MediaScanner] scan() ACTION_MEDIA_SCANNER_STARTED uri : file:///system/media
D/MtpService( 3206): updating state; isCurrentUser=true, mMtpLocked=false
,D/MtpService( 3206): addStorageLocked 65537 /storage/emulated/0
D/WiseScreenService( 1911): [OnBootReceiver.java:24:onReceive()] iKeepScreenOn: 0
D/WiseScreenService( 1911): [OnBootReceiver.java:28:onReceive()] iSmartVideo: 0
W/ContextImpl( 1911): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1804 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.lge.keepscreenon.OnBootReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2663 
E/MtpStorageEx( 3206): setAccessCapability false
D/MediaScannerEx( 3206): [MediaScanner] scanDirectories()[0] = /system/media
D/MediaScannerEx( 3206): [MediaScanner] scanDirectories()[1] = /oem/media
D/MediaScannerEx( 3206): [MediaScanner] scanDirectories()[2] = /cust/OPEN_EU/media
I/MusicBrowser( 2730): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///system/media flg=0x10 }}
,I/MusicBrowser( 2730): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2730): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_STARTED
I/ActivityManager(  856): Start proc com.lge.voicerecorder for broadcast com.lge.voicerecorder/.bookmarkdb.BootCompletedReceiver: pid=3958 uid=10034 gids={50034, 9997, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,D/MtpService( 3206): updating state; isCurrentUser=true, mMtpLocked=false
I/art     ( 3206): Thread[1,tid=3206,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
,V/MediaScannerClient( 3206): [MediaScanner]setLocale: = en_US
E/MediaProfilesEx-JNI( 3206): register_com_lge_media_MediaProfilesEx
,E/MediaRecorderEx-JNI( 3206): register_com_lge_media_MediaRecorderEx
D/AudioSystemEx( 3206): register_com_lge_media_LGAudioSystem
E/SurfaceControlEx( 3206): register_com_lge_view_SurfaceControlEx
I/art     ( 3206): Thread[1,tid=3206,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
D/LGMtpDatabaseJNI( 3206): register_android_mtp_LGMtpDatabase
D/LGMtpServerJNI( 3206): register_android_mtp_LGMtpServer
I/art     ( 3206): Thread[1,tid=3206,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
E/MediaPlayerEx-jni( 3206): register_com_lge_view_MediaPlayerEx
I/art     ( 3206): Thread[1,tid=3206,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
D/        ( 3206): register_com_lge_emoji_EmojiUtil
E/LGMtpDatabaseJNI( 3206): android_mtp_LGMtpDatabase_setup
D/MtpService( 3206): starting MTP server in PTP mode
D/LGMtpServer( 3206): LGMtpServer
D/LGMtpServerJNI( 3206): android_mtp_LGMtpServer_setup
,E/MediaFileEx( 3206): Duplicate type = AVI
E/MediaFileEx( 3206): Duplicate type = ASF
D/MtpService( 3206): addStorageLocked 65537 /storage/emulated/0
E/MtpStorageEx( 3206): setAccessCapability false
D/MtpServerEx( 3206): ANR FIX - addStorage!
D/LGMtpServerJNI( 3206): android_mtp_LGMtpServer_run
V/MediaScannerClient( 3206): [MediaScanner]setLocale: = en_US
W/MediaScanner( 3206): Error opening directory '/oem/media/', skipping: No such file or directory.
V/MediaScannerClient( 3206): [MediaScanner]setLocale: = en_US
W/MediaScanner( 3206): Error opening directory '/cust/OPEN_EU/media/', skipping: No such file or directory.
,D/LGMediaProvider( 3206): [MediaScanner] delete() uri = content://media/internal/file
D/LGMediaProvider( 3206): [MediaScanner] delete() completed notifyChange, uri = content://media/internal
V/MediaScannerEx( 3206): [MediaScanner] isInternalStorage : true
V/MediaScannerEx( 3206): [MediaScanner] isInternalStorage : true
V/MediaScannerEx( 3206): [MediaScanner] isInternalStorage : true
D/MediaScanner( 3206): [MediaScanner] prescan time: 72ms
D/MediaScanner( 3206): [MediaScanner] scan time: 32ms
D/MediaScanner( 3206): [MediaScanner] postscan time: 7ms
D/MediaScanner( 3206): [MediaScanner] total time: 111ms
D/LGMediaProvider( 3206): [MediaScanner] delete() uri = content://media/none/media_scanner
I/VRBookmarkProvider( 3958): [BookmarkProvider.java:76:<init>()-[Thread:Other] BookmarkProvider
,I/VRBookmarkProvider( 3958): [BookmarkProvider.java:254:onCreate()-[Thread:Other] onCreate
I/VRBookmarkProvider( 3958): [BookmarkProvider.java:504:registerObservers()-[Thread:Other] registerObservers : content://media/external/audio/media
D/MediaScannerService( 3206): [MediaScanner] scan() Send Intent ACTION_MEDIA_SCANNER_FINISHED uri : file:///system/media
,I/MusicBrowser( 2730): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 }}
D/LGMediaProvider( 3206): [MediaScanner] mUnmountReceiver ACTION_MEDIA_SCANNER_FINISHED : uri = file:///system/media, path = /system/media
I/MusicBrowser( 2730): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MediaScannerService( 3206): [MediaScanner] done scanning volume internal
D/MusicBrowser( 2730): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_FINISHED
D/MediaScannerService( 3206): [MediaScanner] start scanning volume external: [/storage/emulated/0, /storage/external_SD]
V/LGMediaProvider( 3206): insertInternal: content://media/none/media_scanner, initValues=volume=external
I/MusicBrowser( 2730): [MediaPlaybackService.java:reloadQueue()] oooooo 
D/MusicBrowser( 2730): [MediaPlaybackService.java:reloadQueue()] oooooo id=-1
D/MusicBrowser( 2730): [MediaPlaybackService.java:reloadQueue()] oooooo mCardId=-1
D/MusicBrowser( 2730): [MediaPlaybackService.java:reloadQueue()] oooooo mPreferences.id=-1
D/MusicBrowser( 2730): [MediaPlaybackService.java:reloadQueue()] oooooo q=
D/MusicBrowser( 2730): [MediaPlaybackService.java:reloadQueue()] oooooo q.length=0
D/MusicBrowser( 2730): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.queuechanged}
I/MusicBrowser( 2730): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
,D/MusicBrowser( 2730): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2730): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2730): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2730): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2730): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2730): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2730): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2730): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicBrowser( 2730): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2730): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/MusicWidget( 2681): intentReceiver onReceive() action::com.lge.music.queuechanged
I/MusicWidget( 2681): beingMusicWidget_4x2() result::false
I/MusicWidget( 2681): beingMusicWidget_Quick() result::false
I/MusicWidget( 2681): beingMusicWidget_4x1() result::true
D/MusicBrowser( 2730): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2730): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2730): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
D/MusicBrowser( 2730): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.metachanged}
I/MusicBrowser( 2730): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
I/MusicWidget( 2681): send mDelayedStopHandler
D/MusicBrowser( 2730): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
I/MusicWidget( 2681): performViewUpdater handleMessage() msg.what::3
D/MusicBrowser( 2730): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2730): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
I/MusicWidget( 2681): beingMusicWidget_Quick() result::false
D/MusicBrowser( 2730): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2730): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2730): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2730): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2730): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicBrowser( 2730): [MediaPlaybackService.java:3426:notifyChange()] oooooo mRemoteControlClient.editMetadata :: META_CHANGED 
I/MusicWidget( 2681): intentReceiver onReceive() action::com.lge.music.metachanged
I/MusicBrowser( 2730): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=false}
I/MusicWidget( 2681): beingMusicWidget_4x2() result::false
I/MusicBrowser( 2730): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
,I/MusicBrowser( 2730): [MediaPlaybackService.java:9999:run()] oooooo AlbumImageUpdater() run :: Start
I/MusicBrowser( 2730): [MediaPlaybackService.java:10051:run()] oooooo AlbumImageUpdater() run :: End
I/MusicWidget( 2681): beingMusicWidget_Quick() result::false
I/MusicWidget( 2681): beingMusicWidget_4x1() result::true
I/MusicWidget( 2681): send mDelayedStopHandler
I/MusicWidget( 2681): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2681): beingMusicWidget_Quick() result::false
D/MusicBrowser( 2730): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2730): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2730): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2730): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2730): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
I/MusicBrowser( 2730): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
I/art     (  856): Explicit concurrent mark sweep GC freed 12874(581KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.247ms total 134.916ms
,D/MediaScannerService( 3206): [MediaScanner] scan() ACTION_MEDIA_SCANNER_STARTED uri : file:///storage/emulated/0
I/MusicBrowser( 2730): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///storage/emulated/0 flg=0x10 }}
D/VRBootCompletedReceiver( 3958): [BootCompletedReceiver.java:25:onReceive()-[Thread:Other] Controller has been started on Boot complete
V/LGMediaProvider( 3206): insertInternal: content://media/, initValues=name=external
I/MusicBrowser( 2730): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2730): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_STARTED
I/MusicWidget( 2681): _mediaDataObserver onChange()
I/MusicWidget( 2681): beingMusicWidget_4x2() result::false
D/VRBootCompletedReceiver( 3958): [BootCompletedReceiver.java:47:onReceive()-[Thread:Other] Voice Recorder launcher enable(1)/disable(2) : 1
,D/MediaScannerEx( 3206): [MediaScanner] scanDirectories()[0] = /storage/emulated/0
D/MediaScannerEx( 3206): [MediaScanner] scanDirectories()[1] = /storage/external_SD
I/ActivityManager(  856): Killing 3726:com.google.android.partnersetup/u0a9 (adj 15): empty #11
W/MusicBrowser( 2730): - Start trace [MusicUtils.query]---------------------------------------------------------------
W/MusicBrowser( 2730): [Line 003751] MusicUtils.java, query() : MusicUtils.query
W/MusicBrowser( 2730): [Line 003761] MusicUtils.java, isMediaScannerScanning() : MusicUtils.query
W/MusicBrowser( 2730): [Line 001991] MediaPlaybackService.java, onChange() : MusicUtils.query
W/MusicBrowser( 2730): [Line 000130] ContentObserver.java, onChange() : MusicUtils.query
W/MusicBrowser( 2730): - End   trace [MusicUtils.query]---------------------------------------------------------------
W/VRBookmarkProvider( 3958): [BookmarkProvider.java:546:onChange()-[Thread:Other] Data Change!! false url : content://media/
W/libprocessgroup(  856): failed to open /acct/uid_10009/pid_3726/cgroup.procs: No such file or directory
,D/LGBootCompleteReceiver( 1795): onReceive : android.intent.action.BOOT_COMPLETED
D/ConfigUtils( 1795): setUsimOperator() : card operator = 
D/ConfigUtils( 1795): setUsimOperator() : result = null
D/ConfigUtils( 1795): setUsimOperator() : simOperator = 
D/ConfigUtils( 1795): setUsimOperator() : usimoperator = 0
D/ConfigUtils( 1795): setSupportedUsimMobilityForVoLTE() : false
,I/MusicWidget( 2681): performViewUpdater handleMessage() msg.what::0
I/MusicWidget( 2681): beingMusicWidget_4x1() result::true
I/MusicWidget( 2681): performUpdate()_4x1
I/MusicWidget( 2681): defaultAppWidget()_4x1
D/ConfigUtils( 1795): This Model Voice Clarity Support : false
D/LGBootCompleteReceiver( 1795): onReceive : updateCallrejectNotify rejectCallOption : 1
I/MusicWidget( 2681): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2681): 4x1_currentTheme :: null
I/MusicWidget( 2681): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2681): setDefaultViewLayoutId()_4x1
D/CallRejectInfoToNotify( 1795): update : tPhoneMode : false
I/NotificationManager( 1795): com.android.phone: cancel(2131493582) by com.android.phone
,I/MusicWidget( 2681): appWidgetViewUpdate()_4x1
I/MusicWidget( 2681): linkButtons()_4x1
I/PhoneApp( 1795): saveDefaultRingtoneUriOfOwner = content://media/internal/audio/media/55
I/MusicWidget( 2681): pushUpdate()_4x1
I/art     ( 3206): Explicit concurrent mark sweep GC freed 14797(795KB) AllocSpace objects, 6(96KB) LOS objects, 24% free, 8MB/10MB, paused 454us total 53.902ms
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1966): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/ActivityManager(  856): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=3983 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/MediaScannerClient( 3206): [MediaScanner]setLocale: = en_US
,I/MusicWidget( 2681): performViewUpdater handleMessage() msg.what::1
I/MusicWidget( 2681): beingMusicWidget_4x2() result::false
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1966): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/iu.UploadsManager( 2279): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,V/DrmBroadcastReceiver( 3983): Receive ACTION_BOOT_COMPLETED
,D/MediaScannerEx( 3206): [MediaScanner] beginFile() path = /storage/emulated/0/QuicksetLite Setup/data
V/DrmService( 3983): Service onCreate
D/DrmService( 3983): Received new request = 4
V/MediaScannerClient( 3206): [MediaScanner]setLocale: = en_US
W/MediaScanner( 3206): Error opening directory '/storage/external_SD/', skipping: Permission denied.
,D/LGMediaProvider( 3206): [MediaScanner] delete() uri = content://media/external/file
D/DrmServiceHandler( 3983): updateDrmPushNotification() : No notification
D/DrmService( 3983): Completed !! request = 4
D/DrmService( 3983): Request count = 0
I/MusicWidget( 2681): _mediaDataObserver onChange()
W/MusicBrowser( 2730): - Start trace [MusicUtils.query]---------------------------------------------------------------
W/VRBookmarkProvider( 3958): [BookmarkProvider.java:546:onChange()-[Thread:Other] Data Change!! false url : content://media/external
W/MusicBrowser( 2730): [Line 003751] MusicUtils.java, query() : MusicUtils.query
W/MusicBrowser( 2730): [Line 003761] MusicUtils.java, isMediaScannerScanning() : MusicUtils.query
W/MusicBrowser( 2730): [Line 001991] MediaPlaybackService.java, onChange() : MusicUtils.query
W/MusicBrowser( 2730): [Line 000130] ContentObserver.java, onChange() : MusicUtils.query
W/MusicBrowser( 2730): - End   trace [MusicUtils.query]---------------------------------------------------------------
W/VRBookmarkProvider( 3958): [BookmarkProvider.java:563:onChange()-[Thread:Other] EXTERNAL Change!!
I/MusicWidget( 2681): beingMusicWidget_4x2() result::false
D/LGMediaProvider( 3206): [MediaScanner] delete() completed notifyChange, uri = content://media/external
V/MediaScanner( 3206): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@370863f9
V/MediaScanner( 3206): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@370863f9
D/MediaScanner( 3206): [MediaScanner] prescan time: 151ms
D/MediaScanner( 3206): [MediaScanner] scan time: 88ms
D/MediaScanner( 3206): [MediaScanner] postscan time: 11ms
D/MediaScanner( 3206): [MediaScanner] total time: 250ms
,D/LGMediaProvider( 3206): [MediaScanner] delete() uri = content://media/none/media_scanner
D/MediaScannerService( 3206): [MediaScanner] scan() Send Intent ACTION_MEDIA_SCANNER_FINISHED uri : file:///storage/emulated/0
,I/ActivityManager(  856): Start proc com.lge.cloudhub for broadcast com.lge.cloudhub/.service.CloudHubReceiver: pid=4003 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/MusicBrowser( 2730): [MediaPlaybackService.java:1995:onChange()] oooooo 
,D/LGMediaProvider( 3206): [MediaScanner] mUnmountReceiver ACTION_MEDIA_SCANNER_FINISHED : uri = file:///storage/emulated/0, path = /storage/emulated/0
V/DrmService( 3983): Service onDestroy
I/ActivityManager(  856): Killing 3669:com.lge.settings.easy/1000 (adj 15): empty #11
D/MediaScannerService( 3206): [MediaScanner] done scanning volume external
V/MusicBrowser( 2730): [MediaPlaybackService.java:5808:getPath()] oooooo {mFileToPlay=null}
I/MusicBrowser( 2730): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 }}
I/MusicBrowser( 2730): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2730): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_FINISHED
W/libprocessgroup(  856): failed to open /acct/uid_1000/pid_3669/cgroup.procs: No such file or directory
,I/MusicBrowser( 2730): [MediaPlaybackService.java:reloadQueue()] oooooo 
D/MusicBrowser( 2730): [MediaPlaybackService.java:reloadQueue()] oooooo id=-1
D/MusicBrowser( 2730): [MediaPlaybackService.java:reloadQueue()] oooooo mCardId=-1
D/MusicBrowser( 2730): [MediaPlaybackService.java:reloadQueue()] oooooo mPreferences.id=-1
D/MusicBrowser( 2730): [MediaPlaybackService.java:reloadQueue()] oooooo q=
D/MusicBrowser( 2730): [MediaPlaybackService.java:reloadQueue()] oooooo q.length=0
D/MusicBrowser( 2730): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.queuechanged}
I/MusicBrowser( 2730): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2730): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2730): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2730): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2730): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2730): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2730): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2730): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2730): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicBrowser( 2730): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2730): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
,D/MusicBrowser( 2730): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2730): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2730): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicWidget( 2681): intentReceiver onReceive() action::com.lge.music.queuechanged
I/MusicWidget( 2681): beingMusicWidget_4x2() result::false
D/MusicBrowser( 2730): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.metachanged}
I/MusicWidget( 2681): beingMusicWidget_Quick() result::false
I/MusicWidget( 2681): beingMusicWidget_4x1() result::true
I/MusicBrowser( 2730): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
I/MusicWidget( 2681): send mDelayedStopHandler
I/MusicWidget( 2681): performViewUpdater handleMessage() msg.what::3
D/MusicBrowser( 2730): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2730): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2730): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2730): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
I/MusicWidget( 2681): beingMusicWidget_Quick() result::false
D/MusicBrowser( 2730): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2730): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
I/iu.UploadsManager( 2279): End new media; added: 0, uploading: 0, time: 161 ms
D/MusicBrowser( 2730): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2730): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicWidget( 2681): intentReceiver onReceive() action::com.lge.music.metachanged
,I/MusicWidget( 2681): beingMusicWidget_4x2() result::false
I/MusicBrowser( 2730): [MediaPlaybackService.java:3426:notifyChange()] oooooo mRemoteControlClient.editMetadata :: META_CHANGED 
I/MusicBrowser( 2730): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=false}
I/MusicBrowser( 2730): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/MusicWidget( 2681): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2730): [MediaPlaybackService.java:9999:run()] oooooo AlbumImageUpdater() run :: Start
I/MusicBrowser( 2730): [MediaPlaybackService.java:10051:run()] oooooo AlbumImageUpdater() run :: End
I/MusicWidget( 2681): beingMusicWidget_4x1() result::true
I/MusicWidget( 2681): send mDelayedStopHandler
D/MusicBrowser( 2730): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicWidget( 2681): performViewUpdater handleMessage() msg.what::3
I/MusicBrowser( 2730): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2730): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2730): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2730): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
I/MusicWidget( 2681): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2730): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
V/CloudHub( 4003): [DATABASE][DBConnection|open] open database
,E/CloudHub( 4003): [DATABASE][DBConnection|getUserId] User id: 0
E/CloudHub( 4003): [DATABASE][DBConnection|getDatabasePath] Database path: /data/user/0/com.lge.cloudhub/databases/cloudhub.db
I/VRBookmarkProvider( 3958): [BookmarkProvider.java:530:handleMessage()-[Thread:Other] -- syncTable() START --
,V/CloudHub( 4003): [SERVICE][CloudHubReceiver|queryUploadCount] # of contents to upload: 0
V/DownloadManager( 3206): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3206): created cursor android.database.sqlite.SQLiteCursor@89e9f3e on behalf of 4003
V/CloudHub( 4003): [SERVICE][CloudHubReceiver|queryDownloadCount] # of contents to download: 0
I/MusicWidget( 2681): performViewUpdater handleMessage() msg.what::0
,I/MusicWidget( 2681): beingMusicWidget_4x1() result::true
I/MusicWidget( 2681): performUpdate()_4x1
I/MusicWidget( 2681): defaultAppWidget()_4x1
I/MusicWidget( 2681): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2681): 4x1_currentTheme :: null
I/MusicWidget( 2681): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2681): setDefaultViewLayoutId()_4x1
I/MusicWidget( 2681): appWidgetViewUpdate()_4x1
I/MusicWidget( 2681): linkButtons()_4x1
I/ActivityManager(  856): Start proc com.lge.gnss.airtest for broadcast com.lge.gnss.airtest/.GnssAirTestReceiver: pid=4025 uid=10054 gids={50054, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  856): Killing 2078:com.google.process.gapps/u0a6 (adj 15): empty #11
I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 22.722ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 20.867ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 310us total 23.283ms
,W/libprocessgroup(  856): failed to open /acct/uid_10006/pid_2078/cgroup.procs: No such file or directory
I/VRBookmarkProvider( 3958): [BookmarkProvider.java:532:handleMessage()-[Thread:Other] -- syncTable() END --
I/ActivityManager(  856): Waited long enough for: ServiceRecord{2d567240 u0 com.lge.sizechangable.musicwidget.widget/.service.MusicWidgetUpdater}
I/MusicWidget( 2681): pushUpdate()_4x1
,I/MusicWidget( 2681): performViewUpdater handleMessage() msg.what::1
,I/MusicWidget( 2681): beingMusicWidget_4x2() result::false
D/AirTest ( 4025): Set airtest_enable to false
I/ActivityManager(  856): Killing 3770:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1966): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1966): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,W/libprocessgroup(  856): failed to open /acct/uid_10014/pid_3770/cgroup.procs: No such file or directory
,V/LGSC    ( 2756): [104] 401
I/ActivityManager(  856): Killing 3801:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_1000/pid_3801/cgroup.procs: No such file or directory
,I/ActivityManager(  856): Start proc com.lge.lgfota.permission for broadcast com.lge.lgfota.permission/.DmcTargetValidationReceiver: pid=4043 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/TARGETVALIDLATION_RECEIVER( 4043): TargetValidationReceiver_ACTION_BOOT_COMPLETETED Received
,D/TARGETVALIDLATION_RECEIVER( 4043): updateFlag = new File(TARGET_FLAG_PATH)
D/TARGETVALIDLATION_RECEIVER( 4043): Do Not display result dialog. it is not used Update Tool!!
I/ActivityManager(  856): Killing 3825:com.lge.clock/u0a10 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_10010/pid_3825/cgroup.procs: No such file or directory
V/LGSC    ( 1795): [101] 102, action=android.intent.action.BOOT_COMPLETED, iccState=null
,W/ContextImpl( 2956): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2663 
,E/AtFwd AutoBoot( 2956): AtFwd Auto Boot Started Successfully
I/ActivityManager(  856): Start proc com.google.process.gapps for broadcast com.google.android.syncadapters.contacts/.ContactsSyncAdapterBroadcastReceiver: pid=4063 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/GservicesProvider( 4063): Gservices pushing to system: true; secure/global: true
,I/GoogleHttpClient( 4063): GMS http client unavailable, use old client
,I/GoogleHttpClient( 4063): GMS http client unavailable, use old client
,I/GoogleHttpClient( 4063): GMS http client unavailable, use old client
,I/ActivityManager(  856): Start proc com.lge.defaultaccount for broadcast com.lge.defaultaccount/.receiver.ReceiverBootUp: pid=4086 uid=10062 gids={50062, 9997} abi=armeabi-v7a
,I/InsertAccount( 4086): The account already exists
,I/ActivityManager(  856): Start proc com.lge.hiddenmenu for broadcast com.lge.hiddenmenu/.kddi_only.sms_setting.AssistReceiver: pid=4104 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  856): Killing 3850:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #11
,I/MusicBrowser( 2730): [MediaPlaybackService.java:2010:handleMessage()] oooooo mGroupIndexHandler msg.what : 0
I/MusicBrowser( 2730): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2730): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2730): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2730): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
,W/libprocessgroup(  856): failed to open /acct/uid_10011/pid_3850/cgroup.procs: No such file or directory
I/ActivityManager(  856): Killing 3873:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/MusicBrowser( 2730): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
,W/libprocessgroup(  856): failed to open /acct/uid_10011/pid_3873/cgroup.procs: No such file or directory
I/InsertAccount( 4086): The account info in contact DB already exists
W/ResourcesManager( 4104): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4104): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ActivityManager(  856): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4131 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  856): Killing 3262:com.android.settings/1000 (adj 15): empty #11
I/[SMS_AD]( 4104): Intent action: android.intent.action.BOOT_COMPLETED
W/libprocessgroup(  856): failed to open /acct/uid_1000/pid_3262/cgroup.procs: No such file or directory
,I/[SMS_AD]( 4104): Intent action: android.intent.action.BOOT_COMPLETED
W/ResourcesManager( 4131): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/ActivityManager(  856): Killing 3931:com.android.managedprovisioning/u0a111 (adj 15): empty #11
,D/CalendarProvider2( 4131): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@3f3ae692
,W/libprocessgroup(  856): failed to open /acct/uid_10111/pid_3931/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2715): 2 : onReceive, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 16:56:36
D/CalendarProvider2( 4131): [getOrCreateCalendarAlarmManager]
D/UpdateThreadPoolManager( 2715): 2 : This is isUpdating : false
I/CalendarProvider2( 4131): Created com.android.providers.calendar.CalendarAlarmManager@375e97bf(com.android.providers.calendar.CalendarProvider2@3f3ae692)
D/Weather_cast( 2715): 2 : set auto-update time : 1/11 19:56
D/WeatherAncestor( 2715): 2 : onReceive has processed, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 16:56:36
D/WeatherService( 2715): 2 : onStartCommand, intent!=null, action: android.intent.action.BOOT_COMPLETED
,I/ActivityManager(  856): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.LockSettingsReceiver: pid=4152 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  856): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2715): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2715): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2715): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/InsertAccount( 4086): The account info in calendar DB already exists
I/Process ( 4086): Sending signal. PID: 4086 SIG: 9
I/ActivityManager(  856): Process com.lge.defaultaccount (pid 4086) has died
,I/LockScreenSettings( 4152): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/LockScreenSettings( 4152): Received Broadcast : android.intent.action.BOOT_COMPLETED
,I/ActivityManager(  856): Start proc com.lge.springcleaning for broadcast com.lge.springcleaning/.receiver.BootCompleteReceiver: pid=4173 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/BootCompleteReceiver( 4173): hasclipTray = true
,W/ContextImpl( 4173): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.springcleaning.receiver.BootCompleteReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2663 
I/ActivityManager(  856): Start proc com.lge.springcleaning:AppCleanupService for service com.lge.springcleaning/.service.AppCleanupService: pid=4193 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  856): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4214 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  856): Killing 3958:com.lge.voicerecorder/u0a34 (adj 15): empty #11
,W/libprocessgroup(  856): failed to open /acct/uid_10034/pid_3958/cgroup.procs: No such file or directory
V/AppCleanupService( 4193): registerAlarm
,D/AppCleanupService( 4193): noticeInterval = 2678400000
D/AppCleanupService( 4193): notiDateStr = 2016-01-20 22:41:42
D/AppCleanupService( 4193): noticeStart = 2016-01-20 22:41:42
,D/AppCleanupService( 4193): noticeStart = 1453326102000
D/AppUsageDbAdapter( 4193): initPreloadedAppToTheDB() : row count = 182
,E/UpdateRequestReceiver( 4214): ignoring update request
,E/UpdateRequestReceiver( 4214): ignoring update request
E/UpdateRequestReceiver( 4214): ignoring update request
,E/UpdateRequestReceiver( 4214): ignoring update request
E/UpdateRequestReceiver( 4214): ignoring update request
E/UpdateRequestReceiver( 4214): ignoring update request
I/ActivityManager(  856): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=4245 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  856): Killing 2279:com.google.android.gms/u0a6 (adj 15): empty #11
D/ConnectivityService(  856): ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@2ff8b3b2)
D/ConnectivityService(  856): dumpNetworkRequest
D/ConnectivityService(  856):     NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/ConnectivityService(  856):     Requests:
D/ConnectivityService(  856):         NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  856):         NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  856):         NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  856):     Lingered:
D/ConnectivityService(  856): releasing NetworkRequest NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  856): sending notification RELEASED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,E/ConnectivityService(  856): RemoteException caught trying to send a callback msg for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/libprocessgroup(  856): failed to open /acct/uid_10006/pid_2279/cgroup.procs: No such file or directory
,D/SIMObserver( 4245): action:android.intent.action.BOOT_COMPLETED
D/SIMObserver( 4245): handle ACTION_BOOT_COMPLETED
,I/ActivityManager(  856): Killing 3983:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  856): failed to open /acct/uid_10051/pid_3983/cgroup.procs: No such file or directory
,E/QcrilMsgTunnelAutoboot( 2318): Received Intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot (has extras) } canStartService = false
D/PhoneInterfaceManager( 1795): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
D/PhoneInterfaceManager( 1795): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
I/ActivityManager(  856): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4266 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 340us total 27.740ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 323us total 26.866ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 20.689ms
,W/ResourcesManager( 4266): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/sensors_hal_Time(  856): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  856): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  856): tsOffsetIs: Apps: 52781825871; DSPS: 1821089; Offset : -2795190297
,I/Babel_SMS( 4266): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 4266): MmsConfig.loadMmsSettings
I/Babel_SMS( 4266): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 4266): MmsConfig.loadFromDatabase
,E/Babel_SMS( 4266): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4266): MmsConfig.loadFromResources
E/Babel_SMS( 4266): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 4266): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 4266): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 4266): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 4266): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 4266): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 4266): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 4266): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 4266): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 4266): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 4266): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 4266): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 4266): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 4266): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 4266): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 4266): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 4266): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 4266): found sensor: Motion Accel, handle=46
,I/art     ( 4266): CheckpointMarkThreadRoots callback created = 0xaaf39960
,W/Settings( 4266): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 4266): startup - clean
I/Babel   ( 4266): deleted: false for 0
,I/art     ( 4266): CheckpointMarkThreadRoots callback created = 0xaaf39940
,W/art     ( 4266): Suspending all threads took: 6.907ms
,V/AlarmManager(  856): ELAPSED_WAKEUP set : Alarm{3de2c42d type 2 when 53271 com.android.providers.calendar} when 53271
,W/AudioCapabilities( 4266): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 4266): Unsupported mime audio/adpcm
,W/AudioCapabilities( 4266): Unsupported mime audio/g726
W/AudioCapabilities( 4266): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4266): Unsupported mime audio/wma-voice
W/VideoCapabilities( 4266): Unsupported mime video/mjpg
W/VideoCapabilities( 4266): Unsupported mime video/theora
W/AudioCapabilities( 4266): Unsupported mime audio/evrc
,W/AudioCapabilities( 4266): Unsupported mime audio/qcelp
W/VideoCapabilities( 4266): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 4266): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 4266): Unsupported mime audio/qcelp
W/AudioCapabilities( 4266): Unsupported mime audio/evrc
W/ActivityManager(  856): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
,V/AlarmManager(  856): RTC_WAKEUP set : Alarm{19216d62 type 0 when 1452527776762 com.android.providers.contacts} when 1452527776762
V/AlarmManager(  856): ELAPSED_WAKEUP set : Alarm{1e5b9ef3 type 2 when 53256 com.google.android.talk} when 53256
W/VideoCapabilities( 4266): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 4266): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4266): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4266): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4266): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4266): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 4266): onServiceConnected
,W/Babel   ( 4266): Attempted to change video mute state without an active call.
I/NotificationManager( 4266): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/ActivityManager(  856): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4315 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  856): Killing 4003:com.lge.cloudhub/u0a49 (adj 15): empty #11
,W/libprocessgroup(  856): failed to open /acct/uid_10049/pid_4003/cgroup.procs: No such file or directory
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,W/ResourcesManager( 4315): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4315): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 4315): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 4315): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4315): Installed default security provider GmsCore_OpenSSL
W/ResourcesManager( 4315): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4315): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 4315): CheckpointMarkThreadRoots callback created = 0xb042db80
I/art     ( 4315): CheckpointMarkThreadRoots callback created = 0xb4958de0
,I/ActivityManager(  856): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=4350 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
E/YouTube MDX( 4315): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc-netbsd( 4315): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4315): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/ResourcesManager( 4350): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4350): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
,W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4315): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,I/MultiDex( 4350): VM with version 2.1.0 has multidex support
,I/MultiDex( 4350): install
I/MultiDex( 4350): VM has multidex support, MultiDex support library is disabled.
I/dex2oat ( 4373): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads103685607.jar --oat-fd=25 --oat-location=/data/data/com.google.android.youtube/cache/ads103685607.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 4373): dex2oat took 118.564ms (threads: 4)
,I/art     (  856): Explicit concurrent mark sweep GC freed 17614(860KB) AllocSpace objects, 2(221KB) LOS objects, 33% free, 23MB/34MB, paused 1.967ms total 149.289ms
,V/JNIHelp ( 4350): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/NotificationManager( 4315): com.google.android.youtube: cancel(2) by com.google.android.youtube
,W/ActivityThread( 4350): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4350): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12397b77: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4350): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 4350): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 4350): com.google.android.gms: cancel(39789) by com.google.android.gms
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4315): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4315): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4315): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/InstanceID/Rpc( 4315): Found 10006
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4315): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,D/NativeLibraryUtils( 4350): Install completed successfully. count=14 extracted=0
,D/libc-netbsd( 4315): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4315): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4315): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4315): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10100
,D/DnsProxyListener(  280): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  856): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4440 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 4315): propertyValue:false
D/libc-netbsd( 4315): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4315): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager( 4315): com.google.android.youtube: cancel(10436) by com.google.android.youtube
,I/ActivityManager(  856): Killing 4043:com.lge.lgfota.permission/1000 (adj 15): empty #11
,D/libc-netbsd( 4315): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4315): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  856): Killing 4025:com.lge.gnss.airtest/u0a54 (adj 15): empty #12
,W/libprocessgroup(  856): failed to open /acct/uid_1000/pid_4043/cgroup.procs: No such file or directory
,W/libprocessgroup(  856): failed to open /acct/uid_10054/pid_4025/cgroup.procs: No such file or directory
,I/art     ( 1761): Explicit concurrent mark sweep GC freed 19642(1584KB) AllocSpace objects, 37(592KB) LOS objects, 39% free, 12MB/21MB, paused 1.571ms total 86.558ms
,W/ActivityManager(  856): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4440): getAccountsCursor
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 4440): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ActivityManager(  856): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  856): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,E/Gmail   ( 4440): Error finding the version of the Email provider.....
E/Gmail   ( 4440): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4440): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4440): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4440): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4440): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4440): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4440): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 4440): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4440): We do not support migrating this version of the Email provider.
I/Gmail   ( 4440): Observing account changes for notifications
W/ActivityManager(  856): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 4440): getAccountsCursor
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  856): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  856): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/ActivityThread( 4440): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@193d9931 that was originally bound here
E/ActivityThread( 4440): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@193d9931 that was originally bound here
E/ActivityThread( 4440): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 4440): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 4440): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 4440): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 4440): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4440): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4440): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4440): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4440): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4440): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4440): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4440): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4440): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4440): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4440): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4440): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  856): Unbind failed: could not find connection for android.os.BinderProxy@10bbb746
,I/ActivityManager(  856): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4485 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,V/[BNRBootReceiver]( 4485): boot receiver action = android.intent.action.BOOT_COMPLETED
,V/[BNRBootReceiver]( 4485): set property sys.lge.bnrd = 1
V/[BNRBootReceiver]( 4485): End of BootComplted IF
V/[BNRBootReceiver]( 4485): Boot Receiver Return
V/[BNRBootCompletedThread]( 4485): run
W/linker  ( 4504): /system/bin/bnrd has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/bnrd    ( 4504): BNRD > wait starting [4504-3058102400] <
E/bnrd    ( 4504): /data/data/.bnr_fifo_req
V/[BNRBootCompletedThread]( 4485): End of BNRProcess
,V/[BNRBootCompletedThread]( 4485): End of BNRViaWifiProcess
V/[BNRBootCompletedThread]( 4485): End of SpriteProcess
V/[BNRBootCompletedThread]( 4485): exit
I/ActivityManager(  856): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4510 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  856): Killing 4131:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/Gmail   ( 4440): notifyAccountChanged
,I/Gmail   ( 4440): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
W/libprocessgroup(  856): failed to open /acct/uid_10014/pid_4131/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/Gmail   ( 4440): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ActivityManager(  856): Killing 4104:com.lge.hiddenmenu/1000 (adj 15): empty #11
I/Gmail   ( 4440): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4440): calculateUnknownSyncRationalesAndPurgeInBackground: running
V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/libprocessgroup(  856): failed to open /acct/uid_1000/pid_4104/cgroup.procs: No such file or directory
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4440): getAccountsCursor
V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4440): getAccountsCursor
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4510): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 4510): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 4510): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4510): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 4510): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3206): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3206): created cursor android.database.sqlite.SQLiteCursor@2802e19f on behalf of 4510
D/Volley  ( 4510): [471] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 4510): [478] DiskBasedCache.clear: Cache cleared.
D/Finsky  ( 4510): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4510): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 4510): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Ads     ( 4510): Skipping gmscore version check
D/Finsky  ( 4510): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/FileApkUtils( 4350): Spent 82ms computing apk sha1.
,D/FileApkUtils( 4350): Module already staged or being staged:chimera-modules/MapsModule.apk
I/art     ( 4350): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-ca8b2a9144773fc3650c54ed299f2d4558171b12@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
D/DexOptUtils( 4350): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 4350): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
,D/ChimeraCfgMgr( 4350): Reading stored module config
D/GmsModuleFndr( 4350): Beginning GMS chimera module scan
,W/InstanceID/Rpc( 4350): Found 10006
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/GmsModuleFndr( 4350): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
,D/ChimeraCfgMgr( 4350): Beginning module configuration check
D/ChimeraCfgMgr( 4350): Module APKs unchanged, check complete
D/GCM     ( 4350): COMPAT: Multi user not supported
,D/GCM     ( 1761): COMPAT: Multi user not supported
,I/art     ( 4350): CheckpointMarkThreadRoots callback created = 0xaae7b6a0
I/CheckinService( 4350): Checkin interval check for package: unspecified last checkin: 1452525992039 min interval config: 0 actual interval: 1809926
,I/CheckinService( 4350): Disabling old GoogleServicesFramework version
,I/GCoreUlr( 4350): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
I/art     ( 4350): CheckpointMarkThreadRoots callback created = 0xb042d690
,D/ChimeraCfgMgr( 4350): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/BootCompletedReceiver( 4350): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
D/BootCompletedReceiver( 4350): Got an BootCompleted event.
I/art     ( 4063): Explicit concurrent mark sweep GC freed 8370(430KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.106ms total 39.088ms
,D/BootCompletedReceiver( 4350): Will NOT schedule AdAttestation signal task because it's disabled.
,D/SystemUpdateService( 4350): onCreate
,I/CheckinService( 4350): Checking schedule, now: 1452527802148 next: 1453053241005
I/CheckinService( 4350): active receiver: disabled
D/SystemUpdateService( 4350): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,V/AuthZen ( 4350): Handling intent: android.intent.action.BOOT_COMPLETED
,I/SystemUpdateService( 4350): cancelUpdate (empty URL)
I/SystemUpdateService( 4350): active receiver: disabled
,I/NotificationManager( 4350): com.google.android.gms: cancel(2130838165) by com.google.android.gms
,I/NotificationManager( 4350): com.google.android.gms: cancel(2130838166) by com.google.android.gms
D/AuthZenEventHandler( 4350): Handling event: android.intent.action.BOOT_COMPLETED
,I/art     ( 4063): Explicit concurrent mark sweep GC freed 2569(100KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 4.358ms total 30.576ms
,W/BaseAppContext( 4350): Using Auth Proxy for data requests.
,E/BaseAppContext( 4350): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/AuthZen ( 4350): Fetching signing key...
,I/AuthZen ( 4350): Signing key fetched successfully!
,I/ActivityManager(  856): Waited long enough for: ServiceRecord{166e3bbf u0 com.android.mms/.service.SwitchedService}
W/BaseAppContext( 4350): Using Auth Proxy for data requests.
D/a       ( 4350): Opening database auth.proximity.permit_store...
,D/AuthZenTransactionCache( 4350): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 4350): Clearing transaction cache
I/art     (  856): Explicit concurrent mark sweep GC freed 23966(1192KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 23MB/34MB, paused 2.818ms total 180.600ms
D/SystemUpdateService( 4350): onDestroy
,D/GCM     ( 1761): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/GCoreUlr( 1761): DispatchingService.onCreate()
D/libc-netbsd( 1761): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1761): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1761): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1761): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
I/art     ( 4350): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 4350): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out( 1761): propertyValue:false
I/GCoreUlr( 1761): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/libc-netbsd( 1761): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1761): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NotificationManager(  856): android: cancelAsUser(-591465577) by android
I/art     ( 1761): Explicit concurrent mark sweep GC freed 15602(989KB) AllocSpace objects, 12(192KB) LOS objects, 40% free, 13MB/21MB, paused 4.493ms total 86.358ms
,D/libc-netbsd( 1761): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1761): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/NotificationManager( 4350): com.google.android.gms: cancel(10436) by com.google.android.gms
I/GCoreUlr( 1761): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1761): Unbound from all location providers
I/GCoreUlr( 1761): Place inference reporting - stopped
W/Auth    ( 1761): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,W/GCoreFlp( 1761): No location to return for getLastLocation()
W/FusedLocationProvider( 1761): location=null
I/GCM     ( 1761): GCM config loaded
V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1761): DispatchingService.onDestroy()
I/GCoreUlr( 1761): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1761): Unbound from all location providers
I/GCoreUlr( 1761): Place inference reporting - stopped
W/GCoreFlp( 1761): No location to return for getLastLocation()
W/FusedLocationProvider( 1761): location=null
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout,
,D/PersistentNotificationBroadcastReceiver( 1761): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/ActivityManager(  856): Start proc com.lge.qmemoplus for broadcast com.lge.qmemoplus/.ui.editor.reminder.ReminderMaker: pid=4638 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,W/ResourcesManager( 4638): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager(  856): Killing 4152:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
I/NotificationManager(  856): android: cancelAsUser(-1816247584) by android
W/libprocessgroup(  856): failed to open /acct/uid_10069/pid_4152/cgroup.procs: No such file or directory
,E/App     ( 4638): [App][onCreate()] 4.40.23
D/PowerService( 1883): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1390): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1390): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1390): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,I/[SystemUI]LGPowerUI( 1390): On Skip Timer : true
D/AccountManager( 4638): setSyncFrequency
,W/ContextImpl( 4638): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.qmemoplus.ui.editor.reminder.ReminderMaker.onReceive:14 android.app.ActivityThread.handleReceiver:2663 
,D/WeatherAncestor( 2715): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 16:56:43
D/UpdateThreadPoolManager( 2715): 2 : This is isUpdating : false
D/WeatherAncestor( 2715): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 16:56:43
D/WeatherService( 2715): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
W/ActivityManager(  856): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2715): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2715): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2715): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2715): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/ReminderService( 4638): [onHandleIntent] action : com.lge.qmemoplus.action.SET_REMINDERS
D/UpdateThreadPoolManager( 2715): 2 : This is isUpdating : false
D/WeatherService( 2715): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2715): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2715): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2715): 2 : Fixed theme : optimus
D/WeatherReflect( 2715): 2 : Map key string is -2
D/LocationReminderManager( 4638): [connect] Request location client connection.
D/lim     ( 2715): 2 : time = 16:56
I/WeatherReflect( 2715): Model Name : LG-D722
D/WeatherTheme( 2715): 2 : exactly same view!
D/WeatherTheme( 2715): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
,W/ActivityManager(  856): getTasks: caller 10074 does not hold GET_TASKS; limiting output
V/UserPresentBroadcastReceiver( 1761): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
D/Weather.Utils( 2715): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2715): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2715): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
W/ContextImpl( 4638): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.google.android.gms.internal.he.a:-1 com.google.android.gms.internal.hc.connect:-1 com.google.android.gms.location.LocationClient.connect:-1 
,I/ActivityManager(  856): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=4666 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  856): Killing 4173:com.lge.springcleaning/1000 (adj 15): empty #11
,D/LocationReminderManager( 4638): location cilent is connected.
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/LocationReminderManager( 4638): [removeAllReminders]
,W/libprocessgroup(  856): failed to open /acct/uid_1000/pid_4173/cgroup.procs: No such file or directory
,W/GeofencerStateMachine( 1761): Ignoring removeGeofence because network location is disabled.
,D/LocationReminderManager( 4638): [removeAllReminders] statusCode : 1000
D/LocationReminderManager( 4638): [removeAllReminders] Failed to remove reminder
W/GCoreFlp( 1761): No location to return for getLastLocation()
W/GCoreFlp( 1761): No location to return for getLastLocation()
D/LGDMClient( 4666): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver com.lge.intent.action.fota_data_change
D/LGDMClient( 4666): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4666): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4666): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 4666): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : com.lge.intent.action.fota_data_change
,D/LGDMClient( 4666): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 4666): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  856): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=4700 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
W/ContextImpl( 4666): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4666): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 4666): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 4666): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 4666): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 4666): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  856): Killing 4214:com.google.android.configupdater/u0a3 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_10003/pid_4214/cgroup.procs: No such file or directory
,W/ResourcesManager( 4700): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  856): Message: 20
D/BluetoothManagerService(  856): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bf79b4a:true
,D/BluetoothAdapterService(292483291)( 2100): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e9dc689
D/BluetoothAdapterService(292483291)( 2100): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e9dc689
I/ActivityManager(  856): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4721 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 4700): Create singleton instance
,D/UEI.SmartControl( 4721): Quickset Services start...
I/UEI.SmartControl( 4721): Manufacture = LGE
,D/UEI.SmartControl( 4721): File observer start...
E/UEI.SmartControl( 4721): IR Port is disabled: false
D/UEI.SmartControl( 4721): Starting file observer...
D/UEI.SmartControl( 4721): Extracting JNI libs...
I/AudioManager( 4700): getMode name:com.lge.qremote
D/UEI.SmartControl( 4721): --- this system supports 32-bit or 64-bit only
V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
I/AudioManager( 4700): getMode name:com.lge.qremote
,V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
D/UEI.SmartControl( 4721): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
D/UEI.SmartControl( 4721): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 4721): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
I/UEI.SmartControl( 4721): --- Selecting new region: 2
I/UEI.SmartControl( 4721): -- Running on KitKat(19) and above! JNI will be used.
V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
D/UEI.SmartControl( 4721): Platform has CIR...
V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
D/UEI.SmartControl( 4721): NO CIR support, need to check package...
I/UEI.SmartControl( 4721): Model: LG-D722 uses JNI
V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
D/UEI.SmartControl( 4721): QS Service created
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3185): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3185): ANY_DATA_STATE event received: DISCONNECTED
D/LGDMClient( 4666): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver com.lge.intent.action.fota_data_change
,D/LGDMClient( 4666): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4666): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4666): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 4666): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
D/LGDMClient( 4666): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : com.lge.intent.action.fota_data_change
I/LGDMClient( 4666): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
E/UEI.SmartControl( 4721): QS start get config
,I/ActivityManager(  856): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=4756 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/ContextImpl( 4666): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
D/UEI.SmartControl( 4721): Loading JNI Libs...
,D/UEI.SmartControl( 4721):  configuring local db...
E/LGDMClient( 4666): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 4666): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,D/LGDMClient( 4666): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 4666): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 4666): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,W/ResourcesManager( 4756): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4756): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 4756): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4756): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 4756): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 4756): Using schema version: 115
,I/IndexDatabaseHelper( 4756): Index is fine
D/UEI.SmartControl( 4721):  ---- Has DB8: true
,D/UEI.SmartControl( 4721): QS start statue = true Error code = 0
D/UEI.SmartControl( 4721): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 4721): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 4721): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 4721): IRRCPlayer_nativeInit ++ 
D/irrcClient( 4721): IrrcClient ++ 
D/irrcClient( 4721): getIrrcService ++ 
,D/irrcClient( 4721): getIrrcService -- 
D/irrcClient( 4721): IrrcClient -- 
W/irrc_jni( 4721): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 4721): Services init done
I/UEI.SmartControl( 4721): Device manager: loading config....
D/UEI.SmartControl( 4721): QS Service init finished
D/UEI.SmartControl( 4721): QS Service version name: 0.1.73
,D/UEI.SmartControl( 4721): Config is loaded...
D/UEI.SmartControl( 4721): QS Service version code: 1073
D/UEI.SmartControl( 4721): Service requested: Control
D/UEI.SmartControl( 4721): Internal service binding...
D/UEI.SmartControl( 4721): -----IControl: 11
D/UEI.SmartControl( 4721): Caller: com.lge.qremote
D/UEI.SmartControl( 4721): ------------ IControl registerCallback...
I/UEI.SmartControl( 4721): Registering callback...
D/UEI.SmartControl( 4721): -----IControl: 19
D/UEI.SmartControl( 4721): Caller: com.lge.qremote
I/UEI.SmartControl( 4721): Registering Services Ready callback...
I/UEI.SmartControl( 4721): Notify client services are ready...
D/UEI.SmartControl( 4721): -----IControl: 8
,D/UEI.SmartControl( 4721): Caller: com.lge.qremote
I/ActivityManager(  856): Killing 4266:com.google.android.talk/u0a61 (adj 15): empty #11
D/UEI.SmartControl( 4721):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 4721): Notify AllClients services are ready: 0
V/WiFiOffLoadBroadcast( 4756): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,I/ActivityManager(  856): Killing 4245:com.lge.eula/1000 (adj 15): empty #12
,D/WiFiOffLoadBroadcast( 4756): MCCMNC not supported: null
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  856): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4780 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  856): Killing 4315:com.google.android.youtube/u0a100 (adj 15): empty #11
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 300us total 20.987ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 20.516ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 20.431ms
,W/libprocessgroup(  856): failed to open /acct/uid_10061/pid_4266/cgroup.procs: No such file or directory
W/libprocessgroup(  856): failed to open /acct/uid_1000/pid_4245/cgroup.procs: No such file or directory
W/libprocessgroup(  856): failed to open /acct/uid_10100/pid_4315/cgroup.procs: No such file or directory
D/PCSuite ( 4780): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/AudioManager( 4700): getMode name:com.lge.qremote
D/UsbSettingsReceiver( 4756): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 4756): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 4756): [AUTORUN] sys.usb.state = ptp_only,adb
,D/UsbSettingsReceiver( 4756): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 4756): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 4756): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 4756): [AUTORUN] onReceive() : availableList=[wlan0]
,D/UsbSettingsReceiver( 4756): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 4756): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 4756): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 4756): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 4756): [AUTORUN] setTetherStatus() : status=false
V/WiFiOffLoadBroadcast( 4756): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/WiFiOffLoadBroadcast( 4756): MCCMNC not supported: null
D/PCSuite ( 4780): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/LGDMClient( 4666): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4666): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4666): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4666): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
V/WiFiOffLoadBroadcast( 4756): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4756): MCCMNC not supported: null
D/LGDMClient( 4666): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 4666): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4666): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4666): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/ContextImpl( 4666): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 4666): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 4666): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 4666): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 4666): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
I/PCSuite ( 4780): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/LGDMClient( 4666): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
D/PCSuite ( 4780): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4780): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/[BNRBootReceiver]( 4485): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/BNRAndroBeam( 4485): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,V/[BNRBootReceiver]( 4485): Boot Receiver Return
V/WiFiOffLoadBroadcast( 4756): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4756): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4756): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 4756): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 4756): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 4756): MCCMNC not supported: null
V/AlarmManager(  856): RTC_WAKEUP set : Alarm{36735b08 type 0 when 1452527805101 com.google.android.gms} when 1452527805101
,V/WiFiOffLoadBroadcast( 4756): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4756): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4756): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4756): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4756): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4756): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4756): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4756): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4756): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4756): MCCMNC not supported: null
I/ActivityManager(  856): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=4811 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/iu.UploadsManager( 4350): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
W/ResourcesManager( 4811): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4811): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 4811): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/iu.UploadsManager( 4350): End new media; added: 0, uploading: 0, time: 48 ms
,I/ActivityManager(  856): Killing 4440:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_10053/pid_4440/cgroup.procs: No such file or directory
,I/LGEmail ( 4811): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 4811): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/PackageChangeReceiver( 4811): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager(  856): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4835 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  856): Killing 4510:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  856): failed to open /acct/uid_10036/pid_4510/cgroup.procs: No such file or directory
,I/ActivityManager(  856): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=4858 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  856): Killing 4638:com.lge.qmemoplus/1000 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_1000/pid_4638/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 4858): onCreate
W/AppUp4:DB( 4858):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 4858):  setFingerPrint start
I/AppUp4:DB( 4858):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 4858):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 4858):  SDK version = 0
I/AppUp4:DB( 4858):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 4858): AppBoxApplication onCreate()
D/AppUp4:PreloadHelper( 4858): removed from Exclude : com.example.hello : 1
,I/ActivityManager(  856): Killing 4666:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_1000/pid_4666/cgroup.procs: No such file or directory
,I/ActivityManager(  856): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=4875 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 4875): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4875): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4875): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/art     (  856): Explicit concurrent mark sweep GC freed 21768(1004KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.097ms total 133.989ms
,I/AppConfig( 4875): Total System Memory = 906309632
I/GalleryUtils( 4875): Application Heap = 96 MB
I/AppConfig( 4875): App Tier : NOT_DEF
,D/SystemHelper( 4875): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  856): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=4894 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  856): Killing 4485:com.lge.bnr/1000 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_1000/pid_4485/cgroup.procs: No such file or directory
,W/ResourcesManager( 4894): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4894): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 4894): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 4894): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 4894): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 4894): BUILD Country: EU
I/SystemConfig( 4894): BUILD Operator: OPEN
,I/SystemConfig( 4894): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 4894): existFile = false
I/SystemConfig( 4894): canReadFile = false
I/SystemConfig( 4894): systemFeature RCS result false
D/SystemConfig( 4894): refreshRcsSupport() :false
,I/ActivityManager(  856): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=4913 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  856): Killing 4350:com.google.android.gms/u0a6 (adj 15): empty #11
,W/libprocessgroup(  856): failed to open /acct/uid_10006/pid_4350/cgroup.procs: No such file or directory
I/LockScreenSettings( 4913): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/LockScreenSettings( 4913): New app installed broadcast received ..
,I/LockScreenSettings( 4913): Number of installed packages  1
I/ActivityManager(  856): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=4930 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  856): Killing 4756:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_1000/pid_4756/cgroup.procs: No such file or directory
,D/EulaProviderUpdateObserver( 4930): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 4930): uri : package:com.example.hello
,I/ActivityManager(  856): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4947 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager(  856): Killing 4721:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 4700): android.os.DeadObjectException
,W/System.err( 4700): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4700): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4700): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 4700): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 4700): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4700): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4700): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4700): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4700): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4700): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4700): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4700): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4700): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4700): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4700): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 4700): android.os.DeadObjectException
W/System.err( 4700): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4700): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4700): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 4700): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 4700): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4700): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4700): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4700): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4700): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4700): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4700): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4700): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4700): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4700): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4700): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  856): failed to open /acct/uid_10089/pid_4721/cgroup.procs: No such file or directory
,W/ActivityManager(  856): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  856): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4965 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 4965): Quickset Services start...
,I/UEI.SmartControl( 4965): Manufacture = LGE
D/UEI.SmartControl( 4965): File observer start...
E/UEI.SmartControl( 4965): IR Port is disabled: false
D/UEI.SmartControl( 4965): Starting file observer...
D/UEI.SmartControl( 4965): Extracting JNI libs...
D/UEI.SmartControl( 4965): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 4965): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 4965): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 4965): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 4965): --- Selecting new region: 2
,I/UEI.SmartControl( 4965): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 4965): Platform has CIR...
D/UEI.SmartControl( 4965): NO CIR support, need to check package...
I/UEI.SmartControl( 4965): Model: LG-D722 uses JNI
D/UEI.SmartControl( 4965): QS Service created
E/UEI.SmartControl( 4965): QS start get config
,D/UEI.SmartControl( 4965): Loading JNI Libs...
D/UEI.SmartControl( 4965):  configuring local db...
,D/UEI.SmartControl( 4965):  ---- Has DB8: true
,D/UEI.SmartControl( 4965): QS start statue = true Error code = 0
D/UEI.SmartControl( 4965): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 4965): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 4965): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 4965): IRRCPlayer_nativeInit ++ 
D/irrcClient( 4965): IrrcClient ++ 
D/irrcClient( 4965): getIrrcService ++ 
D/irrcClient( 4965): getIrrcService -- 
D/irrcClient( 4965): IrrcClient -- 
W/irrc_jni( 4965): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 4965): Services init done
D/UEI.SmartControl( 4965): QS Service init finished
D/UEI.SmartControl( 4965): QS Service version name: 0.1.73
I/UEI.SmartControl( 4965): Device manager: loading config....
,D/UEI.SmartControl( 4965): QS Service version code: 1073
D/UEI.SmartControl( 4965): Service requested: Control
D/UEI.SmartControl( 4965): Config is loaded...
I/ActivityManager(  856): Waited long enough for: ServiceRecord{2b8ffe1e u0 com.lge.mlt/.MltMonitorService}
,D/UEI.SmartControl( 4965):  ----- QS SDK is ready!!!
,D/UEI.SmartControl( 4965): Request IControl service: devices are loaded...
I/UEI.SmartControl( 4965): Notify AllClients services are ready: 0
I/ActivityManager(  856): Killing 4780:com.lge.sync/1000 (adj 15): empty #11
D/UEI.SmartControl( 4965): -----IControl: 11
D/UEI.SmartControl( 4965): Caller: com.lge.qremote
D/UEI.SmartControl( 4965): ------------ IControl registerCallback...
I/UEI.SmartControl( 4965): Registering callback...
D/UEI.SmartControl( 4965): -----IControl: 19
D/UEI.SmartControl( 4965): Caller: com.lge.qremote
I/UEI.SmartControl( 4965): Registering Services Ready callback...
I/UEI.SmartControl( 4965): Notify client services are ready...
D/UEI.SmartControl( 4965): -----IControl: 8
D/UEI.SmartControl( 4965): Caller: com.lge.qremote
,I/GAv4    ( 4947): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4947):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4947):   adb logcat -s GAv4
D/UEI.SmartControl( 4965): Internal service binding...
,W/libprocessgroup(  856): failed to open /acct/uid_1000/pid_4780/cgroup.procs: No such file or directory
W/GAv4    ( 4947): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4947): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4947): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 4947): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4947): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
W/ResourcesManager( 4947): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4947): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  856): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5007 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  856): Killing 4700:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_10106/pid_4700/cgroup.procs: No such file or directory
,I/art     ( 4947): CheckpointMarkThreadRoots callback created = 0xaaef02a0
,V/JNIHelp ( 4947): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 5007): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/art     ( 4947): CheckpointMarkThreadRoots callback created = 0xb050c9f0
W/System  ( 4947): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4947): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  856): Killing 4811:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  856): failed to open /acct/uid_10021/pid_4811/cgroup.procs: No such file or directory
,I/ActivityManager(  856): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5041 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/UpdateIcingCorporaServi( 2054): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/art     (  308): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 305us total 22.667ms
I/art     (  308): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.239ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 21.538ms
I/UpdateIcingCorporaServi( 2054): UpdateCorporaTask done [took 92 ms] updated apps [took 92 ms] 
,D/[BNRAppListMgrReceiver]( 5041): android.intent.action.PACKAGE_ADDED : com.example.hello
,I/ActivityManager(  856): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5063 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  856): Killing 4835:com.google.android.partnersetup/u0a9 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_10009/pid_4835/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/Finsky  ( 5063): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5063): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5063): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5063): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5063): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3206): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3206): created cursor android.database.sqlite.SQLiteCursor@9f2b2ec on behalf of 5063
I/NotificationManager( 5063): com.android.vending: cancel(-602347385) by com.android.vending
,D/Ads     ( 5063): Skipping gmscore version check
,I/ActivityManager(  856): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5106 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/ActivityManager(  856): enqueue in BackgroundQueue #51 Intent=Intent { act=com.lge.qremote.action.wait_loading flg=0x14 cmp=com.lge.qremote/.appwidget.RemoteAppWidgetProvider (has extras) }
D/Finsky  ( 5063): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 5063): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5063): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 5063): [1] ExternalReferrer.access$200: Package state data is missing for com.example.hello
D/Finsky  ( 5063): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  856): Killing 4858:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/ResourcesManager( 5106): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5106): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  856): failed to open /acct/uid_10011/pid_4858/cgroup.procs: No such file or directory
,I/MultiDex( 5106): VM with version 2.1.0 has multidex support
,I/MultiDex( 5106): install
,I/MultiDex( 5106): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 5106): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5106): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5106): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12397b77: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5106): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5106): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5106): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 5106): Reading stored module config
,D/PackageBroadcastService( 5106): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
D/ChimeraCfgMgr( 5106): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5106): Loading module APK com.google.android.play.games
,I/ActivityManager(  856): Waited long enough for: ServiceRecord{39c2b587 u0 com.android.calendar/.alerts.InitAlarmsService}
,D/NativeLibraryUtils( 5106): Install completed successfully. count=14 extracted=0
,I/art     ( 5106): CheckpointMarkThreadRoots callback created = 0xb042d3f0
,I/art     ( 5106): CheckpointMarkThreadRoots callback created = 0xb042d3d0
,D/ChimeraCfgMgr( 5106): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5106): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 5106): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 5106): Submit a task: k
,I/QCNEJ   ( 1929): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1929): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:56:49.873 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/ChimeraCfgMgr( 5106): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ChimeraCfgMgr( 5106): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/k       ( 5106): Processing package: com.example.hello
,D/GassUtils( 5106): Found app info for package com.example.hello:18. Hash: 68ddfd019b48f789223df845f1e49bbdc6edef025bd9dbaddc0e41222bbc602e
D/k       ( 5106): Found info for package com.example.hello in db.
,I/PeopleDatabaseHelper( 5106): cleanUpNonGplusAccounts done.
,I/ActivityManager(  856): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5152 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/Icing   ( 5106): Storage manager: low false usage 1.70MB avail 2.43GB capacity 4.06GB
,W/BaseAppContext( 5106): Using Auth Proxy for data requests.
,W/ResourcesManager( 5152): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/art     ( 5106): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5106): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
E/BaseAppContext( 5106): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,D/BluetoothManagerService(  856): Message: 20
D/BluetoothManagerService(  856): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3d70ae12:true
D/BluetoothAdapterService(292483291)( 2100): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e9dc689
D/BluetoothAdapterService(292483291)( 2100): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e9dc689
W/BaseAppContext( 5106): Using Auth Proxy for data requests.
,W/BaseAppContext( 5106): Using Auth Proxy for data requests.
,I/art     ( 4063): Explicit concurrent mark sweep GC freed 2814(111KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 398us total 26.587ms
,V/LGMDMManager( 5152): Create singleton instance
W/BaseAppContext( 5106): Using Auth Proxy for data requests.
W/BaseAppContext( 5106): Using Auth Proxy for data requests.
W/BaseAppContext( 5106): Using Auth Proxy for data requests.
W/BaseAppContext( 5106): Using Auth Proxy for data requests.
,I/AudioManager( 5152): getMode name:com.lge.qremote
,I/ActivityManager(  856): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=5190 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/UEI.SmartControl( 4965): -----IControl: 11
,D/UEI.SmartControl( 4965): Caller: com.lge.qremote
D/UEI.SmartControl( 4965): ------------ IControl registerCallback...
I/UEI.SmartControl( 4965): Registering callback...
D/UEI.SmartControl( 4965): -----IControl: 19
D/UEI.SmartControl( 4965): Caller: com.lge.qremote
I/UEI.SmartControl( 4965): Registering Services Ready callback...
I/UEI.SmartControl( 4965): Notify client services are ready...
D/UEI.SmartControl( 4965): -----IControl: 8
D/UEI.SmartControl( 4965): Caller: com.lge.qremote
I/ActivityManager(  856): Killing 4875:com.android.gallery3d/u0a23 (adj 15): empty #11
,I/Icing   ( 5106): updateResources: need to parse f{com.google.android.gms}
,W/libprocessgroup(  856): failed to open /acct/uid_10023/pid_4875/cgroup.procs: No such file or directory
W/ResourcesManager( 5190): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5190): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5190): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5190): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5190): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/IndexDatabaseHelper( 5190): Using schema version: 115
I/IndexDatabaseHelper( 5190): Index is fine
,V/WiFiOffLoadBroadcast( 5190): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/Icing   ( 5106): Internal init done: storage state 0
,I/NotificationManager( 5106): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/Icing   ( 5106): Post-init done
,D/WiFiOffLoadBroadcast( 5190): MCCMNC not supported: null
,I/ActivityManager(  856): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5216 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  856): Killing 4894:com.android.contacts/u0a18 (adj 15): empty #11
D/ChimeraCfgMgr( 5106): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5106): Module APK com.google.android.play.games already loaded
,W/libprocessgroup(  856): failed to open /acct/uid_10018/pid_4894/cgroup.procs: No such file or directory
,I/art     (  856): Explicit concurrent mark sweep GC freed 22504(1099KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 1.678ms total 135.654ms
,V/WiFiOffLoadBroadcast( 5190): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5190): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 5190): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5190): MCCMNC not supported: null
I/PCSuite ( 5216): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 5216): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 5190): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 5190): MCCMNC not supported: null
I/PCSuite ( 5216): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 5216): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  856): Killing 4913:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  856): failed to open /acct/uid_10069/pid_4913/cgroup.procs: No such file or directory
,V/SmsReceiverService( 3185): onStart: #1 mResultCode: -1 = Activity.RESULT_OK
,D/MmsConfig( 3185): isNotAllowedSms: currentUser:0
D/MmsConfig( 3185): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3185): isUserMode:false
D/SmsReceiverService( 3185): handleMessage isUserMode:false
V/SmsReceiverService( 3185): handleMessage action: com.android.mms.transaction.SEND_MESSAGE error: 0
D/SmsReceiverService( 3185): [LGE] handleSendMessage Send messages in queue
,I/[LGHome]LGNumberBadgeReceiver( 1966): [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = lge.intent.action.UNREAD_MESSAGES
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1966): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1966): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1966): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1966): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,I/ActivityManager(  856): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5252 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 5252): Database version: 120
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5252): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5252): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5252): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,W/ResourcesManager( 5252): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5252): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5252): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/KeyguardUpdateMonitor( 1390): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1390): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1390): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1390): On Skip Timer : true
,D/PowerService( 1883): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,W/ActivityThread( 5252): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5252): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2564368: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5252): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 5252): GMSCore installation verified
D/KeyguardUpdateMonitor( 1390): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/QCNEJ   ( 1929): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1390): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1929): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2100): Disconnected process message: 10, size: 0
,I/[SystemUI]LGPowerUI( 1390): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
D/LEDHandler( 1883): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1883): Battery Level Remaining: 100%
D/LEDHandler( 1883): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
D/charger_monitor(  481): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
W/Settings(  856): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  856): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/PowerService( 1883): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/WifiController(  856): battery changed pluggedType: 2
,I/[SystemUI]BatterySaverHandler( 1390): onReceive = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1390): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1390): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1390): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1390): On Skip Timer : true
I/ConfigStore( 5252): Config Database version: 1
I/Icing   ( 5106): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/ActivityManager(  856): Waited long enough for: ServiceRecord{28b70b26 u0 com.lge.springcleaning/.service.AppCleanupService}
,D/Icing   ( 5106): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 5106): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/MediaRouter( 5252): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 5252): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 5252): type=WIFI subType= reason=null isConnected=true
,I/[LGHome]EVENT( 1966): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[SystemUI]QPairHandler( 1390): onReceive = android.intent.action.PACKAGE_CHANGED
I/QCNEJ   ( 1929): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[LGHome]LGPlusHomeDBManager( 1966): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1966): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[SystemUI]QSlideListController( 1390): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1390): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1390): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1390): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/InputReader(  856): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 1859): CheckpointMarkThreadRoots callback created = 0xaaf21bc0
,I/ActivityManager(  856): Killing 4930:com.lge.eula/1000 (adj 15): empty #11
I/[LGHome]Launcher( 1966): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/administrator(  856): Handling package changes for user 0
,I/art     ( 1859): CheckpointMarkThreadRoots callback created = 0xb042d6a0
W/libprocessgroup(  856): failed to open /acct/uid_1000/pid_4930/cgroup.procs: No such file or directory
I/NetworkMonitor( 5252): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  856): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=5292 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 5252): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5252): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 5292): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5292): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5292): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  856): Killing 4947:com.google.android.apps.docs/u0a58 (adj 15): empty #11
I/NotificationService(  856): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  856): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  856): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/ResourcesManager(  856): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  856): failed to open /acct/uid_10058/pid_4947/cgroup.procs: No such file or directory
,I/NotificationManager( 5252): com.google.android.music: cancel(1061) by com.google.android.music
I/BackupManagerService(  856): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/LGEmail ( 5292): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,V/BackupManagerService(  856): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  856): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@4e0faea
D/LGEmail ( 5292): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
D/UEI.SmartControl( 4965): Internal timer expired: 1
,W/ResourceType(  856): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,D/LCardEmulationManager( 1859): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1859): getDefaultRoute
I/[LGHome]EVENT( 1966): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1761): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  856): applying state to connected service
,D/eas_req ( 5292): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  856): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=5319 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 5292): JNI_OnLoad()
I/HubEmail( 5292): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5292): registerNatives()
I/HubEmail( 5292): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5292): registerNativeMethods()
I/HubEmail( 5292): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 5292): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  856): Killing 5007:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_10086/pid_5007/cgroup.procs: No such file or directory
,W/Settings( 5292): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 5319): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 5319): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 5319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 5319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 5319): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 5319): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 5319): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 5319): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  856): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=5343 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 5319): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 5319): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 5319): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 5319): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 5319): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 5319): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  856): Killing 5041:com.lge.bnr/1000 (adj 15): empty #11
,W/libprocessgroup(  856): failed to open /acct/uid_1000/pid_5041/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 5343): onCreate
,W/AppUp4:DB( 5343):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 5343):  setFingerPrint start
,I/AppUp4:DB( 5343):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5343):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5343):  SDK version = 0
I/AppUp4:DB( 5343):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5343): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 5343): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 5343): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 5343): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 5343): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 5343): onReceive
I/AppUp4:CustModeStarterReceiver( 5343): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 5343): Context : android.app.ReceiverRestrictedContext@23cfe8c
D/AppUp4:CustFacade( 5343): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5343): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 5343): begin check event
I/AppUp4:CustModeStarterReceiver( 5343): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 5343): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 5343): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 5343): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 5343): handleAsyncCustNotification do not startCustService
I/ActivityManager(  856): Killing 5063:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  856): failed to open /acct/uid_10036/pid_5063/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3185): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3185): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3185): networkInfo.isConnected() = true
D/PhoneState( 3185): setPdpRejectCasuse : false
,I/ActivityManager(  856): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5365 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 5365): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 5365): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 5365): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  856): Killing 5190:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_1000/pid_5190/cgroup.procs: No such file or directory
,V/DownloadManager( 3206): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3206): DownloadService onCreate
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
I/DownloadManager( 3206): in removeSpuriousFiles
V/DownloadManager( 3206): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/ActivityManager(  856): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=5386 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/NotificationManager( 3206): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/art     (  308): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 313us total 23.537ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 298us total 22.033ms
,V/DownloadManager( 3206): created cursor android.database.sqlite.SQLiteCursor@83df8bb on behalf of 3206
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 26.410ms
V/DownloadManager( 3206): DownloadService onStartCommand
V/DownloadManager( 3206): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 3206): in trimDatabase
V/DownloadManager( 3206): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3206): created cursor android.database.sqlite.SQLiteCursor@30cd5816 on behalf of 3206
V/DownloadManager( 3206): created cursor android.database.sqlite.SQLiteCursor@f496597 on behalf of 3206
I/CheckinService( 5106): Checkin interval check for package: unspecified last checkin: 1452525992039 min interval config: 0 actual interval: 1821655
,D/PhoneMonitor( 5365): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
I/CheckinService( 5106): Disabling old GoogleServicesFramework version
,V/TelephonyAutoProfiling( 5365): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5365): [parse] Load xml
V/TelephonyAutoProfiling( 5365): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5365): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 5365): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/DrmBroadcastReceiver( 5386): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 5386): 1  network is available. Sync DRM Time with NTP
V/DrmService( 5386): Service onCreate
D/DrmService( 5386): Received new request = 2
,D/WeatherAncestor( 2715): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:56:53
D/UpdateThreadPoolManager( 2715): 2 : This is isUpdating : false
I/DrmSntpClient( 5386): Start Sync process
D/DrmSntpClient( 5386): Server : 0
D/WeatherAncestor( 2715): connectivity changed - connection : true
D/Weather_cast( 2715): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2715): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 16:56:53
D/WeatherService( 2715): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
D/libc-netbsd( 5386): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5386): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5386): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5386): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10051
,D/DnsProxyListener(  280): App 10051 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  856): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5419 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  856): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2715): 2 : Utils getTopActivity com.lge.launcher2 / true
V/DownloadManager( 3206): DownloadService onDestroy
D/WeatherService( 2715): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2715): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/CheckinService( 5106): Checking schedule, now: 1452527813813 next: 1452526022005
I/CheckinService( 5106): active receiver: enabled
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/CheckinService( 5106): Preparing to send checkin request
I/EventLogService( 5106): Accumulating logs since 1452527735245
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out( 5386): propertyValue:false
,W/ResourcesManager( 5419): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/LGDrmClient( 5386): _DRM_ServiceGet() : Bind lgdrm service
,V/ILGDrmService(  291): eDRM_SetDRMTime +++
I/LGDRM   (  291): [DRM] SET TIME : YR=2016, MON=1, DAY=11
I/LGDRM   (  291): [DRM] SET TIME : HR=15, MIN=56, SEC=52
V/ILGDrmService(  291): eDRM_SetDRMTime ---
,I/DrmSntpClient( 5386): Synched
D/DrmService( 5386): Completed !! request = 2
D/DrmService( 5386): Request count = 0
V/DrmService( 5386): Service onDestroy
I/CheckinRequestBuilder( 5106): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5106): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  856): Explicit concurrent mark sweep GC freed 21430(1134KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.091ms total 136.943ms
,I/Babel_SMS( 5419): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5419): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5419): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5419): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5419): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5419): MmsConfig.loadFromResources
E/Babel_SMS( 5419): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5419): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SensorManager( 5419): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5419): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5419): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5419): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5419): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5419): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5419): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5419): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5419): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5419): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5419): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5419): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5419): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5419): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5419): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5419): found sensor: Motion Accel, handle=46
,W/Settings( 5419): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5419): startup - clean
,I/art     ( 5419): CheckpointMarkThreadRoots callback created = 0xb042d4b0
I/art     ( 5419): CheckpointMarkThreadRoots callback created = 0xb042d490
,I/Babel   ( 5419): deleted: false for 0
W/AudioCapabilities( 5419): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5419): Unsupported mime audio/adpcm
W/AudioCapabilities( 5419): Unsupported mime audio/g726
W/AudioCapabilities( 5419): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5419): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5419): Unsupported mime video/mjpg
W/VideoCapabilities( 5419): Unsupported mime video/theora
W/AudioCapabilities( 5419): Unsupported mime audio/evrc
,W/AudioCapabilities( 5419): Unsupported mime audio/qcelp
W/VideoCapabilities( 5419): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  856): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5465 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 5419): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 5419): Unsupported mime audio/qcelp
W/AudioCapabilities( 5419): Unsupported mime audio/evrc
,D/libc-netbsd( 1761): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1761): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1761): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1761): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
W/VideoCapabilities( 5419): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5419): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5419): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5419): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5419): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5419): Unrecognized profile 2130706433 for video/avc
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 1761): propertyValue:false
I/vclib   ( 5419): onServiceConnected
W/Babel   ( 5419): Attempted to change video mute state without an active call.
,D/libc-netbsd( 5419): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5419): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5419): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5419): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  280): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 5419): propertyValue:false
I/NotificationManager( 5419): com.google.android.talk: cancel(10436) by com.google.android.talk
I/Babel   ( 5419): connection state changed from UNKNOWN to CONNECTED
,W/art     ( 5419): Suspending all threads took: 5.073ms
I/ActivityManager(  856): Killing 4965:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,D/libc-netbsd( 1761): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1761): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/System.err( 5152): android.os.DeadObjectException
,W/System.err( 5152): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5152): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5152): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5152): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5152): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5152): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5152): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5152): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5152): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5152): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5152): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5152): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5152): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5152): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5152): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5152): android.os.DeadObjectException
D/libc-netbsd( 1761): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1761): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/System.err( 5152): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5152): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5152): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5152): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5152): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5152): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5152): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5152): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5152): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5152): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5152): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5152): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5152): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5152): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5152): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
D/libc-netbsd( 1761): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1761): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/libprocessgroup(  856): failed to open /acct/uid_10089/pid_4965/cgroup.procs: No such file or directory
,W/ActivityManager(  856): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  856): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5492 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5465): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5465): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/UEI.SmartControl( 5492): Quickset Services start...
,I/UEI.SmartControl( 5492): Manufacture = LGE
D/UEI.SmartControl( 5492): File observer start...
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
E/UEI.SmartControl( 5492): IR Port is disabled: false
W/ContextImpl( 5465): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
D/UEI.SmartControl( 5492): Starting file observer...
D/UEI.SmartControl( 5492): Extracting JNI libs...
D/UEI.SmartControl( 5492): --- this system supports 32-bit or 64-bit only
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5465): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 5465): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5465):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5465):   adb logcat -s GAv4
,W/GAv4    ( 5465): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/NotificationManager(  856): android: cancelAsUser(2) by android
D/UEI.SmartControl( 5492): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5492): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5492): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/NotificationManager( 1761): com.google.android.gms: cancel(0) by com.google.android.gms
W/GAv4    ( 5465): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/UEI.SmartControl( 5492): --- Selecting new region: 2
W/GAv4    ( 5465): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/UEI.SmartControl( 5492): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 5492): Platform has CIR...
D/UEI.SmartControl( 5492): NO CIR support, need to check package...
I/UEI.SmartControl( 5492): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5492): QS Service created
,E/UEI.SmartControl( 5492): QS start get config
,I/ActivityManager(  856): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5517 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/UEI.SmartControl( 5492): Loading JNI Libs...
D/UEI.SmartControl( 5492):  configuring local db...
,W/ResourcesManager( 5517): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5517): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5517): VM with version 2.1.0 has multidex support
I/MultiDex( 5517): install
I/MultiDex( 5517): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5517): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5517): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5517): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@14cd3d69: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5517): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 5517): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5517): com.google.android.gms: cancel(39789) by com.google.android.gms
D/UEI.SmartControl( 5492):  ---- Has DB8: true
,I/art     ( 5517): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 5517): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/UEI.SmartControl( 5492): QS start statue = true Error code = 0
D/UEI.SmartControl( 5492): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5492): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5492): IRRCDataComm has AudioManager!!!!.
I/WebViewFactory( 5465): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/irrc_jni( 5492): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5492): IrrcClient ++ 
D/irrcClient( 5492): getIrrcService ++ 
D/irrcClient( 5492): getIrrcService -- 
D/irrcClient( 5492): IrrcClient -- 
W/irrc_jni( 5492): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5492): Services init done
,I/UEI.SmartControl( 5492): Device manager: loading config....
D/UEI.SmartControl( 5492): Config is loaded...
D/UEI.SmartControl( 5492): QS Service init finished
I/LibraryLoader( 5465): Time to load native libraries: 2 ms (timestamps 636-638)
,I/LibraryLoader( 5465): Expected native library version number "",actual native library version number ""
D/UEI.SmartControl( 5492): QS Service version name: 0.1.73
D/UEI.SmartControl( 5492): QS Service version code: 1073
D/UEI.SmartControl( 5492): Service requested: Control
D/UEI.SmartControl( 5492): -----IControl: 11
D/UEI.SmartControl( 5492): Internal service binding...
,D/UEI.SmartControl( 5492): Caller: com.lge.qremote
D/UEI.SmartControl( 5492): ------------ IControl registerCallback...
I/UEI.SmartControl( 5492): Registering callback...
D/UEI.SmartControl( 5492): -----IControl: 19
D/UEI.SmartControl( 5492): Caller: com.lge.qremote
I/UEI.SmartControl( 5492): Registering Services Ready callback...
D/UEI.SmartControl( 5492):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5492): Notify client services are ready...
I/UEI.SmartControl( 5492): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5492): -----IControl: 8
D/UEI.SmartControl( 5492): Caller: com.lge.qremote
V/WebViewChromiumFactoryProvider( 5465): Binding Chromium to main looper Looper (main, tid 1) {30f352d9}
,I/LibraryLoader( 5465): Expected native library version number "",actual native library version number ""
I/chromium( 5465): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5465): Initializing chromium process, singleProcess=true
,W/art     ( 5465): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5465): ApplicationContext is null in ApplicationStatus
W/chromium( 5465): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5465): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5465): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5465): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5465): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5465): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5465): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5465): Remote Branch: 
I/Adreno-EGL( 5465): Local Patches: 
I/Adreno-EGL( 5465): Reconstruct Branch: 
D/NativeLibraryUtils( 5517): Install completed successfully. count=14 extracted=0
D/WVCdm   (  284): Instantiating CDM.
I/WVCdm   (  284): CdmEngine::OpenSession
I/WVCdm   (  284): Level3 Library Dec 11 2014 16:13:16
,W/WVCdm   (  284): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  284): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  284): L1 library not specified. Falling Back to L3
,I/NSApplication( 5465): Starting up...
,V/AudioPolicyService(  284): registerClient() client 0xb39ad320, uid 10079
W/AudioManagerAndroid( 5465): Requires BLUETOOTH permission
I/WVCdm   (  284): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  284): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  284): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  284): CdmEngine::GenerateKeyRequest
D/WVCdm   (  284): PrepareKeyRequest: nonce=4140433766
I/ActivityManager(  856): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5572 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  856): Killing 5152:com.lge.qremote/u0a106 (adj 15): empty #11
I/ActivityManager(  856): Killing 5216:com.lge.sync/1000 (adj 15): empty #12
,I/art     ( 5517): CheckpointMarkThreadRoots callback created = 0xaaf48f30
,W/libprocessgroup(  856): failed to open /acct/uid_10106/pid_5152/cgroup.procs: No such file or directory
W/libprocessgroup(  856): failed to open /acct/uid_1000/pid_5216/cgroup.procs: No such file or directory
,I/art     ( 5517): CheckpointMarkThreadRoots callback created = 0xaaf48f20
,I/dex2oat ( 5590): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 5590): dex2oat took 117.568ms (threads: 4)
,I/ActivityManager(  856): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5598 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  856): Killing 5252:com.google.android.music:main/u0a81 (adj 15): empty #11
,I/Adreno-EGL( 5517): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5517): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5517): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5517): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5517): Remote Branch: 
I/Adreno-EGL( 5517): Local Patches: 
I/Adreno-EGL( 5517): Reconstruct Branch: 
W/libprocessgroup(  856): failed to open /acct/uid_10081/pid_5252/cgroup.procs: No such file or directory
,W/ResourcesManager( 5598): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  856): Killing 5292:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  856): failed to open /acct/uid_10021/pid_5292/cgroup.procs: No such file or directory
,I/iu.SyncManager( 5106): SYNC; picasa accounts
,D/NetworkLogImpl( 5106): Loaded NetworkSpeedPredictor
,I/iu.Environment( 5106): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 5106): num queued entries: 0
I/iu.UploadsManager( 5106): num updated entries: 0
I/iu.SyncManager( 5106): NEXT; no task
,I/ActivityManager(  856): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5629 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/WVCdm   (  284): CdmEngine::OpenSession
,W/ResourcesManager( 5629): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/BluetoothManagerService(  856): Message: 20
D/BluetoothManagerService(  856): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3885086a:true
,D/BluetoothAdapterService(292483291)( 2100): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e9dc689
D/BluetoothAdapterService(292483291)( 2100): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3e9dc689
I/ActivityManager(  856): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=5649 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/DigitalAppWidgetProvider( 5649): onReceive: android.intent.action.ALARM_CHANGED
,I/ActivityManager(  856): Killing 5319:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_1000/pid_5319/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2715): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 16:56:57
D/UpdateThreadPoolManager( 2715): 2 : This is isUpdating : false
D/Weather_cast( 2715): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2715): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 16:56:57
D/WeatherService( 2715): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
I/ActivityManager(  856): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=5669 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
W/ActivityManager(  856): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2715): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/sensors_hal_Time(  856): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time(  856): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/WeatherService( 2715): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2715): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/sensors_hal_Time(  856): tsOffsetIs: Apps: 72782629248; DSPS: 2476476; Offset : -2795211624
,W/ResourcesManager( 5669): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5669): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5669): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5669): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5669): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/IndexDatabaseHelper( 5669): Using schema version: 115
,I/IndexDatabaseHelper( 5669): Index is fine
I/WVCdm   (  284): CdmEngine::CloseSession
,D/UsbSettingsReceiver( 5669): [AUTORUN] onReceive() : action = android.hardware.usb.action.USB_STATE
D/UsbSettingsReceiver( 5669): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 5669): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5669): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5669): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsReceiver( 5669): [AUTORUN] onReceive() : getDefaultFunction = ptp_only
D/UsbSettingsReceiver( 5669): [AUTORUN] onReceive() : USB_FUNCTION_CDROM_STORAGE = false
D/UsbSettingsReceiver( 5669): [AUTORUN] onReceive() : mDirectAutorun = true
D/UsbSettingsReceiver( 5669): [AUTORUN] onReceive() : mActivityUsbModeChange = false
,D/UsbSettingsReceiver( 5669): [AUTORUN] onReceive() : mActivityFinish = false
D/UsbSettingsReceiver( 5669): [AUTORUN] onReceive() : ===== USB Configured =====
,I/WVCdm   (  284): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  284): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  284): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  284): CdmEngine::GenerateKeyRequest
D/UsbSettingsControl( 5669): [AUTORUN] setUsbConnected() : connected=true
D/UsbSettingsReceiver( 5669): [AUTORUN] onReceive() : checkQmicm = ptp_only,adb
D/WVCdm   (  284): PrepareKeyRequest: nonce=87976905
D/UsbSettingsReceiver( 5669): [AUTORUN] : topPackageName=com.example.hello
D/UsbSettingsReceiver( 5669): [AUTORUN] : topClassName=com.example.hello.MainActivity
D/UsbSettingsReceiver( 5669): [AUTORUN] Not exist com.android.LGSetupWizard
D/UsbSettingsReceiver( 5669): [AUTORUN] setUsbConnect() : mUsbSettingsRun = false
,D/UsbSettingsReceiver( 5669): [AUTORUN] startUsbSettings() : deviceProvisioned=1
I/ActivityManager(  856): Killing 5343:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_10011/pid_5343/cgroup.procs: No such file or directory
,I/ActivityManager(  856): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5690 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/MtpService( 3206): updating state; isCurrentUser=true, mMtpLocked=false
,I/PCSuite ( 5690): [StartReceiver]USB CONNECTED ver UsbManger : ptp_only
I/PCSuite ( 5690): [StartReceiver]isUsbPCSuiteMode : false
,D/PCSuite ( 5690): [StartReceiver][checkEUTStatus] eutStatus = 
,D/PCSuite ( 5690): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5690): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  856): Killing 5365:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_10038/pid_5365/cgroup.procs: No such file or directory
,V/LGMDMManager( 5629): Create singleton instance
,I/DigitalAppWidgetProvider( 5649): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 2715): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 16:56:58
D/UpdateThreadPoolManager( 2715): 2 : This is isUpdating : false
D/Weather_cast( 2715): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2715): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 16:56:58
D/AlertReceiver( 3905): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
D/WeatherService( 2715): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
,W/ActivityManager(  856): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2715): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2715): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2715): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/AlertService( 3905): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 3905): [updateWidgets] 
,D/MonthWidgetProvider( 3905): [onReceive]
D/CalendarWidgetProvider( 3905): [onReceive]
D/CalendarWidgetProvider( 3905): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 3905): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 3905): [onReceive]
D/CalendarWidgetProvider( 3905): [onReceive]
D/CalendarWidgetProvider( 3905): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,D/CalendarTypeController( 3905): [onCreate] mContext.getPackageName() = com.android.calendar
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
I/[SystemUI]SafeModeBroadcastReceiver( 1390): onReceive = com.lge.statusbar.bootcompleted
,D/CalendarWeatherReceiver( 3905): Get action=com.lge.calendar.action.WEATHER_SERVICE_START
,I/ActivityManager(  856): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5715 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 21.884ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 20.626ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 20.637ms
I/MusicStore( 5715): Database version: 120
,I/art     ( 4063): Explicit concurrent mark sweep GC freed 1883(69KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 411us total 26.480ms
,I/QCNEJ   ( 1929): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1929): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:56:58.918 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5715): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5715): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5715): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 5715): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5715): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5715): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5715): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5715): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2564368: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5715): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5715): GMSCore installation verified
I/ConfigStore( 5715): Config Database version: 1
,I/MediaRouter( 5715): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 5715): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  856): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.DamagedFileRemover: pid=5744 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/NetworkMonitor( 5715): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 5715): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5715): Using platform SSLCertificateSocketFactory
I/ActivityManager(  856): Killing 5386:com.lge.drmservice/u0a51 (adj 15): empty #11
,I/art     (  856): Explicit concurrent mark sweep GC freed 20130(1109KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.418ms total 165.353ms
,W/libprocessgroup(  856): failed to open /acct/uid_10051/pid_5386/cgroup.procs: No such file or directory
,I/NotificationManager( 5715): com.google.android.music: cancel(1061) by com.google.android.music
E/stst    ( 5744): DamagedFileRemover media scanning start or checking
,D/ToneMappingReceiver( 5649): Enter doAlarmRingToneUriMapping()
D/ToneMappingReceiver( 5649): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5649): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
,D/CommonUtil( 5649): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5649): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5649): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5649): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5649): Alarm Success count is 0
D/ToneMappingReceiver( 5649): Timer Success count is 0
I/ActivityManager(  856): Killing 5419:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_10061/pid_5419/cgroup.procs: No such file or directory
I/MediaScannerReceiver( 3905): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///system/media
,I/InitNotificationRingtoneService( 3905): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3905): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
E/stst    ( 5744): DamagedFileRemover media scanning finished
,I/AlertUtils( 3905): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/com.lge.bnr.receiver.DamagedFileRemover( 5744): android.intent.action.MEDIA_SCANNER_FINISHED
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,E/stst    ( 5744): DamagedFileRemover media scanning start or checking
D/ToneMappingReceiver( 5649): Enter doAlarmRingToneUriMapping()
D/ToneMappingReceiver( 5649): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5649): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
D/CommonUtil( 5649): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5649): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5649): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
D/ToneMappingReceiver( 5649): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5649): Alarm Success count is 0
D/ToneMappingReceiver( 5649): Timer Success count is 0
,I/MediaScannerReceiver( 3905): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///storage/emulated/0
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3905): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 3905): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3905): End InitializeAlertRingtoneService.onHandleIntent
I/InitNotificationRingtoneService( 3905): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3905): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
E/stst    ( 5744): DamagedFileRemover media scanning finished
I/com.lge.bnr.receiver.DamagedFileRemover( 5744): android.intent.action.MEDIA_SCANNER_FINISHED
,I/art     ( 5715): CheckpointMarkThreadRoots callback created = 0xaaf1c630
I/art     ( 5715): CheckpointMarkThreadRoots callback created = 0xaaf1c600
,I/ActivityManager(  856): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5775 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/AlertUtils( 3905): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
,D/WeatherService( 2715): 2 : TimeTick Intent has been received, Time(hour:min:sec) 16:57:0
D/WeatherService( 2715): 2 : TimeTick Intent And Screen On
D/WeatherService( 2715): 2 : SDK version : 21
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
W/ActivityManager(  856): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2715): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2715): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2715): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2715): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2715): 2 : This is isUpdating : false
D/WeatherService( 2715): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2715): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2715): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2715): 2 : Fixed theme : optimus
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
D/WeatherReflect( 2715): 2 : Map key string is -2
,D/lim     ( 2715): 2 : time = 16:57
I/WeatherReflect( 2715): Model Name : LG-D722
D/WeatherTheme( 2715): 2 : Different view - status_min_formatted : 56 != 57
D/WeatherTheme( 2715): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2715): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
D/Theme   ( 2715): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2715): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
W/ResourcesManager( 5775): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
D/Weather4x2_optimus( 2715): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2715): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2715): forecast size is 0
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
D/Theme   ( 2715): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2715): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2715): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2715): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2715): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2715): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2715): setTouchIntent, appWidgetId: 2
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,D/Theme_WeatherAncestor_optimus( 2715): url is : null
D/Theme   ( 2715): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2715): 2 : update view, appWidgetId: 2
D/WeatherService( 2715): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 16:57:0
D/CalendarProvider2( 5775): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@3f3ae692
,I/WVCdm   (  284): CdmEngine::CloseSession
I/art     ( 3206): Explicit concurrent mark sweep GC freed 5817(386KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/10MB, paused 514us total 43.310ms
I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/WVCdm   (  284): L3 Terminate.
,I/AlertUtils( 3905): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3905): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
D/CalendarProvider2( 5775): [getOrCreateCalendarAlarmManager]
I/AlertUtils( 3905): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3905): End InitializeAlertRingtoneService.onHandleIntent
I/Adreno-EGL( 5517): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5517): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5517): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5517): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5517): Remote Branch: 
I/Adreno-EGL( 5517): Local Patches: 
I/Adreno-EGL( 5517): Reconstruct Branch: 
I/CalendarProvider2( 5775): Created com.android.providers.calendar.CalendarAlarmManager@375e97bf(com.android.providers.calendar.CalendarProvider2@3f3ae692)
,D/CalendarProviderBroadcastReceiver( 5775): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 5775): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 5775): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 5775): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 5775): [getOrCreateCalendarAlarmManager]
I/Adreno-EGL( 5517): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5517): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5517): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5517): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5517): Remote Branch: 
I/Adreno-EGL( 5517): Local Patches: 
I/Adreno-EGL( 5517): Reconstruct Branch: 
,I/ActivityManager(  856): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5797 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/[LgeWidgetLib]LgeAppWidgetHostView( 1966): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/CheckinRequestBuilder( 5106): Classify the device as Phone.
D/CalendarProvider2( 5775): [IntentService] Release Lock
,D/CalendarProvider2( 5775): CalendarProviderIntentService.onDestroy()
W/ResourcesManager( 5797): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/MediaStoreImporter( 5715): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  856): Killing 5465:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
E/[LgeWidgetLib]LgeAppWidgetHostView( 1966): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,W/libprocessgroup(  856): failed to open /acct/uid_10079/pid_5465/cgroup.procs: No such file or directory
,D/libc-netbsd( 5106): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5106): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5106): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5106): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 5106): propertyValue:false
,I/Babel_SMS( 5797): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5797): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5797): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5797): MmsConfig.loadFromDatabase
I/[SystemUI]TimeTickManager( 1390): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1390): called onTimeUpdated()
,D/libc-netbsd( 5106): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5106): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]Clock( 1390): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1390): called onTimeUpdated()
I/[SystemUI]DateView( 1390): called onTimeUpdated()
I/[SystemUI]DateView( 1390): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1390): handleTimeUpdate
E/Babel_SMS( 5797): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5797): MmsConfig.loadFromResources
E/Babel_SMS( 5797): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5797): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/UEI.SmartControl( 5492): Internal timer expired: 1
D/UEI.SmartControl( 5492): Service.onUnbind: IControl
D/UEI.SmartControl( 5492): Service.onDestroy
,D/UEI.SmartControl( 5492): Shutdown IRRCPlayer... 
D/libc-netbsd( 5106): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5106): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/irrc_jni( 5492): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5492): ~IrrcClient ++ 
D/irrcClient( 5492): ~IrrcClient -- 
W/irrc_jni( 5492): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5492): Blaster closed
D/UEI.SmartControl( 5492): Blaster closed
D/UEI.SmartControl( 5492): Shut down QS...
D/UEI.SmartControl( 5492): Stopped file observer...
I/UEI.SmartControl( 5492): QS lib stop result = true
D/UEI.SmartControl( 5492): QS shutdown complete
,D/libc-netbsd( 5106): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5106): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/SensorManager( 5797): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5797): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5797): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5797): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5797): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5797): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5797): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5797): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5797): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5797): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5797): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5797): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5797): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5797): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5797): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5797): found sensor: Motion Accel, handle=46
W/Settings( 5797): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5797): startup - clean
I/CheckinTask( 5106): Sending checkin request (9822 bytes)
I/Babel   ( 5797): deleted: false for 0
,I/art     ( 5797): CheckpointMarkThreadRoots callback created = 0xb042d8b0
,I/art     ( 5797): CheckpointMarkThreadRoots callback created = 0xb042d890
,W/AudioCapabilities( 5797): Unsupported mime audio/x-lg-flac
D/WearableService( 1761): callingUid 10006, callindPid: 1761
,W/AudioCapabilities( 5797): Unsupported mime audio/adpcm
D/LocationInitializer( 5106): Restart initialization of location
W/AudioCapabilities( 5797): Unsupported mime audio/g726
,W/AudioCapabilities( 5797): Unsupported mime audio/x-ms-wma
E/MDM     ( 1761): [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
W/AudioCapabilities( 5797): Unsupported mime audio/wma-voice
D/AuthorizationBluetoothService( 1761): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
W/VideoCapabilities( 5797): Unsupported mime video/mjpg
,W/VideoCapabilities( 5797): Unsupported mime video/theora
V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1761): com.google.android.gms: cancel(0) by com.google.android.gms
W/AudioCapabilities( 5797): Unsupported mime audio/evrc
W/AudioCapabilities( 5797): Unsupported mime audio/qcelp
W/VideoCapabilities( 5797): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5797): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5797): Unsupported mime audio/qcelp
W/AudioCapabilities( 5797): Unsupported mime audio/evrc
I/ActivityManager(  856): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5842 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1761): No location to return for getLastLocation()
W/FusedLocationProvider( 1761): location=null
,W/VideoCapabilities( 5797): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5797): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5797): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5797): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5797): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5797): Unrecognized profile 2130706433 for video/avc
W/IcingInternalCorpora( 5106): getNumBytesRead when not calculated.
,I/vclib   ( 5797): onServiceConnected
,V/AlarmManager(  856): ELAPSED_WAKEUP set : Alarm{1970fcf5 type 2 when 76132 android} when 76132
W/Babel   ( 5797): Attempted to change video mute state without an active call.
W/ResourcesManager( 5797): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5797): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5797): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/CheckinRequestBuilder( 5106): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5106): Failed to find provider info for com.google.android.wearable.settings
W/System  ( 5797): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5797): Installed default security provider GmsCore_OpenSSL
,I/art     (  856): Explicit concurrent mark sweep GC freed 9512(416KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.044ms total 133.966ms
,W/ActivityManager(  856): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/NotificationManager( 5797): com.google.android.talk: cancel(10436) by com.google.android.talk
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5842): getAccountsCursor
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5842): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/CheckinRequestBuilder( 5106): Classify the device as Phone.
,W/ActivityManager(  856): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/CheckinTask( 5106): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5106): Checking schedule, now: 1452527821638 next: 1453055070632
I/CheckinService( 5106): active receiver: disabled
I/Gmail   ( 5842): getAccountsCursor
,W/ActivityManager(  856): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/Gmail   ( 5842): Error finding the version of the Email provider.....
E/Gmail   ( 5842): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5842): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5842): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5842): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5842): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5842): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5842): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5842): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 5842): We do not support migrating this version of the Email provider.
D/CheckinService( 5106): Recording last checkin time for package unspecified as 1452527821677
W/ActivityManager(  856): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  856): Killing 5492:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/Gmail   ( 5842): Observing account changes for notifications
W/libprocessgroup(  856): failed to open /acct/uid_10089/pid_5492/cgroup.procs: No such file or directory
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1761): No location to return for getLastLocation()
W/FusedLocationProvider( 1761): location=null
,V/DownloadManager( 3206): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3206): created cursor android.database.sqlite.SQLiteCursor@37a1976d on behalf of 5106
I/ActivityManager(  856): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5904 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/QCNEJ   ( 1929): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/QCNEJ   ( 1929): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:57:01.932 DNS addrs= 192.168.1.1, 0.0.0.0, 
W/InstanceID/Rpc( 5106): Found 10006
,I/Gmail   ( 5842): notifyAccountChanged
I/Gmail   ( 5842): getAccountsCursor
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5842): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5842): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/DownloadManager( 3206): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3206): created cursor android.database.sqlite.SQLiteCursor@373edfa2 on behalf of 5106
V/DownloadManager( 3206): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3206): created cursor android.database.sqlite.SQLiteCursor@734c433 on behalf of 5106
,I/Gmail   ( 5842): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5842): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5842): getAccountsCursor
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PhoneMonitor( 5904): Register our PhoneStateListener
,I/ActivityManager(  856): Killing 5572:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  856): failed to open /acct/uid_10048/pid_5572/cgroup.procs: No such file or directory
,D/PhoneMonitor( 5904): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5904): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 5904): [parse] Load xml
,D/GCM     ( 1761): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/CheckinService( 5106): Checkin interval check for package: unspecified last checkin: 1452527821677 min interval config: 0 actual interval: 464
V/TelephonyAutoProfiling( 5904): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5904): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 5904): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/CheckinService( 5106): Checking schedule, now: 1452527822152 next: 1452527851632
I/CheckinService( 5106): active receiver: disabled
I/ActivityManager(  856): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5930 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AudioManager( 5629): getMode name:com.lge.qremote
I/AudioManager( 5629): getMode name:com.lge.qremote
,I/AudioManager( 5629): getMode name:com.lge.qremote
,I/AudioManager( 5629): getMode name:com.lge.qremote
,E/MDM     ( 1761): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/UEI.SmartControl( 5930): Quickset Services start...
I/UEI.SmartControl( 5930): Manufacture = LGE
D/LocationInitializer( 5106): Restart initialization of location
,D/UEI.SmartControl( 5930): File observer start...
E/UEI.SmartControl( 5930): IR Port is disabled: false
D/UEI.SmartControl( 5930): Starting file observer...
D/UEI.SmartControl( 5930): Extracting JNI libs...
D/AuthorizationBluetoothService( 1761): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/UEI.SmartControl( 5930): --- this system supports 32-bit or 64-bit only
V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1761): com.google.android.gms: cancel(0) by com.google.android.gms
I/AudioManager( 5629): getMode name:com.lge.qremote
W/GCoreFlp( 1761): No location to return for getLastLocation()
W/FusedLocationProvider( 1761): location=null
,I/AudioManager( 5629): getMode name:com.lge.qremote
D/UEI.SmartControl( 5930): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5930): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5930): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/NotificationManager( 5797): com.google.android.talk: cancel(8) by com.google.android.talk
I/UEI.SmartControl( 5930): --- Selecting new region: 2
I/UEI.SmartControl( 5930): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 5930): Platform has CIR...
D/UEI.SmartControl( 5930): NO CIR support, need to check package...
I/UEI.SmartControl( 5930): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5930): QS Service created
I/ActivityManager(  856): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5958 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,E/UEI.SmartControl( 5930): QS start get config
,I/AppUp4:AppBoxCP( 5958): onCreate
,W/AppUp4:DB( 5958):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 5958):  setFingerPrint start
I/AppUp4:DB( 5958):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5958):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5958):  SDK version = 0
I/AppUp4:DB( 5958):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 5958): AppBoxApplication onCreate()
D/UEI.SmartControl( 5930): Loading JNI Libs...
D/UEI.SmartControl( 5930):  configuring local db...
I/AppUp4:CustModeStarterReceiver( 5958): onReceive
I/AppUp4:CustModeStarterReceiver( 5958): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 5958): Context : android.app.ReceiverRestrictedContext@32466519
D/AppUp4:CustFacade( 5958): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5958): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5958): begin check event
I/AppUp4:CustModeStarterReceiver( 5958): Event For Nothing, skip.
I/ActivityManager(  856): Killing 5598:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/libprocessgroup(  856): failed to open /acct/uid_10086/pid_5598/cgroup.procs: No such file or directory
,I/ActivityManager(  856): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5977 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/UEI.SmartControl( 5930):  ---- Has DB8: true
,W/ResourcesManager( 5977): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5977): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5977): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5930): QS start statue = true Error code = 0
D/UEI.SmartControl( 5930): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5930): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 5930): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5930): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5930): IrrcClient ++ 
D/irrcClient( 5930): getIrrcService ++ 
D/irrcClient( 5930): getIrrcService -- 
D/irrcClient( 5930): IrrcClient -- 
W/irrc_jni( 5930): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 5930): Services init done
D/UEI.SmartControl( 5930): QS Service init finished
D/UEI.SmartControl( 5930): QS Service version name: 0.1.73
D/UEI.SmartControl( 5930): QS Service version code: 1073
I/UEI.SmartControl( 5930): Device manager: loading config....
D/UEI.SmartControl( 5930): Service requested: Control
D/UEI.SmartControl( 5930): Config is loaded...
,D/UEI.SmartControl( 5930): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 5930):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5930): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5930): Internal service binding...
D/UEI.SmartControl( 5930): -----IControl: 11
D/UEI.SmartControl( 5930): Caller: com.lge.qremote
D/UEI.SmartControl( 5930): ------------ IControl registerCallback...
I/UEI.SmartControl( 5930): Registering callback...
D/UEI.SmartControl( 5930): -----IControl: 19
D/UEI.SmartControl( 5930): Caller: com.lge.qremote
I/UEI.SmartControl( 5930): Registering Services Ready callback...
I/UEI.SmartControl( 5930): Notify client services are ready...
D/UEI.SmartControl( 5930): -----IControl: 8
D/UEI.SmartControl( 5930): Caller: com.lge.qremote
,I/ActivityManager(  856): Killing 5690:com.lge.sync/1000 (adj 15): empty #11
I/ActivityManager(  856): Killing 5669:com.android.settings/1000 (adj 15): empty #12
,W/libprocessgroup(  856): failed to open /acct/uid_1000/pid_5690/cgroup.procs: No such file or directory
,W/libprocessgroup(  856): failed to open /acct/uid_1000/pid_5669/cgroup.procs: No such file or directory
I/AppConfig( 5977): Total System Memory = 906309632
I/GalleryUtils( 5977): Application Heap = 96 MB
I/AppConfig( 5977): App Tier : NOT_DEF
,D/SystemHelper( 5977): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  856): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6000 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  856): Killing 5649:com.lge.clock/u0a10 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_10010/pid_5649/cgroup.procs: No such file or directory
,W/ResourcesManager( 6000): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6000): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6000): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6000): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6000): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/AlertService( 3905): Beginning updateAlertNotification
,D/AlertService( 3905): No fired or scheduled alerts
,I/NotificationManager( 3905): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 3905): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 3905): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 3905): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 3905): com.android.calendar: cancel(4) by com.android.calendar
I/SystemConfig( 6000): BUILD Country: EU
I/SystemConfig( 6000): BUILD Operator: OPEN
I/NotificationManager( 3905): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 3905): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 3905): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3905): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 3905): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 3905): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 3905): com.android.calendar: cancel(11) by com.android.calendar
,I/NotificationManager( 3905): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 3905): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 3905): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3905): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3905): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3905): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 3905): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 3905): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 3905): com.android.calendar: cancel(20) by com.android.calendar
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/AlertService( 3905): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 3905): No events found starting within 1 week.
I/ActivityManager(  856): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6022 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  856): Killing 5715:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  856): failed to open /acct/uid_10081/pid_5715/cgroup.procs: No such file or directory
,I/SystemConfig( 6000): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6000): existFile = false
I/SystemConfig( 6000): canReadFile = false
I/SystemConfig( 6000): systemFeature RCS result false
D/SystemConfig( 6000): refreshRcsSupport() :false
I/LockScreenSettings( 6022): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6022): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 6022): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6022): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6022): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6022): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  856): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6039 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  856): Killing 5744:com.lge.bnr/1000 (adj 15): empty #11
I/art     (  308): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 25.954ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 314us total 20.866ms
,W/libprocessgroup(  856): failed to open /acct/uid_1000/pid_5744/cgroup.procs: No such file or directory
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 20.746ms
,I/[LGHome]EVENT( 1966): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1966): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[SystemUI]QPairHandler( 1390): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[LGHome]LGPlusHomeDBManager( 1966): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[LGHome]Launcher( 1966): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/InputReader(  856): Reconfiguring input devices.  changes=0x00000010
,I/QCNEJ   ( 1929): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QSlideListController( 1390): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1390): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1390): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
D/administrator(  856): Handling package changes for user 0
,I/art     (  856): Explicit concurrent mark sweep GC freed 21125(1060KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 8.039ms total 209.785ms
,I/ActivityManager(  856): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=6066 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  856): RTC_WAKEUP set : Alarm{1db4304d type 0 when 1452527824134 com.android.vending} when 1452527824134
W/ResourcesManager( 6039): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/NotificationService(  856): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  856): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  856): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  856): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  856): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  856): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2ead6ad6
,W/ResourcesManager(  856): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/LCardEmulationManager( 1859): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1859): getDefaultRoute
,W/ResourceType(  856): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
D/Finsky  ( 6066): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/[LGHome]EVENT( 1966): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1761): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  856): applying state to connected service
,I/UpdateIcingCorporaServi( 2054): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/art     ( 1761): Explicit concurrent mark sweep GC freed 30212(1885KB) AllocSpace objects, 17(272KB) LOS objects, 40% free, 13MB/22MB, paused 1.659ms total 121.655ms
,D/Finsky  ( 6066): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/UpdateIcingCorporaServi( 2054): UpdateCorporaTask done [took 68 ms] updated apps [took 68 ms] 
,W/Settings( 6066): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6066): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 6066): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3206): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3206): created cursor android.database.sqlite.SQLiteCursor@17b143f0 on behalf of 6066
D/InitAlarmsService( 3905): Clearing and rescheduling alarms.
,D/CalendarProvider2( 5775): Scheduling check of next Alarm
D/CalendarProvider2( 5775): SCHEDULE_ALARM_REMOVE
D/Ads     ( 6066): Skipping gmscore version check
,D/Finsky  ( 6066): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6066): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 6066): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  856): Killing 3905:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  856): failed to open /acct/uid_10013/pid_3905/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 5106): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5106): Null package name or gms related package.  Ignoreing.
E/MDM     ( 1761): [103] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 6066): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/Icing   ( 5106): updateResources: need to parse f{com.google.android.gms}
D/LocationInitializer( 5106): Restart initialization of location
,D/AuthorizationBluetoothService( 1761): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1761): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1761): No location to return for getLastLocation()
,W/FusedLocationProvider( 1761): location=null
I/AudioManager( 5629): getMode name:com.lge.qremote
,I/AudioManager( 5629): getMode name:com.lge.qremote
I/AudioManager( 5629): getMode name:com.lge.qremote
V/SetupWizard( 5904): Connected to Gservices successfully
,D/GCM     ( 1761): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/GCM     ( 1761): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/AudioManager( 5629): getMode name:com.lge.qremote
I/AppUp4:CustModeStarterReceiver( 5958): onReceive
I/AppUp4:CustModeStarterReceiver( 5958): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 5958): Context : android.app.ReceiverRestrictedContext@32466519
D/AppUp4:CustFacade( 5958): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5958): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5958): begin check event
I/AppUp4:CustModeStarterReceiver( 5958): Event For Nothing, skip.
I/NotificationManager( 5797): com.google.android.talk: cancel(8) by com.google.android.talk
D/Finsky  ( 6066): [740] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6066): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/LockScreenSettings( 6022): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 6022): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6022): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6022): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6022): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/UpdateIcingCorporaServi( 2054): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  856): Killing 6066:com.android.vending/u0a36 (adj 15): empty #11
I/UpdateIcingCorporaServi( 2054): UpdateCorporaTask done [took 36 ms] updated apps [took 36 ms] 
,W/libprocessgroup(  856): failed to open /acct/uid_10036/pid_6066/cgroup.procs: No such file or directory
I/ActivityManager(  856): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6146 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  856): Killing 5842:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_10053/pid_5842/cgroup.procs: No such file or directory
,D/Finsky  ( 6146): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6146): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6146): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6146): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 6146): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3206): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3206): created cursor android.database.sqlite.SQLiteCursor@14cd3d69 on behalf of 6146
,I/art     ( 4063): Explicit concurrent mark sweep GC freed 3537(141KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 567us total 39.328ms
,D/Finsky  ( 6146): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6146): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 6146): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Ads     ( 6146): Skipping gmscore version check
D/PackageBroadcastService( 5106): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/CalendarProvider2( 5775): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5775): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/Finsky  ( 6146): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  856): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6194 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/PackageBroadcastService( 5106): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  856): Killing 5775:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/Icing   ( 5106): updateResources: need to parse f{com.google.android.gms}
,W/libprocessgroup(  856): failed to open /acct/uid_10014/pid_5775/cgroup.procs: No such file or directory
I/ActivityManager(  856): Killing 5904:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  856): failed to open /acct/uid_10038/pid_5904/cgroup.procs: No such file or directory
,I/art     ( 5106): Explicit concurrent mark sweep GC freed 39091(2MB) AllocSpace objects, 29(464KB) LOS objects, 40% free, 13MB/22MB, paused 1.520ms total 123.244ms
,W/ActivityManager(  856): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6194): getAccountsCursor
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 5106): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,W/GAV2    ( 6194): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/art     (  856): Explicit concurrent mark sweep GC freed 33835(1584KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.205ms total 161.705ms
,W/ActivityManager(  856): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  856): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  856): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/AudioManager( 5629): getMode name:com.lge.qremote
,I/Gmail   ( 6194): Observing account changes for notifications
I/AudioManager( 5629): getMode name:com.lge.qremote
I/AudioManager( 5629): getMode name:com.lge.qremote
,I/AudioManager( 5629): getMode name:com.lge.qremote
E/Gmail   ( 6194): Error finding the version of the Email provider.....
E/Gmail   ( 6194): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6194): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6194): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6194): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6194): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6194): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6194): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6194): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6194): We do not support migrating this version of the Email provider.
I/Gmail   ( 6194): getAccountsCursor
I/ActivityManager(  856): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6235 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  856): Killing 5958:com.lge.appbox.client/u0a11 (adj 15): empty #11
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 5106): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,W/libprocessgroup(  856): failed to open /acct/uid_10011/pid_5958/cgroup.procs: No such file or directory
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 6235): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6235): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6235): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6235): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@3e1c7c60, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@32466519, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@251cd9de, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@375e97bf, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@23cfe8c, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@35cf39d5, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@1c98b5ea, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@116ef0db, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@1e017778, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@17d69e51, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@e4446b6, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@761bfb7, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@2b929324, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@2815ce8d, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@4461842, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@3248a053, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@1cf7bd90, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@3e9dc689, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@12a1768e, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@20b2eeaf, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@3b4322bc, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@9934245, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@38426d9a, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@10c9c6cb, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@2c7daea8, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3aaabdc1, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@4c9c966, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@302c04a7, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@2c530d54, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@106474fd, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@f1915f2, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@3d8a4443, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@237daac0, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@370863f9, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@89e9f3e, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@2802e19f, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@9f2b2ec, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@3d6246b5, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3961714a, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@83df8bb, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@3fce11d8, lg_preferences_recen,t_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@193d9931
D/GeneralPreferenceUtils( 6235): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
,D/Config  ( 6235): [init]
I/Config  ( 6235): LGCalendar ver.4.40.17
I/Config  ( 6235): start check model
I/Config  ( 6235): start check native_ca
I/Config  ( 6235): Config Operator=OPEN, Country=EU
D/Config  ( 6235): [setDefaultValuesToPref]
,D/Config  ( 6235): [parseProfiles]
D/ProfilesParser( 6235): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6235): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6235): [updateProfiletoCountryInfo]
D/GeneralPreference( 6235): [checkAndMigrateOldPreference]
D/AlertReceiver( 6235): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 6235): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6235): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/AlertUtils( 6235): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6235): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6235): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6235): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6235): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6235): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6235): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6235): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 6235): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6235): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6235): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6235): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 6235): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/Gmail   ( 6194): notifyAccountChanged
,I/AlertUtils( 6235): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/Gmail   ( 6194): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/AlertUtils( 6235): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6235): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6235): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,I/Gmail   ( 6194): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/AlertUtils( 6235): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 6235): End InitializeAlertRingtoneService.onHandleIntent
I/Gmail   ( 6194): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6194): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6194): getAccountsCursor
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6194): getAccountsCursor
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/HolidayIntentService( 6235): onHandleIntent
,D/HolidayDataLoader( 6235): readJsonAsset : holiday.json
D/AlertService( 6235): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 6235): [updateWidgets] 
D/MonthWidgetProvider( 6235): [onReceive]
D/CalendarWidgetProvider( 6235): [onReceive]
D/CalendarWidgetProvider( 6235): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
,D/CalendarTypeController( 6235): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 6235): [onReceive]
D/CalendarWidgetProvider( 6235): [onReceive]
D/CalendarWidgetProvider( 6235): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6235): [onCreate] mContext.getPackageName() = com.android.calendar
E/HolidayIntentService( 6235): onHandleIntent:holiday data empty
,I/Icing   ( 5106): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5106): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
D/PowerService( 1883): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1390): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1390): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1390): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1390): On Skip Timer : true
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/LEDHandler( 1883): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1883): Battery Level Remaining: 100%
D/LEDHandler( 1883): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
,D/HeadsetStateMachine( 2100): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1390): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1390): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1390): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/QCNEJ   ( 1929): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1929): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  856): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  856): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  856): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1390): onReceive = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1390): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1390): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1390): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,W/Settings(  856): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  856): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1929): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1929): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1883): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1883): Battery Level Remaining: 100%
D/LEDHandler( 1883): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2100): Disconnected process message: 10, size: 0
D/WifiController(  856): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1390): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1929): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1929): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:57:07.963 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/UEI.SmartControl( 5930): Internal timer expired: 1
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  856): ELAPSED_WAKEUP set : Alarm{61a7e7 type 2 when 84677 com.android.providers.calendar} when 84677
,I/ActivityManager(  856): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6285 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6285): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6285): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@3f3ae692
,D/CalendarProvider2( 6285): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6285): Created com.android.providers.calendar.CalendarAlarmManager@375e97bf(com.android.providers.calendar.CalendarProvider2@3f3ae692)
D/CalendarProviderBroadcastReceiver( 6285): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6285): [IntentService] WakeLock acquire, start IntentSerivce
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/CalendarProvider2( 6285): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 6285): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6285): [getOrCreateCalendarAlarmManager]
I/ActivityManager(  856): Killing 5977:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  856): failed to open /acct/uid_10023/pid_5977/cgroup.procs: No such file or directory
,D/CalendarProvider2( 6285): [IntentService] Release Lock
D/CalendarProvider2( 6285): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  856): Killing 6000:com.android.contacts/u0a18 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_10018/pid_6000/cgroup.procs: No such file or directory
,I/ActivityManager(  856): Killing 5797:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  856): failed to open /acct/uid_10061/pid_5797/cgroup.procs: No such file or directory
,I/GAV2    ( 6194): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 5106): Google Analytics 8.4.89 is starting up.
V/AlarmManager(  856): RTC_WAKEUP set : Alarm{36de37fb type 0 when 1452527831417 com.android.vending} when 1452527831417
,D/Finsky  ( 6146): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  856): android: cancelAsUser(2) by android
,D/libc-netbsd( 6146): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6146): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6146): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6146): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  280): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 6146): propertyValue:false
D/libc-netbsd( 6146): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6146): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6146): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6146): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/AlertService( 6235): Beginning updateAlertNotification
,D/AlertService( 6235): No fired or scheduled alerts
I/NotificationManager( 6235): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6235): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6235): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6235): com.android.calendar: cancel(3) by com.android.calendar
,I/NotificationManager( 6235): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6235): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6235): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6235): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6235): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6235): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6235): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6235): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6235): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6235): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6235): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6235): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6235): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6235): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6235): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6235): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6235): com.android.calendar: cancel(20) by com.android.calendar
,D/AlertService( 6235): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 6235): No events found starting within 1 week.
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  856): android: cancelAsUser(2) by android
,I/qtaguid ( 6146): Failed write_ctrl(u 41) res=-1 errno=22
,I/qtaguid ( 6146): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6146): untagSocket(41) failed with errno -22
D/Finsky  ( 6146): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/ActivityManager(  856): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6327 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  856): android: cancelAsUser(2) by android
,W/ResourcesManager( 6327): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6327): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6327): VM with version 2.1.0 has multidex support
I/MultiDex( 6327): install
I/MultiDex( 6327): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6327): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 6146): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6146): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6146): untagSocket(41) failed with errno -22
W/ActivityThread( 6327): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6327): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@14cd3d69: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6327): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6327): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6327): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1761): callingUid 10006, callindPid: 1761
,D/AuthorizationBluetoothService( 1761): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 5106): Restart initialization of location
V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1761): com.google.android.gms: cancel(0) by com.google.android.gms
E/MDM     ( 1761): [148] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/ChimeraCfgMgr( 6327): Reading stored module config
,W/GCoreFlp( 1761): No location to return for getLastLocation()
W/FusedLocationProvider( 1761): location=null
D/ChimeraCfgMgr( 6327): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/CAR.SERVICE( 6327): Connecting to CarCallService...
,I/art     ( 6327): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6327): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 6327): Install completed successfully. count=14 extracted=0
I/art     ( 6146): CheckpointMarkThreadRoots callback created = 0xb0566740
,D/CAR.SERVICE( 6327): com.google.android.projection.gearhead isn't installed.
D/CAR.TEL.Service( 6327): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6327): Creating a new PhoneAdapter instance
W/ActivityManager(  856): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6327): setListener: com.google.android.gms.car.dn@27da174c
W/ActivityManager(  856): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6327): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6327): Starting CarCallService with initial phone null
I/art     ( 6146): CheckpointMarkThreadRoots callback created = 0xb0566710
I/NotificationManager( 6327): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 6327): Package validated; name: com.android.vending
,I/NotificationManager( 6146): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 6146): [1] GearheadStateMonitor.access$100: mIsProjecting:false
V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  856): android: cancelAsUser(2) by android
,I/qtaguid ( 6146): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6146): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6146): untagSocket(41) failed with errno -22
,W/ResourcesManager( 6146): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6146): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6146): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 6146): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  856): RTC_WAKEUP set : Alarm{9e8ea3e type 0 when 1452527833561 com.android.vending} when 1452527833561
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/DeviceConnectionService( 1761): client connected with version: 8296000
D/Finsky  ( 6146): [754] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,I/CheckinService( 5106): Done disabling old GoogleServicesFramework version
,I/art     (  856): Explicit concurrent mark sweep GC freed 19919(963KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.099ms total 197.573ms
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6146): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 6146): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/NotificationManager(  856): android: cancelAsUser(2) by android
,D/libc-netbsd( 6146): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6146): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6146): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6146): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  280): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  280): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out( 6146): propertyValue:false
I/QCNEJ   ( 1929): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1929): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:57:13.996 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  856): Killing 6022:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  856): failed to open /acct/uid_10069/pid_6022/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  856): Killing 6039:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  856): failed to open /acct/uid_10086/pid_6039/cgroup.procs: No such file or directory
,D/CAR.SERVICE( 6327): mConnectedToCar = false, abort
,E/ActivityThread( 6327): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3827c5b4 that was originally bound here
E/ActivityThread( 6327): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3827c5b4 that was originally bound here
E/ActivityThread( 6327): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6327): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6327): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6327): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6327): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6327): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6327): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6327): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6327): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6327): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6327): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6327): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6327): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6327): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6327): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6327): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6327): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6327): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6327): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6327): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6327): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6327): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6327): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6327): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@26d19b7f that was originally bound here
E/ActivityThread( 6327): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@26d19b7f that was originally bound here
E/ActivityThread( 6327): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6327): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6327): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6327): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6327): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6327): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6327): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6327): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6327): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6327): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6327): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6327): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6327): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6327): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6327): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6327): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6327): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6327): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6327): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6327): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6327): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6327): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  856): Unbind failed: could not find connection for android.os.BinderProxy@38743497
D/sensors_hal_Time(  856): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  856): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  856): tsOffsetIs: Apps: 92783404866; DSPS: 3131861; Offset : -2795198554
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,W/SQLiteConnectionPool( 5106): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/QCNEJ   ( 1929): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1929): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:57:23.046 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/QCNEJ   ( 1929): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1929): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:57:26.063 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/rmt_storage(  278): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  278): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  278): wakelock acquired: 1, error no: 42
,I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  278): 
,I/rmt_storage(  278): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/QCNEJ   ( 1929): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1929): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:57:29.08 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/QCNEJ   ( 1929): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1929): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:57:32.096 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/AlarmManager(  856): RTC_WAKEUP set : Alarm{18b67e6d type 0 when 1452527847922 com.android.vending} when 1452527847922
V/AlarmManager(  856): RTC_WAKEUP set : Alarm{15873aa2 type 0 when 1452527851632 com.google.android.gms} when 1452527851632
,I/CheckinService( 5106): Checkin interval check for package: unspecified last checkin: 1452527821677 min interval config: 0 actual interval: 31379
,W/ContextImpl( 3694): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/CheckinService( 5106): Checking schedule, now: 1452527853088 next: 1452527851632
I/CheckinService( 5106): active receiver: enabled
,I/CheckinService( 5106): Preparing to send checkin request
I/EventLogService( 5106): Accumulating logs since 1452527813913
,I/CheckinRequestBuilder( 5106): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5106): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WVCdm   (  284): Instantiating CDM.
D/Finsky  ( 6146): [745] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6146): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/WVCdm   (  284): CdmEngine::OpenSession
I/WVCdm   (  284): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  284): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/WVCdm   (  284): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  284): L1 library not specified. Falling Back to L3
I/WVCdm   (  284): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  284): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  284): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  284): CdmEngine::GenerateKeyRequest
D/WVCdm   (  284): PrepareKeyRequest: nonce=3922663565
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/Adreno-EGL( 5517): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5517): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5517): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5517): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5517): Remote Branch: 
I/Adreno-EGL( 5517): Local Patches: 
I/Adreno-EGL( 5517): Reconstruct Branch: 
,I/WVCdm   (  284): CdmEngine::OpenSession
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1929): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1929): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:57:35.107 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/MusicWidget( 2681): mDelayedStopHandler : unbind
,I/MusicBrowser( 2730): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2730): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2730): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2730): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2730): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2730): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2730): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2730): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  856):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@38426d9acom.lge.music.MediaPlaybackService$6@10c9c6cb
,D/MusicBrowser( 2730): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2730): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2730): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2730): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2730): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@1e017778
,I/MusicBrowser( 2730): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2730): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2730): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2730): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2730): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2730): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2730): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2730): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2730): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2730): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2730): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2730): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2730): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2730): reset
,V/MediaPlayer[Native]( 2730): setListener
V/MediaPlayer[Native]( 2730): disconnect
V/MediaPlayer[Native]( 2730): destructor
,V/AudioFlinger(  284): releasing 19 from 2730 for -1
V/AudioFlinger(  284):  decremented refcount to 0
V/AudioFlinger(  284): purging stale effects
V/MediaPlayer[Native]( 2730): disconnect
D/MusicBrowser( 2730): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2730): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2730): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2730): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2730): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2730): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2730): [SmartShareManagerClient] unregisterListener: 746434216
W/SmartShareClient( 2730): [SmartShareManagerClient] unregisterListener invalid listener: 746434216
I/SmartShareClient( 2730): [SmartShareManagerClient] terminate service: 2730/MediaPlaybackService/622647774
E/HomeCloudIF( 2730): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2730): [SmartShareManagerClient] unbindService context:android.app.Application@3aaabdc1
V/CloudHub( 2730): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2730): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2730): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2730): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2730): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/CloudHub( 2730): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29996
,I/WVCdm   (  284): CdmEngine::CloseSession
,I/WVCdm   (  284): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  284): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  284): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  284): CdmEngine::GenerateKeyRequest
D/WVCdm   (  284): PrepareKeyRequest: nonce=1085686579
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  856): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  856): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  856): tsOffsetIs: Apps: 112784167879; DSPS: 3787246; Offset : -2795198351
,I/WVCdm   (  284): CdmEngine::CloseSession
I/WVCdm   (  284): L3 Terminate.
,I/Adreno-EGL( 5517): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5517): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5517): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5517): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5517): Remote Branch: 
I/Adreno-EGL( 5517): Local Patches: 
I/Adreno-EGL( 5517): Reconstruct Branch: 
I/Adreno-EGL( 5517): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5517): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5517): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5517): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5517): Remote Branch: 
I/Adreno-EGL( 5517): Local Patches: 
I/Adreno-EGL( 5517): Reconstruct Branch: 
,I/CheckinRequestBuilder( 5106): Classify the device as Phone.
,D/libc-netbsd( 5106): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5106): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5106): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5106): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 5106): propertyValue:false
D/libc-netbsd( 5106): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5106): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/QCNEJ   ( 1929): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1929): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:57:38.116 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/libc-netbsd( 5106): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5106): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5106): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5106): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/CheckinTask( 5106): Sending checkin request (9789 bytes)
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/CheckinRequestBuilder( 5106): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5106): Failed to find provider info for com.google.android.wearable.settings
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 5106): Classify the device as Phone.
,I/CheckinTask( 5106): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5106): Checking schedule, now: 1452527859072 next: 1453055108067
I/CheckinService( 5106): active receiver: disabled
,D/CheckinService( 5106): Recording last checkin time for package unspecified as 1452527859102
I/ActivityManager(  856): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6446 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  856): Killing 6235:com.android.calendar/u0a13 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_10013/pid_6235/cgroup.procs: No such file or directory
,D/PhoneMonitor( 6446): Register our PhoneStateListener
,V/SetupWizard( 6446): Connected to Gservices successfully
,I/ActivityManager(  856): Killing 5930:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
D/PhoneMonitor( 6446): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6446): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6446): [parse] Load xml
V/TelephonyAutoProfiling( 6446): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6446): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
W/System.err( 5629): android.os.DeadObjectException
,W/System.err( 5629): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5629): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5629): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5629): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5629): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5629): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5629): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5629): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5629): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5629): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5629): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5629): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5629): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5629): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5629): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5629): android.os.DeadObjectException
D/PhoneMonitor( 6446): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/System.err( 5629): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5629): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5629): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5629): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5629): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5629): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5629): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5629): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5629): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5629): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5629): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5629): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5629): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5629): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5629): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  856): failed to open /acct/uid_10089/pid_5930/cgroup.procs: No such file or directory
W/ActivityManager(  856): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,D/GCM     ( 1761): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  856): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6477 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6477): Quickset Services start...
,I/UEI.SmartControl( 6477): Manufacture = LGE
D/UEI.SmartControl( 6477): File observer start...
E/UEI.SmartControl( 6477): IR Port is disabled: false
D/UEI.SmartControl( 6477): Starting file observer...
D/UEI.SmartControl( 6477): Extracting JNI libs...
D/UEI.SmartControl( 6477): --- this system supports 32-bit or 64-bit only
,D/UEI.SmartControl( 6477): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6477): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6477): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6477): --- Selecting new region: 2
,I/UEI.SmartControl( 6477): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6477): Platform has CIR...
D/UEI.SmartControl( 6477): NO CIR support, need to check package...
I/UEI.SmartControl( 6477): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6477): QS Service created
,E/UEI.SmartControl( 6477): QS start get config
,D/UEI.SmartControl( 6477): Loading JNI Libs...
,D/UEI.SmartControl( 6477):  configuring local db...
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 6477):  ---- Has DB8: true
,D/UEI.SmartControl( 6477): QS start statue = true Error code = 0
D/UEI.SmartControl( 6477): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6477): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6477): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6477): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6477): IrrcClient ++ 
D/irrcClient( 6477): getIrrcService ++ 
,D/irrcClient( 6477): getIrrcService -- 
D/irrcClient( 6477): IrrcClient -- 
W/irrc_jni( 6477): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6477): Services init done
I/UEI.SmartControl( 6477): Device manager: loading config....
D/UEI.SmartControl( 6477): QS Service init finished
D/UEI.SmartControl( 6477): QS Service version name: 0.1.73
,D/UEI.SmartControl( 6477): QS Service version code: 1073
D/UEI.SmartControl( 6477): Config is loaded...
D/UEI.SmartControl( 6477): Service requested: Control
D/UEI.SmartControl( 6477): -----IControl: 11
I/ActivityManager(  856): Killing 6194:com.google.android.gm/u0a53 (adj 15): empty #11
D/UEI.SmartControl( 6477): Caller: com.lge.qremote
D/UEI.SmartControl( 6477): ------------ IControl registerCallback...
I/UEI.SmartControl( 6477): Registering callback...
D/UEI.SmartControl( 6477): -----IControl: 19
,D/UEI.SmartControl( 6477): Caller: com.lge.qremote
I/UEI.SmartControl( 6477): Registering Services Ready callback...
D/UEI.SmartControl( 6477):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6477): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6477): -----IControl: 8
D/UEI.SmartControl( 6477): Caller: com.lge.qremote
W/libprocessgroup(  856): failed to open /acct/uid_10053/pid_6194/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6477): Internal service binding...
,I/AudioManager( 5629): getMode name:com.lge.qremote
I/AudioManager( 5629): getMode name:com.lge.qremote
,I/AudioManager( 5629): getMode name:com.lge.qremote
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1929): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1929): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:57:41.135 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QPairHandler( 1390): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[LGHome]EVENT( 1966): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1966): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/InputReader(  856): Reconfiguring input devices.  changes=0x00000010
,I/QCNEJ   ( 1929): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,D/administrator(  856): Handling package changes for user 0
,I/[LGHome]LGPlusHomeDBManager( 1966): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/[LGHome]Launcher( 1966): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  856): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6517 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/[SystemUI]QSlideListController( 1390): onReceive = android.intent.action.PACKAGE_CHANGED
,I/NotificationService(  856): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  856): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  856): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/[SystemUI]QSlideLoader( 1390): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
I/BackupManagerService(  856): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/[SystemUI]QSlideLoader( 1390): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1390): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1390): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
V/BackupManagerService(  856): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  856): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2003c52f
,W/ResourcesManager(  856): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType(  856): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,W/ResourcesManager( 6517): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/[LGHome]EVENT( 1966): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/GCoreNlp( 1761): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  856): applying state to connected service
,I/Babel_SMS( 6517): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6517): MmsConfig.loadMmsSettings
I/Babel_SMS( 6517): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6517): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6517): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6517): MmsConfig.loadFromResources
E/Babel_SMS( 6517): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6517): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6517): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6517): found sensor: LGE Magnetometer Sensor, handle=10
,D/SensorManager( 6517): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6517): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6517): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6517): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6517): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6517): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6517): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6517): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6517): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6517): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6517): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6517): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6517): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6517): found sensor: Motion Accel, handle=46
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
D/LCardEmulationManager( 1859): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1859): getDefaultRoute
,W/Settings( 6517): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6517): startup - clean
I/Babel   ( 6517): deleted: false for 0
,I/art     ( 6517): CheckpointMarkThreadRoots callback created = 0xaaf3e8f0
,I/art     ( 6517): CheckpointMarkThreadRoots callback created = 0xaaf3e8d0
,W/AudioCapabilities( 6517): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6517): Unsupported mime audio/adpcm
W/AudioCapabilities( 6517): Unsupported mime audio/g726
W/AudioCapabilities( 6517): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6517): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6517): Unsupported mime video/mjpg
,W/art     ( 6517): Suspending all threads took: 9.097ms
W/VideoCapabilities( 6517): Unsupported mime video/theora
,I/ActivityManager(  856): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6554 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/AudioCapabilities( 6517): Unsupported mime audio/evrc
W/AudioCapabilities( 6517): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6517): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6517): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6517): Unsupported mime audio/qcelp
W/AudioCapabilities( 6517): Unsupported mime audio/evrc
,W/VideoCapabilities( 6517): Unsupported mime video/mp4v-esdp
,I/AppUp4:AppBoxCP( 6554): onCreate
,W/AppUp4:DB( 6554):  [AppBoxDatabaseHelper] construct
I/VideoCapabilities( 6517): Unsupported profile 4 for video/mp4v-es
I/AppUp4:DB( 6554):  setFingerPrint start
I/AppUp4:DB( 6554):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,W/VideoCapabilities( 6517): Unrecognized profile 2130706433 for video/avc
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
W/VideoCapabilities( 6517): Unrecognized profile 2130706433 for video/avc
I/AppUp4:DB( 6554):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6554):  SDK version = 0
I/AppUp4:DB( 6554):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6554): AppBoxApplication onCreate()
W/VideoCapabilities( 6517): Unrecognized profile 2130706433 for video/avc
,I/AppUp4:CustModeStarterReceiver( 6554): onReceive
I/AppUp4:CustModeStarterReceiver( 6554): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6554): Context : android.app.ReceiverRestrictedContext@32466519
D/AppUp4:CustFacade( 6554): isCustomizationCompleted : false
,W/VideoCapabilities( 6517): Unrecognized profile 2130706433 for video/avc
D/AppUp4:CustFacade( 6554): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6554): begin check event
I/AppUp4:CustModeStarterReceiver( 6554): Event For Nothing, skip.
I/ActivityManager(  856): Killing 6285:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_10014/pid_6285/cgroup.procs: No such file or directory
,I/ActivityManager(  856): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6574 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 20.952ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.382ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 21.044ms
,W/ResourcesManager( 6574): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6574): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6574): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/vclib   ( 6517): onServiceConnected
W/Babel   ( 6517): Attempted to change video mute state without an active call.
I/NotificationManager( 6517): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6517): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6517): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6517): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppConfig( 6574): Total System Memory = 906309632
I/GalleryUtils( 6574): Application Heap = 96 MB
I/AppConfig( 6574): App Tier : NOT_DEF
D/SystemHelper( 6574): region [EU], country [EU], operator [OPEN], sub-operator []
,W/System  ( 6517): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6517): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  856): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6596 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  856): Killing 6327:com.google.android.gms:car/u0a6 (adj 15): empty #11
,W/libprocessgroup(  856): failed to open /acct/uid_10006/pid_6327/cgroup.procs: No such file or directory
,I/art     (  856): Explicit concurrent mark sweep GC freed 50672(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 2.046ms total 158.689ms
,I/NotificationManager( 6517): com.google.android.talk: cancel(10436) by com.google.android.talk
W/ResourcesManager( 6596): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6596): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6596): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 6596): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6596): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemConfig( 6596): BUILD Country: EU
I/SystemConfig( 6596): BUILD Operator: OPEN
,I/ActivityManager(  856): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6621 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  856): Killing 6146:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  856): failed to open /acct/uid_10036/pid_6146/cgroup.procs: No such file or directory
I/SystemConfig( 6596): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 6596): existFile = false
,I/SystemConfig( 6596): canReadFile = false
I/SystemConfig( 6596): systemFeature RCS result false
D/SystemConfig( 6596): refreshRcsSupport() :false
I/LockScreenSettings( 6621): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6621): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 6621): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 6621): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6621): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6621): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  856): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6638 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  856): Killing 2730:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  284): 2730 died, releasing its sessions
V/AudioFlinger(  284):  pid 1795 @ 0
,V/AudioFlinger(  284):  pid 3185 @ 1
,V/AudioFlinger(  284):  pid 3185 @ 2
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  856): failed to open /acct/uid_10028/pid_2730/cgroup.procs: No such file or directory
,W/ResourcesManager( 6638): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6477): Internal timer expired: 1
,I/UpdateIcingCorporaServi( 2054): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 2054): UpdateCorporaTask done [took 39 ms] updated apps [took 39 ms] 
,I/ActivityManager(  856): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6667 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  856): Killing 6446:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  856): failed to open /acct/uid_10038/pid_6446/cgroup.procs: No such file or directory
,D/Finsky  ( 6667): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6667): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6667): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6667): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6667): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3206): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3206): created cursor android.database.sqlite.SQLiteCursor@c4f53ee on behalf of 6667
D/Finsky  ( 6667): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6667): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 6667): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Ads     ( 6667): Skipping gmscore version check
D/PackageBroadcastService( 5106): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5106): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 6667): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 5106): updateResources: need to parse f{com.google.android.gms}
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/Icing   ( 5106): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5106): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  856): Killing 5517:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  856): failed to open /acct/uid_10006/pid_5517/cgroup.procs: No such file or directory
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  856): Killing 6477:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5629): android.os.DeadObjectException
W/System.err( 5629): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5629): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5629): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5629): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5629): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5629): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5629): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5629): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5629): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5629): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5629): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5629): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5629): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5629): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5629): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5629): android.os.DeadObjectException
W/System.err( 5629): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5629): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5629): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5629): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5629): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5629): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5629): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5629): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5629): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5629): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5629): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5629): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5629): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
,W/System.err( 5629): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5629): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,W/libprocessgroup(  856): failed to open /acct/uid_10089/pid_6477/cgroup.procs: No such file or directory
,W/ActivityManager(  856): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  856): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6737 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6737): Quickset Services start...
,I/UEI.SmartControl( 6737): Manufacture = LGE
D/UEI.SmartControl( 6737): File observer start...
E/UEI.SmartControl( 6737): IR Port is disabled: false
D/UEI.SmartControl( 6737): Starting file observer...
D/UEI.SmartControl( 6737): Extracting JNI libs...
D/UEI.SmartControl( 6737): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6737): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6737): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 6737): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6737): --- Selecting new region: 2
I/UEI.SmartControl( 6737): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6737): Platform has CIR...
,D/UEI.SmartControl( 6737): NO CIR support, need to check package...
I/UEI.SmartControl( 6737): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6737): QS Service created
E/UEI.SmartControl( 6737): QS start get config
,D/UEI.SmartControl( 6737): Loading JNI Libs...
,D/UEI.SmartControl( 6737):  configuring local db...
D/UEI.SmartControl( 6737):  ---- Has DB8: true
,D/UEI.SmartControl( 6737): QS start statue = true Error code = 0
D/UEI.SmartControl( 6737): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6737): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6737): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6737): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6737): IrrcClient ++ 
D/irrcClient( 6737): getIrrcService ++ 
D/irrcClient( 6737): getIrrcService -- 
D/irrcClient( 6737): IrrcClient -- 
W/irrc_jni( 6737): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6737): Services init done
,I/UEI.SmartControl( 6737): Device manager: loading config....
D/UEI.SmartControl( 6737): QS Service init finished
D/UEI.SmartControl( 6737): QS Service version name: 0.1.73
D/UEI.SmartControl( 6737): QS Service version code: 1073
D/UEI.SmartControl( 6737): Config is loaded...
D/UEI.SmartControl( 6737): Service requested: Control
I/ActivityManager(  856): Killing 5629:com.lge.qremote/u0a106 (adj 15): empty #11
,D/UEI.SmartControl( 6737):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6737): Notify AllClients services are ready: 0
W/libprocessgroup(  856): failed to open /acct/uid_10106/pid_5629/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 6737): Internal service binding...
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/KeyguardUpdateMonitor( 1390): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1390): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1390): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1390): On Skip Timer : true
,D/PowerService( 1883): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 2100): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1390): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1390): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1390): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
I/QCNEJ   ( 1929): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1929): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1883): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1883): Battery Level Remaining: 100%
D/LEDHandler( 1883): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1390): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  856): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  856): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  856): battery changed pluggedType: 2
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1929): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1929): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:57:53.196 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 6737): Internal timer expired: 1
,D/UEI.SmartControl( 6737): Service.onUnbind: IControl
D/UEI.SmartControl( 6737): Service.onDestroy
W/System.err( 6737): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@116ef0db
W/System.err( 6737): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 6737): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 6737): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 6737): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 6737): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 6737): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 6737): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 6737): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 6737): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6737): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6737): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6737): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6737): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6737): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6737): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6737): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@116ef0db
D/UEI.SmartControl( 6737): Shutdown IRRCPlayer... 
,W/irrc_jni( 6737): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6737): ~IrrcClient ++ 
D/irrcClient( 6737): ~IrrcClient -- 
W/irrc_jni( 6737): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6737): Blaster closed
D/UEI.SmartControl( 6737): Blaster closed
D/UEI.SmartControl( 6737): Shut down QS...
,D/UEI.SmartControl( 6737): Stopped file observer...
I/UEI.SmartControl( 6737): QS lib stop result = true
D/UEI.SmartControl( 6737): QS shutdown complete
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  856): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  856): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  856): tsOffsetIs: Apps: 132785197559; DSPS: 4442640; Offset : -2795205956
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1929): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1929): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:57:59.233 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/PowerManagerServiceEx(  856): acquireWakeLockInternal: lock=667991007, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=856
,D/WeatherService( 2715): 2 : TimeTick Intent has been received, Time(hour:min:sec) 16:58:0
D/WeatherService( 2715): 2 : TimeTick Intent And Screen On
D/WeatherService( 2715): 2 : SDK version : 21
W/ActivityManager(  856): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2715): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2715): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2715): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2715): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2715): 2 : This is isUpdating : false
D/WeatherService( 2715): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2715): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2715): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2715): 2 : Fixed theme : optimus
D/WeatherReflect( 2715): 2 : Map key string is -2
D/lim     ( 2715): 2 : time = 16:58
I/WeatherReflect( 2715): Model Name : LG-D722
D/WeatherTheme( 2715): 2 : Different view - status_min_formatted : 57 != 58
D/WeatherTheme( 2715): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
,D/WeatherReflect( 2715): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2715): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2715): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]TimeTickManager( 1390): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1390): called onTimeUpdated()
I/[SystemUI]Clock( 1390): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1390): called onTimeUpdated()
I/[SystemUI]DateView( 1390): called onTimeUpdated()
I/[SystemUI]DateView( 1390): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1390): handleTimeUpdate
D/Weather4x2_optimus( 2715): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2715): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2715): forecast size is 0
D/Theme   ( 2715): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2715): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2715): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2715): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2715): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2715): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2715): setTouchIntent, appWidgetId: 2
,D/Theme_WeatherAncestor_optimus( 2715): url is : null
D/Theme   ( 2715): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2715): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2715): 2 : update view, appWidgetId: 2
D/WeatherService( 2715): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 16:58:0
D/PowerManagerServiceEx(  856): releaseWakeLockInternal: lock=667991007 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1966): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1966): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/AlarmManager(  856): ELAPSED_WAKEUP set : Alarm{3a98202c type 2 when 137198 com.google.android.gms} when 137198
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/VacuumService( 1761): Vacuum at: now=1452527882389 tag=VacuumService
,I/PhenotypeConfigurator( 1761): Scheduling Phenotype for one-off execution 8036 seconds from now (1452527882842)
,D/GetConfigurationSnapshotOperation( 1761): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1761): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1761): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  856): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1761): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1761): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1761): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1761): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 1761): propertyValue:false
D/libc-netbsd( 1761): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1761): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1761): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1761): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/LocationManagerService(  856): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/LocationManagerService(  856): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  856): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  856): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/art     ( 1761): Explicit concurrent mark sweep GC freed 92252(5MB) AllocSpace objects, 14(247KB) LOS objects, 40% free, 15MB/25MB, paused 2.314ms total 117.276ms
,V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1761): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1761): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1761): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1761): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1761): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
,D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 1761): propertyValue:false
D/libc-netbsd( 1761): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1761): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1761): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1761): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1761): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1761): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  856): android: cancelAsUser(2) by android
,I/NotificationManager( 1761): com.google.android.gms: cancel(0) by com.google.android.gms
,D/LocationManagerService(  856): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/QCNEJ   ( 1929): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1929): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:58:05.261 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  856): ALS enabled for SRE
,D/PowerManagerServiceEx(  856): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (26062 ms ago)
D/qdlights(  856): set_light_backlight: 253
,D/qdlights(  856): set_light_backlight: 250
D/qdlights(  856): set_light_backlight: 246
,D/qdlights(  856): set_light_backlight: 243
,D/qdlights(  856): set_light_backlight: 240
,D/qdlights(  856): set_light_backlight: 236
,D/qdlights(  856): set_light_backlight: 233
,D/qdlights(  856): set_light_backlight: 230
,D/qdlights(  856): set_light_backlight: 226
,D/qdlights(  856): set_light_backlight: 223
,D/qdlights(  856): set_light_backlight: 220
,D/qdlights(  856): set_light_backlight: 216
,D/qdlights(  856): set_light_backlight: 213
,D/qdlights(  856): set_light_backlight: 210
,D/qdlights(  856): set_light_backlight: 206
,D/qdlights(  856): set_light_backlight: 203
,D/qdlights(  856): set_light_backlight: 200
,D/qdlights(  856): set_light_backlight: 196
,D/qdlights(  856): set_light_backlight: 193
,D/qdlights(  856): set_light_backlight: 190
,D/qdlights(  856): set_light_backlight: 186
,D/qdlights(  856): set_light_backlight: 183
,D/qdlights(  856): set_light_backlight: 180
,D/qdlights(  856): set_light_backlight: 177
,D/qdlights(  856): set_light_backlight: 173
,D/qdlights(  856): set_light_backlight: 170
,D/qdlights(  856): set_light_backlight: 167
,D/qdlights(  856): set_light_backlight: 163
,D/qdlights(  856): set_light_backlight: 160
,D/qdlights(  856): set_light_backlight: 157
,D/qdlights(  856): set_light_backlight: 153
,D/qdlights(  856): set_light_backlight: 150
,D/qdlights(  856): set_light_backlight: 147
,D/qdlights(  856): set_light_backlight: 143
,D/qdlights(  856): set_light_backlight: 140
,D/qdlights(  856): set_light_backlight: 137
,D/qdlights(  856): set_light_backlight: 133
,D/qdlights(  856): set_light_backlight: 130
,D/qdlights(  856): set_light_backlight: 127
,D/qdlights(  856): set_light_backlight: 123
,D/qdlights(  856): set_light_backlight: 120
,D/qdlights(  856): set_light_backlight: 117
,D/qdlights(  856): set_light_backlight: 113
,D/qdlights(  856): set_light_backlight: 110
,D/qdlights(  856): set_light_backlight: 107
,D/qdlights(  856): set_light_backlight: 103
,D/qdlights(  856): set_light_backlight: 100
,D/qdlights(  856): set_light_backlight: 97
,D/qdlights(  856): set_light_backlight: 93
,D/qdlights(  856): set_light_backlight: 90
,D/qdlights(  856): set_light_backlight: 87
,D/qdlights(  856): set_light_backlight: 83
,D/qdlights(  856): set_light_backlight: 80
,D/qdlights(  856): set_light_backlight: 77
,D/qdlights(  856): set_light_backlight: 73
,D/qdlights(  856): set_light_backlight: 70
,D/qdlights(  856): set_light_backlight: 67
,D/qdlights(  856): set_light_backlight: 63
,D/qdlights(  856): set_light_backlight: 60
,D/qdlights(  856): set_light_backlight: 57
,D/qdlights(  856): set_light_backlight: 53
,D/qdlights(  856): set_light_backlight: 50
,D/qdlights(  856): set_light_backlight: 47
,D/qdlights(  856): set_light_backlight: 43
,D/qdlights(  856): set_light_backlight: 40
,D/qdlights(  856): set_light_backlight: 37
,D/qdlights(  856): set_light_backlight: 33
,D/qdlights(  856): set_light_backlight: 30
,D/qdlights(  856): set_light_backlight: 27
,D/qdlights(  856): set_light_backlight: 23
,D/qdlights(  856): set_light_backlight: 20
,D/qdlights(  856): set_light_backlight: 17
,D/qdlights(  856): set_light_backlight: 13
,D/qdlights(  856): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1929): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1929): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-11 16:58:14.331 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  856): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  856): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  856): tsOffsetIs: Apps: 152786241249; DSPS: 5098034; Offset : -2795200045
,I/PowerManagerService(  856): ALS enabled for SRE
D/PowerManagerServiceEx(  856): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (33059 ms ago)
,I/PowerManagerService(  856): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  856): ALS enabled for SRE
D/PowerManagerServiceEx(  856): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (33078 ms ago)
W/ContextImpl(  856): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  856): Sleeping (uid 1000)...
D/LPWGController(  856): [updateScreenState] screen on = false
D/LPWGController(  856): disable proximity sensor
,D/LPWGController(  856): enable proximity sensor
I/SensorManager(  856): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@1ea56af4] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  856): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  856): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  856): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  856): activate: handle is 48, enable
,V/sensors_hal_Ctx(  856): activate sensors is 1400000000000
D/sensors_hal_Thresh(  856): enable: handle=48
I/sensors_hal_SAM(  856): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  856): waitForResponse: timeout=1000
V/sensors_hal_SAM(  856): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  856): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  856): enable: Received response: 0
D/PowerManagerServiceEx(  856): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (33151 ms ago)
I/Adreno-EGL(  856): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  856): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  856): Build Date: 03/02/15 Mon
I/Adreno-EGL(  856): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  856): Remote Branch: 
I/Adreno-EGL(  856): Local Patches: 
I/Adreno-EGL(  856): Reconstruct Branch: 
,D/PermissionCache(  247): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (153 us)
,I/Sensors (  427): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  856): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  856): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  856): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  856): processInd: handle 48, count=1
V/sensors_hal_Thresh(  856): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  856): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  856): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  856): poll: count: 256
I/sensors_hal_Ctx(  856): poll: released wakelock sensor_ind
D/sensors_hal_Util(  856): waitForResponse: timeout=0
D/LPWGController(  856): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  856): current mode = 1  value = 1 1
I/LPWGController(  856): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  856): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/qdlights(  856): set_light_backlight: 0
,I/SensorManager(  856): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  856): activate: handle is 46, disable
V/sensors_hal_Ctx(  856): activate sensors is 1000000000000
D/sensors_hal_LP2(  856): enable: handle=46
D/sensors_hal_LP2(  856): enable: Disabling sensor handle=46
,I/sensors_hal_SAM(  856): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  247): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  247): hwc_blank: Blanking display: 0
V/sensors_hal_SAM(  856): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  856): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
I/DisplayManagerService(  856): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  856): Display changed displayId=0
,D/DSDPConnection( 1795): Display #0 changed.
,D/qdhwcomposer(  247): hwc_blank: Done blanking display: 0
,I/qdhwcomposer(  247): handle_blank_event: dpy:0 panel power state: 0
D/SurfaceControl(  856): Excessive delay in setPowerMode(): 224ms
I/QCOM PowerHAL(  856): Got set_interactive hint
,D/KeyguardViewMediator( 1390): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1348): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1348): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1348): handleNotifyScreenOFF
D/KeyguardViewMediator( 1390): notifyScreenOffLocked
,D/KeyguardViewMediator( 1390): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1390): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1390): unregisterProximitySensor
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/StatusBarWindowView( 1390): onScreenTurnedOff why = 3
,D/WifiServerServiceExt(  856): sendKtScanInterval  mRtspPlay : false
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1390): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
V/AudioFlinger(  284): setParameters(): io 0, keyvalue screen_state=on, calling pid 856
D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=on
V/voice   (  284): voice_set_parameters: enter: screen_state=on
V/compress_voip(  284): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  284): voice_extn_compress_voip_set_parameters: exit
V/voice   (  284): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  284): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  284): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  284): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  284): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  284): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  284): adev_set_parameters: exit with code(0)
,D/KeyguardUpdateMonitor( 1390): handleTimeUpdate
,I/WifiServerServiceExt(  856): set CMD_KT_SCAN_INTERVAL
I/Sensors (  427): sns_pwr.c(301):releasing wakelock
,D/GpsLocationProvider(  856): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1390): onReceive = android.intent.action.SCREEN_ON
D/SplitWindow(  856): check instance of lgWin Window{5a7f663 u0 SearchPanel}
,I/QCNEJ   ( 1929): |CORE| sendScreenState: state:true
I/LEDService( 1883): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1883): stopPatternFlashing()
D/qdlights( 1883): set_light_notifications: 0,0,0,0,3
I/LEDService( 1883): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1883): set_light_notifications: 0,0,0,0,3
I/LEDService( 1883): updateLightsLocked : turn off led
D/qdlights( 1883): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1883): RESTART MSG
,D/InputDispatcher(  856): Window went away: Window{46f0b74 u0 SearchPanel}
I/[SystemUI]Clock( 1390): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1390): time changed, timezoneChanged : false
,I/Cliptray Service( 1883): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1883): lockStatus = 0
D/LNfcService( 1859): action : android.intent.action.SCREEN_ON
,D/NfcServiceNXP( 1859): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1859): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1859): isRequireNfcCRouting() return true
D/LNfcService( 1859): isHCERoutingtoHost() return : true
D/NfcService( 1859): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1859): mEnableLPD: true
D/NfcService( 1859): mEnableReader: false
D/NfcService( 1859): mEnableHostRouting: true
D/NfcService( 1859): newParams.techmask= mTechMask: default
D/NfcService( 1859): mEnableLPD: true
D/NfcService( 1859): mEnableReader: false
D/NfcService( 1859): mEnableHostRouting: true
D/NfcService( 1859): screenState= 3
D/NfcService( 1859): Discovery configuration equal, not updating.
D/Ulp_jni (  856): JNI:system_update. Event-0
,V/PhoneApp( 1795): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2715): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:58:20
,D/WeatherService( 2715): 2 : ACTION screen on
D/WeatherService( 2715): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2715): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2715): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 16:58:20
W/Settings(  856): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  856): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  856): ACTION_SCREEN_ON
D/AppCleanupService( 4193): android.intent.action.SCREEN_ON
,V/AudioFlinger(  284): setParameters(): io 0, keyvalue screen_state=off, calling pid 856
D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=off
V/voice   (  284): voice_set_parameters: enter: screen_state=off
V/compress_voip(  284): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  284): voice_extn_compress_voip_set_parameters: exit
V/voice   (  284): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  284): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  284): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  284): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  284): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  284): adev_set_parameters: exit with code(0)
D/WifiController(  856): CMD_SCREEN_OFF 
D/WifiController(  856): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  856): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1390): onReceive = android.intent.action.SCREEN_OFF
,I/QCNEJ   ( 1929): |CORE| sendScreenState: state:false
I/LEDService( 1883): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1883): stopPatternFlashing()
D/qdlights( 1883): set_light_notifications: 0,0,0,0,3
I/LEDService( 1883): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1883): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1883): clear
I/LEDService( 1883): updateLightsLocked : turn on led
E/LEDService( 1883): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1883): Can't handle this request of patternId:0
D/LEDHandler( 1883): RESTART MSG
I/Cliptray Service( 1883): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1859): action : android.intent.action.SCREEN_OFF
,D/NfcServiceNXP( 1859): mScreenState : 1, mInProvisionMode : false
I/[LGHome]EVENT( 1966): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1795): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2715): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:58:20
D/WeatherService( 2715): 2 : ACTION screen off
D/WeatherService( 2715): 2 : TimeTick Receiver Unregister
D/WeatherService( 2715): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 16:58:20
W/Settings(  856): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  856): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  856): ACTION_SCREEN_OFF
D/AppCleanupService( 4193): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4193): AppUsageStatsSaveTask
E/NxpNfcJni( 1859): getReconnectState = 0x0
,D/LCardEmulationManager( 1859): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1859): getDefaultRoute
D/LNfcService( 1859): isRequireNfcCRouting() return true
D/LNfcService( 1859): isHCERoutingtoHost() return : true
D/NfcService( 1859): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1859): mEnableLPD: true
D/NfcService( 1859): mEnableReader: false
D/NfcService( 1859): mEnableHostRouting: true
D/NfcService( 1859): newParams.techmask= mTechMask: 0
D/NfcService( 1859): mEnableLPD: true
D/NfcService( 1859): mEnableReader: false
D/NfcService( 1859): mEnableHostRouting: true
,D/NfcService( 1859): screenState= 1
E/NxpNfcJni( 1859): getReconnectState = 0x0
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,D/KeyguardViewMediator( 1390): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  856): ELAPSED_WAKEUP set : Alarm{9284260 type 2 when 159056 com.android.systemui} when 159056
,D/PhoneUtils( 1795): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1795): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1795): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1795): getCallState : 0
,D/PhoneUtils( 1795): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1795): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1795): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1390): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1390): doKeyguard: not showing because lockscreen is off
V/AlarmManager(  856): ELAPSED_WAKEUP set : Alarm{209db319 type 2 when 161101 android} when 161101
,I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  856): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  856): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  856): tsOffsetIs: Apps: 172787044262; DSPS: 5753420; Offset : -2795189995
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ClearcutLoggerApiImpl( 1761): disconnect managed GoogleApiClient
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,V/AlarmManager(  856): ELAPSED_WAKEUP set : Alarm{e0d0fde type 2 when 185443 com.google.android.gms} when 185443
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1390): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1390): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1390): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1390): On Skip Timer : true
D/PowerService( 1883): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2100): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1390): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/QCNEJ   ( 1929): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1929): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1883): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1883): Battery Level Remaining: 100%
D/LEDHandler( 1883): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1390): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1390): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
W/Settings(  856): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  856): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  856): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1390): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  856): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  856): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  856): tsOffsetIs: Apps: 192789824932; DSPS: 6408871; Offset : -2795186294
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1390): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1390): called onTimeUpdated()
I/[SystemUI]Clock( 1390): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1390): called onTimeUpdated()
I/[SystemUI]DateView( 1390): called onTimeUpdated()
I/[SystemUI]DateView( 1390): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1390): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  856): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  856): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  856): tsOffsetIs: Apps: 212790943362; DSPS: 7064268; Offset : -2795197093
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  856): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  856): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  856): tsOffsetIs: Apps: 232793787521; DSPS: 7719721; Offset : -2795191303
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1390): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1883): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1390): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1390): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1390): On Skip Timer : true
D/HeadsetStateMachine( 2100): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1929): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1929): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1883): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1883): Battery Level Remaining: 100%
D/LEDHandler( 1883): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1390): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1390): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1390): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
I/[SystemUI]BatterySaverHandler( 1390): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  856): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  856): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  856): battery changed pluggedType: 2
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1390): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1883): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1390): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1390): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1390): On Skip Timer : true
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/sensors_hal_Time(  856): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  856): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  856): tsOffsetIs: Apps: 252795832669; DSPS: 8375148; Offset : -2795192682
,D/KeyguardUpdateMonitor( 1390): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1390): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1390): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1390): On Skip Timer : true
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1883): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2100): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1929): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1929): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1883): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1883): Battery Level Remaining: 100%
D/LEDHandler( 1883): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1390): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1390): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1390): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1390): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  856): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  856): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  856): battery changed pluggedType: 2
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1390): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1390): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1390): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1390): On Skip Timer : true
D/PowerService( 1883): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2100): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1929): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1929): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1883): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1883): Battery Level Remaining: 100%
D/LEDHandler( 1883): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1390): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1390): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1390): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1390): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  856): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  856): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  856): battery changed pluggedType: 2
I/[SystemUI]TimeTickManager( 1390): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1390): called onTimeUpdated()
I/[SystemUI]Clock( 1390): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1390): called onTimeUpdated()
I/[SystemUI]DateView( 1390): called onTimeUpdated()
I/[SystemUI]DateView( 1390): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1390): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  856): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  856): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  856): tsOffsetIs: Apps: 272797101932; DSPS: 9030550; Offset : -2795203308
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  856): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  856): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  856): tsOffsetIs: Apps: 292799732081; DSPS: 9685996; Offset : -2795197307
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1390): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1390): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1390): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1390): On Skip Timer : true
,D/PowerService( 1883): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2100): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1390): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/QCNEJ   ( 1929): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1929): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1883): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1883): Battery Level Remaining: 100%
D/LEDHandler( 1883): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1390): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1390): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/[SystemUI]BatterySaverHandler( 1390): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  856): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  856): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  856): battery changed pluggedType: 2
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1390): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1883): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1390): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1390): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1390): On Skip Timer : true
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  856): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  856): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  856): tsOffsetIs: Apps: 312802504366; DSPS: 10341447; Offset : -2795204491
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1390): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1390): called onTimeUpdated()
I/[SystemUI]Clock( 1390): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1390): called onTimeUpdated()
I/[SystemUI]DateView( 1390): called onTimeUpdated()
I/[SystemUI]DateView( 1390): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1390): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  856): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  856): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  856): tsOffsetIs: Apps: 332804835972; DSPS: 10996883; Offset : -2795190241
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/LocationManagerService(  856): remove 2317a9ea
,D/LocationManagerService(  856): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  856): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  856): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  856): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  856): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  856): acquireWakeLockInternal: lock=667991007, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=856
,I/ActivityManager(  856): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6896 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/DigitalAppWidgetProvider( 6896): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 6896): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@32466519
I/ActivityManager(  856): Killing 6554:com.lge.appbox.client/u0a11 (adj 15): empty #11
D/PowerManagerServiceEx(  856): releaseWakeLockInternal: lock=667991007 [*alarm*], flags=0x0
W/libprocessgroup(  856): failed to open /acct/uid_10011/pid_6554/cgroup.procs: No such file or directory
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  856): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  856): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  856): tsOffsetIs: Apps: 352806700807; DSPS: 11652304; Offset : -2795186771
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  481): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1390): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1883): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1390): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1390): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1390): On Skip Timer : true
D/HeadsetStateMachine( 2100): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1390): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/QCNEJ   ( 1929): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1929): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1883): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1883): Battery Level Remaining: 100%
D/LEDHandler( 1883): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1390): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1390): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
I/[SystemUI]BatterySaverHandler( 1390): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  856): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  856): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  856): battery changed pluggedType: 2
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  856): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  856): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  856): tsOffsetIs: Apps: 372808962571; DSPS: 12307738; Offset : -2795183229
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1390): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1390): called onTimeUpdated()
I/[SystemUI]Clock( 1390): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1390): called onTimeUpdated()
I/[SystemUI]DateView( 1390): called onTimeUpdated()
I/[SystemUI]DateView( 1390): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1390): handleTimeUpdate
I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  856): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  856): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  856): tsOffsetIs: Apps: 392811792772; DSPS: 12963191; Offset : -2795191475
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  856): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  856): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  856): tsOffsetIs: Apps: 412813279692; DSPS: 13618600; Offset : -2795199891
,I/ThermalEngine(  298): Sensor:pa_therm0:28000 mC
,TIME-OUT KILL (timeout was 360000ms),D/AndroidRuntime( 6949): 
D/AndroidRuntime( 6949): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6949): CheckJNI is OFF
D/AndroidRuntime( 6949): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  856): Force stopping com.example.hello appid=10317 user=-1: uninstall pkg
I/ActivityManager(  856): Killing 3331:com.example.hello/u0a317 (adj 0): stop com.example.hello
I/WindowState(  856): WIN DEATH: Window{144c0687 u0 com.example.hello/com.example.hello.MainActivity}
D/InputDispatcher(  856): Focus left window: Window{144c0687 u0 com.example.hello/com.example.hello.MainActivity}
D/InputDispatcher(  856): Window went away: Window{144c0687 u0 com.example.hello/com.example.hello.MainActivity}
W/PackageSettings(  856): Skipping PackageSetting{c04e679 com.test.thalitest/10316} due to missing metadata
I/ActivityManager(  856):   Force finishing activity ActivityRecord{8dcca89 u0 com.example.hello/.MainActivity t220}
V/ActivityManager(  856): Display changed displayId=0
D/DSDPConnection( 1795): Display #0 changed.
W/ActivityManager(  856): Spurious death for ProcessRecord{1a1995bf 3331:com.example.hello/u0a317}, curProc for 3331: null
I/ActivityManager(  856): Force stopping com.example.hello appid=10317 user=0: pkg removed
I/ActivityManager(  856):   Force finishing activity ActivityRecord{8dcca89 u0 com.example.hello/.MainActivity t220 f}
W/ActivityManager(  856): Duplicate finish request for ActivityRecord{8dcca89 u0 com.example.hello/.MainActivity t220 f}
D/KeyguardModel( 1390): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/art     ( 2054): Explicit concurrent mark sweep GC freed 27415(1670KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 12MB/20MB, paused 12.354ms total 94.889ms
W/GeofencerStateMachine( 1761): Ignoring removeGeofence because network location is disabled.
I/QCNEJ   ( 1929): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/InputReader(  856): Reconfiguring input devices.  changes=0x00000010
W/System.err( 3694): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 3694): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3694): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3694): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3694): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3694): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3694): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3694): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3694): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3694): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3694): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3694): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  856): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6974 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/art     ( 5106): Explicit concurrent mark sweep GC freed 27985(1805KB) AllocSpace objects, 10(160KB) LOS objects, 24% free, 13MB/18MB, paused 815us total 141.197ms
I/[LGHome]EVENT( 1966): [Launcher.java:5203:onStart()]onStart
I/[SystemUI]QSlideListController( 1390): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 1966): [Launcher.java:776:onResume()]onResume
I/[LGHome]EVENT( 1966): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
D/KeyguardModel( 1390): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1390): createShortcutInfo...
I/[LGHome]Launcher.Model( 1966): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1390): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1390): createShortcutInfo...
I/[LGHome]LGActivityUtil( 1966): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
W/ResourceType( 1390): No package identifier when getting value for resource number 0x00000000
I/[LGHome]EVENT( 1966): [Launcher.java:929:onResume()]onResume end
W/PackageManager( 1390): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/Activity( 1966): Activity.onPostResume() called 
D/KeyguardModel( 1390): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1390): createShortcutInfo...
W/ResourceType( 1390): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1390): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1390): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1390): createShortcutInfo...
I/[LGHome]EVENT( 1966): [Launcher.java:986:onPause()]onPause
W/ResourceType( 1390): No package identifier when getting value for resource number 0x00000000
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1390): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
W/PackageManager( 1390): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1390): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1390): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1390): createShortcutInfo...
D/KeyguardModel( 1390): handleShortcutListChanged...
D/KeyguardModel( 1390): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1390): createShortcutInfo...
D/KeyguardModel( 1390): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1390): createShortcutInfo...
W/[LGHome]LGWallpaperInfo( 1966): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1966): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
W/ResourceType( 1390): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1390): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1390): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1390): createShortcutInfo...
W/ResourceType( 1390): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1390): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/SystemUI[Framework](  856): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/KeyguardModel( 1390): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1390): createShortcutInfo...
W/PhoneWindowManagerEx(  856): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  856): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  856): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  856): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@215eb15c,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  856): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  856): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/ResourceType( 1390): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1390): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
W/PhoneWindowManagerEx(  856): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  856): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  856): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  856): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@215eb15c,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  856): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  856): Focus entered window: Window{17bfa701 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1390): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1390): createShortcutInfo...
I/art     (  856): Explicit concurrent mark sweep GC freed 70178(3MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 2.507ms total 275.560ms
I/art     (  856): WaitForGcToComplete blocked for 97.665ms for cause Explicit
W/ResourcesManager( 6974): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6974): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6974): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1966): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1966): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1966): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/[LGHome]EVENT( 1966): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1390): handleShortcutListChanged...
I/[LGHome]EVENT( 1966): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1966): [setNavigationBarColor] color=0x 0
D/administrator(  856): Handling package changes for user 0
I/NotificationService(  856): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  856): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  856): Receieved: android.intent.action.PACKAGE_REMOVED
D/PhoneStatusBar( 1390): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/PhoneStatusBar( 1390): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
D/TaskPersister(  856): removeObsoleteFile: deleting file=220_task.xml
I/[SystemUI]NavigationThemeResource( 1390): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1390):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1390): , Keyguard show=false, IME shown=false, Panel expanded=false
I/LGEmail ( 6974): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 6974): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
W/InputMethodManagerService(  856): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  856): Got RemoteException sending setActive(false) notification to pid 3331 uid 10317
I/art     (  856): Explicit concurrent mark sweep GC freed 8446(475KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 6.642ms total 242.853ms
I/[LGHome]Launcher.Model( 1966): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1966): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1966): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1966): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/Timeline(  856): Timeline: Activity_windows_visible id: ActivityRecord{17b763c u0 com.lge.launcher2/.Launcher t219} time:415818
I/[LGHome]EVENT( 1966): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1966): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
D/AndroidRuntime( 6949): Shutting down VM
W/IInputConnectionWrapper( 1966): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1966): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1966): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1641): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1966): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1966): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1966): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1966): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1966): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1966): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/PackageChangeReceiver( 6974): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
W/Resources( 1966): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1966): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1966): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1966): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1966): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
I/ActivityManager(  856): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7010 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  856): Killing 6574:com.android.gallery3d/u0a23 (adj 15): empty #11
W/Resources( 1966): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1966): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1966): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1966): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1966): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/ResourcesManager(  856): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/Resources( 1966): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1966): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
W/ResourceType(  856): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
W/libprocessgroup(  856): failed to open /acct/uid_10023/pid_6574/cgroup.procs: No such file or directory
D/LCardEmulationManager( 1859): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1859): getDefaultRoute
I/AppUp4:AppBoxCP( 7010): onCreate
W/AppUp4:DB( 7010):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7010):  setFingerPrint start
I/AppUp4:DB( 7010):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7010):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7010):  SDK version = 0
I/AppUp4:DB( 7010):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7010): AppBoxApplication onCreate()
I/[LgeWidgetLib]LgeAppWidgetHostView( 1966): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
D/AppUp4:PreloadHelper( 7010): added Exclude : com.example.hello
I/ActivityManager(  856): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7030 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  856): Killing 6517:com.google.android.talk/u0a61 (adj 15): empty #11
E/SQLiteLog( 3694): (3850) statement aborts at 13: [INSERT INTO t001(f004,f005,f002,f003,f006) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDatabase( 3694): Error inserting f004=13 f005=7030 f002=1452528161216 f003=com.android.settings f006=1000
E/SQLiteDatabase( 3694): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 3694): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 3694): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:790)
E/SQLiteDatabase( 3694): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 3694): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 3694): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1581)
E/SQLiteDatabase( 3694): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1451)
E/SQLiteDatabase( 3694): 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:708)
E/SQLiteDatabase( 3694): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
E/SQLiteDatabase( 3694): 	at android.content.ContentResolver.insert(ContentResolver.java:1267)
E/SQLiteDatabase( 3694): 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2588)
E/SQLiteDatabase( 3694): 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
E/SQLiteDatabase( 3694): 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3413)
E/SQLiteDatabase( 3694): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3694): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 3694): 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3522)
E/[LgeWidgetLib]LgeAppWidgetHostView( 1966): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1966): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1966): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1966): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1966): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]EVENT( 1966): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 1966): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1966): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1966): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1966): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]

```
