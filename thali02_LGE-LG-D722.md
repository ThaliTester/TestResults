#### Test 503880196b4ec73_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
D/LGMediaProvider( 3349): [MediaScanner] mUnmountReceiver ACTION_MEDIA_SCANNER_FINISHED : uri = file:///storage/emulated/0, path = /storage/emulated/0
--------- beginning of system
W/libprocessgroup(  845): failed to open /acct/uid_10014/pid_3202/cgroup.procs: No such file or directory
I/MusicBrowser( 2703): [MediaPlaybackService.java:3117:onReceive()] oooooo {intent=Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 }}
I/MusicBrowser( 2703): [MediaPlaybackService.java:3135:onReceive()] oooooo hasInternalMemory ==>> true
D/MusicBrowser( 2703): [MusicUtils.java:9350:isMediaRemoved()] oooooo action ==>> android.intent.action.MEDIA_SCANNER_FINISHED
I/MusicBrowser( 2703): [MediaPlaybackService.java:reloadQueue()] oooooo 
D/MusicBrowser( 2703): [MediaPlaybackService.java:reloadQueue()] oooooo id=-1
D/MusicBrowser( 2703): [MediaPlaybackService.java:reloadQueue()] oooooo mCardId=-1
D/MusicBrowser( 2703): [MediaPlaybackService.java:reloadQueue()] oooooo mPreferences.id=-1
D/MusicBrowser( 2703): [MediaPlaybackService.java:reloadQueue()] oooooo q=
D/MusicBrowser( 2703): [MediaPlaybackService.java:reloadQueue()] oooooo q.length=0
D/MusicBrowser( 2703): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.queuechanged}
I/MusicBrowser( 2703): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2703): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2703): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2703): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2703): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2703): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2703): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2703): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2703): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicBrowser( 2703): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicWidget( 2666): intentReceiver onReceive() action::com.lge.music.queuechanged
I/MusicBrowser( 2703): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/MusicWidget( 2666): beingMusicWidget_4x2() result::false
I/MusicWidget( 2666): beingMusicWidget_Quick() result::false
I/MusicWidget( 2666): beingMusicWidget_4x1() result::true
I/MusicWidget( 2666): send mDelayedStopHandler
I/MusicWidget( 2666): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2666): beingMusicWidget_Quick() result::false
D/MusicBrowser( 2703): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2703): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2703): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
D/MusicBrowser( 2703): [MediaPlaybackService.java:3375:notifyChange()] oooooo {what=com.lge.music.metachanged}
I/MusicBrowser( 2703): [MediaPlaybackService.java:3377:notifyChange()] oooooo 
D/MusicBrowser( 2703): [MediaPlaybackService.java:3407:notifyChange()] oooooo id : 0
D/MusicBrowser( 2703): [MediaPlaybackService.java:3408:notifyChange()] oooooo artist : null
D/MusicBrowser( 2703): [MediaPlaybackService.java:3409:notifyChange()] oooooo album : null
D/MusicBrowser( 2703): [MediaPlaybackService.java:3410:notifyChange()] oooooo track : null
D/MusicBrowser( 2703): [MediaPlaybackService.java:3411:notifyChange()] oooooo playing : false
D/MusicBrowser( 2703): [MediaPlaybackService.java:3412:notifyChange()] oooooo duration() : -1
D/MusicBrowser( 2703): [MediaPlaybackService.java:3413:notifyChange()] oooooo position() : -1
D/MusicBrowser( 2703): [MediaPlaybackService.java:3414:notifyChange()] oooooo ListSize : 0
I/MusicWidget( 2666): intentReceiver onReceive() action::com.lge.music.metachanged
I/MusicBrowser( 2703): [MediaPlaybackService.java:3426:notifyChange()] oooooo mRemoteControlClient.editMetadata :: META_CHANGED 
I/MusicWidget( 2666): beingMusicWidget_4x2() result::false
I/MusicBrowser( 2703): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=false}
I/MusicWidget( 2666): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2703): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/MusicWidget( 2666): beingMusicWidget_4x1() result::true
I/MusicWidget( 2666): send mDelayedStopHandler
I/MusicWidget( 2666): performViewUpdater handleMessage() msg.what::3
I/MusicWidget( 2666): beingMusicWidget_Quick() result::false
I/MusicBrowser( 2703): [MediaPlaybackService.java:9999:run()] oooooo AlbumImageUpdater() run :: Start
I/MusicBrowser( 2703): [MediaPlaybackService.java:10051:run()] oooooo AlbumImageUpdater() run :: End
D/MusicBrowser( 2703): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2703): [MediaPlaybackService.java:updateGroupIndexData()] oooooo 
I/MusicBrowser( 2703): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2703): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2703): [GroupIndexApi.java:groupingIndexDataProviderStart()] oooooo 
I/MusicBrowser( 2703): [GroupingIndexDataProvider.java:101:doInBackground()] oooooo mIsMusicPickerMode = false
V/CloudHub( 3552): [DATABASE][DBConnection|open] open database
E/CloudHub( 3552): [DATABASE][DBConnection|getUserId] User id: 0
E/CloudHub( 3552): [DATABASE][DBConnection|getDatabasePath] Database path: /data/user/0/com.lge.cloudhub/databases/cloudhub.db
V/CloudHub( 3552): [SERVICE][CloudHubReceiver|queryUploadCount] # of contents to upload: 0
,V/DownloadManager( 3349): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3349): created cursor android.database.sqlite.SQLiteCursor@3546796d on behalf of 3552
V/CloudHub( 3552): [SERVICE][CloudHubReceiver|queryDownloadCount] # of contents to download: 0
I/VRBookmarkProvider( 3496): [BookmarkProvider.java:530:handleMessage()-[Thread:Other] -- syncTable() START --
I/ActivityManager(  845): Start proc com.lge.gnss.airtest for broadcast com.lge.gnss.airtest/.GnssAirTestReceiver: pid=3576 uid=10054 gids={50054, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  845): Killing 3235:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/MusicWidget( 2666): performViewUpdater handleMessage() msg.what::0
I/MusicWidget( 2666): beingMusicWidget_4x1() result::true
I/MusicWidget( 2666): performUpdate()_4x1
I/MusicWidget( 2666): defaultAppWidget()_4x1
I/MusicWidget( 2666): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2666): 4x1_currentTheme :: null
I/MusicWidget( 2666): getCurrentTheme : com.lge.launcher2.theme.optimus
I/MusicWidget( 2666): setDefaultViewLayoutId()_4x1
I/MusicWidget( 2666): appWidgetViewUpdate()_4x1
I/MusicWidget( 2666): linkButtons()_4x1
W/libprocessgroup(  845): failed to open /acct/uid_1000/pid_3235/cgroup.procs: No such file or directory
I/MusicWidget( 2666): pushUpdate()_4x1
I/MusicWidget( 2666): performViewUpdater handleMessage() msg.what::1
I/MusicWidget( 2666): beingMusicWidget_4x2() result::false
I/VRBookmarkProvider( 3496): [BookmarkProvider.java:532:handleMessage()-[Thread:Other] -- syncTable() END --
D/AirTest ( 3576): Set airtest_enable to false
I/ActivityManager(  845): Killing 3257:com.lge.clock/u0a10 (adj 15): empty #11
I/[LgeWidgetLib]LgeAppWidgetHostView( 1981): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 1981): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
W/libprocessgroup(  845): failed to open /acct/uid_10010/pid_3257/cgroup.procs: No such file or directory
V/LGSC    ( 2779): [104] 401
D/AndroidRuntime( 3582): 
D/AndroidRuntime( 3582): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3582): CheckJNI is OFF
I/ActivityManager(  845): Start proc com.lge.lgfota.permission for broadcast com.lge.lgfota.permission/.DmcTargetValidationReceiver: pid=3599 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
D/TARGETVALIDLATION_RECEIVER( 3599): TargetValidationReceiver_ACTION_BOOT_COMPLETETED Received
D/TARGETVALIDLATION_RECEIVER( 3599): updateFlag = new File(TARGET_FLAG_PATH)
D/TARGETVALIDLATION_RECEIVER( 3599): Do Not display result dialog. it is not used Update Tool!!
I/ActivityManager(  845): Killing 3283:com.lge.appbox.client:SingleBinaryService/u0a11 (adj 15): empty #11
W/libprocessgroup(  845): failed to open /acct/uid_10011/pid_3283/cgroup.procs: No such file or directory
V/LGSC    ( 1814): [101] 102, action=android.intent.action.BOOT_COMPLETED, iccState=null
W/ContextImpl( 2924): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.qualcomm.atfwd.AtFwdAutoboot.onReceive:24 android.app.ActivityThread.handleReceiver:2663 
E/AtFwd AutoBoot( 2924): AtFwd Auto Boot Started Successfully
I/GoogleHttpClient( 2089): GMS http client unavailable, use old client
I/ActivityManager(  845): Start proc com.lge.defaultaccount for broadcast com.lge.defaultaccount/.receiver.ReceiverBootUp: pid=3628 uid=10062 gids={50062, 9997} abi=armeabi-v7a
D/AndroidRuntime( 3582): Calling main entry com.android.commands.am.Am
I/ActivityManager(  845): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  845): setTaskToReturnTo : TaskRecord{1cc7c244 #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  845): setTaskToReturnTo : TaskRecord{1cc7c244 #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  845): AppWindowTokenEx init.. 
D/ContextHelper(  845): convertTheme. context->name=com.example.hello themeResourceId=16973833
I/[LGHome]EVENT( 1981): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  845): Focus left window: Window{37a4a2e9 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 3582): Shutting down VM
I/InsertAccount( 3628): The account already exists
D/SplitWindow(  845): check instance of lgWin Window{21e02cae u0 Starting com.example.hello}
I/ActivityManager(  845): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3648 uid=10030 gids={50030, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/ThermalEngine(  298): Sensor:pa_therm0:30000 mC
I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 22.284ms
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 21.119ms
I/[LGHome]EVENT( 1981): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 22.313ms
I/MicrophoneInputStream( 2059): mic_close com.google.android.apps.gsa.speech.audio.u@3497551a
I/HotwordDetector( 2059): Closing mic
V/AudioRecord( 2059): stop()
D/AudioRecord( 2059): AudioRecord->stop()
V/AudioFlinger(  286): RecordHandle::stop()
V/AudioFlinger(  286): RecordThread::stop
V/AudioFlinger(  286): Record stopped OK
V/AudioPolicyManager(  286): stopInput() input 17
V/AudioPolicyService(  286): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  286): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  286): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  286): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  286): ThreadBase::setParameters() routing=0
V/AudioFlinger(  286): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  286): processConfigEvents_l() remaining events 1
V/AudioFlinger(  286): processConfigEvents_l() DONE thread 0xb3880000
D/audio_hw_primary(  286): in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
I/ActivityManager(  845): Start proc com.lge.hiddenmenu for broadcast com.lge.hiddenmenu/.kddi_only.sms_setting.AssistReceiver: pid=3665 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  845): Killing 3300:com.lge.appbox.client/u0a11 (adj 15): empty #11
V/audio_hw_primary(  286): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  286): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  286): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  286): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  286): disable_audio_route: exit
E/audio_hw_primary(  286): disable_snd_device: enter 144
D/hardware_info(  286): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  286): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  286): stop_input_stream: exit: status(0)
V/audio_hw_primary(  286): in_standby: exit:  status(0)
V/AudioFlinger(  286): RecordThread: loop stopping
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioPolicyManager(  286): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  286): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  286): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  286): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioPolicyService(  286): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  286): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  286): setParameters(): io 17, keyvalue hotword_active=0, calling pid 286
V/AudioFlinger(  286): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  286): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  286): RecordThread: loop starting
V/AudioFlinger(  286): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  286): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  286): in_set_parameters: exit: status(0)
V/AudioFlinger(  286): processConfigEvents_l() DONE thread 0xb3880000
V/AudioFlinger(  286): RecordThread: loop stopping
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioRecord( 2059): stop()
V/AudioRecord( 2059): stop()
V/AudioRecord( 2059): stop()
V/AudioFlinger(  286): RecordHandle::stop()
V/AudioFlinger(  286): releasing 16 from 2059 for -1
V/AudioFlinger(  286):  decremented refcount to 0
V/AudioFlinger(  286): RecordThread::stop
V/AudioFlinger(  286): purging stale effects
V/AudioPolicyManager(  286): releaseInput() 17
V/AudioPolicyManager(  286): closeInput(17)
V/AudioFlinger(  286): closeInput() 17
V/AudioSystem(  286): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  286): ThreadBase::exit
V/AudioFlinger(  286): RecordThread: loop starting
V/AudioSystem( 3321): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  286): RecordThread 0xb3880000 exiting
,D/audio_hw_primary(  286): adev_close_input_stream: enter:stream_handle(0xb546e240)
D/audio_hw_primary(  286): in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
V/audio_hw_primary(  286): in_standby: exit:  status(0)
V/AudioPolicyService(  286): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  286): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioPolicyManager(  286): releaseInput() exit
V/AudioFlinger(  286): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  286): removeClient_l() pid 2059, calling pid 286
V/AudioSystem( 2703): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  845): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1407): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1814): ioConfigChanged() event 4, ioHandle 17
I/HotwordRecognitionRnr( 2059): Stopping hotword detection.
V/AudioSystem( 2059): ioConfigChanged() event 4, ioHandle 17
I/HotwordRecognitionRnr( 2059): Hotword detection finished
I/[LGHome]EVENT( 1981): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  845): Starting window displayed
I/SystemUI[Framework](  845): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
W/PhoneWindowManagerEx(  845): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  845): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  845): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  845): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@104eac1e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  845): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1407): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1407): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1407):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1407): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1407): draw background and invalidate : color = 3000000
D/BarTransitions( 1407): draw background and invalidate : color = 6060606
W/libprocessgroup(  845): failed to open /acct/uid_10011/pid_3300/cgroup.procs: No such file or directory
V/AlarmManager(  845): ELAPSED_WAKEUP set : Alarm{33e1b3c8 type 2 when 48436 com.android.providers.calendar} when 48436
V/AudioFlinger(  286): thread 0xb56eb000 type 0 TID 1293 going to sleep
V/AudioFlinger(  286): thread 0xb5735000 type 0 TID 1295 going to sleep
V/AudioFlinger(  286): thread 0xb5651000 type 0 TID 1292 going to sleep
D/ContextHelper( 3648): convertTheme. context->name=com.example.hello themeResourceId=16973833
W/ResourcesManager( 3665): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 3665): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[SMS_AD]( 3665): Intent action: android.intent.action.BOOT_COMPLETED
I/[SMS_AD]( 3665): Intent action: android.intent.action.BOOT_COMPLETED
I/ActivityManager(  845): Killing 3420:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
I/InsertAccount( 3628): The account info in contact DB already exists
I/WebViewFactory( 3648): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/WeatherAncestor( 2688): 2 : onReceive, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 20:20:36
I/ActivityManager(  845): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3688 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup(  845): failed to open /acct/uid_10069/pid_3420/cgroup.procs: No such file or directory
D/UpdateThreadPoolManager( 2688): 2 : This is isUpdating : false
D/Weather_cast( 2688): 2 : set auto-update time : 11/23 23:20
D/WeatherAncestor( 2688): 2 : onReceive has processed, action: android.intent.action.BOOT_COMPLETED, Time(hour:min:sec) 20:20:36
D/WeatherService( 2688): 2 : onStartCommand, intent!=null, action: android.intent.action.BOOT_COMPLETED
I/LibraryLoader( 3648): Time to load native libraries: 2 ms (timestamps 8806-8808)
I/LibraryLoader( 3648): Expected native library version number "",actual native library version number ""
I/ActivityManager(  845): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.LockSettingsReceiver: pid=3706 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  845): Killing 3439:com.android.settings/1000 (adj 15): empty #11
V/WebViewChromiumFactoryProvider( 3648): Binding Chromium to main looper Looper (main, tid 1) {a315242}
I/LibraryLoader( 3648): Expected native library version number "",actual native library version number ""
I/chromium( 3648): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3648): Initializing chromium process, singleProcess=true
W/art     ( 3648): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 3648): ApplicationContext is null in ApplicationStatus
W/chromium( 3648): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 3648): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
W/ActivityManager(  845): getTasks: caller 10074 does not hold GET_TASKS; limiting output
W/libprocessgroup(  845): failed to open /acct/uid_1000/pid_3439/cgroup.procs: No such file or directory
D/Weather.Utils( 2688): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2688): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2688): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
E/libEGL  ( 3648): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 3648): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 3648): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3648): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 3648): Build Date: 03/02/15 Mon
I/Adreno-EGL( 3648): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 3648): Remote Branch: 
I/Adreno-EGL( 3648): Local Patches: 
I/Adreno-EGL( 3648): Reconstruct Branch: 
W/ResourcesManager( 3688): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/LockScreenSettings( 3706): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
D/CalendarProvider2( 3688): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@f886051
D/CalendarProvider2( 3688): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 3688): Created com.android.providers.calendar.CalendarAlarmManager@a315242(com.android.providers.calendar.CalendarProvider2@f886051)
V/AudioPolicyService(  286): registerClient() client 0xb57e7700, uid 10030
I/LockScreenSettings( 3706): Received Broadcast : android.intent.action.BOOT_COMPLETED
D/BluetoothManagerService(  845): Message: 20
D/BluetoothManagerService(  845): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e3d065b:true
D/BluetoothAdapter( 3648): 739229871: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  845): Start proc com.lge.springcleaning for broadcast com.lge.springcleaning/.receiver.BootCompleteReceiver: pid=3741 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  845): Killing 3470:com.android.managedprovisioning/u0a111 (adj 15): empty #11
W/libprocessgroup(  845): failed to open /acct/uid_10111/pid_3470/cgroup.procs: No such file or directory
,I/InsertAccount( 3628): The account info in calendar DB already exists
I/Process ( 3628): Sending signal. PID: 3628 SIG: 9
,I/ActivityManager(  845): Process com.lge.defaultaccount (pid 3628) has died
,D/BootCompleteReceiver( 3741): hasclipTray = true
W/ContextImpl( 3741): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.springcleaning.receiver.BootCompleteReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2663 
,I/ActivityManager(  845): Start proc com.lge.springcleaning:AppCleanupService for service com.lge.springcleaning/.service.AppCleanupService: pid=3760 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
W/art     ( 3648): Attempt to remove local handle scope entry from IRT, ignoring
,I/ActivityManager(  845): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3778 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
W/AwContents( 3648): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 3648): CordovaWebView is running on device made by: LGE
,W/art     ( 3648): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3648): Attempt to remove local handle scope entry from IRT, ignoring
V/AppCleanupService( 3760): registerAlarm
D/AppCleanupService( 3760): noticeInterval = 2591999999
D/AppCleanupService( 3760): notiDateStr = 2015-12-20 22:35:42
,D/AppCleanupService( 3760): noticeStart = 2015-12-20 22:35:42
D/AppCleanupService( 3760): noticeStart = 1450647342000
D/AppUsageDbAdapter( 3760): initPreloadedAppToTheDB() : row count = 102
,I/Activity( 3648): Activity.onPostResume() called 
,D/OpenGLRenderer( 3648): Render dirty regions requested: true
I/OpenGLRenderer( 3648): Initialized EGL, version 1.4
D/OpenGLRenderer( 3648): Enabling debug mode 0
,D/Atlas   ( 3648): Validating map...
,D/SplitWindow(  845): check instance of lgWin Window{69c5227 u0 com.example.hello/com.example.hello.MainActivity}
E/UpdateRequestReceiver( 3778): ignoring update request
,W/chromium( 3648): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
E/UpdateRequestReceiver( 3778): ignoring update request
,D/InputDispatcher(  845): Focus entered window: Window{69c5227 u0 com.example.hello/com.example.hello.MainActivity}
E/UpdateRequestReceiver( 3778): ignoring update request
E/UpdateRequestReceiver( 3778): ignoring update request
,E/UpdateRequestReceiver( 3778): ignoring update request
,E/UpdateRequestReceiver( 3778): ignoring update request
W/InputMethodManagerService(  845): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/Timeline( 3648): Timeline: Activity_idle id: android.os.BinderProxy@12edf93e time:49519
,I/ActivityManager(  845): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseSIMObserver: pid=3824 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  845): Killing 3496:com.lge.voicerecorder/u0a34 (adj 15): empty #11
I/ActivityManager(  845): Displayed com.example.hello/.MainActivity: +1s341ms
,W/libprocessgroup(  845): failed to open /acct/uid_10034/pid_3496/cgroup.procs: No such file or directory
,I/Timeline(  845): Timeline: Activity_windows_visible id: ActivityRecord{22d69f2d u0 com.example.hello/.MainActivity t220} time:49614
W/BindingManager( 3648): Cannot call determinedVisibility() - never saw a connection for the pid: 3648
,D/SIMObserver( 3824): action:android.intent.action.BOOT_COMPLETED
D/SIMObserver( 3824): handle ACTION_BOOT_COMPLETED
,I/chromium( 3648): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/ActivityManager(  845): Killing 2293:com.google.android.gms/u0a6 (adj 15): empty #11
,W/libprocessgroup(  845): failed to open /acct/uid_10006/pid_2293/cgroup.procs: No such file or directory
,E/QcrilMsgTunnelAutoboot( 2348): Received Intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.qualcomm.qcrilmsgtunnel/.QcrilMsgTunnelAutoboot (has extras) } canStartService = false
,D/PhoneInterfaceManager( 1814): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
D/PhoneInterfaceManager( 1814): [PhoneIntfMgr] hasIccCardUsingSlotId, sub: -1, result: false
D/JsMessageQueue( 3648): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  845): Start proc com.google.android.gms for broadcast com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver: pid=3846 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,E/AndroidProtocolHandler( 3648): Unable to open asset URL: file:///android_asset/www/jxcore.js
W/ResourcesManager( 3846): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3846): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 3846): VM with version 2.1.0 has multidex support
I/MultiDex( 3846): install
I/MultiDex( 3846): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 3846): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/ActivityThread( 3846): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3846): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@134ebe5a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3846): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 3846): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 3846): com.google.android.gms: cancel(39789) by com.google.android.gms
D/jxcore_app_log( 3648): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1627367936
,D/JX-Cordova( 3648): jxcore cordova android initializing
D/NativeLibraryUtils( 3846): Install completed successfully. count=13 extracted=0
,W/jxcore-log( 3648): Initializing JXcore engine
W/jxcore-log( 3648): JXcore engine is ready
W/jxcore-log( 3648): Starting JXcore engine
,W/InstanceID/Rpc( 3846): Found 10006
,D/FileApkUtils( 3846): Spent 70ms computing apk sha1.
,D/FileApkUtils( 3846): Module already staged or being staged:chimera-modules/MapsModule.apk
I/art     ( 3846): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d93aca1818df11c4cd5bccf493ad94e2b544d57a@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
D/DexOptUtils( 3846): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 3846): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
,W/m.example.hello( 3648): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5636]" dev="sockfs" ino=5636 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 3648): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 3648): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5775]" dev="sockfs" ino=5775 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/m.example.hello( 3648): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 3648): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 3648): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[18340]" dev="sockfs" ino=18340 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
D/GmsModuleFndr( 3846): Beginning GMS chimera module scan
,D/GCM     ( 3846): COMPAT: Multi user not supported
,W/jxcore-log( 3648): Platform android
W/jxcore-log( 3648): 
W/jxcore-log( 3648): Process ARCH arm
W/jxcore-log( 3648): 
,D/GCM     ( 2089): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,I/GCoreUlr( 3846): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1784): DispatchingService.onCreate()
,I/CheckinService( 3846): Checkin interval check for package: unspecified last checkin: 1448298640735 min interval config: 0 actual interval: 7798231
,I/jxcore-log( 3648): JXcore Cordova bridge is ready!
I/jxcore-log( 3648): 
W/jxcore-log( 3648): JXcore engine is started
D/GmsModuleFndr( 3846): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/ChimeraCfgMgr( 3846): Beginning module configuration check
,D/ChimeraCfgMgr( 3846): Module APKs unchanged, check complete
I/CheckinService( 3846): Disabling old GoogleServicesFramework version
I/art     ( 3846): CheckpointMarkThreadRoots callback created = 0xb04b4560
,E/jxcore-log( 3648): >> LGE-LG-D722
E/jxcore-log( 3648): 
I/art     ( 1784): Explicit concurrent mark sweep GC freed 15097(977KB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 11MB/18MB, paused 1.359ms total 96.071ms
,I/jxcore-log( 3648): Total memory 906309632
I/jxcore-log( 3648): 
I/jxcore-log( 3648): Free memory 25051136
I/jxcore-log( 3648): 
I/jxcore-log( 3648): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3648): 
I/jxcore-log( 3648): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3648): 
D/SystemUpdateService( 3846): onCreate
I/jxcore-log( 3648): userPath [ 'www' ]
I/jxcore-log( 3648): 
I/jxcore-log( 3648): Size 720 1196
I/jxcore-log( 3648): 
I/jxcore-log( 3648): Screen Brightness 255
I/jxcore-log( 3648): 
E/jxcore-log( 3648): Dummy Error Log.
E/jxcore-log( 3648): 
,I/art     ( 3846): CheckpointMarkThreadRoots callback created = 0xb04b4540
D/SystemUpdateService( 3846): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
V/AuthZen ( 3846): Handling intent: android.intent.action.BOOT_COMPLETED
,W/art     ( 3846): Suspending all threads took: 14.506ms
I/GCoreUlr( 1784): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
I/art     ( 3846): Background partial concurrent mark sweep GC freed 15112(1083KB) AllocSpace objects, 8(128KB) LOS objects, 39% free, 10MB/16MB, paused 29.579ms total 124.315ms
,D/AuthZenEventHandler( 3846): Handling event: android.intent.action.BOOT_COMPLETED
I/SystemUpdateService( 3846): cancelUpdate (empty URL)
I/SystemUpdateService( 3846): active receiver: disabled
,I/NotificationManager( 3846): com.google.android.gms: cancel(2130838130) by com.google.android.gms
,I/NotificationManager( 3846): com.google.android.gms: cancel(2130838131) by com.google.android.gms
V/GLSActivity( 2089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 3846): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
I/art     ( 3846): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.h.c>
,D/ChimeraCfgMgr( 3846): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/CheckinService( 3846): Checking schedule, now: 1448306439236 next: 1448825889681
I/CheckinService( 3846): active receiver: disabled
,D/ChimeraCfgMgr( 3846): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/GCoreUlr( 1784): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
D/SystemUpdateService( 3846): onDestroy
,I/GCoreUlr( 1784): Unbound from all location providers
I/art     ( 2089): Explicit concurrent mark sweep GC freed 4273(229KB) AllocSpace objects, 2(32KB) LOS objects, 40% free, 11MB/18MB, paused 4.850ms total 96.902ms
,W/BaseAppContext( 3846): Using Auth Proxy for data requests.
V/GLSActivity( 2089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Kids    ( 3846): [AbstractKidsOperation] Invalid device state 3
,I/Kids    ( 3846): [KidAccountFixer] No network connection
I/AuthZen ( 3846): Fetching signing key...
,I/AuthZen ( 3846): Signing key fetched successfully!
,W/BaseAppContext( 3846): Using Auth Proxy for data requests.
D/a       ( 3846): Opening database auth.proximity.permit_store...
,D/AuthZenTransactionCache( 3846): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 3846): Clearing transaction cache
I/art     (  845): Explicit concurrent mark sweep GC freed 29719(1435KB) AllocSpace objects, 8(317KB) LOS objects, 33% free, 22MB/34MB, paused 3.081ms total 179.938ms
,I/art     (  845): WaitForGcToComplete blocked for 115.348ms for cause Explicit
I/jxcore-log( 3648): getBuffer is called!!!!
I/jxcore-log( 3648): 
,I/art     (  845): Explicit concurrent mark sweep GC freed 2429(121KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 1.807ms total 124.359ms
,I/GCoreUlr( 1784): DispatchingService.onDestroy()
I/GCoreUlr( 1784): Stopping handler for UlrDispSvcFast
,W/GCoreFlp( 1784): No location to return for getLastLocation()
W/FusedLocationProvider( 3846): location=null
I/GCoreUlr( 1784): Unbound from all location providers
I/NotificationManager( 3846): com.google.android.gms: cancel(10436) by com.google.android.gms
W/Auth    ( 2089): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,W/GCoreFlp( 1784): No location to return for getLastLocation()
W/FusedLocationProvider( 3846): location=null
V/GLSActivity( 2089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GmsCoreStatsServiceLauncher( 3846): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
D/PersistentNotificationBroadcastReceiver( 2089): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/ActivityManager(  845): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3929 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 3929): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  845): Waited long enough for: ServiceRecord{1e787fe3 u0 com.lge.sizechangable.musicwidget.widget/.service.MusicWidgetUpdater}
,I/Babel_SMS( 3929): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 3929): MmsConfig.loadMmsSettings
I/Babel_SMS( 3929): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 3929): MmsConfig.loadFromDatabase
,E/Babel_SMS( 3929): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 3929): MmsConfig.loadFromResources
E/Babel_SMS( 3929): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 3929): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 3929): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 3929): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 3929): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 3929): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 3929): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 3929): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 3929): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 3929): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 3929): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 3929): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 3929): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 3929): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 3929): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 3929): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 3929): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 3929): found sensor: Motion Accel, handle=46
I/art     ( 3929): CheckpointMarkThreadRoots callback created = 0xb042d540
,W/Settings( 3929): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 3929): startup - clean
I/art     ( 3929): CheckpointMarkThreadRoots callback created = 0xb042d520
I/Babel   ( 3929): deleted: false for 0
,W/AudioCapabilities( 3929): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 3929): Unsupported mime audio/adpcm
W/AudioCapabilities( 3929): Unsupported mime audio/g726
W/AudioCapabilities( 3929): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 3929): Unsupported mime audio/wma-voice
W/VideoCapabilities( 3929): Unsupported mime video/mjpg
W/VideoCapabilities( 3929): Unsupported mime video/theora
,I/ActivityManager(  845): Waited long enough for: ServiceRecord{1afed779 u0 com.lge.sizechangable.weather/.service.WeatherService}
,W/AudioCapabilities( 3929): Unsupported mime audio/evrc
W/AudioCapabilities( 3929): Unsupported mime audio/qcelp
W/VideoCapabilities( 3929): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 3929): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 3929): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3929): Unsupported mime audio/evrc
W/VideoCapabilities( 3929): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 3929): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 3929): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3929): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 3929): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 3929): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 3929): onServiceConnected
,W/Babel   ( 3929): Attempted to change video mute state without an active call.
I/NotificationManager( 3929): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/ActivityManager(  845): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3959 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  845): Killing 3530:com.lge.drmservice/u0a51 (adj 15): empty #11
W/CursorWrapperInner( 3552): Cursor finalized without prior close()
,W/libprocessgroup(  845): failed to open /acct/uid_10051/pid_3530/cgroup.procs: No such file or directory
,W/ResourcesManager( 3959): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3959): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 3959): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/System  ( 3959): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3959): Installed default security provider GmsCore_OpenSSL
,W/art     ( 3959): Suspending all threads took: 5.277ms
,W/ResourcesManager( 3959): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 3959): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     ( 3959): CheckpointMarkThreadRoots callback created = 0xb042dbe0
,I/art     ( 3959): CheckpointMarkThreadRoots callback created = 0xb042dbd0
,E/YouTube MDX( 3959): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,I/dex2oat ( 3995): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-1967837716.jar --oat-fd=28 --oat-location=/data/data/com.google.android.youtube/cache/ads-1967837716.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
D/libc-netbsd( 3959): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 3959): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3959): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
I/dex2oat ( 3995): dex2oat took 128.893ms (threads: 4)
,I/ThermalEngine(  298): Sensor:pa_therm0:31000 mC
,I/NotificationManager( 3959): com.google.android.youtube: cancel(2) by com.google.android.youtube
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,D/PowerService( 1908): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1407): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
W/ContextImpl( 3959): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
I/[SystemUI]LGPowerUI( 1407): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1407): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1407): On Skip Timer : true
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 3959): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3959): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/InstanceID/Rpc( 3959): Found 10006
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 3959): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,I/ActivityManager(  845): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4057 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/sensors_hal_Time(  845): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  845): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  845): tsOffsetIs: Apps: 53792251026; DSPS: 1860435; Offset : -2996321852
,I/art     (  310): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 21.134ms
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 20.328ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 20.544ms
,I/NotificationManager( 3959): com.google.android.youtube: cancel(10436) by com.google.android.youtube
I/ActivityManager(  845): Killing 3552:com.lge.cloudhub/u0a49 (adj 15): empty #11
,W/libprocessgroup(  845): failed to open /acct/uid_10049/pid_3552/cgroup.procs: No such file or directory
W/ActivityManager(  845): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4057): getAccountsCursor
,V/GLSActivity( 2089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 4057): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  845): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 4057): Error finding the version of the Email provider.....
E/Gmail   ( 4057): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4057): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4057): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4057): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4057): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4057): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4057): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 4057): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 4057): We do not support migrating this version of the Email provider.
I/Gmail   ( 4057): getAccountsCursor
V/GLSActivity( 2089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  845): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/SearchBackgroundTaskFac( 2059): refreshing internal icing corpora
,I/Gmail   ( 4057): Observing account changes for notifications
I/ActivityManager(  845): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4114 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,W/ActivityManager(  845): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  845): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  845): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/ActivityThread( 4057): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@3c7e3afa that was originally bound here
E/ActivityThread( 4057): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@3c7e3afa that was originally bound here
E/ActivityThread( 4057): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 4057): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 4057): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 4057): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 4057): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4057): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4057): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4057): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4057): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4057): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4057): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4057): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4057): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4057): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4057): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4057): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager(  845): Unbind failed: could not find connection for android.os.BinderProxy@32dfd3ec
I/UpdateIcingCorporaServi( 2059): Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
,V/[BNRBootReceiver]( 4114): boot receiver action = android.intent.action.BOOT_COMPLETED
,V/[BNRBootReceiver]( 4114): set property sys.lge.bnrd = 1
V/[BNRBootReceiver]( 4114): End of BootComplted IF
V/[BNRBootReceiver]( 4114): Boot Receiver Return
V/[BNRBootCompletedThread]( 4114): run
,W/linker  ( 4144): /system/bin/bnrd has text relocations. This is wasting memory and prevents security hardening. Please fix.
W/bnrd    ( 4144): BNRD > wait starting [4144-3058102400] <
E/bnrd    ( 4144): /data/data/.bnr_fifo_req
I/UpdateIcingCorporaServi( 2059): UpdateCorporaTask done [took 153 ms] updated apps [took 152 ms] 
,I/ActivityManager(  845): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4147 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  845): Killing 3576:com.lge.gnss.airtest/u0a54 (adj 15): empty #11
I/Gmail   ( 4057): notifyAccountChanged
,V/[BNRBootCompletedThread]( 4114): End of BNRProcess
V/[BNRBootCompletedThread]( 4114): End of BNRViaWifiProcess
I/Gmail   ( 4057): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/[BNRBootCompletedThread]( 4114): End of SpriteProcess
V/[BNRBootCompletedThread]( 4114): exit
,I/Gmail   ( 4057): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4057): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4057): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/libprocessgroup(  845): failed to open /acct/uid_10054/pid_3576/cgroup.procs: No such file or directory
I/ActivityManager(  845): Killing 3599:com.lge.lgfota.permission/1000 (adj 15): empty #11
,I/WebViewFactory( 2059): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,W/libprocessgroup(  845): failed to open /acct/uid_1000/pid_3599/cgroup.procs: No such file or directory
,I/LibraryLoader( 2059): Time to load native libraries: 2 ms (timestamps 4898-4900)
,I/LibraryLoader( 2059): Expected native library version number "",actual native library version number ""
W/art     ( 2059): Attempt to remove local handle scope entry from IRT, ignoring
,V/GLSActivity( 2089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4057): getAccountsCursor
V/GLSActivity( 2089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4057): getAccountsCursor
,V/GLSActivity( 2089): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/art     ( 2059): Attempt to remove local handle scope entry from IRT, ignoring
,D/Finsky  ( 4147): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ActivityManager(  845): Waited long enough for: ServiceRecord{259ffd4b u0 com.google.android.gms/.gcm.GcmService}
,I/art     (  845): Explicit concurrent mark sweep GC freed 15427(733KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 1.736ms total 133.275ms
,D/Finsky  ( 4147): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 4147): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4147): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 4147): com.android.vending: cancel(-1050172287) by com.android.vending
,D/Volley  ( 4147): [401] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 4147): [408] DiskBasedCache.clear: Cache cleared.
I/ActivityManager(  845): Start proc com.lge.qmemoplus for broadcast com.lge.qmemoplus/.ui.editor.reminder.ReminderMaker: pid=4218 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  845): Killing 3665:com.lge.hiddenmenu/1000 (adj 15): empty #11
W/libprocessgroup(  845): failed to open /acct/uid_1000/pid_3665/cgroup.procs: No such file or directory
,V/DownloadManager( 3349): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
D/Ads     ( 4147): Skipping gmscore version check
D/Finsky  ( 4147): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4147): [1] Libraries$2.run: Finished loading 1 libraries.
V/DownloadManager( 3349): created cursor android.database.sqlite.SQLiteCursor@3f4f19a2 on behalf of 4147
,D/Finsky  ( 4147): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ResourcesManager( 4218): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/Finsky  ( 4147): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/App     ( 4218): [App][onCreate()] 4.40.21
,D/AccountManager( 4218): setSyncFrequency
,W/ContextImpl( 4218): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.qmemoplus.ui.editor.reminder.ReminderMaker.onReceive:14 android.app.ActivityThread.handleReceiver:2663 
,D/ReminderService( 4218): [onHandleIntent] action : com.lge.qmemoplus.action.SET_REMINDERS
D/LocationReminderManager( 4218): [connect] Request location client connection.
W/ContextImpl( 4218): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.google.android.gms.internal.he.a:-1 com.google.android.gms.internal.hc.connect:-1 com.google.android.gms.location.LocationClient.connect:-1 
,I/ActivityManager(  845): Start proc com.android.cellbroadcastreceiver for broadcast com.android.cellbroadcastreceiver/.CellBroadcastReceiver: pid=4246 uid=10016 gids={50016, 9997} abi=armeabi-v7a
D/BluetoothManagerService(  845): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  845): disable(): mBluetooth = null mBinding = false
D/BluetoothManagerService(  845): Message: 2
D/WifiServiceImplEx(  845): setWifiEnabled: false pid=3648, uid=10030, package= com.example.hello, App Lable : HelloWorld
,I/ActivityManager(  845): Killing 3688:com.android.providers.calendar/u0a14 (adj 15): empty #11
D/WifiService(  845): setWifiEnabled: false pid=3648, uid=10030
I/jxcore-log( 3648): ****TEST TOOK:  5080  ms ****
I/jxcore-log( 3648): 
I/jxcore-log( 3648): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3648): 
D/LocationReminderManager( 4218): location cilent is connected.
,D/LocationReminderManager( 4218): [removeAllReminders]
,W/libprocessgroup(  845): failed to open /acct/uid_10014/pid_3688/cgroup.procs: No such file or directory
,W/GeofencerStateMachine( 1784): Ignoring removeGeofence because network location is disabled.
W/GCoreFlp( 1784): No location to return for getLastLocation()
W/GCoreFlp( 1784): No location to return for getLastLocation()
D/LocationReminderManager( 4218): [removeAllReminders] statusCode : 1000
D/LocationReminderManager( 4218): [removeAllReminders] Failed to remove reminder
,D/CellBroadcastReceiverApp( 4246): CellBroadcastReceiverApp, onCreate()
,I/ActivityManager(  845): Killing 3706:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,D/MultiSimWrapper( 4246): [MessageUtils] isTripleSimEnabled=false
D/MultiSimWrapper( 4246): [isMultiSimEnabled] = false
D/MultiSimWrapper( 4246): [MessageUtils] isTripleSimEnabled=false
D/CellBroadcastReceiver( 4246): startInit() started. iccLoaded=false init_complete=false
D/CommonUtil( 4246): spn is empty. use default value as ""
D/CommonUtil( 4246): getRuntimeImsiCode[]
,D/CommonUtil( 4246): spn is empty. use default value as ""
D/CommonUtil( 4246): getRuntimeImsiCode[]
D/CommonUtil( 4246): simOperator =
D/CommonUtil( 4246): getRuntimeMccCode[0]
D/CellBroadcastReceiver( 4246): single sim : imsiCode= MccCode=0
E/CellBroadcastReceiver( 4246): IMSI value is NOT available yet. DO NOT PROCESS NEXT STEP.
D/CellBroadcastReceiver( 4246): onReceive Intent { act=android.intent.action.SIM_STATE_CHANGED flg=0x20000010 cmp=com.android.cellbroadcastreceiver/.CellBroadcastReceiver (has extras) }
D/MultiSimWrapper( 4246): [MessageUtils] isTripleSimEnabled=false
D/MultiSimWrapper( 4246): [isMultiSimEnabled] = false
D/MultiSimWrapper( 4246): [MessageUtils] isTripleSimEnabled=false
D/MultiSimWrapper( 4246): [isMultiSimEnabled] = false
D/MultiSimWrapper( 4246): [MessageUtils] isTripleSimEnabled=false
D/MultiSimWrapper( 4246): [isMultiSimEnabled] = false
D/CellBroadcastReceiver( 4246): [ACTION_SIM_STATE_CHANGED]SIM stateExtra:ABSENT
D/CellBroadcastReceiver( 4246): [INTENT_VALUE_ICC_ABSENT] SIM card absent. Just make setting menu be DISABLED.
D/MultiSimWrapper( 4246): [MessageUtils] isTripleSimEnabled=false
D/MultiSimWrapper( 4246): [isMultiSimEnabled] = false
W/libprocessgroup(  845): failed to open /acct/uid_10069/pid_3706/cgroup.procs: No such file or directory
,I/ActivityManager(  845): Start proc com.lge.email for broadcast com.lge.email/.receiver.DeviceSettingsReceiver: pid=4279 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  845): Killing 3741:com.lge.springcleaning/1000 (adj 15): empty #11
D/AndroidRuntime( 4268): 
D/AndroidRuntime( 4268): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4268): CheckJNI is OFF
,W/libprocessgroup(  845): failed to open /acct/uid_1000/pid_3741/cgroup.procs: No such file or directory
,W/ResourcesManager( 4279): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4279): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 4279): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/AndroidRuntime( 4268): Calling main entry com.android.commands.pm.Pm
,I/LGEmail ( 4279): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 4279): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/ActivityManager(  845): Force stopping com.example.hello appid=10030 user=-1: uninstall pkg
I/ActivityManager(  845): Killing 3648:com.example.hello/u0a30 (adj 0): stop com.example.hello
I/WindowState(  845): WIN DEATH: Window{69c5227 u0 com.example.hello/com.example.hello.MainActivity}
,D/InputDispatcher(  845): Focus left window: Window{69c5227 u0 com.example.hello/com.example.hello.MainActivity}
,D/InputDispatcher(  845): Window went away: Window{69c5227 u0 com.example.hello/com.example.hello.MainActivity}
,W/PackageSettings(  845): Skipping PackageSetting{2a6ca858 com.test.thalitest/10316} due to missing metadata
,W/ActivityManager(  845): Force removing ActivityRecord{22d69f2d u0 com.example.hello/.MainActivity t220}: app died, no saved state
,W/ActivityManager(  845): Spurious death for ProcessRecord{122e1a4e 3648:com.example.hello/u0a30}, curProc for 3648: null
,I/ActivityManager(  845): Force stopping com.example.hello appid=10030 user=0: pkg removed
D/KeyguardModel( 1407): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,W/GeofencerStateMachine( 1784): Ignoring removeGeofence because network location is disabled.
,I/[LGHome]EVENT( 1981): [Launcher.java:5203:onStart()]onStart
I/InputReader(  845): Reconfiguring input devices.  changes=0x00000010
I/QCNEJ   ( 1943): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[LGHome]EVENT( 1981): [Launcher.java:776:onResume()]onResume
W/System.err( 3152): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
,W/System.err( 3152): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3152): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3152): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3152): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3152): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3152): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3152): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3152): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3152): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3152): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3152): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,D/administrator(  845): Handling package changes for user 0
I/ActivityManager(  845): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4317 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/[LGHome]LGActivityUtil( 1981): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[SystemUI]QSlideListController( 1407): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 1981): [Launcher.java:929:onResume()]onResume end
I/Activity( 1981): Activity.onPostResume() called 
I/SystemUI[Framework](  845): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
,W/PhoneWindowManagerEx(  845): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  845): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  845): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  845): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@104eac1e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  845): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  845): Focus entered window: Window{37a4a2e9 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/[LGHome]LGWallpaperInfo( 1981): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1981): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,I/[LGHome]EVENT( 1981): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1981): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1981): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/art     ( 1889): CheckpointMarkThreadRoots callback created = 0xaaf21b80
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1407): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1407): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,I/[LGHome]EVENT( 1981): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1981): [setNavigationBarColor] color=0x 0
V/AlarmManager(  845): ELAPSED_WAKEUP set : Alarm{369bd99 type 2 when 52309 com.google.android.talk} when 52309
,V/AlarmManager(  845): RTC_WAKEUP set : Alarm{31ae43f type 0 when 1448306445293 com.google.android.gms} when 1448306445293
I/art     ( 1889): CheckpointMarkThreadRoots callback created = 0xaaf21f70
,I/LockScreenSettings( 4317): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,D/KeyguardModel( 1407): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1407): createShortcutInfo...
,D/KeyguardModel( 1407): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1407): createShortcutInfo...
W/ResourceType( 1407): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1407): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1407): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1407): createShortcutInfo...
W/ResourceType( 1407): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1407): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/KeyguardModel( 1407): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1407): createShortcutInfo...
W/ResourceType( 1407): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1407): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1407): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1407): createShortcutInfo...
D/KeyguardModel( 1407): handleShortcutListChanged...
D/KeyguardModel( 1407): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1407): createShortcutInfo...
,D/KeyguardModel( 1407): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1407): createShortcutInfo...
W/ResourceType( 1407): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1407): Failure retrieving resources for com.android.mms: Resource ID #0x0
W/InputMethodManagerService(  845): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
D/KeyguardModel( 1407): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1407): createShortcutInfo...
W/ResourceType( 1407): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1407): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1407): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1407): createShortcutInfo...
W/InputMethodManagerService(  845): Got RemoteException sending setActive(false) notification to pid 3648 uid 10030
W/ResourceType( 1407): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1407): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1407): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1407): createShortcutInfo...
D/KeyguardModel( 1407): handleShortcutListChanged...
,I/HotwordRecognitionRnr( 2059): Starting hotword detection.
,I/MicrophoneInputStream( 2059): mic_starting com.google.android.apps.gsa.speech.audio.u@3fc318f6
V/AudioRecord( 2059): set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
V/AudioRecord( 2059): set(): mSessionId 22
V/AudioPolicyManager(  286): getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 22, flags 0
V/AudioPolicyManager(  286): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  286): isPlaybackThread 0,isRecordThread 1
D/audio_hw_primary(  286): adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb546e240)
V/audio_hw_primary(  286): adev_open_input_stream: exit
V/AudioFlinger(  286): openInput_l() openInputStream returned input 0xb546e240, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
V/AudioFlinger(  286): openInput_l() created record thread: ID 23 thread 0xb4393000
,I/AudioFlinger(  286): AudioFlinger's thread 0xb4393000 ready to run
D/audio_hw_primary(  286): in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
V/audio_hw_primary(  286): in_standby: exit:  status(0)
V/AudioSystem(  286): ioConfigChanged() event 3, ioHandle 23
D/audio_hw_primary(  286): in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
V/audio_hw_primary(  286): in_standby: exit:  status(0)
V/AudioFlinger(  286): RecordThread: loop stopping
V/AudioSystem(  845): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 1407): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  286): AudioCommandThread() adding update audio port list
V/AudioSystem( 2703): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 1814): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 3321): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  286): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioSystem( 2059): ioConfigChanged() event 3, ioHandle 23
V/AudioFlinger(  286): openRecord() lSessionId: 22 input 23
V/AudioFlinger(  286): getOrphanEffectChain_l session 22 index -2
V/AudioFlinger(  286): acquiring 22 from 2059, for -1
V/AudioFlinger(  286):  added new entry for 22
V/AudioRecord( 2059): start, sync event 0 trigger session 0
V/AudioRecord( 2059): mAudioRecord->start()
V/AudioFlinger(  286): RecordHandle::start()
V/AudioFlinger(  286): RecordThread::start event 0, triggerSession 0
V/AudioPolicyManager(  286): startInput() module primary->input primary(23)
V/AudioPolicyManager(  286): getDeviceForInputSource()input source 1999, device 80000004
,V/AudioPolicyManager(  286): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  286): DeviceVector::refreshTypes() mDeviceTypes 80000004
,V/AudioPolicyManager(  286): DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
V/AudioPolicyService(  286): AudioCommandThread() adding create patch delay 0
V/AudioPolicyService(  286): inserting command: 7 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing create audio patch
V/AudioFlinger::PatchPanel(  286): createAudioPatch() num_sources 1 num_sinks 1 handle 0
V/AudioFlinger::PatchPanel(  286): createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
V/AudioFlinger(  286): ThreadBase::setParameters() input_source=6;routing=-2147483644
V/AudioFlinger(  286): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  286): RecordThread: loop starting
V/AudioFlinger(  286): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  286): in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
V/audio_hw_primary(  286): in_set_parameters: exit: status(0)
V/AudioFlinger(  286): processConfigEvents_l() DONE thread 0xb4393000
V/AudioFlinger::PatchPanel(  286): createAudioPatch() status 0
V/AudioFlinger::PatchPanel(  286): createAudioPatch() added new patch handle 24 halHandle 0
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
I/Timeline( 1981): Timeline: Activity_idle id: android.os.BinderProxy@37bb6180 time:57459
V/AudioPolicyManager(  286): setInputDevice() createAudioPatch returned 0 patchHandle 24
V/AudioPolicyManager(  286): addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
V/AudioPolicyService(  286): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  286): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() adding set parameter string hotword_active=1, io 23 ,delay 0
V/AudioPolicyService(  286): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  286): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  286): AudioCommandThread() waking up
V/AudioPolicyService(  286): AudioCommandThread() processing set parameters string hotword_active=1, io 23
V/AudioFlinger(  286): setParameters(): io 23, keyvalue hotword_active=1, calling pid 286
V/AudioFlinger(  286): ThreadBase::setParameters() hotword_active=1
V/AudioFlinger(  286): sendConfigEvent_l() num events 1 event 2
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
I/SystemUI[Framework](  845): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  845): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  845): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  845): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  845): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@104eac1e,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  845): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
V/AudioFlinger(  286): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  286): in_set_parameters: enter: kvpairs=hotword_active=1
V/audio_hw_primary(  286): in_set_parameters: exit: status(0)
V/AudioFlinger(  286): processConfigEvents_l() DONE thread 0xb4393000
E/PhoneInterfaceManager( 1814): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
V/AudioPolicyService(  286): AudioCommandThread() going to sleep
V/AudioPolicyManager(  286): AudioPolicyManager::startInput() input source = 1999
,I/iu.UploadsManager( 3846): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
V/msm8974_platform(  286): platform_update_usecase_from_source: input source :6
D/audio_hw_primary(  286): start_input_stream: enter: stream(0xb546e240)usecase(7: audio-record)
V/voice   (  286): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  286): start_input_stream: usecase(7)
E/audio_hw_primary(  286): select_devices: enter and usecase(7)
V/msm8974_platform(  286): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  286): platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
V/msm8974_platform_lge(  286): LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
V/audio_hw_lge_primary(  286): LGE_exeption_scenario: enter and out: 0, in: 144
D/audio_hw_primary(  286): select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
E/audio_hw_primary(  286): enable_snd_device: enter  144
D/hardware_info(  286): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  286): enable_snd_device: snd_device(144: lg-vr-handset-mic)
V/msm8974_platform_lge(  286): LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
D/ACDB-LOADER(  286): ACDB -> send_audio_cal, acdb_id = 65, path =  1
D/ACDB-LOADER(  286): ACDB -> send_adm_topology
D/ACDB-LOADER(  286): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  286): ACDB -> send_asm_topology
D/ACDB-LOADER(  286): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  286): ACDB -> send_audtable
D/ACDB-LOADER(  286): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  286): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  286): ACDB -> send_audvoltable
D/ACDB-LOADER(  286): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  286): Failed to fetch the lookup information of the device 00000041 
E/ACDB-LOADER(  286): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  286): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  286): ACDB -> AUDIO_SET_AFE_CAL
,W/art     (  845): Suspending all threads took: 7.197ms
V/audio_hw_primary(  286): enable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  286): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  286): enable_audio_route: apply mixer and update path: audio-record
V/audio_hw_primary(  286): enable_audio_route: exit
D/audio_hw_primary(  286): select_devices: done
V/audio_hw_primary(  286): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
V/audio_hw_primary(  286): start_input_stream: exit
I/MicrophoneInputStream( 2059): mic_started com.google.android.apps.gsa.speech.audio.u@3fc318f6
,I/art     (  845): Explicit concurrent mark sweep GC freed 17374(1125KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 19.151ms total 447.069ms
,I/ActivityManager(  845): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=4349 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  845): Killing 3778:com.google.android.configupdater/u0a3 (adj 15): empty #11
D/AndroidRuntime( 4268): Shutting down VM
,I/HotwordWorker( 2059): onReady
,I/NotificationService(  845): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  845): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  845): Receieved: android.intent.action.PACKAGE_REMOVED
W/libprocessgroup(  845): failed to open /acct/uid_10003/pid_3778/cgroup.procs: No such file or directory
,D/TaskPersister(  845): removeObsoleteFile: deleting file=220_task.xml
D/PhoneStatusBar( 1407): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/PhoneStatusBar( 1407): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
I/[SystemUI]NavigationThemeResource( 1407): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1407):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1407): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1407): draw background and invalidate : color = f8000000
D/BarTransitions( 1407): draw background and invalidate : color = f6ececec
,I/iu.UploadsManager( 3846): End new media; added: 0, uploading: 0, time: 190 ms
,I/ActivityManager(  845): Killing 3824:com.lge.eula/1000 (adj 15): empty #11
W/ResourcesManager(  845): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  845): failed to open /acct/uid_1000/pid_3824/cgroup.procs: No such file or directory
,I/Timeline(  845): Timeline: Activity_windows_visible id: ActivityRecord{2df9c428 u0 com.lge.launcher2/.Launcher t219} time:57752
I/ActivityManager(  845): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=4366 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  845): Killing 3929:com.google.android.talk/u0a61 (adj 15): empty #11
D/LCardEmulationManager( 1889): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1889): getDefaultRoute
,I/ActivityManager(  845): Waited long enough for: ServiceRecord{316f188a u0 com.lge.mlt/.MltMonitorService}
W/libprocessgroup(  845): failed to open /acct/uid_10061/pid_3929/cgroup.procs: No such file or directory
W/ResourceType(  845): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,D/LGDMClient( 4366): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.intent.action.SIM_STATE_CHANGED
D/LGDMClient( 4366): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4366): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:86 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/[LGHome]EVENT( 1981): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
E/LGDMClient( 4366): [DmServiceProcessor.java] [onHandleIntent()] : [153] : Received SIM_STATE_CHANGED
,I/ActivityManager(  845): Start proc com.lge.appbox.client:SingleBinaryService for broadcast com.lge.appbox.client/com.lge.appbox.singlebinary.SimChangeReceiver: pid=4387 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a

```
