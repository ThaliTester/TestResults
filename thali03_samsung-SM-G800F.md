#### Test 57132760f6ec045_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/main
D/dalvikvm( 6258): GC_CONCURRENT freed 3007K, 31% free 9573K/13716K, paused 3ms+2ms, total 26ms
D/dalvikvm( 6258): WAIT_FOR_CONCURRENT_GC blocked 21ms
W/ContextImpl( 6258): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
I/SELinux ( 6280): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6280):  
E/Device Type Shared Preferences( 6258): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences( 6258): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication( 6258): ContentProvider is not null
W/ResourceType( 6258): No package identifier when getting value for resource number 0x00000000
I/System.out( 6258): resource Id::2131361807
I/SELinux ( 6280): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6280):  
I/SELinux ( 6280):  
I/SELinux ( 6280): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6280): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6280): >>>>> Normal User
E/dalvikvm( 6280): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 6280): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6280): in addTimaSignatureService
D/TimaKeyStoreProvider( 6280): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6280): Added TimaKesytore provider
D/dalvikvm( 6280): GC_CONCURRENT freed 2993K, 31% free 9573K/13708K, paused 2ms+1ms, total 18ms
D/dalvikvm( 6280): WAIT_FOR_CONCURRENT_GC blocked 15ms
D/com.sec.android.app.shealth.SHealthApplication( 6258): Success during batch insertion in App registry:0
V/MediaPlayer( 6258): decode(56, 30565892, 48105)
V/MediaPlayerService( 1924): decode(28, 30565892, 48105)
V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): constructor
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
V/StagefrightPlayer( 1924): setDataSource(28, 30565892, 48105)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f1aa0, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1924): prepare
V/AwesomePlayer( 1924): prepareAsync
V/MediaPlayerService( 1924): wait for prepare
V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x444f1aa0, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f1aa0, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f1aa0, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f1aa0, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
V/MediaPlayerService( 1924): wait for playback complete
--------- beginning of /dev/log/system
D/AmoledAdjustTimer( 2401): prevTemp = 304, currTemp = 303, prevStep = 4, currStep = 4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f1aa0, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f1aa0, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f1aa0, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x36, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 6258): decode(58, 30501792, 10421)
V/MediaPlayerService( 1924): decode(28, 30501792, 10421)
V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): constructor
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
V/StagefrightPlayer( 1924): setDataSource(28, 30501792, 10421)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f8818, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1924): prepare
V/AwesomePlayer( 1924): prepareAsync
V/MediaPlayerService( 1924): wait for prepare
V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x444f8818, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f8818, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f8818, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f8818, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
V/MediaPlayerService( 1924): wait for playback complete
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f8818, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f8818, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x444f8818, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x37, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 6258): decode(59, 34044116, 34198)
V/MediaPlayerService( 1924): decode(29, 34044116, 34198)
V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): constructor
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
V/StagefrightPlayer( 1924): setDataSource(29, 34044116, 34198)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3438, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1924): prepare
V/AwesomePlayer( 1924): prepareAsync
V/MediaPlayerService( 1924): wait for prepare
V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x442b3438, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3438, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3438, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3438, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
V/MediaPlayerService( 1924): wait for playback complete
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3438, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3438, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b3438, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x38, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 6258): decode(60, 30449260, 7405)
V/MediaPlayerService( 1924): decode(28, 30449260, 7405)
V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): constructor
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
V/StagefrightPlayer( 1924): setDataSource(28, 30449260, 7405)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x4414f0b8, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1924): prepare
V/AwesomePlayer( 1924): prepareAsync
V/MediaPlayerService( 1924): wait for prepare
V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x4414f0b8, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x4414f0b8, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x4414f0b8, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x4414f0b8, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
V/MediaPlayerService( 1924): wait for playback complete
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x4414f0b8, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x4414f0b8, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x4414f0b8, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x39, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 6258): decode(61, 34134748, 5555)
V/MediaPlayerService( 1924): decode(28, 34134748, 5555)
V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): constructor
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
V/StagefrightPlayer( 1924): setDataSource(28, 34134748, 5555)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b54a0, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1924): prepare
V/AwesomePlayer( 1924): prepareAsync
V/MediaPlayerService( 1924): wait for prepare
V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x442b54a0, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b54a0, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b54a0, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b54a0, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
V/MediaPlayerService( 1924): wait for playback complete
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b54a0, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b54a0, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b54a0, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x3a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 6258): decode(62, 26954540, 5085)
V/MediaPlayerService( 1924): decode(28, 26954540, 5085)
V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): constructor
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
V/StagefrightPlayer( 1924): setDataSource(28, 26954540, 5085)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1924): prepare
V/AwesomePlayer( 1924): prepareAsync
V/MediaPlayerService( 1924): wait for prepare
V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
I/AudioPlayer( 1924): First fillBuffer call!!
V/MediaPlayerService( 1924): wait for playback complete
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x3b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 6258): decode(63, 26959684, 21552)
V/MediaPlayerService( 1924): decode(28, 26959684, 21552)
V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): constructor
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
V/StagefrightPlayer( 1924): setDataSource(28, 26959684, 21552)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1924): prepare
V/AwesomePlayer( 1924): prepareAsync
V/MediaPlayerService( 1924): wait for prepare
V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
I/AudioPlayer( 1924): First fillBuffer call!!
V/MediaPlayerService( 1924): wait for playback complete
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x3c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 6258): decode(64, 34130460, 4230)
V/MediaPlayerService( 1924): decode(28, 34130460, 4230)
V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): constructor
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
V/StagefrightPlayer( 1924): setDataSource(28, 34130460, 4230)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1924): prepare
V/AwesomePlayer( 1924): prepareAsync
V/MediaPlayerService( 1924): wait for prepare
V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 1924): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/MediaPlayerService( 1924): wait for playback complete
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x3d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 6258): decode(65, 26923896, 9400)
V/MediaPlayerService( 1924): decode(27, 26923896, 9400)
V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): constructor
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
V/StagefrightPlayer( 1924): setDataSource(27, 26923896, 9400)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b1700, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1924): prepare
V/AwesomePlayer( 1924): prepareAsync
V/MediaPlayerService( 1924): wait for prepare
V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
,V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x442b1700, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b1700, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b1700, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/SELinux ( 6338): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6338):  
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 1924): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b1700, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
V/MediaPlayerService( 1924): wait for playback complete
I/ActivityManager( 2401): Killing 5289:com.sec.android.app.taskmanager/u0a168 (adj 15): empty #43
I/ActivityManager( 2401): Killing 5262:org.simalliance.openmobileapi.service/1101 (adj 15): empty #44
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b1700, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b1700, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b1700, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x3e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/SELinux ( 6338): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6338):  
I/SELinux ( 6338):  
I/SELinux ( 6338): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
E/SELinux ( 6338): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6338): >>>>> Normal User
E/dalvikvm( 6338): >>>>> com.policydm [ userId:0 | appId:1000 ]
I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
E/SELinux ( 6338): [DEBUG] seapp_context_lookup: seinfoCategory = platform
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 6258): decode(66, 30512272, 44276)
V/MediaPlayerService( 1924): decode(28, 30512272, 44276)
D/dalvikvm( 6280): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42273840, skipping init
I/SecureStorage( 6280): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6280): [INFO]: SPID(0x00000000)This device supports Secure Storage
V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): constructor
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
V/StagefrightPlayer( 1924): setDataSource(28, 30512272, 44276)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b1660, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
I/SecureStorage( 1965): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 6280
I/SecureStorage( 1965): [INFO]: SPID(0x00000003)Received function mask & code: 0000010C
I/SecureStorage( 6280): [INFO]: SPID(0x00000000)SS Daemon is running
V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1924): prepare
V/AwesomePlayer( 1924): prepareAsync
V/MediaPlayerService( 1924): wait for prepare
V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x442b1660, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b1660, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b1660, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b1660, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
V/MediaPlayerService( 1924): wait for playback complete
I/SecureStorage( 6280): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage( 1965): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 6280
I/SecureStorage( 1965): [INFO]: SPID(0x00000003)Received function mask & code: 00000106
D/TimaKeyStoreProvider( 6338): in addTimaSignatureService
D/TimaKeyStoreProvider( 6338): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6338): Added TimaKesytore provider
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b1660, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b1660, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b1660, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x3f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 6258): decode(67, 30472480, 29256)
V/MediaPlayerService( 1924): decode(28, 30472480, 29256)
V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): constructor
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
V/StagefrightPlayer( 1924): setDataSource(28, 30472480, 29256)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x44150038, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1924): prepare
V/AwesomePlayer( 1924): prepareAsync
V/MediaPlayerService( 1924): wait for prepare
V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x44150038, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x44150038, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x44150038, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x44150038, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
V/MediaPlayerService( 1924): wait for playback complete
I/AudioPlayer( 1924): First fillBuffer call!!
D/dalvikvm( 6338): GC_CONCURRENT freed 3002K, 31% free 9571K/13712K, paused 4ms+3ms, total 31ms
D/dalvikvm( 6338): WAIT_FOR_CONCURRENT_GC blocked 23ms
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x44150038, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x44150038, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x44150038, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x40, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 6258): decode(68, 34078380, 52024)
V/MediaPlayerService( 1924): decode(28, 34078380, 52024)
V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): constructor
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
V/StagefrightPlayer( 1924): setDataSource(28, 34078380, 52024)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1924): prepare
V/AwesomePlayer( 1924): prepareAsync
V/MediaPlayerService( 1924): wait for prepare
V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1924): open(48000, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
V/MediaPlayerService( 1924): wait for playback complete
I/AudioPlayer( 1924): First fillBuffer call!!
I/SELinux ( 6368): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6368):  
I/ActivityManager( 2401): Killing 5301:com.samsung.android.service.travel/u0a170 (adj 15): empty #43
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
I/SELinux ( 6368): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6368):  
I/SELinux ( 6368):  
I/SELinux ( 6368): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6368): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 6368): >>>>> Normal User
E/dalvikvm( 6368): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10043 ]
E/SELinux ( 6368): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x41, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 6258): decode(69, 30556608, 9226)
V/MediaPlayerService( 1924): decode(28, 30556608, 9226)
V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): constructor
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
V/StagefrightPlayer( 1924): setDataSource(28, 30556608, 9226)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1924): prepare
V/AwesomePlayer( 1924): prepareAsync
V/MediaPlayerService( 1924): wait for prepare
V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
D/TimaKeyStoreProvider( 6368): in addTimaSignatureService
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
V/MediaPlayerService( 1924): wait for playback complete
D/TimaKeyStoreProvider( 6368): Cannot add TimaSignature Service, License check Failed
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
D/ActivityThread( 6368): Added TimaKesytore provider
V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x42, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/MediaPlayer( 6258): decode(70, 26989388, 4509)
V/MediaPlayerService( 1924): decode(28, 26989388, 4509)
V/MediaPlayerService( 1924): player type = 3
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): constructor
V/AwesomePlayer( 1924): setDefault
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): StagefrightPlayer
V/AwesomePlayer( 1924): setListener
V/StagefrightPlayer( 1924): initCheck
V/AwesomePlayer( 1924): setAudioSink
V/StagefrightPlayer( 1924): setDataSource(28, 26989388, 4509)
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1924): mBitrate = -1 bits/sec
V/AwesomePlayer( 1924): current audio track index (0) is added to vector
V/AwesomePlayer( 1924): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1924): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1924): prepare
V/AwesomePlayer( 1924): prepareAsync
V/MediaPlayerService( 1924): wait for prepare
V/AwesomePlayer( 1924): onPrepareAsyncEvent
I/SecMediaClock( 1924): SecMediaClock constructor
I/SecMediaClock( 1924): reset
V/AwesomePlayer( 1924): initAudioDecoder
V/AwesomePlayer( 1924): checkOffloadExceptions is true
I/OMXCodec( 1924): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1924): mDispatchers.add
I/OMXCodec( 1924): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1924): finishAsyncPrepare_l
V/AwesomePlayer( 1924): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 200, 973, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 5, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 1, 0, 0)
V/AudioCache( 1924): prepared
V/AudioCache( 1924): wait - success
V/MediaPlayerService( 1924): start
V/StagefrightPlayer( 1924): start
V/AwesomePlayer( 1924): play
V/AwesomePlayer( 1924): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1924): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] End Of Stream
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1924):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1924): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1924): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 6, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): addBatteryData
V/MediaPlayerService( 1924): wait for playback complete
V/AwesomePlayer( 1924): postAudioEOS delayUs (0)
V/AwesomePlayer( 1924): onCheckAudioStatus
V/AwesomePlayer( 1924): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1924): onStreamDone
V/AwesomePlayer( 1924): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1924): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 2, 0, 0)
V/AudioCache( 1924): playback complete - thread will wake up later
V/AwesomePlayer( 1924): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 7, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1924): addBatteryData
V/AudioCache( 1924): wait - success
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1924): notify(0x442b6d18, 8, 0, 0)
V/AudioCache( 1924): ignored
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stop() sendCommand(0x43, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1924): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1924): reset out
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1924): SecMediaClock destructor
V/AwesomePlayer( 1924): mSecMediaClock clear
V/StagefrightPlayer( 1924): ~StagefrightPlayer
V/StagefrightPlayer( 1924): reset
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
V/AwesomePlayer( 1924): destructor
V/AwesomePlayer( 1924): reset_l()
V/AwesomePlayer( 1924): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1924): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1924): mAudioTrackVector clear
V/AwesomePlayer( 1924): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1924): mSecMediaClock clear
D/dalvikvm( 6368): GC_CONCURRENT freed 2995K, 31% free 9582K/13716K, paused 3ms+1ms, total 22ms
D/dalvikvm( 6368): WAIT_FOR_CONCURRENT_GC blocked 11ms
E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 6368): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ActivityManager( 2401): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 6368): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
I/SA      ( 6041): [PMR] Received action : android.intent.action.PACKAGE_ADDED
I/SA      ( 6041): [DM] init START
I/SA      ( 6041): [DM] This device is not a Vodafone
I/SA      ( 6041): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6041): support phone number id : false
I/SA      ( 6041): [DM] init END
I/SA      ( 6041): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
I/SA      ( 6041): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
D/Mms/PackageInstallReceiver( 5610): loadAuthorityPref(): sEnableAuthority = true
I/Icing.InternalIcingCorporaProvider( 5949): Updating corpora: A: com.test.thalitest, C: MAYBE
W/ContextImpl( 4835): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
I/SELinux ( 6404): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6404):  
D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 12% free 9508K/10688K, paused 3ms+3ms, total 32ms
I/SELinux ( 6404): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6404):  
I/SELinux ( 6404):  
I/SELinux ( 6404): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6404): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 6404): >>>>> Normal User
E/dalvikvm( 6404): >>>>> com.sec.android.service.cm [ userId:0 | appId:10082 ]
E/SELinux ( 6404): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9508K/10688K, paused 2ms+8ms, total 32ms
D/TimaKeyStoreProvider( 6404): in addTimaSignatureService
D/TimaKeyStoreProvider( 6404): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6404): Added TimaKesytore provider
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9508K/10688K, paused 2ms+3ms, total 29ms
I/ActivityManager( 2401): Killing 5328:com.gameloft.android.GloftGF2H/u0a179 (adj 15): empty #43
D/AndroidRuntime( 6400): 
D/AndroidRuntime( 6400): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6400): CheckJNI is OFF
D/AndroidRuntime( 6400): setted country_code = Poland
D/AndroidRuntime( 6400): setted countryiso_code = PL
D/AndroidRuntime( 6400): setted sales_code = PLS
D/AndroidRuntime( 6400): readGMSProperty: start
D/AndroidRuntime( 6400): readGMSProperty: already setted!!
D/AndroidRuntime( 6400): readGMSProperty: end
D/AndroidRuntime( 6400): addProductProperty: start
I/SecureStorage( 1965): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
I/SecureStorage( 1965): [INFO]: SPID(0x00000003)PID: 6280, TID: 6292
D/dalvikvm( 6400): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6400): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6400): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6400): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6400): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/Icing.InternalIcingCorporaProvider( 5949): UpdateCorporaTask done [took 431 ms] updated apps [took 431 ms] 
D/dalvikvm( 6404): GC_CONCURRENT freed 2998K, 31% free 9578K/13712K, paused 6ms+1ms, total 48ms
D/dalvikvm( 6404): WAIT_FOR_CONCURRENT_GC blocked 36ms
D/CapabilityManagerService New( 6404): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
I/SELinux ( 6424): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6424):  
I/ActivityManager( 2401): Killing 5341:com.gameloft.android.GloftKLMF/u0a180 (adj 15): empty #43
I/SecureStorage( 6280): [INFO]: SPID(0x00000000)Processing data has been completed
I/SecureStorage( 6280): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
I/SQLiteSecureOpenHelper( 6280): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 6280): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 6280): Open platform.db in secure mode
I/SELinux ( 6424): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6424):  
I/SELinux ( 6424):  
I/SELinux ( 6424): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6424): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6424): >>>>> Normal User
E/dalvikvm( 6424): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10104 ]
E/SELinux ( 6424): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6424): in addTimaSignatureService
D/TimaKeyStoreProvider( 6424): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6424): Added TimaKesytore provider
E/memtrack( 6400): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6400): failed to load memtrack module: -2
D/dalvikvm( 6400): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/dalvikvm( 6424): GC_CONCURRENT freed 3008K, 31% free 9571K/13716K, paused 3ms+1ms, total 19ms
D/dalvikvm( 6424): WAIT_FOR_CONCURRENT_GC blocked 8ms
D/PackageIntentReceiver( 6424): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 6424): Not GearManger package! 
I/SQLiteSecureOpenHelper( 6280): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 6280): ...getDatabaseLocked(b,b,pwd)
I/SELinux ( 6436): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6436):  
I/ActivityManager( 2401): Killing 5356:com.gameloft.android.GloftPSHU/u0a181 (adj 15): empty #43
I/SELinux ( 6436): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6436):  
I/SELinux ( 6436):  
I/SELinux ( 6436): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6436): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6436): >>>>> Normal User
E/dalvikvm( 6436): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10110 ]
E/SELinux ( 6436): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/AndroidRuntime( 6400): Calling main entry com.android.commands.am.Am
D/TimaKeyStoreProvider( 6436): in addTimaSignatureService
D/TimaKeyStoreProvider( 6436): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6436): Added TimaKesytore provider
D/dalvikvm( 6436): GC_CONCURRENT freed 3005K, 31% free 9569K/13712K, paused 2ms+1ms, total 18ms
D/dalvikvm( 6436): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/ApplicationPolicy( 2401): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/MagazineService Version( 6436): Magazine-Channel: 13
D/MagazineService Version( 6436): Magazine-Provider: 13
D/MagazineService Version( 6436): Magazine-Administrator: 11
D/CustomFrequencyManagerService( 2401): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  pkgName : ACTIVITY_RESUME_BOOSTER@4
I/SurfaceFlinger( 1920): id=17 createSurf (16x16),-1 flag=20004, EimLayer
W/ActivityManager( 2401): mDVFSHelper.acquire()
I/SurfaceFlinger( 1920): id=18 createSurf (16x16),-1 flag=20004, EimLayer
I/SELinux ( 6450): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6450):  
D/PointerIcon( 2401): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2401): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2401): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2401): setHoveringSpenCustomIcon IconType is same.1
D/HeadlinesChannelApplication( 6436): [onCreate]
D/AndroidRuntime( 6400): Shutting down VM
D/MagazineService::MagazineBroadcastReceiver( 6436): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
D/dalvikvm( 6400): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+1ms, total 3ms
I/MagazineService::MagazineService( 6436): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/SELinux ( 6455): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6455):  
I/SELinux ( 6450): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6450):  
I/SELinux ( 6450):  
I/SELinux ( 6450): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6450): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6450): >>>>> Normal User
E/dalvikvm( 6450): >>>>> com.test.thalitest [ userId:0 | appId:10648 ]
E/SELinux ( 6450): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/MagazineService::MagazineService( 6436): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager( 2401): Killing 5392:com.google.android.youtube/u0a175 (adj 15): empty #43
D/TimaKeyStoreProvider( 6450): in addTimaSignatureService
D/TimaKeyStoreProvider( 6450): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6450): Added TimaKesytore provider
I/SELinux ( 6455): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6455):  
I/SELinux ( 6455):  
I/SELinux ( 6455): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6455): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6455): >>>>> Normal User
E/dalvikvm( 6455): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
E/SELinux ( 6455): [DEBUG] seapp_context_lookup: seinfoCategory = platform
V/WindowManager( 2401): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
D/TimaKeyStoreProvider( 6455): in addTimaSignatureService
D/TimaKeyStoreProvider( 6455): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6455): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4125): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4125): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1920): id=9 Removed Mauncher (8/10)
I/SurfaceFlinger( 1920): id=9 Removed Mauncher (-2/10)
D/Launcher( 2781): onTrimMemory. Level: 20
D/dalvikvm( 6450): GC_CONCURRENT freed 2998K, 31% free 9571K/13708K, paused 2ms+1ms, total 20ms
D/dalvikvm( 6450): WAIT_FOR_CONCURRENT_GC blocked 16ms
D/dalvikvm( 6455): GC_CONCURRENT freed 3001K, 31% free 9575K/13716K, paused 3ms+1ms, total 20ms
D/dalvikvm( 6455): WAIT_FOR_CONCURRENT_GC blocked 12ms
,V/WebViewChromium( 6450): Binding Chromium to the background looper Looper (main, tid 1) {4226d458}
,I/chromium( 6450): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6450): Initializing chromium process, renderers=0
,W/chromium( 6450): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 6450): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 6450): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 6450): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 6450): Mali API Version : 401
,I/Mali    ( 6450): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/SELinux ( 6491): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6491):  
,I/ActivityManager( 2401): Killing 5542:com.samsung.klmsagent/u0a18 (adj 15): empty #43,
,I/SELinux ( 6491): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 6491):  
I/SELinux ( 6491):  
,I/SELinux ( 6491): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6491): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6491): >>>>> Normal User
,E/dalvikvm( 6491): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10160 ],
I/dalvikvm( 6450): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 6450): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 6450): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 6450): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush,
W/dalvikvm( 6450): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 6450): VFY: replacing opcode 0x6e at 0x0008
,E/SELinux ( 6491): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,W/dalvikvm( 6450): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,D/StatusBarManagerService( 2401): tr p:6450,o:f
W/dalvikvm( 6450): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 6450): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 6450): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 6450): VFY: replacing opcode 0x6f at 0x001a
D/TimaKeyStoreProvider( 6491): in addTimaSignatureService
W/dalvikvm( 6450): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 6450): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 6450): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 6450): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 6450): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 6450): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 6450): VFY: replacing opcode 0x6e at 0x0000
D/TimaKeyStoreProvider( 6491): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6491): Added TimaKesytore provider
D/SystemWebViewEngine( 6450): CordovaWebView is running on device made by: samsung
,D/dalvikvm( 6491): GC_CONCURRENT freed 3006K, 31% free 9571K/13716K, paused 3ms+1ms, total 20ms,
,D/dalvikvm( 6491): WAIT_FOR_CONCURRENT_GC blocked 11ms,
,D/KidsPlatformStub( 6491): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 6509): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6509):  
I/ActivityManager( 2401): Killing 5632:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
D/StatusBarManagerService( 2401): semi p:6450,o:f
,D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,I/SurfaceFlinger( 1920): id=19 createSurf (1x1),1 flag=404, NainActivit
,D/STATUSBAR-StatusBarManagerService( 2401): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
I/SELinux ( 6509): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6509):  
I/SELinux ( 6509):  
I/SELinux ( 6509): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6509): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6509): >>>>> Normal User
E/dalvikvm( 6509): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10164 ]
E/SELinux ( 6509): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/STATUSBAR-StatusBarManagerService( 2401): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2401): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2401): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2401): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2401): setHoveringSpenCustomIcon IconType is same.1
I/HWUI    ( 6450): EGLImpl-HWUI Protected EGL context created
D/TimaKeyStoreProvider( 6509): in addTimaSignatureService
D/TimaKeyStoreProvider( 6509): Cannot add TimaSignature Service, License check Failed,
D/ActivityThread( 6509): Added TimaKesytore provider
,D/OpenGLRenderer( 6450): Enabling debug mode 0,
,I/Icing   ( 3155): Indexing 8AF1F6B88973B002A001A3BB90ED270D05322BB1 from com.google.android.googlequicksearchbox,
,W/AwContents( 6450): nativeOnDraw failed; clearing to background color.,
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/CustomFrequencyManagerService( 2401): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2401): mDVFSHelper.release()
,W/AwContents( 6450): nativeOnDraw failed; clearing to background color.
D/CustomFrequencyManagerService( 2401): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/IInputConnectionWrapper( 6450): showStatusIcon on inactive InputConnection
,D/dalvikvm( 6509): GC_CONCURRENT freed 3003K, 31% free 9574K/13716K, paused 5ms+3ms, total 39ms
,D/dalvikvm( 6509): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/SELinux ( 6528): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6528):  
I/ActivityManager( 2401): Killing 5746:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,I/Icing   ( 3155): Indexing done 8AF1F6B88973B002A001A3BB90ED270D05322BB1
I/SELinux ( 6528): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6528):  
I/SELinux ( 6528):  
,I/SELinux ( 6528): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6528): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6528): >>>>> Normal User
,E/dalvikvm( 6528): >>>>> com.sec.enterprise.knox.cloudmdm.smdms [ userId:0 | appId:10171 ]
,E/SELinux ( 6528): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6528): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6528): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6528): Added TimaKesytore provider
,D/dalvikvm( 6528): GC_CONCURRENT freed 2990K, 31% free 9582K/13712K, paused 3ms+2ms, total 20ms
,D/dalvikvm( 6528): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/UMC:Core( 6528): onCreate(): 
,D/USER_AGENT( 6528): UMC/1.0.12 (SM-G800F) SAFE-5 KNOX-2.0
,D/JsMessageQueue( 6450): Set native->JS mode to OnlineEventsBridgeMode
,D/[SAMSUNG SMARCART NATIVE]( 6528): initialize...
,D/[SAMSUNG SMARCART NATIVE]( 6528): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
I/TZ_CCM_C_GetFunctionList: ( 6528): TZ_CCM_C_GetFunctionList was called
,D/[SAMSUNG SMARCART NATIVE]( 6528): FINISHED: initialize rv:0
,D/dalvikvm( 6450): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422660e8
,D/dalvikvm( 6450): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422660e8
,D/jxcore_app_log( 6450): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2028026904
,I/chromium( 6450): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/dalvikvm( 6528): GC_CONCURRENT freed 1884K, 22% free 10773K/13792K, paused 3ms+2ms, total 35ms
,D/dalvikvm( 6528): WAIT_FOR_CONCURRENT_GC blocked 14ms
W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/UMC:SecurityUtils( 6528): Loaded server certificates: 0
,D/UMC:SecurityUtils( 6528): Loaded server certificates: 0
,D/UMC:CloudMDMSecurity( 6528): New Flow
I/        ( 2401): CCM JNI: In ccm_register_for_default_cert
,I/        ( 2401): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: ( 2401): &ctx = 0x7bccc618
I/TLC_TZ_CCM: ( 2401): creating new ccm context...
I/TLC_TZ_CCM: ( 2401): initializing ccm context...
I/TLC_TZ_CCM: ( 2401): root = 0, root_strlen = 1
I/TLC_TZ_CCM: ( 2401): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: client_server_communication( 2401): input max_sendmsg_size = 19420
I/TZ: client_server_communication( 2401): input max_recvmsg_size = 19420
I/TZ: client_server_communication( 2401): root = 0, root_len = 1
I/TZ: client_server_communication( 2401): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: client_server_communication( 2401): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication( 2401): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication( 2401): Client_Server_Open was called
I/TZ: client_server_communication( 2401): IClientServer::IClientServer()
,I/TZ: client_server_communication( 2401): BpClientServer::BpClientServer()
I/TZ_CCM_SERVER( 2510): BnCCM::onTransact(0) 16
,I/TZ_CCM_SERVER( 2510): creating new ccm context...
D/TimaService( 2401): TIMA3: in ccmRegisterForDefaultCertificate
,D/TimaService( 2401): TIMA: in getTimaVersion
I/TZ_CCM_SERVER( 2510): initializing ccm context...
I/TZ_CCM_SERVER( 2510): root = 0, root_strlen = 1
I/TZ_CCM_SERVER( 2510): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: mc_tlc_communication( 2510): input max_sendmsg_size = 19420
I/TZ: mc_tlc_communication( 2510): input max_recvmsg_size = 19420
I/TZ: mc_tlc_communication( 2510): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2510): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: mc_tlc_communication( 2510): aligned max_sendmsg_size = 19456
I/TZ: mc_tlc_communication( 2510): aligned max_recvmsg_size = 19456
I/TZ: mc_tlc_communication( 2510): device_id = 0x0
I/TZ: mc_tlc_communication( 2510): tlc_open() was called
I/TZ: mc_tlc_communication( 2510): Opening MobiCore device
I/TZ: mc_tlc_communication( 2510): Allocating WSM for TCI
I/TZ: mc_tlc_communication( 2510): Opening the session
,I/TZ: mc_tlc_communication( 2510): tlc_open() succeeded
I/TZ: client_server_communication( 2401): Client_Server_Open succeeded
I/TZ_CCM_C_Initialize: ( 2401): ctx = 0x7a11baa8, comm = 0x87561350, sendmsg = 0x7b960008, recvmsg = 0x7b964c08
,I/TZ_init: ( 2401): TZ_init: sending initialization request...
I/TZ_CCM_SERVER( 2510): BnCCM::onTransact(2) 16
,E/Parcel  ( 2510): nm 19456
E/Parcel  ( 2401): nm 19456
E/TZ_init: ( 2401): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 2401): trustlet initialization failed
,I/TZ_init: ( 2401): TZ_init_START...
,I/TZ_init: ( 2401): TZ_init_with_data: sending initialization request...
I/TZ_CCM_SERVER( 2510): BnCCM::onTransact(2) 16
,E/Parcel  ( 2510): nm 19456
,E/Parcel  ( 2401): nm 19456
I/TZ_init: ( 2401): TZ_init: successful initialization
,I/TLC_TZ_COMMON: key_db_init: ( 2401): Exercising TZ_DB_INIT in TLC
,I/TZ_CCM_SERVER( 2510): BnCCM::onTransact(2) 16
,E/Parcel  ( 2510): nm 19456
E/Parcel  ( 2401): nm 19456
I/TZ_COMMON: tlc_key_db_util: ( 2401): DB Operation suceeded
,I/TLC_TZ_CCM: register for default cert: ( 2401): Exercising TZ_CCM_register_default_TLC
I/TZ_CCM_SERVER( 2510): BnCCM::onTransact(2) 16
,E/Parcel  ( 2510): nm 19456
E/Parcel  ( 2401): nm 19456
I/TLC_TZ_CCM: register for default cert: ( 2401): TZ_CCM_register_default_TLC_END: DB file size to update is 0
I/TLC_TZ_CCM: register for default cert: ( 2401): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
,I/TZ_CCM_C_Finalize: ( 2401): Exercising TZ_CCM_C_Finalize_TLC
I/TZ_CCM_SERVER( 2510): BnCCM::onTransact(2) 16
,E/Parcel  ( 2510): nm 19456
E/Parcel  ( 2401): nm 19456
I/TZ: client_server_communication( 2401): Client_Server_Close was called
I/TZ_CCM_SERVER( 2510): BnCCM::onTransact(1) 16
I/TZ: mc_tlc_communication( 2510): tlc_close() was called
,I/TZ: mc_tlc_communication( 2510): Closing the session
I/TZ: mc_tlc_communication( 2510): Free WSM
,I/TZ: mc_tlc_communication( 2510): Closing MobiCore device
,I/TZ: mc_tlc_communication( 2510): tlc_close() succeeded
I/TZ: client_server_communication( 2401): Client_Server_Close succeeded
D/UMC:CloudMDMSecurity( 6528): TIMA service call for password change success!!
,D/UMC:AdminManager( 6528): init - start
,D/dalvikvm( 6450): GC_CONCURRENT freed 1293K, 18% free 11352K/13780K, paused 4ms+3ms, total 39ms,
,D/dalvikvm( 6450): WAIT_FOR_CONCURRENT_GC blocked 13ms,
,D/UMC:AdminManager( 6528): loadAdmins,
,D/UMC:AdminManager( 6528): removeOutOfSyncProxyAdmins,
D/UMC:AdminManager( 6528): startPolicyHandlers
I/UMC:TestPolicyHandler( 6528): Setup is called in testpolicyhandler
D/UMC:AdminManager( 6528): init - end
,V/UMC:AlarmHandler( 6528): Enter loadList
,D/EnterpriseDeviceManagerService( 2401): Creating context as user 0
,D/SPPApp  ( 6528): [SppMessageReceiver] onReceive,
,D/SPPApp  ( 6528): [SppMessageReceiver] onReceive. ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest,
,I/SELinux ( 6547): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 6547):  
I/ActivityManager( 2401): Killing 5851:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 6547): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 6547):  
I/SELinux ( 6547):  
,I/SELinux ( 6547): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 6547): [DEBUG] seapp_context_lookup: seinfoCategory = default,
E/dalvikvm( 6547): >>>>> Normal User
,E/dalvikvm( 6547): >>>>> com.n7mobile.promenadaplusa [ userId:0 | appId:10183 ],
,E/SELinux ( 6547): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 6547): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 6547): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 6547): Added TimaKesytore provider,
,D/dalvikvm( 6547): GC_CONCURRENT freed 2993K, 31% free 9572K/13708K, paused 2ms+1ms, total 18ms,
,D/dalvikvm( 6547): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/CustomFrequencyManagerService( 2401): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2401  tag : ACTIVITY_RESUME_BOOSTER@8
,D/ApplicationPromenada( 6547): Application OnCreate start,
,D/ApplicationPromenada( 6547): Application OnCreate po on Create,
D/CrashReporter( 6547): Initing Crashreporter: com.n7mobile.promenada2.ApplicationPromenada@4226f6f0
,D/CrashReporter( 6547): Swaping uncaught exception handler
,D/ApplicationPromenada( 6547): Application OnCreate App Loader start,
,D/ApplicationPromenada( 6547): Application OnCreate App Loader finish,
,D/p2.ApplicationLoader( 6547): ############################## cached apps: ,
,V/WebViewChromium( 6547): Binding Chromium to the background looper Looper (main, tid 1) {422723d0},
I/chromium( 6547): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6547): Initializing chromium process, renderers=0,
,W/chromium( 6547): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation,
,D/libEGL  ( 6547): loaded /system/lib/egl/libEGL_mali.so,
,D/libEGL  ( 6547): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 6547): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 6547): Mali API Version : 401
,I/Mali    ( 6547): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/ApplicationPromenada( 6547): Application OnCreate Finish
,D/dalvikvm( 6450): GC_CONCURRENT freed 1730K, 17% free 15161K/18052K, paused 1ms+4ms, total 47ms
,D/dalvikvm( 6450): WAIT_FOR_CONCURRENT_GC blocked 35ms
,D/dalvikvm( 6450): WAIT_FOR_CONCURRENT_GC blocked 26ms
,I/SELinux ( 6578): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6578):  
,I/ActivityManager( 2401): Killing 5937:com.sec.android.Kies/1000 (adj 15): empty #43
,I/SELinux ( 6578): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6578):  
I/SELinux ( 6578):  
,I/SELinux ( 6578): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6578): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 6578): >>>>> Normal User
,E/dalvikvm( 6578): >>>>> com.sec.android.app.samsungapps [ userId:0 | appId:10041 ]
,E/SELinux ( 6578): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 6578): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6578): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6578): Added TimaKesytore provider
,D/dalvikvm( 6578): GC_CONCURRENT freed 2997K, 31% free 9574K/13712K, paused 4ms+1ms, total 28ms
,D/dalvikvm( 6578): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/ActivityManager( 2401): Killing 5799:com.sec.phone/1001 (adj 15): empty #43
,D/PackageBroadcastService( 3155): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraCfgMgr( 3155): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3155): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 3155): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3155): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 3155): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 3155): Submit a task: k
,D/ChimeraCfgMgr( 3155): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 3155): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 3155): Processing package: com.test.thalitest
,D/dalvikvm( 6547): GC_CONCURRENT freed 1780K, 22% free 10839K/13736K, paused 9ms+29ms, total 145ms
,D/GassUtils( 3155): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
,D/k       ( 3155): Found info for package com.test.thalitest in db.
,D/Finsky  ( 3876): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/dalvikvm( 6450): GC_FOR_ALLOC freed 5727K, 30% free 16731K/23632K, paused 48ms, total 48ms
,D/dalvikvm( 6547): GC_CONCURRENT freed 2381K, 26% free 10430K/13956K, paused 1ms+3ms, total 35ms
,W/ResourceType( 6547): Failure getting entry for 0x7f060000 (t=5 e=0) in package 0 (error -75)
,W/PackageManager( 6547): Failure retrieving text 0x7f060000 in package com.android.keyguard
W/PackageManager( 6547): android.content.res.Resources$NotFoundException: String resource ID #0x7f060000
W/PackageManager( 6547): 	at android.content.res.Resources.getText(Resources.java:1374)
W/PackageManager( 6547): 	at android.app.ApplicationPackageManager.getText(ApplicationPackageManager.java:1198)
W/PackageManager( 6547): 	at android.content.pm.PackageItemInfo.loadLabel(PackageItemInfo.java:135)
W/PackageManager( 6547): 	at android.app.ApplicationPackageManager.getApplicationLabel(ApplicationPackageManager.java:1242)
W/PackageManager( 6547): 	at com.n7mobile.promenada2.applications.ApplicationLoader.a(SourceFile:155)
W/PackageManager( 6547): 	at com.n7mobile.promenada2.applications.ApplicationLoader.c(SourceFile:135)
W/PackageManager( 6547): 	at com.n7mobile.promenada2.applications.ApplicationLoader.a(SourceFile:125)
W/PackageManager( 6547): 	at com.n7p.pp.run(SourceFile:52)
W/PackageManager( 6547): 	at java.lang.Thread.run(Thread.java:841)
,D/dalvikvm( 6547): GC_CONCURRENT freed 2032K, 25% free 10534K/13956K, paused 1ms+3ms, total 41ms
,D/dalvikvm( 6450): GC_CONCURRENT freed 6778K, 31% free 18108K/26060K, paused 3ms+10ms, total 72ms
,D/dalvikvm( 6450): WAIT_FOR_CONCURRENT_GC blocked 53ms
,D/dalvikvm( 6450): WAIT_FOR_CONCURRENT_GC blocked 53ms
,I/Icing   ( 3155): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
,D/dalvikvm( 3155): GC_CONCURRENT freed 1711K, 19% free 12609K/15460K, paused 7ms+13ms, total 77ms
,W/SQLiteConnectionPool( 3155): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/Icing   ( 3155): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,D/dalvikvm( 6450): GC_FOR_ALLOC freed 1152K, 32% free 17823K/26060K, paused 45ms, total 45ms
,I/dalvikvm-heap( 6450): Grow heap (frag case) to 22.031MB for 3688532-byte allocation
,D/dalvikvm( 6450): GC_FOR_ALLOC freed 2405K, 36% free 19019K/29664K, paused 45ms, total 45ms
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2401): stay LED for fully charged
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/p2.ApplicationLoader( 6547): Process time: 2319
,D/p2.ApplicationLoader( 6547): ##############################  apps after loading: 
,W/jxcore-log( 6450): Initializing JXcore engine
,W/jxcore-log( 6450): JXcore engine is ready
,W/jxcore-log( 6450): Starting JXcore engine
,W/jxcore-log( 6450): Platform android
W/jxcore-log( 6450): 
,W/jxcore-log( 6450): Process ARCH arm
W/jxcore-log( 6450): 
,I/PowerManagerService( 2401): [PWL] Off : 30s ago
,V/AlarmManager( 2401): waitForAlarm result :4
,V/AlarmManager( 2401): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 370, Delta = 20
,V/AlarmManager( 2401): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/NtpTrustedTime( 2401): forceRefresh() from cache miss
,D/NtpTrustedTime( 2401): forceRefresh Fail.
,I/jxcore-log( 6450): JXcore Cordova bridge is ready!
I/jxcore-log( 6450): 
,W/jxcore-log( 6450): JXcore engine is started
,I/jxcore-log( 6450): Toggling radios to true
I/jxcore-log( 6450): 
,W/ActivityManager( 2401): Permission Denial: getCurrentUser() from pid=6450, uid=10648 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 2401): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 2401): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6450, uid=10648 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 2401): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/BluetoothManagerService( 2401): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:620)
W/BluetoothManagerService( 2401): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService( 2401): 	at android.os.Binder.execTransact(Binder.java:404)
W/BluetoothManagerService( 2401): 	at dalvik.system.NativeStart.run(Native Method)
E/DevicePolicyManagerService( 2401): getAllowBluetoothMode - value retunrs : 2
,D/BluetoothManagerService( 2401): foregroundUser: 0
,E/BluetoothManagerService( 2401): Package is exist.
,D/BluetoothAdapterState( 5115): CURRENT_STATE=OFF, MSG = USER_TURN_ON
I/BluetoothAdapterState( 5115): Bluetooth adapter state changed: 10-> 11
I/WifiManager( 6450): packageName : com.test.thalitest
D/BluetoothAdapterService( 5115): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5115): updateAdapterState state is 11
I/WifiManager( 6450): setWifiEnabled : true
,D/BluetoothAdapterService( 5115): Broadcasting updateAdapterState() to 1 receivers.
I/WifiService( 2401): setWifiEnabled: true pid=6450, uid=10648
D/BluetoothAdapterService( 5115): Autoconnection is available 
D/BluetoothAdapterService( 5115): updateAdapterState prevState = 10newState = 11
D/BtConfig.SecureMode( 5115): isSecureModeOn:false
,D/BtSettings.ProfileConfig( 5115): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 5115): isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,D/BtSettings.ProfileConfig( 5115): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/ActivityManager( 2401): Permission Denial: getCurrentUser() from pid=6450, uid=10648 requires android.permission.INTERACT_ACROSS_USERS
W/InputMethodManagerService( 2401): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 2401): [BT Setting State] State =11
D/PhoneApp( 2750): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 11
W/WifiService( 2401): Failed getting userId using ActivityManagerNative
W/WifiService( 2401): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6450, uid=10648 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2401): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2401): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2401): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2401): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2401): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2401): 	at dalvik.system.NativeStart.run(Native Method)
I/SamsungIME( 2947): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
W/BluetoothAdapterService( 5115): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5115): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 5115): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5115): getProfileSaveSetting: com.android.bluetooth.hid.HidService
I/QuickConnect[1.1][2] ( 5089): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_ON
W/BluetoothAdapterService( 5115): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5115): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5115): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 5115): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,I/WifiService( 2401): disconnect: pid=6450, uid=10648
E/WifiHW  ( 2401): ##################### set firmware type 0 #####################
W/BluetoothAdapterService( 5115): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 5115): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
I/WifiHW  ( 1915): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
E/WifiHW  ( 1915): Cannot open "/data/.cid.info": No such file or directory
I/WifiHW  ( 1915): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
E/WifiHW  ( 1915): TEMP_FAILURE_RETRY complete
,D/SoftapController( 1915): Softap fwReload - Ok
,I/jxcore-log( 6450): Radios toggled
I/jxcore-log( 6450): 
,I/jxcore-log( 6450): My device name is: samsung-SM-G800F
I/jxcore-log( 6450): 
,D/BluetoothNotiBroadcastReceiver( 5579): onReceive
W/BluetoothAdapterService( 5115): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 5115): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/CommandListener( 1915): Setting iface cfg
,D/CommandListener( 1915): Trying to bring down wlan0
W/BluetoothAdapterService( 5115): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5115): Unable to stop service com.android.bluetooth.gatt.GattService. Invalid state: 12
W/BluetoothAdapterService( 5115): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 5115): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
W/BluetoothAdapterService( 5115): Not skipping com.android.bluetooth.hfp.HeadsetService
,I/SELinux ( 6605): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6605):  
D/WifiHW  ( 2401): Skip the update_ctrl_interface
D/WifiHW  ( 2401): Skip the update_ctrl_interface
,E/WifiHW  ( 2401): supplicant_name : p2p_supplicant
,W/BluetoothAdapterService( 5115): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 5115): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 5115): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/WifiMonitor( 2401): startMonitoring(wlan0) with mConnected = false
I/SELinux ( 6605): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6605):  
I/SELinux ( 6605):  
,I/SELinux ( 6605): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6605): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6605): >>>>> Normal User
,E/dalvikvm( 6605): >>>>> pl.k2.droidoaudioteka [ userId:0 | appId:10066 ]
,E/SELinux ( 6605): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/dalvikvm( 6605): Enabling JNI app bug workarounds for target SDK version 7...
,I/wpa_supplicant( 6609): wpa_supplicant v2.1-devel-4.4.22014-07-16/12:43:14
I/wpa_supplicant( 6609): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 6609): Successfully initialized wpa_supplicant
,I/wpa_supplicant( 6609): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 6609): getIMSI cannot open file
,E/wpa_supplicant( 6609): Interworking config: - SIM READ ERROR
,D/TimaKeyStoreProvider( 6605): in addTimaSignatureService
,D/HeadsetService( 5115): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 5115): classInitNative: succeeds
,D/HeadsetStateMachine( 5115): Version 1.5
,D/HeadsetStateMachine( 5115): make
,D/QuickConnect[1.1][2] ( 5089): HeadsetProfile.onServiceConnected - Bluetooth service connected
,E/HeadsetStateMachine( 5115): # of Max HF connection is 2
,W/BluetoothAdapterService( 5115): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 5115): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/TimaKeyStoreProvider( 6605): Cannot add TimaSignature Service, License check Failed
,W/BluetoothAdapterService( 5115): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5115): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 5115): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5115): Not skipping com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5115): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5115): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 5115): Not skipping com.android.bluetooth.pan.PanService
,D/ActivityThread( 6605): Added TimaKesytore provider
,W/BluetoothAdapterService( 5115): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 5115): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5115): Not skipping com.android.bluetooth.map.BluetoothMapService
,I/wpa_supplicant( 6609): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 6609): getIMSI cannot open file
,E/wpa_supplicant( 6609): Interworking config: - SIM READ ERROR
,I/wpa_supplicant( 6609): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 6609): rfkill: Cannot open RFKILL control device
W/BluetoothAdapterService( 5115): check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5115): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService,
W/BluetoothAdapterService( 5115): Not skipping com.broadcom.bt.service.sap.SapService
,I/bluedroid( 5115): get_profile_interface handsfree,
,I/BluetoothAdapterState( 5115): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false,
,D/BluetoothAtMessage( 5115): createCMTIContentObservers
,D/HeadsetStateMachine( 5115): Enter Disconnected: -2
,E/HeadsetStateMachine( 5115): set to mRemoteBrsf = 0
,D/HeadsetStateMachine( 5115): map size, before remove : 0
D/HeadsetStateMachine( 5115): map size, after remove: 0
,D/HeadsetStateMachine( 5115): mNextConnectingDevice : null
,D/BluetoothA2dp( 5089): Proxy object connected
,D/BluetoothA2dp( 4125): Proxy object connected
,D/QuickConnect[1.1][2] ( 5089): A2dpProfile.onServiceConnected - Bluetooth service connected
D/A2dpService( 5115): Received start request. Starting profile...,
I/BluetoothA2dpServiceJni( 5115): classInitNative: succeeds
,D/A2dpStateMachine( 5115): make,
,I/bluedroid( 5115): get_profile_interface a2dp,
,I/GKI_LINUX( 5115): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting,
D/A2dpStateMachine( 5115): Enter Disconnected: -2
,I/BluetoothAvrcpServiceJni( 5115): classInitNative: succeeds
,I/bluedroid( 5115): get_profile_interface avrcp,
,D/MediaFocusControl( 2401): >>> registerRemoteControlDisplay,
,I/BluetoothHidServiceJni( 5115): classInitNative: succeeds,
,D/BluetoothInputDevice( 5089): Proxy object connected,
D/HidService( 5115): Received start request. Starting profile...
I/bluedroid( 5115): get_profile_interface hidhost
D/HidService( 5115): setHidService(): set to: null,
,I/BluetoothHealthServiceJni( 5115): classInitNative: succeeds,
,D/QuickConnect[1.1][2] ( 5089): HidProfile.onServiceConnected - Bluetooth service connected,
,D/HealthService( 5115): Received start request. Starting profile...,
,I/bluedroid( 5115): get_profile_interface health
,I/BluetoothPanServiceJni( 5115): classInitNative(L105): succeeds,
D/PanService( 5115): Received start request. Starting profile...
D/BluetoothPanServiceJni( 5115): initializeNative(L110): pan
,I/bluedroid( 5115): get_profile_interface pan,
,D/BluetoothTethering( 2401): got CMD_CHANNEL_HALF_CONNECTED,
,D/BluetoothMapService( 5115): Received start request. Starting profile...,
,W/BluetoothMapMasInstance( 5115): mAccount : null,
D/HeadsetStateMachine( 5115): Try to query the phonestate on bind
,D/dalvikvm( 2401): GC_EXPLICIT freed 3014K, 75% free 24591K/97084K, paused 18ms+22ms, total 252ms
,D/BluetoothPhoneService( 2750): handleMessage: 4
,V/BluetoothPhoneService( 2750): Call state Converted2: IDLE/IDLE -> 6
,W/BluetoothHeadset( 2750): Proxy not attached to service
,D/HeadsetStateMachine( 5115): Proxy object connected,
D/HeadsetPhoneState( 5115): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetStateMachine( 5115): Disconnected process message: 11
,I/BluetoothSAPServiceJni( 5115): classInitNative(L204): succeeds
D/SapService( 5115): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 5115): initializeNative(L209): sap
I/bluedroid( 5115): get_profile_interface sap
,D/BluetoothA2dp( 2401): Proxy object connected
,D/HeadsetPhoneState( 5115): sendDeviceDataStateChanged
D/HeadsetStateMachine( 5115): Disconnected process message: 20
D/HeadsetPhoneState( 5115): Signal level : previous=0 curr=0
,D/BluetoothAdapterService( 5115): Profile still not running:com.broadcom.bt.service.sap.SapService
V/HeadsetService( 5115): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5115): Disconnected process message: 10
D/HeadsetPhoneState( 5115): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 5115): Disconnected process message: 11
D/BluetoothPan( 2401): BluetoothPAN Proxy object connected
D/BluetoothAdapterService( 5115): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5115): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5115): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5115): Profile still not running:com.broadcom.bt.service.sap.SapService
,D/BluetoothAdapterService( 5115): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterState( 5115): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 5115): enable
,D/GKI_LINUX( 5115): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
,E/bt-btif ( 5115): Calling BTA_HhEnable
,E/bt-btif ( 5115): btif_storage_get_adapter_property service_mask:0x160040
E/BluetoothServiceJni( 5115): populateRssiValuesNative
I/bluedroid( 5115): getModelRssiValues
,E/BluetoothServiceJni( 5115): model_rssi_values_callback: low = -75, mid = -65, high = 127
D/dalvikvm( 6605): GC_CONCURRENT freed 3001K, 31% free 9572K/13712K, paused 3ms+6ms, total 80ms
,D/dalvikvm( 6605): WAIT_FOR_CONCURRENT_GC blocked 67ms
,E/BluetoothRemoteDevices( 5115): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BtConfig.SecureMode( 5115): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5115): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 241
,E/BluetoothRemoteDevices( 5115): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 10
,D/BtConfig.SecureMode( 5115): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5115): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 241
,E/BluetoothRemoteDevices( 5115): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
,D/BtConfig.SecureMode( 5115): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5115): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 241
,E/BluetoothRemoteDevices( 5115): devicePropertyChangedCallback: bdDevice: F8:CF:C5:D9:E5:61, value is empty for type: 10
,D/BtConfig.SecureMode( 5115): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5115): devicePropertyChangedCallback: bdDevice: F8:CF:C5:D9:E5:61, value is empty for type: 241
,E/BluetoothRemoteDevices( 5115): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
,D/BtConfig.SecureMode( 5115): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5115): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 241
,E/BluetoothRemoteDevices( 5115): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,D/BtConfig.SecureMode( 5115): isSecureModeOn:false
,W/System.err( 6605): java.io.FileNotFoundException: /system/etc/vold.fstab: open failed: ENOENT (No such file or directory)
,E/BluetoothRemoteDevices( 5115): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 241
W/System.err( 6605): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 6605): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 6605): 	at java.util.Scanner.<init>(Scanner.java:158)
W/System.err( 6605): 	at java.util.Scanner.<init>(Scanner.java:138)
W/System.err( 6605): 	at pl.k2.droidoaudioteka.common.helpers.StorageOptions.readVoldFile(StorageOptions.java:107)
W/System.err( 6605): 	at pl.k2.droidoaudioteka.common.helpers.StorageOptions.determineStorageOptions(StorageOptions.java:31)
W/System.err( 6605): 	at pl.k2.droidoaudioteka.uipl.managers.impl.ResManager.<init>(ResManager.java:81)
W/System.err( 6605): 	at pl.k2.droidoaudioteka.uipl.managers.impl.ResManager.<init>(ResManager.java:129)
W/System.err( 6605): 	at pl.k2.droidoaudioteka.ui.AudiotekaApplication.onCreate(AudiotekaApplication.java:171)
W/System.err( 6605): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 6605): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 6605): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
,W/System.err( 6605): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 6605): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6605): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6605): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 6605): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 6605): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 6605): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 6605): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 6605): 	at dalvik.system.NativeStart.main(Native Method)
,W/System.err( 6605): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err( 6605): 	at libcore.io.Posix.open(Native Method)
,W/System.err( 6605): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 6605): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 6605): 	... 20 more
,E/BluetoothRemoteDevices( 5115): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
W/System.err( 6605): file res dir: /data/data/pl.k2.droidoaudioteka/files
,W/System.err( 6605): Excternal dir: /mnt/sdcard
,D/BtConfig.SecureMode( 5115): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5115): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 241
,E/BluetoothRemoteDevices( 5115): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,D/BtConfig.SecureMode( 5115): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5115): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 241
E/bt-btif ( 5115): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
E/bt-btif ( 5115): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
E/bt-btif ( 5115): btif_sock_init: !radio_req && !rfc_init
,D/IOP_DB_BT( 5115): db_open: file /etc/bluetooth/iop_bt.db
,D/IOP_DB_BT( 5115): db_open: db_open : handle 2010063916l, read 9734 bytes onto local cache
D/IOP_DB_BT( 5115): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 5115): db_query: result 1
I/        ( 5115): iop_db_open: iop_db_open status 0
,I/bte_conf( 5115): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 5115): [1] primary_record=1 vendor_id=0x0075 vendor_id_source=0x0001 product_id=0x0100 version=0x0200
I/bte_conf( 5115): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 5115): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/BluetoothAdapterState( 5115): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5115): ScanMode =  20
,D/BluetoothAdapterProperties( 5115): State =  11
D/BtConfig.SecureMode( 5115): isSecureModeOn:false
D/BtConfig.SecureMode( 5115): isSecureModeOn:false
D/BtConfig.SecureMode( 5115): isSecureModeOn:false
,D/BtConfig.SecureMode( 5115): isSecureModeOn:false
D/BtConfig.SecureMode( 5115): isSecureModeOn:false
D/BtConfig.SecureMode( 5115): isSecureModeOn:false
D/BtConfig.SecureMode( 5115): isSecureModeOn:false
D/BtConfig.SecureMode( 5115): isSecureModeOn:false
I/BluetoothAdapterState( 5115): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 5115): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5115): updateAdapterState state is 12
,D/BluetoothAdapterService( 5115): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothAdapterService(1109851232)( 5115): Register RemoteMessageListener
,D/BluetoothA2dp( 2401): onBluetoothStateChange: up=true
D/HeadsetService( 5115): registerMessageListener
D/BluetoothAdapterService( 5115): Autoconnection is available 
D/BluetoothAdapterService( 5115): updateAdapterState prevState = 11newState = 12
,D/BluetoothAdapterService( 5115): starting service from this receiver
,D/HeadsetStateMachine( 5115): Disconnected process message: 70
,D/BluetoothA2dp( 4125): onBluetoothStateChange: up=true
,D/HeadsetStateMachine( 5115): processRegisterMessageListener : 2, com.android.bluetooth.btservice.RemoteDevices$1@422df5c0
,W/ContextImpl( 5115): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.startService:506 com.android.bluetooth.btservice.AdapterService.updateAdapterState:653 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
,D/BluetoothInputDevice( 5089): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 5089): onBluetoothStateChange: up=true
,D/BluetoothAdapterService( 5115): initWakeLock, pfd lock: {ParcelFileDescriptor: FileDescriptor[85]}, pfd unlock: {ParcelFileDescriptor: FileDescriptor[86]}
,D/bluedroid( 5115): init_wake_lock lock_fd:85, unlock_fd:86
,I/BluetoothAdapterState( 5115): Entering On State from state = 11
W/InputMethodManagerService( 2401): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 2401): [BT Setting State] State =12
,I/InputMethodManagerService( 2401): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
D/PhoneApp( 2750): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 12
I/SamsungIME( 2947): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BluetoothAdapterService(1109851232)( 5115): Get Bonded Devices being called
D/BluetoothHeadset( 2750): registerListener : 11, listenercom.android.phone.PhoneGlobals$MessageListener@4244f898, true
D/BluetoothHeadset( 2750): registerMessageListener
I/QuickConnect[1.1][2] ( 5089): BluetoothHelper.ACTION_STATE_CHANGED - STATE_ON
D/HeadsetService( 5115): registerMessageListener
D/HeadsetService( 5115): registerMessageListener
D/HeadsetStateMachine( 5115): Disconnected process message: 70
D/HeadsetStateMachine( 5115): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@42354440
D/PhoneApp( 2750): registerMessageListener
D/BluetoothPanServiceJni( 5115): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
I/BluetoothPbapService( 5115): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,I/BluetoothPbapService( 5115): Handler(): got msg=1
,V/BluetoothPbapService( 5115): PBAP Service initSocket try: 0
,W/BluetoothAdapter( 5115): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothMapMasInstance( 5115): set MAP SDP message type : 1
,E/BluetoothServiceJni( 5115): SOCK FLAG = 1 ***********************
,D/BluetoothPbapService( 5115): PBAP Socket is BluetoothServerSocket
,W/BluetoothAdapter( 5115): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 5115): SOCK FLAG = 3 ***********************
D/STATUSBAR-IconMerger( 2581): checkOverflow(336), More:false, Req:false Child:2
,V/MaBo    ( 6605): preinstalledFolder externalSD nie istnieje /mnt/sdcard/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6605): Katalog z preintalacją NIE istnieje!!!! /storage/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6605): Katalog z preintalacją NIE istnieje!!!! /mnt/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,D/GKI_LINUX( 5115): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,I/System.out( 6605): moge zapisać w resDir?true
,V/MaBo    ( 6605): preinstalledFolder externalSD nie istnieje /mnt/sdcard/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6605): Katalog z preintalacją NIE istnieje!!!! /storage/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6605): Katalog z preintalacją NIE istnieje!!!! /mnt/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,W/GAV2    ( 6605): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GAV2    ( 6605): Thread[main,5,main]: ExceptionReporter created, original handler is pl.k2.droidoaudioteka.common.helpers.AudiotekaExceptionHandler
,I/AUDIOTEKA_GA( 6605): init tracking...
,I/AUDIOTEKA_GA( 6605): app started!
,I/BugSenseHandler( 6605): Registering default exceptions handler
,D/AuthorizationBluetoothService( 2845): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/DownloadService( 6605): Tworzenie serwisu - onCreate()
,I/DownloadService( 6605): Start serwisu - onStart()
,I/knox    ( 5032): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 5032): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 5032): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 5032): KNOXAgentService : onCreate()
,I/SELinux ( 6644): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6644):  
,D/knox    ( 5032): KNOXAgentService : set alarms for deniallog and usage data upload
,D/knox    ( 5032): KNOXAgentService. startJobThread() start
D/knox    ( 5032): KNOXAgentService. JobThread()
D/knox    ( 5032): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 5032): KNOXAgentService. startJobThread() wait
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 12% free 9508K/10688K, paused 2ms+3ms, total 34ms
,I/SELinux ( 6644): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6644):  
I/SELinux ( 6644):  
,I/SELinux ( 6644): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6644): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6644): >>>>> Normal User
,E/dalvikvm( 6644): >>>>> tv.peel.smartremote [ userId:0 | appId:10165 ]
,E/SELinux ( 6644): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9508K/10688K, paused 2ms+3ms, total 28ms
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9508K/10688K, paused 3ms+3ms, total 27ms
,D/knox    ( 5032): KNOXAgentService : onDestroy().
,I/BugSenseHandler( 6605): Registering default exceptions handler
,D/knox    ( 5032): ModuleBase.cancelAllAlarmManageModule()
,I/BugSenseHandler( 6605): Flushing...
,I/BugSenseHandler( 6605): Registering default exceptions handler
,I/PlayerService( 6605): Tworzenie serwisu - onCreate()
,I/MediaFocusControl( 2401):   Remote Control   registerMediaButtonIntent() for PendingIntent{42eee858: PendingIntentRecord{43007dc8 pl.k2.droidoaudioteka broadcastIntent}}
,V/KeyguardUpdateMonitor( 2581): handleSetGenerationId(g=2, clear=true)
,V/AUDIOTEKA_MB( 6605): new AudioManagerFocusWrapper in playerservice oncreate
,I/PlayerService( 6605): Start serwisu - onStart()
I/BugSenseHandler( 6605): Flushing...
,I/BugSenseHandler( 6605): Registering default exceptions handler
,D/TimaKeyStoreProvider( 6644): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6644): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6644): Added TimaKesytore provider
,D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2401): interfaceStatusChanged wlan0, true
,E/Tethering( 2401): No numeric data
,I/ConnectivityService( 2401): defaultVal : 1, tetherEnabledInSettings : true
D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
D/Tethering( 2401): interfaceStatusChanged wlan0, true
D/NtpTrustedTime( 2401): forceRefresh() from cache miss
,D/NtpTrustedTime( 2401): forceRefresh Fail.
,V/NetworkStats( 2401): performPollLocked(flags=0x1)
D/Tethering( 2401): sendTetherStateChangedBroadcast 1, 0, 0
,V/NetworkStats( 2401): performPollLocked() took 15ms
I/wpa_supplicant( 6609): wlan0: Setting scan request: 0 sec 100000 usec
D/NtpTrustedTime( 2401): forceRefresh() from cache miss
D/NtpTrustedTime( 2401): forceRefresh Fail.
D/dalvikvm( 6644): GC_CONCURRENT freed 2998K, 31% free 9578K/13712K, paused 6ms+6ms, total 71ms
D/dalvikvm( 6644): WAIT_FOR_CONCURRENT_GC blocked 62ms
,I/wpa_supplicant( 6609): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 6609): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 6609): rfkill: Cannot open RFKILL control device
D/Tethering( 2401): interfaceLinkStateChanged p2p0, true
,D/Tethering( 2401): interfaceStatusChanged p2p0, true
D/Tethering( 2401): interfaceLinkStateChanged p2p0, true
,D/Tethering( 2401): interfaceStatusChanged p2p0, true
,I/wpa_supplicant( 6609): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/ActivityManager( 2401): Killing 5659:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,I/wpa_supplicant( 6609): P2P: initialized channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
I/wpa_supplicant( 6609): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 6609): Skip scan - bUseNetwork false
,D/WifiStateMachine( 2401): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,D/WifiNative( 2401): callSECApiString - ID [21]
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
I/wpa_supplicant( 6609): HOTSPOT20_ENABLE called
I/wpa_supplicant( 6609): wlan0: HS20_DISABLED_COMPLETE normal
,D/WifiNative( 2401): callSECApiInt - ID [65]
,E/WifiConfigStore( 2401): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
W/ContextImpl( 5579): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/WifiNative( 2401): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 6609): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 6609): reset timer : RESET_TIMER 0
I/wpa_supplicant( 6609): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 6609): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 6609): First Scan Start
,I/wpa_supplicant( 6609): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine( 2401): Set the Nv default ccode
,D/WifiStateMachine( 2401): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,D/WifiP2pService( 2401): P2pDisabledState{ what=131203 }
E/WifiStateMachine( 2401): HS20_DISABLED_COMPLETEnormal
,W/Settings( 5369): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/CommandListener( 1915): Setting iface cfg
,D/CommandListener( 1915): Trying to bring up p2p0
,D/WifiMonitor( 2401): startMonitoring(p2p0) with mConnected = true
D/WifiP2pService( 2401): P2pEnablingState
D/WifiP2pService( 2401): P2pEnablingState{ what=147457 }
D/WifiP2pService( 2401): P2p socket connection successful
D/WifiP2pService( 2401): P2pEnabledState
,E/WifiStateMachine( 2401): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/QuickConnect[1.1][2] ( 5089): SconnectManager.INetworkStateListener, onEnabled - mNetworkState : 4
D/WifiP2pService( 2401): sending p2p connection changed broadcast: IDLE
D/WifiDisplayController( 2401): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController( 2401): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 2401): disconnect
D/WifiDisplayController( 2401): updateConnection
D/WifiDisplayController( 2401): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 2401): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/QuickConnect[1.1][2] ( 5089): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
D/WifiDisplayAdapter( 2401): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/wpa_supplicant( 6609): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
W/WifiP2pStateTracker( 2401): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/WifiDisplayController( 2401): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/QuickConnect[1.1][2] ( 5089): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
,D/QuickConnect[1.1][2] ( 5089): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
,I/System.out( 6605): Thread-612(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
D/WifiP2pService( 2401): DeviceAddress: 02:e0:6d
,D/WifiDisplayController( 2401): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: S5mini-1
D/WifiDisplayController( 2401):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiDisplayController( 2401):  primary type: 10-0050F204-5
D/WifiDisplayController( 2401):  secondary type: null
D/WifiDisplayController( 2401):  wps: 0
D/WifiDisplayController( 2401):  grpcapab: 0
D/WifiDisplayController( 2401):  devcapab: 0
D/WifiDisplayController( 2401):  status: 3
D/WifiDisplayController( 2401):  wfdInfo: null
D/WifiDisplayController( 2401):  groupownerAddress: null
D/WifiDisplayController( 2401):  GOdeviceName: null
D/WifiDisplayController( 2401):  interfaceAddress: 
D/WifiDisplayController( 2401):  SConnectInfo : null
,D/WifiP2pService( 2401): sending p2p persistent groups changed broadcast
I/System.out( 6605): Thread-612(ApacheHTTPLog):isShipBuild true
I/System.out( 6605): Thread-612(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/WifiP2pService( 2401): InactiveState
,D/WifiP2pService( 2401): InactiveState{ what=139287 }
D/WifiP2pService( 2401): P2pEnabledState{ what=139287 }
,D/QuickConnect[1.1][2] ( 5089): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
,D/WifiP2pService( 2401): DefaultState{ what=139287 }
I/System.out( 6605): Thread-617(ApacheHTTPLog):isShipBuild true
I/System.out( 6605): Thread-617(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/LocalBluetoothProfileManager( 5579): Adding local A2DP profile
,W/ContextImpl( 5579): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
,D/LocalBluetoothProfileManager( 5579): Adding local HEADSET profile
I/System.out( 6605): pool-1-thread-1 calls detatch()
,W/BugSenseHandler( 6605): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
I/System.out( 6605): pool-1-thread-2 calls detatch()
E/BluetoothHeadset( 5579): BTStateChangeCB is registed
,W/BugSenseHandler( 6605): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
,E/BluetoothHeadset( 5579): BluetoothHeadset service is binded
W/ContextImpl( 5579): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
,W/ContextImpl( 5579): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/Bluetoothsap( 5579): bindService called to Bluetooth SAP Service
,W/ContextImpl( 5579): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
,D/LocalBluetoothProfileManager( 5579): PANU : true
,D/LocalBluetoothProfileManager( 5579): Adding local MAP profile
,W/ContextImpl( 5579): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
,D/BluetoothMap( 5579): Create BluetoothMap proxy object
W/ContextImpl( 5579): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
,W/ContextImpl( 5579): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,D/Bluetoothsap( 5579): bindService called to Bluetooth SAP Service
,D/LocalBluetoothProfileManager( 5579): LocalBluetoothProfileManager construction complete
,W/ContextImpl( 5579): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/DockEventReceiver( 5579): finishStartingService: stopping service
D/BluetoothNotiBroadcastReceiver( 5579): onReceive
D/BluetoothA2dp( 5579): Proxy object connected
D/A2dpProfile( 5579): Bluetooth service connected
,D/BtConfig.SecureMode( 5115): isSecureModeOn:false
,D/HeadsetProfile( 5579): Bluetooth service connected
D/AuthorizationBluetoothService( 2845): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 2845): Proximity feature is not enabled.
,D/Bluetoothsap( 5579): BluetoothSAP Proxy object connected
,D/SapProfile( 5579): Bluetooth service connected
,D/Bluetoothsap( 5579): getConnectedDevices()
,D/BluetoothInputDevice( 5579): Proxy object connected
,D/HidProfile( 5579): Bluetooth service connected
,W/BluetoothAdapter( 5115): getBluetoothService() called with no BluetoothManagerCallback
,D/BluetoothPan( 5579): BluetoothPAN Proxy object connected
E/BluetoothServiceJni( 5115): SOCK FLAG = 0 ***********************
,D/GKI_LINUX( 5115): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
I/BtOppRfcommListener( 5115): Accept thread started.
,D/PanProfile( 5579): Bluetooth service connected
,D/BluetoothMap( 5579): Proxy object connected
,D/MapProfile( 5579): Bluetooth service connected
,D/BluetoothPbap( 5579): Proxy object connected
D/PbapServerProfile( 5579): Bluetooth service connected
D/Bluetoothsap( 5579): BluetoothSAP Proxy object connected
D/SapProfile( 5579): Bluetooth service connected
,D/Bluetoothsap( 5579): getConnectedDevices()
,I/knox    ( 5032): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 5032): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 5032): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 5032): KNOXAgentService : onCreate()
,D/knox    ( 5032): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 5032): KNOXAgentService. startJobThread() start
,D/knox    ( 5032): KNOXAgentService. JobThread()
D/knox    ( 5032): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 5032): KNOXAgentService. startJobThread() wait
,D/knox    ( 5032): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
,D/knox    ( 5032): KNOXAgentService : onDestroy().
,D/knox    ( 5032): ModuleBase.cancelAllAlarmManageModule()
,D/NearbySettings( 5579): MountReceiver.onReceive - Create HandlerThread
,D/NearbySettings( 5579): MountReceiver.onReceive - Start HandlerThread
D/NearbySettings( 5579): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 5579): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 5579): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5579): DMSUtil.isNetworkConnected - WIFI: IDLE
I/NearbySettings( 5579): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5579): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5579): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 5579): MountReceiver.mPrefHandler - 7002
,D/FileShare-Server( 6108): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Server( 6108): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
,D/GKI_LINUX( 5115): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,I/wpa_supplicant( 6609): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,I/wpa_supplicant( 6609): nl80211: Received scan results (5 BSSes)
I/wpa_supplicant( 6609): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 6609): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 6609): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2401): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 6609): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,I/wpa_supplicant( 6609): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 6609): Associated with C0.AA.48
,I/wpa_supplicant( 6609): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2401): interfaceStatusChanged wlan0, true
,E/WifiStateMachine( 2401): Error! unhandled message{ when=-25ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2401): interfaceStatusChanged wlan0, true
D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2401): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 6609): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 6609): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 6609): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 6609): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2401): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2401): interfaceStatusChanged wlan0, true
,D/WifiNative( 2401): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 6682): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6682):  
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 6682): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6682):  
I/SELinux ( 6682):  
,I/SELinux ( 6682): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6682): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6682): >>>>> Normal User
,E/dalvikvm( 6682): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 6682): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 6682): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6682): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6682): Added TimaKesytore provider
,D/WifiP2pService( 2401): InactiveState{ what=143375 }
,D/WifiP2pService( 2401): P2pEnabledState{ what=143375 }
,D/dalvikvm( 6682): GC_CONCURRENT freed 2990K, 31% free 9578K/13708K, paused 12ms+1ms, total 29ms
,D/dalvikvm( 6682): WAIT_FOR_CONCURRENT_GC blocked 11ms
,I/System.out( 6682): Inside WakeupProvider
,I/System.out( 6682): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 6682): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 6682): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 6682): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,I/dhcpcd  ( 6696): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 6696): bssid match
,D/AmoledAdjustTimer( 2401): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4
,D/NearbySettings( 5579): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 5579): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5579): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
,D/DialogFlow( 6682): initQueue()
I/NearbySettings( 5579): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5579): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5579): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 5579): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2401): Killing 5822:com.android.calendar/u0a144 (adj 15): empty #43
,D/WifiP2pService( 2401): InactiveState{ what=143375 }
,D/WifiP2pService( 2401): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2401): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2401): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2401): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2401): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2401): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/ConnectivityService( 2401): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2401): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2401): evaluateTrafficStatsPolling
D/ConnectivityService( 2401): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2401): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2401): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/NearbySettings( 5579): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 5579): MountReceiver.onReceive - Keep current state
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
D/ConnectivityService( 2401): handleConnectivityChange: setting default proxy info 
,V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,D/NearbySettings( 5579): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 5579): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5579): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 5579): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5579): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5579): MountReceiver.onReceive - Keep current state
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/NetworkStats( 2401): updateIfacesLocked()
,D/NtpTrustedTime( 2401): forceRefresh() from cache miss
V/NetworkStats( 2401): performPollLocked(flags=0x1)
,V/NetworkStats( 2401): performPollLocked() took 15ms
,D/NearbySettings( 5579): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 5579): MountReceiver.onReceive - Keep current state
,I/SurfaceFlinger( 1920): id=20 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 2401): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2401
,D/NtpTrustedTime( 2401): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1453758255841 mCachedNtpElapsedRealtime : 151274 mCachedNtpCertainty : 11
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
V/NetworkStats( 2401): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/Tethering( 2401): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2401): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2401): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
D/NtpTrustedTime( 2401): currentTimeMillis() cache hit
D/        ( 2401): Setting time of day to sec=1453758256
,D/        ( 2401): Trying to open a file
D/        ( 2401): File Open Success
D/        ( 2401): File Close Success
,V/AlarmManager( 2401): waitForAlarm result :65536
,I/        ( 2401): DRM_TIME_PATH CHMOD 660 for resetState done 
D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_SET
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,I/DBG_DM  ( 4669): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
I/PCWCLIENTTRACE_PushUtil( 6229): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6229): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6229): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6229): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
D/StatusBar-DoNotDistrub( 2581): Received intent with android.intent.action.TIME_SET action
,D/StatusBar-DoNotDistrub( 2581): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/NotificationMgr( 2750): updateNotificationsAtStartup()...
D/NotificationMgr( 2750): - start call log query...
,W/Settings( 2401): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Parcel  ( 2401): nm 23
,I/AudioService( 2401): getStreamVolume 5 index 110
D/StatusBar-DoNotDistrub( 2581): sendBroadcast android.intent.action.DORMANT_MODE_OFF
D/StatusBar-DoNotDistrub( 2581): The STREAM NOTIFICATION volume is 0
,D/STATUSBAR-StatusBarManagerService( 2401): manageDisableList what=0x0 pkg=com.android.systemui
I/PrGenericPlugin( 1923): [A] ENTER onAcquireDrmInfo : 0x8da
I/PrGenericPlugin( 1923): [A] LEAVE onAcquireDrmInfo : 0x8da
I/DrmEventService( 2401):  no response from SecureClock 
,D/STATUSBAR-NotificationService( 2401): received android.intent.action.DORMANT_MODE_OFF
D/LightsService( 2401): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2401) 
,I/SensorManagerA( 2401): getReportingMode :: sensor.mType = 5
,D/LightsService( 2401): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/Sensors ( 2401): LightSensor setDelay = 200000000
D/Sensors ( 2401): LightSensor setSensorDelay = 200000000
D/Sensors ( 2401): Light sensor flush: not enabled 0
D/Sensors ( 2401): LightSensor enable = 1
D/Sensors ( 2401): LightSensor enableSensor = 1
D/SensorManager( 2401): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/NotificationMgr( 2750): call log query complete.
D/NotificationMgr( 2750): call log cursor count : 0
,D/NotificationMgr( 2750): call log cursor count2 : null
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,I/DBG_DM  ( 4669): [3.19.140541][Line:609][onReceive] ----------- XEVENT_DM_INIT WIFI ok
,I/DBG_DM  ( 4669): [3.19.140541][Line:214][xdmAgentTaskHandler] XEVENT_DM_INIT
,I/DBG_DM  ( 4669): [3.19.140541][Line:432][xdmInitAdpWaitSystemRootingCheck] Check completed.
,I/DBG_DM  ( 4669): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/DBG_DM  ( 4669): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 4669): [3.19.140541][Line:78][xdmFeatureGetBearerSettingFromCSCFotaDataBase] 
,I/SELinux ( 6745): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6745):  
I/SELinux ( 6745): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6745):  
I/SELinux ( 6745):  
I/SELinux ( 6745): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6745): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6745): >>>>> Normal User
E/dalvikvm( 6745): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
,E/SELinux ( 6745): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/Sensors ( 2401): LightSensor enable = 0
,D/Sensors ( 2401): LightSensor enableSensor = 0
,D/SensorManager( 2401): unregisterListener ::   
,D/TimaKeyStoreProvider( 6745): in addTimaSignatureService
D/LightsService( 2401): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2401): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/DBG_DM  ( 4669): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
,D/TimaKeyStoreProvider( 6745): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6745): Added TimaKesytore provider
,I/DBG_DM  ( 4669): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/dalvikvm( 4669): Total arena pages for JIT: 11
,I/dalvikvm( 4669): Total arena pages for JIT: 12
I/dalvikvm( 4669): Total arena pages for JIT: 13
,I/dalvikvm( 4669): Total arena pages for JIT: 14
,I/dalvikvm( 4669): Total arena pages for JIT: 15
,I/dalvikvm( 4669): Total arena pages for JIT: 16
,I/dalvikvm( 4669): Total arena pages for JIT: 17
,I/DBG_DM  ( 4669): [3.19.140541][Line:5949][xdbGetFUMOInitiatedType] Initiated Type: 2
,I/DBG_DM  ( 4669): [3.19.140541][Line:119][xdmInitAdpEXTInit] nStatus [220]
,I/DBG_DM  ( 4669): [3.19.140541][Line:463][xdmGetEnableLiveDemoFromCSCFeature] enable LiveDemo : false
,E/DBG_DM  ( 4669): Warning!!! [3.19.140541][Line:65][xdmInitAdpGetSIMLockState] SIM Status is not ready
,D/dalvikvm( 6745): GC_CONCURRENT freed 2994K, 31% free 9575K/13708K, paused 3ms+1ms, total 87ms
,D/dalvikvm( 6745): WAIT_FOR_CONCURRENT_GC blocked 73ms
,I/DBG_DM  ( 4669): [3.19.140541][Line:261][xdmInitAdpEXTInit] XDL_STATE_READY_TO_UPDATE
,I/DBG_DM  ( 4669): [3.19.140541][Line:271][xdmAgentTaskHandler] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 4669): [3.19.140541][Line:1854][xdmAgentCheckResumeNoti] 
,I/DBG_DM  ( 4669): [3.19.140541][Line:769][xdmUIEvent] XUI_DL_UPDATE_START
,I/DBG_DM  ( 4669): [3.19.140541][Line:369][handleMessage] event ->214
,I/HarmonyEASService( 2401): Updating for all 1
,W/dalvikvm( 2734): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2734): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2734): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 2734): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 2734): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2734): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 2734): Using platform SSLCertificateSocketFactory
,I/DBG_DM  ( 4669): [3.19.140541][Line:318][xdmBroadcastGetIsSavedNfcMode] m_IsSavedNfcMode : false
,D/PackageManager( 2401): [MSG] WRITE_PACKAGE_RESTRICTIONS
I/DBG_DM  ( 4669): [3.19.140541][Line:546][xuiAdpGetUpdateReport] Get bUpdateReport = false
,I/DBG_DM  ( 4669): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 4669): [3.19.140541][Line:2008][xdmCallUiFotaInstall] 
,I/DBG_DM  ( 4669): [3.19.140541][Line:729][xdmUIEvent] XUI_DL_UPDATE_CONFIRM
W/ContextImpl( 4669): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 com.wssyncmldm.XDMService.xdmCallUiFotaInstall:2023 com.wssyncmldm.XDMService$1.handleMessage:372 android.os.Handler.dispatchMessage:102 
,I/DBG_DM  ( 4669): [3.19.140541][Line:1320][xdmCheckIdleScreen] Idle Screen : false
,I/DBG_DM  ( 4669): [3.19.140541][Line:890][xdmUnRegisterBatteryReceiver] 
,E/DBG_DM  ( 4669): Warning!!! [3.19.140541][Line:898][xdmUnRegisterBatteryReceiver] didn't register
,E/DBG_DM  ( 4669): Warning!!! [3.19.140541][Line:899][xdmUnRegisterBatteryReceiver] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.XDMService$3@4235e6f8
,I/SELinux ( 6763): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6763):  
,I/dalvikvm( 4669): Total arena pages for JIT: 18
,I/DBG_DM  ( 4669): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/SELinux ( 6763): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6763):  
I/SELinux ( 6763):  
,I/SELinux ( 6763): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6763): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6763): >>>>> Normal User
,E/dalvikvm( 6763): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 6763): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 6763): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6763): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6763): Added TimaKesytore provider
,I/DBG_DM  ( 4669): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2401): sendNotification(1) - 4
,W/ResourceType( 2581): Attempt to retrieve bag 0x01030068 which is invalid or in a cycle.
,W/ResourceType( 2581): Attempt to retrieve bag 0x01030067 which is invalid or in a cycle.
,D/ProgressBar( 2581): setProgressDrawable drawableHeight = 12
,D/ProgressBar( 2581): setProgressDrawable drawableHeight = 12
,D/PhoneStatusBar( 2581): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@422be358
,E/dalvikvm( 6745): Could not find class 'android.app.Notification$Action$Builder', referenced from method b.a
W/dalvikvm( 6745): VFY: unable to resolve new-instance 406 (Landroid/app/Notification$Action$Builder;) in Lb;
,D/dalvikvm( 6745): VFY: replacing opcode 0x22 at 0x0000
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 6763): GC_CONCURRENT freed 2998K, 31% free 9571K/13708K, paused 4ms+1ms, total 64ms
,D/dalvikvm( 6763): WAIT_FOR_CONCURRENT_GC blocked 57ms
,W/dalvikvm( 6745): Unable to resolve superclass of Lal; (749)
W/dalvikvm( 6745): Link of class 'Lal;' failed
E/dalvikvm( 6745): Could not find class 'al', referenced from method b.a
W/dalvikvm( 6745): VFY: unable to resolve new-instance 304 (Lal;) in Lb;
,D/dalvikvm( 6745): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 6745): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 6745): Link of class 'Lan;' failed
E/dalvikvm( 6745): Could not find class 'an', referenced from method b.a
W/dalvikvm( 6745): VFY: unable to resolve new-instance 358 (Lan;) in Lb;
,D/dalvikvm( 6745): VFY: replacing opcode 0x22 at 0x002a
I/dalvikvm( 6745): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method b.a
W/dalvikvm( 6745): VFY: unable to resolve virtual method 5407: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 6745): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 6745): Could not find method android.view.View.getTransitionName, referenced from method b.a
W/dalvikvm( 6745): VFY: unable to resolve virtual method 5231: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 6745): VFY: replacing opcode 0x6e at 0x0006
,W/dalvikvm( 6745): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 6745): Could not find class 'android.app.RemoteInput[]', referenced from method b.a
W/dalvikvm( 6745): VFY: unable to resolve new-array 12200 ([Landroid/app/RemoteInput;) in Lb;
,D/dalvikvm( 6745): VFY: replacing opcode 0x23 at 0x0005
,D/dalvikvm( 6745): DexOpt: unable to opt direct call 0x090f at 0x0e in Lb;.a
W/dalvikvm( 6745): Unable to resolve superclass of Lal; (749)
W/dalvikvm( 6745): Link of class 'Lal;' failed
,D/dalvikvm( 6745): DexOpt: unable to opt direct call 0x068d at 0x08 in Lb;.a
W/dalvikvm( 6745): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 6745): Link of class 'Lan;' failed
,D/dalvikvm( 6745): DexOpt: unable to opt direct call 0x0802 at 0x2c in Lb;.a
,D/dalvikvm( 6745): DexOpt: unable to opt direct call 0x0957 at 0x13 in Lb;.a
,I/dalvikvm( 6745): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method dyp.a
W/dalvikvm( 6745): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6745): VFY: replacing opcode 0x6e at 0x000d
,I/SELinux ( 6784): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6784):  
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 6784): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6784):  
I/SELinux ( 6784):  
,I/SELinux ( 6784): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6784): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6784): >>>>> Normal User
,E/dalvikvm( 6784): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 6784): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/dalvikvm( 3155): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 3155): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 3155): VFY: replacing opcode 0x6e at 0x003d
,D/TimaKeyStoreProvider( 6784): in addTimaSignatureService
,D/dalvikvm( 6745): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 6745): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 6745): VFY: replacing opcode 0x62 at 0x000a
,D/dalvikvm( 6745): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 6745): VFY: unable to resolve instance field 36
,D/dalvikvm( 6745): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 6745): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6745): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6745): VFY: replacing opcode 0x62 at 0x0047
,D/dalvikvm( 6745): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 6745): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/TimaKeyStoreProvider( 6784): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6784): Added TimaKesytore provider
,D/dalvikvm( 6745): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4231da10
,D/dalvikvm( 6745): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4231da10
,D/dalvikvm( 6745): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4231da10, skipping init
,D/dalvikvm( 6745): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4231da10
,D/dalvikvm( 6745): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4231da10
,V/JNIHelp ( 6745): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 6745): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4231da10
,D/dalvikvm( 6745): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x4231da10
,D/dalvikvm( 6745): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4231da10
,D/dalvikvm( 6745): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4231da10
D/dalvikvm( 6784): GC_CONCURRENT freed 3002K, 31% free 9571K/13716K, paused 4ms+1ms, total 54ms
,D/dalvikvm( 6784): WAIT_FOR_CONCURRENT_GC blocked 47ms
,I/dalvikvm( 2734): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 2734): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2734): VFY: replacing opcode 0x6e at 0x003d
,D/KLMS-2.3.201 : ( 6784): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 6784): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453758257948
,I/KLMS-2.3.201 : ( 6784): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/dalvikvm( 2734): GC_CONCURRENT freed 1786K, 21% free 11625K/14620K, paused 9ms+6ms, total 60ms
,I/System.out( 2734): Thread-119(HTTPLog):isShipBuild true
,I/System.out( 2734): Thread-119(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/ProviderInstaller( 6745): Installed default security provider GmsCore_OpenSSL
,D/DelayedSyncController( 5961): Delaying sync.
,I/GAV2    ( 6605): Thread[GAThread,5,main]: connecting to Analytics service
,W/ContextImpl( 6605): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:529 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,D/dalvikvm( 2401): GC_EXPLICIT freed 2493K, 75% free 24635K/97084K, paused 25ms+21ms, total 290ms
,E/ActivityThread( 3155): Failed to find provider info for com.android.contacts.metadata
,I/GAV2    ( 6605): Thread[GAThread,5,main]: connect: bindService returned true for Intent { act=com.google.android.gms.analytics.service.START (has extras) }
,D/GAV2    ( 6605): Thread[main,5,main]: service connected, binder: android.os.BinderProxy@4243a9a0
,D/GAV2    ( 6605): Thread[main,5,main]: bound to service
,I/GAV2    ( 6605): Thread[main,5,main]: Connected to service
,I/GAV2    ( 6605): Thread[GAThread,5,main]: No campaign data found.
,I/GAV2    ( 6605): Thread[GAThread,5,main]: putHit called
,I/GAV2    ( 6605): Thread[GAThread,5,main]: Sending hit to service
,I/SELinux ( 6816): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6816):  
I/dalvikvm( 6745): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 6745): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6745): VFY: replacing opcode 0x6e at 0x000d
,I/LocationTagReadyService( 3461): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3461): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3461): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3461): [Slink platform] The state of Slink geocode service is true
,I/SELinux ( 6816): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6816):  
I/SELinux ( 6816):  
,I/SELinux ( 6816): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6816): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6816): >>>>> Normal User
,E/dalvikvm( 6816): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,I/GallerySearchProvider( 3589): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,E/SELinux ( 6816): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 6816): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6816): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6816): Added TimaKesytore provider
,D/dalvikvm( 2845): GC_EXPLICIT freed 1429K, 22% free 10834K/13832K, paused 10ms+13ms, total 90ms
,I/System.out( 6763): Thread-615(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/libgps  ( 2401): agps_ril_update_network_state: Waiting for IPC connection...
,D/PackageManager( 2401): [MSG] SEND_PENDING_BROADCAST
,E/YouTube MDX( 6745): Bogus value in shared preferences for key MdxServerSelection value , returning default value.,
D/PackageManager( 2401): Sending to user 0: act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000000 Bundle[{android.intent.extra.changed_component_name=com.sec.enterprise.knox.cloudmdm.smdms.core.CoreReceiver, android.intent.extra.DONT_KILL_APP=true, android.intent.extra.UID=10171, android.intent.extra.changed_component_name_list=[Ljava.lang.String;@42fc8838, com.samsung.android.intent.extra.SECRET_APP=false, android.intent.extra.user_handle=0}]
,I/dalvikvm( 6745): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a,
W/dalvikvm( 6745): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 6745): VFY: replacing opcode 0x71 at 0x004e,
,I/System.out( 6763): Thread-615(ApacheHTTPLog):isShipBuild true,
,I/System.out( 6763): Thread-615(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false,
,I/InputReader( 2401): Reconfiguring input devices.  changes=0x00000010,
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO",
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "sms",
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO",
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "smsto",
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 6816): GC_CONCURRENT freed 2998K, 31% free 9578K/13716K, paused 4ms+2ms, total 108ms,
,D/dalvikvm( 6816): WAIT_FOR_CONCURRENT_GC blocked 113ms,
,D/RegisteredServicesCache( 2756): empty dynamic service,
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO",
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "mms",
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system,
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30,
W/ContextImpl( 6745): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :,
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2401):   Scheme: "mmsto"
,D/SO_AGENT( 6816): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE,
,I/SO_AGENT( 6816): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...,
,I/SELinux ( 6845): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 6845):  
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO",
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "sms",
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO",
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "smsto",
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 6845): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 6845):  
I/SELinux ( 6845):  
I/SELinux ( 6845): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 6845): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6845): >>>>> Normal User
,E/dalvikvm( 6845): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ],
,E/SELinux ( 6845): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO",
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2401):   Scheme: "mms"
,I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :,
D/TimaKeyStoreProvider( 6845): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6845): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 6845): Added TimaKesytore provider,
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO",
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "mmsto",
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SA      ( 6041): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ],
,I/SA      ( 6041): [BDLM] already registered in spp,
I/SA      ( 6041): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 6041): [OR] == ACTION_CONNECTIVITY_CHANGE ==,
,D/btif_config_util( 5115): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new,
,D/dalvikvm( 6338): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x422c4d08, skipping init,
,D/dalvikvm( 6845): GC_CONCURRENT freed 2997K, 31% free 9575K/13712K, paused 4ms+2ms, total 31ms,
,D/dalvikvm( 6845): WAIT_FOR_CONCURRENT_GC blocked 27ms,
,I/SecureStorage( 6338): [INFO]: SPID(0x00000000)Processing data,
E/WifiStateMachine( 2401): CAPTIVE_PORTAL_EVENT_AUTHENTICATED,
I/SecureStorage( 1965): [INFO]: SPID(0x00000004)Credentials: uid 1000, gid 1000, pid 6338
,I/SecureStorage( 1965): [INFO]: SPID(0x00000004)Received function mask & code: 00000106,
,V/KVNProvider( 6845): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query,
,V/KVNProvider( 6845): getFindoCursor query string : ,
,V/KVNProvider( 6845): getTagSearchCursor() tagSearchCursor count : 0,
,I/SA      ( 6041): [SLFUCHKMGR] constructor called,
,I/SA      ( 6041): [TPMU]  strSIMState ,	:SIM_STATE_UNKNOWN
,I/SA      ( 6041): [OR] == isSIMCardReady false ==
,I/SA      ( 6041): [SCU] == networkStateCheck == true
I/SA      ( 6041): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6041): isChinaCountryCode : false
,I/SA      ( 6041): [OR] == networkStateCheck true ==
,I/SA      ( 6041): [OR] GetMyCountryZoneTask
,D/dalvikvm( 6745): GC_CONCURRENT freed 1859K, 22% free 10789K/13784K, paused 43ms+9ms, total 108ms
,D/dalvikvm( 6745): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/SA      ( 6041): [OR] onReceive END
I/ActivityManager( 2401): Killing 5872:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2750): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2750): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 6085): Other Intent
,I/SA      ( 6041): [SRS] prepareGetMyCountryZone
,D/dalvikvm( 6745): DexOpt: --- BEGIN 'ads64054040.jar' (bootstrap=0) ---
,I/SELinux ( 6868): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6868):  
,I/SELinux ( 6868): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6868):  
I/SELinux ( 6868):  
,I/SELinux ( 6868): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6868): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6868): >>>>> Normal User
E/dalvikvm( 6868): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 6868): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 6041): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6041): [SSP] query invoked
,I/ActivityManager( 2401): Killing 5876:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/TimaKeyStoreProvider( 6868): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6868): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6868): Added TimaKesytore provider
,I/SurfaceFlinger( 1920): id=21 createSurf (1x1),1 flag=4, Uoast
,I/SA      ( 6041): [TPMU] GetMccFromDB : null
,I/SA      ( 6041): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6041): [TPM] isNoProxy(default) : true
,I/SA      ( 6041): [RC New] Execute method=[GET] start
,D/dalvikvm( 6868): GC_CONCURRENT freed 2999K, 31% free 9565K/13708K, paused 4ms+1ms, total 46ms
,D/dalvikvm( 6868): WAIT_FOR_CONCURRENT_GC blocked 49ms
,I/dalvikvm( 6745): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
,W/dalvikvm( 6745): VFY: unable to resolve virtual method 2614: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 6745): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 6745): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 6745): VFY: unable to resolve virtual method 2615: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 6745): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm( 6745): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 6745): VFY: unable to resolve virtual method 2622: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 6745): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm( 6745): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 6745): VFY: unable to resolve virtual method 2623: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 6745): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm( 6745): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method agv.getLeanbackLaunchIntentForPackage
,W/dalvikvm( 6745): VFY: unable to resolve virtual method 2639: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 6745): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm( 6745): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method agv.getPackageInstaller
,W/dalvikvm( 6745): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6745): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm( 6745): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method agv.getUserBadgedDrawableForDensity
,W/dalvikvm( 6745): VFY: unable to resolve virtual method 2659: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 6745): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 6745): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method agv.getUserBadgedIcon
,W/dalvikvm( 6745): VFY: unable to resolve virtual method 2660: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 6745): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 6745): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method agv.getUserBadgedLabel
,W/dalvikvm( 6745): VFY: unable to resolve virtual method 2661: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
,D/dalvikvm( 6745): VFY: replacing opcode 0x6e at 0x0002
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 6745): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 6745): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 6745): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,D/com.samsung.app( 6868): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 6868): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 6868): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,W/InstanceID/Rpc( 6745): Found 10012
,D/com.samsung.app( 6868): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 6868): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 6868): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/libgps  ( 2401): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2401): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2401): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2401): agps_ril_update_network_availability: Waiting for IPC connection...
,I/SurfaceFlinger( 1920): id=20 Removed Uoast (10/12)
,I/SurfaceFlinger( 1920): id=20 Removed Uoast (-2/12)
,D/daemonapp( 5313): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ApplicationsProvider( 2979): Could not fetch usage stats
W/ApplicationsProvider( 2979): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2979): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2979): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2979): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2979): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2979): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2979): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2979): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2979): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:212)
W/ApplicationsProvider( 2979): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2979): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2979): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/com.samsung.app( 6868): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5313): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 6745): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
D/com.samsung.app( 6868): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5313): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 6868): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 6868): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2401): Killing 5676:com.google.android.music:main/u0a125 (adj 15): empty #43
,I/SELinux ( 6888): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6888):  
,I/SELinux ( 6888): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6888):  
I/SELinux ( 6888):  
,I/SELinux ( 6888): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6888): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6888): >>>>> Normal User
,E/dalvikvm( 6888): >>>>> com.samsung.android.internal.headlines [ userId:0 | appId:10110 ]
,E/SELinux ( 6888): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 6888): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6888): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6888): Added TimaKesytore provider
,D/dalvikvm( 6888): GC_CONCURRENT freed 3000K, 31% free 9575K/13716K, paused 19ms+1ms, total 74ms
,D/dalvikvm( 6888): WAIT_FOR_CONCURRENT_GC blocked 53ms
,D/HeadlinesChannelApplication( 6888): [onCreate]
,D/Headlines( 6888): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/dalvikvm( 6872): DexOpt: load 74ms, verify+opt 116ms, 194052 bytes
,D/HeadlinesChannelUtil( 6888): getCountryCode(): countryCode = PL
,I/SELinux ( 6923): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6923):  
,D/Headlines( 6888): Breath.onCreate
,D/HeadlinesCardManager( 6888): HeadlinesCardManager : constructor
,E/HeadlinesCardManager( 6888): HeadlinesCardManager : ctor = image_cache size is 42MB
,D/SA Version( 6888): CardProvider Library : 13
,I/SecureStorage( 1965): [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage( 1965): [INFO]: SPID(0x00000004)PID: 6338, TID: 6360
I/SELinux ( 6923): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6923):  
I/SELinux ( 6923):  
,I/SELinux ( 6923): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6923): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6923): >>>>> Normal User
,E/dalvikvm( 6923): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 6923): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/MagazineService::CardProviderContentProvider( 6436): insertProvider: provider already exists.: com.samsung.android.app.headlines
,D/MagazineService::CardProviderContentProvider( 6436): insertProvider: provider is updated.: com.samsung.android.app.headlines
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 6888): registerCardProvider: provider already exists.
,I/Headlines( 6888): HeadlinesDataCenter ctor
D/TimaKeyStoreProvider( 6923): in addTimaSignatureService
I/Headlines( 6888): HeadlinesDataCenter. mLocale = en_US
,D/HeadlinesChannelUtil( 6888): getCountryCode(): countryCode = PL
,D/HeadlinesCardManager( 6888): HeadlinesCardManager : constructor welcome :YES
,D/TimaKeyStoreProvider( 6923): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6923): Added TimaKesytore provider
,D/dalvikvm( 6745): DexOpt: --- END 'ads64054040.jar' (success) ---
,D/dalvikvm( 6745): DEX prep '/data/data/com.google.android.youtube/cache/ads64054040.jar': unzip in 0ms, rewrite 975ms
,I/System.out( 6745): Thread-668(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6745): Thread-668(ApacheHTTPLog):isShipBuild true
,I/System.out( 6745): Thread-668(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 6041): Thread-536(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/Headlines( 6888): Breath timer started. interval : 30000
,D/Headlines( 6888): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 6888): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 6888): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 6888): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 6888): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 6888): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 6888): requestUpdateNewsWelcomeCard !!! no welcome card
,I/System.out( 6041): Thread-536(ApacheHTTPLog):isShipBuild true
,I/System.out( 6041): Thread-536(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 6923): GC_CONCURRENT freed 2997K, 31% free 9577K/13716K, paused 2ms+1ms, total 30ms
,D/dalvikvm( 6923): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/SecureStorage( 6338): [INFO]: SPID(0x00000000)Processing data has been completed
,V/WebViewChromium( 6923): Binding Chromium to the background looper Looper (main, tid 1) {42273048}
,I/chromium( 6923): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6923): Initializing chromium process, renderers=0
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,W/chromium( 6923): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,W/PhenotypeConfigurator( 2734): Server returned 404
,D/libEGL  ( 6923): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 6923): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 6923): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 6923): Mali API Version : 401
,I/Mali    ( 6923): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/libgps  ( 2401): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2401): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2401): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/ChimeraCfgMgr( 3155): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3155): Module APK com.google.android.play.games already loaded
,W/WifiP2pStateTracker( 2401): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,W/ActivityThread( 6338): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2401): stay LED for fully charged
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5115): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5115): Disconnected process message: 10
D/ConnectivityService( 2401): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2401):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
D/ConnectivityService( 2401): handleConnectivityChange: setting default proxy info 
D/ConnectivityService( 2401): updateSourceRoutes : no source routing conditions
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,W/GAV2    ( 6923): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GamesSyncServiceMain( 3155): Found unexpected GCM tag when scheduling; aborting,
,W/GamesSyncServiceMain( 3155): Failed to execute periodic sync, missing client context - aborting,
,I/System.out( 6745): Thread-668 calls detatch(),
,I/ActivityManager( 2401): Killing 5997:com.google.android.apps.uploader/u0a117 (adj 15): empty #43,
,I/dalvikvm( 6338): Total arena pages for JIT: 11,
I/dalvikvm( 6338): Total arena pages for JIT: 12
I/dalvikvm( 6338): Total arena pages for JIT: 13
I/dalvikvm( 6338): Total arena pages for JIT: 14
I/dalvikvm( 6338): Total arena pages for JIT: 15
I/dalvikvm( 6338): Total arena pages for JIT: 16
,I/dalvikvm( 6338): Total arena pages for JIT: 17,
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6229): mConnectivityHandler : connected,
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system,
,W/ContextImpl( 6923): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache,
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,W/PCWCLIENTTRACE_AccountUtil( 6229): [hasSamungAccount] - No Samsung Account,
,D/dalvikvm( 6745): GC_CONCURRENT freed 1370K, 19% free 11360K/13868K, paused 8ms+9ms, total 80ms,
,D/SyncManager( 2401): failed sync operation ,
,I/System.out( 6338): Thread-572(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables,
,V/AlarmManager( 2401): waitForAlarm result :4,
,V/AlarmManager( 2401): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/System.out( 6338): Thread-572(ApacheHTTPLog):isShipBuild true,
,I/System.out( 6338): Thread-572(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false,
,D/SyncManager( 2401): not retrying sync operation because the error is a hard error: ,
,I/dalvikvm( 6338): Total arena pages for JIT: 18,
,I/NSApplication( 6923): Starting up...,
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6229): failed to loading secure library,
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6229): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6229): GetString : secure API is not supported!!,
I/PCWCLIENTTRACE_PushUtil( 6229): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6229): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6229): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6229): [ensureRegistration] - No Samsung account,
,I/System.out( 6338): Thread-572 calls detatch(),
,I/ImageResourceManager( 5760): ImageResourceManager: uninitalized,
,I/iu.Environment( 5760): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*,
I/ActivityManager( 2401): Killing 5369:com.google.android.talk/u0a109 (adj 15): empty #43
,D/QuickConnect[1.1][2] ( 5089): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE,
I/QuickConnect[1.1][2] ( 5089): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5089): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4227b4d8,
,D/dalvikvm( 5760): GC_FOR_ALLOC freed 1124K, 28% free 9933K/13712K, paused 32ms, total 35ms,
,I/dalvikvm-heap( 5760): Grow heap (frag case) to 12.839MB for 2129936-byte allocation,
,I/SELinux ( 6982): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 6982):  
,I/SELinux ( 6982): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 6982):  
I/SELinux ( 6982):  
I/SELinux ( 6982): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6982): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6982): >>>>> Normal User
,E/dalvikvm( 6982): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 6982): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,D/TimaKeyStoreProvider( 6982): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 6982): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6982): Added TimaKesytore provider
,D/dalvikvm( 5760): GC_FOR_ALLOC freed <1K, 24% free 12013K/15796K, paused 111ms, total 111ms
,D/dalvikvm( 5760): GC_CONCURRENT freed 25K, 25% free 11995K/15796K, paused 4ms+12ms, total 46ms
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/iu.UploadsManager( 5760): num queued entries: 0
,I/iu.UploadsManager( 5760): num updated entries: 0
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 6982): GC_CONCURRENT freed 3000K, 31% free 9580K/13716K, paused 2ms+2ms, total 33ms
,D/dalvikvm( 6982): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/iu.SyncManager( 5760): NEXT; no task
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SA      ( 6041): [RC New] [v2liruge] api execute + 2366
,I/SA      ( 6041): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6745): Thread-651 calls detatch(),
I/System.out( 6763): AsyncTask #1 calls detatch()
,I/System.out( 6041): AsyncTask #1 calls detatch(),
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId,
,I/SA      ( 6041): [TPMU] getNetworkMcc : ,
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId,
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId,
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 380, Delta = 10,
W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/System.err( 6763): com.sec.android.fota.osp.http.RestClientException,
W/System.err( 6763): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
,W/System.err( 6763): ,	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 6763): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 6763): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 6763): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 6763): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 6763): ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 6763): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 6763): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 6763): Caused by: java.lang.NullPointerException
W/System.err( 6763): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 6763): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 6763): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 6763): ,	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
W/System.err( 6763): 	... 8 more
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0x0 a=-1},
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/ActivityManager( 2401): Killing 5897:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/SA      ( 6041): [SCU] saveMccToPreferece Start
,I/SA      ( 6041): [SCU] RegionMCC : 260
,I/SA      ( 6041): [SSP] query invoked
,I/SA      ( 6041): [TPMU] GetMccFromDB : null
,I/SA      ( 6041): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6041): [SCU] saveMccToPreferece End
I/SA      ( 6041): [RC New] executeRequest [v2liruge] end. 2534
I/SA      ( 6041): [RC New] Execute end
I/SA      ( 6041): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6041): [OR] GetMyCountryZoneTask Success
,I/SELinux ( 7000): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7000):  
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId
I/SELinux ( 7000): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7000):  
I/SELinux ( 7000):  
I/SELinux ( 7000): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7000): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7000): >>>>> Normal User
E/dalvikvm( 7000): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7000): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 12% free 9508K/10688K, paused 3ms+2ms, total 38ms
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId
,D/RCPManagerService( 2401): exchangeData() failure , invalid userId
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9508K/10688K, paused 2ms+3ms, total 26ms
,W/ActivityManager( 2401): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/TimaKeyStoreProvider( 7000): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7000): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7000): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9508K/10688K, paused 3ms+3ms, total 26ms
,I/ActivityManager( 2401): Killing 6121:com.sec.knox.bridge/1000 (adj 15): empty #43
,D/NtpTrustedTime( 2401): getCachedNtpTime() cache hit
,D/dalvikvm( 7000): GC_CONCURRENT freed 3004K, 31% free 9570K/13716K, paused 2ms+2ms, total 29ms
,D/dalvikvm( 7000): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/SELinux ( 7015): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7015):  
,I/ActivityManager( 2401): Killing 5555:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,D/dalvikvm( 3155): GC_FOR_ALLOC freed 1282K, 22% free 12367K/15784K, paused 54ms, total 54ms
,D/BadgeProvider( 7000): onCreate
,D/BadgeProvider( 7000): DatabaseHelper
I/SELinux ( 7015): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7015):  
I/SELinux ( 7015):  
,I/SELinux ( 7015): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7015): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7015): >>>>> Normal User
,E/dalvikvm( 7015): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7015): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/BadgeProvider( 7000): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 7015): in addTimaSignatureService
,D/Launcher.Model( 2781): reloadBadges entered.
D/BadgeProvider( 7000): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7000): sendNotify, [notify] : null
D/BadgeProvider( 7000): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7000): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7000): update, [UpdateCount] : 1
,D/TimaKeyStoreProvider( 7015): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7015): Added TimaKesytore provider
,I/GoogleURLConnFactory( 3155): Using platform SSLCertificateSocketFactory
,D/dalvikvm( 7015): GC_CONCURRENT freed 2997K, 31% free 9575K/13712K, paused 2ms+1ms, total 23ms
,D/dalvikvm( 7015): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/SELinux ( 7030): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7030):  
,I/ActivityManager( 2401): Killing 6168:com.android.defcontainer/u0a6 (adj 15): empty #43
,I/SELinux ( 7030): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7030):  
I/SELinux ( 7030):  
,I/SELinux ( 7030): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7030): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7030): >>>>> Normal User
,E/dalvikvm( 7030): >>>>> com.google.android.talk [ userId:0 | appId:10109 ]
,E/SELinux ( 7030): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7030): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7030): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7030): Added TimaKesytore provider
,D/dalvikvm( 7030): GC_CONCURRENT freed 2987K, 31% free 9589K/13716K, paused 3ms+4ms, total 36ms
,D/dalvikvm( 7030): WAIT_FOR_CONCURRENT_GC blocked 25ms
,V/GLSActivity( 2845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 2401): GC_EXPLICIT freed 3135K, 75% free 24784K/97084K, paused 9ms+23ms, total 227ms
,I/Gmail   ( 4987): getStartSyncRequest: handledServerOpId: 15626, upperFetchedConvoId: 1517003032157487104, lowerFetchedConvoId: 0, ackedClientOp: 0
,I/SurfaceFlinger( 1920): id=21 Removed Uoast (10/11)
,I/SurfaceFlinger( 1920): id=21 Removed Uoast (-2/11)
D/PowerManagerService( 2401): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2401) eventTime = 158272
D/PowerManagerService( 2401): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2401 (0x0)
D/PowerManagerService( 2401): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2401, ws=WorkSource{1000}) (elapsedTime=7011)
,I/System.out( 3155): Thread-215(HTTPLog):isShipBuild true
,I/System.out( 3155): Thread-215(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/dalvikvm( 7030): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N
W/dalvikvm( 7030): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 7030): VFY: replacing opcode 0x6e at 0x0008
,V/GLSActivity( 2845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/dalvikvm( 7030): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7030): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7030): VFY: replacing opcode 0x22 at 0x0000
,E/dalvikvm( 7030): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a
W/dalvikvm( 7030): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
,D/dalvikvm( 7030): VFY: replacing opcode 0x22 at 0x0037
,I/System.out( 6745): Thread-658 calls detatch()
,I/System.out( 6745): Thread-657 calls detatch()
,W/dalvikvm( 7030): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7030): Link of class 'Ldqp;' failed
,W/dalvikvm( 7030): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7030): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7030): Link of class 'Ldqp;' failed
I/dalvikvm( 7030): Could not find method dqp.q, referenced from method g.a
W/dalvikvm( 7030): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
,D/dalvikvm( 7030): VFY: replacing opcode 0x6e at 0x0000
,E/dalvikvm( 7030): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7030): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7030): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm( 7030): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7030): Link of class 'Ldqp;' failed
,W/dalvikvm( 7030): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7030): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7030): Link of class 'Ldqp;' failed
I/dalvikvm( 7030): Could not find method dqp.getState, referenced from method g.a
W/dalvikvm( 7030): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
,D/dalvikvm( 7030): VFY: replacing opcode 0x6e at 0x0008
E/dalvikvm( 7030): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
W/dalvikvm( 7030): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
,D/dalvikvm( 7030): VFY: replacing opcode 0x1c at 0x0026
,W/dalvikvm( 7030): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7030): Link of class 'Ldqp;' failed
,I/ActivityManager( 2401): Killing 5968:com.google.android.partnersetup/u0a14 (adj 15): empty #43
W/dalvikvm( 7030): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7030): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
W/dalvikvm( 7030): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7030): Link of class 'Ldqp;' failed
I/dalvikvm( 7030): Could not find method dqp.d, referenced from method g.a
W/dalvikvm( 7030): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
D/dalvikvm( 7030): VFY: replacing opcode 0x6e at 0x0003
W/dalvikvm( 7030): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7030): Link of class 'Lax;' failed
E/dalvikvm( 7030): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 7030): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
D/dalvikvm( 7030): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 7030): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 7030): Link of class 'Laz;' failed
E/dalvikvm( 7030): Could not find class 'az', referenced from method g.a
W/dalvikvm( 7030): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
D/dalvikvm( 7030): VFY: replacing opcode 0x22 at 0x002c
I/dalvikvm( 7030): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
W/dalvikvm( 7030): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
D/dalvikvm( 7030): VFY: replacing opcode 0x6e at 0x0008
,I/dalvikvm( 7030): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a
,W/dalvikvm( 7030): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
,D/dalvikvm( 7030): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 7030): Could not find method android.view.View.getTransitionName, referenced from method g.a
W/dalvikvm( 7030): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7030): VFY: replacing opcode 0x6e at 0x0006
,I/dalvikvm( 7030): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
W/dalvikvm( 7030): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
,D/dalvikvm( 7030): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 7030): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 7030): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
D/dalvikvm( 7030): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7030): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
W/dalvikvm( 7030): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 7030): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7030): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
W/dalvikvm( 7030): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 7030): VFY: replacing opcode 0x72 at 0x0000
W/dalvikvm( 7030): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;),
E/dalvikvm( 7030): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
W/dalvikvm( 7030): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
,D/dalvikvm( 7030): VFY: replacing opcode 0x23 at 0x0005,
,I/dalvikvm( 7030): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b,
W/dalvikvm( 7030): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7030): VFY: replacing opcode 0x6e at 0x0009,
,W/dalvikvm( 7030): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764),
W/dalvikvm( 7030): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
E/dalvikvm( 7030): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 7030): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;,
,D/dalvikvm( 7030): VFY: replacing opcode 0x1c at 0x0002,
E/dalvikvm( 7030): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 7030): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
,D/dalvikvm( 7030): VFY: replacing opcode 0x1f at 0x000c,
,D/dalvikvm( 7030): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS,
W/dalvikvm( 7030): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7030): VFY: replacing opcode 0x62 at 0x0006,
,D/dalvikvm( 7030): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a,
,D/dalvikvm( 7030): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a,
,D/dalvikvm( 7030): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7030): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
,D/dalvikvm( 7030): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a
W/dalvikvm( 7030): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7030): Link of class 'Lax;' failed
,D/dalvikvm( 7030): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
W/dalvikvm( 7030): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 7030): Link of class 'Laz;' failed
,D/dalvikvm( 7030): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
,D/dalvikvm( 7030): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a
,I/System.out( 4987): Thread-388(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6745): Thread-659 calls detatch()
,D/dalvikvm( 7030): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l
,I/System.out( 4987): Thread-388(ApacheHTTPLog):isShipBuild true
,I/System.out( 4987): Thread-388(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 7030): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x42265008,
,D/dalvikvm( 7030): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x42265008,
,I/dalvikvm( 7030): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b,
W/dalvikvm( 7030): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
,D/dalvikvm( 7030): VFY: replacing opcode 0x6e at 0x0076,
,I/Babel_SMS( 7030): MmsConfig: mnc/mcc: 0/0,
I/Babel_SMS( 7030): MmsConfig.loadMmsSettings
I/Babel_SMS( 7030): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,I/Babel_SMS( 7030): MmsConfig.loadFromDatabase,
,E/Babel_SMS( 7030): canonicalizeMccMnc: invalid mccmnc ,
I/Babel_SMS( 7030): MmsConfig.loadFromResources
,E/Babel_SMS( 7030): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7030): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml,
,W/dalvikvm( 7030): Unable to resolve superclass of Lfzc; (613),
W/dalvikvm( 7030): Link of class 'Lfzc;' failed
E/dalvikvm( 7030): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
W/dalvikvm( 7030): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
D/dalvikvm( 7030): VFY: replacing opcode 0x22 at 0x0033
W/dalvikvm( 7030): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7030): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7030): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;),
W/dalvikvm( 7030): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
I/dalvikvm( 7030): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e,
W/dalvikvm( 7030): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
,D/dalvikvm( 7030): VFY: replacing opcode 0x74 at 0x006d
,I/dalvikvm( 7030): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
W/dalvikvm( 7030): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
,D/dalvikvm( 7030): VFY: replacing opcode 0x6e at 0x0033
I/dalvikvm( 7030): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
W/dalvikvm( 7030): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
,D/dalvikvm( 7030): VFY: replacing opcode 0x6e at 0x0030
W/dalvikvm( 7030): Unable to resolve superclass of Lfzc; (613)
,W/dalvikvm( 7030): Link of class 'Lfzc;' failed
,D/dalvikvm( 7030): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
,D/dalvikvm( 7030): GC_CONCURRENT freed 1763K, 22% free 10897K/13796K, paused 3ms+2ms, total 36ms
D/dalvikvm( 7030): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 7030): WAIT_FOR_CONCURRENT_GC blocked 23ms
E/SensorService( 2401): Permission Denial : SEC Private Sensor 
,E/SensorService( 2401): Permission Denial : SEC Private Sensor 
D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1924): DEBUG:duration time(    1 msec):(HAL_getCameraInfo)
,I/jxcore-log( 6450): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 6450): 
,W/Settings( 7030): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7030): startup - clean
,I/dalvikvm( 7030): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
W/dalvikvm( 7030): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7030): VFY: replacing opcode 0x6e at 0x000d
,I/Babel   ( 7030): deleted: false for 0
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,W/dalvikvm( 7030): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,I/dalvikvm( 7030): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 7030): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
D/dalvikvm( 7030): VFY: replacing opcode 0x6e at 0x004e
,W/dalvikvm( 7030): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7030): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7030): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
W/dalvikvm( 7030): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
,D/dalvikvm( 7030): VFY: replacing opcode 0x22 at 0x0071
,W/dalvikvm( 7030): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7030): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7030): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7030): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7030): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 7030): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
,D/dalvikvm( 7030): VFY: replacing opcode 0x1f at 0x0021
,W/dalvikvm( 7030): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,D/dalvikvm( 7030): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
,I/dalvikvm( 7030): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
W/dalvikvm( 7030): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
,D/dalvikvm( 7030): VFY: replacing opcode 0x6e at 0x0074
,D/WaitQueueForNetworkActivate( 6578): notifyNetworkActivated
,I/vclib   ( 7030): onServiceConnected
,W/Babel   ( 7030): Attempted to change video mute state without an active call.
,W/ContextImpl( 6578): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ActivityManager( 2401): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/dalvikvm( 7030): GC_CONCURRENT freed 929K, 15% free 12014K/14080K, paused 3ms+2ms, total 35ms
,D/dalvikvm( 7030): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/dalvikvm( 7030): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 7030): GC_FOR_ALLOC freed 705K, 17% free 12575K/15120K, paused 25ms, total 26ms
,D/dalvikvm( 7030): GC_FOR_ALLOC freed 1774K, 23% free 12958K/16712K, paused 25ms, total 25ms
,D/hcjo    ( 6578): AutoUpdateManager:IDLE:execute
,I/System.out( 7030): Thread-656(HTTPLog):isShipBuild true
,I/System.out( 7030): Thread-656(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/dalvikvm( 6578): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
W/dalvikvm( 6578): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 6578): VFY: replacing opcode 0x6e at 0x0024
,I/CheckinService( 3155): Checkin interval check for package: unspecified last checkin: 1453041324326 min interval config: 0 actual interval: 716939731
,D/InitializeManagerStateMachine( 6578): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6578): exit::IDLE
,D/InitializeManagerStateMachine( 6578): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6578): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 6578): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6578): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6578): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6578): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6578): entry::SUCCESS
,D/hcjo    ( 6578): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6578): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/CheckinService( 3155): Checking schedule, now: 1453758264087 next: 1453599667141
,I/CheckinService( 3155): active receiver: enabled
,I/CheckinService( 3155): Preparing to send checkin request
,I/EventLogService( 3155): Accumulating logs since 1453757203351
,I/Volley  ( 6578): RestApi Request Add : 2307
,I/iu.Environment( 3155): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/Babel   ( 7030): connection state changed from UNKNOWN to CONNECTED
,I/iu.UploadsManager( 3155): num queued entries: 0
,I/iu.UploadsManager( 3155): num updated entries: 0
,E/SPPClientService( 5512): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5512): [SystemStateMoniter] Current Time : 159637
,I/iu.SyncManager( 3155): NEXT; no task
,E/SPPClientService( 5512): [SystemStateMoniter] No Connect : false
,I/SELinux ( 7077): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7077):  
,I/SELinux ( 7077): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7077):  
I/SELinux ( 7077):  
,I/SELinux ( 7077): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7077): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7077): >>>>> Normal User
,E/dalvikvm( 7077): >>>>> com.android.calendar [ userId:0 | appId:10144 ]
,E/SELinux ( 7077): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7077): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7077): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7077): Added TimaKesytore provider,
,D/dalvikvm( 7077): GC_CONCURRENT freed 2991K, 31% free 9584K/13712K, paused 3ms+1ms, total 25ms,
,D/dalvikvm( 7077): WAIT_FOR_CONCURRENT_GC blocked 19ms,
,V/AlarmManager( 2401): waitForAlarm result :4,
,V/AlarmManager( 2401): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/GCM     ( 2845): GCM config loaded,
,I/ActivityManager( 2401): Killing 6204:com.samsung.groupcast/u0a15 (adj 15): empty #43
,D/BootCompletedReceiver( 2401): onReceive
,I/KLMS-2.3.201 : ( 6784): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/CheckinRequestBuilder( 3155): Checkin reason type: 12 attempt count: 1
,I/KLMS-2.3.201 : ( 6784): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1453758264866
,I/KLMS-2.3.201 : ( 6784): StateImplV2() : dateTimeChanged() : Mon Jan 25 22:44:24 CET 2016
,E/ActivityThread( 3155): Failed to find provider info for com.google.android.wearable.settings
,D/SO_AGENT( 6816): [ServerTimeReceiver.java(Line:44/Method:onReceive)] Receive broadcast meassage:android.intent.action.TIME_SET
,I/SO_AGENT( 6816): [ServerTimeReceiver.java(Line:47/Method:onReceive)] No action is available before server time settings
,I/SA      ( 6041): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,I/Gmail   ( 4987): StartSyncInfoProto: Personal inbox enabled: true
,I/Gmail   ( 4987): StartSyncInfoProto: Personal inbox android config: com.google.common.io.protocol.ProtoBuf@42529bc8
,D/dalvikvm( 6578): GC_CONCURRENT freed 2550K, 27% free 10089K/13764K, paused 13ms+13ms, total 118ms
,D/AmoledAdjustTimer( 2401): prevTemp = 303, currTemp = 304, prevStep = 4, currStep = 4
,D/dalvikvm( 4987): GC_CONCURRENT freed 2150K, 25% free 10389K/13712K, paused 5ms+28ms, total 93ms
,D/dalvikvm( 2845): GC_CONCURRENT freed 1826K, 22% free 10950K/13984K, paused 3ms+3ms, total 40ms
,I/VacuumService( 2734): Vacuum at: now=1453758265135 tag=VacuumService
D/ConnectivityService( 2401): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
,D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,D/Mms/MessagingNotification( 5610): [start]    nonBlockingUpdateMessageIndicator()
,D/Mms/MessagingNotification( 5610): sDisableVibrateForCamera = false
,D/Mms/MessagingNotification( 5610): isBlockingModeEnable() = false
,D/Mms/TelephonyPermission( 5610): isDefault true
,D/TP/MmsSmsProvider( 2750): match 8:Elapsed time : 19.537 ms,
,I/SELinux ( 7108): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7108):  
I/jxcore-log( 6450): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 6450): 
,I/jxcore-log( 6450): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 6450): 
I/SELinux ( 7108): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7108):  
I/SELinux ( 7108):  
I/SELinux ( 7108): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7108): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7108): >>>>> Normal User
E/dalvikvm( 7108): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10064 ]
,E/SELinux ( 7108): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TP/MmsSmsProvider( 2750): match 200:Elapsed time : 22.772 ms
,D/TimaKeyStoreProvider( 7108): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7108): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7108): Added TimaKesytore provider
,D/dalvikvm( 7108): GC_CONCURRENT freed 3001K, 31% free 9568K/13712K, paused 2ms+1ms, total 35ms
,D/dalvikvm( 7108): WAIT_FOR_CONCURRENT_GC blocked 32ms
,I/jxcore-log( 6450): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 6450): 
,I/jxcore-log( 6450): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 6450): 
,I/jxcore-log( 6450): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 6450): 
,I/jxcore-log( 6450): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 6450): 
,D/BadgeProvider( 7000): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/com.samsung.app( 6868): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidintentactionTIME_SET
,D/com.samsung.app( 6868): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,I/ Time Manager ( 7108): Time Difference not stored. TIME_DIFFERENCE
,I/SELinux ( 7125): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7125):  
,I/SELinux ( 7125): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7125):  
I/SELinux ( 7125):  
I/SELinux ( 7125): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7125): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7125): >>>>> Normal User
E/dalvikvm( 7125): >>>>> com.google.android.syncadapters.calendar [ userId:0 | appId:10107 ]
,E/SELinux ( 7125): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/SELinux ( 7130): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7130):  
,I/ActivityManager( 2401): Killing 6216:com.android.musicfx/u0a24 (adj 15): empty #43
,D/BadgeProvider( 7000): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 7000): sendNotify, [notify] : null
D/BadgeProvider( 7000): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 7000): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7000): update, [UpdateCount] : 1
,D/Mms/MessagingNotification( 5610): setBadgeCount(), count=0
,I/SELinux ( 7130): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7130):  
I/SELinux ( 7130):  
,I/SELinux ( 7130): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/TimaKeyStoreProvider( 7125): in addTimaSignatureService
,E/SELinux ( 7130): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7130): >>>>> Normal User
E/dalvikvm( 7130): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10088 ]
,D/MessagingNotification( 5610): remove alarm
,E/SELinux ( 7130): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7125): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7125): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 7130): in addTimaSignatureService
,D/Mms/MessagingNotification( 5610): updateAllHistoryAsRead()
,D/TimaKeyStoreProvider( 7130): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7130): Added TimaKesytore provider
,D/Launcher.Model( 2781): reloadBadges entered.
,D/dalvikvm( 4987): GC_CONCURRENT freed 2038K, 25% free 10311K/13712K, paused 13ms+9ms, total 61ms
,D/dalvikvm( 6578): GC_CONCURRENT freed 2046K, 27% free 10051K/13764K, paused 9ms+2ms, total 55ms
,D/dalvikvm( 2401): GC_EXPLICIT freed 2217K, 75% free 24560K/97084K, paused 13ms+19ms, total 219ms
,D/Mms/MessagingNotification( 5610): [end]    nonBlockingUpdateMessageIndicator()
,D/dalvikvm( 7125): GC_CONCURRENT freed 3005K, 31% free 9564K/13712K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 7125): WAIT_FOR_CONCURRENT_GC blocked 22ms
,W/AbstractGoogleClient( 7125): Application name is not set. Call Builder#setApplicationName.
,D/dalvikvm( 7130): GC_CONCURRENT freed 2985K, 31% free 9580K/13708K, paused 5ms+1ms, total 40ms
,D/dalvikvm( 7130): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/CaptivePortalTracker( 2401): DelayedCaptiveCheckState{ when=-67ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 2401): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2401): Checking http://216.58.209.46/generate_204
W/ActivityThread( 2401): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/GAV2    ( 6923): Thread[GAThread,5,main]: No campaign data found.
,I/SELinux ( 7158): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7158):  
,I/System.out( 2401): Thread-160(HTTPLog):isShipBuild true
,I/System.out( 2401): Thread-160(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/SELinux ( 7158): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7158):  
I/SELinux ( 7158):  
,I/SELinux ( 7158): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7158): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7158): >>>>> Normal User
E/dalvikvm( 7158): >>>>> com.android.providers.calendar [ userId:0 | appId:10045 ]
,E/SELinux ( 7158): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7158): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7158): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7158): Added TimaKesytore provider
D/CaptivePortalTracker( 2401): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker( 2401): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 2401): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2401): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2401): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/dalvikvm( 7158): GC_CONCURRENT freed 3006K, 31% free 9571K/13716K, paused 7ms+1ms, total 24ms
,D/dalvikvm( 7158): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/SELinux ( 7174): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7174):  
I/ActivityManager( 2401): Killing 6244:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
I/SELinux ( 7174): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7174):  
I/SELinux ( 7174):  
I/SELinux ( 7174): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7174): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7174): >>>>> Normal User
E/dalvikvm( 7174): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
,E/SELinux ( 7174): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7174): in addTimaSignatureService
D/dalvikvm( 6578): GC_CONCURRENT freed 1884K, 26% free 10214K/13764K, paused 3ms+3ms, total 81ms
,D/dalvikvm( 6578): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/TimaKeyStoreProvider( 7174): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7174): Added TimaKesytore provider
,D/dalvikvm( 3155): GC_CONCURRENT freed 1563K, 19% free 12850K/15784K, paused 6ms+25ms, total 138ms
,D/InitializeManagerStateMachine( 6578): exit::SUCCESS
,D/InitializeManagerStateMachine( 6578): entry::IDLE
,D/dalvikvm( 7174): GC_CONCURRENT freed 3010K, 31% free 9570K/13716K, paused 3ms+1ms, total 28ms
,D/dalvikvm( 7174): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/Gmail   ( 4987): checkLabelsSets changed the label sets to: included([^r, ^^out]), partial([^f]), all([^sq_ig_i_social, userlabel:1123230114, userlabel:90242014, userlabel:90242001, ^smartlabel_social, ^io_im, userlabel:2914456, ^smartlabel_promo, userlabel:-1497466235, userlabel:90241997, ^smartlabel_notification, userlabel:382548592, userlabel:1880465491, userlabel:94101, userlabel:93982, ^smartlabel_personal, userlabel:1680828287, userlabel:90242029, userlabel:-1492276990, userlabel:-1492276991, userlabel:-1492276992, userlabel:2914615, userlabel:826208851, userlabel:94076, ^imi, userlabel:-244132349, ^iim, userlabel:-812318908, ^all, ^smartlabel_group, ^sq_ig_i_personal, ^imn, userlabel:2896756, userlabel:614875005, userlabel:-1492276993, userlabel:-1492276994, ^i, ^g, ^f, ^sq_ig_i_promo, userlabel:-1508083783, ^k, userlabel:3011, userlabel:-1711782184, userlabel:93692, ^b, userlabel:3026, userlabel:3025, ^t, ^u, userlabel:843908213, ^r, userlabel:-1492383895, ^s])
,I/System.out( 6578): Thread-604(HTTPLog):isShipBuild true
,I/System.out( 6578): Thread-604(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,V/GLSActivity( 2845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/elm:14132( 7174): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:14132( 7174): ELMEngine.ELMEngine( context ).
,D/elm:14132( 7174): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 7174): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/elm:14132( 7174): ElmAgentService : onCreate()
,D/elm:14132( 7174): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,D/elm:14132( 7174): ELMAgentService.listeningToTimeDateChanges( context, intent ).
D/elm:14132( 7174): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,D/elm:14132( 7174): ModuleBase.resetCalllogAPIAlarm()
,I/knox    ( 5032): MainReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
W/ContextImpl( 5032): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,D/knox    ( 5032): MainReceiver.listeningToTimeDateChanges( context, intent ).
,I/knox    ( 5032): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
D/knox    ( 5032): KNOXAgentService : onCreate()
D/knox    ( 5032): KNOXAgentService : set alarms for deniallog and usage data upload
D/elm:14132( 7174): ModuleBase.ModifySetAlarm()
D/elm:14132( 7174): MDMBridge.getInstance()
,D/elm:14132( 7174): MDMBridge.getAllLicenseInfoFromSDK()
,D/knox    ( 5032): KNOXAgentService. startJobThread() start
D/knox    ( 5032): KNOXAgentService. JobThread()
D/knox    ( 5032): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 5032): KNOXAgentService. startJobThread() wait
,D/elm:14132( 7174): ElmAgentService : onDestroy().
,I/SELinux ( 7197): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7197):  
D/knox    ( 5032): KNOXAgentService : onDestroy().
,D/knox    ( 5032): ModuleBase.cancelAllAlarmManageModule()
I/ActivityManager( 2401): Killing 6280:com.sec.android.service.health/u0a16 (adj 15): empty #43
,I/SELinux ( 7197): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7197):  
I/SELinux ( 7197):  
,I/SELinux ( 7197): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7197): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7197): >>>>> Normal User
,E/dalvikvm( 7197): >>>>> com.sec.android.widgetapp.SPlannerAppWidget [ userId:0 | appId:10145 ]
,E/SELinux ( 7197): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7197): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7197): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7197): Added TimaKesytore provider
,I/PhenotypeConfigurator( 2734): Scheduling Phenotype for one-off execution 7309 seconds from now (1453758267297)
,E/SPPClientService( 5512): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,D/dalvikvm( 7197): GC_CONCURRENT freed 2997K, 31% free 9572K/13712K, paused 4ms+1ms, total 28ms
,D/dalvikvm( 7197): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/GetConfigurationSnapshotOperation( 2734): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/SELinux ( 7216): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7216):  
,V/AlarmManager( 2401):  next == MAX_VALUE
,I/SELinux ( 7216): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7216):  
I/SELinux ( 7216):  
,I/SELinux ( 7216): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7216): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7216): >>>>> Normal User
,E/dalvikvm( 7216): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10168 ]
,E/SELinux ( 7216): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7216): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7216): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7216): Added TimaKesytore provider
,I/PhenotypeFlagCommitter( 2734): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 2734): Using platform SSLCertificateSocketFactory
,D/hcjo    ( 6578): AutoUpdateTriggerManager:REQUEST2:setInterval:345600000
,E/SPPClientService( 5512): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,D/hcjo    ( 6578): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
D/hcjo    ( 6578): AutoUpdateManager:UPD_CHECK_TIMING:onUpdateTime
,D/hcjo    ( 6578): SelfUpdateManager:IDLE:execute
,D/dalvikvm( 7216): GC_CONCURRENT freed 3000K, 31% free 9571K/13712K, paused 2ms+1ms, total 30ms
,D/dalvikvm( 7216): WAIT_FOR_CONCURRENT_GC blocked 26ms
,E/SPPClientService( 5512): [a] [ConnectionManager] Connection is already disconnected.
,D/hcjo    ( 6578): SelfUpdateManager:CONDITION_CHECK:onUpdateCondition
I/ActivityManager( 2401): Killing 6368:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty #43
,V/AlarmManager( 2401): waitForAlarm result :4
,V/AlarmManager( 2401): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/daemonapp( 5313): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5313): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5313): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5313): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/Volley  ( 6578): RestApi Request Add : 2346
,D/daemonapp( 5313): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionTIME_SET, run:true
,D/comsamsunglog( 5313): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5313): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
,D/comsamsunglog( 5313): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 5313): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5313): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5313): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/jxcore-log( 6450): Test app app.js loaded
I/jxcore-log( 6450): 
,D/daemonapp( 5313): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 5313): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5313): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5313): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
I/dalvikvm( 6450): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 6450): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 6450): VFY: replacing opcode 0x6e at 0x0002
,D/daemonapp( 5313): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 6450): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 6450): BLE advertisement is supported
I/jxcore-log( 6450): 
,I/chromium( 6450): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/LocationManagerService( 2401): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/comdaemonstockapp( 5313): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 5313): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
,I/CheckinService( 3155): Checkin interval check for package: unspecified last checkin: 1453041324326 min interval config: 0 actual interval: 716943494
,I/System.out( 4987): SyncAdapterThread-1 calls detatch()
,D/Finsky  ( 3876): [220] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/dalvikvm( 4987): GC_EXPLICIT freed 1927K, 26% free 10189K/13712K, paused 6ms+5ms, total 83ms
,D/Finsky  ( 3876): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/Icing.InternalIcingCorporaProvider( 5949): Updating corpora: A: com.sec.enterprise.knox.cloudmdm.smdms, C: MAYBE
,D/FileShare-Server( 6108): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,I/SELinux ( 7237): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7237):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 42K, 12% free 9508K/10688K, paused 3ms+3ms, total 31ms
,I/SELinux ( 7237): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7237):  
I/SELinux ( 7237):  
,I/SELinux ( 7237): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7237): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7237): >>>>> Normal User
,E/dalvikvm( 7237): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
,E/SELinux ( 7237): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/ActivityManager( 2401): Waited long enough for: ServiceRecord{44f50150 u0 pl.k2.droidoaudioteka/.services.DownloadService}
,I/ActivityManager( 2401): Waited long enough for: ServiceRecord{44a41e10 u0 pl.k2.droidoaudioteka/.services.PlayerService}
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9508K/10688K, paused 2ms+3ms, total 27ms
,D/TimaKeyStoreProvider( 7237): in addTimaSignatureService
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9508K/10688K, paused 3ms+4ms, total 27ms
,D/TimaKeyStoreProvider( 7237): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7237): Added TimaKesytore provider
,I/qtaguid ( 6578): Failed write_ctrl(u -1) res=-1 errno=9
I/qtaguid ( 6578): Untagging socket -1 failed errno=-9
,W/NetworkManagementSocketTagger( 6578): untagSocket(-1) failed with errno -9
,D/hcjo    ( 6578): SelfUpdateManager:REQUEST_UPD_CHECK:onUpdateCheckSuccessAndNoNeedUpdate
,D/hcjo    ( 6578): AutoUpdateManager:CHECK_SELF_UPD:onSelfUpdateResult:T
,D/hcjo    ( 6578): SellerAppAutoUpdate:clearFlag
,D/SellerAppAutoUpdateManagerStateMachine( 6578): execute::IDLE:EXECUTE
,D/SellerAppAutoUpdateManagerStateMachine( 6578): exit::IDLE
,D/SellerAppAutoUpdateManagerStateMachine( 6578): entry::TOKENCHECK
,D/SellerAppAutoUpdateManagerStateMachine( 6578): execute::TOKENCHECK:TOKEN_RECEIVED
,D/SellerAppAutoUpdateManagerStateMachine( 6578): exit::TOKENCHECK
D/SellerAppAutoUpdateManagerStateMachine( 6578): entry::FAILED
,D/hcjo    ( 6578): AutoUpdateManager:SELLER_UPD:onSellerAutoUpdateFailed
,D/SellerAppAutoUpdateManagerStateMachine( 6578): exit::FAILED
,D/SellerAppAutoUpdateManagerStateMachine( 6578): entry::IDLE
,I/ActivityManager( 2401): Killing 4835:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #43
D/dalvikvm( 5949): GC_CONCURRENT freed 2222K, 25% free 10414K/13772K, paused 8ms+5ms, total 117ms
D/dalvikvm( 5949): WAIT_FOR_CONCURRENT_GC blocked 74ms
,I/Gmail   ( 4987): MainSyncRequestProto: lowestBkwdConvoId: 0, highestHandledServerOp: 15626, normalSync: true
,I/Icing.InternalIcingCorporaProvider( 5949): UpdateCorporaTask done [took 238 ms] updated apps [took 237 ms] 
W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 7237): GC_CONCURRENT freed 3003K, 31% free 9571K/13716K, paused 3ms+2ms, total 34ms
,D/dalvikvm( 7237): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/Gmail   ( 4987): lowestBackward conversation id 0
,I/SELinux ( 7249): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7249):  
,D/BezelQuickConnect( 5101): BezelBroadcastReceiver - onReceive : android.intent.action.PACKAGE_CHANGED
,D/BezelQuickConnect( 5101): BezelBroadcastReceiver - packageName : com.sec.enterprise.knox.cloudmdm.smdms
,D/PackageBroadcastService( 3155): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
I/SELinux ( 7249): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7249):  
I/SELinux ( 7249):  
,I/SELinux ( 7249): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/dalvikvm( 5760): GC_FOR_ALLOC freed 85K, 25% free 11929K/15788K, paused 42ms, total 44ms
,E/SELinux ( 7249): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/dalvikvm( 7249): >>>>> Normal User
,E/dalvikvm( 7249): >>>>> com.google.android.gms.unstable [ userId:0 | appId:10012 ]
,E/SELinux ( 7249): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/dalvikvm-heap( 5760): Grow heap (frag case) to 14.788MB for 2129936-byte allocation
,D/TimaKeyStoreProvider( 7249): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7249): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7249): Added TimaKesytore provider
,D/dalvikvm( 5760): GC_FOR_ALLOC freed 2K, 22% free 14006K/17872K, paused 79ms, total 79ms
,I/ActivityManager( 2401): Killing 6404:com.sec.android.service.cm/u0a82 (adj 15): empty #43
D/dalvikvm( 5760): GC_CONCURRENT freed 4K, 22% free 14004K/17872K, paused 7ms+8ms, total 37ms
D/dalvikvm( 5760): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/dalvikvm-heap( 5760): Grow heap (frag case) to 16.814MB for 2129936-byte allocation
,D/dalvikvm( 5760): GC_FOR_ALLOC freed <1K, 20% free 16083K/19956K, paused 41ms, total 41ms
,D/dalvikvm( 7249): GC_CONCURRENT freed 3014K, 31% free 9565K/13716K, paused 3ms+2ms, total 53ms
,D/dalvikvm( 7249): WAIT_FOR_CONCURRENT_GC blocked 49ms
,W/dalvikvm( 7249): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 7249): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 7249): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 7249): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 7249): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 7249): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 7249): install
,I/MultiDex( 7249): MultiDexExtractor.load(/data/app/com.google.android.gms-5.apk, false)
,I/MultiDex( 7249): loading existing secondary dex files
,I/MultiDex( 7249): load found 3 secondary dex files
,I/MultiDex( 7249): install done
,D/LocationManagerService( 2401): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/dalvikvm( 7249): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7249): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7249): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 7249): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 7249): VFY: unable to resolve instance field 36
,D/dalvikvm( 7249): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 7249): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7249): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7249): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 7249): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 7249): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 7249): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4226ed88
,D/dalvikvm( 7249): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4226ed88
,D/dalvikvm( 7249): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4226ed88, skipping init
,D/dalvikvm( 7249): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4226ed88
D/dalvikvm( 7249): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4226ed88
,V/JNIHelp ( 7249): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 7249): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4226ed88
,D/dalvikvm( 7249): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x4226ed88
D/dalvikvm( 7249): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4226ed88
,D/dalvikvm( 7249): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4226ed88
,D/dalvikvm( 2401): GC_EXPLICIT freed 1680K, 75% free 24834K/97084K, paused 16ms+23ms, total 252ms
,D/Headlines( 6888): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 6888): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 6888): Breath 8727 latestRequest time : 1453758260274 current time : 1453758269001
,I/System.out( 7125): Thread-654(HTTPLog):isShipBuild true
,I/System.out( 7125): Thread-654(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/ProviderInstaller( 7249): Installed default security provider GmsCore_OpenSSL
,I/dalvikvm( 7249): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 7249): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 7249): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 7249): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 7249): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7249): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 7249): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 7249): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 7249): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 7249): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 7249): VFY: replacing opcode 0x22 at 0x0000
,I/dalvikvm( 7249): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 7249): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 7249): VFY: replacing opcode 0x6e at 0x0036
,I/dalvikvm( 7249): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 7249): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 7249): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,E/Parcel  ( 1924): nm 16
,D/WVCdm   ( 1924): Instantiating CDM.
,I/WVCdm   ( 1924): Level3 Library Nov 20 2013 18:09:31
,E/wv_dash ( 1924): chunk TEE virt: 0x2008a0
,D/WVCdm   ( 1924): OEMCrypto_Initialize Level 1 success. I will use level 1.
,I/WVCdm   ( 1924): CdmEngine::OpenSession
,I/WVCdm   ( 1924): CdmEngine::QueryKeyControlInfo
,E/Parcel  ( 7249): nm 16
E/Parcel  ( 1924): nm 16
E/Parcel  ( 1924): nm 1
,I/WVCdm   ( 1924): CdmEngine::GenerateKeyRequest
,D/WVCdm   ( 1924): PrepareKeyRequest: nonce=2311583715
,I/dalvikvm( 7249): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 7249): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 7249): VFY: replacing opcode 0x6e at 0x003d
,W/dalvikvm( 7249): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/dalvikvm( 2845): GC_CONCURRENT freed 1897K, 23% free 10992K/14100K, paused 5ms+16ms, total 91ms
,W/dalvikvm( 7249): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 7249): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 7249): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 7249): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 7249): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 7249): Using platform SSLCertificateSocketFactory,
,D/dalvikvm( 2734): GC_CONCURRENT freed 1692K, 20% free 11885K/14824K, paused 7ms+11ms, total 113ms
,I/System.out( 7249): Thread-673(HTTPLog):isShipBuild true
,I/System.out( 7249): Thread-673(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/Parcel  ( 7249): nm 1834
,D/dalvikvm( 7249): GC_CONCURRENT freed 1659K, 21% free 10977K/13772K, paused 6ms+4ms, total 105ms
,D/dalvikvm( 7249): WAIT_FOR_CONCURRENT_GC blocked 50ms
,D/dalvikvm( 7249): WAIT_FOR_CONCURRENT_GC blocked 50ms
E/Parcel  ( 1924): nm 16
,I/WVCdm   ( 1924): CdmEngine::CloseSession
,D/Mms/MessagesLockscreen( 5610): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
,W/Binder  ( 2581): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 2581): android.view.InflateException: Binary XML file line #11: Error inflating class <unknown>
W/Binder  ( 2581): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
W/Binder  ( 2581): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
W/Binder  ( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
W/Binder  ( 2581): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
W/Binder  ( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
W/Binder  ( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
W/Binder  ( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:498)
W/Binder  ( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
W/Binder  ( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
W/Binder  ( 2581): 	at android.view.View.inflate(View.java:18495)
W/Binder  ( 2581): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
W/Binder  ( 2581): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
W/Binder  ( 2581): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
W/Binder  ( 2581): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
W/Binder  ( 2581): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239)
W/Binder  ( 2581): 	at android.os.Binder.execTransact(Binder.java:404)
W/Binder  ( 2581): 	at dalvik.system.NativeStart.run(Native Method)
W/Binder  ( 2581): Caused by: java.lang.reflect.InvocationTargetException
W/Binder  ( 2581): 	at java.lang.reflect.Constructor.constructNative(Native Method)
W/Binder  ( 2581): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
W/Binder  ( 2581): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
W/Binder  ( 2581): 	... 16 more
W/Binder  ( 2581): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
W/Binder  ( 2581): 	at android.os.Handler.<init>(Handler.java:200)
W/Binder  ( 2581): 	at android.os.Handler.<init>(Handler.java:114)
W/Binder  ( 2581): 	at android.widget.TextClock.<init>(TextClock.java:130)
W/Binder  ( 2581): 	at android.widget.TextClock.<init>(TextClock.java:191)
W/Binder  ( 2581): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
W/Binder  ( 2581): 	... 19 more
,E/JavaBinder( 2581): *** Uncaught remote exception!  (Exceptions are not yet supported across processes.)
E/JavaBinder( 2581): android.view.InflateException: Binary XML file line #11: Error inflating class <unknown>
E/JavaBinder( 2581): 	at android.view.LayoutInflater.createView(LayoutInflater.java:626)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.createViewFromTag(LayoutInflater.java:702)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:761)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.parseInclude(LayoutInflater.java:855)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:751)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.rInflate(LayoutInflater.java:769)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:498)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:398)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.inflate(LayoutInflater.java:354)
E/JavaBinder( 2581): 	at android.view.View.inflate(View.java:18495)
E/JavaBinder( 2581): 	at com.android.keyguard.sec.ContextualEventManager.<init>(ContextualEventManager.java:276)
E/JavaBinder( 2581): 	at com.android.keyguard.sec.ContextualEventManager.getInstance(ContextualEventManager.java:298)
E/JavaBinder( 2581): 	at com.android.keyguard.KeyguardViewMediator.removeContextualEvent(KeyguardViewMediator.java:2667)
E/JavaBinder( 2581): 	at com.android.keyguard.KeyguardService$1.removeContextualEvent(KeyguardService.java:158)
E/JavaBinder( 2581): 	at com.android.internal.policy.IKeyguardService$Stub.onTransact(IKeyguardService.java:239)
E/JavaBinder( 2581): 	at android.os.Binder.execTransact(Binder.java:404)
E/JavaBinder( 2581): 	at dalvik.system.NativeStart.run(Native Method)
E/JavaBinder( 2581): Caused by: java.lang.reflect.InvocationTargetException
E/JavaBinder( 2581): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/JavaBinder( 2581): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/JavaBinder( 2581): 	at android.view.LayoutInflater.createView(LayoutInflater.java:600)
E/JavaBinder( 2581): 	... 16 more
E/JavaBinder( 2581): Caused by: java.lang.RuntimeException: Can't create handler inside thread that has not called Looper.prepare()
E/JavaBinder( 2581): 	at android.os.Handler.<init>(Handler.java:200)
E/JavaBinder( 2581): 	at android.os.Handler.<init>(Handler.java:114)
E/JavaBinder( 2581): 	at android.widget.TextClock.<init>(TextClock.java:130)
E/JavaBinder( 2581): 	at android.widget.TextClock.<init>(TextClock.java:191)
E/JavaBinder( 2581): 	at com.android.keyguard.sec.SecKeyguardTextClock.<init>(SecKeyguardTextClock.java:27)
E/JavaBinder( 2581): 	... 19 more
,D/NativeLibraryUtils( 7249): Install completed successfully. count=14 extracted=0
,I/Icing   ( 3155): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
,I/Icing   ( 3155): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,I/System.out( 2845): Thread-98(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 2845): Thread-98(ApacheHTTPLog):isShipBuild true
,I/System.out( 2845): Thread-98(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/SPPClientService( 5512): [g] getNetMCC return empty string
,E/SPPClientService( 5512): [g] getNetMNC return empty string
,D/WearableService( 2734): callingUid 10012, callindPid: 2734
,E/MDM     ( 2734): [131] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 2845): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 2845): Proximity feature is not enabled.
,D/LocationInitializer( 3155): Restart initialization of location
,V/GLSActivity( 2845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 2734): No location to return for getLastLocation()
,W/FusedLocationProvider( 2734): location=null
,D/dalvikvm( 7249): GC_CONCURRENT freed 1369K, 18% free 11646K/14160K, paused 10ms+8ms, total 81ms
,D/dalvikvm( 7249): WAIT_FOR_CONCURRENT_GC blocked 41ms
,D/CalendarSyncAdapter( 7125): Found 0 events marked dirty & lastSynced
,I/ActivityManager( 2401): Killing 6424:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty #43
,I/ActivityManager( 2401): Killing 6455:com.samsung.helphub/1000 (adj 15): empty #43
,D/dalvikvm( 7249): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x423a6d10
,D/LocationManagerService( 2401): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/dalvikvm( 7249): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x423a6d10
,D/dalvikvm( 7249): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x423a6d10, skipping init
,I/System.out( 2845): GDataFeedFetcher calls detatch()
,I/PeopleSync( 3155): onPerformSync() [5005f081]
,D/LocationManagerService( 2401): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/QuickConnect[1.1][2] ( 5089): PreDiscoveryHelper.mContentObserver - Contact Data changed
,V/QuickConnect[1.1][2] ( 5089): CONTACT_Info.getMyMobileNumber - 
D/Mms/Contact( 5610): sContactsObserver.onChange(),selfUpdate=false
,D/Mms/Contact( 5610): performUpdate:widgetCount=0
,D/ContactProvider( 3589): getAllContactInfoList Start
,D/QuickConnect[1.1][2] ( 5089): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 5089): CONTACT_Info.getMyMobileNumber - null 
,D/ContactProvider( 3589): getAllContactInfoList End
,I/syncContacts( 3589): thread: 167, onChange
,I/System.out( 2845): GDataFeedFetcher calls detatch()
,D/Mms/Contact( 5610): sContactsObserver.onChange(),selfUpdate=false
D/QuickConnect[1.1][2] ( 5089): PreDiscoveryHelper.mContentObserver - Contact Data changed
,V/QuickConnect[1.1][2] ( 5089): CONTACT_Info.getMyMobileNumber - 
,D/QuickConnect[1.1][2] ( 5089): CONTACT_Info.getAccountNumber - ($)
,I/QuickConnect[1.1][2] ( 5089): CONTACT_Info.getMyMobileNumber - null 
,I/PeopleSync( 3155): Setting subscription: result=true [5005f081]
,D/ContactProvider( 3589): getAllContactInfoList Start
,D/dalvikvm( 7249): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,I/PeopleSync( 3155): Starting sync, feed=null [5005f081]
,D/dalvikvm( 7305): DexOpt: load 5ms, verify+opt 21ms, 123556 bytes
,D/dalvikvm( 2722): GC_EXPLICIT freed 321K, 28% free 9963K/13700K, paused 5ms+10ms, total 76ms
D/dalvikvm( 7249): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 7249): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 127ms
,D/ContactProvider( 3589): getAllContactInfoList End
,I/syncContacts( 3589): thread: 168, onChange
,D/libEGL  ( 7249): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7249): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7249): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7249): Mali API Version : 401
,I/Mali    ( 7249): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2401): stay LED for fully charged
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5115): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5115): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/Settings( 7249): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/BaseAppContext( 3155): Using Auth Proxy for data requests.
,W/BaseAppContext( 3155): Using Auth Proxy for data requests.
,W/BaseAppContext( 3155): Using Auth Proxy for data requests.
,W/BaseAppContext( 3155): Using Auth Proxy for data requests.
,W/BaseAppContext( 3155): Using Auth Proxy for data requests.
W/BaseAppContext( 3155): Using Auth Proxy for data requests.
,W/BaseAppContext( 3155): Using Auth Proxy for data requests.
,W/BaseAppContext( 3155): Using Auth Proxy for data requests.
,I/PeopleSync( 3155): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,D/LocationManagerService( 2401): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,W/BaseAppContext( 3155): Using Auth Proxy for data requests.
,W/BaseAppContext( 3155): Using Auth Proxy for data requests.
,D/LocationManagerService( 2401): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/PicasaService( 3589): start picasa sync
,D/PicasaService( 3589): end picasa sync
,D/LocationManagerService( 2401): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/PowerManagerService( 2401): [PWL] Off : 50s ago
I/PowerManagerService( 2401): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService( 2401): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2401): [PWL]       PARTIAL_WAKE_LOCK              'Checkin Service' (uid=10012, pid=3155, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=7446)
I/PowerManagerService( 2401): [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10012, pid=2845, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=5214)
,I/PowerManagerService( 2401): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.gms.people/com.google/eM_ADDR' (uid=1000, pid=2401, ws=WorkSource{10012}) (elapsedTime=1100)
,I/PowerManagerService( 2401): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.plus.content.EsProvider/com.google/eM_ADDR' (uid=1000, pid=2401, ws=WorkSource{10133}) (elapsedTime=36)
,I/SELinux ( 7324): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7324):  
,I/SELinux ( 7324): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7324):  
I/SELinux ( 7324):  
,I/SELinux ( 7324): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7324): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7324): >>>>> Normal User
,E/dalvikvm( 7324): >>>>> com.google.android.music:main [ userId:0 | appId:10125 ]
,E/SELinux ( 7324): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7324): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7324): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7324): Added TimaKesytore provider
,D/dalvikvm( 2845): GC_CONCURRENT freed 1697K, 21% free 11236K/14200K, paused 4ms+5ms, total 52ms
,D/dalvikvm( 7324): GC_FOR_ALLOC freed 3011K, 31% free 9561K/13716K, paused 19ms, total 19ms
,I/Mali    ( 7249): Mali API Version : 401
,I/Mali    ( 7249): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/dalvikvm( 7324): GC_CONCURRENT freed 224K, 15% free 9569K/11180K, paused 1ms+3ms, total 19ms
,I/Mali    ( 7249): Mali API Version : 401
,I/Mali    ( 7249): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/MusicStore( 7324): Database version: 85
,W/ContextImpl( 7324): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 380, Delta = 0
,D/WVMDrmPlugIn( 1923): WVMDrmPlugin::onInitialize : 139
,D/WVMDrmPlugIn( 1923): WVMDrmPlugin::onSetOnInfoListener : add 139
I/PrGenericPlugin( 1923): [A] ENTER onInitialize : 0x8b
I/PrGenericPlugin( 1923): [A] LEAVE onInitialize : 0x8b
,D/WVMDrmPlugIn( 1923): WVMDrmPlugin::onGetSupportInfo : 0
,W/ContextImpl( 7324): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PrGenericPlugin( 1923): [A] ENTER onGetSupportInfo : 0
,I/PrGenericPlugin( 1923): [A] LEAVE onGetSupportInfo : 0
,E/Parcel  ( 1924): nm 16
,I/WVCdm   ( 1924): CdmEngine::OpenSession
,I/WVCdm   ( 1924): CdmEngine::QueryKeyControlInfo
,E/Parcel  ( 7249): nm 16
E/Parcel  ( 1924): nm 16
,E/Parcel  ( 1924): nm 16
E/Parcel  ( 1924): nm 16
E/Parcel  ( 1924): nm 1
,I/WVCdm   ( 1924): CdmEngine::GenerateKeyRequest
,D/WVCdm   ( 1924): PrepareKeyRequest: nonce=3091474092
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7324): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7324): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7324): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,D/WifiDisplayAdapter( 2401): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/Parcel  ( 7249): nm 1869
E/Parcel  ( 1924): nm 16
,I/WVCdm   ( 1924): CdmEngine::CloseSession
,I/CheckinRequestBuilder( 3155): Classify the device as Phone.
,D/dalvikvm( 2401): GC_EXPLICIT freed 2275K, 75% free 24768K/97084K, paused 9ms+20ms, total 252ms
,D/WifiDisplayAdapter( 2401): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/Watchdog( 2401): !@Sync 5
,I/AudioService( 2401): getStreamVolume 3 index 70
,I/MediaRouter( 7324): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/Mms/Contact( 5610): performUpdate:widgetCount=0
,E/SPPClientService( 5512): [b] __ProvisionReply__
,E/SPPClientService( 5512): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5512): [d] null
,V/AlarmManager( 2401):  next == MAX_VALUE
,D/WifiDisplayAdapter( 2401): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/CastUtils( 7324): Removing provider: MediaRouter.RouteProviderInfo{ packageName=com.google.android.gms }
,E/SPPClientService( 5512): [g] getPLMN return empty string
,E/SPPClientService( 5512): [b] SharedConstants.WHAT_PROV_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5512): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,D/dalvikvm( 5512): GC_CONCURRENT freed 2139K, 25% free 10403K/13708K, paused 8ms+10ms, total 91ms
,E/SPPClientService( 5512): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5512): [g] getNetMCC return empty string
,D/dalvikvm( 3155): GC_EXPLICIT freed 1827K, 19% free 12917K/15880K, paused 8ms+12ms, total 118ms
,I/ConfigStore( 7324): Config Database version: 1
,I/CheckinTask( 3155): Sending checkin request (12261 bytes)
,I/System.out( 7324): Thread-688(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7324): Thread-688(ApacheHTTPLog):isShipBuild true
,I/System.out( 7324): Thread-688(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/PeopleSync( 3155): Sync finished, successful=true, took 2202ms
,I/PeopleContactsSync( 3155): CP2 sync start [5005f081]
,I/PeopleContactsSync( 3155): CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/PeopleContactsSync( 3155): Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/PeopleContactsSync( 3155): CP2 cleanup done, kept= duration=112 ms
,I/PeopleContactsSync( 3155): ===CP2 sync finished, success=true, time=147,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
,I/PeopleSync( 3155): ***Sync finished***, duration: 3210 [5005f081]
,D/DelayedSyncController( 5961): Delaying sync.
,I/CheckinResponseProcessor( 3155): From server: 11 gservices updates and 2 deletes
,I/SELinux ( 7371): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7371):  
,I/SELinux ( 7371): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7371):  
I/SELinux ( 7371):  
,I/SELinux ( 7371): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7371): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7371): >>>>> Normal User
,E/dalvikvm( 7371): >>>>> com.google.android.apps.docs [ userId:0 | appId:10094 ]
,E/SELinux ( 7371): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7371): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7371): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7371): Added TimaKesytore provider
,I/System.out( 7324): SyncAdapterThread-1 calls detatch()
,D/PreloadUpdateManagerStateMachine( 6578): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 6578): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6578): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6578): AutoUpdateTriggerManager:IDLE:setInterval:86400000
,D/hcjo    ( 6578): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6578): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 6578): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6578): entry::IDLE
,D/dalvikvm( 7371): GC_CONCURRENT freed 2974K, 31% free 9597K/13712K, paused 10ms+1ms, total 38ms
,D/dalvikvm( 7371): WAIT_FOR_CONCURRENT_GC blocked 28ms
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7324): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,I/CertBlacklister( 2401): Certificate blacklist changed, updating...
,I/CertBlacklister( 2401): Certificate blacklist updated
,I/GservicesProvider( 2845): main difference update completed
,I/SELinux ( 7385): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7385):  
,I/CheckinRequestBuilder( 3155): Checkin reason type: 12 attempt count: 1
,I/Icing   ( 3155): Indexing 6245F4AA15572483160DEB38E2CBB6FB536E377A from com.google.android.music
,E/ActivityThread( 3155): Failed to find provider info for com.google.android.wearable.settings
I/SELinux ( 7385): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7385):  
I/SELinux ( 7385):  
I/SELinux ( 7385): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7385): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7385): >>>>> Normal User
E/dalvikvm( 7385): >>>>> com.google.android.configupdater [ userId:0 | appId:10003 ]
E/SELinux ( 7385): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/dalvikvm( 7371): Could not find class 'com.google.trix.ritz.shared.messages.b', referenced from method bnz.<init>
W/dalvikvm( 7371): VFY: unable to resolve new-instance 7208 (Lcom/google/trix/ritz/shared/messages/b;) in Lbnz;
,D/dalvikvm( 7371): VFY: replacing opcode 0x22 at 0x03bc
E/dalvikvm( 7371): Could not find class 'com.google.trix.ritz.shared.render.g', referenced from method bnz.<init>
W/dalvikvm( 7371): VFY: unable to resolve new-instance 7339 (Lcom/google/trix/ritz/shared/render/g;) in Lbnz;
,D/dalvikvm( 7371): VFY: replacing opcode 0x22 at 0x03cb
,W/MusicApiClient( 7324): No content in 'data' field in GET sync response for Track
,I/System.out( 7324): SyncAdapterThread-1 calls detatch()
,D/TimaKeyStoreProvider( 7385): in addTimaSignatureService
E/dalvikvm( 7371): Could not find class 'com.google.trix.ritz.shared.behavior.validation.a', referenced from method bnz.<init>
W/dalvikvm( 7371): VFY: unable to resolve new-instance 7168 (Lcom/google/trix/ritz/shared/behavior/validation/a;) in Lbnz;
,D/dalvikvm( 7371): VFY: replacing opcode 0x22 at 0x05d8
,E/dalvikvm( 7371): Could not find class 'com.google.trix.ritz.shared.mutation.O', referenced from method bnz.<init>
W/dalvikvm( 7371): VFY: unable to resolve new-instance 7301 (Lcom/google/trix/ritz/shared/mutation/O;) in Lbnz;
,D/dalvikvm( 7371): VFY: replacing opcode 0x22 at 0x07a9
,D/TimaKeyStoreProvider( 7385): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7385): Added TimaKesytore provider
,D/dalvikvm( 7371): DexOpt: unable to opt direct call 0xb146 at 0x3be in Lbnz;.<init>
,D/dalvikvm( 7371): DexOpt: unable to opt direct call 0xb292 at 0x3cd in Lbnz;.<init>
,D/dalvikvm( 7371): DexOpt: unable to opt direct call 0xb108 at 0x5da in Lbnz;.<init>
,D/dalvikvm( 7371): DexOpt: unable to opt direct call 0xb23b at 0x7ab in Lbnz;.<init>
,W/dalvikvm( 7371): method Lcom/google/android/apps/docs/editors/toolbar/PreHoneyCombActionBar;.a incorrectly overrides package-private method with same name in Lakm;
,W/dalvikvm( 7371): method Lcom/google/android/apps/docs/editors/toolbar/PreHoneyCombActionBar;.b incorrectly overrides package-private method with same name in Lakm;
,D/dalvikvm( 7385): GC_CONCURRENT freed 3002K, 31% free 9571K/13712K, paused 3ms+3ms, total 28ms
,D/dalvikvm( 7385): WAIT_FOR_CONCURRENT_GC blocked 20ms
,W/dalvikvm( 7371): VFY: unable to resolve instance field 20115
,D/dalvikvm( 7371): VFY: replacing opcode 0x54 at 0x001e
,I/dalvikvm( 7371): DexOpt: unable to optimize instance field ref 0x4e93 at 0x28 in LbvF;.getInstance
,W/ContextImpl( 7385): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.START (has extras) } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 7385): Update started
,E/UpdateRequestReceiver( 7385): Received malformed URL while handling Gservices.CHANGED_ACTION
,W/ContextImpl( 7385): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.START (has extras) } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.google.android.configupdater.UpdateRequestReceiver.startUpdate:219 
,I/UpdateFetcherService( 7385): Update started
,D/dalvikvm( 2845): GC_EXPLICIT freed 799K, 22% free 11171K/14200K, paused 6ms+12ms, total 143ms
,I/Icing   ( 3155): Indexing done 6245F4AA15572483160DEB38E2CBB6FB536E377A
,E/SPPClientService( 5512): [b] __InitReply__
,W/MusicApiClient( 7324): No content in 'data' field in GET sync response for SyncablePlaylist
,I/System.out( 7324): SyncAdapterThread-1 calls detatch()
,E/UpdateRequestReceiver( 7385): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 7385): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 7385): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/SELinux ( 7419): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7419):  
I/ActivityManager( 2401): Killing 6491:com.sec.kidsplat.installer/u0a160 (adj 15): empty #43
,W/ActiveOrDefaultContextProvider( 7371): Missing scope.enter somewhere. Returning default context
,I/ActivityManager( 2401): Waited long enough for: ServiceRecord{456f9f98 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/AmoledAdjustTimer( 2401): prevTemp = 304, currTemp = 306, prevStep = 4, currStep = 4
,W/ActiveOrDefaultContextProvider( 7371): Missing scope.enter somewhere. Returning default context
,I/SELinux ( 7419): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7419):  
I/SELinux ( 7419):  
,I/SELinux ( 7419): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7419): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7419): >>>>> Normal User
,E/dalvikvm( 7419): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ]
,E/SELinux ( 7419): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7419): in addTimaSignatureService
,D/dalvikvm( 2401): GC_EXPLICIT freed 1073K, 75% free 24774K/97084K, paused 7ms+20ms, total 218ms
,D/TimaKeyStoreProvider( 7419): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7419): Added TimaKesytore provider
,I/DownloadManager( 2722): Download 98 starting
,D/dalvikvm( 7371): GC_CONCURRENT freed 2127K, 24% free 10468K/13724K, paused 4ms+11ms, total 52ms
,I/DownloadManager( 2722): Download 99 starting
,W/MusicApiClient( 7324): No content in 'data' field in GET sync response for SyncablePlaylistEntry
,I/System.out( 7324): SyncAdapterThread-1 calls detatch()
,W/ActivityThread( 2722): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/GAV2    ( 7371): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/dalvikvm( 3155): Jit: resizing JitTable from 4096 to 8192
,I/CheckinRequestBuilder( 3155): Classify the device as Phone.
,D/dalvikvm( 7419): GC_CONCURRENT freed 2999K, 31% free 9575K/13712K, paused 3ms+1ms, total 24ms
,D/dalvikvm( 7419): WAIT_FOR_CONCURRENT_GC blocked 19ms
,W/MusicApiClient( 7324): No content in 'data' field in GET sync response for SyncableRadioStation
,I/System.out( 7324): SyncAdapterThread-1 calls detatch()
,I/MusicSyncAdapter( 7324): Periodic sync is disabled
,D/dalvikvm( 7371): GC_FOR_ALLOC freed 248K, 23% free 10569K/13724K, paused 29ms, total 29ms
,D/dalvikvm( 7371): GC_FOR_ALLOC freed <1K, 23% free 10608K/13724K, paused 35ms, total 35ms
,I/CheckinTask( 3155): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/System.out( 7371): Thread-693(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7371): Thread-693(ApacheHTTPLog):isShipBuild true
,I/System.out( 7371): Thread-693(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/CheckinService( 3155): Checking schedule, now: 1453758275572 next: 1454316618469
,I/CheckinService( 3155): active receiver: disabled
,I/Search.GservicesUpdateTask( 5949): Updating Gservices keys
,D/EnterpriseDeviceManagerService( 2401): Creating context as user 0
,D/CheckinService( 3155): Recording last checkin time for package unspecified as 1453758275628
,I/System.out( 2722): Thread-53(HTTPLog):isShipBuild true
,I/System.out( 2722): Thread-53(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 2722): Thread-52(HTTPLog):isShipBuild true
,I/System.out( 2722): Thread-52(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/ActivityManager( 2401): Killing 6509:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty #43
,D/dalvikvm( 2734): GC_CONCURRENT freed 1565K, 19% free 12263K/15028K, paused 5ms+12ms, total 66ms
,I/ActivityManager( 2401): Killing 6528:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty #43
,I/CheckinService( 3155): Checkin interval check for package: unspecified last checkin: 1453758275628 min interval config: 0 actual interval: 247
,I/CheckinService( 3155): Checking schedule, now: 1453758275919 next: 1454316618469
,I/CheckinService( 3155): active receiver: disabled
,I/SystemUpdateService( 3155): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,I/DownloadManager( 2722): Ignoring Content-Length since Transfer-Encoding is also defined
,D/SystemUpdateService( 3155): onCreate
,D/SystemUpdateService( 3155): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 3155): cancelUpdate (empty URL)
,I/SystemUpdateService( 3155): active receiver: disabled
I/dalvikvm( 3155): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
,W/dalvikvm( 3155): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 3155): VFY: replacing opcode 0x71 at 0x004e
,I/System.out( 7371): DocsSyncAdapter calls detatch()
,V/DownloadManager( 2722): MIME Type = text/plain
,I/DownloadManager( 2722): Download 99 finished with status SUCCESS
,D/dalvikvm( 2845): GC_EXPLICIT freed 611K, 22% free 11209K/14200K, paused 4ms+6ms, total 58ms
,I/DownloadManager( 2722): Ignoring Content-Length since Transfer-Encoding is also defined
,W/BaseAppContext( 2734): Using Auth Proxy for data requests.
,V/DownloadManager( 2722): MIME Type = text/plain
,I/DownloadManager( 2722): Download 98 finished with status SUCCESS
,E/BaseAppContext( 2734): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,I/Auth    ( 2845): [BroadcastManager] Broadcasting account services changed.
,D/dalvikvm( 3155): GC_EXPLICIT freed 1702K, 19% free 12907K/15932K, paused 12ms+10ms, total 113ms
,D/dalvikvm( 2845): GC_EXPLICIT freed 635K, 21% free 11226K/14200K, paused 6ms+15ms, total 74ms
,I/Auth    ( 2845): [BroadcastManager] Broadcasting account services changed.
,D/SystemUpdateService( 3155): onDestroy
,I/System.out( 7371): DocsSyncAdapter calls detatch()
,E/DynamiteModule( 3155): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 3155): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-5.apk", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-5.apk.classes2.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-5.apk.classes3.zip", zip file "/data/data/com.google.android.gms/code_cache/secondary-dexes/com.google.android.gms-5.apk.classes4.zip"],nativeLibraryDirectories=[/data/app-lib/com.google.android.gms-5, /data/app-lib/com.google.android.gms-5, /data/app-lib/com.google.android.gms-5, /data/app-lib/com.google.android.gms-5, /data/app-lib/com.google.android.gms-5, /vendor/lib, /system/lib]]
E/DynamiteModule( 3155): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:67)
E/DynamiteModule( 3155): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:497)
E/DynamiteModule( 3155): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:457)
E/DynamiteModule( 3155): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 3155): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 3155): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 3155): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 3155): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 3155): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 3155): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/DynamiteModule( 3155): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/DynamiteModule( 3155): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/DynamiteModule( 3155): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 3155): 	at android.os.Looper.loop(Looper.java:146)
E/DynamiteModule( 3155): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/DynamiteModule( 3155): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/DynamiteModule( 3155): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/DynamiteModule( 3155): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/DynamiteModule( 3155): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/DynamiteModule( 3155): 	at dalvik.system.NativeStart.main(Native Method)
,I/DynamiteModule( 3155): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
,I/DynamiteModule( 3155): Selected local version of com.google.android.gms.flags
,D/dalvikvm( 7371): GC_FOR_ALLOC freed 2364K, 25% free 11181K/14800K, paused 55ms, total 55ms
,D/SystemEventReceiver( 3155): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 3155): Updating ocr activity enabled=false
,I/ActivityManager( 2401): Killing 6547:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty #43
,W/ActivityManager( 2401): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/GCM     ( 2845): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/GCoreUlr( 2734): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_ACTIVE_STATE cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{source=sync_server_wins}]
,D/OcrModelManager( 3155): Updating downloaded model state (gservices changed)
,I/GCoreUlr( 2734): DispatchingService.onCreate()
,I/System.out( 7371): DocsSyncAdapter calls detatch()
,D/dalvikvm( 2401): GC_EXPLICIT freed 2100K, 75% free 24870K/97084K, paused 9ms+26ms, total 277ms
,I/GCoreUlr( 2734): DispatchingService.updateActiveState+sync_server_wins: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2734): Unbound from all location providers
,I/GCoreUlr( 2734): Place inference reporting - stopped
,I/System.out( 7371): DocsSyncAdapter calls detatch()
,E/dalvikvm( 2734): Could not find class 'android.app.usage.UsageStatsManager', referenced from method com.google.android.contextmanager.m.a.az.i
,W/dalvikvm( 2734): VFY: unable to resolve check-cast 57 (Landroid/app/usage/UsageStatsManager;) in Lcom/google/android/contextmanager/m/a/az;
,D/dalvikvm( 2734): VFY: replacing opcode 0x1f at 0x001a
,D/dalvikvm( 2734): DexOpt: unable to opt direct call 0x00e3 at 0x2b in Lcom/google/android/contextmanager/m/a/az;.i
,I/dalvikvm( 2734): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.contextmanager.m.a.bc.b
,W/dalvikvm( 2734): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2734): VFY: replacing opcode 0x6e at 0x0012
,I/GCoreUlr( 2734): DispatchingService.onDestroy()
,I/GCoreUlr( 2734): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2734): Unbound from all location providers
,I/GCoreUlr( 2734): Place inference reporting - stopped
,I/GCoreUlr( 2734): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 2734): DispatchingService.onCreate()
,D/dalvikvm( 2734): GC_CONCURRENT freed 2189K, 22% free 12127K/15520K, paused 8ms+8ms, total 76ms
,D/dalvikvm( 2734): WAIT_FOR_CONCURRENT_GC blocked 40ms
D/dalvikvm( 2734): WAIT_FOR_CONCURRENT_GC blocked 42ms
,D/dalvikvm( 2734): WAIT_FOR_CONCURRENT_GC blocked 42ms
,W/ContextImpl( 7324): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/GCoreUlr( 2734): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7324): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 7324): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 7324): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7324): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
D/dalvikvm( 2845): GC_EXPLICIT freed 865K, 21% free 11253K/14176K, paused 11ms+16ms, total 116ms
W/ContextImpl( 7324): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/ContextImpl( 7324): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7324): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7324): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
D/CacheService( 7324): onCreate
W/ArtDownloadService( 7324): Setting cache size 0
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7324): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/CacheService( 7324): onBind
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7324): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ArtDownloadService( 7324): Setting cache size 0
,I/MusicLeanback( 7324): Conditions not met for autocaching.
,I/MusicLeanback( 7324): Stop autocaching.
,D/CacheService( 7324): onDestroy
,D/dalvikvm( 3155): GC_EXPLICIT freed 1101K, 19% free 12927K/15932K, paused 13ms+13ms, total 132ms
,D/GCM     ( 2845): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/GeofencerStateMachine( 2734): Ignoring removeGeofence because network location is disabled.
,D/GCM     ( 2845): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,E/ctxmgr  ( 2734): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,W/ContextImpl( 7385): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,I/GCoreUlr( 2734): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/ctxmgr  ( 2734): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10012, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 2734): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,I/GCoreUlr( 2734): Unbound from all location providers
,I/GCoreUlr( 2734): Place inference reporting - stopped
,I/GCoreUlr( 2734): DispatchingService.onDestroy()
,I/GCoreUlr( 2734): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2734): Unbound from all location providers
,I/GCoreUlr( 2734): Place inference reporting - stopped
,D/dalvikvm( 7371): GC_FOR_ALLOC freed 1824K, 25% free 11211K/14800K, paused 56ms, total 56ms
,I/System.out( 7371): DocsSyncAdapter calls detatch()
,W/ContextImpl( 7385): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_METADATA (has extras) } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.google.android.configupdater.UpdateRequestReceiver.handleMetadataDownload:244 
,I/DownloadManager( 2722): Download 100 starting
,D/dalvikvm( 7371): GC_FOR_ALLOC freed 834K, 25% free 11215K/14800K, paused 47ms, total 47ms
,I/DownloadManager( 2722): Ignoring Content-Length since Transfer-Encoding is also defined
,I/DownloadManager( 2722): Download 101 starting
,I/DownloadManager( 2722): Ignoring Content-Length since Transfer-Encoding is also defined
,W/GAV2    ( 7371): DocsSyncAdapter-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,V/DownloadManager( 2722): MIME Type = text/plain
,I/DownloadManager( 2722): Download 100 finished with status SUCCESS
,W/ContextImpl( 7324): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 7324): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/CacheService( 7324): onCreate
,D/CacheService( 7324): onBind
,V/DownloadManager( 2722): MIME Type = text/plain
,I/DownloadManager( 2722): Download 101 finished with status SUCCESS
,I/MusicLeanback( 7324): Conditions not met for autocaching.
,I/MusicLeanback( 7324): Stop autocaching.
,W/ContextImpl( 7324): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:529 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/GAV2    ( 7371): Thread[GAThread,5,main]: No campaign data found.
,W/ContextImpl( 7385): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.SmsShortCodes.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7324): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 7324): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/cache
,I/UpdateFetcherService( 7385): Update downloaded, starting installation
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
I/UpdateFetcherService( 7385): Started installation
D/CacheService( 7324): onDestroy
,D/dalvikvm( 2722): GC_CONCURRENT freed 1457K, 24% free 10445K/13700K, paused 6ms+14ms, total 64ms
,W/ContextImpl( 7385): Implicit intents with startService are not safe: Intent { act=com.google.android.configupdater.CertPin.NEW_CONTENT (has extras) } android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.google.android.configupdater.UpdateRequestReceiver.handleContentDownload:231 
,I/UpdateFetcherService( 7385): Update downloaded, starting installation
,I/UpdateFetcherService( 7385): Started installation
,D/dalvikvm( 2401): GC_EXPLICIT freed 1781K, 75% free 24848K/97084K, paused 16ms+24ms, total 320ms
,I/ActivityManager( 2401): Killing 6026:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty #43
,I/ConfigUpdateInstallReceiver( 2401): Not installing, new version is <= current version
,E/Auth.Api.Credentials( 3155): [CredentialSyncAdapter] Unknown sync event.
,I/GAV2    ( 5760): Thread[GAThread,5,main]: No campaign data found.
,V/CalendarSyncAdapter( 7125): Saving inProgress state: {calendarId=thalitester@gmail.com, maxAttendees=50, maxResults=200, timeMax=2017-01-24T00:00:00.000Z, updatedMin=2015-11-18T16:31:02.459Z}
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2401): stay LED for fully charged
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 5115): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5115): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/dalvikvm( 7125): GC_CONCURRENT freed 2414K, 27% free 10100K/13708K, paused 6ms+5ms, total 63ms
,D/CalendarSyncAdapter( 7125): Found 0 events marked dirty & lastSynced
,V/CalendarSyncAdapter( 7125): Saving inProgress state: {calendarId=thalitester@gmail.com, maxAttendees=50, maxResults=200, timeMax=2017-01-24T00:00:00.000Z, timeMin=2017-02-23T00:00:00.000Z}
,D/CalendarSyncAdapter( 7125): Found 0 events marked dirty & lastSynced
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 370, Delta = -10
,I/ActivityManager( 2401): Waited long enough for: ServiceRecord{435db438 u0 com.sec.spp.push/.PushClientService},
,D/AmoledAdjustTimer( 2401): prevTemp = 306, currTemp = 307, prevStep = 4, currStep = 4,
,D/PackageManager( 2401): [MSG] WRITE_SETTINGS,
,W/PackageSettings( 2401): Skipping PackageSetting{42afcc98 com.example.hello/10614} due to missing metadata,
,D/PackageManager( 2401): [MSG] SEND_PENDING_BROADCAST,
,D/PackageManager( 2401): Sending to user 0: act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000000 Bundle[{android.intent.extra.changed_component_name=com.google.android.gms.checkin.CheckinService$ActiveReceiver, android.intent.extra.DONT_KILL_APP=true, android.intent.extra.UID=10012, android.intent.extra.changed_component_name_list=[Ljava.lang.String;@42f82f90, com.samsung.android.intent.extra.SECRET_APP=false, android.intent.extra.user_handle=0}],
,D/RegisteredServicesCache( 2756): empty dynamic service,
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT",
,I/PackageManager( 2401):   Scheme: "sms"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO",
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "smsto",
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :,
,I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2401):   Scheme: "mms"
,I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2401):   Scheme: "mmsto"
I/InputReader( 2401): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "sms"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "smsto"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "mms"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "mmsto"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/Icing.InternalIcingCorporaProvider( 5949): Updating corpora: A: com.google.android.gms, C: MAYBE
,D/FileShare-Server( 6108): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,D/dalvikvm( 7030): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS,
,W/dalvikvm( 7030): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;,
,D/dalvikvm( 7030): VFY: replacing opcode 0x62 at 0x000a,
,D/dalvikvm( 7030): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs,
W/dalvikvm( 7030): VFY: unable to resolve instance field 36,
D/dalvikvm( 7030): VFY: replacing opcode 0x54 at 0x005f
D/BezelQuickConnect( 5101): BezelBroadcastReceiver - onReceive : android.intent.action.PACKAGE_CHANGED,
,D/BezelQuickConnect( 5101): BezelBroadcastReceiver - packageName : com.google.android.gms,
D/dalvikvm( 7030): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS,
W/dalvikvm( 7030): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;,
,D/dalvikvm( 7030): VFY: replacing opcode 0x62 at 0x0047,
,D/dalvikvm( 7030): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs,
,I/dalvikvm( 7030): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b,
,D/dalvikvm( 7030): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42c7cbc0,
D/dalvikvm( 7030): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42c7cbc0
,D/dalvikvm( 7030): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42c7cbc0, skipping init,
,D/dalvikvm( 7030): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42c7cbc0,
D/dalvikvm( 7030): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42c7cbc0
,V/JNIHelp ( 7030): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...,
,D/PackageBroadcastService( 3155): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 3155): Null package name or gms related package.  Ignoreing.
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 7030): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42c7cbc0
,D/dalvikvm( 7030): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x42c7cbc0
D/dalvikvm( 7030): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42c7cbc0
,D/dalvikvm( 7030): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42c7cbc0
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/Icing   ( 3155): updateResources: need to parse f{com.google.android.gms}
,I/GCoreNlp( 2734): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ProviderInstaller( 7030): Installed default security provider GmsCore_OpenSSL
,W/ApplicationsProvider( 2979): Could not fetch usage stats
W/ApplicationsProvider( 2979): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2979): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2979): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2979): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2979): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2979): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2979): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2979): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2979): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:212)
W/ApplicationsProvider( 2979): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2979): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2979): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/LocationProviderProxy( 2401): applying state to connected service
,D/LocationProviderProxy( 2401): applying state to connected service
,D/dalvikvm( 2845): GC_EXPLICIT freed 455K, 22% free 11196K/14176K, paused 6ms+10ms, total 71ms
,I/Icing.InternalIcingCorporaProvider( 5949): UpdateCorporaTask done [took 1160 ms] updated apps [took 1160 ms] 
,I/Icing   ( 3155): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
,D/Icing   ( 3155): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 3155): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,D/dalvikvm( 3155): GC_CONCURRENT freed 1940K, 20% free 12921K/16072K, paused 6ms+7ms, total 65ms
,I/Icing   ( 3155): Indexing 8AF1F6B88973B002A001A3BB90ED270D05322BB1 from com.google.android.googlequicksearchbox
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/Icing   ( 3155): Indexing done 8AF1F6B88973B002A001A3BB90ED270D05322BB1
,V/AlarmManager( 2401): waitForAlarm result :8,
,D/Headlines( 6888): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 6888): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 6888): Breath 30029 latestRequest time : 1453758260274 current time : 1453758290303,
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 307, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2401): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2401): mCoverManager.getCoverState() : true
,V/HeadsetService( 5115): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 5115): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 350, Delta = -20
,D/AmoledAdjustTimer( 2401): prevTemp = 307, currTemp = 307, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2401): [PWL] Off : 75s ago,
,V/AlarmManager( 2401): waitForAlarm result :8,
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,W/IcingInternalCorpora( 3155): getNumBytesRead when not calculated.,
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2401): stay LED for fully charged
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 5115): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5115): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 340, Delta = -10,
,E/Watchdog( 2401): !@Sync 6,
,D/AmoledAdjustTimer( 2401): prevTemp = 307, currTemp = 306, prevStep = 4, currStep = 4,
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/dalvikvm( 2401): GC_CONCURRENT freed 3507K, 75% free 25075K/97084K, paused 10ms+20ms, total 227ms,
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 306, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2401): stay LED for fully charged,
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 5115): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5115): Disconnected process message: 10,
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,I/Icing   ( 3155): Indexing 6245F4AA15572483160DEB38E2CBB6FB536E377A from com.google.android.music,
,I/Icing   ( 3155): Indexing done 6245F4AA15572483160DEB38E2CBB6FB536E377A
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 340, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 306, currTemp = 306, prevStep = 4, currStep = 4,
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2401): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/BatteryService( 2401): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5115): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5115): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 330, Delta = -10,
,D/AmoledAdjustTimer( 2401): prevTemp = 306, currTemp = 305, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2401): [PWL] Off : 105s ago,
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2401): mCoverManager.getCoverState() : true
,D/BatteryService( 2401): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5115): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5115): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 330, Delta = 0,
,E/Watchdog( 2401): !@Sync 7,
,D/AmoledAdjustTimer( 2401): prevTemp = 305, currTemp = 304, prevStep = 4, currStep = 4,
,V/AlarmManager( 2401): waitForAlarm result :4,
,V/AlarmManager( 2401): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/Headlines( 6888): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 6888): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 6888): Breath 75083 latestRequest time : 1453758260274 current time : 1453758335357,
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2401): mCoverManager.getCoverState() : true,
,D/BatteryService( 2401): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5115): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5115): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2401): prevTemp = 304, currTemp = 303, prevStep = 4, currStep = 4,
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2401): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4,
,V/AlarmManager( 2401): waitForAlarm result :8,
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2401): mCoverManager.getCoverState() : true
,D/BatteryService( 2401): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5115): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5115): Disconnected process message: 10,
I/PowerManagerService( 2401): [PWL] Off : 140s ago
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 330, Delta = 0,
,E/Watchdog( 2401): !@Sync 8,
,D/AmoledAdjustTimer( 2401): prevTemp = 303, currTemp = 302, prevStep = 4, currStep = 4,
,V/AlarmManager( 2401): waitForAlarm result :4,
,V/AlarmManager( 2401): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/Headlines( 6888): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 6888): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 6888): Breath 105183 latestRequest time : 1453758260274 current time : 1453758365457,
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2401): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4,
,V/AlarmManager( 2401): waitForAlarm result :8,
,D/Headlines( 6888): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 6888): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
D/Headlines( 6888): Breath 120029 latestRequest time : 1453758260274 current time : 1453758380303
,D/Headlines( 6888): stop ,
,D/Headlines( 6888): Breath.onDestroy : ,
I/ActivityManager( 2401): Killing 6229:com.sec.pcw.device/1000 (adj 15): empty #43
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2401): mCoverManager.getCoverState() : true
,D/BatteryService( 2401): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5115): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5115): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2401): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4,
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/ClearcutLoggerApiImpl( 2845): disconnect managed GoogleApiClient,
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2401): !@Sync 9,
,I/ClearcutLoggerApiImpl( 3155): disconnect managed GoogleApiClient,
,D/AmoledAdjustTimer( 2401): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2401): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2401): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2401): mCoverManager.getCoverState() : true
,D/BatteryService( 2401): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5115): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5115): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2401): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4,
,D/TimaService( 2401): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 2401): TIMA: checkEvent, operation: 50000 subject: 10000,
,D/TimaService( 2401): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_initialize( 2401): initializing...,
I/TLC_TIMA_PKM_initialize( 2401): root = 0, root_strlen = 1,
,I/TLC_TIMA_PKM_initialize( 2401): process = ffffffff00000000000000000000000a, process_strlen = 32,
I/TZ: mc_tlc_communication( 2401): input max_sendmsg_size = 262196,
I/TZ: mc_tlc_communication( 2401): input max_recvmsg_size = 262196
,I/TZ: mc_tlc_communication( 2401): root = 0, root_len = 1,
,I/TZ: mc_tlc_communication( 2401): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2401): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2401): aligned max_recvmsg_size = 262208,
I/TZ: mc_tlc_communication( 2401): device_id = 0x0
I/TZ: mc_tlc_communication( 2401): tlc_open() was called
,I/TZ: mc_tlc_communication( 2401): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2401): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2401): Opening the session,
,I/TZ: mc_tlc_communication( 2401): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 2401): Trustlet response is completed,
,V/AlarmManager( 2401): waitForAlarm result :8,
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2401): !@Sync 10,
,I/TLC_TIMA_PKM_measure_kernel( 2401): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2401): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2401): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
D/TimaService( 2401): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2401): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2401): mCoverManager.getCoverState() : true
,D/BatteryService( 2401): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5115): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5115): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2401): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4,
,V/GLSActivity( 2845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,V/GLSActivity( 2845): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2401): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2401): [PWL] Off : 225s ago,
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2401): !@Sync 11,
,D/AmoledAdjustTimer( 2401): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,V/AlarmManager( 2401): waitForAlarm result :4,
,V/AlarmManager( 2401): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 8505): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 8505):  
,I/SELinux ( 8505): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 8505):  
I/SELinux ( 8505):  
,I/SELinux ( 8505): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 8505): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 8505): >>>>> Normal User,
,E/dalvikvm( 8505): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 8505): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 8505): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 8505): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8505): Added TimaKesytore provider
,D/dalvikvm( 8505): GC_CONCURRENT freed 3009K, 31% free 9563K/13712K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 8505): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/ActivityManager( 2401): Killing 5923:com.sec.android.cloudagent/u0a2 (adj 15): empty #43
,D/BatteryService( 2401): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2401): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2401): mCoverManager.getCoverState() : true,
,D/BatteryService( 2401): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5115): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5115): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2401): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2401): SIOP:: AP = 320, Delta = 0,
,I/jxcore-log( 6450): --= Surplus to requirements =--,
I/jxcore-log( 6450): 
I/jxcore-log( 6450): ****TEST TOOK:  ms ****
I/jxcore-log( 6450): 
,I/jxcore-log( 6450): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
I/jxcore-log( 6450): 
,D/AmoledAdjustTimer( 2401): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/AndroidRuntime( 8619): 
D/AndroidRuntime( 8619): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8619): CheckJNI is OFF
D/AndroidRuntime( 8619): setted country_code = Poland
,D/AndroidRuntime( 8619): setted countryiso_code = PL,
D/AndroidRuntime( 8619): setted sales_code = PLS
D/AndroidRuntime( 8619): readGMSProperty: start
D/AndroidRuntime( 8619): readGMSProperty: already setted!!
D/AndroidRuntime( 8619): readGMSProperty: end
,D/AndroidRuntime( 8619): addProductProperty: start,
,D/dalvikvm( 8619): Trying to load lib libjavacore.so 0x0,
,D/dalvikvm( 8619): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 8619): Trying to load lib libnativehelper.so 0x0,
D/dalvikvm( 8619): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 8619): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,E/memtrack( 8619): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 8619): failed to load memtrack module: -2
,D/dalvikvm( 8619): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods,
,D/AndroidRuntime( 8619): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 2401): START PACKAGE DELETE: observer{1131136368}
D/PackageManager( 2401): pkg{<packageName>}
D/PackageManager( 2401): user{0}
,D/PackageManager( 2401): deletePackageAsUser : uid = 2000 userId = 0
,D/PackageManager( 2401): [MSG] DELETE_PACKAGE_AS_USER
D/ApplicationPolicy( 2401): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2401): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2401): deletePackageX- pkg:com.test.thalitest, userId:0
,D/PackageManager( 2401): !@killApplicatoin: 10648, uninstall pkg
,I/ActivityManager( 2401): Killing 6450:com.test.thalitest/u0a648 (adj 0): stop com.test.thalitest
,D/PointerIcon( 2401): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2401): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2401): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2401): setHoveringSpenCustomIcon IconType is same.1
,I/SurfaceFlinger( 1920): id=18 Removed EimLayer (5/10)
,I/SurfaceFlinger( 1920): id=18 Removed EimLayer (-2/10)
,I/SurfaceFlinger( 1920): id=17 Removed EimLayer (4/9)
,I/SurfaceFlinger( 1920): id=17 Removed EimLayer (-2/9)
,V/WindowManager( 2401): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
W/InputDispatcher( 2401): channel ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher( 2401): channel ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher( 2401): Attempted to unregister already unregistered input channel
I/SurfaceFlinger( 1920): id=19 Removed NainActivit (6/8)
,I/SurfaceFlinger( 1920): id=19 Removed NainActivit (-2/8)
,I/WindowState( 2401): WIN DEATH: Window{424390b0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/Launcher( 2781): onRestart, Launcher: 1110046784
D/Launcher( 2781): onStart, Launcher: 1110046784
D/Launcher.HomeView( 2781): onStart
,I/SurfaceFlinger( 1920): id=22 createSurf (720x1280),1 flag=4, Mauncher
D/STATUSBAR-StatusBarManagerService( 2401): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2401): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2401): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2401): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2401): setHoveringSpenCustomIcon IconType is same.1
D/STATUSBAR-StatusBarManagerService( 2401): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 2401): tr p:2781,o:f
,D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2401): semi p:2781,o:f
,W/InputMethodManagerService( 2401): Got RemoteException sending setActive(false) notification to pid 6450 uid 10648
,W/ContextImpl( 2401): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/PackageSettings( 2401): Skipping PackageSetting{42afcc98 com.example.hello/10614} due to missing metadata
,D/PackageManager( 2401): checkUidPermission - Execution time: 197 ms
D/PackageManager( 2401): checkUidPermission - Execution time: 153 ms
,D/PackageManager( 2401): checkUidPermission - Execution time: 121 ms
D/PackageManager( 2401): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10648, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/dalvikvm( 5949): GC_EXPLICIT freed 1619K, 28% free 10036K/13772K, paused 9ms+8ms, total 93ms
,D/dalvikvm( 3155): GC_EXPLICIT freed 503K, 20% free 12910K/16072K, paused 25ms+10ms, total 153ms
D/PackageManager( 2401): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10648, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/dalvikvm( 2979): GC_EXPLICIT freed 1722K, 27% free 10107K/13708K, paused 12ms+7ms, total 130ms
,I/FPMS_FingerprintManagerService( 2601): onReceive: android.intent.action.PACKAGE_REMOVED
,E/SamsungIME( 2947): mOCRHelper is null
,W/GeofencerStateMachine( 2734): Ignoring removeGeofence because network location is disabled.
,D/QuickConnect[1.1][2] ( 5089): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "sms"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/elm:14132( 7174): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "smsto"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/InputReader( 2401): Reconfiguring input devices.  changes=0x00000010
,D/dalvikvm( 2401): GC_EXPLICIT freed 3191K, 75% free 24977K/97084K, paused 15ms+24ms, total 306ms
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "mms"
,I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 2401): WAIT_FOR_CONCURRENT_GC blocked 38ms
D/elm:14132( 7174): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132( 7174): ElmAgentService : onCreate()
D/elm:14132( 7174): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 7174): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 7174): MDMBridge.getInstance()
D/elm:14132( 7174): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 7174): MDMBridge.getAllLicenseInfoFromSDK()
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "mmsto"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 8636): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8636):  
,D/RegisteredServicesCache( 2756): empty dynamic service
,D/elm:14132( 7174): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
I/SELinux ( 8636): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8636):  
I/SELinux ( 8636):  
,I/SELinux ( 8636): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/elm:14132( 7174): ElmAgentService : onDestroy().
E/SELinux ( 8636): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8636): >>>>> Normal User
,E/dalvikvm( 8636): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2401):   Scheme: "sms"
,E/SELinux ( 8636): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "smsto"
,I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 8636): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8636): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8636): Added TimaKesytore provider
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "mms"
,I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService( 2401): PackageReceiver onReceive()
,I/HarmonyEASService( 2401): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2401):   Scheme: "mmsto"
,D/EnterpriseDeviceManagerService( 2401): Package has changed for user 0
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 2756): GC_CONCURRENT freed 2347K, 26% free 10260K/13740K, paused 14ms+6ms, total 153ms
,D/dalvikvm( 8636): GC_CONCURRENT freed 2989K, 31% free 9584K/13712K, paused 6ms+4ms, total 52ms
,D/dalvikvm( 8636): WAIT_FOR_CONCURRENT_GC blocked 37ms
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 8652): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8652):  
,I/ActivityManager( 2401): Killing 6066:com.sec.android.diagmonagent/1000 (adj 15): empty #43
,D/BackupManagerService( 2401): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 2401): removePackageParticipantsLocked: uid=10648 #1
,I/SELinux ( 8652): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8652):  
I/SELinux ( 8652):  
I/SELinux ( 8652): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/dalvikvm( 2401): GC_EXPLICIT freed 1150K, 75% free 25200K/97084K, paused 19ms+40ms, total 684ms
,E/SELinux ( 8652): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8652): >>>>> Normal User
,E/dalvikvm( 8652): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
,E/SELinux ( 8652): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/PackageManager( 2401): delete sourFile : 
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager( 2401): delete native library directory: 
,D/TimaKeyStoreProvider( 8652): in addTimaSignatureService
,D/AndroidRuntime( 8619): Shutting down VM
D/PackageManager( 2401): return delete result to caller: 1131136368
,D/PackageManager( 2401): returnCode: 1
D/TimaKeyStoreProvider( 8652): Cannot add TimaSignature Service, License check Failed
D/dalvikvm( 8619): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+0ms, total 5ms
D/ActivityThread( 8652): Added TimaKesytore provider
,I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2401):   Scheme: "sms"
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "smsto"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "mms"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 8652): GC_CONCURRENT freed 3003K, 31% free 9562K/13708K, paused 4ms+4ms, total 37ms
,D/dalvikvm( 8652): WAIT_FOR_CONCURRENT_GC blocked 33ms
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2401):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2401):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2401):   Scheme: "mmsto"
I/PackageManager( 2401): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/ApplicationsProvider( 2979): Could not fetch usage stats
W/ApplicationsProvider( 2979): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2979): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2979): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2979): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2979): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2979): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2979): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2979): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2979): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2979): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2979): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2979): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 8664): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8664):  
,I/ActivityManager( 2401): Killing 6682:com.vlingo.midas/u0a34 (adj 15): empty #43
,I/SELinux ( 8664): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8664):  
I/SELinux ( 8664):  
,I/SELinux ( 8664): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8664): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 8664): >>>>> Normal User
,E/dalvikvm( 8664): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
,E/SELinux ( 8664): [DEBUG] seapp_context_lookup: seinfoCategory = release
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 8664): in addTimaSignatureService
W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider( 8664): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 8664): Added TimaKesytore provider
W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2401): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/CrashAnrDetector( 2401): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2401): clearDefaults: com.test.thalitest
,W/AtomicFile( 2401): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl( 2401): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,D/dalvikvm( 8664): GC_CONCURRENT freed 2996K, 31% free 9571K/13708K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 8664): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/SELinux ( 8680): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8680):  
,I/ActivityManager( 2401): Killing 5818:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 8680): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8680):  
I/SELinux ( 8680):  
,I/SELinux ( 8680): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8680): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8680): >>>>> Normal User
,E/dalvikvm( 8680): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
,E/SELinux ( 8680): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/dalvikvm( 8680): Enabling JNI app bug workarounds for target SDK version 8...
,D/TimaKeyStoreProvider( 8680): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8680): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8680): Added TimaKesytore provider
,D/dalvikvm( 8680): GC_CONCURRENT freed 3006K, 31% free 9572K/13716K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 8680): WAIT_FOR_CONCURRENT_GC blocked 22ms
,E/SQLiteDatabase( 8680): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase( 8680): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8680): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8680): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8680): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8680): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8680): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8680): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8680): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8680): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8680): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8680): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8680): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8680): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8680): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 8680): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/SQLiteDatabase( 8680): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 8680): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 8680): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 8680): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 8680): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 8680): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 8680): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 8680): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8680): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8680): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 8680): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 8680): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 8680): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 8680): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 8680): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 8680): Shutting down VM
,W/dalvikvm( 8680): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 8680): FATAL EXCEPTION: main
E/AndroidRuntime( 8680): Process: com.sec.pcw.device, PID: 8680
E/AndroidRuntime( 8680): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.URLProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8680): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 8680): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 8680): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 8680): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8680): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 8680): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8680): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 8680): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 8680): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 8680): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 8680): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 8680): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 8680): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 8680): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8680): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8680): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 8680): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 8680): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 8680): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 8680): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8680): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 8680): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 8680): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 8680): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 8680): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 8680): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 8680): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 8680): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/AndroidRuntime( 8680): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 8680): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 8680): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 8680): 	... 12 more
,E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop227.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2401): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2401): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2401): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2401): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2401): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2401): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2401): 	... 5 more
,I/SELinux ( 8693): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8693):  
,I/Process ( 8680): Sending signal. PID: 8680 SIG: 9
,I/ActivityManager( 2401): Process com.sec.pcw.device (pid 8680) (adj 0) has died.
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 12% free 9508K/10688K, paused 4ms+4ms, total 40ms
,I/SELinux ( 8693): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8693):  
I/SELinux ( 8693):  
,I/SELinux ( 8693): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8693): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8693): >>>>> Normal User
,E/dalvikvm( 8693): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10035 ]
,E/SELinux ( 8693): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9508K/10688K, paused 3ms+3ms, total 33ms
,D/TimaKeyStoreProvider( 8693): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8693): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8693): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9508K/10688K, paused 3ms+3ms, total 31ms
,D/dalvikvm( 8693): GC_CONCURRENT freed 3005K, 31% free 9574K/13716K, paused 4ms+2ms, total 26ms
,D/dalvikvm( 8693): WAIT_FOR_CONCURRENT_GC blocked 21ms
,W/System.err( 8693): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err( 8693): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 8693): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 8693): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err( 8693): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err( 8693): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err( 8693): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err( 8693): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err( 8693): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
,W/System.err( 8693): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err( 8693): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
W/System.err( 8693): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err( 8693): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err( 8693): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 8693): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err( 8693): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8693): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 8693): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 8693): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 8693): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 8693): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 8693): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 8693): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 8693): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
,W/System.err( 8693): 	at libcore.io.Posix.open(Native Method)
W/System.err( 8693): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 8693): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 8693): 	... 21 more
,D/GalaxyFinderApplication( 8693): [Slink platform] Version = 29011
,D/GalaxyFinderApplication( 8693): [Slink platform] use state of slink location service is [false] to [true]
,I/SELinux ( 8707): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8707):  
,E/SQLiteLog( 6258): (3850) statement aborts at 35: [DELETE FROM app_registry WHERE package_name=? AND plugin_id=? AND sync_status != 170004 AND sync_status = 170002] disk I/O error
,W/dalvikvm( 6258): threadid=12: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 6258): FATAL EXCEPTION: IntentService[HandleAppDataService]
E/AndroidRuntime( 6258): Process: com.sec.android.app.shealth, PID: 6258
E/AndroidRuntime( 6258): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6258): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6258): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 6258): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6258): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6258): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 6258): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericDelete(BaseContentProvider.java:486)
E/AndroidRuntime( 6258): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.delete(BaseContentProvider.java:441)
E/AndroidRuntime( 6258): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6258): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6258): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.deleteAppRegistryData(AppRegistryDbManagerWithProvider.java:459)
E/AndroidRuntime( 6258): 	at com.sec.android.app.shealth.service.HandleAppDataService.onHandleIntent(HandleAppDataService.java:56)
E/AndroidRuntime( 6258): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6258): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6258): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6258): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 6258): Sending signal. PID: 6258 SIG: 9
E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop228.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2401): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2401): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2401): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2401): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2401): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2401): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2401): 	... 5 more
,I/ActivityManager( 2401): Process com.sec.android.app.shealth (pid 6258) (adj 5) has died.
,I/SELinux ( 8707): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8707):  
I/SELinux ( 8707):  
,I/SELinux ( 8707): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8707): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 8707): >>>>> Normal User
,E/dalvikvm( 8707): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10043 ]
,E/SELinux ( 8707): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 8707): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8707): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8707): Added TimaKesytore provider
,D/dalvikvm( 8707): GC_CONCURRENT freed 3001K, 31% free 9565K/13708K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 8707): WAIT_FOR_CONCURRENT_GC blocked 21ms
,E/SQLiteDatabase( 8707): Failed to open database '/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db'.
E/SQLiteDatabase( 8707): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8707): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8707): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8707): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8707): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8707): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8707): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8707): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8707): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8707): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8707): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8707): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8707): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8707): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 8707): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:429)
E/SQLiteDatabase( 8707): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 8707): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 8707): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 8707): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 8707): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 8707): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 8707): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 8707): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8707): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8707): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 8707): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 8707): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 8707): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 8707): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 8707): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 8707): Shutting down VM
,W/dalvikvm( 8707): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 8707): FATAL EXCEPTION: main
E/AndroidRuntime( 8707): Process: com.samsung.android.sdk.samsunglink, PID: 8707
E/AndroidRuntime( 8707): java.lang.RuntimeException: Unable to get provider com.mfluent.asp.datamodel.ASPMediaStoreProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8707): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 8707): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 8707): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 8707): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8707): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 8707): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8707): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 8707): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 8707): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 8707): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 8707): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 8707): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 8707): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 8707): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8707): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8707): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 8707): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 8707): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 8707): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 8707): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8707): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 8707): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 8707): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 8707): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 8707): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 8707): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 8707): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 8707): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:429)
E/AndroidRuntime( 8707): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 8707): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 8707): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 8707): 	... 12 more
,E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop229.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2401): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2401): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2401): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2401): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2401): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2401): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2401): 	... 5 more
I/Process ( 8707): Sending signal. PID: 8707 SIG: 9
I/SA      ( 6041): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 6041): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
I/ActivityManager( 2401): Killing 6338:com.policydm/1000 (adj 15): empty #43
,I/ActivityManager( 2401): Process com.samsung.android.sdk.samsunglink (pid 8707) (adj 9) has died.
,E/SharedPreferencesImpl( 3589): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,I/Icing.InternalIcingCorporaProvider( 5949): Updating corpora: A: com.test.thalitest, C: MAYBE
,E/SQLiteLog( 5949): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/dalvikvm( 5949): threadid=14: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 5949): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 5949): Process: com.google.android.googlequicksearchbox:search, PID: 5949
E/AndroidRuntime( 5949): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 5949): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 5949): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 5949): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 5949): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 5949): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 5949): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 5949): 	at com.google.android.search.core.summons.icing.ApplicationsHelper.updateApplicationsList(ApplicationsHelper.java:171)
E/AndroidRuntime( 5949): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.updateApplications(InternalIcingCorporaProvider.java:511)
E/AndroidRuntime( 5949): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:288)
E/AndroidRuntime( 5949): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 5949): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 5949): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AndroidRuntime( 5949): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AndroidRuntime( 5949): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AndroidRuntime( 5949): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AndroidRuntime( 5949): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AndroidRuntime( 5949): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5949): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5949): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 5949): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/SELinux ( 8726): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8726):  
,I/Process ( 5949): Sending signal. PID: 5949 SIG: 9
E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop230.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2401): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2401): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2401): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2401): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2401): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2401): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2401): 	... 5 more
,I/ActivityManager( 2401): Process com.google.android.googlequicksearchbox:search (pid 5949) (adj 5) has died.
,I/SELinux ( 8726): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8726):  
I/SELinux ( 8726):  
,I/SELinux ( 8726): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8726): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8726): >>>>> Normal User
,E/dalvikvm( 8726): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,E/SELinux ( 8726): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 8726): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8726): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8726): Added TimaKesytore provider
,D/dalvikvm( 8726): GC_CONCURRENT freed 2994K, 31% free 9575K/13708K, paused 2ms+1ms, total 24ms
,D/dalvikvm( 8726): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/UserAnalysis.PlaceProvider( 8726): Create SecureDbHelper
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 8726): Create SecureDbHelper
,E/SQLiteDatabase( 8726): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 8726): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8726): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8726): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8726): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 8726): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 8726): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteDatabase( 8726): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 8726): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 8726): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 8726): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 8726): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8726): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8726): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 8726): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 8726): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 8726): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 8726): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 8726): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 8726): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 8726): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 8726): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 8726): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 8726): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 8726): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 8726): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 8726): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 8726): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 8726): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 8726): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 8726): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 8726): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 8726): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 8726): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 8726): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 8726): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 8726): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteOpenHelper( 8726): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 8726): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 8726): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 8726): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 8726): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 8726): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 8726): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 8726): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 8726): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 8726): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 8726): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 8726): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 8726): Opened privacy in read-only mode
,E/SQLiteDatabase( 8726): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 8726): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8726): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8726): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8726): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 8726): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 8726): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteDatabase( 8726): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 8726): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 8726): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 8726): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 8726): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8726): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8726): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 8726): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 8726): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 8726): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 8726): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 8726): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 8726): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 8726): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 8726): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 8726): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 8726): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 8726): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 8726): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 8726): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 8726): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 8726): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 8726): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 8726): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 8726): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 8726): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 8726): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 8726): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 8726): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 8726): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteOpenHelper( 8726): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 8726): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 8726): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 8726): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 8726): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 8726): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 8726): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 8726): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 8726): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 8726): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 8726): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 8726): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 8726): Opened privacy in read-only mode
,E/SQLiteDatabase( 8726): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 8726): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8726): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8726): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8726): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8726): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 8726): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
E/SQLiteDatabase( 8726): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 8726): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 8726): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 8726): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 8726): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8726): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8726): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 8726): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 8726): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 8726): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 8726): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 8726): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 8726): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 8726): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 8726): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 8726): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 8726): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 8726): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 8726): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 8726): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 8726): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 8726): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteData,base.java:696)
W/System.err( 8726): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 8726): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 8726): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 8726): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 8726): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 8726): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
W/System.err( 8726): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
W/System.err( 8726): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 8726): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 8726): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 8726): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8726): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 8726): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 8726): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 8726): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 8726): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 8726): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 8726): 	at dalvik.system.NativeStart.main(Native Method)
,I/SELinux ( 8739): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8739):  
,I/SELinux ( 8739): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8739):  
I/SELinux ( 8739):  
,I/SELinux ( 8739): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8739): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8739): >>>>> Normal User
,E/dalvikvm( 8739): >>>>> com.samsung.android.app.assistantmenu [ userId:0 | appId:1000 ]
,E/SELinux ( 8739): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 8739): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8739): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8739): Added TimaKesytore provider
,D/dalvikvm( 8739): GC_CONCURRENT freed 3004K, 31% free 9572K/13712K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 8739): WAIT_FOR_CONCURRENT_GC blocked 21ms
,W/ContextImpl( 8739): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:165 android.app.ActivityThread.handleReceiver:2698 
,D/RCPManager( 7237):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2401):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 2401): queryAllProviders():  providerCallBack is not register for 0
,E/SQLiteDatabase( 8739): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 8739): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8739): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8739): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8739): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8739): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8739): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8739): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8739): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8739): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8739): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8739): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8739): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8739): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8739): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 8739): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 8739): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 8739): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 8739): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8739): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8739): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 8739): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 8739): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,W/System.err( 8739): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 8739): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 8739): ,	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 8739): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
,W/System.err( 8739): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
,W/System.err( 8739): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
,W/System.err( 8739): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
,W/System.err( 8739): 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 8739): 	,at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
I/SELinux ( 8752): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8752):  
,W/System.err( 8739): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 8739): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
,W/System.err( 8739): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
,W/System.err( 8739): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 8739): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
,W/System.err( 8739): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 8739): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 8739): 	at android.os.Looper.loop(Looper.java:146)
,W/System.err( 8739): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager( 2401): Killing 6845:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,V/AlarmManager( 2401): waitForAlarm result :8
,V/AlarmManager( 2401): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,I/SELinux ( 8752): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8752):  
I/SELinux ( 8752):  
,I/SELinux ( 8752): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8752): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 8752): >>>>> Normal User
,E/dalvikvm( 8752): >>>>> com.sec.android.service.cm [ userId:0 | appId:10082 ]
,E/SELinux ( 8752): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/TimaKeyStoreProvider( 8752): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8752): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8752): Added TimaKesytore provider
,D/dalvikvm( 8752): GC_CONCURRENT freed 3002K, 31% free 9571K/13712K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 8752): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/CapabilityManagerService New( 8752): Receiver Broadcast:android.intent.action.PACKAGE_REMOVED
,D/CapabilityManagerService New( 8752): The package(com.test.thalitest) removed
,W/System.err( 2401): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
,W/System.err( 2401): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2401): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2401): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
,W/System.err( 2401): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2401): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 2401): 	at dalvik.system.NativeStart.run(Native Method)
,W/System.err( 2401): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 2401): 	at libcore.io.Posix.open(Native Method)
,W/System.err( 2401): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 2401): 	... 8 more
,W/System.err( 2401): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2401): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
,W/System.err( 2401): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2401): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
,W/System.err( 2401): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2401): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 2401): 	at dalvik.system.NativeStart.run(Native Method)
,W/System.err( 2401): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 2401): 	at libcore.io.Posix.open(Native Method)
,W/System.err( 2401): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 2401): 	... 8 more
,I/SELinux ( 8764): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8764):  
I/ActivityManager( 2401): Killing 6085:com.samsung.android.scloud.backup/u0a62 (adj 15): empty #43
,I/SELinux ( 8764): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8764):  
I/SELinux ( 8764):  
,I/SELinux ( 8764): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8764): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8764): >>>>> Normal User
,E/dalvikvm( 8764): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10104 ]
,E/SELinux ( 8764): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 8764): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8764): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8764): Added TimaKesytore provider
,D/dalvikvm( 8764): GC_CONCURRENT freed 3006K, 31% free 9565K/13712K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 8764): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/MagazineService::MagazineBroadcastReceiver( 6436): [onReceive] android.intent.action.PACKAGE_REMOVED com.test.thalitest
,I/MagazineService::MagazineService( 6436): [onHandleIntent] ACTION_PACKAGE_REMOVED
,E/SQLiteLog( 6436): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/dalvikvm( 6436): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
,I/SELinux ( 8777): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8777):  
E/AndroidRuntime( 6436): FATAL EXCEPTION: IntentService[MagazineService::MagazineService]
E/AndroidRuntime( 6436): Process: com.samsung.android.magazine.service, PID: 6436
E/AndroidRuntime( 6436): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6436): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6436): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 6436): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6436): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6436): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 6436): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 6436): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:408)
E/AndroidRuntime( 6436): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6436): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6436): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/AndroidRuntime( 6436): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6436): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6436): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6436): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 6436): Sending signal. PID: 6436 SIG: 9
E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop231.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2401): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2401): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2401): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2401): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2401): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2401): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2401): 	... 5 more
,I/ActivityManager( 2401): Process com.samsung.android.magazine.service (pid 6436) (adj 5) has died.
,I/SELinux ( 8777): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8777):  
I/SELinux ( 8777):  
,I/SELinux ( 8777): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8777): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8777): >>>>> Normal User
,E/dalvikvm( 8777): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 8777): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 8777): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8777): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8777): Added TimaKesytore provider
,I/SELinux ( 8790): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8790):  
D/dalvikvm( 8777): GC_CONCURRENT freed 2998K, 31% free 9579K/13716K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 8777): WAIT_FOR_CONCURRENT_GC blocked 21ms
,E/SQLiteDatabase( 8777): Failed to open database '/data/data/com.samsung.helphub/databases/search.db'.
E/SQLiteDatabase( 8777): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8777): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8777): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8777): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8777): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8777): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8777): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8777): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8777): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8777): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8777): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8777): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8777): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8777): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 8777): 	at com.samsung.helphub.search.SearchProvider.onCreate(SearchProvider.java:63)
E/SQLiteDatabase( 8777): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 8777): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 8777): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 8777): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 8777): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 8777): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 8777): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 8777): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8777): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8777): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 8777): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 8777): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 8777): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 8777): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 8777): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 8777): Couldn't open search.db for writing (will try read-only):
E/SQLiteOpenHelper( 8777): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 8777): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 8777): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 8777): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 8777): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 8777): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 8777): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 8777): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 8777): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 8777): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 8777): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 8777): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 8777): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 8777): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 8777): 	at com.samsung.helphub.search.SearchProvider.onCreate(SearchProvider.java:63)
E/SQLiteOpenHelper( 8777): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteOpenHelper( 8777): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteOpenHelper( 8777): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteOpenHelper( 8777): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteOpenHelper( 8777): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteOpenHelper( 8777): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteOpenHelper( 8777): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteOpenHelper( 8777): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 8777): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 8777): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 8777): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 8777): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 8777): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 8777): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 8777): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 8777): Opened search.db in read-only mode
,I/SELinux ( 8790): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8790):  
I/SELinux ( 8790):  
,I/SELinux ( 8790): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8790): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
I/SELinux ( 8794): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8794):  
E/dalvikvm( 8790): >>>>> Normal User
,E/dalvikvm( 8790): >>>>> com.google.android.googlequicksearchbox:search [ userId:0 | appId:10059 ]
,E/SELinux ( 8790): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
I/ActivityManager( 2401): Killing 6982:com.android.email/u0a157 (adj 15): empty #43
,D/TimaKeyStoreProvider( 8790): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8790): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8790): Added TimaKesytore provider
,I/SELinux ( 8794): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8794):  
I/SELinux ( 8794):  
,I/SELinux ( 8794): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8794): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8794): >>>>> Normal User
,E/dalvikvm( 8794): >>>>> com.android.keychain [ userId:0 | appId:1000 ]
,E/SELinux ( 8794): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 8794): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8794): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8794): Added TimaKesytore provider
,D/dalvikvm( 8790): GC_CONCURRENT freed 3001K, 31% free 9571K/13708K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 8790): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 8794): GC_CONCURRENT freed 3000K, 31% free 9571K/13708K, paused 2ms+1ms, total 26ms
,D/dalvikvm( 8794): WAIT_FOR_CONCURRENT_GC blocked 23ms
,W/ContextImpl( 8794): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2698 
,E/SQLiteDatabase( 8794): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 8794): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8794): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8794): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8794): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8794): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8794): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8794): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8794): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8794): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8794): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8794): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8794): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8794): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8794): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 8794): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/SQLiteDatabase( 8794): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/SQLiteDatabase( 8794): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 8794): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8794): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8794): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 8794): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 8794): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 8794): Process: com.android.keychain, PID: 8794
E/AndroidRuntime( 8794): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8794): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8794): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 8794): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 8794): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 8794): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 8794): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8794): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 8794): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 8794): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 8794): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 8794): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 8794): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 8794): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 8794): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/AndroidRuntime( 8794): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/AndroidRuntime( 8794): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 8794): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8794): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 8794): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/SELinux ( 8816): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8816):  
,E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop232.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2401): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2401): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2401): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2401): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2401): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2401): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2401): 	... 5 more
I/Process ( 8794): Sending signal. PID: 8794 SIG: 9
I/Icing.InternalIcingCorporaProvider( 8790): Updating corpora: A: com.test.thalitest, C: MAYBE
,I/ActivityManager( 2401): Process com.android.keychain (pid 8794) (adj 5) has died.
,I/SELinux ( 8816): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8816):  
I/SELinux ( 8816):  
,I/SELinux ( 8816): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8816): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8816): >>>>> Normal User
,E/dalvikvm( 8816): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10160 ]
,D/LocationManagerService( 2401): getProviders()=[passive]
,E/SELinux ( 8816): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 8816): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8816): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8816): Added TimaKesytore provider
,D/dalvikvm( 8816): GC_CONCURRENT freed 3008K, 31% free 9561K/13708K, paused 3ms+2ms, total 33ms
,D/dalvikvm( 8816): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/KidsModeInstallReceiver( 8816): onReceive intent data =  package:com.test.thalitest
,D/KidsPlatformStub( 8816): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 8837): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8837):  
I/ActivityManager( 2401): Killing 7000:com.sec.android.provider.badge/u0a76 (adj 15): empty #43
,I/SELinux ( 8837): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8837):  
I/SELinux ( 8837):  
,I/SELinux ( 8837): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8837): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8837): >>>>> Normal User
,E/dalvikvm( 8837): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10164 ]
,E/SELinux ( 8837): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 8837): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8837): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8837): Added TimaKesytore provider
,E/SharedPreferencesImpl( 3155): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,E/Icing   ( 3155): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,E/SharedPreferencesImpl( 3155): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,E/SharedPreferencesImpl( 3155): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak,
,E/Icing   ( 3155): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system),
,E/SharedPreferencesImpl( 3155): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak,
D/dalvikvm( 8837): GC_CONCURRENT freed 3002K, 31% free 9574K/13716K, paused 2ms+1ms, total 27ms
,D/dalvikvm( 8837): WAIT_FOR_CONCURRENT_GC blocked 24ms,
,E/SQLiteDatabase( 8837): Failed to open database '/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db'.,
E/SQLiteDatabase( 8837): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8837): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8837): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8837): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
,E/SQLiteDatabase( 8837): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8837): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8837): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8837): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8837): 	,at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8837): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8837): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8837): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268),
E/SQLiteDatabase( 8837): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8837): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 8837): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:265)
E/SQLiteDatabase( 8837): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:228)
,E/SQLiteDatabase( 8837): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 8837): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 8837): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 8837): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
,E/SQLiteDatabase( 8837): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 8837): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 8837): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 8837): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8837): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8837): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 8837): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 8837): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 8837): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 8837): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 8837): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 8837): Shutting down VM
,W/dalvikvm( 8837): threadid=1: thread exiting with uncaught exception (group=0x4180ac08),
,E/AndroidRuntime( 8837): FATAL EXCEPTION: main,
E/AndroidRuntime( 8837): Process: com.samsung.android.provider.shootingmodeprovider, PID: 8837
E/AndroidRuntime( 8837): java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8837): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 8837): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 8837): 	,at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 8837): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8837): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 8837): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8837): 	at android.os.Looper.loop(Looper.java:146),
E/AndroidRuntime( 8837): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 8837): 	at java.lang.reflect.Method.invokeNative(Native Method)
,E/AndroidRuntime( 8837): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 8837): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 8837): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 8837): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 8837): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
E/AndroidRuntime( 8837): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8837): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 8837): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 8837): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 8837): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 8837): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8837): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 8837): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 8837): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696),
E/AndroidRuntime( 8837): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 8837): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 8837): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 8837): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
,E/AndroidRuntime( 8837): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:265)
E/AndroidRuntime( 8837): 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:228)
E/AndroidRuntime( 8837): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 8837): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 8837): ,	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 8837): 	... 12 more
,E/SharedPreferencesImpl( 3155): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak,
,E/DropBoxManagerService( 2401): Can't write: system_app_crash,
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop233.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
,E/DropBoxManagerService( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2401): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2401): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2401): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2401): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system),
E/DropBoxManagerService( 2401): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2401): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2401): 	... 5 more,
I/SELinux ( 8851): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8851):  
,I/Process ( 8837): Sending signal. PID: 8837 SIG: 9,
,E/Icing   ( 3155): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system),
,E/SharedPreferencesImpl( 3155): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml.bak,
,I/ActivityManager( 2401): Process com.samsung.android.provider.shootingmodeprovider (pid 8837) (adj 0) has died.,
,D/dalvikvm( 1921): GC_EXPLICIT freed 44K, 12% free 9508K/10688K, paused 3ms+5ms, total 37ms,
,E/Icing   ( 3155): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system),
I/SELinux ( 8851): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8851):  
I/SELinux ( 8851):  
,I/SELinux ( 8851): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 8851): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 8851): >>>>> Normal User
,E/dalvikvm( 8851): >>>>> com.n7mobile.promenadaplusa [ userId:0 | appId:10183 ],
,E/SELinux ( 8851): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,E/SQLiteDatabase( 8790): Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db'.,
E/SQLiteDatabase( 8790): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8790): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8790): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8790): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8790): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8790): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8790): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
,E/SQLiteDatabase( 8790): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8790): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8790): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8790): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8790): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8790): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8790): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.getWritableDatabase(InternalIcingCorporaProvider.java:500)
E/SQLiteDatabase( 8790): 	at com.google.android.gms.appdatasearch.util.AppDataSearchDbOpenHelperBase.cleanSequenceTable(AppDataSearchDbOpenHelperBase.java:348)
E/SQLiteDatabase( 8790): 	,at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.requestIndexingIfRequired(AppDataSearchProviderBase.java:321)
E/SQLiteDatabase( 8790): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:165)
E/SQLiteDatabase( 8790): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:156)
E/SQLiteDatabase( 8790): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.executeWithConnection(AppDataSearchProviderBase.java:295)
E/SQLiteDatabase( 8790): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider.registerCorpora(AppDataSearchProvider.java:171)
E/SQLiteDatabase( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.safeRegisterCorpora(InternalIcingCorporaProvider.java:376)
E/SQLiteDatabase( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.registerCorpora(InternalIcingCorporaProvider.java:330)
E/SQLiteDatabase( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:273)
E/SQLiteDatabase( 8790): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/SQLiteDatabase( 8790): 	,at android.content.ContentResolver.update(ContentResolver.java:1327)
E/SQLiteDatabase( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/SQLiteDatabase( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/SQLiteDatabase( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/SQLiteDatabase( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/SQLiteDatabase( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/SQLiteDatabase( 8790): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 8790): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8790): 	,at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8790): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9508K/10688K, paused 3ms+4ms, total 31ms,
E/Icing.InternalIcingCorporaProvider( 8790): Exception thrown from registerCorpora
,E/Icing.InternalIcingCorporaProvider( 8790): java.lang.RuntimeException: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/Icing.InternalIcingCorporaProvider( 8790): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.executeWithConnection(AppDataSearchProviderBase.java:297)
E/Icing.InternalIcingCorporaProvider( 8790): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider.registerCorpora(AppDataSearchProvider.java:171)
E/Icing.InternalIcingCorporaProvider( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.safeRegisterCorpora(InternalIcingCorporaProvider.java:376)
E/Icing.InternalIcingCorporaProvider( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.registerCorpora(InternalIcingCorporaProvider.java:330)
E/Icing.InternalIcingCorporaProvider( 8790): ,	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:273)
E/Icing.InternalIcingCorporaProvider( 8790): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/Icing.InternalIcingCorporaProvider( 8790): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/Icing.InternalIcingCorporaProvider( 8790): ,	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/Icing.InternalIcingCorporaProvider( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/Icing.InternalIcingCorporaProvider( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/Icing.InternalIcingCorporaProvider( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/Icing.InternalIcingCorporaProvider( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/Icing.InternalIcingCorporaProvider( 8790): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Icing.InternalIcingCorporaProvider( 8790): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Icing.InternalIcingCorporaProvider( 8790): 	at android.os.Looper.loop(Looper.java:146)
E/Icing.InternalIcingCorporaProvider( 8790): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/Icing.InternalIcingCorporaProvider( 8790): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/Icing.InternalIcingCorporaProvider( 8790): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/Icing.InternalIcingCorporaProvider( 8790): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/Icing.InternalIcingCorporaProvider( 8790): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/Icing.InternalIcingCorporaProvider( 8790): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/Icing.InternalIcingCorporaProvider( 8790): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/Icing.InternalIcingCorporaProvider( 8790): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/Icing.InternalIcingCorporaProvider( 8790): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/Icing.InternalIcingCorporaProvider( 8790): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/Icing.InternalIcingCorporaProvider( 8790): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/Icing.InternalIcingCorporaProvider( 8790): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/Icing.InternalIcingCorporaProvider( 8790): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/Icing.InternalIcingCorporaProvider( 8790): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/Icing.InternalIcingCorporaProvider( 8790): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/Icing.InternalIcingCorporaProvider( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.getWritableDatabase(InternalIcingCorporaProvider.java:500)
E/Icing.InternalIcingCorporaProvider( 8790): 	at com.google.android.gms.appdatasearch.util.AppDataSearchDbOpenHelperBase.cleanSequenceTable(AppDataSearchDbOpenHelperBase.java:348)
E/Icing.InternalIcingCorporaProvider( 8790): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.requestIndexingIfRequired(AppDataSearchProviderBase.java:321)
E/Icing.InternalIcingCorporaProvider( 8790): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:165)
E/Icing.InternalIcingCorporaProvider( 8790): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProvider$2.call(AppDataSearchProvider.java:156)
E/Icing.InternalIcingCorporaProvid,er( 8790): 	at com.google.android.gms.appdatasearch.util.AppDataSearchProviderBase.executeWithConnection(AppDataSearchProviderBase.java:295)
E/Icing.InternalIcingCorporaProvider( 8790): 	... 15 more
W/Icing.InternalIcingCorporaProvider( 8790): Corpora registration failed
D/TimaKeyStoreProvider( 8851): in addTimaSignatureService
E/SQLiteDatabase( 8790): Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db'.
E/SQLiteDatabase( 8790): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8790): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8790): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8790): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8790): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8790): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8790): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8790): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8790): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8790): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8790): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8790): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8790): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8790): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.getWritableDatabase(InternalIcingCorporaProvider.java:500)
E/SQLiteDatabase( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:281)
E/SQLiteDatabase( 8790): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/SQLiteDatabase( 8790): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/SQLiteDatabase( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/SQLiteDatabase( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/SQLiteDatabase( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/SQLiteDatabase( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/SQLiteDatabase( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/SQLiteDatabase( 8790): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 8790): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8790): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8790): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 8790): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
D/TimaKeyStoreProvider( 8851): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 8851): Added TimaKesytore provider
E/AndroidRuntime( 8790): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 879,0): Process: com.google.android.googlequicksearchbox:search, PID: 8790
E/AndroidRuntime( 8790): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8790): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8790): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 8790): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 8790): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 8790): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 8790): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8790): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 8790): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 8790): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 8790): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 8790): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 8790): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 8790): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.getWritableDatabase(InternalIcingCorporaProvider.java:500)
E/AndroidRuntime( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:281)
E/AndroidRuntime( 8790): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 8790): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AndroidRuntime( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AndroidRuntime( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AndroidRuntime( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AndroidRuntime( 8790): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AndroidRuntime( 8790): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 8790): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8790): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 8790): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9508K/10688K, paused 3ms+3ms, total 31ms
I/Process ( 8790): Sending signal. PID: 8790 SIG: 9
E/DropBoxManagerService( 2401): Can't write: system_app_crash
E/DropBoxManagerService( 2401): java.io.FileNotFoundException: /data/system/dropbox/drop234.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2401): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2401): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2401): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2401): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2401): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2401): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2401): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2401): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2401): 	... 5 more
I/ActivityManager( 2401): Process com.google.android.googlequicksearchbox:search (pid 8790) (adj 5) has died.
W/ActivityManager( 2401): Service crashed 2 times, stopping: ServiceRecord{430ae8a0 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService}
,D/dalvikvm( 8851): GC_CONCURRENT freed 3006K, 31% free 9571K/13716K, paused 2ms+2ms, total 24ms
D/dalvikvm( 8851): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/ApplicationPromenada( 8851): Application OnCreate start
,D/ApplicationPromenada( 8851): Application OnCreate po on Create
D/CrashReporter( 8851): Initing Crashreporter: com.n7mobile.promenada2.ApplicationPromenada@42272860
D/CrashReporter( 8851): Swaping uncaught exception handler,
D/ApplicationPromenada( 8851): Application OnCreate App Loader start
,D/ApplicationPromenada( 8851): Application OnCreate App Loader finish

```
