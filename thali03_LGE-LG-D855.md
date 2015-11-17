#### Test 50388019c82294c_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/UEI.SmartControl( 3986): serial port data available: 4
D/MediaScannerReceiver( 3347): [MediaScanner] ACTION_BOOT_COMPLETED scan INTERNAL_VOLUME, EXTERNAL_VOLUME
D/MediaScannerService( 3347): [MediaScanner] start scanning volume internal: [/system/media, /oem/media, /cust/OPEN_EU/media]
V/SIM_STK ( 1033): Menu title from STK is T-Mobile
V/LGMediaProvider( 3347): insertInternal: content://media/none/media_scanner, initValues=volume=internal
D/MediaScannerService( 3347): [MediaScanner] scan() ACTION_MEDIA_SCANNER_STARTED uri : file:///system/media
I/MusicBrowser( 2197): [MediaPlaybackService.java:3069:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///system/media flg=0x10 }}
I/MusicBrowser( 2197): [MediaPlaybackService.java:3087:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2197): [MusicUtils.java:9327:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_STARTED
I/LIA_Service_LIAService( 1971): [LIA Service Info] -------------------------------
I/LIA_Service_LIAService( 1971):  - LIA Service Version Name : 0.8.20.2
I/LIA_Service_LIAService( 1971):  - LIA Service Release Date : 2014.10.27
I/LIA_Service_LIAService( 1971): --------------------------------------------------
D/LIA_Service_LIAService( 1971): onCreate()
--------- beginning of system
W/ContextImpl( 3986): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
V/MmsSystemEventReceiver( 3290): Intent received: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
D/MediaScannerEx( 3347): [MediaScanner] scanDirectories()[0] = /system/media
D/MediaScannerEx( 3347): [MediaScanner] scanDirectories()[1] = /oem/media
D/MediaScannerEx( 3347): [MediaScanner] scanDirectories()[2] = /cust/OPEN_EU/media
E/UEI.SmartControl( 3986): Services init done
D/UEI.SmartControl( 3986): QS Service init finished
D/UEI.SmartControl( 3986): QS Service version name: 2.1.91
D/UEI.SmartControl( 3986): QS Service version code: 201091
D/UEI.SmartControl( 3986): Service requested: Control
I/UEI.SmartControl( 3986): Device manager: loading config....
D/UEI.SmartControl( 3986): ----------- loading internal config...
D/MtpService( 3347): updating state; isCurrentUser=true, mMtpLocked=false
E/UEI.SmartControl( 3986): Loading SETTINGS...
D/UEI.SmartControl( 3986): Request IControl service: devices are loaded...
W/ResourcesManager( 3290): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/ActivityManager( 1033): Killing 3651:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
D/UEI.SmartControl( 3986): -- Open brand translation xml: brands_translations_ko
D/MtpService( 3347): addStorageLocked 65537 /storage/emulated/0
E/MtpStorageEx( 3347): setAccessCapability false
D/MmsConfig( 3290): getUserModeNotAllowedSms:sUserModeNotAllowedSms:false
I/UEI.SmartControl( 3986): Notify AllClients services are ready: 0
D/UEI.SmartControl( 3986): -----service ready thread exits
W/libprocessgroup( 1033): failed to open /acct/uid_10085/pid_3651/cgroup.procs: No such file or directory
D/MmsConfig( 3290): isNotAllowedSms: currentUser:0
D/MmsConfig( 3290): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3290): isUserMode:false
D/MtpService( 3347): updating state; isCurrentUser=true, mMtpLocked=false
E/ActivityThread( 3986): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@25533e1a that was originally bound here
E/ActivityThread( 3986): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@25533e1a that was originally bound here
E/ActivityThread( 3986): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
E/ActivityThread( 3986): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
E/ActivityThread( 3986): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
E/ActivityThread( 3986): 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
E/ActivityThread( 3986): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 3986): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 3986): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 3986): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 3986): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
E/ActivityThread( 3986): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/ActivityThread( 3986): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 3986): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3986): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 3986): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/ActivityThread( 3986): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3986): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3986): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/ActivityThread( 3986): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/UEI.SmartControl( 3986): Internal service binding...
D/MmsConfig( 3290): getUserModeNotAllowedSms:sUserModeNotAllowedSms:false
D/MmsConfig( 3290): isNotAllowedSms: currentUser:0
D/MmsConfig( 3290): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3290): isUserMode:false
I/art     ( 3347): Thread[1,tid=3347,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x751d7fa0,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
E/SQLiteLog( 3347): (283) recovered 158 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
D/MmsConfig( 3290): getUserModeNotAllowedSms:sUserModeNotAllowedSms:false
E/MediaProfilesEx-JNI( 3347): register_com_lge_media_MediaProfilesEx
E/MediaRecorderEx-JNI( 3347): register_com_lge_media_MediaRecorderEx
D/AudioSystemEx( 3347): register_com_lge_media_LGAudioSystem
E/SurfaceControlEx( 3347): register_com_lge_view_SurfaceControlEx
I/art     ( 3347): Thread[1,tid=3347,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x751d7fa0,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
D/LGMtpDatabaseJNI( 3347): register_android_mtp_LGMtpDatabase
D/LGMtpServerJNI( 3347): register_android_mtp_LGMtpServer
I/art     ( 3347): Thread[1,tid=3347,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x751d7fa0,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
E/MediaPlayerEx-jni( 3347): register_com_lge_view_MediaPlayerEx
E/LGMtpDatabaseJNI( 3347): android_mtp_LGMtpDatabase_setup
I/ActivityManager( 1033): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.BootReceiver: pid=4111 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
V/SIM_STK ( 1033): Menu title from STK is T-Mobile
D/MtpService( 3347): starting MTP server in PTP mode
D/LGMtpServer( 3347): LGMtpServer
D/LGMtpServerJNI( 3347): android_mtp_LGMtpServer_setup
D/MmsConfig( 3290): isNotAllowedSms: currentUser:0
D/MmsConfig( 3290): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3290): isUserMode:false
D/MmsConfig( 3290): isNotAllowedSms: currentUser:0
D/MmsConfig( 3290): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3290): isUserMode:false
D/SmsReceiverService( 3290): handleMessage isUserMode:false
D/LIA_Service_RemotePackageHandler( 1971): LIA task pacakge added(Using PackageManager) : com.lge.ia.task.mrgdblogger
D/LIA_Service_RemoteSessionManager( 1971): onAdded() : com.lge.ia.task.mrgdblogger
D/LIA_Service_RemoteProxy( 1971): connectToRemoteService() : sleep for 100(msec) and start to connect to com.lge.ia.task.mrgdblogger
D/MtpService( 3347): addStorageLocked 65537 /storage/emulated/0
E/MtpStorageEx( 3347): setAccessCapability false
D/MtpServerEx( 3347): ANR FIX - addStorage!
D/SmsReceiverService( 3290): [LGE] ACTION_BOOT_COMPLETED received
D/LGMtpServerJNI( 3347): android_mtp_LGMtpServer_run
V/LEDService( 1916): stopInternal(), pkg=com.android.mms, id=123
D/MessagingNotification( 3290): disalbleEmotionalLED id= 123
V/LEDService( 1916): stopInternal(), pkg=com.android.mms, id=946
D/MessagingNotification( 3290): disalbleEmotionalLED id= 946
D/MessagingNotification( 3290): unread_count:0, thread_count:0, thread_id:-2
D/MessagingNotification( 3290): toLockscreenWithUnreadMsgCnt - count = 0
I/ActivityManager( 1033): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4136 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
D/LIA_Service_RemoteProxy( 1971): connectToRemoteService() : start service - com.lge.ia.task.mrgdblogger
D/LIA_Service_RemoteProxy( 1971): connectToRemoteService() : startService() succeeded. - com.lge.ia.task.mrgdblogger
D/LIA_Service_RemoteProxy( 1971): connectToRemoteService() : bind service - com.lge.ia.task.mrgdblogger
D/LIA_MrGDBLogger_LIARemoteService( 2665): [dreamwood]onStartCommand() : LIARemoteService started! - (Id :2), Intent { act=com.lge.ia.task.mrgdblogger pkg=com.lge.ia.task.mrgdblogger (has extras) }
D/LIA_MrGDBLogger_LIARemoteService( 2665): [dreamwood]onBind()
D/LIA_MrGDBLogger_LIARemoteManager( 2665): [dreamwood]getBinder()
D/LIA_Service_RemoteProxy( 1971): connectToRemoteService() : bindService() succeeded - waiting for onServiceConnected() for com.lge.ia.task.mrgdblogger ...
D/LIA_Service_RemotePackageHandler( 1971): LIA task pacakge added(Using PackageManager) : com.lge.ia.task.informant
D/LIA_Service_RemoteSessionManager( 1971): onAdded() : com.lge.ia.task.informant
D/LIA_Service_RemoteProxy( 1971): connectToRemoteService() : sleep for 100(msec) and start to connect to com.lge.ia.task.informant
E/ActivityThread( 4111): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 4111): No ProfileInfo entries
I/LG Account v2.2( 4111): isEnabled: false
I/Feature ( 4111): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 4111): [Lifetracker]Country: EU
I/Feature ( 4111): [Lifetracker]Operator: OPEN
I/Feature ( 4111): [Lifetracker]Ranking support: false
I/Feature ( 4111): [Lifetracker]Comfort support: false
I/Feature ( 4111): [Lifetracker]Accessory: true
I/Feature ( 4111): [Lifetracker]Health device: true
I/Feature ( 4111): [Lifetracker]Extra Pedometer: false
I/Feature ( 4111): [Lifetracker]Blood glucose device: false
I/Feature ( 4111): [Lifetracker]Device Number: 3
I/BootReceiver( 4111): [onReceive] Action=android.intent.action.BOOT_COMPLETED
E/MediaScannerClient( 3347): SetLocale  locale=en_US ,mLocaleEncoding = 0
E/BootingWorkIntentService( 4111): [BootingWorkIntentService] doWakefulWork!!
E/MediaFileEx( 3347): Duplicate type = AVI
E/MediaFileEx( 3347): Duplicate type = ASF
W/ResourcesManager( 1826): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1826): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 1826): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
E/MediaScannerClient( 3347): SetLocale  locale=en_US ,mLocaleEncoding = 0
W/MediaScanner( 3347): Error opening directory '/oem/media/', skipping: No such file or directory.
E/MediaScannerClient( 3347): SetLocale  locale=en_US ,mLocaleEncoding = 0
W/MediaScanner( 3347): Error opening directory '/cust/OPEN_EU/media/', skipping: No such file or directory.
D/LGMediaProvider( 3347): [MediaScanner] delete() uri = content://media/internal/file
D/LGMediaProvider( 3347): [MediaScanner] delete() completed notifyChange, uri = content://media/internal
V/MediaScannerEx( 3347): [MediaScanner] isInternalStorage : true
D/MediaScanner( 3347):  prescan time: 286ms
D/MediaScanner( 3347):     scan time: 33ms
D/MediaScanner( 3347): postscan time: 5ms
D/LGNetworkSettings( 1826): onCreate()...
D/MediaScanner( 3347):    total time: 324ms
D/LGMediaProvider( 3347): [MediaScanner] delete() uri = content://media/none/media_scanner
I/GBoardStateUtil( 4111): [GBoardStateUtil] isEnableLGHealthofGBoard : true
E/BootingWorkIntentService( 4111): gboard state : true
I/BootingWorkIntentService( 4111): lifetracker is not yet started!! do nothing...
D/ConfigUtils( 1826): COUNTRY : EU
D/ConfigUtils( 1826): OPERATOR : OPEN
D/ConfigUtils( 1826): ALTERNATIVE CARRIER : OPEN
D/ConfigUtils( 1826): MODEL NAME : LG-D855
D/ConfigUtils( 1826): REGION : EU
D/ConfigUtils( 1826): TARGET PLATFORM : msm8974
D/ConfigUtils( 1826): DeviceName : g3
D/ConfigUtils( 1826): MODEL NAME : LG-D855
D/networksettings : ( 1826): NetworkSettingBootReceiver.java[82] : onReceive, action = android.intent.action.BOOT_COMPLETED
V/LGNetworkSettings( 1826): Action intent recieved:android.intent.action.ANY_DATA_STATE
I/SettingConfigUtils( 1826): isCroatiaTele_SIM 
E/InsertStillActivityIntentService( 4111): [InsertStillActivityIntentService] doWakefulWork!!
I/SettingConfigUtils( 1826): isCroatiaTele_SIM false
I/SettingConfigUtils( 1826): isPolandP4P_SIM 
I/LockScreenSettings( 4136): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/SettingConfigUtils( 1826): isPolandP4P_SIM false
I/SettingConfigUtils( 1826): isH3G_SIM 
I/Feature ( 4111): byteAvailable : 25145229312
I/SettingConfigUtils( 1826): isH3G_SIM false
I/SettingConfigUtils( 1826): isCroatiaTele_SIM 
I/SettingConfigUtils( 1826): isCroatiaTele_SIM false
V/LGNetworkSettings( 1826): Action intent recieved:android.intent.action.SIM_STATE_CHANGED
V/LGNetworkSettings( 1826): Action intent recieved:android.intent.action.SERVICE_STATE
D/NotificationMgr( 1826): updateNetworkSelection()...state = 3 new network 
I/networksettings : ( 1826): NetworkSettingBootReceiver.java[65] : disable LteGsmUmtsSettings
I/ActivityManager( 1033): Killing 3708:com.android.keychain/1000 (adj 15): empty #17
D/LIA_Service_RemoteProxy( 1971): connectToRemoteService() : start service - com.lge.ia.task.informant
D/MediaScannerService( 3347): [MediaScanner] scan() Send Intent ACTION_MEDIA_SCANNER_FINISHED uri : file:///system/media
W/BroadcastQueue( 1033): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to com.lge.privacylock/com.lge.cic.maf.core.setting.AuthSettingServiceBRrcv requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_3708/cgroup.procs: No such file or directory
D/MediaScannerService( 3347): [MediaScanner] done scanning volume internal
D/LIA_Service_RemoteProxy( 1971): connectToRemoteService() : startService() succeeded. - com.lge.ia.task.informant
D/LIA_Service_RemoteProxy( 1971): connectToRemoteService() : bind service - com.lge.ia.task.informant
D/LIA_Informant_LIARemoteService( 2665): onStartCommand() : LIARemoteService started! - (Id :4), Intent { act=com.lge.ia.task.informant pkg=com.lge.ia.task.informant (has extras) }
D/QuickCoverActivity( 3290): lockscreensettings ret = true
I/MusicBrowser( 2197): [MediaPlaybackService.java:3069:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 }}
I/MusicBrowser( 2197): [MediaPlaybackService.java:3087:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2197): [MusicUtils.java:9327:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager( 1033): Start proc com.android.settings for broadcast com.android.settings/.wifi.WifiAutoControlReceiver: pid=4162 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/LIA_Service_RemoteProxy( 1971): connectToRemoteService() : bindService() succeeded - waiting for onServiceConnected() for com.lge.ia.task.informant ...
D/LIA_Service_RemotePackageHandler( 1971): LIA task pacakge added(Using PackageManager) : com.lge.ia.task.s4urecommender
D/LIA_Service_RemoteSessionManager( 1971): onAdded() : com.lge.ia.task.s4urecommender
D/LIA_Informant_LIARemoteService( 2665): onBind()
D/LIA_Service_RemoteProxy( 1971): connectToRemoteService() : sleep for 100(msec) and start to connect to com.lge.ia.task.s4urecommender
D/LIA_Informant_LIARemoteManager( 2665): getBinder()
D/MediaScannerService( 3347): [MediaScanner] start scanning volume external: [/storage/emulated/0, /storage/external_SD]
I/ActivityManager( 1033): Killing 3419:com.lge.hiddenmenu/1000 (adj 15): empty #17
V/LGMediaProvider( 3347): insertInternal: content://media/none/media_scanner, initValues=volume=external
D/MediaScannerService( 3347): [MediaScanner] scan() ACTION_MEDIA_SCANNER_STARTED uri : file:///storage/emulated/0
D/UEI.SmartControl( 3986): Internal timer expired: 2
D/LIA_Service_RemoteProxy( 1971): connectToRemoteService() : start service - com.lge.ia.task.s4urecommender
D/SmartCoverUpdateMonitor( 1398): received broadcast lge.intent.action.UNREAD_MESSAGES
I/NfcP2pLinkManager( 1897): LLCP deactivated.
I/NfcP2pLinkManager( 1897): Duplicate onLlcpDectivated()
D/LIA_S4URecommender_LIARemoteService( 2665): onStartCommand() : LIARemoteService started! - (Id :2), Intent { act=com.lge.ia.task.s4urecommender pkg=com.lge.ia.task.s4urecommender (has extras) }
D/KeyguardModel( 1458): mReceiver, received action: lge.intent.action.UNREAD_MESSAGES, sendingUserId:0
D/LIA_Service_RemoteProxy( 1971): connectToRemoteService() : startService() succeeded. - com.lge.ia.task.s4urecommender
D/LIA_Service_RemoteProxy( 1971): connectToRemoteService() : bind service - com.lge.ia.task.s4urecommender
D/KeyguardModel( 1458): putNotificationIntoList Number: 0 Id: 1 UserId: 0
I/MessagingNotification( 3290): repeat count :0
W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_3419/cgroup.procs: No such file or directory
V/LGMediaProvider( 3347): insertInternal: content://media/, initValues=name=external
D/LIA_Service_RemoteProxy( 1971): connectToRemoteService() : bindService() succeeded - waiting for onServiceConnected() for com.lge.ia.task.s4urecommender ...
D/LIA_Service_LIAManager( 1971): LIAManager instance created.
I/MusicBrowser( 2197): [MediaPlaybackService.java:reloadQueue()] oooooo 
D/LIA_S4URecommender_LIARemoteService( 2665): onBind()
D/MusicBrowser( 2197): [MediaPlaybackService.java:reloadQueue()] oooooo id=-1
D/LIA_S4URecommender_LIARemoteManager( 2665): getBinder()
D/MusicBrowser( 2197): [MediaPlaybackService.java:reloadQueue()] oooooo mCardId=-1
D/MusicBrowser( 2197): [MediaPlaybackService.java:reloadQueue()] oooooo mPreferences.id=-1
D/LIA_Service_LIAService( 1971): onStartCommand() : LIAService started! - id :1, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
D/MusicBrowser( 2197): [MediaPlaybackService.java:reloadQueue()] oooooo q=
D/MusicBrowser( 2197): [MediaPlaybackService.java:reloadQueue()] oooooo q.length=0
D/MusicBrowser( 2197): [MediaPlaybackService.java:3327:notifyChange()] oooooo {what=com.lge.music.queuechanged}
I/MusicBrowser( 2197): [MediaPlaybackService.java:3329:notifyChange()] oooooo 
D/MusicBrowser( 2197): [MediaPlaybackService.java:3359:notifyChange()] oooooo id : 0
E/SmartCoverUpdateMonitor( 1398): MSG_BIGNOTI_XXX
D/MusicBrowser( 2197): [MediaPlaybackService.java:3360:notifyChange()] oooooo artist : null
D/QuickCircle( 1398): onNotificationsFromDesignatedApps 
D/MusicBrowser( 2197): [MediaPlaybackService.java:3361:notifyChange()] oooooo album : null
D/MusicBrowser( 2197): [MediaPlaybackService.java:3362:notifyChange()] oooooo track : null
D/QuickCircle( 1398): updateMsgBigNoti not in that case
D/QuickCircleBigNotiView( 1398): hide: input type=2/saved state:0
D/MusicBrowser( 2197): [MediaPlaybackService.java:3363:notifyChange()] oooooo playing : false
I/MusicWidget( 2687): _mediaDataObserver onChange()
D/LIA_Service_RemoteProxy( 1971): onServiceConnected() : com.lge.ia.task.mrgdblogger
I/MusicWidget( 2687): beingMusicWidget_4x2() result::false
D/MusicBrowser( 2197): [MediaPlaybackService.java:3364:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2197): [MediaPlaybackService.java:3365:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2197): [MediaPlaybackService.java:3366:notifyChange()] oooooo ListSize : 0
I/MusicWidget( 2687): intentReceiver onReceive() action::com.lge.music.queuechanged
I/MusicBrowser( 2197): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2197): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MediaScannerEx( 3347): [MediaScanner] scanDirectories()[0] = /storage/emulated/0
D/MediaScannerEx( 3347): [MediaScanner] scanDirectories()[1] = /storage/external_SD
I/MusicWidget( 2687): beingMusicWidget_4x2() result::false
D/MusicBrowser( 2197): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2197): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2197): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicWidget( 2687): beingMusicWidget_4x1() result::true
I/MusicWidget( 2687): send mDelayedStopHandler
I/MusicWidget( 2687): performViewUpdater handleMessage() msg.what::0
D/MusicBrowser( 2197): [MediaPlaybackService.java:3327:notifyChange()] oooooo {what=com.lge.music.metachanged}
I/MusicBrowser( 2197): [MediaPlaybackService.java:3329:notifyChange()] oooooo 
D/MusicBrowser( 2197): [MediaPlaybackService.java:3359:notifyChange()] oooooo id : 0
D/MusicBrowser( 2197): [MediaPlaybackService.java:3360:notifyChange()] oooooo artist : null
D/MusicBrowser( 2197): [MediaPlaybackService.java:3361:notifyChange()] oooooo album : null
D/MusicBrowser( 2197): [MediaPlaybackService.java:3362:notifyChange()] oooooo track : null
D/MusicBrowser( 2197): [MediaPlaybackService.java:3363:notifyChange()] oooooo playing : false
D/MusicBrowser( 2197): [MediaPlaybackService.java:3364:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2197): [MediaPlaybackService.java:3365:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2197): [MediaPlaybackService.java:3366:notifyChange()] oooooo ListSize : 0
I/MusicWidget( 2687): beingMusicWidget_4x1() result::true
I/MusicWidget( 2687): performUpdate()_4x1
I/MusicWidget( 2687): defaultAppWidget()_4x1
I/MusicBrowser( 2197): [MediaPlaybackService.java:3378:notifyChange()] oooooo mRemoteControlClient.editMetadata :: META_CHANGED 
I/MusicBrowser( 2197): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=false}
I/MusicBrowser( 2197): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MmsConfig( 3290): getUserModeNotAllowedSms:sUserModeNotAllowedSms:false
D/MmsConfig( 3290): isNotAllowedSms: currentUser:0
D/MmsConfig( 3290): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3290): isUserMode:false
D/MusicBrowser( 2197): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2197): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2197): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2197): [MediaPlaybackService.java:9953:run()] oooooo AlbumImageUpdater() run :: Start
I/MusicBrowser( 2197): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2197): [MediaPlaybackService.java:10005:run()] oooooo AlbumImageUpdater() run :: End
I/MusicBrowser( 2197): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
W/ResourcesManager( 4162): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/LIA_MrGDBLogger_LIARemoteManager( 2665): [dreamwood]getProperties()
W/ResourcesManager( 4162): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
D/LIA_MrGDBLogger_TaskLauncher( 2665): [dreamwood]getTaskPropertyList() - main launcher : false
E/[SMS_LW]( 3290): getMaxEfSms(), maxSms-1
W/ResourcesManager( 4162): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/SmsWrapper( 3290): [LGE] getMaxEFSMS for single sim: -1
I/MusicWidget( 2687): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2687): 4x1_currentTheme :: null
D/MessagingNotification( 3290): simMsgCount = 0
W/ResourcesManager( 4162): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
I/MusicWidget( 2687): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2687): setDefaultViewLayoutId()_4x1
V/LIA_Service_RemoteProxy( 1971): onServiceConnected() : Task Property for MrGDBLogger - Activation:true, AutoExecution:true
W/ResourcesManager( 4162): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/MessagingNotification( 3290): simMaxLimitCount = -1
W/ResourcesManager( 4162): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/MusicBrowser( 2197): [MediaPlaybackService.java:3069:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///storage/emulated/0 flg=0x10 }}
D/LIA_Service_RemoteSessionManager( 1971): New RemoteProxy received and try to update proxy map ...
I/LIA_Service_RemoteSessionManager( 1971): Added task & RemoteProxy: MrGDBLogger, com.lge.ia.manager.remote.RemoteProxy@186e3f0e
V/LIA_Service_RemoteSessionManager( 1971): Trying to register task(s) to LIACore ...
D/LIA_Service_TaskLauncher( 1971): register() - main launcher : true
D/LIA_Service_TaskLauncher( 1971): --> MrGDBLogger is registered on LIACores
D/LIA_Service_TaskLauncher( 1971): --> MrGDBLogger is auto execution task. Try to run ...
D/LIA_Service_TaskLauncher( 1971): runTask - main launcher : true
D/LIA_Service_RemoteSessionManager( 1971): runTask() : MrGDBLogger
D/LIA_Service_RemoteProxy( 1971): runTask() : Task name & RemoteProxy - MrGDBLogger, com.lge.ia.manager.remote.RemoteProxy@186e3f0e
I/MusicBrowser( 2197): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
I/MusicBrowser( 2197): [MediaPlaybackService.java:3087:onReceive()] oooooo hasInternalMemory ==>> true
I/LIA_Service_LogTracer( 1971): [Log Tracer - Task State Transition] runTask(MrGDBLogger)...... 
D/MusicBrowser( 2197): [MusicUtils.java:9327:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_STARTED
D/LIA_MrGDBLogger_LIARemoteManager( 2665): [dreamwood]runTask() : MrGDBLogger
D/LIA_MrGDBLogger_TaskLauncher( 2665): [dreamwood]runTask - main launcher : false
V/LIA_MrGDBLogger_TaskContext( 2665): [dreamwood]runSession() : MrGDBLogger
D/LIA_MrGDBLogger_LIARemoteService( 2665): [dreamwood]getTask()
W/MusicBrowser( 2197): - Start trace [MusicUtils.query]---------------------------------------------------------------
W/MusicBrowser( 2197): [Line 003747] MusicUtils.java, query() : MusicUtils.query
W/MusicBrowser( 2197): [Line 003757] MusicUtils.java, isMediaScannerScanning() : MusicUtils.query
W/MusicBrowser( 2197): [Line 001952] MediaPlaybackService.java, onChange() : MusicUtils.query
W/MusicBrowser( 2197): [Line 000130] ContentObserver.java, onChange() : MusicUtils.query
W/MusicBrowser( 2197): - End   trace [MusicUtils.query]---------------------------------------------------------------
D/LIA_MrGDBLogger_TaskSession( 2665): [dreamwood]TaskSession.of() - thread id : 203, thread name : Binder_4
I/LIA_MrGDBLogger_LogTracer( 2665): [dreamwood][Log Tracer - Task State Transition] create(MrGDBLogger)...... Request
E/LIA_MrGDBLogger_MrGDBLoggerTask( 2665): [dreamwood]onCreate
I/LIA_MrGDBLogger_LogTracer( 2665): [dreamwood][Log Tracer - Task State Transition] create(MrGDBLogger)...... Success
I/LIA_MrGDBLogger_TaskSession( 2665): [dreamwood]MrGDBLogger task is created !!
I/LIA_MrGDBLogger_TaskSession( 2665): [dreamwood]MrGDBLogger create() process time = 1 msec
D/LIA_MrGDBLogger_TaskSession( 2665): [dreamwood]enable() - enable state : false, thread id : 203, thread name : Binder_4
I/LIA_MrGDBLogger_LogTracer( 2665): [dreamwood][Log Tracer - Task State Transition] start(MrGDBLogger)...... Request
I/MusicWidget( 2687): appWidgetViewUpdate()_4x1
I/MusicWidget( 2687): linkButtons()_4x1
D/LIA_MrGDBLogger_MrGDBLoggerTask( 2665): [dreamwood]MrGDBLoggerTask start
D/LIA_MrGDBLogger_DataRepositoryBase( 2665): [dreamwood]setDataType !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
D/LIA_MrGDBLogger_DataRepositoryBase( 2665): [dreamwood]DataRepositoryBase Context : com.lge.ia.task.mrgdblogger
D/LIA_MrGDBLogger_MrGDBHelper( 2665): [dreamwood]make new DBHelper
D/LIA_MrGDBLogger_DataRepositoryBase( 2665): [dreamwood]setDataType !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
D/LIA_MrGDBLogger_DataRepositoryBase( 2665): [dreamwood]DataRepositoryBase Context : com.lge.ia.task.mrgdblogger
I/MusicWidget( 2687): pushUpdate()_4x1
D/LIA_MrGDBLogger_AppUsageDetector( 2665): [dreamwood]isScreenOn : true
D/LIA_MrGDBLogger_ActionManagerMessageDetector( 2665): [dreamwood]start
I/MusicWidget( 2687): intentReceiver onReceive() action::com.lge.music.metachanged
W/ActivityManager( 1033): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
W/ActivityManager( 1033): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
D/LIA_MrGDBLogger_MrGDBLoggerTask( 2665): [dreamwood]startBoardDetector
I/MusicWidget( 2687): beingMusicWidget_4x2() result::false
D/LIA_MrGDBLogger_MrGDBLoggerTask( 2665): [dreamwood]startCBSettingDetector
I/MusicWidget( 2687): beingMusicWidget_4x1() result::true
I/MusicWidget( 2687): send mDelayedStopHandler
I/MusicWidget( 2687): performViewUpdater handleMessage() msg.what::0
D/LIA_MrGDBLogger_ConciergeSettingDetector( 2665): [dreamwood]start
D/LIA_MrGDBLogger_ConciergeSettingDetector( 2665): [dreamwood]registerContentObserver
I/MusicWidget( 2687): beingMusicWidget_4x1() result::true
I/MusicWidget( 2687): performUpdate()_4x1
I/MusicWidget( 2687): defaultAppWidget()_4x1
I/MusicWidget( 2687): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2687): 4x1_currentTheme :: null
I/MusicWidget( 2687): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2687): setDefaultViewLayoutId()_4x1
I/[LgeWidgetLib]LgeAppWidgetHostView( 2009): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
D/LIA_MrGDBLogger_MrGDBLoggerTask( 2665): [dreamwood]start AlarmForDBCleaning
I/LIA_MrGDBLogger_ActionManagerMessageDetector( 2665): [dreamwood]connect ActionManager: action id mask = 0x40000
V/LEDService( 1916): stopInternal(), pkg=com.android.mms, id=123
D/MessagingNotification( 3290): disalbleEmotionalLED id= 123
D/ActionManager( 2665): connecting to ActionManagerService...
V/LEDService( 1916): stopInternal(), pkg=com.android.mms, id=946
E/[LgeWidgetLib]LgeAppWidgetHostView( 2009): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/MusicWidget( 2687): appWidgetViewUpdate()_4x1
I/MusicWidget( 2687): linkButtons()_4x1
D/MessagingNotification( 3290): disalbleEmotionalLED id= 946
I/LIA_MrGDBLogger_TaskSession( 2665): [dreamwood]MrGDBLogger start() result: true, process time = 77 msec
I/LIA_MrGDBLogger_LogTracer( 2665): [dreamwood][Log Tracer - Task State Transition] start(MrGDBLogger)...... Success
I/LIA_MrGDBLogger_TaskSession( 2665): [dreamwood]enable() - enable state : true
D/LIA_MrGDBLogger_TaskContext( 2665): [dreamwood]runSeesion() succeeded.
D/LIA_MrGDBLogger_TaskLauncher( 2665): [dreamwood]runTask - succeeded.
I/LIA_Service_RemoteSessionManager( 1971): RemoteProxyMap Size : 1
I/LIA_Service_RemoteSessionManager( 1971): RemoteProxyMap : com.lge.ia.task.mrgdblogger [key: MrGDBLogger]
D/LIA_Service_RemoteProxy( 1971): onServiceConnected() : com.lge.ia.task.informant
D/ActionManager( 2665): connected to ActionManagerService.
D/LIA_MrGDBLogger_ActionManagerMessageDetector( 2665): [dreamwood]handleMessage =1002
D/LIA_MrGDBLogger_ActionManagerMessageDetector( 2665): [dreamwood]Connected to ActionManager Service
D/LIA_Informant_LIARemoteManager( 2665): getProperties()
D/LIA_Informant_TaskLauncher( 2665): getTaskPropertyList() - main launcher : false
V/LIA_Service_RemoteProxy( 1971): onServiceConnected() : Task Property for TermExtraction - Activation:true, AutoExecution:false
V/LIA_Service_RemoteProxy( 1971): onServiceConnected() : Task Property for Informant - Activation:true, AutoExecution:true
D/LIA_Service_RemoteSessionManager( 1971): New RemoteProxy received and try to update proxy map ...
I/LIA_Service_RemoteSessionManager( 1971): Added task & RemoteProxy: TermExtraction, com.lge.ia.manager.remote.RemoteProxy@10fb4d2f
I/LIA_Service_RemoteSessionManager( 1971): Added task & RemoteProxy: Informant, com.lge.ia.manager.remote.RemoteProxy@10fb4d2f
V/LIA_Service_RemoteSessionManager( 1971): Trying to register task(s) to LIACore ...
D/LIA_Service_TaskLauncher( 1971): register() - main launcher : true
D/LIA_Service_TaskLauncher( 1971): --> TermExtraction is registered on LIACores
D/LIA_Service_TaskLauncher( 1971): register() - main launcher : true
D/LIA_Service_TaskLauncher( 1971): --> Informant is registered on LIACores
D/LIA_Service_TaskLauncher( 1971): --> Informant is auto execution task. Try to run ...
D/LIA_Service_TaskLauncher( 1971): runTask - main launcher : true
D/LIA_Service_RemoteSessionManager( 1971): runTask() : Informant
D/LIA_Service_RemoteProxy( 1971): runTask() : Task name & RemoteProxy - Informant, com.lge.ia.manager.remote.RemoteProxy@10fb4d2f
I/LIA_Service_LogTracer( 1971): [Log Tracer - Task State Transition] runTask(Informant)...... 
D/ActionManagerService( 1879): Messenger is registered - action id mask=0x40000
D/LIA_Informant_LIARemoteManager( 2665): runTask() : Informant
D/LIA_Informant_TaskLauncher( 2665): runTask - main launcher : false
V/LIA_Informant_TaskContext( 2665): runSession() : Informant
D/LIA_Informant_LIARemoteService( 2665): getTask()
D/LIA_Informant_TaskSession( 2665): TaskSession.of() - thread id : 200, thread name : Binder_2
I/MusicWidget( 2687): pushUpdate()_4x1
D/MessagingNotification( 3290): unread_count:0, thread_count:0, thread_id:-2
D/MessagingNotification( 3290): toLockscreenWithUnreadMsgCnt - count = 0
I/LIA_Informant_LogTracer( 2665): [Log Tracer - Task State Transition] create(Informant)...... Request
I/[LgeWidgetLib]LgeAppWidgetHostView( 2009): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/LIA_Informant_InformantTask( 2665): create!!!!!!
I/LIA_Informant_LogTracer( 2665): [Log Tracer - Task State Transition] create(Informant)...... Success
I/LIA_Informant_TaskSession( 2665): Informant task is created !!
I/LIA_Informant_TaskSession( 2665): Informant create() process time = 4 msec
D/LIA_Informant_TaskSession( 2665): enable() - enable state : false, thread id : 200, thread name : Binder_2
I/LIA_Informant_LogTracer( 2665): [Log Tracer - Task State Transition] start(Informant)...... Request
I/LIA_Informant_InformantTask( 2665): task start!!!!
D/LIA_Informant_ConciergeCardManager( 2665): start
I/LIA_Informant_ConciergeCardManager( 2665): setState = 0
D/LIA_Informant_ConciergeCardManager( 2665): new actionCategoryID = 117716480
D/LIA_Informant_ActionManagerMessageHandler( 2665): start
D/LIA_Informant_ActionManagerMessageHandler( 2665): connectActionManager
D/LIA_Informant_ConciergeCardManager( 2665): registerActionEventListener
I/LIA_Informant_ActionManagerMessageHandler( 2665): registerListener = concierge_card
I/LIA_Informant_ActionManagerMessageHandler( 2665): after add numListener = 1
I/LIA_Informant_ActionManagerMessageHandler( 2665): connect ActionManager: action id mask = 0x7043600
D/QuickCoverActivity( 3290): lockscreensettings ret = true
D/ActionManager( 2665): connecting to ActionManagerService...
E/[LgeWidgetLib]LgeAppWidgetHostView( 2009): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
D/ActionManager( 2665): connected to ActionManagerService.
D/LIA_Informant_ActionManagerMessageHandler( 2665): handleMessage: what(1002) actionID(0x0)
D/LIA_Informant_ActionManagerMessageHandler( 2665): ActionManager connected!!!!
D/LIA_Informant_ConciergeCardManager( 2665): ActionManager onConnected
D/LIA_Informant_FlowManagerPlant( 2665): WEATHER_BRIEFING
D/ActionManagerService( 1879): Messenger is registered - action id mask=0x7043600
D/SmartCoverUpdateMonitor( 1398): received broadcast lge.intent.action.UNREAD_MESSAGES
D/KeyguardModel( 1458): mReceiver, received action: lge.intent.action.UNREAD_MESSAGES, sendingUserId:0
D/KeyguardModel( 1458): putNotificationIntoList Number: 0 Id: 1 UserId: 0
I/NfcP2pLinkManager( 1897): LLCP deactivated.
I/NfcP2pLinkManager( 1897): Duplicate onLlcpDectivated()
I/LIA_Informant_TaskSession( 2665): Informant start() result: true, process time = 14 msec
I/LIA_Informant_LogTracer( 2665): [Log Tracer - Task State Transition] start(Informant)...... Success
I/LIA_Informant_TaskSession( 2665): enable() - enable state : true
E/SmartCoverUpdateMonitor( 1398): MSG_BIGNOTI_XXX
D/QuickCircle( 1398): onNotificationsFromDesignatedApps 
D/LIA_Informant_TaskContext( 2665): runSeesion() succeeded.
D/LIA_Informant_TaskLauncher( 2665): runTask - succeeded.
I/LIA_Service_RemoteSessionManager( 1971): RemoteProxyMap Size : 3
I/LIA_Service_RemoteSessionManager( 1971): RemoteProxyMap : com.lge.ia.task.mrgdblogger [key: MrGDBLogger]
I/LIA_Service_RemoteSessionManager( 1971): RemoteProxyMap : com.lge.ia.task.informant [key: TermExtraction]
I/LIA_Service_RemoteSessionManager( 1971): RemoteProxyMap : com.lge.ia.task.informant [key: Informant]
D/LIA_Service_RemoteProxy( 1971): onServiceConnected() : com.lge.ia.task.s4urecommender
D/LIA_S4URecommender_LIARemoteManager( 2665): getProperties()
D/LIA_S4URecommender_TaskLauncher( 2665): getTaskPropertyList() - main launcher : false
D/QuickCircle( 1398): updateMsgBigNoti not in that case
D/QuickCircleBigNotiView( 1398): hide: input type=2/saved state:0
V/LIA_Service_RemoteProxy( 1971): onServiceConnected() : Task Property for S4URecommender - Activation:true, AutoExecution:true
D/LIA_Service_RemoteSessionManager( 1971): New RemoteProxy received and try to update proxy map ...
I/LIA_Service_RemoteSessionManager( 1971): Added task & RemoteProxy: S4URecommender, com.lge.ia.manager.remote.RemoteProxy@2dde5f3c
V/LIA_Service_RemoteSessionManager( 1971): Trying to register task(s) to LIACore ...
D/LIA_Service_TaskLauncher( 1971): register() - main launcher : true
D/LIA_Service_TaskLauncher( 1971): --> S4URecommender is registered on LIACores
D/LIA_Service_TaskLauncher( 1971): --> S4URecommender is auto execution task. Try to run ...
D/LIA_Service_TaskLauncher( 1971): runTask - main launcher : true
D/LIA_Service_RemoteSessionManager( 1971): runTask() : S4URecommender
D/LIA_Service_RemoteProxy( 1971): runTask() : Task name & RemoteProxy - S4URecommender, com.lge.ia.manager.remote.RemoteProxy@2dde5f3c
I/LIA_Service_LogTracer( 1971): [Log Tracer - Task State Transition] runTask(S4URecommender)...... 
D/LIA_S4URecommender_LIARemoteManager( 2665): runTask() : S4URecommender
D/LIA_S4URecommender_TaskLauncher( 2665): runTask - main launcher : false
V/LIA_S4URecommender_TaskContext( 2665): runSession() : S4URecommender
D/LIA_S4URecommender_LIARemoteService( 2665): getTask()
I/MessagingNotification( 3290): repeat count :0
D/LIA_S4URecommender_TaskSession( 2665): TaskSession.of() - thread id : 203, thread name : Binder_4
I/iu.UploadsManager( 2328): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
I/LIA_Informant_FlowManagerPlant( 2665): ConciergeScript serverMode = OP_SERVER
E/MediaScannerClient( 3347): SetLocale  locale=en_US ,mLocaleEncoding = 0
D/LIA_Informant_ArchiveManager( 2665): ArchiveManager
I/LIA_Informant_RecoverableAlarmManager( 2665): sharedPreferences key = #Intent;action=com.lge.ia.conciergescript.Polling.Date;end
I/LIA_S4URecommender_LogTracer( 2665): [Log Tracer - Task State Transition] create(S4URecommender)...... Request
I/LGDrmClient( 3347): _DRM_ServiceGet() : Bind lgdrm service
V/ILGDrmService(  319): eDRM_IsSupportedExtension +++
V/ILGDrmService(  319): eDRM_IsSupportedExtension ---
D/LIA_S4URecommender_AsyncChannel( 2665): Send Order (17)
D/LIA_S4URecommender_S4URecommenderTask( 2665): registerRunBatchStarterAlarm entered
W/LIA_S4URecommender_S4URecommenderTask( 2665): unregisterRunBatchStarterAlarm
D/LIA_S4URecommender_S4URecommenderTask( 2665): registerRunBatch start alarm time : Wed Nov 18 00:00:00 GMT+01:00 2015
D/LIA_S4URecommender_AndroidDBHelper( 2665): /data/data/com.lge.ia.task.s4urecommender/
D/LIA_S4URecommender_AndroidDBHelper( 2665): /data/data/com.lge.ia.task.s4urecommender/
D/LIA_S4URecommender_AndroidDBHelper( 2665): /data/data/com.lge.ia.task.s4urecommender/
D/LIA_S4URecommender_CommunicationRankCallLogCollector( 2665): CommunicationRankCallLogCollector Creator
D/LIA_S4URecommender_S4URecommenderTask( 2665): registerListener
D/LIA_S4URecommender_AsyncChannel( 2665): Receive Order (17)
I/LIA_S4URecommender_LogTracer( 2665): [Log Tracer - Task State Transition] create(S4URecommender)...... Success
I/LIA_S4URecommender_TaskSession( 2665): S4URecommender task is created !!
E/WifiAutoControlRegister( 4162): WifiAutoControlRegister
I/LIA_S4URecommender_TaskSession( 2665): S4URecommender create() process time = 23 msec
D/LIA_S4URecommender_TaskSession( 2665): enable() - enable state : false, thread id : 203, thread name : Binder_4
I/LIA_S4URecommender_LogTracer( 2665): [Log Tracer - Task State Transition] start(S4URecommender)...... Request
V/ILGDrmService(  319): eDRM_IsDRMByHnd +++
D/LGDRM   (  319): [DRM]drmUtilCmpPreloadID start : DRM_PRELOAD_CODEC
D/LGDRM   (  319): [DRM]drmUtilCmpPreloadID end : DRM_PRELOAD_CODEC
V/ILGDrmService(  319): eDRM_IsDRMByHnd ---#2
V/ILGDrmService(  319): eDRM_IsDRMByHnd +++
V/ILGDrmService(  319): eDRM_IsDRMByHnd ---#2
V/ILGDrmService(  319): eDRM_ContentInfoByHnd +++
V/ILGDrmService(  319): eDRM_ContentInfoByHnd ---#2
I/LIA_S4URecommender_TaskSession( 2665): S4URecommender start() result: true, process time = 5 msec
I/LIA_S4URecommender_LogTracer( 2665): [Log Tracer - Task State Transition] start(S4URecommender)...... Success
I/LIA_S4URecommender_TaskSession( 2665): enable() - enable state : true
D/LIA_S4URecommender_TaskContext( 2665): runSeesion() succeeded.
D/LIA_S4URecommender_TaskLauncher( 2665): runTask - succeeded.
I/LIA_Service_RemoteSessionManager( 1971): RemoteProxyMap Size : 4
I/LIA_Service_RemoteSessionManager( 1971): RemoteProxyMap : com.lge.ia.task.mrgdblogger [key: MrGDBLogger]
I/LIA_Service_RemoteSessionManager( 1971): RemoteProxyMap : com.lge.ia.task.informant [key: TermExtraction]
I/LIA_Service_RemoteSessionManager( 1971): RemoteProxyMap : com.lge.ia.task.s4urecommender [key: S4URecommender]
I/LIA_Service_RemoteSessionManager( 1971): RemoteProxyMap : com.lge.ia.task.informant [key: Informant]
V/ILGDrmService(  319): eDRM_IsDRMByHnd +++
V/ILGDrmService(  319): eDRM_IsDRMByHnd ---#2
V/ILGDrmService(  319): eDRM_IsDRMByHnd +++
D/ActionManager( 2665): connecting to ActionManagerService...
D/ActionManager( 2665): connected to ActionManagerService.
V/ILGDrmService(  319): eDRM_IsDRMByHnd ---#2
D/ActionManagerService( 1879): Messenger is registered - action id mask=0x43e00
V/ILGDrmService(  319): eDRM_ContentInfoByHnd +++
D/LIA_S4URecommender_S4URecommenderTask( 2665): handleMessage : 1002
D/LIA_S4URecommender_S4URecommenderTask( 2665): Connected to ActionManager Service
V/ILGDrmService(  319): eDRM_ContentInfoByHnd ---#2
D/AntiFlickerReceiver( 4162): action = android.intent.action.BOOT_COMPLETED
D/UsbSettingsReceiver( 4162): [AUTORUN] onReceive() : action = android.intent.action.BOOT_COMPLETED
I/MusicWidget( 2687): performViewUpdater handleMessage() msg.what::1
I/MusicWidget( 2687): beingMusicWidget_4x2() result::false
D/UsbSettingsReceiver( 4162): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 4162): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 4162): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 4162): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/LIA_Informant_RecoverableAlarmManager( 2665): re setRepeating Alarm
D/LIA_Informant_CS_ConciergeScript( 2665): registArchiveManagerListener() - Listener is registered
D/LIA_Informant_CS_ConciergeScript( 2665): scheduleForPolling()
D/LIA_Informant_CS_SQLiteAdapter( 2665): getDataBaseName() : ConciergeScript_enus.db
D/LIA_Informant_CS_ConciergeScriptArchiveManager( 2665): getServerConfiguration() - option(no push): enus
D/UsbSettingsControl( 4162): [AUTORUN] setTetherStatus() : status=false
D/UsbSettingsReceiver( 4162): [AUTORUN] onReceive() : android.intent.action.BOOT_COMPLETED
D/UsbSettingsReceiver( 4162): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 4162): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 4162): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/LIA_Informant_CS_ConciergeScript( 2665): response
D/VibratePatternInfoReceiverEx( 4162): CONFIGURATION_CHANGED
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
D/LIA_Informant_CS_ConciergeScript( 2665): java.net.UnknownHostException: Unable to resolve host "static-avc.lglime.com": No address associated with hostname
D/DSQN    ( 1033): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/LIA_Informant_CS_ConciergeScript( 2665):  JSON object (no network): version: null checksum: null
D/LIA_Informant_ArchiveParameter( 2665): ArchiveParameter  build
D/LIA_Informant_ArchiveParameter( 2665): ArchiveParameter
D/VibratePatternInfo( 4162): Shardpreference empty case
D/LIA_Informant_SharedPreference( 2665): getSharedPreference() keyName : enus
D/LIA_Informant_SharedPreferenceManager( 2665): SP name: ConciergeScript_SharedPreference sp dir: com.lge.ia.task.informant
D/LIA_Informant_SharedPreference( 2665): enus- getSharedPreference():201509010
D/LIA_Informant_CS_ConciergeScript( 2665): Current Language : enus, Stored Database version: 201509010
D/LIA_Informant_LGCloudGcmManager( 2665): getRegistrationId
D/SettingBootReceiver( 4162): onReceive
D/SettingBootReceiver( 4162): Boot Completed intent received, action=android.intent.action.BOOT_COMPLETED
D/SettingsProviderInitializer( 1033): timezoneID is null
I/[SystemUI]LGBootReceiver( 1458): onReceive = android.intent.action.BOOT_COMPLETED
D/SettingBootReceiver( 4162): setStyle()
D/LIA_Informant_LGCloudGcmManager( 2665): registeredVersion = 42101400 currentVersion = 42101400
D/LIA_Informant_LGCloudGcmManager( 2665): registrationId = APA91bHGKs
D/SettingBootReceiver( 4162): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
D/SettingBootReceiver( 4162): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
D/SettingBootReceiver( 4162): com.lge.appwidget.settings.powercontrol is not installed.(Successfully Removed)
I/[SystemUI]LGPowerUI( 1458): onReceive = com.lge.statusbar.bootcompleted
D/LIA_Informant_ArchiveManager( 2665): start()
E/ThermalEngine(  328): [GPU_MON] 0 percent. Current Sampling Time is 1 sec
D/LIA_Informant_ArchiveManager( 2665): start() - archive manager name : ConciergeScriptArchiveManager
D/LIA_Informant_CS_ConciergeScriptArchiveManager( 2665): createScheduler() : POLLING
D/SettingBootReceiver( 4162): SettingStyle=0
D/LIA_Informant_ArchiveManager( 2665): start() - init scheduler.
D/LIA_Informant_ArchiveManager( 2665): start() - start scheduler
D/LIA_Informant_CS_ConciergeScriptScheduler( 2665): Scheduler starts - POLLING
D/LGBootCompleteReceiver( 1826): onReceive : android.intent.action.BOOT_COMPLETED
D/ConfigUtils( 1826): setUsimOperator() : card operator = 
D/ConfigUtils( 1826): setUsimOperator() : result = null
D/ConfigUtils( 1826): setUsimOperator() : simOperator = 
D/ConfigUtils( 1826): setUsimOperator() : usimoperator = 0
D/ConfigUtils( 1826): setSupportedUsimMobilityForVoLTE() : false
D/LGBootCompleteReceiver( 1826): ACTION_BOOT_COMPLETED - NOISE_SUPPRESSION_KEY : false
V/AudioFlinger(  314): setParameters(): io 0, keyvalue ns_enable=OFF, calling pid 1826
D/audio_hw_primary(  314): adev_set_parameters: enter: ns_enable=OFF
V/voice   (  314): voice_set_parameters: enter: ns_enable=OFF
V/compress_voip(  314): voice_extn_compress_voip_set_parameters: enter: ns_enable=OFF
V/compress_voip(  314): voice_extn_compress_voip_set_parameters: exit
V/voice   (  314): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  314): LGE_platform_set_parameters: enter: ns_enable=OFF
V/msm8974_platform(  314): platform_set_parameters: enter: ns_enable=OFF
V/msm8974_platform(  314): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  314): lge_platform_set_loopback_parameters: enter: 
I/PhoneWindow( 1458): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx( 1458): [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 1458): [setNavigationBarColor2] color=0x fff5f5f5
D/SettingBootReceiver( 4162): setAccountMenu()
D/TAG     ( 4162): setKidsMode
D/TAG     ( 4162): mIsOwner, setKidsMode
D/SettingBootReceiver( 4162): setAccountMenu()
V/audio_hw_primary(  314): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  314): adev_set_parameters: ERROR: set param called even when stream out is null
D/ConfigUtils( 1826): This Model Voice Clarity Support : true
D/LGBootCompleteReceiver( 1826): ACTION_BOOT_COMPLETED - VOICE_CLARITY_KEY : false
V/AudioFlinger(  314): setParameters(): io 0, keyvalue voice_clarity=off, calling pid 1826
D/audio_hw_primary(  314): adev_set_parameters: enter: voice_clarity=off
V/voice   (  314): voice_set_parameters: enter: voice_clarity=off
V/compress_voip(  314): voice_extn_compress_voip_set_parameters: enter: voice_clarity=off
V/compress_voip(  314): voice_extn_compress_voip_set_parameters: exit
V/voice   (  314): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  314): LGE_platform_set_parameters: enter: voice_clarity=off
V/msm8974_platform(  314): platform_set_parameters: enter: voice_clarity=off
V/msm8974_platform(  314): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  314): lge_platform_set_loopback_parameters: enter: 
V/audio_hw_primary(  314): adev_set_parameters: exit with code(0)
E/audio_a2dp_hw(  314): adev_set_parameters: ERROR: set param called even when stream out is null
I/SettingBootReceiver( 4162): disable au
D/LIA_Informant_LGCloudGcmManager( 2665): registerForGcm
D/LIA_Informant_LGCloudGcmManager( 2665): checkPlayServices
D/SplitWindow( 1033): check instance of lgWin Window{ba72db0 u0 com.android.systemui}
D/WindowManager( 1033): [PWM]2.notifyNavigationBarColor => Color.TRANSPARENT 
I/SystemUI[Framework]( 1033): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1033): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1033): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1033): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1033): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@351894a1,  pkg=WindowManager.LayoutParams
D/InputDispatcher( 1033): Focus left window: Window{33fe78c3 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/InputDispatcher( 1033): Focus entered window: Window{ba72db0 u0 com.android.systemui}
I/SystemUI[Framework]( 1033): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
V/SettingsProvider( 1033): call_put(system:gentle_vibration_status=1) for 0 calling package = com.android.settings
I/art     ( 1033): Explicit concurrent mark sweep GC freed 17247(825KB) AllocSpace objects, 2(884KB) LOS objects, 33% free, 43MB/65MB, paused 1.738ms total 116.025ms
D/LGBootCompleteReceiver( 1826): onReceive : updateCallrejectNotify rejectCallOption : 1
I/PhoneApp( 1826): saveDefaultRingtoneUriOfOwner = content://media/internal/audio/media/48
D/LIA_Informant_LGCloudGcmManager( 2665): getRegistrationId
D/LIA_Informant_LGCloudGcmManager( 2665): registeredVersion = 42101400 currentVersion = 42101400
D/LIA_Informant_LGCloudGcmManager( 2665): registrationId = APA91bHGKs
I/LIA_Informant_LGCloudGcmManager( 2665): This message is not visible. (debuggable = false)
D/LIA_Informant_CS_ConciergeScriptArchiveManager( 2665): GCM Registration : true / CloudID : 254945183
W/LIA_Informant_ArchiveManager( 2665): onStart() is not overriden
V/SettingsProvider( 1033): call_put(system:smart_ringtone=0) for 0 calling package = com.android.settings
I/[SystemUI]NavigationThemeResource( 1458): notify navigation bar color(0x0)
D/PhoneStatusBar( 1458): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
I/ActivityManager( 1033): Start proc com.lge.voicerecorder for broadcast com.lge.voicerecorder/.bookmarkdb.BootCompletedReceiver: pid=4215 uid=10042 gids={50042, 9997, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
E/MediaScannerClient( 3347): SetLocale  locale=en_US ,mLocaleEncoding = 0
W/MediaScanner( 3347): Error opening directory '/storage/external_SD/', skipping: Permission denied.
D/LGMediaProvider( 3347): [MediaScanner] delete() uri = content://media/external/file
D/LIA_S4URecommender_CommunicationRankerEngineAndroidSync( 2665): youngjung[delayedBatch: RFD Model Learning] elapsed Time: 174
D/LIA_Informant_CS_ConnectionDetector( 2665): connectedToInternet() - Mobile : false, Wi-Fi : false
D/LIA_Informant_CS_ConciergeScript( 2665): updateFromAVC() - Not available Network
D/LIA_Informant_WS_LIAS4USummaryWeather( 2665): LIAS4USummaryWeather created
I/MusicWidget( 2687): _mediaDataObserver onChange()
I/MusicWidget( 2687): beingMusicWidget_4x2() result::false
D/LGMediaProvider( 3347): [MediaScanner] delete() completed notifyChange, uri = content://media/external
W/MusicBrowser( 2197): - Start trace [MusicUtils.query]---------------------------------------------------------------
W/MusicBrowser( 2197): [Line 003747] MusicUtils.java, query() : MusicUtils.query
W/MusicBrowser( 2197): [Line 003757] MusicUtils.java, isMediaScannerScanning() : MusicUtils.query
W/MusicBrowser( 2197): [Line 001952] MediaPlaybackService.java, onChange() : MusicUtils.query
D/LIA_Informant_WS_WeatherServiceReceiver( 2665): WeaetherServiceReceiver created
W/MusicBrowser( 2197): [Line 000130] ContentObserver.java, onChange() : MusicUtils.query
W/MusicBrowser( 2197): - End   trace [MusicUtils.query]---------------------------------------------------------------
D/LIA_S4URecommender_CommunicationRankerEngineAndroidSync( 2665): youngjung[dailyBatchCore] elapsed Time: 9
D/LIA_S4URecommender_S4URecommenderTask( 2665): Prepare Done Callback ~~~ !!!!!!!!!!!
D/LIA_Informant_EventFlowManager( 2665): workerService == null
I/LIA_Informant_EmbeddedWeatherScheduler( 2665): start registerListener
I/LIA_Informant_ActionManagerMessageHandler( 2665): registerListener = concierge_weather_briefing
I/LIA_Informant_ActionManagerMessageHandler( 2665): after add numListener = 2
I/LIA_Informant_EmbeddedWeatherScheduler( 2665): weather scheduler registerListener time = 1447782201995
I/LIA_Informant_ConciergeCardManager( 2665): registerCBStateReceiver
D/LIA_Informant_ConciergeCardManager( 2665): send PING!!!
I/LIA_Informant_ConciergeCardManager( 2665): ping count = 4
D/[Concierge]Service( 2568): Ping received. Pong sent. Sender : null
E/[Concierge]Service( 2568): Failed to request daily-briefing. No cached weather information 
I/LIA_Informant_ConciergeCardManager( 2665): ACTION_PONG onReceive!!!!!
D/LIA_Informant_ConciergeCardManager( 2665): unregister CBStateReceiver
I/LIA_Informant_ConciergeCardManager( 2665): registerCBSettingObserver
V/MediaScanner( 3347): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@3c226022
V/MediaScanner( 3347): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@3c226022
I/LIA_Informant_ConciergeCardManager( 2665): getState = 0
I/LIA_Informant_ConciergeCardManager( 2665): getState = 0
I/LIA_Informant_ConciergeCardManager( 2665): setState = 1
D/LIA_Informant_ConciergeCardManager( 2665): stopInformantCardScheduling
D/LIA_Informant_ConciergeCardManager( 2665): clear event [0]
D/LIA_Informant_ConciergeCardManager( 2665): startInformantCardScheduling
D/LIA_Informant_ConciergeCardManager( 2665): getCBSettings
D/LIA_Informant_ConciergeCardManager( 2665): concierge_add_contact_proposal settings is 1
D/LIA_Informant_ConciergeCardManager( 2665): concierge_redial_recommend settings is 1
I/LIA_Informant_Tips_ModelReleaseConfig( 2665): isSupportModel() : SmartTips App Installed - true
D/LIA_Informant_ConciergeCardManager( 2665): concierge_reconnect_old_contact settings is 1
D/LIA_Informant_ConciergeCardManager( 2665): targetOperator = OPEN
D/LIA_Informant_ConciergeCardManager( 2665): concierge_notify_birthday settings is 1
D/LIA_Informant_ConciergeCardManager( 2665): list size = 4
D/MediaScanner( 3347):  prescan time: 206ms
D/MediaScanner( 3347):     scan time: 209ms
D/MediaScanner( 3347): postscan time: 32ms
D/MediaScanner( 3347):    total time: 447ms
I/LIA_Informant_Tips_LogTracer( 2665): [Log Tracer - State Transition] setState - Created...... Request
D/LIA_Informant_Tips_SmartTipsFlowManager( 2665): start() - 4.21.8, 2014.12.24
I/LIA_Informant_Tips_DateChangeManager( 2665): isFirstStartUp() - false
I/LIA_Informant_Tips_LogTracer( 2665): [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 6, total count : 86, new day : false...... Request
D/LIA_Informant_Tips_DateChangeManager( 2665): DateInfo : SmartTips Total Working Day Count = 86
D/LIA_Informant_Tips_DateChangeManager( 2665): DateInfo : UserGuide Working Duration Count = 6
D/LIA_Informant_Tips_DateChangeManager( 2665): DateInfo : Last Date Check Time = 2015-11-17 18:43:22
I/LIA_Informant_Tips_LogTracer( 2665): [Log Tracer - State Transition] setState - Initialized...... Request
I/LIA_Informant_Tips_UserGuideDBManager( 2665): initialize() - start
I/LIA_Informant_Tips_UserGuideDBManager( 2665): isEmpty() - 31
I/LIA_Informant_Tips_UserGuideDBManager( 2665): isEmpty() - false
D/LIA_Informant_Tips_UserGuideDBManager( 2665): excludeFeatureListIfNeed() user is owner.
I/LIA_Informant_Tips_UserGuideDBManager( 2665): initialize() - done
D/LIA_Informant_Tips_MyGuideCardFlowHandler( 2665): start()
W/ResourcesManager( 1033): Asset path '/system/framework/com.lge.systemui.jar' does not exist or contains no resources.
W/ResourcesManager( 1033): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/iu.UploadsManager( 2328): End new media; added: 0, uploading: 0, time: 246 ms
I/[LGHome]EVENT( 2009): [Launcher.java:5833:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
D/ConciergeFeature( 2665): Trying to open card setting file : /system/etc/mrg_default_forms/ConciergeBoard/card_settings/card_settings.json
I/LIA_Informant_Tips_MyGuideCardScheduler( 2665): loadReqCodeFromSP() : REQ_CODE - 6
D/ConciergeFeature( 2665): concierge_reconnect_old_contact  : true
D/ConciergeFeature( 2665): concierge_add_contact_proposal  : true
D/ConciergeFeature( 2665): concierge_redial_recommend  : true
D/ConciergeFeature( 2665): concierge_notify_birthday  : true
D/ConciergeFeature( 2665): concierge_qmemo  : true
D/ConciergeFeature( 2665): concierge_weather_newsflash  : false
D/ConciergeFeature( 2665): concierge_spring_cleaning  : true
D/ConciergeFeature( 2665): concierge_my_guide  : true
D/ConciergeFeature( 2665): concierge_my_wellness  : true
D/ConciergeFeature( 2665): concierge_isai_keyword_update  : false
I/LIA_Informant_ConciergeCardManager( 2665): availability of concierge_add_contact_proposal: true
D/LIA_Informant_FlowManagerPlant( 2665): ADD_CONTACT_PROPOSAL
D/LIA_Informant_AddPhonebookManager( 2665): CallHistoryChecker constructor
D/LIA_Informant_AddPhoneBookMessageGenerator( 2665): AddPhoneBookMessageGenerator start
I/LIA_Informant_AddPhonebookManager( 2665): start registerListener
I/LIA_Informant_ActionManagerMessageHandler( 2665): registerListener = concierge_add_contact_proposal
I/LIA_Informant_ActionManagerMessageHandler( 2665): after add numListener = 3
I/LIA_Informant_Tips_RecoverableAlarmManager( 2665): restoreAllAlarm() : with handler
D/ConciergeFeature( 2665): Trying to open card setting file : /system/etc/mrg_default_forms/ConciergeBoard/card_settings/card_settings.json
D/ConciergeFeature( 2665): concierge_reconnect_old_contact  : true
D/ConciergeFeature( 2665): concierge_add_contact_proposal  : true
D/ConciergeFeature( 2665): concierge_redial_recommend  : true
D/ConciergeFeature( 2665): concierge_notify_birthday  : true
D/ConciergeFeature( 2665): concierge_qmemo  : true
D/ConciergeFeature( 2665): concierge_weather_newsflash  : false
D/ConciergeFeature( 2665): concierge_spring_cleaning  : true
D/ConciergeFeature( 2665): concierge_my_guide  : true
D/ConciergeFeature( 2665): concierge_my_wellness  : true
D/ConciergeFeature( 2665): concierge_isai_keyword_update  : false
I/LIA_Informant_ConciergeCardManager( 2665): availability of concierge_redial_recommend: true
D/LIA_Informant_FlowManagerPlant( 2665): RECONNECT_NOTI
I/LIA_Informant_RedialManager( 2665): start registerListener
I/LIA_Informant_BoardStateUtil( 2665): isEnabledGBoard() : count > 0 - true
,I/LIA_Informant_RecoverableAlarmManager( 2665): restoreAllAlarm() : without handler
I/LIA_Informant_ActionManagerMessageHandler( 2665): registerListener = concierge_redial_recommend
I/LIA_Informant_ActionManagerMessageHandler( 2665): after add numListener = 4
D/LIA_Informant_RedialManager( 2665): connectS4URecommender
D/LIA_Informant_BoardStateUtil( 2665): isEnabledMyGuideOfGboard : true
D/LIA_Informant_Tips_MyGuideCardFlowHandler( 2665): restoreFormEvent() : GBoard is visible and SmartTips option of GBoard is enabled
D/LIA_Informant_Tips_FormEventRepository( 2665): getSize() : size - 0
D/LIA_Informant_Tips_MyGuideCardFlowHandler( 2665): restoreFormEvent() : FormEventRepository SIZE - 0
D/LGMediaProvider( 3347): [MediaScanner] delete() uri = content://media/none/media_scanner
I/LIA_Informant_Tips_CardFormUtil( 2665): isValidHtmlFile() : Valid - true
V/BoardContentProvider( 2665): query(): uri(content://com.lge.mrg.boardcontent/doyouknow) projection([raw_uri]) order(null)
I/LIA_Informant_Tips_CardFormUtil( 2665): isInBoardContract() : in BoardContract - true
I/LIA_Informant_Tips_RestorationJesus( 2665): restoreMissedPromotioinCard() : formUrl is not null, but not valid html file or in BoardContract, MyGuideScheduler - MyGuide/MyGuideBoard/PromotionCard/SmartKeyboard
I/LIA_Informant_Tips_CardFormUtil( 2665): isValidHtmlFile() : Valid - true
V/BoardContentProvider( 2665): query(): uri(content://com.lge.mrg.boardcontent/doyouknow) projection([raw_uri]) order(null)
I/LIA_Informant_Tips_CardFormUtil( 2665): isInBoardContract() : in BoardContract - true
I/LIA_Informant_Tips_RestorationJesus( 2665): restoreMissedPromotioinCard() : formUrl is not null, but not valid html file or in BoardContract, MyGuideScheduler - MyGuide/MyGuideBoard/PromotionCard/QuickCircle
V/SIM_STK ( 1033): Menu title from STK is T-Mobile
I/LIA_Informant_Tips_CardFormUtil( 2665): isValidHtmlFile() : Valid - true
V/BoardContentProvider( 2665): query(): uri(content://com.lge.mrg.boardcontent/doyouknow) projection([raw_uri]) order(null)
I/LIA_Informant_Tips_CardFormUtil( 2665): isInBoardContract() : in BoardContract - true
I/LIA_Informant_Tips_RestorationJesus( 2665): restoreMissedPromotioinCard() : formUrl is not null, but not valid html file or in BoardContract, MyGuideScheduler - MyGuide/MyGuideBoard/PromotionCard/SmartBulletin
I/LIA_Informant_Tips_CardFormUtil( 2665): isValidHtmlFile() : Valid - true
V/BoardContentProvider( 2665): query(): uri(content://com.lge.mrg.boardcontent/doyouknow) projection([raw_uri]) order(null)
I/LIA_Informant_Tips_CardFormUtil( 2665): isInBoardContract() : in BoardContract - true
I/LIA_Informant_Tips_RestorationJesus( 2665): restoreMissedPromotioinCard() : formUrl is not null, but not valid html file or in BoardContract, MyGuideScheduler - MyGuide/MyGuideBoard/PromotionCard/DualWindow
I/VRBookmarkProvider( 4215): [BookmarkProvider.java:76:<init>()-[Thread:Other] BookmarkProvider
I/VRBookmarkProvider( 4215): [BookmarkProvider.java:254:onCreate()-[Thread:Other] onCreate
I/VRBookmarkProvider( 4215): [BookmarkProvider.java:504:registerObservers()-[Thread:Other] registerObservers : content://media/external/audio/media
I/LIA_Informant_Tips_CardFormUtil( 2665): isValidHtmlFile() : Valid - true
V/BoardContentProvider( 2665): query(): uri(content://com.lge.mrg.boardcontent/doyouknow) projection([raw_uri]) order(null)
I/LIA_Informant_Tips_CardFormUtil( 2665): isInBoardContract() : in BoardContract - true
I/LIA_Informant_Tips_RestorationJesus( 2665): restoreMissedPromotioinCard() : formUrl is not null, but not valid html file or in BoardContract, MyGuideScheduler - MyGuide/MyGuideBoard/PromotionCard/QuadHD
I/LIA_Informant_Tips_CardFormUtil( 2665): isValidHtmlFile() : Valid - true
V/BoardContentProvider( 2665): query(): uri(content://com.lge.mrg.boardcontent/doyouknow) projection([raw_uri]) order(null)
D/VRBootCompletedReceiver( 4215): [BootCompletedReceiver.java:25:onReceive()-[Thread:Other] Controller has been started on Boot complete
I/LIA_Informant_Tips_CardFormUtil( 2665): isInBoardContract() : in BoardContract - true
I/LIA_Informant_Tips_RestorationJesus( 2665): restoreMissedPromotioinCard() : formUrl is not null, but not valid html file or in BoardContract, MyGuideScheduler - MyGuide/MyGuideBoard/PromotionCard/QuickCircleCase
D/MediaScannerService( 3347): [MediaScanner] scan() Send Intent ACTION_MEDIA_SCANNER_FINISHED uri : file:///storage/emulated/0
D/VRBootCompletedReceiver( 4215): [BootCompletedReceiver.java:47:onReceive()-[Thread:Other] Voice Recorder launcher enable(1)/disable(2) : 1
I/MusicBrowser( 2197): [MediaPlaybackService.java:3069:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 }}
D/MediaScannerService( 3347): [MediaScanner] done scanning volume external
I/MusicBrowser( 2197): [MediaPlaybackService.java:3087:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2197): [MusicUtils.java:9327:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_FINISHED
V/SIM_STK ( 1033): Menu title from STK is T-Mobile
I/LIA_Informant_LGIntelligentAgent( 2665): [LG Intelligent Agent Info] ----------------------
I/LIA_Informant_LGIntelligentAgent( 2665):  - LIA SDK Version Name : 0.8.20
I/LIA_Informant_LGIntelligentAgent( 2665):  - LIA SDK Release Date : 2014.09.05
I/LIA_Informant_LGIntelligentAgent( 2665):  - LIA Service Version Name : 0.8.20.2
I/LIA_Informant_LGIntelligentAgent( 2665):  - This APK(com.lge.ia.task.informant) Version Name : 4.21.14
I/LIA_Informant_LGIntelligentAgent( 2665): --------------------------------------------------
I/ActivityManager( 1033): Start proc com.lge.mlt for broadcast com.lge.mlt/.MptOnBootReceiver: pid=4240 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1033): Killing 3774:com.google.android.onetimeinitializer/u0a7 (adj 15): empty #17
D/LIA_Service_LIAService( 1971): onStartCommand() : LIAService started! - id :2, intent : Intent { act=com.lge.ia pkg=com.lge.ia }
W/libprocessgroup( 1033): failed to open /acct/uid_10007/pid_3774/cgroup.procs: No such file or directory
I/LIA_Informant_LGIntelligentAgent( 2665): connectLIAService - task name : S4URecommender
I/LIA_Informant_LGIntelligentAgent( 2665): tryConnecting ...
D/AndroidRuntime( 4238): 
D/AndroidRuntime( 4238): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/LIA_Informant_LIATaskLoader( 2665): getTaskSdkClassName : com.lge.ia.LIAS4URecommender
D/LIA_Informant_LIATaskLoader( 2665): classLoad - TargetClass : com.lge.ia.LIAS4URecommender
D/AndroidRuntime( 4238): CheckJNI is OFF
I/LIA_Informant_Tips_RestorationJesus( 2665): restoreMissedPromotioinCard() : formUrl from FormManager is null or empty - MyGuide/MyGuideBoard/PromotionCard/QuadCore
D/LIA_Informant_Tips_MyGuideCardFlowHandler( 2665): restoreMissedPromotionCard() : SIZE = 0
D/LIA_Informant_Tips_DeletionSquad( 2665): deleteInvalidPromotioinCard()
I/LIA_Informant_LIATaskLoader( 2665): createLIAService - Success
I/MusicBrowser( 2197): [MediaPlaybackService.java:reloadQueue()] oooooo 
D/MusicBrowser( 2197): [MediaPlaybackService.java:reloadQueue()] oooooo id=-1
D/MusicBrowser( 2197): [MediaPlaybackService.java:reloadQueue()] oooooo mCardId=-1
D/MusicBrowser( 2197): [MediaPlaybackService.java:reloadQueue()] oooooo mPreferences.id=-1
D/MusicBrowser( 2197): [MediaPlaybackService.java:reloadQueue()] oooooo q=
D/MusicBrowser( 2197): [MediaPlaybackService.java:reloadQueue()] oooooo q.length=0
D/MusicBrowser( 2197): [MediaPlaybackService.java:3327:notifyChange()] oooooo {what=com.lge.music.queuechanged}
I/LIA_Informant_ConnectionProxyHandler( 2665): open() : S4URecommender opened.
I/MusicBrowser( 2197): [MediaPlaybackService.java:3329:notifyChange()] oooooo 
I/LIA_Informant_LGIntelligentAgent( 2665): tryConnecting : map put - 0
D/MusicBrowser( 2197): [MediaPlaybackService.java:3359:notifyChange()] oooooo id : 0
D/MusicBrowser( 2197): [MediaPlaybackService.java:3360:notifyChange()] oooooo artist : null
I/LIA_Informant_ConnectionProxyHandler( 2665): tryConnecting...
D/MusicBrowser( 2197): [MediaPlaybackService.java:3361:notifyChange()] oooooo album : null
D/MusicBrowser( 2197): [MediaPlaybackService.java:3362:notifyChange()] oooooo track : null
D/MusicBrowser( 2197): [MediaPlaybackService.java:3363:notifyChange()] oooooo playing : false
D/MusicBrowser( 2197): [MediaPlaybackService.java:3364:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2197): [MediaPlaybackService.java:3365:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2197): [MediaPlaybackService.java:3366:notifyChange()] oooooo ListSize : 0
I/LIA_Informant_ConnectionProxy( 2665): startService(com.lge.ia.task.s4urecommender) : Success
V/BoardContentProvider( 2665): query(): uri(content://com.lge.mrg.boardcontent/doyouknow) projection([raw_uri]) order(null)
I/MusicWidget( 2687): intentReceiver onReceive() action::com.lge.music.queuechanged
D/LIA_Informant_Tips_DeletionSquad( 2665): deleteInvalidPromotioinCard() : invalidUriList.size() = 0
I/LIA_Informant_ConnectionProxy( 2665): bindService(com.lge.ia.task.s4urecommender) : Success
D/LIA_Informant_Tips_MyGuideCardFlowHandler( 2665): deleteInvalidPromotioinCard() : SIZE = 0
D/LIA_Informant_Tips_UserGuideCardFlowHandler( 2665): start()
I/MusicWidget( 2687): beingMusicWidget_4x2() result::false
I/MusicWidget( 2687): beingMusicWidget_4x1() result::true
I/MusicWidget( 2687): send mDelayedStopHandler
I/MusicWidget( 2687): performViewUpdater handleMessage() msg.what::0
I/MusicBrowser( 2197): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2197): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2197): [MediaPlaybackService.java:2161:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2197): [MediaPlaybackService.java:2163:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2197): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
D/MusicBrowser( 2197): [MediaPlaybackService.java:3327:notifyChange()] oooooo {what=com.lge.music.metachanged}
I/MusicBrowser( 2197): [MediaPlaybackService.java:3329:notifyChange()] oooooo 
D/MusicBrowser( 2197): [MediaPlaybackService.java:3359:notifyChange()] oooooo id : 0
D/MusicBrowser( 2197): [MediaPlaybackService.java:3360:notifyChange()] oooooo artist : null
D/MusicBrowser( 2197): [MediaPlaybackService.java:3361:notifyChange()] oooooo album : null
D/MusicBrowser( 2197): [MediaPlaybackService.java:3362:notifyChange()] oooooo track : null
D/MusicBrowser( 2197): [MediaPlaybackService.java:3363:notifyChange()] oooooo playing : false
D/MusicBrowser( 2197): [MediaPlaybackService.java:3364:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2197): [MediaPlaybackService.java:3365:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2197): [MediaPlaybackService.java:3366:notifyChange()] oooooo ListSize : 0
D/LIA_Informant_Tips_UserGuideXMLParser( 2665): getUpdatedFeatureList() : dyk_userguide_updated_featurelist.xml : use updated file.
I/MusicBrowser( 2197): [MediaPlaybackService.java:3378:notifyChange()] oooooo mRemoteControlClient.editMetadata :: META_CHANGED 
I/MusicBrowser( 2197): [MediaPlaybackService.java:2076:saveQueue()] oooooo {full=false}
D/LIA_Informant_Tips_UserGuideCardFlowHandler( 2665): deleteInvalidFeatureCard() : feature = ugc_guest_mode
I/MusicBrowser( 2197): [MediaPlaybackService.java:2081:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
V/BoardContentProvider( 2665): query(): uri(content://com.lge.mrg.boardcontent/doyouknow) projection([raw_uri]) order(null)
D/MusicBrowser( 2197): [MediaPlaybackService.java:2198:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2197): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2197): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2197): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2197): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
D/LIA_Informant_Tips_UserGuideCardFlowHandler( 2665): deleteInvalidFeatureCard() : feature = ugc_qremote_on_lockscreen
V/BoardContentProvider( 2665): query(): uri(content://com.lge.mrg.boardcontent/doyouknow) projection([raw_uri]) order(null)
I/MusicWidget( 2687): beingMusicWidget_4x1() result::true
I/MusicWidget( 2687): performUpdate()_4x1
I/LIA_Informant_Tips_UserGuideCardFlowHandler( 2665): restoreUserGuideAlarm() : alarm time is empty
I/MusicWidget( 2687): defaultAppWidget()_4x1
I/MusicWidget( 2687): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2687): 4x1_currentTheme :: null
I/MusicWidget( 2687): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2687): setDefaultViewLayoutId()_4x1
D/LIA_Informant_Tips_UserGuideXMLParser( 2665): getXML() : Ok - system/etc/mrg_default_forms/MyGuide/MyGuideBoard/UserGuideCard/userguidecard.xml
I/MusicBrowser( 2197): [MediaPlaybackService.java:9953:run()] oooooo AlbumImageUpdater() run :: Start
I/MusicBrowser( 2197): [MediaPlaybackService.java:10005:run()] oooooo AlbumImageUpdater() run :: End
I/LIA_Informant_Tips_UserGuideDBManager( 2665): checkUploadAllCard() : false - Some features(16) reamain to be uploaded, for example .. ugc_camera_dual
D/LIA_Informant_Tips_UserGuideCardFlowHandler( 2665): getUserGuideDuration() : duration=7, uploaded=false, allCard=false
I/LIA_Informant_Tips_UserGuideCardFlowHandler( 2665): checkUserGuideCountDay() :count is smaller than duration, count = 6
I/LIA_Informant_ActionManagerMessageHandler( 2665): registerListener = dyk_user_guide
I/LIA_Informant_ActionManagerMessageHandler( 2665): after add numListener = 5
D/LIA_Informant_Tips_DateChangeManager( 2665): start()
D/LIA_Informant_Tips_DateChangeManager( 2665): setNextDayAlarm() : 2015-11-18 00:10:00
I/LIA_Informant_Tips_LogTracer( 2665): [Log Tracer - State Transition] setState - Started...... Request
I/MusicBrowser( 2197): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
I/MusicWidget( 2687): appWidgetViewUpdate()_4x1
I/MusicWidget( 2687): linkButtons()_4x1
I/MusicWidget( 2687): pushUpdate()_4x1
I/MusicWidget( 2687): intentReceiver onReceive() action::com.lge.music.metachanged
I/MusicWidget( 2687): beingMusicWidget_4x2() result::false
I/MusicWidget( 2687): beingMusicWidget_4x1() result::true
I/MusicWidget( 2687): send mDelayedStopHandler
I/MusicWidget( 2687): performViewUpdater handleMessage() msg.what::0
I/MusicWidget( 2687): beingMusicWidget_4x1() result::true
I/MusicWidget( 2687): performUpdate()_4x1
I/MusicWidget( 2687): defaultAppWidget()_4x1
I/MusicWidget( 2687): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2687): 4x1_currentTheme :: null
I/MusicWidget( 2687): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2687): setDefaultViewLayoutId()_4x1
I/[LgeWidgetLib]LgeAppWidgetHostView( 2009): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/SQLiteLog( 4240): (283) recovered 10 frames from WAL file /mpt/MPT_MainData.db-wal
I/MusicWidget( 2687): appWidgetViewUpdate()_4x1
I/MusicWidget( 2687): linkButtons()_4x1
I/MusicWidget( 2687): pushUpdate()_4x1
E/[LgeWidgetLib]LgeAppWidgetHostView( 2009): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
D/AndroidRuntime( 4238): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1033): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/[LgeWidgetLib]LgeAppWidgetHostView( 2009): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
V/SplitWindowPolicy( 1916): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1033): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
V/ActivityStackEx( 1033): create ActivityStackEx
E/[LgeWidgetLib]LgeAppWidgetHostView( 2009): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
D/ActivityManager( 1033): setTaskToReturnTo : TaskRecord{8c430d3 #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1033): setTaskToReturnTo : TaskRecord{8c430d3 #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1033): AppWindowTokenEx init.. 
D/ContextHelper( 1033): convertTheme. context->name=com.example.hello themeResourceId=16973833
E/GBMv2   (  336): DFP En is all cleared set to be enabled
D/SplitWindowPolicy( 1916): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1916): topRunningActivity=ActivityInfo{71eda48 co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
D/QuickStatusbarLayout( 1398): Notification difference=198
D/QuickStatusbarLayout( 1398): child = android.widget.LinearLayout{33f551f6 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/LgeAbsQuickCoverView( 1398): mCoverXPos: 0 ,mCoverYPos: 0
D/LgeAbsQuickCoverView( 1398): mCoverWidth: 0 ,mCoverHeight: 0
I/[LGHome]EVENT( 2009): [Launcher.java:1114:onPause()]onPause
D/SplitWindow( 1033): check instance of lgWin Window{37d8913c u0 Starting com.example.hello}
D/AndroidRuntime( 4238): Shutting down VM
D/ActionManagerService( 1879): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 2665): handleMessage: what(1000) actionID(0x1000004)
V/BoardContentProvider( 2665): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2009): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2009): , create_time: 1430558575574
I/GBoardWebViewUtils( 2009): , expire_time: 0
I/GBoardWebViewUtils( 2009): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2009): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2009): , display: false
I/GBoardWebViewUtils( 2009): , animation: false }
I/GBoardWebViewUtils( 2009): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2009): , create_time: 1430558575600
I/GBoardWebViewUtils( 2009): , expire_time: 0
I/GBoardWebViewUtils( 2009): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2009): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2009): , display: false
I/GBoardWebViewUtils( 2009): , animation: false }
I/GBoardWebViewUtils( 2009): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1447331016048
I/GBoardWebViewUtils( 2009): , create_time: 1447331016852
I/GBoardWebViewUtils( 2009): , expire_time: 0
I/GBoardWebViewUtils( 2009): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1447331016048&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2009): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2009): , display: false
I/GBoardWebViewUtils( 2009): , animation: false }
W/ContextImpl( 4240): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.mlt.MptOnBootReceiver.onReceive:107 android.app.ActivityThread.handleReceiver:2586 
I/ActivityManager( 1033): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4273 uid=10318 gids={50318, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/MusicWidget( 2687): performViewUpdater handleMessage() msg.what::1
I/MusicWidget( 2687): beingMusicWidget_4x2() result::false
I/[LGHome]GBoardWebView( 2009): [GBoardWebView.java:266:writeCacheBitmap()]writeCacheBitmap()
I/ActivityManager( 1033): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=4290 uid=10043 gids={50043, 9997, 1028, 3003} abi=armeabi-v7a
I/WindowStateAnimator( 1033): Starting window displayed
I/SystemUI[Framework]( 1033): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1458): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1458): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1458):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1458): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx( 1033): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1033): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1033): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1033): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@351894a1,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1033): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/LgDataFeature( 4240): LgDataFeature() Constructor: none
D/LgDataFeature( 4240): LgDataFeature() Constructor Done, null
D/SplitWindowPolicy( 1916): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1916): topRunningActivity=ActivityInfo{a5510e1 co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
,E/MPT MptOnPowerWatcher( 4240): MptOnPowerWatcher
,E/dbFlushManager( 4240): Handler is not ready.
E/dbFlushManager( 4240): It's going to sleep routine until the message handler is generated.
D/ContextHelper( 4273): convertTheme. context->name=com.example.hello themeResourceId=16973833
,E/MPT MptOnPowerWatcher( 4240): startListen
,I/ActivityManager( 1033): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4315 uid=10050 gids={50050, 9997, 3003, 3001, 1028, 3002, 1015, 1005} abi=armeabi-v7a
I/ActivityManager( 1033): Killing 3801:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,I/art     (  340): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 271us total 12.346ms
I/art     (  340): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 250us total 12.033ms
,I/art     (  340): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 255us total 11.789ms
,I/WebViewFactory( 4273): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,W/libprocessgroup( 1033): failed to open /acct/uid_10008/pid_3801/cgroup.procs: No such file or directory
I/LibraryLoader( 4273): Loading: webviewchromium
I/[LGHome]EVENT( 2009): [Launcher.java:5349:onStop()]onStop
I/LibraryLoader( 4273): Time to load native libraries: 4 ms (timestamps 6801-6805)
I/LibraryLoader( 4273): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4273): Binding Chromium to main looper Looper (main, tid 1) {e403210}
,I/LibraryLoader( 4273): Expected native library version number "",actual native library version number ""
I/chromium( 4273): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4273): Initializing chromium process, renderers=0
W/art     ( 4273): Attempt to remove local handle scope entry from IRT, ignoring
,W/chromium( 4273): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
W/chromium( 4273): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,I/chromium( 4273): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 4273): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
V/AudioPolicyService(  314): registerClient() client 0xb1427460, uid 10318
D/BluetoothManagerService( 1033): Message: 20
D/BluetoothManagerService( 1033): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c006893:true
,D/BluetoothAdapter( 4273): 687235337: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 4273): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4273): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4273): Build Date: 12/12/14 금
I/Adreno-EGL( 4273): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 4273): Remote Branch: 
I/Adreno-EGL( 4273): Local Patches: 
I/Adreno-EGL( 4273): Reconstruct Branch: 
,I/ActivityManager( 1033): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4351 uid=10008 gids={50008, 9997, 3003} abi=armeabi-v7a
D/LocationManagerService( 1033): getProviders()=[passive]
,W/chromium( 4273): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,W/chromium( 4273): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/art     ( 4273): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 4273): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 4273): CordovaWebView is running on device made by: LGE
,I/ContactAccountLoggerTas( 4315): canRun() : Opted Out
W/art     ( 4273): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4273): Attempt to remove local handle scope entry from IRT, ignoring
I/ActivityManager( 1033): Killing 3839:com.lge.clock/u0a10 (adj 15): empty #17
,D/LgDataFeature( 4273): LgDataFeature() Constructor: none
,D/LgDataFeature( 4273): LgDataFeature() Constructor Done, null
W/libprocessgroup( 1033): failed to open /acct/uid_10010/pid_3839/cgroup.procs: No such file or directory
,D/OpenGLRenderer( 4273): Render dirty regions requested: true
I/OpenGLRenderer( 4273): Initialized EGL, version 1.4
D/OpenGLRenderer( 4273): Enabling debug mode 0
,D/Atlas   ( 4273): Validating map...
D/SplitWindow( 1033): check instance of lgWin Window{3282892e u0 com.example.hello/com.example.hello.MainActivity}
,W/GAV2    ( 4315): Thread[Background Non-Blocking-0,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/GAV2    ( 4315): Thread[Background Non-Blocking-0,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ContactAccountLoggerTas( 4315): canRun() : Opted Out
D/WifiService( 1033): New client listening to asynchronous messages
,D/LgDataFeature( 4315): LgDataFeature() Constructor: none
D/LgDataFeature( 4315): LgDataFeature() Constructor Done, null
,I/ActivityManager( 1033): Displayed com.example.hello/.MainActivity: +910ms
I/Timeline( 1033): Timeline: Activity_windows_visible id: ActivityRecord{189b4410 u0 com.example.hello/.MainActivity t2} time:47321
I/Timeline( 4273): Timeline: Activity_idle id: android.os.BinderProxy@37fc9e79 time:47322
I/MediaRouter( 4315): Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/chromium( 4273): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 4273): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/FavoriteContactNamesSup( 4315): get() : Execute runnable (UI thread)
I/ContactLabelSupplier( 4315): get() : Execute runnable (UI thread)
I/ContactLabelSupplier( 4315): get() : OptedIn = false
,D/WiseScreenService( 1953): [OnBootReceiver.java:24:onReceive()] iKeepScreenOn: 0
,D/WiseScreenService( 1953): [OnBootReceiver.java:28:onReceive()] iSmartVideo: 0
W/ContextImpl( 1953): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1763 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.lge.keepscreenon.OnBootReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2586 
W/ContextImpl( 1033): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
W/ContextImpl( 1033): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.dsi.ant.server.AntService.startService:129 
,D/JsMessageQueue( 4273): Set native->JS mode to OnlineEventsBridgeMode
I/ActivityManager( 1033): Start proc com.lge.cloudhub for broadcast com.lge.cloudhub/.service.CloudHubReceiver: pid=4403 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/chromium( 4273): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 4273): 
,I/chromium( 4273): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 4273): 
,W/ActivityManager( 1033): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,V/AudioPolicyService(  314): registerClient() client 0xb14275e0, uid 10003
D/jxcore_app_log( 4273): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435102976
D/JX-Cordova( 4273): jxcore cordova android initializing
,W/ActivityManager( 1033): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
,D/sensors_hal_Time( 1033): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1033): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1033): tsOffsetIs: Apps: 47691264307; DSPS: 1703512; Offset : -4310266497
,V/CloudHub( 4403): [DATABASE][DBConnection|open] open database
E/CloudHub( 4403): [DATABASE][DBConnection|getUserId] User id: 0
E/CloudHub( 4403): [DATABASE][DBConnection|getDatabasePath] Database path: /data/user/0/com.lge.cloudhub/databases/cloudhub.db
I/GBMv2   (  336): >>>GBM state is 1<<<
,E/GBMv2   (  336): DFP En is all cleared set to be enabled
E/GBMv2   (  336): Set value is all cleared set the max
I/GBMv2   (  336): DFP Enabled. Ignore VFP set
V/CloudHub( 4403): [SERVICE][CloudHubReceiver|queryUploadCount] # of contents to upload: 0
V/DownloadManager( 3347): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='197' OR (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3347): created cursor android.database.sqlite.SQLiteCursor@10397ab3 on behalf of 4403
V/CloudHub( 4403): [SERVICE][CloudHubReceiver|queryDownloadCount] # of contents to download: 0
,W/jxcore-log( 4273): Initializing JXcore engine
W/jxcore-log( 4273): JXcore engine is ready
W/jxcore-log( 4273): Starting JXcore engine
,I/ActivityManager( 1033): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4423 uid=10059 gids={50059, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 1033): Killing 3903:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #17
,W/m.example.hello( 4273): type=1400 audit(0.0:146): avc: denied { ioctl } for path="socket:[7323]" dev="sockfs" ino=7323 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 4273): type=1400 audit(0.0:147): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/m.example.hello( 4273): type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[7496]" dev="sockfs" ino=7496 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 4273): type=1400 audit(0.0:149): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/m.example.hello( 4273): type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[24701]" dev="sockfs" ino=24701 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,W/libprocessgroup( 1033): failed to open /acct/uid_10011/pid_3903/cgroup.procs: No such file or directory
,W/jxcore-log( 4273): Platform android
W/jxcore-log( 4273): 
,W/jxcore-log( 4273): Process ARCH arm
W/jxcore-log( 4273): 
I/jxcore-log( 4273): JXcore Cordova bridge is ready!
I/jxcore-log( 4273): 
,W/jxcore-log( 4273): JXcore engine is started
E/UpdateRequestReceiver( 4423): ignoring update request
,E/UpdateRequestReceiver( 4423): ignoring update request
E/UpdateRequestReceiver( 4423): ignoring update request
E/jxcore-log( 4273): >> LGE-LG-D855
E/jxcore-log( 4273): 
,I/jxcore-log( 4273): Total memory 2995761152
I/jxcore-log( 4273): 
I/jxcore-log( 4273): Free memory 899047424
I/jxcore-log( 4273): 
I/jxcore-log( 4273): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4273): 
I/jxcore-log( 4273): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4273): 
E/UpdateRequestReceiver( 4423): ignoring update request
I/jxcore-log( 4273): userPath [ 'www' ]
I/jxcore-log( 4273): 
I/jxcore-log( 4273): Size 1440 2392
I/jxcore-log( 4273): 
E/UpdateRequestReceiver( 4423): ignoring update request
,I/jxcore-log( 4273): Screen Brightness 50
I/jxcore-log( 4273): 
E/jxcore-log( 4273): Dummy Error Log.
E/jxcore-log( 4273): 
E/UpdateRequestReceiver( 4423): ignoring update request
I/ActivityManager( 1033): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4457 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager( 1033): Killing 3923:com.lge.appbox.client/u0a11 (adj 15): empty #17
W/libprocessgroup( 1033): failed to open /acct/uid_10011/pid_3923/cgroup.procs: No such file or directory
,V/DrmBroadcastReceiver( 4457): Receive ACTION_BOOT_COMPLETED
,V/DrmService( 4457): Service onCreate
D/DrmService( 4457): Received new request = 4
,E/UEI.SmartControl( 3986): file observer is disposed!
,D/DrmServiceHandler( 4457): updateDrmPushNotification() : No notification
D/DrmService( 4457): Completed !! request = 4
D/DrmService( 4457): Request count = 0
,I/ActivityManager( 1033): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4474 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/DrmService( 4457): Service onDestroy
I/ActivityManager( 1033): Killing 3944:com.android.browser/u0a12 (adj 15): empty #17
W/libprocessgroup( 1033): failed to open /acct/uid_10012/pid_3944/cgroup.procs: No such file or directory
,I/GBMv2   (  336): >>>GBM state is 0<<<
,I/jxcore-log( 4273): getBuffer is called!!!!
I/jxcore-log( 4273): 
,W/ActivityManager( 1033): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4474): getAccountsCursor
,I/art     ( 1033): Explicit concurrent mark sweep GC freed 16625(898KB) AllocSpace objects, 5(939KB) LOS objects, 33% free, 43MB/65MB, paused 1.736ms total 115.889ms
,W/ActivityManager( 1033): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,V/GLSActivity( 2047): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1033): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/GAV2    ( 4474): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Gmail   ( 4474): Observing account changes for notifications
D/ConciergeFeature( 2665): Trying to open card setting file : /system/etc/mrg_default_forms/ConciergeBoard/card_settings/card_settings.json
,D/ConciergeFeature( 2665): concierge_reconnect_old_contact  : true
D/ConciergeFeature( 2665): concierge_add_contact_proposal  : true
D/ConciergeFeature( 2665): concierge_redial_recommend  : true
D/ConciergeFeature( 2665): concierge_notify_birthday  : true
D/ConciergeFeature( 2665): concierge_qmemo  : true
D/ConciergeFeature( 2665): concierge_weather_newsflash  : false
D/ConciergeFeature( 2665): concierge_spring_cleaning  : true
D/ConciergeFeature( 2665): concierge_my_guide  : true
D/ConciergeFeature( 2665): concierge_my_wellness  : true
D/ConciergeFeature( 2665): concierge_isai_keyword_update  : false
I/LIA_Informant_ConciergeCardManager( 2665): availability of concierge_reconnect_old_contact: true
D/LIA_Informant_FlowManagerPlant( 2665): FAVORITENUM_RECOMMENDER
D/LIA_Informant_FavoriteNumScheduler( 2665): start!
I/LIA_Informant_ActionManagerMessageHandler( 2665): registerListener = concierge_reconnect_old_contact
I/LIA_Informant_ActionManagerMessageHandler( 2665): after add numListener = 6
D/LIA_Informant_FavoriteNumScheduler( 2665): curentDate : 20151117
D/LIA_Informant_FavoriteNumScheduler( 2665): AlarmReceivedDate : 20151117
,D/InformantAlarmUtil( 2665): getFirstAlarm
D/LIA_Informant_InformantCalendarUtil( 2665): getDay()
D/InformantAlarmUtil( 2665): getAlarmListOfDay: day = 4
I/ActivityManager( 1033): Start proc com.lge.clock for content provider com.lge.clock/.alarmclock.ALProvider: pid=4523 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,W/ActivityManager( 1033): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 4474): Error finding the version of the Email provider.....
E/Gmail   ( 4474): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4474): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4474): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1235)
E/Gmail   ( 4474): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:187)
E/Gmail   ( 4474): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4474): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4474): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 4474): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4474): We do not support migrating this version of the Email provider.
,I/Gmail   ( 4474): getAccountsCursor
,I/GLSUser ( 2047): [ChannelManager] Attempting to channel bind connection HttpClient.
,I/GLSUser ( 2047): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
I/ActivityManager( 1033): Start proc com.lge.gnss.airtest for broadcast com.lge.gnss.airtest/.GnssAirTestReceiver: pid=4545 uid=10065 gids={50065, 9997, 1028, 1015} abi=armeabi-v7a
W/ActivityManager( 1033): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,V/GLSActivity( 2047): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1033): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/ActivityThread( 4474): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@333edb21 that was originally bound here
E/ActivityThread( 4474): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@333edb21 that was originally bound here
E/ActivityThread( 4474): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
E/ActivityThread( 4474): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
E/ActivityThread( 4474): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
E/ActivityThread( 4474): 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
E/ActivityThread( 4474): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4474): 	at com.android.emailcommon.service.H.a(SourceFile:181)
E/ActivityThread( 4474): 	at com.android.emailcommon.service.H.mb(SourceFile:224)
E/ActivityThread( 4474): 	at com.android.email.service.n.j(SourceFile:160)
E/ActivityThread( 4474): 	at com.android.email.provider.b.a(SourceFile:171)
E/ActivityThread( 4474): 	at com.android.email.provider.b.F(SourceFile:115)
E/ActivityThread( 4474): 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
E/ActivityThread( 4474): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
E/ActivityThread( 4474): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4474): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4474): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4474): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager( 1033): Unbind failed: could not find connection for android.os.BinderProxy@99980fa
D/LIA_Informant_FavoriteNumScheduler( 2665): setAlarm
D/LIA_Informant_FavoriteNumScheduler( 2665): Date : Tue Nov 17 08:00:00 GMT+01:00 2015
D/ConciergeFeature( 2665): Trying to open card setting file : /system/etc/mrg_default_forms/ConciergeBoard/card_settings/card_settings.json
,D/ConciergeFeature( 2665): concierge_reconnect_old_contact  : true
D/ConciergeFeature( 2665): concierge_add_contact_proposal  : true
D/ConciergeFeature( 2665): concierge_redial_recommend  : true
D/ConciergeFeature( 2665): concierge_notify_birthday  : true
D/ConciergeFeature( 2665): concierge_qmemo  : true
D/ConciergeFeature( 2665): concierge_weather_newsflash  : false
D/ConciergeFeature( 2665): concierge_spring_cleaning  : true
D/ConciergeFeature( 2665): concierge_my_guide  : true
D/ConciergeFeature( 2665): concierge_my_wellness  : true
D/ConciergeFeature( 2665): concierge_isai_keyword_update  : false
I/LIA_Informant_ConciergeCardManager( 2665): availability of concierge_notify_birthday: true
D/LIA_Informant_FlowManagerPlant( 2665): BIRTHDAY_NOTI
D/LIA_Informant_AnniversaryRequester( 2665): AnniversaryRequester
D/LIA_Informant_AnniversaryMessageGenerator( 2665): AnniversaryMessageGenerator
D/LIA_Informant_DailyScheduler( 2665): AlarmCheckingScheduler = 0
D/LIA_Informant_DailyScheduler( 2665): start!
D/LIA_Informant_DailyScheduler( 2665): curentDate : 20151117
D/LIA_Informant_DailyScheduler( 2665): excutedDate : 20151117
I/LIA_Informant_ConciergeCardManager( 2665): after add event [4]
D/LIA_S4URecommender_LIARemoteService( 2665): onStartCommand() : LIARemoteService started! - (Id :3), Intent { act=com.lge.ia.task.s4urecommender pkg=com.lge.ia.task.s4urecommender (has extras) }
D/LIA_Informant_ConnectionProxy( 2665): onServiceConnected() : com.lge.ia.task.s4urecommender
D/LIA_S4URecommender_LIARemoteManager( 2665): getProperties()
D/LIA_S4URecommender_TaskLauncher( 2665): getTaskPropertyList() - main launcher : false
,I/LIA_Informant_ConnectionProxy( 2665): Checking activation option of S4URecommender
I/LIA_Informant_ConnectionProxy( 2665): Task Property : S4URecommender, true
I/LIA_Informant_ConnectionProxy( 2665): Task activation property : S4URecommender, true
I/LIA_Informant_ConnectionProxyHandler( 2665): ConnectionProxyListener - onConnected : 
V/LIA_Informant_ConnectionProxyHandler( 2665): S4URecommender Task Property: Activation:true, AutoExecution:true
D/LIA_Informant_ConnectionProxy( 2665): getTaskConnector(S4URecommender / com.lge.ia.task.s4urecommender) : Thread(1)
D/LIA_S4URecommender_LIARemoteManager( 2665): getTask() : S4URecommender
D/LIA_S4URecommender_TaskLauncher( 2665): getTask() : S4URecommender (main launcher : false)
I/LIA_S4URecommender_TaskContext( 2665): getNewAppSession() : App session is added - com.lge.ia.manager.session.AppSession@62ee06
I/LIA_Informant_ConnectionProxyHandler( 2665): setTaskConnectorIntoTask - Success
I/LIA_Informant_ConnectionProxyHandler( 2665): stopTimeoutTimer
I/LIA_Informant_LGIntelligentAgent( 2665): tryConnecting : onTryConnectionSuccess - com.lge.ia.LIAS4URecommender@2d495cc7
I/LIA_Informant_LGIntelligentAgent( 2665): tryConnecting onTryConnectionSuccess : map remove - 0
D/LIA_Informant_RedialManager( 2665): S4URecommender onConnected!
E/SQLiteLog( 4474): (283) recovered 350 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
I/ActivityManager( 1033): Killing 2479:com.google.android.gms.wearable/u0a5 (adj 15): empty #17
D/AirTest ( 4545): Set airtest_enable to false
,I/Gmail   ( 4474): notifyAccountChanged
,I/Gmail   ( 4474): getAccountsCursor
I/Gmail   ( 4474): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/ActivityManager( 1033): Killing 3966:com.android.cellbroadcastreceiver/u0a16 (adj 15): empty #17
I/Gmail   ( 4474): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4474): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 4474): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/ActivityManager( 1033): Killing 3009:com.android.contacts/u0a19 (adj 15): empty #17
,W/libprocessgroup( 1033): failed to open /acct/uid_10005/pid_2479/cgroup.procs: No such file or directory
,W/libprocessgroup( 1033): failed to open /acct/uid_10016/pid_3966/cgroup.procs: No such file or directory
W/libprocessgroup( 1033): failed to open /acct/uid_10019/pid_3009/cgroup.procs: No such file or directory
W/ActivityManager( 1033): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
V/GLSActivity( 2047): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GoogleHttpClient( 2047): GMS http client unavailable, use old client
I/ActivityManager( 1033): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4569 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager( 1033): Waited long enough for: ServiceRecord{2a73babb u0 com.android.mms/.service.SwitchedService}
,I/Gmail   ( 4474): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_promo (has extras) }
I/Gmail   ( 4474): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_social (has extras) }
,I/Gmail   ( 4474): Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_personal (has extras) }
I/ActivityManager( 1033): Killing 4038:com.lge.email/u0a23 (adj 15): empty #17
W/ResourcesManager( 4569): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/libprocessgroup( 1033): failed to open /acct/uid_10023/pid_4038/cgroup.procs: No such file or directory
,E/ThermalEngine(  328): [GPU_MON] 0 percent. Current Sampling Time is 1 sec
,I/Gmail   ( 4474): getAccountsCursor
,V/GLSActivity( 2047): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LgDataFeature( 4569): LgDataFeature() Constructor: none
D/LgDataFeature( 4569): LgDataFeature() Constructor Done, null
,I/Icing   ( 2328): Storage manager: low false usage 1.99MB avail 19.92GB capacity 21.67GB
,D/UEI.SmartControl( 3986): Internal timer expired: 3
D/UEI.SmartControl( 3986): unbind internal service
D/UEI.SmartControl( 3986): Service.onUnbind: IControl
D/UEI.SmartControl( 3986): Service.onDestroy
D/UEI.SmartControl( 3986): Lock is in USE false
D/UEI.SmartControl( 3986): unbind internal service
W/System.err( 3986): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@fd2077d
W/System.err( 3986): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
W/System.err( 3986): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
W/System.err( 3986): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 3986): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 3986): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 3986): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
W/System.err( 3986): 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
W/System.err( 3986): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
W/System.err( 3986): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3986): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3986): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 3986): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3986): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3986): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 3986): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 3986): java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@fd2077d
D/serial_port( 3986): close(fd = 24)
I/UEI.SmartControl( 3986): Serial port is closed.
I/UEI.SmartControl( 3986): Serial port is closed.
D/UEI.SmartControl( 3986): Blaster closed
D/UEI.SmartControl( 3986): Shut down QS...
D/UEI.SmartControl( 3986): Stopping QS lib
D/UEI.SmartControl( 3986): QS lib stop result = true
D/UEI.SmartControl( 3986): Stopped QS lib
D/UEI.SmartControl( 3986): QS shutdown complete
,I/Babel   ( 4569): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 4569): MmsConfig.loadMmsSettings
I/Babel   ( 4569): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 4569): MmsConfig.loadFromDatabase
,E/Babel   ( 4569): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 4569): MmsConfig.loadFromResources
E/Babel   ( 4569): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 4569): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
W/AudioCapabilities( 4569): Unsupported mime audio/evrc
,W/AudioCapabilities( 4569): Unsupported mime audio/qcelp
W/VideoCapabilities( 4569): Unrecognized profile 2130706433 for video/avc
W/Settings( 4569): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/AudioCapabilities( 4569): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 4569): Unsupported mime audio/qcelp
W/AudioCapabilities( 4569): Unsupported mime audio/evrc
W/VideoCapabilities( 4569): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 4569): Unsupported mime video/divx
W/VideoCapabilities( 4569): Unsupported mime video/divx311
W/VideoCapabilities( 4569): Unsupported mime video/divx4
W/VideoCapabilities( 4569): Unsupported mime video/mp4v-esdp
,V/Babel   ( 4569): babel boot account: SMS
V/Babel   ( 4569): babel boot account: thalitester@gmail.com
I/VideoCapabilities( 4569): Unsupported profile 4 for video/mp4v-es
,W/AudioCapabilities( 4569): Unsupported mime audio/eac3
W/AudioCapabilities( 4569): Unsupported mime audio/ac3
W/AudioCapabilities( 4569): Unsupported mime audio/g726
W/AudioCapabilities( 4569): Unsupported mime audio/wma-voice
W/AudioCapabilities( 4569): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4569): Unsupported mime audio/adpcm
W/VideoCapabilities( 4569): Unsupported mime video/theora
,W/VideoCapabilities( 4569): Unsupported mime video/mjpg
,I/ActivityManager( 1033): Start proc com.lge.hiddenmenu for broadcast com.lge.hiddenmenu/.lgodm.LGODMReceiver: pid=4615 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{2c896449 type 2 when 50128 com.google.android.talk} when 50128
V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{2c84214e type 2 when 50132 com.google.android.talk} when 50132
,W/ResourcesManager( 4615): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager( 1033): Killing 3986:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,V/LGSC    ( 1826): [101] 102, action=android.intent.action.BOOT_COMPLETED, iccState=null
,W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_3986/cgroup.procs: No such file or directory
I/ActivityManager( 1033): Start proc com.lge.defaultaccount for broadcast com.lge.defaultaccount/.receiver.ReceiverBootUp: pid=4635 uid=10073 gids={50073, 9997} abi=armeabi-v7a
,I/Icing   ( 2328): updateResources: need to parse f{com.google.android.gms}
,I/InsertAccount( 4635): The account already exists
,I/ActivityManager( 1033): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=4654 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1033): Killing 3620:com.wsandroid.suite.lge/1000 (adj 15): empty #17
I/art     (  340): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 263us total 14.183ms
,I/art     (  340): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 250us total 11.952ms
,I/art     (  340): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 249us total 11.597ms
,W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_3620/cgroup.procs: No such file or directory
,I/InsertAccount( 4635): The account info in contact DB already exists
W/ResourcesManager( 4654): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/LGBluetoothProfileConnectionReceiver_EasySetting( 4654): [BTUI] ACTION_BOOT_COMPLETED : reset connected device information
,I/ActivityManager( 1033): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4672 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
I/ActivityManager( 1033): Start proc com.lge.lgfota.permission for broadcast com.lge.lgfota.permission/.DmcTargetValidationReceiver: pid=4689 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1033): Killing 4136:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,I/ActivityManager( 1033): Killing 4111:com.lge.lifetracker/u0a37 (adj 15): empty #17
W/libprocessgroup( 1033): failed to open /acct/uid_10080/pid_4136/cgroup.procs: No such file or directory
,W/libprocessgroup( 1033): failed to open /acct/uid_10037/pid_4111/cgroup.procs: No such file or directory
I/Icing   ( 2328): Internal init done: storage state 0
W/ResourcesManager( 4672): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/Icing   ( 2328): Post-init done
,D/TARGETVALIDLATION_RECEIVER( 4689): TargetValidationReceiver_ACTION_BOOT_COMPLETETED Received
D/TARGETVALIDLATION_RECEIVER( 4689): updateFlag = new File(TARGET_FLAG_PATH)
D/TARGETVALIDLATION_RECEIVER( 4689): Do Not display result dialog. it is not used Update Tool!!
,D/CalendarProvider2( 4672): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@3ca4bfa4
,I/ActivityManager( 1033): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.LockSettingsReceiver: pid=4706 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1033): Killing 4162:com.android.settings/1000 (adj 15): empty #17
D/CalendarProvider2( 4672): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 4672): Created com.android.providers.calendar.CalendarAlarmManager@28f66109(com.android.providers.calendar.CalendarProvider2@3ca4bfa4)
W/libprocessgroup( 1033): failed to open /acct/uid_1000/pid_4162/cgroup.procs: No such file or directory
I/InsertAccount( 4635): The account info in calendar DB already exists
,I/Process ( 4635): Sending signal. PID: 4635 SIG: 9
I/ActivityManager( 1033): Killing 4215:com.lge.voicerecorder/u0a42 (adj 15): empty #17
I/LockScreenSettings( 4706): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/ActivityManager( 1033): Process com.lge.defaultaccount (pid 4635) has died
,W/libprocessgroup( 1033): failed to open /acct/uid_10042/pid_4215/cgroup.procs: No such file or directory
I/LockScreenSettings( 4706): Received Broadcast : android.intent.action.BOOT_COMPLETED
V/LGSC    ( 2137): [104] 401
,I/ActivityManager( 1033): Start proc com.lge.springcleaning for broadcast com.lge.springcleaning/.receiver.BootCompleteReceiver: pid=4726 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/BootCompleteReceiver( 4726): hasclipTray = true
,W/ContextImpl( 4726): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.springcleaning.receiver.BootCompleteReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2586 
I/ActivityManager( 1033): Start proc com.lge.springcleaning:AppCleanupService for service com.lge.springcleaning/.service.AppCleanupService: pid=4743 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1033): Killing 4069:com.lge.formmanager/u0a26 (adj 15): empty #17
V/SIM_STK ( 1033): Menu title from STK is T-Mobile
V/SIM_STK ( 1033): Menu title from STK is T-Mobile
,W/libprocessgroup( 1033): failed to open /acct/uid_10026/pid_4069/cgroup.procs: No such file or directory
V/SIM_STK ( 1033): Menu title from STK is T-Mobile
V/SIM_STK ( 1033): Menu title from STK is T-Mobile
V/SIM_STK ( 1033): Menu title from STK is T-Mobile
,I/ActivityManager( 1033): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=4764 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AppCleanupService( 4743): registerAlarm
D/AppCleanupService( 4743): noticeInterval = 2592000000
D/AppCleanupService( 4743): notiDateStr = 2015-11-24 08:57:26
,D/AppCleanupService( 4743): noticeStart = 2015-11-24 08:57:26
D/AppCleanupService( 4743): noticeStart = 1448351846000
D/AppUsageDbAdapter( 4743): initPreloadedAppToTheDB() : row count = 90
,I/art     ( 4764): Almond Protected OAT
,D/WeatherApplication( 4764): removeAccount
,D/WeatherApplication( 4764): Account.length = 0
E/WeatherApplication( 4764): OPERATOR:OPEN
D/WeatherAncestor( 4764): 2 : onReceive, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 18:43:27
W/ActivityManager( 1033): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
D/Weather.Utils( 4764): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 4764): 2 : All the weather widget is gone.
,D/UpdateThreadPoolManager( 4764): 2 : This is isUpdating : false
,D/WeatherService( 4764): 2 : isServiceAlived():false forecastCache:null
,D/ForecastDataCache( 4764): 2 : lastUpdatedTime: 1430558561343
D/ForecastDataCache( 4764): 2 : currentPackageVersion: 4.40.4
,D/ForecastDataCache( 4764): 2 : Cache is not up-to-date, count: 0
I/ActivityManager( 1033): Killing 4290:com.android.managedprovisioning/u0a43 (adj 15): empty #17
,W/libprocessgroup( 1033): failed to open /acct/uid_10043/pid_4290/cgroup.procs: No such file or directory
D/Weather_cast( 4764): 2 : set auto-update time : 11/17 21:43
,D/WeatherAncestor( 4764): 2 : onReceive has processed, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 18:43:27
I/ActivityManager( 1033): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=4784 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1033): Killing 4351:com.google.android.partnersetup/u0a8 (adj 15): empty #17
W/libprocessgroup( 1033): failed to open /acct/uid_10008/pid_4351/cgroup.procs: No such file or directory
,I/art     ( 1033): Explicit concurrent mark sweep GC freed 13228(643KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 2.618ms total 133.675ms
,D/SIMObserver( 4784): action:android.intent.action.BOOT_COMPLETED
,D/SIMObserver( 4784): handle ACTION_BOOT_COMPLETED
D/LgDataFeature( 4784): LgDataFeature() Constructor: none
D/LgDataFeature( 4784): LgDataFeature() Constructor Done, null
,I/ActivityManager( 1033): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=4801 uid=10106 gids={50106, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1033): Killing 4403:com.lge.cloudhub/u0a58 (adj 15): empty #17
W/libprocessgroup( 1033): failed to open /acct/uid_10058/pid_4403/cgroup.procs: No such file or directory
,W/ActivityManager( 1033): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
V/AlarmManager( 1033): RTC_WAKEUP set : Alarm{d381ef1 type 0 when 1447695784208 com.android.providers.contacts} when 1447695784208
,V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{19b8cad6 type 2 when 50064 com.google.android.talk} when 50064
V/AlarmManager( 1033): ELAPSED_WAKEUP set : Alarm{38ffc157 type 2 when 52151 com.google.android.gms} when 52151
I/GAV2    ( 4315): Thread[GAThread,5,main]: No campaign data found.
,W/ResourcesManager( 4801): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4801): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4801): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/System  ( 4801): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/app/YouTube/YouTube.apk"],nativeLibraryDirectories=[/system/app/YouTube/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 4801): Installed default security provider GmsCore_OpenSSL
I/art     ( 2047): Explicit concurrent mark sweep GC freed 31191(1856KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 29MB/45MB, paused 663us total 64.570ms
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
,W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4801): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
I/[SystemUI]LGPowerUI( 1458): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1458): On Skip Timer : true
,D/LgDataFeature( 4801): LgDataFeature() Constructor: none
,D/LgDataFeature( 4801): LgDataFeature() Constructor Done, null
,E/YouTube ( 4801): apps.youtube.app.YouTubeApplication.e:196 YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
,D/DSQN    ( 1033): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/GoogleConversionPing( 4801): Error sending ping
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4801): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4801): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4801): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
D/BluetoothManagerService( 1033): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1033): disable(): mBluetooth = null mBinding = false
,D/BluetoothManagerService( 1033): Message: 2
D/WifiService( 1033): New client listening to asynchronous messages
D/WifiServiceImplEx( 1033): setWifiEnabled: false pid=4273, uid=10318, package= com.example.hello, App Lable : HelloWorld
D/WifiService( 1033): setWifiEnabled: false pid=4273, uid=10318
E/WifiService( 1033): Invoking mWifiStateMachine.setWifiEnabled
I/jxcore-log( 4273): ****TEST TOOK:  5041  ms ****
I/jxcore-log( 4273): 
I/jxcore-log( 4273): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4273): 
W/ContextImpl( 3192): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2586 
,E/AtFwd AutoBoot( 3192): AtFwd Auto Boot Started Successfully
W/ContextImpl( 1933): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:2586 
,D/QcrilMsgTunnelAutoboot( 2375): ComponentInfo{com.qualcomm.qcrilmsgtunnel/com.qualcomm.qcrilmsgtunnel.QcrilMsgTunnelService} started successfully
D/SecUISvc( 1933): Service started flags 0 startId 1
D/SecUISvc( 1933): Thread created.
I/ActivityManager( 1033): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4887 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,D/SecUISvc.WfdReceiver( 1933): WfdReceiver(), wfdActive=true
D/SecUISvc.WfdReceiver( 1933): Creating service, binding to WFD
D/SecUISvc.WfdReceiver( 1933): service: ComponentInfo{com.qualcomm.wfd.service/com.qualcomm.wfd.service.WfdService}
W/ContextImpl( 1933): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.qualcomm.qti.services.secureui.WfdReceiver.<init>:48 com.qualcomm.qti.services.secureui.SecureUIService.run:95 java.lang.Thread.run:818 
I/ActivityManager( 1033): Start proc com.qualcomm.wfd.service:wfd_service for service com.qualcomm.wfd.service/.WfdService: pid=4905 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,D/SecUISvc.WfdReceiver( 1933): WfdService binding has started
D/LgDataFeature( 1933): LgDataFeature() Constructor: none
D/LgDataFeature( 1933): LgDataFeature() Constructor Done, null
,D/WfdService( 4905): onBind()
,D/WfdService( 4905): Creating SessionManagerService with context:android.app.Application@2161c10d
W/ActivityManager( 1033): getRecentTasks: caller 10003 is using old GET_TASKS but privileged; allowing
D/SessionManagerService( 4905): SessionManagerService ctor
D/SessionManagerService( 4905): Reinitializing callback list
,D/SessionManagerService( 4905): Reinitializing HID callback list
D/SessionManagerService( 4905): WFD_CmdHdlr setup successfully
D/SessionManagerService( 4905): teardown()
D/SessionManagerService( 4905): Teardown session, broadcast intents first
D/SessionManagerService( 4905): broadcastWifiDisplayAudioIntent() - flag: false
E/SessionManagerService( 4905): Calling Audio System Proxy disable
V/AudioPolicyManager(  314): setDeviceConnectionState() device: 2000000, state 0, address 
,W/AudioPolicyManager(  314): setDeviceConnectionState() device not connected: 2000000
D/SessionManagerService( 4905): broadcastWifiDisplayVideoEnabled() - flag: false
D/SessionManagerService( 4905): Broadcasting WFD video intent: Intent { act=org.codeaurora.intent.action.WIFI_DISPLAY_VIDEO (has extras) }
W/ContextImpl( 4905): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.qualcomm.wfd.service.SessionManagerService.broadcastWifiDisplayVideoEnabled:1221 com.qualcomm.wfd.service.SessionManagerService.teardown:1053 com.qualcomm.wfd.service.SessionManagerService.<init>:159 
D/SessionManagerService( 4905): No session in progress
,D/AndroidRuntime( 4885): 
D/AndroidRuntime( 4885): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/SessionManagerService( 4905): Cleanup any existing sessions. ret: 0
D/AndroidRuntime( 4885): CheckJNI is OFF
D/WFDNative( 4905): try to load libwfdrtsp.so
,D/WFDNative( 4905): libwfdrtsp.so loaded.
D/WFDNative( 4905): try to load libwfdnative.so
,W/linker  ( 4905): libaudioeffectsole.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
V/[BNRBootReceiver]( 4887): boot receiver action = android.intent.action.BOOT_COMPLETED
V/[BNRBootReceiver]( 4887): set property sys.lge.bnrd = 1
V/[BNRBootReceiver]( 4887): End of BootComplted IF
V/[BNRBootReceiver]( 4887): Boot Receiver Return
,D/CalendarReceiver( 4672): [onReceive] intent = Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.providers.calendar/.CalendarReceiver (has extras) }
V/[BNRBootCompletedThread]( 4887): run
D/CalendarReceiver( 4672): [onReceive] WakeLock new : CalendarReceiver_Provider, ReferenceCounted = true
D/CalendarReceiver( 4672): [onReceive] WakeLock acquire : CalendarReceiver_Provider
D/CalendarReceiver( 4672): [onReceive] android.intent.action.BOOT_COMPLETED
D/CalendarProvider2( 4672): Scheduling check of next Alarm
D/CalendarProvider2( 4672): SCHEDULE_ALARM_REMOVE
,D/CalendarReceiver( 4672): [onReceive] WakeLock release : CalendarReceiver_Provider
V/[BNRBootCompletedThread]( 4887): End of BNRProcess
,V/[BNRBootCompletedThread]( 4887): End of BNRViaWifiProcess
V/[BNRBootCompletedThread]( 4887): End of SpriteProcess
V/[BNRBootCompletedThread]( 4887): exit
I/ActivityManager( 1033): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4945 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,E/WFDNative_CPP( 4905): JNI_OnLoad called
E/WFDNative_CPP( 4905): Unable to find field 
E/WFDNative_CPP( 4905): Unable to find field 
E/UIBCManager( 4905): HID payload is null, ignore callback
E/UIBCManager( 4905): HIDCListener is null, ignore callback
D/WFDNative( 4905): libwfdnative.so loaded.
D/WFDNative( 4905): eventCallback triggered
D/WFDNative( 4905): No event info, ignore.
D/SecUISvc.WfdReceiver( 1933): Connection object created
D/SessionManagerService( 4905): init()
E/SessionManagerService( 4905): listener != null
D/AndroidRuntime( 4885): Calling main entry com.android.commands.pm.Pm
E/SessionManagerService( 4905): WfdDevice arg can not be null
,D/SessionManagerService( 4905): Received intent: #Intent;action=android.intent.action.HDMI_PLUGGED;launchFlags=0x44000010;B.state=false;end
E/ThermalEngine(  328): [GPU_MON] 0 percent. Current Sampling Time is 1 sec
I/art     (  340): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 473us total 20.487ms
I/ActivityManager( 1033): Force stopping com.example.hello appid=10318 user=-1: uninstall pkg
I/ActivityManager( 1033): Killing 4273:com.example.hello/u0a318 (adj 0): stop com.example.hello
,I/art     (  340): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 409us total 19.640ms
,I/art     (  340): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 399us total 18.630ms
,I/WindowState( 1033): WIN DEATH: Window{3282892e u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService( 1033): Client connection lost with reason: 4
D/InputDispatcher( 1033): Window went away: Window{3282892e u0 com.example.hello/com.example.hello.MainActivity}
W/PackageSettings( 1033): Skipping PackageSetting{3fd59707 com.test.thalitest/10311} due to missing metadata
,W/ActivityManager( 1033): Force removing ActivityRecord{189b4410 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,D/SplitWindowManager( 1033): removeStackAndNeedHomeResume ActivityStack{22203d96 stackId=1, 0 tasks}
,E/GBMv2   (  336): DFP En is all cleared set to be enabled
,W/ActivityManager( 1033): Spurious death for ProcessRecord{12821d17 4273:com.example.hello/u0a318}, curProc for 4273: null
D/SplitWindowPolicy( 1916): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1916): topRunningActivity=ActivityInfo{62ee06 co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
I/ActivityManager( 1033): Force stopping com.example.hello appid=10318 user=0: pkg removed
I/[LGHome]EVENT( 2009): [Launcher.java:5338:onStart()]onStart
D/SplitWindowPolicy( 1916): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1916): topRunningActivity=ActivityInfo{2d495cc7 co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2009): [Launcher.java:903:onResume()]onResume
,D/KeyguardModel( 1458): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
D/LIA_Service_RemotePackageHandler( 1971): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.example.hello
D/LIA_MrGDBLogger_PackageInfoDetector( 2665): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.example.hello
W/ResourcesManager( 4945): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/InputReader( 1033): Reconfiguring input devices.  changes=0x00000010
,W/System.err( 4240): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 4240): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4240): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4240): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4240): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4240): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4240): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4240): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4240): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4240): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4240): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4240): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
W/GeofencerStateMachine( 1790): Ignoring removeGeofence because network location is disabled.
I/[LGHome]GBoardWebView( 2009): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1879): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 2665): handleMessage: what(1000) actionID(0x1000003)
,I/[LGHome]LGActivityUtil( 2009): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 2009): [Launcher.java:1056:onResume()]onResume end
I/[SystemUI]QSlideListController( 1458): onReceive = android.intent.action.PACKAGE_REMOVED
D/WallpaperManager( 2009): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,D/KeyguardModel( 1458): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1458): createShortcutInfo...
D/administrator( 1033): Handling package changes for user 0
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1458): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1458): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1458): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1458): createShortcutInfo...
W/ResourcesManager( 1458): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1458): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1458): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1458): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 2009): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2009): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
W/ResourceType( 1458): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1458): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/SplitUIManager( 1843): split_name #11 / not available #0
D/SplitUIService( 1843): removed split : 
D/KeyguardModel( 1458): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1458): createShortcutInfo...
,W/ResourcesManager( 1458): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1458): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1458): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1458): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
V/SIM_STK ( 1033): Menu title from STK is T-Mobile
,D/KeyguardModel( 1458): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1458): createShortcutInfo...
W/ResourcesManager( 1458): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1458): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1458): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1458): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
W/ResourceType( 1458): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1458): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/art     ( 2009): Background sticky concurrent mark sweep GC freed 40695(2MB) AllocSpace objects, 54(7MB) LOS objects, 11% free, 73MB/83MB, paused 6.936ms total 48.371ms
,D/CalendarApplication( 4945): CalendarApplication.onCreate()
I/GAV2    ( 4474): Thread[GAThread,5,main]: No campaign data found.
D/KeyguardModel( 1458): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1458): createShortcutInfo...
D/SplitUIManager( 1843): split_name #11 / not available #0
I/SplitUIService( 1843): split app #11
,D/KeyguardModel( 1458): handleShortcutListChanged...
D/KeyguardModel( 1458): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1458): createShortcutInfo...
D/KeyguardModel( 1458): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1458): createShortcutInfo...
W/ResourceType( 1458): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1458): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/KeyguardModel( 1458): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1458): createShortcutInfo...
W/ResourceType( 1458): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1458): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1458): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1458): createShortcutInfo...
W/ResourceType( 1458): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1458): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1458): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1458): createShortcutInfo...
D/KeyguardModel( 1458): handleShortcutListChanged...
D/PreferenceKeysParser( 4945): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 4945): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@1c7f58c2, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@175016d3, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@e403210, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@28f66109, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@186e3f0e, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@10fb4d2f, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@2dde5f3c, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@2d1b04c5, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@25533e1a, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@23798d4b, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@36d03328, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3f2c2841, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@3d5721e6, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@851b327, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@268959d4, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@fd2077d, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2637672, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@209c5ac3, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@3c0c3f40, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@37fc9e79, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@196e87be, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@3c5fe01f, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@22160f6c, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@159fa935, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@2e8761ca, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3bac5f3b, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@100ab658, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@382ea3b1, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@2da1d096, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2577b417, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@da0e004, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@18d8c9ed, lg_pref,erences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@3c226022, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@10397ab3, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@54df870, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@1a8517e9, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3f2a5c6e, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@38470f0f, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@11722b9c, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@d8e49a5, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@3aa3d17a, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@1fef8
D/GeneralPreferenceUtils( 4945): [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
,D/Config  ( 4945): [init]
I/Config  ( 4945): LGCalendar ver.4.40.16
I/Config  ( 4945): start check model
I/Config  ( 4945): start check native_ca
I/Config  ( 4945): Config Operator=OPEN, Country=EU
D/Config  ( 4945): [setDefaultValuesToPref]
,D/Config  ( 4945): [parseProfiles]
D/ProfilesParser( 4945): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 4945): [debug_displayParseInfos] profile.operator = null
D/Config  ( 4945): [updateProfiletoCountryInfo]
D/GeneralPreference( 4945): [checkAndMigrateOldPreference]
,D/AlertReceiver( 4945): onReceive: a=android.intent.action.BOOT_COMPLETED Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.android.calendar/.alerts.AlertReceiver (has extras) }
,I/NotificationService( 1033): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1033): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 1033): Receieved: android.intent.action.PACKAGE_REMOVED
V/SIM_STK ( 1033): Menu title from STK is T-Mobile
I/Timeline( 2009): Timeline: Activity_idle id: android.os.BinderProxy@3431ec39 time:54323
,I/ActivityManager( 1033): Start proc com.nuance.voicemate for broadcast com.nuance.voicemate/com.nuance.androidcore.manifest.receivers.UploadServiceBootStart: pid=4972 uid=10117 gids={50117, 9997, 1028, 1015, 3003, 3001, 3002} abi=armeabi
,D/TaskPersister( 1033): removeObsoleteFile: deleting file=2_task.xml
I/SystemUI[Framework]( 1033): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
D/PhoneStatusBar( 1458): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1458): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1458):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1458): , Keyguard show=false, IME shown=false, Panel expanded=false
,W/PhoneWindowManagerEx( 1033): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1033): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1033): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1033): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@351894a1,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1033): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,I/art     ( 1033): Explicit concurrent mark sweep GC freed 14811(1044KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 3.301ms total 335.044ms
I/InitNotificationRingtoneService( 4945): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 4945): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
D/AndroidRuntime( 4885): Shutting down VM
W/HolidayIntentService( 4945): onHandleIntent
,D/HolidayDataLoader( 4945): readJsonAsset : holiday.json
I/AlertUtils( 4945): [getCalendarNotiSoundURIFromCursor] getCount()= 21
D/AlertService( 4945): 0 Action = android.intent.action.BOOT_COMPLETED
,I/AlertUtils( 4945): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 4945): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
D/AlertService( 4945): [Widget]com.android.calendar.widget.CalendarAppWidgetProvider enabled
D/Feature ( 4945): MemoryLevel - 5:NOT_DEF:Not UI4.2 LOS
I/AlertUtils( 4945): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
D/AlertService( 4945): [Widget]com.android.calendar.widget.MonthWidgetProvider enabled
,D/AlertService( 4945): [Widget]com.android.calendar.widget.WeekWidgetProvider enabled
I/AlertUtils( 4945): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 4945): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 4945): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 4945): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
D/AlertService( 4945): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
I/AlertUtils( 4945): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 4945): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 4945): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 4945): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 4945): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 4945): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 4945): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 4945): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 4945): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
,I/AlertUtils( 4945): set default noti to content://media/internal/audio/media/41
E/HolidayIntentService( 4945): onHandleIntent:holiday data empty
I/InitNotificationRingtoneService( 4945): End InitializeAlertRingtoneService.onHandleIntent
D/AlarmScheduler( 4945): No events found starting within 1 week.
,W/ResourcesManager( 1033): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1033): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2009): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/LgDataFeature( 4972): LgDataFeature() Constructor: none
,D/LgDataFeature( 4972): LgDataFeature() Constructor Done, null
I/Timeline( 1033): Timeline: Activity_windows_visible id: ActivityRecord{1e7dbea9 u0 com.lge.launcher2/.Launcher t1} time:54618
,I/LicenseContentProvider( 4784): start selecting data
D/EULA::SimManager( 4784): SimManager getInstance.
,I/EULA::SimManager( 4784): LGMSimTelephonyManager will be used!
I/EULA::SimManager( 4784): sSimInstance : com.lge.telephony.msim.LGMSimTelephonyManager@2161c10d
I/EULA::SimManager( 4784): sIsMultiSimEnabled : false
I/EULA::SimManager( 4784): sSIMCount : 1
I/EULA::SimManager( 4784): LGMSimTelephonyManager will be used!
I/EULA::SimManager( 4784): sSimInstance : com.lge.telephony.msim.LGMSimTelephonyManager@2161c10d
I/EULA::SimManager( 4784): sIsMultiSimEnabled : false
I/EULA::SimManager( 4784): sSIMCount : 1
D/SIMObserver( 4784): simInfo1
I/ActivityManager( 1033): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4997 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1033): Killing 4423:com.google.android.configupdater/u0a59 (adj 15): empty #17
I/CalendarProvider2( 4672): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 4672): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,W/libprocessgroup( 1033): failed to open /acct/uid_10059/pid_4423/cgroup.procs: No such file or directory
,I/ActivityManager( 1033): Killing 4457:com.lge.drmservice/u0a62 (adj 15): empty #17
,W/libprocessgroup( 1033): failed to open /acct/uid_10062/pid_4457/cgroup.procs: No such file or directory
,I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0

```
