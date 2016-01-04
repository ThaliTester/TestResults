#### Test 50388019831b9e1_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
W/libprocessgroup(  850): failed to open /acct/uid_10021/pid_3406/cgroup.procs: No such file or directory
--------- beginning of main
V/DownloadManager( 3154): Received broadcast intent for android.intent.action.BOOT_COMPLETED
V/DownloadManager( 3154): DownloadService onCreate
I/DownloadManager( 3154): in removeSpuriousFiles
V/DownloadManager( 3154): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 3154): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3154): created cursor android.database.sqlite.SQLiteCursor@3fcbb4e7 on behalf of 3154
I/DownloadManager( 3154): in trimDatabase
V/DownloadManager( 3154): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3154): DownloadService onStartCommand
V/DownloadManager( 3154): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3154): created cursor android.database.sqlite.SQLiteCursor@2fafb332 on behalf of 3154
D/MediaScannerReceiver( 3154): [MediaScanner] ACTION_BOOT_COMPLETED scan INTERNAL_VOLUME, EXTERNAL_VOLUME
D/MediaScannerService( 3154): [MediaScanner] start scanning volume internal: [/system/media, /oem/media, /cust/OPEN_EU/media]
V/LGMediaProvider( 3154): insertInternal: content://media/none/media_scanner, initValues=volume=internal
D/MediaScannerService( 3154): [MediaScanner] scan() ACTION_MEDIA_SCANNER_STARTED uri : file:///system/media
D/MtpService( 3154): updating state; isCurrentUser=true, mMtpLocked=false
I/MusicBrowser( 2708): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///system/media flg=0x10 }}
I/MusicBrowser( 2708): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2708): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_STARTED
D/MtpService( 3154): addStorageLocked 65537 /storage/emulated/0
E/MtpStorageEx( 3154): setAccessCapability false
D/MtpService( 3154): updating state; isCurrentUser=true, mMtpLocked=false
D/WiseScreenService( 1836): [OnBootReceiver.java:24:onReceive()] iKeepScreenOn: 0
D/WiseScreenService( 1836): [OnBootReceiver.java:28:onReceive()] iSmartVideo: 0
W/ContextImpl( 1836): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1804 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.lge.keepscreenon.OnBootReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2663 
D/MediaScannerEx( 3154): [MediaScanner] scanDirectories()[0] = /system/media
D/MediaScannerEx( 3154): [MediaScanner] scanDirectories()[1] = /oem/media
D/MediaScannerEx( 3154): [MediaScanner] scanDirectories()[2] = /cust/OPEN_EU/media
,V/DownloadManager( 3154): created cursor android.database.sqlite.SQLiteCursor@2d6059df on behalf of 3154
I/art     ( 3154): Thread[1,tid=3154,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
E/MediaProfilesEx-JNI( 3154): register_com_lge_media_MediaProfilesEx
E/MediaRecorderEx-JNI( 3154): register_com_lge_media_MediaRecorderEx
D/AudioSystemEx( 3154): register_com_lge_media_LGAudioSystem
E/SurfaceControlEx( 3154): register_com_lge_view_SurfaceControlEx
I/art     ( 3154): Thread[1,tid=3154,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
D/LGMtpDatabaseJNI( 3154): register_android_mtp_LGMtpDatabase
D/LGMtpServerJNI( 3154): register_android_mtp_LGMtpServer
I/art     ( 3154): Thread[1,tid=3154,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
E/MediaPlayerEx-jni( 3154): register_com_lge_view_MediaPlayerEx
I/art     ( 3154): Thread[1,tid=3154,WaitingForJniOnLoad,Thread*=0xb4827800,peer=0x75ab31f8,"main"] recursive attempt to load library "/system/lib/libhook_jni.so"
D/        ( 3154): register_com_lge_emoji_EmojiUtil
E/LGMtpDatabaseJNI( 3154): android_mtp_LGMtpDatabase_setup
I/ActivityManager(  850): Start proc com.lge.voicerecorder for broadcast com.lge.voicerecorder/.bookmarkdb.BootCompletedReceiver: pid=3685 uid=10034 gids={50034, 9997, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
D/MtpService( 3154): starting MTP server in PTP mode
D/LGMtpServer( 3154): LGMtpServer
D/LGMtpServerJNI( 3154): android_mtp_LGMtpServer_setup
D/MtpService( 3154): addStorageLocked 65537 /storage/emulated/0
E/MtpStorageEx( 3154): setAccessCapability false
D/MtpServerEx( 3154): ANR FIX - addStorage!
V/DownloadManager( 3154): DownloadService onDestroy
D/LGMtpServerJNI( 3154): android_mtp_LGMtpServer_run
V/MediaScannerClient( 3154): [MediaScanner]setLocale: = en_US
E/MediaFileEx( 3154): Duplicate type = AVI
E/MediaFileEx( 3154): Duplicate type = ASF
V/MediaScannerClient( 3154): [MediaScanner]setLocale: = en_US
W/MediaScanner( 3154): Error opening directory '/oem/media/', skipping: No such file or directory.
V/MediaScannerClient( 3154): [MediaScanner]setLocale: = en_US
W/MediaScanner( 3154): Error opening directory '/cust/OPEN_EU/media/', skipping: No such file or directory.
D/LGMediaProvider( 3154): [MediaScanner] delete() uri = content://media/internal/file
D/LGMediaProvider( 3154): [MediaScanner] delete() completed notifyChange, uri = content://media/internal
V/MediaScannerEx( 3154): [MediaScanner] isInternalStorage : true
V/MediaScannerEx( 3154): [MediaScanner] isInternalStorage : true
V/MediaScannerEx( 3154): [MediaScanner] isInternalStorage : true
D/MediaScanner( 3154): [MediaScanner] prescan time: 98ms
D/MediaScanner( 3154): [MediaScanner] scan time: 26ms
D/MediaScanner( 3154): [MediaScanner] postscan time: 6ms
D/MediaScanner( 3154): [MediaScanner] total time: 130ms
D/LGMediaProvider( 3154): [MediaScanner] delete() uri = content://media/none/media_scanner
I/VRBookmarkProvider( 3685): [BookmarkProvider.java:76:<init>()-[Thread:Other] BookmarkProvider
I/VRBookmarkProvider( 3685): [BookmarkProvider.java:254:onCreate()-[Thread:Other] onCreate
I/VRBookmarkProvider( 3685): [BookmarkProvider.java:504:registerObservers()-[Thread:Other] registerObservers : content://media/external/audio/media
D/VRBootCompletedReceiver( 3685): [BootCompletedReceiver.java:25:onReceive()-[Thread:Other] Controller has been started on Boot complete
D/VRBootCompletedReceiver( 3685): [BootCompletedReceiver.java:47:onReceive()-[Thread:Other] Voice Recorder launcher enable(1)/disable(2) : 1
I/ActivityManager(  850): Killing 3447:com.google.android.partnersetup/u0a9 (adj 15): empty #11
D/MediaScannerService( 3154): [MediaScanner] scan() Send Intent ACTION_MEDIA_SCANNER_FINISHED uri : file:///system/media
W/libprocessgroup(  850): failed to open /acct/uid_10009/pid_3447/cgroup.procs: No such file or directory
D/LGMediaProvider( 3154): [MediaScanner] mUnmountReceiver ACTION_MEDIA_SCANNER_FINISHED : uri = file:///system/media, path = /system/media
I/MusicBrowser( 2708): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 }}
D/MediaScannerService( 3154): [MediaScanner] done scanning volume internal
D/MediaScannerService( 3154): [MediaScanner] start scanning volume external: [/storage/emulated/0, /storage/external_SD]
I/MusicBrowser( 2708): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2708): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_FINISHED
V/LGMediaProvider( 3154): insertInternal: content://media/none/media_scanner, initValues=volume=external
D/MediaScannerService( 3154): [MediaScanner] scan() ACTION_MEDIA_SCANNER_STARTED uri : file:///storage/emulated/0
D/LGBootCompleteReceiver( 1765): onReceive : android.intent.action.BOOT_COMPLETED
D/ConfigUtils( 1765): setUsimOperator() : card operator = 
D/ConfigUtils( 1765): setUsimOperator() : result = null
V/LGMediaProvider( 3154): insertInternal: content://media/, initValues=name=external
D/ConfigUtils( 1765): setUsimOperator() : simOperator = 
D/ConfigUtils( 1765): setUsimOperator() : usimoperator = 0
D/ConfigUtils( 1765): setSupportedUsimMobilityForVoLTE() : false
I/MusicWidget( 2669): _mediaDataObserver onChange()
D/ConfigUtils( 1765): This Model Voice Clarity Support : false
I/MusicWidget( 2669): beingMusicWidget_4x2() result::false
D/LGBootCompleteReceiver( 1765): onReceive : updateCallrejectNotify rejectCallOption : 1
W/VRBookmarkProvider( 3685): [BookmarkProvider.java:546:onChange()-[Thread:Other] Data Change!! false url : content://media/
I/MusicBrowser( 2708): [MediaPlaybackService.java:reloadQueue()] oooooo 
D/MusicBrowser( 2708): [MediaPlaybackService.java:reloadQueue()] oooooo id=-1
D/MusicBrowser( 2708): [MediaPlaybackService.java:reloadQueue()] oooooo mCardId=-1
D/MusicBrowser( 2708): [MediaPlaybackService.java:reloadQueue()] oooooo mPreferences.id=-1
D/MusicBrowser( 2708): [MediaPlaybackService.java:reloadQueue()] oooooo q=
D/MusicBrowser( 2708): [MediaPlaybackService.java:reloadQueue()] oooooo q.length=0
D/MediaScannerEx( 3154): [MediaScanner] scanDirectories()[0] = /storage/emulated/0
D/MediaScannerEx( 3154): [MediaScanner] scanDirectories()[1] = /storage/external_SD
D/MusicBrowser( 2708): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.queuechanged}
I/MusicBrowser( 2708): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2708): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2708): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2708): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2708): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2708): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2708): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2708): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2708): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicBrowser( 2708): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2708): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/MusicWidget( 2669): intentReceiver onReceive() action::com.lge.music.queuechanged
D/CallRejectInfoToNotify( 1765): update : tPhoneMode : false
I/NotificationManager( 1765): com.android.phone: cancel(2131493582) by com.android.phone
I/MusicWidget( 2669): beingMusicWidget_4x2() result::false
D/MusicBrowser( 2708): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
I/PhoneApp( 1765): saveDefaultRingtoneUriOfOwner = content://media/internal/audio/media/55
D/MusicBrowser( 2708): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2708): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicWidget( 2669): beingMusicWidget_Quick() result::false
I/MusicWidget( 2669): beingMusicWidget_4x1() result::true
I/MusicWidget( 2669): send mDelayedStopHandler
I/MusicWidget( 2669): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2669): beingMusicWidget_Quick() result::false
D/MusicBrowser( 2708): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.metachanged}
I/MusicBrowser( 2708): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2708): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2708): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2708): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2708): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2708): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2708): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2708): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2708): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/ActivityManager(  850): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=3708 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/MusicBrowser( 2708): [MediaPlaybackService.java:3426:notifyChange()] oooooo mRemoteControlClient.editMetadata :: META_CHANGED 
I/MusicBrowser( 2708): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=false}
I/MusicBrowser( 2708): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/MusicBrowser( 2708): [MediaPlaybackService.java:9999:run()] oooooo AlbumImageUpdater() run :: Start
I/MusicBrowser( 2708): [MediaPlaybackService.java:10051:run()] oooooo AlbumImageUpdater() run :: End
D/MusicBrowser( 2708): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2708): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2708): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2708): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2708): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
I/MusicBrowser( 2708): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///storage/emulated/0 flg=0x10 }}
I/MusicBrowser( 2708): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2708): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_STARTED
I/MusicWidget( 2669): intentReceiver onReceive() action::com.lge.music.metachanged
I/MusicWidget( 2669): beingMusicWidget_4x2() result::false
I/MusicBrowser( 2708): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
W/MusicBrowser( 2708): - Start trace [MusicUtils.query]---------------------------------------------------------------
W/MusicBrowser( 2708): [Line 003751] MusicUtils.java, query() : MusicUtils.query
W/MusicBrowser( 2708): [Line 003761] MusicUtils.java, isMediaScannerScanning() : MusicUtils.query
W/MusicBrowser( 2708): [Line 001991] MediaPlaybackService.java, onChange() : MusicUtils.query
W/MusicBrowser( 2708): [Line 000130] ContentObserver.java, onChange() : MusicUtils.query
W/MusicBrowser( 2708): - End   trace [MusicUtils.query]---------------------------------------------------------------
I/MusicWidget( 2669): beingMusicWidget_Quick() result::false
I/MusicWidget( 2669): beingMusicWidget_4x1() result::true
I/MusicWidget( 2669): send mDelayedStopHandler
I/MusicWidget( 2669): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2669): beingMusicWidget_Quick() result::false
D/AndroidRuntime( 3703): 
D/AndroidRuntime( 3703): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/iu.UploadsManager( 2278): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
V/MediaScannerClient( 3154): [MediaScanner]setLocale: = en_US
D/AndroidRuntime( 3703): CheckJNI is OFF
V/DrmBroadcastReceiver( 3708): Receive ACTION_BOOT_COMPLETED
V/DrmService( 3708): Service onCreate
D/DrmService( 3708): Received new request = 4
D/DrmServiceHandler( 3708): updateDrmPushNotification() : No notification
D/DrmService( 3708): Completed !! request = 4
D/DrmService( 3708): Request count = 0
I/MusicWidget( 2669): performViewUpdater handleMessage() msg.what::0
I/ActivityManager(  850): Start proc com.lge.cloudhub for broadcast com.lge.cloudhub/.service.CloudHubReceiver: pid=3731 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/MusicWidget( 2669): beingMusicWidget_4x1() result::true
I/MusicWidget( 2669): performUpdate()_4x1
V/DrmService( 3708): Service onDestroy
I/ActivityManager(  850): Killing 2403:com.android.defcontainer/u0a4 (adj 15): empty #11
I/MusicWidget( 2669): defaultAppWidget()_4x1
I/MusicWidget( 2669): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2669): 4x1_currentTheme :: null
I/MusicWidget( 2669): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2669): setDefaultViewLayoutId()_4x1
I/MusicWidget( 2669): appWidgetViewUpdate()_4x1
I/MusicWidget( 2669): linkButtons()_4x1
D/MediaScannerEx( 3154): [MediaScanner] beginFile() path = /storage/emulated/0/QuicksetLite Setup/data
V/MediaScannerClient( 3154): [MediaScanner]setLocale: = en_US
W/MediaScanner( 3154): Error opening directory '/storage/external_SD/', skipping: Permission denied.
D/LGMediaProvider( 3154): [MediaScanner] delete() uri = content://media/external/file
D/LGMediaProvider( 3154): [MediaScanner] delete() completed notifyChange, uri = content://media/external
W/MusicBrowser( 2708): - Start trace [MusicUtils.query]---------------------------------------------------------------
W/MusicBrowser( 2708): [Line 003751] MusicUtils.java, query() : MusicUtils.query
W/MusicBrowser( 2708): [Line 003761] MusicUtils.java, isMediaScannerScanning() : MusicUtils.query
W/MusicBrowser( 2708): [Line 001991] MediaPlaybackService.java, onChange() : MusicUtils.query
W/MusicBrowser( 2708): [Line 000130] ContentObserver.java, onChange() : MusicUtils.query
W/MusicBrowser( 2708): - End   trace [MusicUtils.query]---------------------------------------------------------------
W/VRBookmarkProvider( 3685): [BookmarkProvider.java:546:onChange()-[Thread:Other] Data Change!! false url : content://media/external
W/VRBookmarkProvider( 3685): [BookmarkProvider.java:563:onChange()-[Thread:Other] EXTERNAL Change!!
V/MediaScanner( 3154): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@3125b918
V/MediaScanner( 3154): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@3125b918
D/MediaScanner( 3154): [MediaScanner] prescan time: 156ms
D/MediaScanner( 3154): [MediaScanner] scan time: 155ms
D/MediaScanner( 3154): [MediaScanner] postscan time: 9ms
D/MediaScanner( 3154): [MediaScanner] total time: 320ms
D/LGMediaProvider( 3154): [MediaScanner] delete() uri = content://media/none/media_scanner
W/libprocessgroup(  850): failed to open /acct/uid_10004/pid_2403/cgroup.procs: No such file or directory
D/MediaScannerService( 3154): [MediaScanner] scan() Send Intent ACTION_MEDIA_SCANNER_FINISHED uri : file:///storage/emulated/0
D/LGMediaProvider( 3154): [MediaScanner] mUnmountReceiver ACTION_MEDIA_SCANNER_FINISHED : uri = file:///storage/emulated/0, path = /storage/emulated/0
I/MusicBrowser( 2708): [MediaPlaybackService.java:1995:onChange()] oooooo 
D/MediaScannerService( 3154): [MediaScanner] done scanning volume external
I/iu.UploadsManager( 2278): End new media; added: 0, uploading: 0, time: 183 ms
V/MusicBrowser( 2708): [MediaPlaybackService.java:5808:getPath()] oooooo {mFileToPlay=null}
I/MusicBrowser( 2708): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 }}
I/MusicWidget( 2669): pushUpdate()_4x1
I/MusicWidget( 2669): performViewUpdater handleMessage() msg.what::1
I/MusicWidget( 2669): beingMusicWidget_4x2() result::false
I/MusicWidget( 2669): _mediaDataObserver onChange()
I/MusicWidget( 2669): beingMusicWidget_4x2() result::false
I/MusicBrowser( 2708): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2708): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_FINISHED
I/MusicBrowser( 2708): [MediaPlaybackService.java:reloadQueue()] oooooo 
D/MusicBrowser( 2708): [MediaPlaybackService.java:reloadQueue()] oooooo id=-1
D/MusicBrowser( 2708): [MediaPlaybackService.java:reloadQueue()] oooooo mCardId=-1
D/MusicBrowser( 2708): [MediaPlaybackService.java:reloadQueue()] oooooo mPreferences.id=-1
D/MusicBrowser( 2708): [MediaPlaybackService.java:reloadQueue()] oooooo q=
D/MusicBrowser( 2708): [MediaPlaybackService.java:reloadQueue()] oooooo q.length=0
D/MusicBrowser( 2708): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.queuechanged}
I/MusicBrowser( 2708): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2708): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2708): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2708): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2708): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2708): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2708): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2708): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2708): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicWidget( 2669): intentReceiver onReceive() action::com.lge.music.queuechanged
I/MusicWidget( 2669): beingMusicWidget_4x2() result::false
I/MusicWidget( 2669): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2708): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicWidget( 2669): beingMusicWidget_4x1() result::true
I/MusicWidget( 2669): send mDelayedStopHandler
I/MusicWidget( 2669): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2669): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2708): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2708): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2708): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2708): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
D/MusicBrowser( 2708): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.metachanged}
I/MusicBrowser( 2708): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2708): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2708): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2708): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2708): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2708): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2708): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2708): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2708): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicWidget( 2669): intentReceiver onReceive() action::com.lge.music.metachanged
I/MusicWidget( 2669): beingMusicWidget_4x2() result::false
I/MusicBrowser( 2708): [MediaPlaybackService.java:3426:notifyChange()] oooooo mRemoteControlClient.editMetadata :: META_CHANGED 
I/MusicWidget( 2669): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2708): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=false}
I/MusicWidget( 2669): beingMusicWidget_4x1() result::true
I/MusicWidget( 2669): send mDelayedStopHandler
I/MusicWidget( 2669): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2669): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2708): [MediaPlaybackService.java:9999:run()] oooooo AlbumImageUpdater() run :: Start
I/MusicBrowser( 2708): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/[LgeWidgetLib]LgeAppWidgetHostView( 1893): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/MusicBrowser( 2708): [MediaPlaybackService.java:10051:run()] oooooo AlbumImageUpdater() run :: End
D/MusicBrowser( 2708): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2708): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2708): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2708): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2708): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
I/MusicBrowser( 2708): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
E/[LgeWidgetLib]LgeAppWidgetHostView( 1893): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
D/AndroidRuntime( 3703): Calling main entry com.android.commands.am.Am
I/ActivityManager(  850): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/CloudHub( 3731): [DATABASE][DBConnection|open] open database
E/CloudHub( 3731): [DATABASE][DBConnection|getUserId] User id: 0
E/CloudHub( 3731): [DATABASE][DBConnection|getDatabasePath] Database path: /data/user/0/com.lge.cloudhub/databases/cloudhub.db
D/ActivityManager(  850): setTaskToReturnTo : TaskRecord{2e2574c #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  850): setTaskToReturnTo : TaskRecord{2e2574c #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  850): AppWindowTokenEx init.. 
V/CloudHub( 3731): [SERVICE][CloudHubReceiver|queryUploadCount] # of contents to upload: 0
D/InputDispatcher(  850): Focus left window: Window{c70fa8b u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 3703): Shutting down VM
D/ContextHelper(  850): convertTheme. context->name=com.example.hello themeResourceId=16973833
I/[LGHome]EVENT( 1893): [Launcher.java:986:onPause()]onPause
V/DownloadManager( 3154): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
I/MusicWidget( 2669): performViewUpdater handleMessage() msg.what::0
V/DownloadManager( 3154): created cursor android.database.sqlite.SQLiteCursor@2c054f71 on behalf of 3731
I/MusicWidget( 2669): beingMusicWidget_4x1() result::true
I/MusicWidget( 2669): performUpdate()_4x1
I/MusicWidget( 2669): defaultAppWidget()_4x1
I/MusicWidget( 2669): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2669): 4x1_currentTheme :: null
I/MusicWidget( 2669): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2669): setDefaultViewLayoutId()_4x1
D/SplitWindow(  850): check instance of lgWin Window{2540d976 u0 Starting com.example.hello}
I/MusicWidget( 2669): appWidgetViewUpdate()_4x1
I/MusicWidget( 2669): linkButtons()_4x1
I/VRBookmarkProvider( 3685): [BookmarkProvider.java:530:handleMessage()-[Thread:Other] -- syncTable() START --
I/ActivityManager(  850): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3763 uid=10317 gids={50317, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1893): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 1949): Closing mic
I/MusicWidget( 2669): pushUpdate()_4x1
I/MicrophoneInputStream( 1949): mic_close com.google.android.apps.gsa.speech.audio.u@2fa4ed4e
V/AudioRecord( 1949): stop()
D/AudioRecord( 1949): AudioRecord->stop()
V/AudioFlinger(  283): RecordHandle::stop()
V/AudioFlinger(  283): RecordThread::stop
V/AudioFlinger(  283): Record stopped OK
V/AudioPolicyManager(  283): stopInput() input 17
V/AudioPolicyService(  283): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  283): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  283): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  283): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  283): ThreadBase::setParameters() routing=0
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 2
I/MusicWidget( 2669): performViewUpdater handleMessage() msg.what::1
V/CloudHub( 3731): [SERVICE][CloudHubReceiver|queryDownloadCount] # of contents to download: 0
I/MusicWidget( 2669): beingMusicWidget_4x2() result::false
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb3a11000
D/audio_hw_primary(  283): in_standby: enter: stream (0xb3806340) usecase(7: audio-record)
I/ActivityManager(  850): Start proc com.lge.gnss.airtest for broadcast com.lge.gnss.airtest/.GnssAirTestReceiver: pid=3780 uid=10054 gids={50054, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  850): Killing 3510:com.lge.lgdmsclient/1000 (adj 15): empty #11
V/audio_hw_primary(  283): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  283): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  283): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  283): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  283): disable_audio_route: exit
E/audio_hw_primary(  283): disable_snd_device: enter 144
D/hardware_info(  283): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  283): disable_snd_device: snd_device(144: lg-vr-handset-mic)
I/[LgeWidgetLib]LgeAppWidgetHostView( 1893): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
V/audio_hw_primary(  283): stop_input_stream: exit: status(0)
V/audio_hw_primary(  283): in_standby: exit:  status(0)
V/AudioFlinger(  283): RecordThread: loop stopping
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioPolicyManager(  283): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  283): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  283): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  283): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioPolicyService(  283): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  283): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  283): setParameters(): io 17, keyvalue hotword_active=0, calling pid 283
V/AudioFlinger(  283): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  283): RecordThread: loop starting
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  283): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  283): in_set_parameters: exit: status(0)
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb3a11000
V/AudioFlinger(  283): RecordThread: loop stopping
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
E/[LgeWidgetLib]LgeAppWidgetHostView( 1893): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
V/AudioRecord( 1949): stop()
V/AudioRecord( 1949): stop()
V/AudioRecord( 1949): stop()
V/AudioFlinger(  283): releasing 16 from 1949 for -1
V/AudioFlinger(  283):  decremented refcount to 0
V/AudioFlinger(  283): purging stale effects
V/AudioFlinger(  283): RecordHandle::stop()
V/AudioFlinger(  283): RecordThread::stop
V/AudioPolicyManager(  283): releaseInput() 17
V/AudioPolicyManager(  283): closeInput(17)
V/AudioFlinger(  283): closeInput() 17
V/AudioSystem(  283): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  850): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1765): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1949): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  283): ThreadBase::exit
V/AudioFlinger(  283): RecordThread: loop starting
V/AudioSystem( 2708): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3123): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1399): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  283): RecordThread 0xb3a11000 exiting
D/audio_hw_primary(  283): adev_close_input_stream: enter:stream_handle(0xb3806340)
D/audio_hw_primary(  283): in_standby: enter: stream (0xb3806340) usecase(7: audio-record)
V/audio_hw_primary(  283): in_standby: exit:  status(0)
V/AudioPolicyService(  283): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  283): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  283): releaseInput() exit
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioFlinger(  283): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  283): removeClient_l() pid 1949, calling pid 283
I/HotwordRecognitionRnr( 1949): Stopping hotword detection.
I/HotwordRecognitionRnr( 1949): Hotword detection finished
,I/[LGHome]EVENT( 1893): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  850): Starting window displayed
I/SystemUI[Framework](  850): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
W/PhoneWindowManagerEx(  850): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  850): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  850): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  850): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@620a9c2,  pkg=WindowManager.LayoutParams
D/PhoneStatusBar( 1399): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/SystemUI[Framework](  850): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1399): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1399):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1399): , Keyguard show=false, IME shown=false, Panel expanded=false
W/libprocessgroup(  850): failed to open /acct/uid_1000/pid_3510/cgroup.procs: No such file or directory
D/BarTransitions( 1399): draw background and invalidate : color = f000000
D/BarTransitions( 1399): draw background and invalidate : color = 11111111
I/VRBookmarkProvider( 3685): [BookmarkProvider.java:532:handleMessage()-[Thread:Other] -- syncTable() END --
D/ContextHelper( 3763): convertTheme. context->name=com.example.hello themeResourceId=16973833
D/AirTest ( 3780): Set airtest_enable to false
I/ActivityManager(  850): Killing 3532:com.lge.clock/u0a10 (adj 15): empty #11
W/libprocessgroup(  850): failed to open /acct/uid_10010/pid_3532/cgroup.procs: No such file or directory
V/LGSC    ( 2788): [104] 401
I/WebViewFactory( 3763): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/ActivityManager(  850): Start proc com.lge.lgfota.permission for broadcast com.lge.lgfota.permission/.DmcTargetValidationReceiver: pid=3798 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  850): Killing 3560:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #11
I/LibraryLoader( 3763): Time to load native libraries: 2 ms (timestamps 349-351)
I/LibraryLoader( 3763): Expected native library version number "",actual native library version number ""
W/libprocessgroup(  850): failed to open /acct/uid_10011/pid_3560/cgroup.procs: No such file or directory
V/WebViewChromiumFactoryProvider( 3763): Binding Chromium to main looper Looper (main, tid 1) {141ebff6}
I/LibraryLoader( 3763): Expected native library version number "",actual native library version number ""
I/chromium( 3763): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/TARGETVALIDLATION_RECEIVER( 3798): TargetValidationReceiver_ACTION_BOOT_COMPLETETED Received
D/TARGETVALIDLATION_RECEIVER( 3798): updateFlag = new File(TARGET_FLAG_PATH)
D/TARGETVALIDLATION_RECEIVER( 3798): Do Not display result dialog. it is not used Update Tool!!
I/ActivityManager(  850): Killing 3577:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/BrowserStartupController( 3763): Initializing chromium process, singleProcess=true
W/art     ( 3763): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3763): ApplicationContext is null in ApplicationStatus
W/chromium( 3763): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3763): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
V/LGSC    ( 1765): [101] 102, action=android.intent.action.BOOT_COMPLETED, iccState=null
W/libprocessgroup(  850): failed to open /acct/uid_10011/pid_3577/cgroup.procs: No such file or directory
E/libEGL  ( 3763): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3763): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3763): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3763): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 3763): Build Date: 03/02/15 Mon
I/Adreno-EGL( 3763): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 3763): Remote Branch: 
I/Adreno-EGL( 3763): Local Patches: 
I/Adreno-EGL( 3763): Reconstruct Branch: 
W/ContextImpl( 2952): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2663 
E/AtFwd AutoBoot( 2952): AtFwd Auto Boot Started Successfully
I/GoogleHttpClient( 2067): GMS http client unavailable, use old client
I/ActivityManager(  850): Start proc com.lge.defaultaccount for broadcast com.lge.defaultaccount/.receiver.ReceiverBootUp: pid=3823 uid=10062 gids={50062, 9997} abi=armeabi-v7a
V/AudioPolicyService(  283): registerClient() client 0xb39d4c40, uid 10317
D/BluetoothManagerService(  850): Message: 20
D/BluetoothManagerService(  850): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20fbd381:true
D/BluetoothAdapter( 3763): 192013513: getState() :  mService = null. Returning STATE_OFF
I/InsertAccount( 3823): The account already exists
,I/ActivityManager(  850): Start proc com.lge.hiddenmenu for broadcast com.lge.hiddenmenu/.kddi_only.sms_setting.AssistReceiver: pid=3854 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,W/art     ( 3763): Attempt to remove local handle scope entry from IRT, ignoring
I/InsertAccount( 3823): The account info in contact DB already exists
W/AwContents( 3763): onDetachedFromWindow called when already detached. Ignoring
,W/ResourcesManager( 3854): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 3854): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/MusicBrowser( 2708): [MediaPlaybackService.java:2010:handleMessage()] oooooo mGroupIndexHandler msg.what : 0
,I/MusicBrowser( 2708): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2708): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2708): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2708): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
I/MusicBrowser( 2708): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
D/SystemWebViewEngine( 3763): CordovaWebView is running on device made by: LGE
,W/art     ( 3763): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3763): Attempt to remove local handle scope entry from IRT, ignoring
I/[SMS_AD]( 3854): Intent action: android.intent.action.BOOT_COMPLETED
I/InsertAccount( 3823): The account info in calendar DB already exists
,I/[SMS_AD]( 3854): Intent action: android.intent.action.BOOT_COMPLETED
I/Process ( 3823): Sending signal. PID: 3823 SIG: 9
I/ActivityManager(  850): Killing 3477:com.android.providers.calendar/u0a14 (adj 15): empty #11
D/WeatherAncestor( 2690): 2 : onReceive, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 16:33:41
,I/ActivityManager(  850): Process com.lge.defaultaccount (pid 3823) has died
W/libprocessgroup(  850): failed to open /acct/uid_10014/pid_3477/cgroup.procs: No such file or directory
D/UpdateThreadPoolManager( 2690): 2 : This is isUpdating : false
,I/Activity( 3763): Activity.onPostResume() called 
D/OpenGLRenderer( 3763): Render dirty regions requested: true
I/OpenGLRenderer( 3763): Initialized EGL, version 1.4
D/Weather_cast( 2690): 2 : set auto-update time : 1/4 19:33
,D/WeatherAncestor( 2690): 2 : onReceive has processed, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 16:33:41
D/WeatherService( 2690): 2 : onStartCommand, intent!=null, action: android.intent.action.BOOT_COMPLETED
D/OpenGLRenderer( 3763): Enabling debug mode 0
D/Atlas   ( 3763): Validating map...
,D/SplitWindow(  850): check instance of lgWin Window{1bdf9ef1 u0 com.example.hello/com.example.hello.MainActivity}
I/ActivityManager(  850): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.LockSettingsReceiver: pid=3879 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  850): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2690): 2 : Utils getTopActivity com.lge.launcher2 / true
W/chromium( 3763): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/WeatherService( 2690): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2690): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/InputDispatcher(  850): Focus entered window: Window{1bdf9ef1 u0 com.example.hello/com.example.hello.MainActivity}
,W/InputMethodManagerService(  850): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
I/ActivityManager(  850): Displayed com.example.hello/.MainActivity: +1s87ms
I/Timeline(  850): Timeline: Activity_windows_visible id: ActivityRecord{1c08395 u0 com.example.hello/.MainActivity t220} time:50974
I/ActivityManager(  850): Waited long enough for: ServiceRecord{3dab26fd u0 com.lge.sizechangable.musicwidget.widget/.service.MusicWidgetUpdater}
,I/Timeline( 3763): Timeline: Activity_idle id: android.os.BinderProxy@2fafb332 time:50992
I/LockScreenSettings( 3879): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/LockScreenSettings( 3879): Received Broadcast : android.intent.action.BOOT_COMPLETED
,W/BindingManager( 3763): Cannot call determinedVisibility() - never saw a connection for the pid: 3763
,I/ActivityManager(  850): Start proc com.lge.springcleaning for broadcast com.lge.springcleaning/.receiver.BootCompleteReceiver: pid=3901 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  850): Killing 3624:com.android.settings/1000 (adj 15): empty #11
,I/chromium( 3763): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/art     (  312): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 301us total 25.903ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 314us total 23.108ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 22.096ms
,W/libprocessgroup(  850): failed to open /acct/uid_1000/pid_3624/cgroup.procs: No such file or directory
,D/JsMessageQueue( 3763): Set native->JS mode to OnlineEventsBridgeMode
,D/BootCompleteReceiver( 3901): hasclipTray = true
W/ContextImpl( 3901): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.springcleaning.receiver.BootCompleteReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2663 
,E/AndroidProtocolHandler( 3763): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/ActivityManager(  850): Start proc com.lge.springcleaning:AppCleanupService for service com.lge.springcleaning/.service.AppCleanupService: pid=3919 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  850): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3937 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  850): Killing 3657:com.android.managedprovisioning/u0a111 (adj 15): empty #11
,W/libprocessgroup(  850): failed to open /acct/uid_10111/pid_3657/cgroup.procs: No such file or directory
,V/AppCleanupService( 3919): registerAlarm
,D/AppCleanupService( 3919): noticeInterval = 2678400000
D/AppCleanupService( 3919): notiDateStr = 2016-01-20 22:41:42
D/AppCleanupService( 3919): noticeStart = 2016-01-20 22:41:42
,D/AppCleanupService( 3919): noticeStart = 1453326102000
D/AppUsageDbAdapter( 3919): initPreloadedAppToTheDB() : row count = 167
,E/UpdateRequestReceiver( 3937): ignoring update request
,E/UpdateRequestReceiver( 3937): ignoring update request
E/UpdateRequestReceiver( 3937): ignoring update request
,E/UpdateRequestReceiver( 3937): ignoring update request
E/UpdateRequestReceiver( 3937): ignoring update request
,E/UpdateRequestReceiver( 3937): ignoring update request
I/ActivityManager(  850): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=3970 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  850): Killing 3685:com.lge.voicerecorder/u0a34 (adj 15): empty #11
,W/libprocessgroup(  850): failed to open /acct/uid_10034/pid_3685/cgroup.procs: No such file or directory
,D/jxcore_app_log( 3763): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1618835968
,D/JX-Cordova( 3763): jxcore cordova android initializing
D/SIMObserver( 3970): action:android.intent.action.BOOT_COMPLETED
D/SIMObserver( 3970): handle ACTION_BOOT_COMPLETED
,I/ActivityManager(  850): Killing 3708:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/jxcore-log( 3763): Initializing JXcore engine
W/jxcore-log( 3763): JXcore engine is ready
,W/jxcore-log( 3763): Starting JXcore engine
W/m.example.hello( 3763): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5828]" dev="sockfs" ino=5828 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3763): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 3763): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6420]" dev="sockfs" ino=6420 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/m.example.hello( 3763): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 3763): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 3763): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[18880]" dev="sockfs" ino=18880 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/libprocessgroup(  850): failed to open /acct/uid_10051/pid_3708/cgroup.procs: No such file or directory
,E/QcrilMsgTunnelAutoboot( 2311): Received Intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot (has extras) } canStartService = false
,D/PhoneInterfaceManager( 1765): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
D/PhoneInterfaceManager( 1765): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
I/ActivityManager(  850): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3993 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/ActivityManager(  850): enqueue in BackgroundQueue #60 Intent=Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 (has extras) }
V/AlarmManager(  850): ELAPSED_WAKEUP set : Alarm{124f37ba type 2 when 52044 com.android.providers.calendar} when 52044
,W/ResourcesManager( 3993): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/jxcore-log( 3763): Platform android
W/jxcore-log( 3763): 
W/jxcore-log( 3763): Process ARCH arm
W/jxcore-log( 3763): 
I/jxcore-log( 3763): JXcore Cordova bridge is ready!
I/jxcore-log( 3763): 
W/jxcore-log( 3763): JXcore engine is started
,I/ActivityManager(  850): Waited long enough for: ServiceRecord{346103b9 u0 com.lge.sizechangable.weather/.service.WeatherService}
,E/jxcore-log( 3763): >> LGE-LG-D722
E/jxcore-log( 3763): 
I/jxcore-log( 3763): Total memory 906309632
I/jxcore-log( 3763): 
,I/jxcore-log( 3763): Free memory 28065792
I/jxcore-log( 3763): 
I/jxcore-log( 3763): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3763): 
I/jxcore-log( 3763): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3763): 
I/jxcore-log( 3763): userPath [ 'www' ]
I/jxcore-log( 3763): 
I/jxcore-log( 3763): Size 720 1196
I/jxcore-log( 3763): 
I/jxcore-log( 3763): Screen Brightness 255
I/jxcore-log( 3763): 
E/jxcore-log( 3763): Dummy Error Log.
E/jxcore-log( 3763): 
,I/Babel_SMS( 3993): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 3993): MmsConfig.loadMmsSettings
I/Babel_SMS( 3993): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 3993): MmsConfig.loadFromDatabase
,E/Babel_SMS( 3993): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 3993): MmsConfig.loadFromResources
E/Babel_SMS( 3993): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 3993): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 3993): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 3993): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 3993): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 3993): found sensor: LGE Proximity Sensor, handle=48
,D/SensorManager( 3993): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 3993): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 3993): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 3993): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 3993): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 3993): found sensor: LGE Significant Motion Detector Sensor, handle=47
,D/SensorManager( 3993): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 3993): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 3993): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 3993): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 3993): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 3993): found sensor: Motion Accel, handle=46
,I/art     ( 3993): CheckpointMarkThreadRoots callback created = 0xb042d890
,W/Settings( 3993): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 3993): startup - clean
I/art     ( 3993): CheckpointMarkThreadRoots callback created = 0xb042d870
I/Babel   ( 3993): deleted: false for 0
,W/AudioCapabilities( 3993): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 3993): Unsupported mime audio/adpcm
W/AudioCapabilities( 3993): Unsupported mime audio/g726
W/AudioCapabilities( 3993): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 3993): Unsupported mime audio/wma-voice
W/VideoCapabilities( 3993): Unsupported mime video/mjpg
I/jxcore-log( 3763): getBuffer is called!!!!
I/jxcore-log( 3763): 
W/VideoCapabilities( 3993): Unsupported mime video/theora
,W/AudioCapabilities( 3993): Unsupported mime audio/evrc
W/AudioCapabilities( 3993): Unsupported mime audio/qcelp
W/VideoCapabilities( 3993): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 3993): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 3993): Unsupported mime audio/qcelp
W/AudioCapabilities( 3993): Unsupported mime audio/evrc
,W/VideoCapabilities( 3993): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 3993): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 3993): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3993): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3993): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3993): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 3993): onServiceConnected
W/Babel   ( 3993): Attempted to change video mute state without an active call.
,I/NotificationManager( 3993): com.google.android.talk: cancel(10436) by com.google.android.talk
I/art     (  850): Explicit concurrent mark sweep GC freed 20106(954KB) AllocSpace objects, 3(237KB) LOS objects, 33% free, 22MB/34MB, paused 2.767ms total 165.232ms
,I/ActivityManager(  850): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4037 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  850): Killing 3731:com.lge.cloudhub/u0a49 (adj 15): empty #11
D/sensors_hal_Time(  850): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  850): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  850): tsOffsetIs: Apps: 53047325036; DSPS: 1836719; Offset : -3016660904
,W/libprocessgroup(  850): failed to open /acct/uid_10049/pid_3731/cgroup.procs: No such file or directory
,W/ResourcesManager( 4037): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4037): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4037): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 4037): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4037): Installed default security provider GmsCore_OpenSSL
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/art     ( 4037): CheckpointMarkThreadRoots callback created = 0xb042db30
,I/art     ( 4037): CheckpointMarkThreadRoots callback created = 0xb4958de0
,W/ResourcesManager( 4037): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4037): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/YouTube MDX( 4037): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc-netbsd( 4037): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4037): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4037): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
I/dex2oat ( 4080): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads940975377.jar --oat-fd=31 --oat-location=/data/data/com.google.android.youtube/cache/ads940975377.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 4080): dex2oat took 104.062ms (threads: 4)
,I/NotificationManager( 4037): com.google.android.youtube: cancel(2) by com.google.android.youtube
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4037): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4037): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4037): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/InstanceID/Rpc( 4037): Found 10006
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4037): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,I/ActivityManager(  850): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4128 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/NotificationManager( 4037): com.google.android.youtube: cancel(10436) by com.google.android.youtube
,I/ActivityManager(  850): Killing 3780:com.lge.gnss.airtest/u0a54 (adj 15): empty #11
,W/libprocessgroup(  850): failed to open /acct/uid_10054/pid_3780/cgroup.procs: No such file or directory
W/ActivityManager(  850): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4128): getAccountsCursor
,W/GAV2    ( 4128): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  850): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  850): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
E/Gmail   ( 4128): Error finding the version of the Email provider.....
E/Gmail   ( 4128): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4128): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4128): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4128): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4128): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4128): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4128): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 4128): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4128): We do not support migrating this version of the Email provider.
,I/Gmail   ( 4128): getAccountsCursor
V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  850): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4128): Observing account changes for notifications
V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  850): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  850): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/ActivityThread( 4128): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@2ea1552e that was originally bound here
E/ActivityThread( 4128): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@2ea1552e that was originally bound here
E/ActivityThread( 4128): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 4128): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 4128): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 4128): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 4128): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4128): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4128): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4128): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4128): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4128): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4128): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4128): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4128): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4128): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4128): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4128): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager(  850): Unbind failed: could not find connection for android.os.BinderProxy@34f0d3cd
I/SearchBackgroundTaskFac( 1949): refreshing internal icing corpora
,I/ActivityManager(  850): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4190 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/SearchBackgroundTaskFac( 1949): Checking for language pack updates
,I/VelvetNetworkClient( 1949): Network connection not availble
,I/Gmail   ( 4128): notifyAccountChanged
I/Gmail   ( 4128): getAccountsCursor
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4128): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ActivityManager(  850): Killing 3798:com.lge.lgfota.permission/1000 (adj 15): empty #11
I/Gmail   ( 4128): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4128): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 4128): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/libprocessgroup(  850): failed to open /acct/uid_1000/pid_3798/cgroup.procs: No such file or directory
,V/[BNRBootReceiver]( 4190): boot receiver action = android.intent.action.BOOT_COMPLETED
,V/[BNRBootReceiver]( 4190): set property sys.lge.bnrd = 1
V/[BNRBootReceiver]( 4190): End of BootComplted IF
V/[BNRBootReceiver]( 4190): Boot Receiver Return
,V/[BNRBootCompletedThread]( 4190): run
W/linker  ( 4209): /system/bin/bnrd has text relocations. This is wasting memory and prevents security hardening. Please fix.
W/bnrd    ( 4209): BNRD > wait starting [4209-3058102400] <
V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/bnrd    ( 4209): /data/data/.bnr_fifo_req
V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/[BNRBootCompletedThread]( 4190): End of BNRProcess
,V/[BNRBootCompletedThread]( 4190): End of BNRViaWifiProcess
V/[BNRBootCompletedThread]( 4190): End of SpriteProcess
V/[BNRBootCompletedThread]( 4190): exit
I/ActivityManager(  850): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4216 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  850): Killing 3854:com.lge.hiddenmenu/1000 (adj 15): empty #11
W/libprocessgroup(  850): failed to open /acct/uid_1000/pid_3854/cgroup.procs: No such file or directory
,I/GservicesUpdateTask( 1949): Updating Gservices keys
,I/VelvetNetworkClient( 1949): Network connection not availble
,I/UpdateIcingCorporaServi( 1949): Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
I/VelvetNetworkClient( 1949): Network connection not availble
,I/NotificationManager( 1949): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/Gmail   ( 4128): getAccountsCursor
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 2278): Storage manager: low false usage 1.41MB avail 2.41GB capacity 4.06GB
I/art     ( 1747): Explicit concurrent mark sweep GC freed 20082(1411KB) AllocSpace objects, 18(288KB) LOS objects, 40% free, 12MB/21MB, paused 7.983ms total 148.654ms
,W/ResourcesManager( 1949): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
,E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  850): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  850): DNSproblemNotiEnabled is disabled ignore DNS fail CB
E/Auth    ( 1747): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
E/Auth    ( 1747): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 1949): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1949): java.io.IOException: NetworkError
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1949): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,I/art     ( 2067): Explicit concurrent mark sweep GC freed 3874(167KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.159ms total 41.699ms
,D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Auth    ( 1747): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1949): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1949): java.io.IOException: NetworkError
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1949): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/Search.LoginHelper( 1949): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1949): java.io.IOException: NetworkError
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecuto,r$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1949): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
I/WebViewFactory( 1949): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/Finsky  ( 4216): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Auth    ( 1747): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
E/Auth    ( 1747): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1949): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1949): java.io.IOException: NetworkError
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1949): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/Search.LoginHelper( 1949): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1949): java.io.IOException: NetworkError
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPool,Executor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1949): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Auth    ( 1747): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Auth    ( 1747): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1949): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1949): java.io.IOException: NetworkError
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1949): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/Search.LoginHelper( 1949): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1949): java.io.IOException: NetworkError
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1949): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Auth    ( 1747): [GoogleAccountDataServiceImpl] getToken() failed. Status NETWORK_ERROR, Account: <ELLIDED:1197869880>, App: com.google.android.googlequicksearchbox, Service: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1949): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1949): java.io.IOException: NetworkError
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1949): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1949): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1949): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
I/LibraryLoader( 1949): Time to load native libraries: 2 ms (timestamps 6079-6081)
,I/LibraryLoader( 1949): Expected native library version number "",actual native library version number ""
W/art     ( 1949): Attempt to remove local handle scope entry from IRT, ignoring
,W/ResourcesManager( 1949): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Finsky  ( 4216): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/art     ( 1949): Attempt to remove local handle scope entry from IRT, ignoring
V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  850): android: cancelAsUser(2) by android
,W/Settings( 4216): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 4216): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 4216): com.android.vending: cancel(-1050172287) by com.android.vending
,D/libc-netbsd( 4216): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4216): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4216): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4216): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  279): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  850): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/Volley  ( 4216): [438] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 4216): [431] DiskBasedCache.clear: Cache cleared.
,I/Icing   ( 2278): updateResources: need to parse f{com.google.android.gms}
,I/art     (  850): Explicit concurrent mark sweep GC freed 23146(1096KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 11.638ms total 168.160ms
,V/DownloadManager( 3154): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3154): created cursor android.database.sqlite.SQLiteCursor@3edd7156 on behalf of 4216
,D/Ads     ( 4216): Skipping gmscore version check
D/Finsky  ( 4216): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4216): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 4216): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4216): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 2278): Internal init done: storage state 0
,I/Icing   ( 2278): Post-init done
,I/Icing   ( 2278): Query from com.google.android.googlequicksearchbox package restrict com.google.android.googlequicksearchbox start 0 num 1000
,E/Icing   ( 2278): No scoring data for corpus [22]
,I/Icing   ( 2278): Query from com.google.android.googlequicksearchbox package restrict com.google.android.googlequicksearchbox start 0 num 1000
,I/ApplicationLogger( 1949): logBytes() : Old Hash = -213850704 : New Hash = 441496333
,I/ApplicationLogger( 1949): logEvent(): Logged 1772 bytes in 1707 ms
,D/FileApkUtils( 2278): Spent 59ms computing apk sha1.
,D/FileApkUtils( 2278): Module already staged or being staged:chimera-modules/MapsModule.apk
I/art     ( 2278): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-ca8b2a9144773fc3650c54ed299f2d4558171b12@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
W/InstanceID/Rpc( 2278): Found 10006
D/DexOptUtils( 2278): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 2278): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
D/GmsModuleFndr( 2278): Beginning GMS chimera module scan
,D/GmsModuleFndr( 2278): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/ChimeraCfgMgr( 2278): Beginning module configuration check
,D/ChimeraCfgMgr( 2278): Module APKs unchanged, check complete
I/NotificationManager( 2278): com.google.android.gms: cancel(10436) by com.google.android.gms
D/ChimeraCfgMgr( 2278): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/BootCompletedReceiver( 2278): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BluetoothManagerService(  850): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  850): disable(): mBluetooth = null mBinding = false
D/BluetoothManagerService(  850): Message: 2
D/BootCompletedReceiver( 2278): Got an BootCompleted event.
D/BootCompletedReceiver( 2278): Will NOT schedule AdAttestation signal task because it's disabled.
,D/WifiServiceImplEx(  850): setWifiEnabled: false pid=3763, uid=10317, package= com.example.hello, App Lable : HelloWorld
D/WifiService(  850): setWifiEnabled: false pid=3763, uid=10317
,I/jxcore-log( 3763): ****TEST TOOK:  5070  ms ****
I/jxcore-log( 3763): 
I/jxcore-log( 3763): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3763): 
D/GCM     ( 2278): COMPAT: Multi user not supported
,D/GCM     ( 1747): COMPAT: Multi user not supported
,I/GCoreUlr( 2278): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/CheckinService( 2278): Checkin interval check for package: unspecified last checkin: 1450837195376 min interval config: 0 actual interval: 1084433002
I/CheckinService( 2278): Disabling old GoogleServicesFramework version
,D/SystemUpdateService( 2278): onCreate
,D/SystemUpdateService( 2278): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,V/AuthZen ( 2278): Handling intent: android.intent.action.BOOT_COMPLETED
,I/SystemUpdateService( 2278): cancelUpdate (empty URL)
,I/SystemUpdateService( 2278): active receiver: disabled
D/KeyguardUpdateMonitor( 1399): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1399): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1399): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1399): On Skip Timer : true
D/PowerService( 1818): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,I/NotificationManager( 2278): com.google.android.gms: cancel(2130838165) by com.google.android.gms
,I/NotificationManager( 2278): com.google.android.gms: cancel(2130838166) by com.google.android.gms
,D/SystemUpdateService( 2278): onDestroy
D/AuthZenEventHandler( 2278): Handling event: android.intent.action.BOOT_COMPLETED
,I/art     ( 2067): Explicit concurrent mark sweep GC freed 2941(115KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 744us total 30.739ms
I/CheckinService( 2278): Checking schedule, now: 1451921628624 next: 1451364444338
,I/CheckinService( 2278): active receiver: enabled
W/BaseAppContext( 2278): Using Auth Proxy for data requests.
E/BaseAppContext( 2278): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,D/AndroidRuntime( 4344): 
D/AndroidRuntime( 4344): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4344): CheckJNI is OFF
I/AuthZen ( 2278): Fetching signing key...
,I/AuthZen ( 2278): Signing key fetched successfully!
,W/BaseAppContext( 2278): Using Auth Proxy for data requests.
D/a       ( 2278): Opening database auth.proximity.permit_store...
,D/AuthZenTransactionCache( 2278): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 2278): Clearing transaction cache
I/art     ( 1747): Explicit concurrent mark sweep GC freed 20221(1497KB) AllocSpace objects, 24(384KB) LOS objects, 40% free, 13MB/21MB, paused 2.262ms total 121.426ms
,D/GCM     ( 1747): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1747): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1747): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  279): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  279): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  279): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  279): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  279): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  850): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/GCoreUlr( 1747): DispatchingService.onCreate()
,I/GCoreUlr( 1747): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,W/GCoreFlp( 1747): No location to return for getLastLocation()
W/FusedLocationProvider( 1747): location=null
,W/GCoreFlp( 1747): No location to return for getLastLocation()
W/FusedLocationProvider( 1747): location=null
,W/Auth    ( 1747): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,V/GLSActivity( 1747): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PersistentNotificationBroadcastReceiver( 1747): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/UpdateIcingCorporaServi( 1949): UpdateCorporaTask done [took 2770 ms] updated apps [took 2625 ms] updated contacts [took 145 ms]
,I/GCoreUlr( 1747): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
D/AndroidRuntime( 4344): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  850): Start proc com.lge.qmemoplus for broadcast com.lge.qmemoplus/.ui.editor.reminder.ReminderMaker: pid=4390 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  850): Force stopping com.example.hello appid=10317 user=-1: uninstall pkg
,I/ActivityManager(  850): Killing 3763:com.example.hello/u0a317 (adj 0): stop com.example.hello
I/WindowState(  850): WIN DEATH: Window{1bdf9ef1 u0 com.example.hello/com.example.hello.MainActivity}
,D/InputDispatcher(  850): Focus left window: Window{1bdf9ef1 u0 com.example.hello/com.example.hello.MainActivity}
D/InputDispatcher(  850): Window went away: Window{1bdf9ef1 u0 com.example.hello/com.example.hello.MainActivity}
W/PackageSettings(  850): Skipping PackageSetting{298b4598 com.test.thalitest/10316} due to missing metadata
,W/ActivityManager(  850): Force removing ActivityRecord{1c08395 u0 com.example.hello/.MainActivity t220}: app died, no saved state
,W/ActivityManager(  850): Spurious death for ProcessRecord{cfee333 3763:com.example.hello/u0a317}, curProc for 3763: null
,I/ActivityManager(  850): Force stopping com.example.hello appid=10317 user=0: pkg removed
I/GCoreUlr( 1747): Unbound from all location providers
I/GCoreUlr( 1747): Place inference reporting - stopped
,W/ResourcesManager( 4390): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/ActivityManager(  850): Waited long enough for: ServiceRecord{d32674b u0 com.android.mms/.service.SwitchedService}
D/KeyguardModel( 1399): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1893): [Launcher.java:5203:onStart()]onStart
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/QCNEJ   ( 1854): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[LGHome]EVENT( 1893): [Launcher.java:776:onResume()]onResume
,W/GeofencerStateMachine( 1747): Ignoring removeGeofence because network location is disabled.
,W/System.err( 3430): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
D/KeyguardModel( 1399): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1399): createShortcutInfo...
W/System.err( 3430): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3430): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3430): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3430): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3430): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3430): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3430): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3430): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3430): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3430): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3430): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/[SystemUI]QSlideListController( 1399): onReceive = android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1399): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1399): createShortcutInfo...
W/ResourceType( 1399): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1399): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[LGHome]LGActivityUtil( 1893): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1893): [Launcher.java:929:onResume()]onResume end
I/Activity( 1893): Activity.onPostResume() called 
D/KeyguardModel( 1399): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1399): createShortcutInfo...
W/ResourceType( 1399): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1399): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/KeyguardModel( 1399): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1399): createShortcutInfo...
W/ResourceType( 1399): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1399): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/GCoreUlr( 1747): DispatchingService.onDestroy()
I/GCoreUlr( 1747): Stopping handler for UlrDispSvcFast
,W/[LGHome]LGWallpaperInfo( 1893): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1893): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/KeyguardModel( 1399): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1399): createShortcutInfo...
I/InputReader(  850): Reconfiguring input devices.  changes=0x00000010
I/GCoreUlr( 1747): Unbound from all location providers
I/GCoreUlr( 1747): Place inference reporting - stopped
I/SystemUI[Framework](  850): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  850): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  850): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  850): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  850): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@620a9c2,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  850): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,D/InputDispatcher(  850): Focus entered window: Window{c70fa8b u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1399): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1399): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1399): handleShortcutListChanged...
,I/art     ( 1801): CheckpointMarkThreadRoots callback created = 0xaaf21b40
D/administrator(  850): Handling package changes for user 0
I/[LGHome]EVENT( 1893): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1893): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1893): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/KeyguardModel( 1399): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1399): createShortcutInfo...
D/KeyguardModel( 1399): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1399): createShortcutInfo...
W/ResourceType( 1399): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1399): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1399): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1399): createShortcutInfo...
,W/ResourceType( 1399): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1399): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1399): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1399): createShortcutInfo...
W/ResourceType( 1399): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1399): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1399): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1399): createShortcutInfo...
D/KeyguardModel( 1399): handleShortcutListChanged...
,I/[LGHome]EVENT( 1893): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1893): [setNavigationBarColor] color=0x 0
I/art     ( 1801): CheckpointMarkThreadRoots callback created = 0xb042d8f0
,E/App     ( 4390): [App][onCreate()] 4.40.23
,I/NotificationService(  850): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,D/BackupManagerService(  850): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  850): Receieved: android.intent.action.PACKAGE_REMOVED
W/InputMethodManagerService(  850): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/InputMethodManagerService(  850): Got RemoteException sending setActive(false) notification to pid 3763 uid 10317
D/TaskPersister(  850): removeObsoleteFile: deleting file=220_task.xml
D/PhoneStatusBar( 1399): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
I/HotwordRecognitionRnr( 1949): Starting hotword detection.
I/Timeline( 1893): Timeline: Activity_idle id: android.os.BinderProxy@1c8ff0fd time:58892
,I/SystemUI[Framework](  850): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
,W/PhoneWindowManagerEx(  850): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  850): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  850): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  850): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@620a9c2,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  850): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1399): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1399): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1399):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1399): , Keyguard show=false, IME shown=false, Panel expanded=false
I/MicrophoneInputStream( 1949): mic_starting com.google.android.apps.gsa.speech.audio.u@c381065
V/AudioRecord( 1949): set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
,V/AudioRecord( 1949): set(): mSessionId 22
V/AudioPolicyManager(  283): getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 22, flags 0
V/AudioPolicyManager(  283): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  283): isPlaybackThread 0,isRecordThread 1
D/audio_hw_primary(  283): adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb3806340)
V/audio_hw_primary(  283): adev_open_input_stream: exit
V/AudioFlinger(  283): openInput_l() openInputStream returned input 0xb3806340, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
V/AudioFlinger(  283): openInput_l() created record thread: ID 23 thread 0xb3a11000
V/AudioSystem(  283): ioConfigChanged() event 3, ioHandle 23
D/BarTransitions( 1399): draw background and invalidate : color = f2000000
V/AudioPolicyService(  283): AudioCommandThread() adding update audio port list
V/AudioSystem( 1765): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 2708): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem(  850): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 1399): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 3123): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 1949): ioConfigChanged() event 3, ioHandle 23
D/BarTransitions( 1399): draw background and invalidate : color = f3e9e9e9
V/AudioPolicyService(  283): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioFlinger(  283): openRecord() lSessionId: 22 input 23
V/AudioFlinger(  283): getOrphanEffectChain_l session 22 index -2
I/AudioFlinger(  283): AudioFlinger's thread 0xb3a11000 ready to run
D/audio_hw_primary(  283): in_standby: enter: stream (0xb3806340) usecase(7: audio-record)
V/audio_hw_primary(  283): in_standby: exit:  status(0)
V/AudioFlinger(  283): acquiring 22 from 1949, for -1
V/AudioFlinger(  283):  added new entry for 22
D/audio_hw_primary(  283): in_standby: enter: stream (0xb3806340) usecase(7: audio-record)
V/audio_hw_primary(  283): in_standby: exit:  status(0)
V/AudioFlinger(  283): RecordThread: loop stopping
V/AudioRecord( 1949): start, sync event 0 trigger session 0
V/AudioRecord( 1949): mAudioRecord->start()
V/AudioFlinger(  283): RecordHandle::start()
V/AudioFlinger(  283): RecordThread::start event 0, triggerSession 0
V/AudioPolicyManager(  283): startInput() module primary->input primary(23)
V/AudioPolicyManager(  283): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  283): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  283): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  283): DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
V/AudioPolicyService(  283): AudioCommandThread() adding create patch delay 0
V/AudioPolicyService(  283): inserting command: 7 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing create audio patch
,V/AudioFlinger::PatchPanel(  283): createAudioPatch() num_sources 1 num_sinks 1 handle 0
,V/AudioFlinger::PatchPanel(  283): createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
V/AudioFlinger(  283): ThreadBase::setParameters() input_source=6;routing=-2147483644
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  283): RecordThread: loop starting
,V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  283): in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
V/audio_hw_primary(  283): in_set_parameters: exit: status(0)
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb3a11000
V/AudioFlinger::PatchPanel(  283): createAudioPatch() status 0,
V/AudioFlinger::PatchPanel(  283): createAudioPatch() added new patch handle 24 halHandle 0
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioPolicyManager(  283): setInputDevice() createAudioPatch returned 0 patchHandle 24
,V/AudioPolicyManager(  283): addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
,V/AudioPolicyService(  283): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  283): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
,V/AudioPolicyService(  283): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioPolicyService(  283): AudioCommandThread() adding set parameter string hotword_active=1, io 23 ,delay 0
,V/AudioPolicyService(  283): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  283): AudioCommandThread() waking up
V/AudioPolicyService(  283): AudioCommandThread() processing set parameters string hotword_active=1, io 23
V/AudioFlinger(  283): setParameters(): io 23, keyvalue hotword_active=1, calling pid 283
V/AudioFlinger(  283): ThreadBase::setParameters() hotword_active=1
V/AudioFlinger(  283): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  283): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  283): in_set_parameters: enter: kvpairs=hotword_active=1
V/audio_hw_primary(  283): in_set_parameters: exit: status(0)
V/AudioFlinger(  283): processConfigEvents_l() DONE thread 0xb3a11000
V/AudioPolicyService(  283): AudioCommandThread() going to sleep
V/AudioPolicyManager(  283): AudioPolicyManager::startInput() input source = 1999
I/MicrophoneInputStream( 1949): mic_started com.google.android.apps.gsa.speech.audio.u@c381065
,V/msm8974_platform(  283): platform_update_usecase_from_source: input source :6
D/audio_hw_primary(  283): start_input_stream: enter: stream(0xb3806340)usecase(7: audio-record)
V/voice   (  283): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  283): start_input_stream: usecase(7)
E/audio_hw_primary(  283): select_devices: enter and usecase(7)
V/msm8974_platform(  283): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  283): platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
V/msm8974_platform_lge(  283): LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
V/audio_hw_lge_primary(  283): LGE_exeption_scenario: enter and out: 0, in: 144
D/audio_hw_primary(  283): select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
E/audio_hw_primary(  283): enable_snd_device: enter  144
D/hardware_info(  283): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  283): enable_snd_device: snd_device(144: lg-vr-handset-mic)
V/msm8974_platform_lge(  283): LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
D/ACDB-LOADER(  283): ACDB -> send_audio_cal, acdb_id = 65, path =  1
D/ACDB-LOADER(  283): ACDB -> send_adm_topology
D/ACDB-LOADER(  283): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  283): ACDB -> send_asm_topology
D/ACDB-LOADER(  283): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  283): ACDB -> send_audtable
D/ACDB-LOADER(  283): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  283): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  283): ACDB -> send_audvoltable
D/ACDB-LOADER(  283): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  283): Failed to fetch the lookup information of the device 00000041 
E/ACDB-LOADER(  283): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  283): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  283): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  283): enable_audio_route: enter: usecase(7)
,V/msm8974_platform_lge(  283): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  283): enable_audio_route: apply mixer and update path: audio-record
V/audio_hw_primary(  283): enable_audio_route: exit
D/audio_hw_primary(  283): select_devices: done
V/audio_hw_primary(  283): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
I/art     (  850): Explicit concurrent mark sweep GC freed 24600(1528KB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/34MB, paused 7.757ms total 445.742ms
V/audio_hw_primary(  283): start_input_stream: exit
D/AndroidRuntime( 4344): Shutting down VM
,I/HotwordWorker( 1949): onReady
,D/AccountManager( 4390): setSyncFrequency
I/Icing   ( 2278): Indexing 0A5267A505F47CB39AEB664724AACA2991DAA8A8 from com.google.android.googlequicksearchbox
,D/LCardEmulationManager( 1801): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1801): getDefaultRoute
,W/ResourcesManager(  850): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Icing   ( 2278): Loaded CLD2 Version V2.0 - 20141016
W/ContextImpl( 4390): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.qmemoplus.ui.editor.reminder.ReminderMaker.onReceive:14 android.app.ActivityThread.handleReceiver:2663 
I/Timeline(  850): Timeline: Activity_windows_visible id: ActivityRecord{1c1748d9 u0 com.lge.launcher2/.Launcher t219} time:59158
,D/ReminderService( 4390): [onHandleIntent] action : com.lge.qmemoplus.action.SET_REMINDERS
D/LocationReminderManager( 4390): [connect] Request location client connection.
W/ContextImpl( 4390): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.google.android.gms.internal.he.a:-1 com.google.android.gms.internal.hc.connect:-1 com.google.android.gms.location.LocationClient.connect:-1 
,I/ActivityManager(  850): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=4417 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
W/ResourceType(  850): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1893): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/ActivityManager(  850): Killing 3901:com.lge.springcleaning/1000 (adj 15): empty #11
,D/LocationReminderManager( 4390): location cilent is connected.
,W/libprocessgroup(  850): failed to open /acct/uid_1000/pid_3901/cgroup.procs: No such file or directory
I/Icing   ( 2278): Indexing done 0A5267A505F47CB39AEB664724AACA2991DAA8A8
,W/ResourcesManager( 4417): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/LocationReminderManager( 4390): [removeAllReminders]
,W/GeofencerStateMachine( 1747): Ignoring removeGeofence because network location is disabled.
D/LocationReminderManager( 4390): [removeAllReminders] statusCode : 1000
,D/LocationReminderManager( 4390): [removeAllReminders] Failed to remove reminder
W/GCoreFlp( 1747): No location to return for getLastLocation()
W/GCoreFlp( 1747): No location to return for getLastLocation()
W/ActivityManager(  850): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found

```
