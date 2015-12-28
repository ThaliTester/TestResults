#### Test 503880191ec81a5_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
D/MediaScannerService( 3212): [MediaScanner] scan() Send Intent ACTION_MEDIA_SCANNER_FINISHED uri : file:///system/media
--------- beginning of system
W/libprocessgroup(  968): failed to open /acct/uid_10006/pid_2279/cgroup.procs: No such file or directory
I/MusicBrowser( 2702): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 }}
D/LGMediaProvider( 3212): [MediaScanner] mUnmountReceiver ACTION_MEDIA_SCANNER_FINISHED : uri = file:///system/media, path = /system/media
D/MediaScannerService( 3212): [MediaScanner] done scanning volume internal
I/MusicBrowser( 2702): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2702): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_FINISHED
D/MediaScannerService( 3212): [MediaScanner] start scanning volume external: [/storage/emulated/0, /storage/external_SD]
V/LGMediaProvider( 3212): insertInternal: content://media/none/media_scanner, initValues=volume=external
D/MediaScannerService( 3212): [MediaScanner] scan() ACTION_MEDIA_SCANNER_STARTED uri : file:///storage/emulated/0
V/LGMediaProvider( 3212): insertInternal: content://media/, initValues=name=external
I/MusicWidget( 2640): _mediaDataObserver onChange()
D/LGBootCompleteReceiver( 1766): onReceive : android.intent.action.BOOT_COMPLETED
D/ConfigUtils( 1766): setUsimOperator() : card operator = 
D/ConfigUtils( 1766): setUsimOperator() : result = null
D/MediaScannerEx( 3212): [MediaScanner] scanDirectories()[0] = /storage/emulated/0
D/MediaScannerEx( 3212): [MediaScanner] scanDirectories()[1] = /storage/external_SD
D/ConfigUtils( 1766): setUsimOperator() : simOperator = 
D/ConfigUtils( 1766): setUsimOperator() : usimoperator = 0
D/ConfigUtils( 1766): setSupportedUsimMobilityForVoLTE() : false
W/VRBookmarkProvider( 3899): [BookmarkProvider.java:546:onChange()-[Thread:Other] Data Change!! false url : content://media/
I/MusicWidget( 2640): beingMusicWidget_4x2() result::false
D/ConfigUtils( 1766): This Model Voice Clarity Support : false
D/LGBootCompleteReceiver( 1766): onReceive : updateCallrejectNotify rejectCallOption : 1
I/MusicBrowser( 2702): [MediaPlaybackService.java:reloadQueue()] oooooo 
D/MusicBrowser( 2702): [MediaPlaybackService.java:reloadQueue()] oooooo id=-1
D/MusicBrowser( 2702): [MediaPlaybackService.java:reloadQueue()] oooooo mCardId=-1
D/MusicBrowser( 2702): [MediaPlaybackService.java:reloadQueue()] oooooo mPreferences.id=-1
D/MusicBrowser( 2702): [MediaPlaybackService.java:reloadQueue()] oooooo q=
D/MusicBrowser( 2702): [MediaPlaybackService.java:reloadQueue()] oooooo q.length=0
D/CallRejectInfoToNotify( 1766): update : tPhoneMode : false
I/NotificationManager( 1766): com.android.phone: cancel(2131493582) by com.android.phone
I/PhoneApp( 1766): saveDefaultRingtoneUriOfOwner = content://media/internal/audio/media/55
D/MusicBrowser( 2702): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.queuechanged}
I/MusicBrowser( 2702): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2702): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2702): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2702): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2702): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2702): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2702): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2702): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2702): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
V/MediaScannerClient( 3212): [MediaScanner]setLocale: = en_US
I/ActivityManager(  968): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=3924 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/MusicBrowser( 2702): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2702): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2702): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
I/MusicWidget( 2640): intentReceiver onReceive() action::com.lge.music.queuechanged
D/MusicBrowser( 2702): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2702): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicWidget( 2640): beingMusicWidget_4x2() result::false
D/MusicBrowser( 2702): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.metachanged}
I/MusicWidget( 2640): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2702): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
I/MusicWidget( 2640): beingMusicWidget_4x1() result::true
D/MusicBrowser( 2702): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2702): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2702): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
I/MusicWidget( 2640): send mDelayedStopHandler
I/MusicWidget( 2640): performViewUpdater handleMessage() msg.what::3
D/MusicBrowser( 2702): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2702): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2702): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
I/MusicWidget( 2640): beingMusicWidget_Quick() result::false
D/MusicBrowser( 2702): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2702): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicBrowser( 2702): [MediaPlaybackService.java:3426:notifyChange()] oooooo mRemoteControlClient.editMetadata :: META_CHANGED 
I/MusicWidget( 2640): intentReceiver onReceive() action::com.lge.music.metachanged
I/MusicWidget( 2640): beingMusicWidget_4x2() result::false
I/MusicBrowser( 2702): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=false}
I/MusicBrowser( 2702): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/MusicWidget( 2640): beingMusicWidget_Quick() result::false
I/MusicWidget( 2640): beingMusicWidget_4x1() result::true
D/MusicBrowser( 2702): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2702): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicWidget( 2640): send mDelayedStopHandler
I/MusicBrowser( 2702): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicWidget( 2640): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2640): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2702): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2702): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
I/MusicBrowser( 2702): [MediaPlaybackService.java:9999:run()] oooooo AlbumImageUpdater() run :: Start
I/MusicBrowser( 2702): [MediaPlaybackService.java:10051:run()] oooooo AlbumImageUpdater() run :: End
I/MusicBrowser( 2702): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_STARTED dat=file:///storage/emulated/0 flg=0x10 }}
I/MusicBrowser( 2702): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2702): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_STARTED
I/MusicBrowser( 2702): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
W/MusicBrowser( 2702): - Start trace [MusicUtils.query]---------------------------------------------------------------
W/MusicBrowser( 2702): [Line 003751] MusicUtils.java, query() : MusicUtils.query
W/MusicBrowser( 2702): [Line 003761] MusicUtils.java, isMediaScannerScanning() : MusicUtils.query
W/MusicBrowser( 2702): [Line 001991] MediaPlaybackService.java, onChange() : MusicUtils.query
W/MusicBrowser( 2702): [Line 000130] ContentObserver.java, onChange() : MusicUtils.query
W/MusicBrowser( 2702): - End   trace [MusicUtils.query]---------------------------------------------------------------
D/MediaScannerEx( 3212): [MediaScanner] beginFile() path = /storage/emulated/0/QuicksetLite Setup/data
V/DrmBroadcastReceiver( 3924): Receive ACTION_BOOT_COMPLETED
V/MediaScannerClient( 3212): [MediaScanner]setLocale: = en_US
W/MediaScanner( 3212): Error opening directory '/storage/external_SD/', skipping: Permission denied.
D/LGMediaProvider( 3212): [MediaScanner] delete() uri = content://media/external/file
V/DrmService( 3924): Service onCreate
D/DrmService( 3924): Received new request = 4
W/VRBookmarkProvider( 3899): [BookmarkProvider.java:546:onChange()-[Thread:Other] Data Change!! false url : content://media/external
W/VRBookmarkProvider( 3899): [BookmarkProvider.java:563:onChange()-[Thread:Other] EXTERNAL Change!!
W/MusicBrowser( 2702): - Start trace [MusicUtils.query]---------------------------------------------------------------
W/MusicBrowser( 2702): [Line 003751] MusicUtils.java, query() : MusicUtils.query
W/MusicBrowser( 2702): [Line 003761] MusicUtils.java, isMediaScannerScanning() : MusicUtils.query
W/MusicBrowser( 2702): [Line 001991] MediaPlaybackService.java, onChange() : MusicUtils.query
W/MusicBrowser( 2702): [Line 000130] ContentObserver.java, onChange() : MusicUtils.query
W/MusicBrowser( 2702): - End   trace [MusicUtils.query]---------------------------------------------------------------
I/MusicWidget( 2640): _mediaDataObserver onChange()
I/MusicWidget( 2640): beingMusicWidget_4x2() result::false
I/art     ( 3212): Explicit concurrent mark sweep GC freed 15599(850KB) AllocSpace objects, 6(96KB) LOS objects, 24% free, 8MB/10MB, paused 604us total 60.508ms
D/LGMediaProvider( 3212): [MediaScanner] delete() completed notifyChange, uri = content://media/external
V/MediaScanner( 3212): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@37cd8941
V/MediaScanner( 3212): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@37cd8941
D/MediaScanner( 3212): [MediaScanner] prescan time: 48ms
D/MediaScanner( 3212): [MediaScanner] scan time: 118ms
D/MediaScanner( 3212): [MediaScanner] postscan time: 30ms
D/MediaScanner( 3212): [MediaScanner] total time: 196ms
D/LGMediaProvider( 3212): [MediaScanner] delete() uri = content://media/none/media_scanner
D/DrmServiceHandler( 3924): updateDrmPushNotification() : No notification
D/DrmService( 3924): Completed !! request = 4
D/DrmService( 3924): Request count = 0
D/MediaScannerService( 3212): [MediaScanner] scan() Send Intent ACTION_MEDIA_SCANNER_FINISHED uri : file:///storage/emulated/0
I/ActivityManager(  968): Start proc com.lge.cloudhub for broadcast com.lge.cloudhub/.service.CloudHubReceiver: pid=3946 uid=10049 gids={50049, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/MusicWidget( 2640): performViewUpdater handleMessage() msg.what::0
D/LGMediaProvider( 3212): [MediaScanner] mUnmountReceiver ACTION_MEDIA_SCANNER_FINISHED : uri = file:///storage/emulated/0, path = /storage/emulated/0
V/DrmService( 3924): Service onDestroy
I/MusicWidget( 2640): beingMusicWidget_4x1() result::true
I/MusicWidget( 2640): performUpdate()_4x1
D/MediaScannerService( 3212): [MediaScanner] done scanning volume external
I/MusicWidget( 2640): defaultAppWidget()_4x1
I/ActivityManager(  968): Killing 3692:com.google.android.partnersetup/u0a9 (adj 15): empty #11
I/MusicWidget( 2640): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2640): 4x1_currentTheme :: null
I/MusicWidget( 2640): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2640): setDefaultViewLayoutId()_4x1
I/MusicWidget( 2640): appWidgetViewUpdate()_4x1
I/MusicWidget( 2640): linkButtons()_4x1
W/libprocessgroup(  968): failed to open /acct/uid_10009/pid_3692/cgroup.procs: No such file or directory
I/MusicBrowser( 2702): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 }}
I/MusicBrowser( 2702): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2702): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_FINISHED
I/MusicBrowser( 2702): [MediaPlaybackService.java:reloadQueue()] oooooo 
D/MusicBrowser( 2702): [MediaPlaybackService.java:reloadQueue()] oooooo id=-1
D/MusicBrowser( 2702): [MediaPlaybackService.java:reloadQueue()] oooooo mCardId=-1
D/MusicBrowser( 2702): [MediaPlaybackService.java:reloadQueue()] oooooo mPreferences.id=-1
D/MusicBrowser( 2702): [MediaPlaybackService.java:reloadQueue()] oooooo q=
D/MusicBrowser( 2702): [MediaPlaybackService.java:reloadQueue()] oooooo q.length=0
D/MusicBrowser( 2702): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.queuechanged}
I/MusicBrowser( 2702): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2702): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2702): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2702): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2702): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2702): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2702): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2702): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2702): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicBrowser( 2702): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2702): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/MusicWidget( 2640): pushUpdate()_4x1
D/MusicBrowser( 2702): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2702): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2702): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicWidget( 2640): intentReceiver onReceive() action::com.lge.music.queuechanged
I/MusicWidget( 2640): beingMusicWidget_4x2() result::false
I/MusicWidget( 2640): beingMusicWidget_Quick() result::false
D/MusicBrowser( 2702): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.metachanged}
I/MusicBrowser( 2702): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2702): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2702): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2702): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2702): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2702): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2702): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
I/MusicWidget( 2640): beingMusicWidget_4x1() result::true
D/MusicBrowser( 2702): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
I/MusicWidget( 2640): send mDelayedStopHandler
I/MusicWidget( 2640): performViewUpdater handleMessage() msg.what::3
D/MusicBrowser( 2702): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicWidget( 2640): beingMusicWidget_Quick() result::false
I/MusicWidget( 2640): intentReceiver onReceive() action::com.lge.music.metachanged
I/MusicBrowser( 2702): [MediaPlaybackService.java:3426:notifyChange()] oooooo mRemoteControlClient.editMetadata :: META_CHANGED 
I/MusicBrowser( 2702): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=false}
I/MusicBrowser( 2702): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/ActivityManager(  968): Waited long enough for: ServiceRecord{34119f4e u0 com.lge.sizechangable.musicwidget.widget/.service.MusicWidgetUpdater}
I/MusicBrowser( 2702): [MediaPlaybackService.java:9999:run()] oooooo AlbumImageUpdater() run :: Start
I/MusicBrowser( 2702): [MediaPlaybackService.java:10051:run()] oooooo AlbumImageUpdater() run :: End
I/MusicWidget( 2640): beingMusicWidget_4x2() result::false
I/MusicWidget( 2640): beingMusicWidget_Quick() result::false
I/MusicWidget( 2640): beingMusicWidget_4x1() result::true
I/MusicWidget( 2640): send mDelayedStopHandler
I/MusicWidget( 2640): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2640): beingMusicWidget_Quick() result::false
D/MusicBrowser( 2702): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2702): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2702): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2702): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2702): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
I/MusicBrowser( 2702): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
E/MusicBrowser( 2702): [GroupingIndexDataProvider.java:381:onCancelled()] oooooo ASYNCTASK is canceled
I/[LgeWidgetLib]LgeAppWidgetHostView( 1892): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 1892): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
V/CloudHub( 3946): [DATABASE][DBConnection|open] open database
E/CloudHub( 3946): [DATABASE][DBConnection|getUserId] User id: 0
E/CloudHub( 3946): [DATABASE][DBConnection|getDatabasePath] Database path: /data/user/0/com.lge.cloudhub/databases/cloudhub.db
V/CloudHub( 3946): [SERVICE][CloudHubReceiver|queryUploadCount] # of contents to upload: 0
I/VRBookmarkProvider( 3899): [BookmarkProvider.java:530:handleMessage()-[Thread:Other] -- syncTable() START --
V/DownloadManager( 3212): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3212): created cursor android.database.sqlite.SQLiteCursor@b9b6ee6 on behalf of 3946
I/MusicWidget( 2640): performViewUpdater handleMessage() msg.what::0
I/MusicWidget( 2640): beingMusicWidget_4x1() result::true
I/MusicWidget( 2640): performUpdate()_4x1
D/AndroidRuntime( 3943): 
D/AndroidRuntime( 3943): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/MusicWidget( 2640): defaultAppWidget()_4x1
I/MusicWidget( 2640): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2640): 4x1_currentTheme :: null
I/MusicWidget( 2640): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2640): setDefaultViewLayoutId()_4x1
V/CloudHub( 3946): [SERVICE][CloudHubReceiver|queryDownloadCount] # of contents to download: 0
D/AndroidRuntime( 3943): CheckJNI is OFF
I/MusicWidget( 2640): appWidgetViewUpdate()_4x1
I/MusicWidget( 2640): linkButtons()_4x1
I/ActivityManager(  968): Start proc com.lge.gnss.airtest for broadcast com.lge.gnss.airtest/.GnssAirTestReceiver: pid=3965 uid=10054 gids={50054, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  968): Killing 1982:com.google.process.gapps/u0a6 (adj 15): empty #11
W/libprocessgroup(  968): failed to open /acct/uid_10006/pid_1982/cgroup.procs: No such file or directory
I/MusicWidget( 2640): pushUpdate()_4x1
I/VRBookmarkProvider( 3899): [BookmarkProvider.java:532:handleMessage()-[Thread:Other] -- syncTable() END --
I/MusicWidget( 2640): performViewUpdater handleMessage() msg.what::1
I/MusicWidget( 2640): beingMusicWidget_4x2() result::false
D/AirTest ( 3965): Set airtest_enable to false
I/ActivityManager(  968): Killing 3747:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/[LgeWidgetLib]LgeAppWidgetHostView( 1892): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 1892): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
W/libprocessgroup(  968): failed to open /acct/uid_1000/pid_3747/cgroup.procs: No such file or directory
V/LGSC    ( 2779): [104] 401
D/AndroidRuntime( 3943): Calling main entry com.android.commands.am.Am
I/ActivityManager(  968): Start proc com.lge.lgfota.permission for broadcast com.lge.lgfota.permission/.DmcTargetValidationReceiver: pid=3993 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  968): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  968): setTaskToReturnTo : TaskRecord{157c7b6c #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  968): setTaskToReturnTo : TaskRecord{157c7b6c #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 359us total 26.199ms
D/WindowStateEx(  968): AppWindowTokenEx init.. 
D/ContextHelper(  968): convertTheme. context->name=com.example.hello themeResourceId=16973833
D/InputDispatcher(  968): Focus left window: Window{1e4cdf4d u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 3943): Shutting down VM
I/[LGHome]EVENT( 1892): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  968): check instance of lgWin Window{af4dc96 u0 Starting com.example.hello}
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 374us total 31.717ms
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 23.371ms
I/ActivityManager(  968): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4012 uid=10317 gids={50317, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1892): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
D/TARGETVALIDLATION_RECEIVER( 3993): TargetValidationReceiver_ACTION_BOOT_COMPLETETED Received
I/HotwordDetector( 1950): Closing mic
D/TARGETVALIDLATION_RECEIVER( 3993): updateFlag = new File(TARGET_FLAG_PATH)
D/TARGETVALIDLATION_RECEIVER( 3993): Do Not display result dialog. it is not used Update Tool!!
I/MicrophoneInputStream( 1950): mic_close com.google.android.apps.gsa.speech.audio.u@2004d763
V/AudioRecord( 1950): stop()
D/AudioRecord( 1950): AudioRecord->stop()
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
I/[LGHome]EVENT( 1892): [Launcher.java:5214:onStop()]onStop
V/AudioFlinger(  282): Record stopped OK
V/AudioPolicyManager(  282): stopInput() input 17
V/AudioPolicyService(  282): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  282): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  282): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  282): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  282): ThreadBase::setParameters() routing=0
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
W/ActivityThread( 1892): Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1892): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1892): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3407)
W/ActivityThread( 1892): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3496)
W/ActivityThread( 1892): 	at android.app.ActivityThread.access$1100(ActivityThread.java:155)
W/ActivityThread( 1892): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1352)
W/ActivityThread( 1892): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ActivityThread( 1892): 	at android.os.Looper.loop(Looper.java:135)
W/ActivityThread( 1892): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/ActivityThread( 1892): 	at java.lang.reflect.Method.invoke(Native Method)
W/ActivityThread( 1892): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ActivityThread( 1892): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/ActivityThread( 1892): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/WindowStateAnimator(  968): Starting window displayed
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb39e9000
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
I/SystemUI[Framework](  968): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
D/PhoneStatusBar( 1391): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  968): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  968): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  968): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  968): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@301b2767,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  968): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1391): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1391):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1391): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager(  968): Killing 3769:com.lge.clock/u0a10 (adj 15): empty #11
D/BarTransitions( 1391): draw background and invalidate : color = c000000
D/BarTransitions( 1391): draw background and invalidate : color = e0d0d0d
V/audio_hw_primary(  282): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  282): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  282): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  282): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  282): disable_audio_route: exit
E/audio_hw_primary(  282): disable_snd_device: enter 144
D/hardware_info(  282): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  282): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  282): stop_input_stream: exit: status(0)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyManager(  282): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  282): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  282): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  282): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  282): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  282): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  282): setParameters(): io 17, keyvalue hotword_active=0, calling pid 282
V/AudioFlinger(  282): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  282): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  282): in_set_parameters: exit: status(0)
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb39e9000
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
W/libprocessgroup(  968): failed to open /acct/uid_10010/pid_3769/cgroup.procs: No such file or directory
V/LGSC    ( 1766): [101] 102, action=android.intent.action.BOOT_COMPLETED, iccState=null
V/AudioRecord( 1950): stop()
V/AudioRecord( 1950): stop()
V/AudioRecord( 1950): stop()
I/ActivityManager(  968): Activity reported stop, but no longer stopping: ActivityRecord{1cd1fdf5 u0 com.lge.launcher2/.Launcher t219}
V/AudioFlinger(  282): releasing 16 from 1950 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
,V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
V/AudioPolicyManager(  282): releaseInput() 17
V/AudioPolicyManager(  282): closeInput(17)
V/AudioFlinger(  282): closeInput() 17
V/AudioSystem(  282): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1766): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): ThreadBase::exit
V/AudioSystem( 2702): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1391): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2001): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3182): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  968): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioSystem( 1950): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): RecordThread 0xb39e9000 exiting
D/ContextHelper( 4012): convertTheme. context->name=com.example.hello themeResourceId=16973833
D/audio_hw_primary(  282): adev_close_input_stream: enter:stream_handle(0xb546e240)
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioPolicyService(  282): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  282): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  282): releaseInput() exit
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioFlinger(  282): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  282): AudioCommandThread() processing update audio port list
V/AudioFlinger(  282): removeClient_l() pid 1950, calling pid 282
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
W/ContextImpl( 2889): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2663 
E/AtFwd AutoBoot( 2889): AtFwd Auto Boot Started Successfully
I/HotwordRecognitionRnr( 1950): Stopping hotword detection.
I/HotwordRecognitionRnr( 1950): Hotword detection finished
I/ActivityManager(  968): Start proc com.google.process.gapps for broadcast com.google.android.syncadapters.contacts/.ContactsSyncAdapterBroadcastReceiver: pid=4029 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/SearchBackgroundTaskFac( 1950): refreshing internal icing corpora
I/WebViewFactory( 4012): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/SearchBackgroundTaskFac( 1950): Checking for language pack updates
I/GservicesProvider( 4029): Gservices pushing to system: true; secure/global: true
I/LibraryLoader( 4012): Time to load native libraries: 12 ms (timestamps 2838-2850)
I/LibraryLoader( 4012): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 4012): Binding Chromium to main looper Looper (main, tid 1) {15472674}
I/LibraryLoader( 4012): Expected native library version number "",actual native library version number ""
I/chromium( 4012): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/GservicesUpdateTask( 1950): Updating Gservices keys
I/BrowserStartupController( 4012): Initializing chromium process, singleProcess=true
W/art     ( 4012): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4012): ApplicationContext is null in ApplicationStatus
W/chromium( 4012): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 4012): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4012): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4012): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4012): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4012): Build Date: 03/02/15 Mon
I/Adreno-EGL( 4012): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 4012): Remote Branch: 
I/Adreno-EGL( 4012): Local Patches: 
I/Adreno-EGL( 4012): Reconstruct Branch: 
I/GoogleHttpClient( 4029): GMS http client unavailable, use old client
V/GLSActivity( 1748): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1748): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GoogleHttpClient( 4029): GMS http client unavailable, use old client
I/GservicesProvider( 4029): Gservices pushing to system: true; secure/global: true
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.googlequicksearchbox/files/download_cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 1950): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.googlequicksearchbox/files/download_cache
V/AudioPolicyService(  282): registerClient() client 0xb39ad6a0, uid 10317
D/BluetoothManagerService(  968): Message: 20
D/BluetoothManagerService(  968): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d09e1d2:true
D/BluetoothAdapterService(183121376)( 2001): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3c798c36
I/UpdateIcingCorporaServi( 1950): Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
I/ActivityManager(  968): Start proc com.lge.defaultaccount for broadcast com.lge.defaultaccount/.receiver.ReceiverBootUp: pid=4091 uid=10062 gids={50062, 9997} abi=armeabi-v7a
,I/GoogleHttpClient( 4029): GMS http client unavailable, use old client
,I/NotificationManager( 1950): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/InsertAccount( 4091): The account already exists
,I/ActivityManager(  968): Start proc com.lge.hiddenmenu for broadcast com.lge.hiddenmenu/.kddi_only.sms_setting.AssistReceiver: pid=4125 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  968): Killing 3794:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #11
I/art     ( 1748): Explicit concurrent mark sweep GC freed 20748(1518KB) AllocSpace objects, 22(352KB) LOS objects, 39% free, 12MB/21MB, paused 6.147ms total 148.129ms
,W/art     ( 4012): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 4012): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 4012): CordovaWebView is running on device made by: LGE
,W/libprocessgroup(  968): failed to open /acct/uid_10011/pid_3794/cgroup.procs: No such file or directory
,W/art     ( 4012): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4012): Attempt to remove local handle scope entry from IRT, ignoring
I/InsertAccount( 4091): The account info in contact DB already exists
,I/InsertAccount( 4091): The account info in calendar DB already exists
,W/ResourcesManager( 4125): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4125): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/WebViewFactory( 1950): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/Process ( 4091): Sending signal. PID: 4091 SIG: 9
I/[SMS_AD]( 4125): Intent action: android.intent.action.BOOT_COMPLETED
,I/UpdateIcingCorporaServi( 1950): UpdateCorporaTask done [took 454 ms] updated apps [took 413 ms] 
I/ActivityManager(  968): Process com.lge.defaultaccount (pid 4091) has died
,I/Activity( 4012): Activity.onPostResume() called 
D/OpenGLRenderer( 4012): Render dirty regions requested: true
I/OpenGLRenderer( 4012): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4012): Enabling debug mode 0
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
I/[SMS_AD]( 4125): Intent action: android.intent.action.BOOT_COMPLETED
D/libc-netbsd( 1748): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1748): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1748): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1748): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1748): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1748): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd( 1748): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1748): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/Atlas   ( 4012): Validating map...
,D/SplitWindow(  968): check instance of lgWin Window{1f037ae7 u0 com.example.hello/com.example.hello.MainActivity}
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/WeatherAncestor( 2696): 2 : onReceive, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 23:23:42
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
,D/UpdateThreadPoolManager( 2696): 2 : This is isUpdating : false
W/chromium( 4012): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/LibraryLoader( 1950): Time to load native libraries: 5 ms (timestamps 3645-3650)
I/LibraryLoader( 1950): Expected native library version number "",actual native library version number ""
D/Weather_cast( 2696): 2 : set auto-update time : 12/29 2:23
D/WeatherAncestor( 2696): 2 : onReceive has processed, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 23:23:42
,W/art     ( 1950): Attempt to remove local handle scope entry from IRT, ignoring
D/WeatherService( 2696): 2 : onStartCommand, intent!=null, action: android.intent.action.BOOT_COMPLETED
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1748): propertyValue:false
D/InputDispatcher(  968): Focus entered window: Window{1f037ae7 u0 com.example.hello/com.example.hello.MainActivity}
I/System.out( 1748): propertyValue:false
I/ActivityManager(  968): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.LockSettingsReceiver: pid=4162 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
W/ActivityManager(  968): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,I/ActivityManager(  968): Killing 3814:com.lge.appbox.client/u0a11 (adj 15): empty #11
D/Weather.Utils( 2696): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2696): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2696): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/InputMethodManagerService(  968): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
D/libc-netbsd( 1748): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1748): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1748): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1748): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/libprocessgroup(  968): failed to open /acct/uid_10011/pid_3814/cgroup.procs: No such file or directory
I/ActivityManager(  968): Displayed com.example.hello/.MainActivity: +1s351ms
I/Timeline(  968): Timeline: Activity_windows_visible id: ActivityRecord{3523a535 u0 com.example.hello/.MainActivity t220} time:53797
,I/Timeline( 4012): Timeline: Activity_idle id: android.os.BinderProxy@26062fd3 time:53818
,I/LockScreenSettings( 4162): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/LockScreenSettings( 4162): Received Broadcast : android.intent.action.BOOT_COMPLETED
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 53940594255; DSPS: 1866104; Offset : -3013418737
,W/BindingManager( 4012): Cannot call determinedVisibility() - never saw a connection for the pid: 4012
W/art     ( 1950): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  968): Start proc com.lge.springcleaning for broadcast com.lge.springcleaning/.receiver.BootCompleteReceiver: pid=4184 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  968): Killing 3254:com.android.settings/1000 (adj 15): empty #11
D/libc-netbsd( 1748): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1748): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1748): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1748): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1748): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1748): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1748): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1748): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/chromium( 4012): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,W/libprocessgroup(  968): failed to open /acct/uid_1000/pid_3254/cgroup.procs: No such file or directory
,D/libc-netbsd( 1950): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1950): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
,E/BandwidthController(  278): [LG DATA] No such appUid: 10042
D/DnsProxyListener(  278): App 10042 tries DNS query. Accept family:2 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/BootCompleteReceiver( 4184): hasclipTray = true
,W/ContextImpl( 4184): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.springcleaning.receiver.BootCompleteReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2663 
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
D/JsMessageQueue( 4012): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  968): Start proc com.lge.springcleaning:AppCleanupService for service com.lge.springcleaning/.service.AppCleanupService: pid=4210 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,E/AndroidProtocolHandler( 4012): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/GCM     ( 1748): COMPAT: Multi user not supported
,I/ActivityManager(  968): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=4227 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  968): Killing 3725:com.android.providers.calendar/u0a14 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  968): failed to open /acct/uid_10014/pid_3725/cgroup.procs: No such file or directory
,I/NotificationManager(  968): android: cancelAsUser(2) by android
,I/NotificationManager(  968): android: cancelAsUser(2) by android
V/AppCleanupService( 4210): registerAlarm
,D/AppCleanupService( 4210): noticeInterval = 2678400000
D/AppCleanupService( 4210): notiDateStr = 2016-01-20 22:41:42
D/AppCleanupService( 4210): noticeStart = 2016-01-20 22:41:42
,D/AppCleanupService( 4210): noticeStart = 1453326102000
D/AppUsageDbAdapter( 4210): initPreloadedAppToTheDB() : row count = 166
,I/NotificationManager( 1748): com.google.android.gms: cancel(0) by com.google.android.gms
I/NotificationManager( 1748): com.google.android.gms: cancel(0) by com.google.android.gms
D/libc-netbsd( 1950): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1950): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
E/BandwidthController(  278): [LG DATA] No such appUid: 10042
D/DnsProxyListener(  278): App 10042 tries DNS query. Accept family:2 protocol:0
,D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
E/UpdateRequestReceiver( 4227): ignoring update request
,E/UpdateRequestReceiver( 4227): ignoring update request
E/UpdateRequestReceiver( 4227): ignoring update request
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,E/UpdateRequestReceiver( 4227): ignoring update request
,E/UpdateRequestReceiver( 4227): ignoring update request
E/UpdateRequestReceiver( 4227): ignoring update request
,I/ActivityManager(  968): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=4262 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  968): Killing 3873:com.android.managedprovisioning/u0a111 (adj 15): empty #11
W/libprocessgroup(  968): failed to open /acct/uid_10111/pid_3873/cgroup.procs: No such file or directory
,D/jxcore_app_log( 4012): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1623030272
D/JX-Cordova( 4012): jxcore cordova android initializing
D/SIMObserver( 4262): action:android.intent.action.BOOT_COMPLETED
,D/SIMObserver( 4262): handle ACTION_BOOT_COMPLETED
,I/ActivityManager(  968): Killing 3899:com.lge.voicerecorder/u0a34 (adj 15): empty #11
,W/jxcore-log( 4012): Initializing JXcore engine
W/jxcore-log( 4012): JXcore engine is ready
,W/jxcore-log( 4012): Starting JXcore engine
W/libprocessgroup(  968): failed to open /acct/uid_10034/pid_3899/cgroup.procs: No such file or directory
,W/m.example.hello( 4012): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6712]" dev="sockfs" ino=6712 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 4012): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 4012): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5731]" dev="sockfs" ino=5731 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 4012): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 4012): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 4012): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[21567]" dev="sockfs" ino=21567 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
V/AlarmManager(  968): ELAPSED_WAKEUP set : Alarm{38d04130 type 2 when 54899 com.android.providers.calendar} when 54899
,E/QcrilMsgTunnelAutoboot( 2309): Received Intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot (has extras) } canStartService = false
,D/PhoneInterfaceManager( 1766): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
D/PhoneInterfaceManager( 1766): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
I/ActivityManager(  968): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4283 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/jxcore-log( 4012): Platform android
W/jxcore-log( 4012): 
W/jxcore-log( 4012): Process ARCH arm
W/jxcore-log( 4012): 
,W/ResourcesManager( 4283): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/jxcore-log( 4012): JXcore Cordova bridge is ready!
I/jxcore-log( 4012): 
W/jxcore-log( 4012): JXcore engine is started
,E/jxcore-log( 4012): >> LGE-LG-D722
E/jxcore-log( 4012): 
,I/jxcore-log( 4012): Total memory 906309632
I/jxcore-log( 4012): 
I/jxcore-log( 4012): Free memory 29057024
I/jxcore-log( 4012): 
I/jxcore-log( 4012): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4012): 
I/jxcore-log( 4012): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4012): 
I/jxcore-log( 4012): userPath [ 'www' ]
I/jxcore-log( 4012): 
I/jxcore-log( 4012): Size 720 1196
I/jxcore-log( 4012): 
,I/jxcore-log( 4012): Screen Brightness 255
I/jxcore-log( 4012): 
E/jxcore-log( 4012): Dummy Error Log.
E/jxcore-log( 4012): 
,I/Babel_SMS( 4283): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4283): MmsConfig.loadMmsSettings
,I/Babel_SMS( 4283): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 4283): MmsConfig.loadFromDatabase
,E/Babel_SMS( 4283): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4283): MmsConfig.loadFromResources
E/Babel_SMS( 4283): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4283): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 4283): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 4283): found sensor: LGE Magnetometer Sensor, handle=10
,D/SensorManager( 4283): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 4283): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 4283): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 4283): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 4283): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 4283): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 4283): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 4283): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 4283): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 4283): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 4283): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 4283): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 4283): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 4283): found sensor: Motion Accel, handle=46
I/art     (  968): Explicit concurrent mark sweep GC freed 26536(1278KB) AllocSpace objects, 3(237KB) LOS objects, 33% free, 23MB/34MB, paused 2.489ms total 159.772ms
I/art     ( 4283): CheckpointMarkThreadRoots callback created = 0xb042d8a0
,I/art     ( 4283): CheckpointMarkThreadRoots callback created = 0xb042d870
,W/Settings( 4283): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4283): startup - clean
I/Babel   ( 4283): deleted: false for 0
,I/jxcore-log( 4012): getBuffer is called!!!!
I/jxcore-log( 4012): 
,W/AudioCapabilities( 4283): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 4283): Unsupported mime audio/adpcm
W/AudioCapabilities( 4283): Unsupported mime audio/g726
W/AudioCapabilities( 4283): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4283): Unsupported mime audio/wma-voice
W/VideoCapabilities( 4283): Unsupported mime video/mjpg
W/VideoCapabilities( 4283): Unsupported mime video/theora
,W/AudioCapabilities( 4283): Unsupported mime audio/evrc
W/AudioCapabilities( 4283): Unsupported mime audio/qcelp
W/VideoCapabilities( 4283): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 4283): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 4283): Unsupported mime audio/qcelp
W/AudioCapabilities( 4283): Unsupported mime audio/evrc
W/VideoCapabilities( 4283): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 4283): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 4283): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4283): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4283): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4283): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 4283): onServiceConnected
W/Babel   ( 4283): Attempted to change video mute state without an active call.
,I/NotificationManager( 4283): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/ActivityManager(  968): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4319 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  968): Killing 3924:com.lge.drmservice/u0a51 (adj 15): empty #11
I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 22.044ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 345us total 21.197ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 22.180ms
,W/libprocessgroup(  968): failed to open /acct/uid_10051/pid_3924/cgroup.procs: No such file or directory
,W/ResourcesManager( 4319): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4319): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/JNIHelp ( 4319): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 4319): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4319): Installed default security provider GmsCore_OpenSSL
,I/art     ( 4319): CheckpointMarkThreadRoots callback created = 0xaaf39220
,I/art     ( 4319): CheckpointMarkThreadRoots callback created = 0xaaf39210
,I/ActivityManager(  968): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=4353 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
E/YouTube MDX( 4319): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,W/ResourcesManager( 4319): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4319): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/libc-netbsd( 4319): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4319): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ResourcesManager( 4353): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4353): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4319): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
I/MultiDex( 4353): VM with version 2.1.0 has multidex support
,I/MultiDex( 4353): install
I/MultiDex( 4353): VM has multidex support, MultiDex support library is disabled.
I/dex2oat ( 4383): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-427047789.jar --oat-fd=34 --oat-location=/data/data/com.google.android.youtube/cache/ads-427047789.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 4383): dex2oat took 122.647ms (threads: 4)
,V/JNIHelp ( 4353): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/NotificationManager( 4319): com.google.android.youtube: cancel(2) by com.google.android.youtube
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4319): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4319): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4319): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/CursorWrapperInner( 3946): Cursor finalized without prior close()
,W/ActivityThread( 4353): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4353): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@67768cc: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4353): Installed default security provider GmsCore_OpenSSL
W/InstanceID/Rpc( 4319): Found 10006
I/NotificationManager( 4353): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 4353): com.google.android.gms: cancel(39789) by com.google.android.gms
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4319): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,D/NativeLibraryUtils( 4353): Install completed successfully. count=14 extracted=0
,D/libc-netbsd( 4319): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4319): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/libc-netbsd( 4319): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4319): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  278): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  968): Process com.lge.cloudhub (pid 3946) has died
,D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,I/System.out( 4319): propertyValue:false
D/libc-netbsd( 4319): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4319): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  968): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4444 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/NotificationManager( 4319): com.google.android.youtube: cancel(10436) by com.google.android.youtube
,I/ActivityManager(  968): Killing 3965:com.lge.gnss.airtest/u0a54 (adj 15): empty #11
,D/libc-netbsd( 4319): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4319): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/libprocessgroup(  968): failed to open /acct/uid_10054/pid_3965/cgroup.procs: No such file or directory
,W/ActivityManager(  968): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4444): getAccountsCursor
,V/GLSActivity( 1748): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 4444): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ActivityManager(  968): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  968): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,E/Gmail   ( 4444): Error finding the version of the Email provider.....
E/Gmail   ( 4444): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4444): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4444): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4444): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4444): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4444): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4444): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 4444): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4444): We do not support migrating this version of the Email provider.
W/ActivityManager(  968): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4444): Observing account changes for notifications
I/Gmail   ( 4444): getAccountsCursor
V/GLSActivity( 1748): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1748): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  968): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4491 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,W/ActivityManager(  968): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  968): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/ActivityThread( 4444): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@284f74be that was originally bound here
E/ActivityThread( 4444): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@284f74be that was originally bound here
E/ActivityThread( 4444): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 4444): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 4444): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 4444): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 4444): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4444): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4444): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4444): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4444): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4444): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4444): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4444): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4444): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4444): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4444): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4444): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager(  968): Unbind failed: could not find connection for android.os.BinderProxy@2ca7b29b
,V/GLSActivity( 1748): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/[BNRBootReceiver]( 4491): boot receiver action = android.intent.action.BOOT_COMPLETED
,V/[BNRBootReceiver]( 4491): set property sys.lge.bnrd = 1
V/[BNRBootReceiver]( 4491): End of BootComplted IF
V/[BNRBootReceiver]( 4491): Boot Receiver Return
V/[BNRBootCompletedThread]( 4491): run
W/linker  ( 4512): /system/bin/bnrd has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/bnrd    ( 4512): BNRD > wait starting [4512-3058102400] <
E/bnrd    ( 4512): /data/data/.bnr_fifo_req
V/[BNRBootCompletedThread]( 4491): End of BNRProcess
,V/[BNRBootCompletedThread]( 4491): End of BNRViaWifiProcess
V/[BNRBootCompletedThread]( 4491): End of SpriteProcess
V/[BNRBootCompletedThread]( 4491): exit
I/Gmail   ( 4444): notifyAccountChanged
,I/ActivityManager(  968): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4520 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  968): Killing 3993:com.lge.lgfota.permission/1000 (adj 15): empty #11
I/Gmail   ( 4444): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4444): getAccountsCursor
,I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Gmail   ( 4444): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4444): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4444): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/libprocessgroup(  968): failed to open /acct/uid_1000/pid_3993/cgroup.procs: No such file or directory
V/GLSActivity( 1748): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  968): Killing 4125:com.lge.hiddenmenu/1000 (adj 15): empty #11
,W/libprocessgroup(  968): failed to open /acct/uid_1000/pid_4125/cgroup.procs: No such file or directory
,I/Gmail   ( 4444): getAccountsCursor
,V/GLSActivity( 1748): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 4520): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/Finsky  ( 4520): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 4520): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4520): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 4520): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3212): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3212): created cursor android.database.sqlite.SQLiteCursor@38dc7c27 on behalf of 4520
D/Volley  ( 4520): [473] DiskBasedCache.clear: Cache cleared.
,D/Ads     ( 4520): Skipping gmscore version check
D/Volley  ( 4520): [466] DiskBasedCache.clear: Cache cleared.
D/Finsky  ( 4520): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4520): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 4520): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4520): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/FileApkUtils( 4353): Spent 59ms computing apk sha1.
D/FileApkUtils( 4353): Module already staged or being staged:chimera-modules/MapsModule.apk
,I/art     ( 4353): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-ca8b2a9144773fc3650c54ed299f2d4558171b12@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
D/DexOptUtils( 4353): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
,D/FileApkUtils( 4353): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
D/ChimeraCfgMgr( 4353): Reading stored module config
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/art     (  968): Explicit concurrent mark sweep GC freed 21119(1008KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 1.970ms total 164.628ms
,D/GmsModuleFndr( 4353): Beginning GMS chimera module scan
W/InstanceID/Rpc( 4353): Found 10006
,D/GmsModuleFndr( 4353): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/ChimeraCfgMgr( 4353): Beginning module configuration check
,D/ChimeraCfgMgr( 4353): Module APKs unchanged, check complete
D/ChimeraCfgMgr( 4353): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/BootCompletedReceiver( 4353): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
D/BootCompletedReceiver( 4353): Got an BootCompleted event.
D/BootCompletedReceiver( 4353): Will NOT schedule AdAttestation signal task because it's disabled.
,I/art     ( 4353): CheckpointMarkThreadRoots callback created = 0xaae7b5d0
I/art     ( 4029): Explicit concurrent mark sweep GC freed 10203(527KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 439us total 42.441ms
,D/KeyguardUpdateMonitor( 1391): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1391): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1391): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1391): On Skip Timer : true
D/PowerService( 1819): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/CheckinService( 4353): Checkin interval check for package: unspecified last checkin: 1450837195376 min interval config: 0 actual interval: 504232806
I/art     ( 4353): CheckpointMarkThreadRoots callback created = 0xb042d740
D/GCM     ( 4353): COMPAT: Multi user not supported
,I/CheckinService( 4353): Disabling old GoogleServicesFramework version
I/GCoreUlr( 4353): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/SystemUpdateService( 4353): onCreate
,I/CheckinService( 4353): Checking schedule, now: 1451341428339 next: 1451364444338
I/CheckinService( 4353): active receiver: disabled
D/SystemUpdateService( 4353): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,V/AuthZen ( 4353): Handling intent: android.intent.action.BOOT_COMPLETED
,I/SystemUpdateService( 4353): cancelUpdate (empty URL)
I/SystemUpdateService( 4353): active receiver: disabled
,I/NotificationManager( 4353): com.google.android.gms: cancel(2130838165) by com.google.android.gms
,I/NotificationManager( 4353): com.google.android.gms: cancel(2130838166) by com.google.android.gms
I/art     ( 4353): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 4353): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/AuthZenEventHandler( 4353): Handling event: android.intent.action.BOOT_COMPLETED
W/BaseAppContext( 4353): Using Auth Proxy for data requests.
,E/BaseAppContext( 4353): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/art     ( 4029): Explicit concurrent mark sweep GC freed 6630(329KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 953us total 35.603ms
D/SystemUpdateService( 4353): onDestroy
,I/AuthZen ( 4353): Fetching signing key...
,I/ActivityManager(  968): Waited long enough for: ServiceRecord{fd189c8 u0 com.android.mms/.service.SwitchedService}
I/AuthZen ( 4353): Signing key fetched successfully!
W/BaseAppContext( 4353): Using Auth Proxy for data requests.
,D/a       ( 4353): Opening database auth.proximity.permit_store...
,D/AuthZenTransactionCache( 4353): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 4353): Clearing transaction cache
I/art     ( 1748): Explicit concurrent mark sweep GC freed 29067(1745KB) AllocSpace objects, 23(368KB) LOS objects, 40% free, 13MB/22MB, paused 1.747ms total 88.832ms
D/GCM     ( 1748): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,D/libc-netbsd( 1748): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1748): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1748): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1748): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
I/GCoreUlr( 1748): DispatchingService.onCreate()
I/NotificationManager(  968): android: cancelAsUser(-591465577) by android
,D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,I/System.out( 1748): propertyValue:false
D/BluetoothManagerService(  968): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  968): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2bc9c40d mBinding = false
D/BluetoothManagerService(  968): Message: 2
,D/BluetoothAdapterService(183121376)( 2001): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3c798c36
D/BluetoothManagerService(  968): Sending off request.
D/BluetoothAdapterService(183121376)( 2001): disable() called...
,D/LocationManagerService(  968): getAllProviders()=[passive, gps, network]
D/BluetoothAdapterService(183121376)( 2001): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3c798c36
D/BluetoothAdapterService(183121376)( 2001): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3c798c36
D/BluetoothAdapterState( 2001): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 2001): Setting state to 13
I/BluetoothAdapterState( 2001): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService(183121376)( 2001): updateAdapterState() - Broadcasting state to 1 receivers.
D/Ulp_jni (  968): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/WifiServiceImplEx(  968): setWifiEnabled: false pid=4012, uid=10317, package= com.example.hello, App Lable : HelloWorld
D/Ulp_jni (  968): JNI:system_update. Event-4
D/WifiService(  968): setWifiEnabled: false pid=4012, uid=10317
D/BluetoothAdapterProperties( 2001): onBluetoothDisable()
I/bt-btif ( 2001): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterState( 2001): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,I/jxcore-log( 4012): ****TEST TOOK:  5088  ms ****
I/jxcore-log( 4012): 
D/LocationManagerService(  968): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  968): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  968): JNI:system_update. Event-4
D/BluetoothAdapterProperties( 2001): Scan Mode:20
I/jxcore-log( 4012): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4012): 
D/BluetoothAdapterState( 2001): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 2001): BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
E/bt-btif ( 2001): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
D/bt-btif ( 2001): btsock_ctrl_hci_cleanup(L202): poll handle:4
I/bt-btif ( 2001): BTA_JvDeleteRecord
I/bt-btif ( 2001): BTA_JvRfcommStopServer
I/bt-btif ( 2001): BTA_JvDeleteRecord
I/bt-btif ( 2001): BTA_JvRfcommStopServer
W/bt-btif ( 2001): invalid rfc slot id: 1
D/IOP_DB_BT( 2001): db_close: nbr users 0
D/IOP_DB_BT( 2001): db_close: free database
E/WifiStateMachine(  968): WifiStateMachine: Leaving Connected state
I/GCoreUlr( 1748): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,I/NotificationManager( 4353): com.google.android.gms: cancel(10436) by com.google.android.gms
E/WifiConfigStore(  968): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/btif_config_util( 2001): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/btif_config_util( 2001): enum_config(L300): in, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 2001): enum_config(L302): section name:Local, key name:Adapter, value name:BluezMigrationDone, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:Adapter, value:Address
D/btif_config_util( 2001): enum_config(L302): section name:Local, key name:Adapter, value name:Address, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:Adapter, value:Address
D/btif_config_util( 2001): enum_config(L344): out, value:f8:95:c7:87:85:54
D/btif_config_util( 2001): enum_config(L300): in, key:Adapter, value:Name
D/btif_config_util( 2001): enum_config(L302): section name:Local, key name:Adapter, value name:Name, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:Adapter, value:Name
D/btif_config_util( 2001): enum_config(L344): out, value:G3s-1
D/btif_config_util( 2001): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 2001): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IR, value type:binary
D/btif_config_util( 2001): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 2001): enum_config(L344): out, value:��l:4A�O���x�x�E@=-��ӑ`-'����8�\�婓��n�ScanMode
D/btif_config_util( 2001): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 2001): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IRK, value type:binary
D/btif_config_util( 2001): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 2001): enum_config(L344): out, value:�E@=-��ӑ`-'����8�\�婓��n�ScanMode
D/btif_config_util( 2001): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 2001): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_DHK, value type:binary
D/btif_config_util( 2001): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 2001): enum_config(L344): out, value:��8�\�婓��n�ScanMode
D/btif_config_util( 2001): enum_config(L300): in, key:Adapter, value:ScanMode
D/btif_config_util( 2001): enum_config(L302): section name:Local, key name:Adapter, value name:ScanMode, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:Adapter, value:ScanMode
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 2001): enum_config(L302): section name:Local, key name:Adapter, value name:DiscoveryTimeout, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 2001): enum_config(L344): out, value:x
D/btif_config_util( 2001): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 2001): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_ER, value type:binary
D/btif_config_util( 2001): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 2001): enum_config(L344): out, value:s!WE�(E��00:0F:F6
D/btif_config_util( 2001): enum_config(L300): in, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 2001): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:AddressBlacklist, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 2001): enum_config(L344): out, value:00:02:C7,00:16:FE,00:19:C1,00:1B:FB,00:1E:3D,00:2,1:4F,00:23:06,00:24:33,00:A0:79,00:0E:6D,00:13:E0,00:21:E8,00:60:57,00:0E:9F,00:12:1C,00:18:91,00:18:96,00:13:04,00:16:FD,00:22:A0,00:0B:4C,00:60:6F,00:23:3D,00:C0:59,00:0A:30,00:1E:AE,00:1C:D7,00:80:F0,00:12:8A,00:09:93,00:80:37,00:26:7E,00:06:F7,00:13:7B,00:1E:B2,00:07:04,00:13:7B,00:14:0A,00:1A:1B,00:22:4D,00:0B:24,00:1E:B2,00:0B:1F,18:6D:99,00:54:AF,18:6D:99,94:44:44,00:21:CC,04:98:F3,00:26:E8
D/btif_config_util( 2001): enum_config(L300): in, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 2001): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:ExactNameBlacklist, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 2001): enum_config(L344): out, value:Motorola IHF1000,i.TechBlueBAND,X5 Stereo v1.3,KML_CAN,Microsoft Mouse
D/btif_config_util( 2001): enum_config(L300): in, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 2001): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:PartialNameBlacklist, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 2001): enum_config(L344): out, value:BMW,Audi,Parrot,Car
D/btif_config_util( 2001): enum_config(L300): in, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 2001): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:FixedPinZerosKeyboardBlacklist, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 2001): enum_config(L344): out, value:00:0F:F6
D/btif_config_util( 2001): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Manufacturer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpVer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpSubVer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L344): out, value:�
D/btif_config_util( 2001): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Name, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Name
,D/btif_config_util( 2001): enum_config(L344): out, value:HTC Desire 820
D/btif_config_util( 2001): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevClass, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 2001): enum_config(L344): out, value:Z
D/btif_config_util( 2001): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevType, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:JustWorks, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:GlobalTrust, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Service, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 2001): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2001): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Manufacturer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpVer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpSubVer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L344): out, value:$
D/btif_config_util( 2001): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Name, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 2001): enum_config(L344): out, value:Galaxy S6-1
D/btif_config_util( 2001): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 2001): enum_config(L302): section nam,e:Remote, key name:10:d3:8a:fb:85:d4, value name:DevClass, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 2001): enum_config(L344): out, value:Z
D/btif_config_util( 2001): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevType, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:JustWorks, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:GlobalTrust, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Service, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 2001): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2001): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Manufacturer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpVer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpSubVer, value type:int,
D/btif_config_util( 2001): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L344): out, value:�
D/btif_config_util( 2001): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Name, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 2001): enum_config(L344): out, value:A5-1
D/btif_config_util( 2001): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevClass, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 2001): enum_config(L344): out, value:Z
D/btif_config_util( 2001): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevType, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:JustWorks, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:GlobalTrust
,D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:GlobalTrust, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Service
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Service, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Service
D/btif_config_util( 2001): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
,D/btif_config_util( 2001): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Manufacturer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpVer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpVer
,D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpSubVer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L344): out, value:#
D/btif_config_util( 2001): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Name,
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Name, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 2001): enum_config(L344): out, value:Nexus 6
D/btif_config_util( 2001): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevClass, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevClass
,D/btif_config_util( 2001): enum_config(L344): out, value:Z
D/btif_config_util( 2001): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevType, value type:int
V/BluetoothPbapService( 2001): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/GCoreFlp( 1748): No location to return for getLastLocation()
D/btif_config_util( 2001): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 2001): enum_config(L344): out, value:
,D/btif_config_util( 2001): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:JustWorks, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:JustWorks
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
,D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:GlobalTrust, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Service, value type:string
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/btif_config_util( 2001): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 2001): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2001): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Manufacturer,
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Manufacturer, value type:int
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/btif_config_util( 2001): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Manufacturer
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpVer, value type:int
,D/btif_config_util( 2001): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpVer
D/libc-netbsd( 1748): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpSubVer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/libc-netbsd( 1748): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/btif_config_util( 2001): enum_config(L344): out, value:�
D/btif_config_util( 2001): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Name, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 2001): enum_config(L344): out, value:XT1072
D/btif_config_util( 2001): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevClass
,D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevClass, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 2001): enum_config(L344): out, value:Z
D/btif_config_util( 2001): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevType, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevType
,W/bt-btif ( 2001): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:JustWorks, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:GlobalTrust, value type:int
,D/btif_config_util( 2001): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Service, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Service
D/btif_config_util( 2001): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
,D/btif_config_util( 2001): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Manufacturer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpVer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpVer
,D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpSubVer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L344): out, value:a
,D/btif_config_util( 2001): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Name, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 2001): enum_config(L344): out, value:S5-1
D/btif_config_util( 2001): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevClass, value type:int
,D/btif_config_util( 2001): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 2001): enum_config(L344): out, value:Z
D/btif_config_util( 2001): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevType, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:JustWorks, value type:int
,D/btif_config_util( 2001): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:GlobalTrust, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Service
,D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Service, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Service
D/btif_config_util( 2001): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2001): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Manufacturer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Manufacturer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Manufacturer
,D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpVer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpVer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpVer
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpSubVer, value type:int
,D/btif_config_util( 2001): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L344): out, value:	a
D/btif_config_util( 2001): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Name
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Name, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Name
D/btif_config_util( 2001): enum_config(L344): out, value:G4-1
D/btif_config_util( 2001): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevClass
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevClass, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevClass
D/btif_config_util( 2001): enum_config(L344): out, value:Z
D/btif_config_util( 2001): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevType
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevType, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevType
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:JustWorks
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:JustWorks, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:JustWorks
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:GlobalTrust, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Service
E/bt-btif ( 2001): btif_hf_upstreams_evt: wrong handle = 2610 
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Service, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Service
W/FusedLocationProvider( 1748): location=null
D/btif_config_util( 2001): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2001): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Manufacturer
,D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Manufacturer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Manufacturer
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpVer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpVer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpVer
,D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpSubVer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L344): out, value:a
D/btif_config_util( 2001): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Name
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Name, value type:string
,D/btif_config_util( 2001): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Name
D/btif_config_util( 2001): enum_config(L344): out, value:Thali Test (Galaxy S5)
D/btif_config_util( 2001): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevClass
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevClass, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevClass
D/btif_config_util( 2001): enum_config(L344): out, value:Z
D/btif_config_util( 2001): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevType
,D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevType, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevType
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:JustWorks
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:JustWorks, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:JustWorks
D/btif_config_util( 2001): enum_config(L344): out, value:
,D/btif_config_util( 2001): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:GlobalTrust, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Service
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Service, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Service
,D/btif_config_util( 2001): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2001): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Manufacturer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Manufacturer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Manufacturer
,D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpVer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpVer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpVer
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpSubVer, value type:int
,D/btif_config_util( 2001): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L344): out, value:�
D/btif_config_util( 2001): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Name
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Name, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Name
D/btif_config_util( 2001): enum_config(L344): out, value:Thali Test (Galaxy A5)
,D/btif_config_util( 2001): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevClass
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevClass, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevClass
D/btif_config_util( 2001): enum_config(L344): out, value:Z
D/btif_config_util( 2001): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevType
,D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevType, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevType
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:JustWorks, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:GlobalTrust
,D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:GlobalTrust, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Service
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Service, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Service
D/btif_config_util( 2001): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
,D/btif_config_util( 2001): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Manufacturer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Manufacturer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Manufacturer
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpVer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpSubVer, value type:int
,D/btif_config_util( 2001): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L344): out, value:�
D/btif_config_util( 2001): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Name
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Name, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Name
D/btif_config_util( 2001): enum_config(L344): out, value:Thali Test (Galaxy A3)
D/btif_config_util( 2001): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevClass
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevClass, value type:int
,D/btif_config_util( 2001): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevClass
D/btif_config_util( 2001): enum_config(L344): out, value:Z
D/btif_config_util( 2001): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevType
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevType, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevType
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:08:ec:a9:50:76:27, value:JustWorks
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:JustWorks, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:08:ec:a9:50:76:27, value:JustWorks
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:08:ec:a9:50:76:27, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:GlobalTrust, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:08:ec:a9:50:76:27, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Service
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Service, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Service
D/btif_config_util( 2001): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2001): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Manufacturer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Manufacturer, value type:int
,D/btif_config_util( 2001): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Manufacturer
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpVer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpVer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpVer
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpSubVer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L344): out, value:A
D/btif_config_util( 2001): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Name
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Name, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Name
D/btif_config_util( 2001): enum_config(L344): out, value:Thali Test's G2
D/btif_config_util( 2001): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevClass
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevClass, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevClass
D/btif_config_util( 2001): enum_config(L344): out, value:Z
D/btif_config_util( 2001): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevType
,D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevType, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevType
D/btif_config_util( 2001): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:JustWorks
D/btif_config_util( 2001): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:JustWorks
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Service
,D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Service, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Service
D/btif_config_util( 2001): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Manufacturer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Manufacturer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Manufacturer
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpSubVer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Name
D/btif_config_util( 2001): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevClass
,D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevClass, value type:int
D/btif_config_util( 2001): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevType
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevType, value type:int
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:JustWorks, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:JustWorks
D/btif_config_util( 2001): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:GlobalTrust, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:GlobalTrust
,D/btif_config_util( 2001): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Service
D/btif_config_util( 2001): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Service
D/btif_config_util( 2001): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2001): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Manufacturer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpVer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpVer
D/btif_config_util( 2001): enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L344): out, value:�
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Name, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Name
D/btif_config_util( 2001): enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevClass
D/btif_config_util( 2001): enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevClass
D/btif_config_util( 2001): enum_config(L344): out, value:Z
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevType, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevType,
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:08:ec:a9:50:75:41, value:JustWorks
,D/btif_config_util( 2001): enum_config(L343): out, key:08:ec:a9:50:75:41, value:JustWorks
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:08:ec:a9:50:75:41, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L343): out, key:08:ec:a9:50:75:41, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Service, value type:string
D/btif_config_util( 2001): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
,D/btif_config_util( 2001): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Manufacturer
D/btif_config_util( 2001): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpVer
D/btif_config_util( 2001): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpVer
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:LmpSubVer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L344): out, value:�
,D/btif_config_util( 2001): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Name
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Name, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Name
D/btif_config_util( 2001): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:DevClass
D/btif_config_util( 2001): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevClass
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:JustWorks
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:GlobalTrust
,D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Service, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Service
D/btif_config_util( 2001): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Manufacturer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Manufacturer, value type:int
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpVer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpVer
D/btif_config_util( 2001): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpSubVer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L344): out, value:�
D/btif_config_util( 2001): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Name
,D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Name, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Name
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevClass, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:80:01:84:8a:b3:68, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Name
D/btif_config_util( 2001): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Name
D/btif_config_util( 2001): enum_config(L344): out, value:HTC Desire 820
D/btif_config_util( 2001): enum_config(L300): in, key:80:01:84:8a:b3:68, value:DevClass
D/btif_config_util( 2001): enum_config(L300): in, key:80:01:84:8a:b3:68, value:DevType
D/btif_config_util( 2001): enum_config(L343): out, key:80:01:84:8a:b3:68, value:DevType
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:80:01:84:8a:b3:68, value:JustWorks
D/btif_config_util( 2001): enum_config(L343): out, key:80:01:84:8a:b3:68, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Service
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Service, value type:string
,D/btif_config_util( 2001): enum_config(L300): in, key:58:3f:54:73:64:c0, value:Manufacturer
D/btif_config_util( 2001): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Manufacturer
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:58:3f:54:73:64:c0, value:LmpVer
D/btif_config_util( 2001): enum_config(L343): out, key:58:3f:54:73:64:c0, value:LmpVer
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:58:3f:54:73:64:c0, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:LmpSubVer, value type:int
D/btif_config_util( 2001): enum_config(L344): out, value:�
,D/btif_config_util( 2001): enum_config(L300): in, key:58:3f:54:73:64:c0, value:Name
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Name, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Name
D/btif_config_util( 2001): enum_config(L343): out, key:58:3f:54:73:64:c0, value:DevClass
D/btif_config_util( 2001): enum_config(L344): out, value:Z
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:DevType, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:58:3f:54:73:64:c0, value:DevType
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:JustWorks, value type:int
D/btif_config_util( 2001): enum_config(L300): in, key:58:3f:54:73:64:c0, value:GlobalTrust
,D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:GlobalTrust, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:58:3f:54:73:64:c0, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Service, value type:string
D/btif_config_util( 2001): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 0bbfc6ef-14cc-4ab2-af63-b92e887227ae 
D/btif_config_util( 2001): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Manufacturer
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:LmpVer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:LmpVer
D/btif_config_util( 2001): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:LmpSubVer,
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:LmpSubVer, value type:int
D/btif_config_util( 2001): enum_config(L344): out, value:	a
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Name, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Name
D/btif_config_util( 2001): enum_config(L344): out, value:Nexus 5,
D/btif_config_util( 2001): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:DevClass
D/btif_config_util( 2001): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:DevType
D/btif_config_util( 2001): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:DevType
D/btif_config_util( 2001): enum_config(L344): out, value:
,D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:JustWorks, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:JustWorks
D/btif_config_util( 2001): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L344): out, value:
,D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Service, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Service
D/btif_config_util( 2001): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Manufacturer
,D/btif_config_util( 2001): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Manufacturer
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:LmpVer, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:LmpVer
D/btif_config_util( 2001): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:LmpSubVer,
D/btif_config_util( 2001): enum_config(L344): out, value:�
D/btif_config_util( 2001): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Name
D/btif_config_util( 2001): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Name
D/btif_config_util( 2001): enum_config(L344): out, value:HTC One M8s,
D/btif_config_util( 2001): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:DevClass
D/btif_config_util( 2001): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:DevClass
D/btif_config_util( 2001): enum_config(L344): out, value:Z
D/btif_config_util( 2001): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:DevType
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:DevType, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:DevType
,D/btif_config_util( 2001): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Service
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Service, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Service
D/btif_config_util( 2001): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 00006675-7475-7265-6469-616c62756d70 
,D/btif_config_util( 2001): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:LmpVer
D/btif_config_util( 2001): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:LmpSubVer
D/btif_config_util( 2001): enum_config(L344): out, value:A
D/btif_config_util( 2001): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Name
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Name, value type:string
D/btif_config_util( 2001): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Name
D/btif_config_util( 2001): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:DevClass
D/btif_config_util( 2001): enum_config(L344): out, value:Z
,D/btif_config_util( 2001): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:DevType
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:DevType, value type:int
D/btif_config_util( 2001): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:JustWorks
D/btif_config_util( 2001): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:JustWorks
D/btif_config_util( 2001): enum_config(L344): out, value:
D/btif_config_util( 2001): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:GlobalTrust
D/btif_config_util( 2001): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:GlobalTrust
,D/btif_config_util( 2001): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Service
D/btif_config_util( 2001): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Service
D/btif_config_util( 2001): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2001): enum_config(L343): out, key:08:00:00:00:67:f3, value:Name
D/btif_config_util( 2001): enum_config(L300): in, key:08:00:00:00:67:f3, value:DevClass
D/btif_config_util( 2001): enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:DevClass
D/btif_config_util( 2001): enum_config(L344): out, value:��\
,D/btif_config_util( 2001): enum_config(L300): in, key:94:c6:76:a0:e3:b1, value:DevType
D/btif_config_util( 2001): enum_config(L302): section name:Remote, key name:94:c6:76:a0:e3:b1, value name:DevType, value type:int
D/btif_config_util( 2001): enum_config(L343): out, key:94:c6:76:a0:e3:b1, value:DevType
D/BluetoothAdapterService(183121376)( 2001): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3c798c36
D/OppService( 2001): Recieved MESSAGE_OPS_DISABLE
D/BluetoothManagerService(  968): Message: 60
V/BluetoothMapMasInstance( 2001): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2001): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2001): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
,V/BluetoothMapMasInstance( 2001): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 2001): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 2001): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2001): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2001): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
D/BluetoothManagerService(  968): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  968): Bluetooth State Change Intent: 12 -> 13
D/LGBluetoothAPIService( 1819): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapterService(183121376)( 2001): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3c798c36
D/BluetoothAdapterService(183121376)( 2001): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3c798c36
I/BluetoothMapService( 2001): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 2001): STATE_TURNING_OFF
V/BluetoothMapService( 2001): Handler(): got msg=4
D/BluetoothMapService( 2001): MAP Service closeService in
D/BluetoothMapMasInstance( 2001): MAP Service shutdown
D/LGBluetoothMapAdapter( 2001): [BTUI] LGBluetoothMapAdapter cleanup
,V/BluetoothMapService( 2001): MAP Service closeService out
I/[SystemUI]QuickSettingsHandler( 1391): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1391): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,D/LGWifiP2pService(  968): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  968): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager(  968): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=4640 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/CommandListener(  278): Clearing all IP addresses on wlan0
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 7
D/DhcpStateMachine(  968): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
W/GCoreFlp( 1748): No location to return for getLastLocation()
,V/NativeCrypto( 1748): SSL handshake aborted: ssl=0xaaee1000: I/O error during system call, Connection timed out
W/FusedLocationProvider( 1748): location=null
D/libc-netbsd(  968): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  968): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 7
D/ConnectivityService(  968): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  968): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/WifiHS20(  968): hidePasspointNotification off =false
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1391): mWifiConnected = false, mWifiLevel = 0
D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1855): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1855): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-28 23:23:48.992 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/WifiHS20(  968): hidePasspointNotification off =false
I/QCNEJ   ( 1855): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/libc-netbsd( 1748): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1748): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Auth    ( 1748): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
I/QCNEJ   ( 1855): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1855): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-28 23:23:49.007 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1855): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1391): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1391): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1391): Remote
D/libc-netbsd(  968): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  968): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  968): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  968): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LGWifiP2pService(  968): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  968): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNetworkAgent(  968): NetworkAgent: NetworkAgent channel lost
D/WifiScanningService(  968): SCAN_AVAILABLE : 1
D/RttService(  968): SCAN_AVAILABLE : 1
D/WifiScanningService(  968): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1391): mWifiConnected = false, mWifiLevel = 0
D/RttService(  968): EnabledState got{ when=-3ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/LGWifiP2pService(  968): P2pDisablingState
D/LGWifiP2pService(  968): P2pDisablingState{ when=-13ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  968): p2p socket connection lost
D/LGWifiP2pService(  968): P2pDisabledState
I/[SystemUI]QuickSettingsHandler( 1391): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1391): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1391): Remote
D/LGWifiP2pService(  968): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  968): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager(  968): Killing 4162:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
V/GLSActivity( 1748): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WfdsService( 1819): WifiP2pState is changed : false
D/WfdsService( 1819): WfdsEnabledState: Receive the WFDS_DISABLE message
,D/WfdsJNI ( 1819): doCommand: P2P_STOP_FIND
I/[SystemUI]QuickSettingsHandler( 1391): Got action android.net.wifi.p2p.STATE_CHANGED at null
W/libprocessgroup(  968): failed to open /acct/uid_10069/pid_4162/cgroup.procs: No such file or directory
D/CommandListener(  278): Clearing all IP addresses on wlan0
D/ConnectivityService(  968): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  968): disableDataServiceNotify
I/QCNEJ   ( 1855): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1855): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-28 23:23:49.095 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1855): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WfdsService( 1819): Set the WFDS Monitor: false
I/QCNEJ   ( 1855): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1855): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-28 23:23:49.1 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1855): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1391): mWifiConnected = false, mWifiLevel = 0
D/WifiHS20(  968): hidePasspointNotification off =false
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/DSQN    (  968): stop dsqn bin
D/WifiOffDelayIfNotUsed(  968): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/WifiServerServiceExt(  968): WIFI_STATE_CHANGED_ACTION [0]
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1391): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1391): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1391): Remote
D/WifiServerServiceExt(  968): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  968): setSupplicantStateDISCONNECTED
D/WfdsMonitor( 1819): WFDS Monitor is stopped
D/CtrlSupplicant( 1819): Received on exit socket, terminate
E/CtrlSupplicant( 1819): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsService( 1819): STATE : WfdsDisabledState - enter
D/WfdsService( 1819): WFDS: Scanner is paused
D/WfdsMonitor( 1819): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1819): WfdsMonitorThread is received the interrupt - closing
D/WfdsDiscoveryStore( 1819): Clear Discovery Method Map: ScanAlwaysMode false
W/WfdsSession:Controller( 1819): DefaultState - msg [9441355] is not handled
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1391): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/ConnectivityService(  968): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  968): ValidatedState{ when=0 what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  968): DefaultState{ when=0 what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  968): Forcing reevaluation
,D/PersistentNotificationBroadcastReceiver( 1748): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
D/WifiServiceExtension( 1819): isInternetCheckAvailable return false
I/Netd    (  278): M: Get netlink event, ifname: p2p0 action: 4
,I/Netd    (  278): M: Get netlink event, ifname: p2p0 action: 5
I/wpa_supplicant( 2840): p2p0: CTRL-EVENT-TERMINATING 
I/Netd    (  278): M: Get netlink event, ifname: p2p0 action: 10
I/wpa_supplicant( 2840): monitor socket send errors count : 1
I/wpa_supplicant( 2840): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1819-2\x00 that cannot receive messages
I/Netd    (  278): M: Get netlink event, ifname: p2p0 action: 7
D/libc-netbsd(  968): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  968): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  968): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,I/wpa_supplicant( 2840): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  968): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
W/wpa_supplicant( 2840): USIM:  scard_deinit function
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  968): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1391): CM callback handler got msg 524292
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  968): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  968): Disconnected - quitting
D/Nat464Xlat(  968): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
D/libc-netbsd(  968): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  968): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CSLegacyTypeTracker(  968): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  968): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/DhcpStateMachine(  968): StoppedState
D/DhcpStateMachine(  968): StoppedState{ when=-155ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,W/ResourcesManager( 4640): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/ActivityManager(  968): Start proc com.lge.qmemoplus for broadcast com.lge.qmemoplus/.ui.editor.reminder.ReminderMaker: pid=4668 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
D/Tethering(  968): MasterInitialState.processMessage what=3
D/ConnectivityService(  968): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  968): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy(  968): [LG_RESTRICTED] !!!isConnected  type  :1
W/ResourcesManager( 4640): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 4640): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4640): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
V/NetworkPolicy(  968): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  968): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  968): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  968): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  968): Removing idletimer
,W/Settings(  968): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/Tethering(  968): MasterInitialState.processMessage what=3
W/ResourcesManager( 4640): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/WIFI    (  968): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  968):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  968): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyNetworkFactory-1( 1766): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/QCNEJ   ( 1855): |CORE| No family connected
W/QCNEJ   ( 1855): |CORE| No family connected
I/QCNEJ   ( 1855): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/TelephonyNetworkFactory-1( 1766):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
,I/QCNEJ   ( 1855): |CORE| sendDefaultNwMsg: default = -1
I/GCoreUlr( 1748): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 4
I/GCoreUlr( 1748): Unbound from all location providers
I/GCoreUlr( 1748): Place inference reporting - stopped
D/TelephonyIcons( 1391): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1391): updateLGTelephonySignalStrength : !hasService()
I/Netd    (  278): M: Get netlink event, ifname: wlan0 action: 5
,I/wpa_supplicant( 2840): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  968): InitialState.processMessage what=4
D/WifiOffDelayIfNotUsed(  968): stopMonitoring
,D/Tethering(  968): sendTetherStateChangedBroadcast 0, 0, 0
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/Settings( 4283): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/WfdsService( 1819): Supplicant Connection state is changed : false
D/WfdsService( 1819): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1819): Set the WFDS Monitor: false
D/WfdsMonitor( 1819): WFDS Monitor is stopped
I/WifiServerServiceExt(  968): WIFI_STATE_CHANGED_ACTION [1]
,I/QCNEJ   ( 1855): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1855): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-12-28 23:23:49.274 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1855): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/WifiServerServiceExt(  968): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt(  968): batteryPsActivateMsgHandler : this is not treated
W/Settings( 1748): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyIcons( 1391): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1391): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1391): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]QuickSettingsHandler( 1391): Got action android.net.wifi.WIFI_STATE_CHANGED at null
I/GCoreUlr( 1748): DispatchingService.onDestroy()
I/GCoreUlr( 1748): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1748): Unbound from all location providers
I/GCoreUlr( 1748): Place inference reporting - stopped
,W/ResourcesManager( 4668): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/IndexDatabaseHelper( 4640): Using schema version: 115
D/AndroidRuntime( 4638): 
D/AndroidRuntime( 4638): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/IndexDatabaseHelper( 4640): Index is fine
D/AndroidRuntime( 4638): CheckJNI is OFF
,V/AlarmManager(  968): ELAPSED_WAKEUP set : Alarm{370ef60e type 2 when 60905 com.google.android.gms} when 60905
,E/App     ( 4668): [App][onCreate()] 4.40.23
W/ContextImpl( 4640): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,V/BluetoothPbapReceiver( 2001): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 2001): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 2001): ***********state = 13
V/BluetoothPbapReceiver( 2001): ***********Calling start service!!!! with action = null
,V/BluetoothPbapService( 2001): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 2001): state: 13
V/BluetoothPbapService( 2001): Pbap Service closeService in
V/BluetoothPbapService( 2001): successfully stopped pbap service
V/BluetoothPbapService( 2001): Pbap Service closeService out
V/BluetoothPbapService( 2001): Pbap Service onDestroy
V/BluetoothPbapService( 2001): Pbap Service closeService in
V/BluetoothPbapService( 2001): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 2001): [BTUI] cleanup
D/BluetoothManagerService(  968): Message: 20
,D/BluetoothManagerService(  968): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@362067c5:true
D/BluetoothAdapterService(183121376)( 2001): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3c798c36
,D/BluetoothManagerService(  968): Message: 30
D/BluetoothManagerService(  968): Message: 30
D/LocalBluetoothProfileManager( 4640): Adding local MAP profile
,D/BluetoothMap( 4640): Create BluetoothMap proxy object
D/BluetoothManagerService(  968): Message: 30
D/BluetoothManagerService(  968): Message: 30
D/LocalBluetoothProfileManager( 4640): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 4640):  get() - isFeatureLoaded : false
,D/LGBluetoothUserBindClient( 4640): [BTUI] initUserBindClient
,W/ContextImpl( 4640): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 4640): finishStartingService: stopping service
,D/BluetoothInputDevice( 4640): Proxy object connected
,D/HidProfile( 4640): Bluetooth service connected
D/BluetoothAdapterService(183121376)( 2001): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3c798c36
D/BluetoothPan( 4640): BluetoothPAN Proxy object connected
D/PanProfile( 4640): Bluetooth service connected
D/BluetoothAdapterService(183121376)( 2001): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3c798c36
D/BluetoothMap( 4640): Proxy object connected
D/MapProfile( 4640): Bluetooth service connected
D/BluetoothMap( 4640): getConnectedDevices()
,D/BluetoothAdapterService(183121376)( 2001): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3c798c36
D/BluetoothMap( 4640): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 4640): [BTUI] onServiceConnected
D/LGBluetoothAuthorization( 4640): [BTUI] cancel All Notification
I/NotificationManager( 4640): com.android.settings: cancel(17301632) by com.android.settings
I/NotificationManager( 4640): com.android.settings: cancel(-1000001) by com.android.settings
I/NotificationManager( 4640): com.android.settings: cancel(-1000011) by com.android.settings
I/NotificationManager( 4640): com.android.settings: cancel(-1000021) by com.android.settings
D/AndroidRuntime( 4638): Calling main entry com.android.commands.pm.Pm
I/NotificationManager( 4640): com.android.settings: cancel(-1000031) by com.android.settings
I/NotificationManager( 4640): com.android.settings: cancel(-1000041) by com.android.settings
D/BluetoothPermissionRequest( 4640): onReceive
D/LGBluetoothAuthorization( 4640): [BTUI] cancel All Notification
I/NotificationManager( 4640): com.android.settings: cancel(17301632) by com.android.settings
I/NotificationManager( 4640): com.android.settings: cancel(-1000001) by com.android.settings
I/NotificationManager( 4640): com.android.settings: cancel(-1000011) by com.android.settings
I/NotificationManager( 4640): com.android.settings: cancel(-1000021) by com.android.settings
I/NotificationManager( 4640): com.android.settings: cancel(-1000031) by com.android.settings
I/NotificationManager( 4640): com.android.settings: cancel(-1000041) by com.android.settings
,I/ActivityManager(  968): Killing 4184:com.lge.springcleaning/1000 (adj 15): empty #11
,W/PackageSettings(  968): Skipping PackageSetting{233b6f66 com.test.thalitest/10316} due to missing metadata
,W/libprocessgroup(  968): failed to open /acct/uid_1000/pid_4184/cgroup.procs: No such file or directory
V/BluetoothOppReceiver( 2001): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 2001): [BTUI] cancel opp incoming file confirm notification
,I/NotificationManager( 2001): com.android.bluetooth: cancel(-1) by com.android.bluetooth
D/BluetoothOppNotification( 2001): [BTUI] cancel opp active transfer file notification
I/NotificationManager( 2001): com.android.bluetooth: cancel(-1) by com.android.bluetooth
,I/ActivityManager(  968): Force stopping com.example.hello appid=10317 user=0: pkg removed
I/ActivityManager(  968): Killing 4012:com.example.hello/u0a317 (adj 0): stop com.example.hello
D/AccountManager( 4668): setSyncFrequency
,I/WindowState(  968): WIN DEATH: Window{1f037ae7 u0 com.example.hello/com.example.hello.MainActivity}
,D/InputDispatcher(  968): Focus left window: Window{1f037ae7 u0 com.example.hello/com.example.hello.MainActivity}
D/InputDispatcher(  968): Window went away: Window{1f037ae7 u0 com.example.hello/com.example.hello.MainActivity}
W/bt-l2cap( 2001): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2001): L2CAP - PSM: 0x0017 not found for deregistration
,W/bt-btif ( 2001): ag scb idx 1 not allocated
E/bt-btif ( 2001): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2001): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2001): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 2001): ag scb idx 1 not allocated
E/bt-btif ( 2001): BTA AG is already disabled, ignoring ...
E/bt-btif ( 2001): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt-btif ( 2001): bta_gattc_deregister Deregister Failedm unknown client cif
W/bt_userial( 2001): select_read return size <=0:0, exiting userial_read_thread
D/bt_hwcfg( 2001): hw_epilog_process
I/bt_userial_vendor( 2001): device fd = 70 close
W/ContextImpl( 4668): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.qmemoplus.ui.editor.reminder.ReminderMaker.onReceive:14 android.app.ActivityThread.handleReceiver:2663 
E/bt_vendor( 2001): [BTUI] Proto is enabled. Set Proto disable!!
,W/ActivityManager(  968): Force removing ActivityRecord{3523a535 u0 com.example.hello/.MainActivity t220}: app died, no saved state
,I/ActivityManager(  968): Force stopping com.example.hello appid=10317 user=-1: uninstall pkg
,V/BluetoothSapReceiver( 2001): [BTUI] checkServiceStart
D/ReminderService( 4668): [onHandleIntent] action : com.lge.qmemoplus.action.SET_REMINDERS
D/LocationReminderManager( 4668): [connect] Request location client connection.
W/ActivityManager(  968): Spurious death for ProcessRecord{17e4ced 4012:com.example.hello/u0a317}, curProc for 4012: null
D/LGBluetoothStateChangeReceiver( 2001): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
,D/KeyguardModel( 1391): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1748): Ignoring removeGeofence because network location is disabled.
,I/GKI_LINUX( 2001): GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
W/System.err( 3641): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 3641): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3641): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3641): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3641): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3641): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3641): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3641): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3641): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3641): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3641): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3641): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/InputReader(  968): Reconfiguring input devices.  changes=0x00000010
,I/QCNEJ   ( 1855): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/ActivityManager(  968): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=4707 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ContextImpl( 4668): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.google.android.gms.internal.he.a:-1 com.google.android.gms.internal.hc.connect:-1 com.google.android.gms.location.LocationClient.connect:-1 
,I/ActivityManager(  968): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4723 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,D/administrator(  968): Handling package changes for user 0
I/[LGHome]EVENT( 1892): [Launcher.java:5203:onStart()]onStart
,I/GKI_LINUX( 2001): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2001): GKI_destroy_task(): task [BTU] terminated
,I/bt-btif ( 2001): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 2001): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 2001): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2001): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService( 2001): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2001): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
I/[LGHome]EVENT( 1892): [Launcher.java:776:onResume()]onResume
D/BtSettings.ProfileConfig( 2001): Unable to read settings
D/BtSettings.ProfileConfig( 2001): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2001): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 2001): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 2001): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 2001): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 2001): 	at com.android.bluetooth.btservice.AdapterService.stopProfileServices(AdapterService.java:738)
D/BtSettings.ProfileConfig( 2001): 	at com.android.bluetooth.btservice.AdapterState$PendingCommandState.processMessage(AdapterState.java:529)
D/BtSettings.ProfileConfig( 2001): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 2001): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 2001): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 2001): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 2001): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 2001): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(183121376)( 2001): setProfileServiceState() - Stopping service com.android.bluetooth.hfp.HeadsetService
,D/LocationReminderManager( 4668): location cilent is connected.
,I/ActivityManager(  968): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=4741 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/[SystemUI]QSlideListController( 1391): onReceive = android.intent.action.PACKAGE_REMOVED
,D/BluetoothAdapterService( 2001): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2001): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 2001): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2001): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 2001): Not skipping com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService(183121376)( 2001): setProfileServiceState() - Stopping service com.android.bluetooth.a2dp.A2dpService
D/HeadsetService( 2001): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2001): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2001): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2001): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2001): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 2001): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(183121376)( 2001): setProfileServiceState() - Stopping service com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2001): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2001): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 2001): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2001): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 2001): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(183121376)( 2001): setProfileServiceState() - Stopping service com.android.bluetooth.hdp.HealthService
I/LGBluetoothHfpAdapter( 2001): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 2001): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 2001): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aea35e0
D/HeadsetStateMachine( 2001): Exit Disconnected: -1
,D/BluetoothHeadset( 1766): Proxy object disconnected
D/A2dpService( 2001): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2001): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2001): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 2001): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2001): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/BluetoothHeadset( 1766): Proxy object disconnected
D/BluetoothHeadset( 1766): Proxy object disconnected
D/A2dpStateMachine( 2001): Exit Disconnected: -1
W/BluetoothAdapterService( 2001): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(183121376)( 2001): setProfileServiceState() - Stopping service com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 2001): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2001): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 2001): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2001): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 2001): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(183121376)( 2001): setProfileServiceState() - Stopping service com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 2001): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2001): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2001): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2001): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 2001): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(183121376)( 2001): setProfileServiceState() - Stopping service com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2001): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2001): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2001): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2001): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 2001): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(183121376)( 2001): setProfileServiceState() - Stopping service com.broadcom.bt.service.sap.SapService
D/LGBluetoothA2dpAdapter( 2001): [BTUI] LGBluetoothA2dpAdapter cleanup
D/BluetoothAdapterService( 2001): getQuietmodeRadioCount = 0
W/LGBluetoothA2dpServiceJni( 2001): Cleaning up Bluetooth Handsfree callback object
W/BluetoothAdapterService( 2001): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 2001): getQuietmodeRadioCount = 0
D/LGBluetoothPowerControlManager( 2001): [BTUI] terminate
D/BtSettings.ProfileConfig( 2001): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 2001): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(183121376)( 2001): setProfileServiceState() - Stopping service com.broadcom.bt.service.ftp.FTPService
D/BluetoothManagerService(  968): Message: 31
D/BluetoothAdapterService( 2001): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2001): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2001): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2001): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2001): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aea35e0
W/BluetoothAdapterService( 2001): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(183121376)( 2001): setProfileServiceState() - Stopping service com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterState( 2001): Stopping profile services that were post enabled
D/HidService( 2001): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2001): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aea35e0
D/BluetoothAdapterService(183121376)( 2001): handleMessage() - Message: 1
,D/BluetoothAdapterService(183121376)( 2001): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(183121376)( 2001): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BluetoothAdapterState( 2001): isTurningOnRadio()=false
D/BluetoothAdapterState( 2001): isTurningOffRadio()=false
D/BluetoothAdapterState( 2001): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2001): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2001): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2001): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2001): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(183121376)( 2001): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/HealthService( 2001): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2001): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aea35e0
D/HeadsetStateMachine( 2001): Unbinding service...
D/HeadsetPhoneState( 2001): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 2001): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 2001): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 2001): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 2001): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2001): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 2001): [BTUI] LGBluetoothHfpAdapter cleanup
D/PanService( 2001): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2001): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aea35e0
D/BtGatt.DebugUtils( 2001): handleDebugAction() action=null
D/BtGatt.GattService( 2001): Received stop request...Stopping profile...
D/BtGatt.GattService( 2001): stop()
D/BtGatt.AdvertiseManager( 2001): advertise clients cleared
D/LGBluetoothGattAdapter( 2001): [BTUI] LGBluetoothGattAdapter cleanup
D/BluetoothAdapterService( 2001): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aea35e0
D/BluetoothMapService( 2001): Received stop request...Stopping profile...
D/BluetoothMapService( 2001): stop()
D/BluetoothMapEmailAppObserver( 2001): deinitObservers()
D/BluetoothMapEmailAppObserver( 2001): removeReceiver()
D/BluetoothAdapterService( 2001): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aea35e0
,I/[LGHome]LGActivityUtil( 1892): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/LocationReminderManager( 4668): [removeAllReminders]
D/BluetoothInputDevice( 4640): Proxy object disconnected
D/HidProfile( 4640): Bluetooth service disconnected
D/SapService( 2001): Received stop request...Stopping profile...
,D/SapService( 2001): Stopping Bluetooth SapService
D/LGBluetoothSapAdapter( 2001): [BTUI] LGBluetoothSapAdapter cleanup
D/LGBluetoothSapManager( 2001): [BTUI] terminateSapManager
,D/BluetoothPan( 4640): BluetoothPAN Proxy object disconnected
D/PanProfile( 4640): Bluetooth service disconnected
D/BluetoothMap( 4640): Proxy object disconnected
D/MapProfile( 4640): Bluetooth service disconnected
I/[LGHome]EVENT( 1892): [Launcher.java:929:onResume()]onResume end
I/Activity( 1892): Activity.onPostResume() called 
I/art     ( 1802): CheckpointMarkThreadRoots callback created = 0xaaf21b80
D/BluetoothAdapterService( 2001): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aea35e0
D/**BluetoothFTPService( 2001): Received stop request...Stopping profile...
D/**BluetoothFTPService( 2001): Stopping Bluetooth FTP Service
V/BluetoothFTPServiceJni( 2001): closeFtpServerNative
D/LgeBluetoothSimManager( 1766): [BTUI] SAP_DISABLE_EVT
D/BluetoothAdapterService( 2001): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aea35e0
D/BluetoothAdapterService(183121376)( 2001): handleMessage() - Message: 1
D/BluetoothAdapterService(183121376)( 2001): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(183121376)( 2001): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BluetoothAdapterState( 2001): isTurningOnRadio()=false
D/BluetoothAdapterState( 2001): isTurningOffRadio()=false
D/BluetoothAdapterState( 2001): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2001): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2001): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2001): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2001): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(183121376)( 2001): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(183121376)( 2001): handleMessage() - Message: 1
D/BluetoothAdapterService(183121376)( 2001): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService(183121376)( 2001): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BluetoothAdapterState( 2001): isTurningOnRadio()=false
D/BluetoothAdapterState( 2001): isTurningOffRadio()=false
D/BluetoothAdapterState( 2001): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2001): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2001): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2001): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2001): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(183121376)( 2001): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
I/BluetoothA2dpServiceJni( 2001): cleanupNative
I/GKI_LINUX( 2001): GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2001): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2001): GKI_destroy_task(): task [A2DP-MEDIA] terminated
D/**OppService( 2001): Received stop request...Stopping profile...
D/OppService( 2001): Stopping Bluetooth OppService
D/OppService( 2001): cleanup OPP Service
W/BluetoothOPPServiceJni( 2001): Cleaning up Bluetooth Opp Interface...
W/BluetoothOPPServiceJni( 2001): Cleaning up Bluetooth OPP callback object
D/OppService( 2001): remove callbacks and handler
D/LGBluetoothOppAdapter( 2001): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 2001): cleanup done
D/BluetoothAdapterService( 2001): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@aea35e0
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1391): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1391): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,W/[LGHome]LGWallpaperInfo( 1892): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1892): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
W/BluetoothHidServiceJni( 2001): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 2001): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService(183121376)( 2001): handleMessage() - Message: 1
D/BluetoothAdapterService(183121376)( 2001): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(183121376)( 2001): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BluetoothAdapterState( 2001): isTurningOnRadio()=false
D/BluetoothAdapterState( 2001): isTurningOffRadio()=false
D/BluetoothAdapterState( 2001): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2001): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2001): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2001): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2001): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(183121376)( 2001): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothHealthServiceJni( 2001): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2001): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 2001): Cleaning up Bluetooth Health object
D/BluetoothAdapterService(183121376)( 2001): handleMessage() - Message: 1
D/BluetoothAdapterService(183121376)( 2001): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(183121376)( 2001): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BluetoothAdapterState( 2001): isTurningOnRadio()=false
D/BluetoothAdapterState( 2001): isTurningOffRadio()=false
D/BluetoothAdapterState( 2001): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2001): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2001): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2001): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2001): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(183121376)( 2001): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothPanServiceJni( 2001): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2001): Cleaning up Bluetooth PAN callback object
I/SystemUI[Framework](  968): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
,D/InputDispatcher(  968): Focus entered window: Window{1e4cdf4d u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/PhoneWindowManagerEx(  968): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  968): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  968): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  968): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@301b2767,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  968): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/BluetoothAdapterService(183121376)( 2001): handleMessage() - Message: 1
D/BluetoothAdapterService(183121376)( 2001): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
W/GeofencerStateMachine( 1748): Ignoring removeGeofence because network location is disabled.
,D/BluetoothAdapterService(183121376)( 2001): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=true
D/BluetoothAdapterState( 2001): isTurningOnRadio()=false
D/BluetoothAdapterState( 2001): isTurningOffRadio()=false
D/BluetoothAdapterState( 2001): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2001): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2001): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2001): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2001): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(183121376)( 2001): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 2001): Handler(): got msg=4
D/BluetoothMapService( 2001): MAP Service closeService in
D/LGBluetoothMapAdapter( 2001): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 2001): MAP Service closeService out
D/BluetoothAdapterService(183121376)( 2001): handleMessage() - Message: 1
D/BluetoothAdapterService(183121376)( 2001): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(183121376)( 2001): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BluetoothAdapterState( 2001): isTurningOnRadio()=false
D/BluetoothAdapterState( 2001): isTurningOffRadio()=false
D/BluetoothAdapterState( 2001): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2001): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2001): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2001): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2001): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(183121376)( 2001): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/GCoreFlp( 1748): No location to return for getLastLocation()
D/BluetoothMapService( 2001): cleanup()
D/BluetoothMapService( 2001): MAP Service closeService in
D/LGBluetoothMapAdapter( 2001): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 2001): MAP Service closeService out
W/art     ( 4353): Suspending all threads took: 5.541ms
D/BluetoothAdapterService(183121376)( 2001): handleMessage() - Message: 1
D/BluetoothAdapterService(183121376)( 2001): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(183121376)( 2001): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
D/BluetoothAdapterState( 2001): isTurningOnRadio()=false
D/BluetoothAdapterState( 2001): isTurningOffRadio()=false
D/BluetoothAdapterState( 2001): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2001): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2001): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2001): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2001): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(183121376)( 2001): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothSAPServiceJni( 2001): ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 2001): ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterService(183121376)( 2001): handleMessage() - Message: 1
D/BluetoothAdapterService(183121376)( 200,1): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(183121376)( 2001): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, doUpdate=true
D/BluetoothAdapterState( 2001): isTurningOnRadio()=false
D/BluetoothAdapterState( 2001): isTurningOffRadio()=false
D/BluetoothAdapterState( 2001): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2001): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2001): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2001): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2001): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(183121376)( 2001): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothFTPService( 2001): cleanup FTP Service
V/BluetoothFTPServiceJni( 2001): closeFtpServerNative
V/BluetoothFTPServiceJni( 2001): cleanupNative
W/BluetoothFTPServiceJni( 2001): Cleaning up Bluetooth FTP Server Interface...
W/BluetoothFTPServiceJni( 2001): Cleaning up Bluetooth FTP callback object
D/BluetoothFTPService( 2001): BluetoothFtpBinder.cleanup()
D/BluetoothFTPService( 2001): cleanup done
D/BluetoothAdapterService(183121376)( 2001): handleMessage() - Message: 1
D/BluetoothAdapterService(183121376)( 2001): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(183121376)( 2001): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=10, doUpdate=true
D/BluetoothAdapterState( 2001): isTurningOnRadio()=false
D/BluetoothAdapterState( 2001): isTurningOffRadio()=false
D/BluetoothAdapterState( 2001): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2001): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2001): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BluetoothAdapterService(183121376)( 2001): onProfileServiceStateChange() - All profile services stopped...
D/OppService( 2001): cleanup OPP Service
D/OppService( 2001): remove callbacks and handler
D/LGBluetoothOppAdapter( 2001): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 2001): cleanup done
D/BluetoothAdapterState( 2001): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2001): Setting state to 10
I/BluetoothAdapterState( 2001): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService(183121376)( 2001): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService(  968): Message: 60
D/BluetoothManagerService(  968): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  968): Broadcasting onBluetoothStateChange(false) to 9 receivers.
,W/ResourcesManager( 4741): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/BluetoothAdapterState( 2001): Entering OffState
W/GCoreFlp( 1748): No location to return for getLastLocation()
D/BluetoothHeadset( 1766): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 4640): onBluetoothStateChange: up=false
,D/BluetoothPan( 4640): onBluetoothStateChange on: false
D/BluetoothPbap( 4640): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1766): onBluetoothStateChange: up=false
D/BluetoothHeadset(  968): onBluetoothStateChange: up=false
D/BluetoothA2dp(  968): onBluetoothStateChange: up=false
D/BluetoothMap( 4640): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1766): onBluetoothStateChange: up=false
I/LockScreenSettings( 4723): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/BluetoothAdapterService(183121376)( 2001): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3c798c36
I/[LGHome]EVENT( 1892): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/LocationReminderManager( 4668): [removeAllReminders] statusCode : 1000
D/LocationReminderManager( 4668): [removeAllReminders] Failed to remove reminder
I/[LGHome]LGPlusHomeDBManager( 1892): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1892): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/BluetoothManagerService(  968): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  968): Broadcasting onBluetoothServiceDown() to 8 receivers.
,D/BluetoothManagerService(  968): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService(  968): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService(  968): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2bc9c40d mBinding = false
I/ActivityManager(  968): Killing 4227:com.google.android.configupdater/u0a3 (adj 15): empty #11
I/art     ( 1802): CheckpointMarkThreadRoots callback created = 0xb042dab0
D/BluetoothManagerService(  968): Sending unbind request.
I/art     ( 1802): Background partial concurrent mark sweep GC freed 53586(3MB) AllocSpace objects, 0(0B) LOS objects, 40% free, 8MB/14MB, paused 1.200ms total 105.727ms
,W/ResourcesManager( 4707): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1892): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1892): [setNavigationBarColor] color=0x 0
W/InputMethodManagerService(  968): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/InputMethodManagerService(  968): Got RemoteException sending setActive(false) notification to pid 4012 uid 10317
I/Timeline( 1892): Timeline: Activity_idle id: android.os.BinderProxy@198c7482 time:61846
,D/BluetoothAdapterService(183121376)( 2001): onUnbind() - calling cleanup
D/BluetoothManagerService(  968): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapterService(183121376)( 2001): cleanup()
D/BluetoothAdapter( 1391): 807530964: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1391): 807530964: getState() :  mService = null. Returning STATE_OFF
D/LGBluetoothAPIService( 1819): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1819): Message: 2
D/LGBluetoothFeatureConfig( 4640): isPrivacyLogsEnabled : true
D/LGBluetoothAPIService( 1819): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@214e380f mBinding = false
,D/LGBluetoothAPIService( 1819): Sending unbind request.
I/ActivityManager(  968): Killing 4262:com.lge.eula/1000 (adj 15): empty #11
I/[SystemUI]QuickSettingsHandler( 1391): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1391): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
I/SystemUI[Framework](  968): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  968): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  968): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  968): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  968): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@301b2767,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  968): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/LGBluetoothUtils( 4640): [BTUI] resetProperty - success
E/LGBluetoothEventManager( 4640): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 4640): [BTUI] clear device connection state
,D/BluetoothAdapter( 1748): 929137038: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1748): 929137038: getState() :  mService = null. Returning STATE_OFF
,I/art     (  968): Explicit concurrent mark sweep GC freed 43823(2MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 23MB/35MB, paused 11.721ms total 543.901ms
,D/AuthorizationBluetoothService( 1748): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/libprocessgroup(  968): failed to open /acct/uid_10003/pid_4227/cgroup.procs: No such file or directory
W/libprocessgroup(  968): failed to open /acct/uid_1000/pid_4262/cgroup.procs: No such file or directory
,W/ContextImpl( 4640): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/KeyguardModel( 1391): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1391): createShortcutInfo...
D/KeyguardModel( 1391): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1391): createShortcutInfo...
W/ResourceType( 1391): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1391): Failure retrieving resources for com.android.mms: Resource ID #0x0
,D/DockEventReceiver( 4640): finishStartingService: stopping service
D/BluetoothAdapterService(183121376)( 2001): cleanup() - Cleaning up adapter native
I/bt-btif ( 2001): btif_shutdown_bluetooth()::btif_core_cb: state: 0, is_radio_req: 0, radio_ref_count: 0, dut_mode: 0, shutdown_pending: 0
I/GKI_LINUX( 2001): GKI_destroy_task(1): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/bt-btif ( 2001): HAL bt_hal_cbacks->thread_evt_cb
I/GKI_LINUX( 2001): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 2001): GKI_destroy_task(): task [BTIF] terminated
I/GKI_LINUX( 2001): GKI_destroy_task(2): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2001): GKI_destroy_task(1): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2001): GKI_destroy_task(0): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2001): GKI_exit_task 2 done
I/GKI_LINUX( 2001): GKI_exit_task 1 done
I/GKI_LINUX( 2001): GKI_exit_task 0 done
I/BluetoothServiceJni( 2001): cleanupNative: return from cleanup
W/LGBluetoothServiceJni( 2001): Cleaning up Bluetooth Service callback object
I/HotwordRecognitionRnr( 1950): Starting hotword detection.
,D/KeyguardModel( 1391): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1391): createShortcutInfo...
W/ResourceType( 1391): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1391): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1391): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1391): createShortcutInfo...
I/MicrophoneInputStream( 1950): mic_starting com.google.android.apps.gsa.speech.audio.u@14268f5b
V/AudioRecord( 1950): set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
V/AudioRecord( 1950): set(): mSessionId 23
W/ResourceType( 1391): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1391): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,V/AudioPolicyManager(  282): getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 23, flags 0
V/AudioPolicyManager(  282): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  282): isPlaybackThread 0,isRecordThread 1
D/audio_hw_primary(  282): adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb546dd40)
V/audio_hw_primary(  282): adev_open_input_stream: exit
V/AudioFlinger(  282): openInput_l() openInputStream returned input 0xb546dd40, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
D/KeyguardModel( 1391): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1391): createShortcutInfo...
V/AudioFlinger(  282): openInput_l() created record thread: ID 24 thread 0xb39e9000
V/AudioSystem(  282): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem( 1391): ioConfigChanged() event 3, ioHandle 24
I/AudioFlinger(  282): AudioFlinger's thread 0xb39e9000 ready to run
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioSystem( 1766): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem( 2001): ioConfigChanged() event 3, ioHandle 24
V/AudioPolicyService(  282): AudioCommandThread() adding update audio port list
V/AudioSystem( 3182): ioConfigChanged() event 3, ioHandle 24
V/AudioPolicyService(  282): inserting command: 9 at index 0, num commands 0
V/AudioSystem(  968): ioConfigChanged() event 3, ioHandle 24
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioSystem( 2702): ioConfigChanged() event 3, ioHandle 24
V/AudioPolicyService(  282): AudioCommandThread() processing update audio port list
V/AudioSystem( 1950): ioConfigChanged() event 3, ioHandle 24
D/audio_hw_primary(  282): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/AudioFlinger(  282): openRecord() lSessionId: 23 input 24
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioFlinger(  282): getOrphanEffectChain_l session 23 index -2
V/AudioFlinger(  282): acquiring 23 from 1950, for -1
V/AudioFlinger(  282):  added new entry for 23
D/LGBluetoothSettingsDBObserver( 2001): [BTUI] unregister observer for LG device name DB
D/BluetoothAdapterService(183121376)( 2001): cleanup() - Bluetooth process exited normally.
V/AudioRecord( 1950): start, sync event 0 trigger session 0
D/BluetoothAdapterService(183121376)( 2001): cleanup() done
,V/AudioRecord( 1950): mAudioRecord->start()
V/AudioFlinger(  282): RecordHandle::start()
V/AudioFlinger(  282): RecordThread::start event 0, triggerSession 0
V/AudioPolicyManager(  282): startInput() module primary->input primary(24)
V/AudioPolicyManager(  282): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  282): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  282): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  282): DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
V/AudioPolicyService(  282): AudioCommandThread() adding create patch delay 0
V/AudioPolicyService(  282): inserting command: 7 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing create audio patch
V/AudioFlinger::PatchPanel(  282): createAudioPatch() num_sources 1 num_sinks 1 handle 0
V/AudioFlinger::PatchPanel(  282): createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
V/AudioFlinger(  282): ThreadBase::setParameters() input_source=6;routing=-2147483644
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  282): in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
V/audio_hw_primary(  282): in_set_parameters: exit: status(0)
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb39e9000
V/AudioFlinger::PatchPanel(  282): createAudioPatch() status 0
V/AudioFlinger::PatchPanel(  282): createAudioPatch() added new patch handle 25 halHandle 0
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyManager(  282): setInputDevice() createAudioPatch returned 0 patchHandle 25
V/AudioPolicyManager(  282): addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
V/AudioPolicyService(  282): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  282): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyService(  282): AudioCommandThread() adding set parameter string hotword_active=1, io 24 ,delay 0
V/AudioPolicyService(  282): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing set parameters string hotword_active=1, io 24
V/AudioFlinger(  282): setParameters(): io 24, keyvalue hotword_active=1, calling pid 282
V/AudioFlinger(  282): ThreadBase::setParameters() hotword_active=1
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
I/art     ( 2001): System.exit called, status: 0
I/AndroidRuntime( 2001): VM exiting with result code 0, cleanup skipped.
D/KeyguardModel( 1391): handleShortcutListChanged...
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  282): in_set_parameters: enter: kvpairs=hotword_active=1
V/audio_hw_primary(  282): in_set_parameters: exit: status(0)
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb39e9000
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyManager(  282): AudioPolicyManager::startInput() input source = 1999
,D/KeyguardModel( 1391): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1391): createShortcutInfo...
D/KeyguardModel( 1391): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1391): createShortcutInfo...
I/MicrophoneInputStream( 1950): mic_started com.google.android.apps.gsa.speech.audio.u@14268f5b
W/ResourceType( 1391): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1391): Failure retrieving resources for com.android.mms: Resource ID #0x0
V/msm8974_platform(  282): platform_update_usecase_from_source: input source :6
D/audio_hw_primary(  282): start_input_stream: enter: stream(0xb546dd40)usecase(7: audio-record)
V/voice   (  282): voice_check_and_set_incall_rec_usecase: voice call not active
,V/audio_hw_primary(  282): start_input_stream: usecase(7)
I/NotificationService(  968): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
E/audio_hw_primary(  282): select_devices: enter and usecase(7)
V/msm8974_platform(  282): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
D/BackupManagerService(  968): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
V/msm8974_platform(  282): platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
V/msm8974_platform_lge(  282): LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
V/audio_hw_lge_primary(  282): LGE_exeption_scenario: enter and out: 0, in: 144
D/audio_hw_primary(  282): select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
E/audio_hw_primary(  282): enable_snd_device: enter  144
D/hardware_info(  282): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  282): enable_snd_device: snd_device(144: lg-vr-handset-mic)
V/msm8974_platform_lge(  282): LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
D/ACDB-LOADER(  282): ACDB -> send_audio_cal, acdb_id = 65, path =  1
D/ACDB-LOADER(  282): ACDB -> send_adm_topology
D/ACDB-LOADER(  282): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/JobSchedulerService(  968): Receieved: android.intent.action.PACKAGE_REMOVED
D/ACDB-LOADER(  282): ACDB -> send_asm_topology
D/ACDB-LOADER(  282): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  282): ACDB -> send_audtable
D/ACDB-LOADER(  282): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  282): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  282): ACDB -> send_audvoltable
D/ACDB-LOADER(  282): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  282): Failed to fetch the lookup information of the device 00000041 
E/ACDB-LOADER(  282): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  282): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  282): ACDB -> AUDIO_SET_AFE_CAL
D/KeyguardModel( 1391): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1391): createShortcutInfo...
W/ResourceType( 1391): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1391): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,V/audio_hw_primary(  282): enable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  282): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  282): enable_audio_route: apply mixer and update path: audio-record
D/KeyguardModel( 1391): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1391): createShortcutInfo...
V/audio_hw_primary(  282): enable_audio_route: exit
D/audio_hw_primary(  282): select_devices: done
V/audio_hw_primary(  282): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
D/TaskPersister(  968): removeObsoleteFile: deleting file=220_task.xml
D/PhoneStatusBar( 1391): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/PhoneStatusBar( 1391): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1391): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1391):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1391): , Keyguard show=false, IME shown=false, Panel expanded=false
V/audio_hw_primary(  282): start_input_stream: exit
W/ResourceType( 1391): No package identifier when getting value for resource number 0x00000000
D/BarTransitions( 1391): draw background and invalidate : color = fb000000
W/PackageManager( 1391): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/BarTransitions( 1391): draw background and invalidate : color = fbf1f1f1
D/KeyguardModel( 1391): package = com.lge.camera, class = com.lge.camera.CameraApp
V/AudioFlinger(  282): 2001 died, releasing its sessions
D/KeyguardModel( 1391): createShortcutInfo...
V/AudioFlinger(  282):  pid 1766 @ 0
V/AudioFlinger(  282):  pid 2702 @ 1
V/AudioFlinger(  282):  pid 3182 @ 2
V/AudioFlinger(  282):  pid 3182 @ 3
V/AudioFlinger(  282):  pid 1950 @ 4
,D/FMFRW_FmProxy( 1819): Fm Proxy object disconnected
D/LGBluetoothUserBindClient( 4640): [BTUI] onServiceDisconnected
D/BluetoothManagerService(  968): Message: 20
D/BluetoothManagerService(  968): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d0a0506:true
,D/AndroidRuntime( 4638): Shutting down VM
,I/ActivityManager(  968): Process com.android.bluetooth (pid 2001) has died
W/ActivityManager(  968): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
W/ActivityManager(  968): Scheduling restart of crashed service com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService in 11000ms
D/BluetoothAdapter( 4707): 183121376: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4707): 183121376: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothPermissionRequest( 4640): onReceive
D/LGBluetoothUtils( 4640): [BTUI] FileNotFound: readProperty
D/BluetoothDiscoverableTimeoutReceiver( 4640): cancelDiscoverableAlarm(): Enter
I/HotwordWorker( 1950): onReady
,I/ActivityManager(  968): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=4766 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1035, 4002, 1023} abi=armeabi-v7a
I/ActivityManager(  968): Killing 4283:com.google.android.talk/u0a61 (adj 15): empty #11
,D/KeyguardModel( 1391): handleShortcutListChanged...
,I/Timeline(  968): Timeline: Activity_windows_visible id: ActivityRecord{1cd1fdf5 u0 com.lge.launcher2/.Launcher t219} time:62275
W/libprocessgroup(  968): failed to open /acct/uid_10061/pid_4283/cgroup.procs: No such file or directory
W/OpenGLRenderer( 1892): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
W/OpenGLRenderer( 1892): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
,D/LCardEmulationManager( 1802): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1802): getDefaultRoute
W/ResourcesManager( 4766): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 4766): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4766): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
W/ResourcesManager( 4766): Asset path '/system/framework/com.broadcom.fm.jar' does not exist or contains no resources.
,W/ResourcesManager(  968): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/ActivityManager(  968): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4784 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 22.423ms
,V/LGMDMManager( 4707): Create singleton instance
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 20.478ms
D/BluetoothAdapterApp( 4766): Loading JNI Library
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 309us total 21.495ms
,I/AudioManager( 4707): getMode name:com.lge.qremote
,E/BluetoothServiceJni( 4766): [BTUI] JNI_OnLoad : ### LGBT_USE_BDT : TRUE ###
D/BluetoothAdapterApp( 4766): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@2eb8b66b Instance Count = 1
I/AudioManager( 4707): getMode name:com.lge.qremote
,E/UEI.SmartControl( 4784): Failed while opening the log file.
E/UEI.SmartControl( 4784): java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.lite/app_log/app.log: open failed: EROFS (Read-only file system)
E/UEI.SmartControl( 4784): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/UEI.SmartControl( 4784): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/UEI.SmartControl( 4784): 	at java.io.FileWriter.<init>(FileWriter.java:58)
E/UEI.SmartControl( 4784): 	at com.uei.f.c.a(Unknown Source)
E/UEI.SmartControl( 4784): 	at com.uei.f.c.a(Unknown Source)
E/UEI.SmartControl( 4784): 	at com.uei.f.c.<init>(Unknown Source)
E/UEI.SmartControl( 4784): 	at com.uei.f.c.a(Unknown Source)
E/UEI.SmartControl( 4784): 	at com.uei.control.core.QSApp.onCreate(Unknown Source)
E/UEI.SmartControl( 4784): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1011)
E/UEI.SmartControl( 4784): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4657)
E/UEI.SmartControl( 4784): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/UEI.SmartControl( 4784): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/UEI.SmartControl( 4784): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UEI.SmartControl( 4784): 	at android.os.Looper.loop(Looper.java:135)
E/UEI.SmartControl( 4784): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/UEI.SmartControl( 4784): 	at java.lang.reflect.Method.invoke(Native Method)
E/UEI.SmartControl( 4784): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/UEI.SmartControl( 4784): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/UEI.SmartControl( 4784): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4784): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/UEI.SmartControl( 4784): 	at libcore.io.Posix.open(Native Method)
E/UEI.SmartControl( 4784): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/UEI.SmartControl( 4784): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/UEI.SmartControl( 4784): 	... 18 more
D/UEI.SmartControl( 4784): Quickset Services start...
,I/UEI.SmartControl( 4784): Manufacture = LGE
D/UEI.SmartControl( 4784): File observer start...
E/UEI.SmartControl( 4784): IR Port is disabled: false
D/UEI.SmartControl( 4784): Starting file observer...
D/UEI.SmartControl( 4784): Extracting JNI libs...
D/UEI.SmartControl( 4784): --- this system supports 32-bit or 64-bit only
I/ActivityManager(  968): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=4804 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/BluetoothAdapterApp( 4766): onCreate
,I/LGBluetoothServiceJni( 4766): classInitNative: succeeds
,W/ResourceType(  968): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
D/BtSettings.ProfileConfig( 4766): [BTUI] HeadsetServiceis supported
D/BtSettings.ProfileConfig( 4766): Adding HeadsetService
D/BtSettings.ProfileConfig( 4766): [BTUI] A2dpServiceis supported
D/BtSettings.ProfileConfig( 4766): Adding A2dpService
D/UEI.SmartControl( 4784): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 4784): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 4784): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/BtSettings.ProfileConfig( 4766): [BTUI] HidServiceis supported
D/BtSettings.ProfileConfig( 4766): Adding HidService
D/BtSettings.ProfileConfig( 4766): [BTUI] HealthServiceis supported
D/BtSettings.ProfileConfig( 4766): Adding HealthService
D/LGBluetoothFeatureConfig( 4766): isSupportPan() :  mTargetOp=OPEN
I/[LGHome]EVENT( 1892): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
E/UEI.SmartControl( 4784): unzip: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.lite/files/libqs_jni.so: open failed: EROFS (Read-only file system)
,I/UEI.SmartControl( 4784): --- Selecting new region: 2
,I/UEI.SmartControl( 4784): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 4784): Platform has CIR...
D/UEI.SmartControl( 4784): NO CIR support, need to check package...
I/UEI.SmartControl( 4784): Model: LG-D722 uses JNI
D/UEI.SmartControl( 4784): QS Service created

```
