#### Test 54970261c23922d_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/main
D/GalaxyFinderApplication( 6296): [Slink platform] Version = 29011
D/GalaxyFinderApplication( 6296): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux ( 6312): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6312):  
--------- beginning of /dev/log/system
I/ActivityManager( 2404): Killing 5086:com.sec.android.app.camera/u0a149 (adj 15): empty #43
D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 12% free 9504K/10724K, paused 3ms+3ms, total 35ms
I/SELinux ( 6312): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6312):  
I/SELinux ( 6312):  
I/SELinux ( 6312): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6312): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6312): >>>>> Normal User
E/dalvikvm( 6312): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
E/SELinux ( 6312): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9504K/10724K, paused 2ms+2ms, total 24ms
D/TimaKeyStoreProvider( 6312): in addTimaSignatureService
D/TimaKeyStoreProvider( 6312): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6312): Added TimaKesytore provider
D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9504K/10724K, paused 2ms+3ms, total 24ms
D/dalvikvm( 6312): GC_CONCURRENT freed 2999K, 31% free 9576K/13748K, paused 3ms+1ms, total 23ms
D/dalvikvm( 6312): WAIT_FOR_CONCURRENT_GC blocked 18ms
W/ContextImpl( 6312): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
I/SELinux ( 6332): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6332):  
E/Device Type Shared Preferences( 6312): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences( 6312): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication( 6312): ContentProvider is not null
W/ResourceType( 6312): No package identifier when getting value for resource number 0x00000000
I/System.out( 6312): resource Id::2131361807
I/SELinux ( 6332): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6332):  
I/SELinux ( 6332):  
I/SELinux ( 6332): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6332): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6332): >>>>> Normal User
E/dalvikvm( 6332): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 6332): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 6332): in addTimaSignatureService
D/TimaKeyStoreProvider( 6332): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6332): Added TimaKesytore provider
D/com.sec.android.app.shealth.SHealthApplication( 6312): Success during batch insertion in App registry:0
D/dalvikvm( 6332): GC_CONCURRENT freed 2990K, 31% free 9580K/13744K, paused 3ms+1ms, total 31ms
D/dalvikvm( 6332): WAIT_FOR_CONCURRENT_GC blocked 15ms
V/MediaPlayer( 6312): decode(56, 30565892, 48105)
V/MediaPlayerService( 1926): decode(26, 30565892, 48105)
V/MediaPlayerService( 1926): player type = 3
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): constructor
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): StagefrightPlayer
V/AwesomePlayer( 1926): setListener
V/StagefrightPlayer( 1926): initCheck
V/AwesomePlayer( 1926): setAudioSink
V/StagefrightPlayer( 1926): setDataSource(26, 30565892, 48105)
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x445efd48, 8, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/AwesomePlayer( 1926): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1926): mBitrate = -1 bits/sec
V/AwesomePlayer( 1926): current audio track index (0) is added to vector
V/AwesomePlayer( 1926): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1926): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1926): prepare
V/AwesomePlayer( 1926): prepareAsync
V/MediaPlayerService( 1926): wait for prepare
V/AwesomePlayer( 1926): onPrepareAsyncEvent
I/SecMediaClock( 1926): SecMediaClock constructor
I/SecMediaClock( 1926): reset
V/AwesomePlayer( 1926): initAudioDecoder
V/AwesomePlayer( 1926): checkOffloadExceptions is true
I/OMXCodec( 1926): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1926): mDispatchers.add
I/OMXCodec( 1926): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1926): finishAsyncPrepare_l
V/AwesomePlayer( 1926): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1926): notify(0x445efd48, 200, 973, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x445efd48, 5, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x445efd48, 1, 0, 0)
V/AudioCache( 1926): prepared
V/AudioCache( 1926): wait - success
V/MediaPlayerService( 1926): start
V/StagefrightPlayer( 1926): start
V/AwesomePlayer( 1926): play
V/AwesomePlayer( 1926): AwesomePlayer::play_l():: This is not a DRM content
,V/AwesomePlayer( 1926): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1926): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1926): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x445efd48, 6, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): addBatteryData
V/MediaPlayerService( 1926): wait for playback complete
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1926): postAudioEOS delayUs (0)
V/AwesomePlayer( 1926): onCheckAudioStatus
V/AwesomePlayer( 1926): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1926): onStreamDone
V/AwesomePlayer( 1926): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1926): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x445efd48, 2, 0, 0)
V/AudioCache( 1926): playback complete - thread will wake up later
V/AwesomePlayer( 1926): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x445efd48, 7, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1926): addBatteryData
V/AudioCache( 1926): wait - success
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x445efd48, 8, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop() sendCommand(0x36, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1926): reset out
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1926): SecMediaClock destructor
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): ~StagefrightPlayer
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/AwesomePlayer( 1926): destructor
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/MediaPlayer( 6312): decode(58, 30501792, 10421)
V/MediaPlayerService( 1926): decode(26, 30501792, 10421)
V/MediaPlayerService( 1926): player type = 3
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): constructor
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): StagefrightPlayer
V/AwesomePlayer( 1926): setListener
V/StagefrightPlayer( 1926): initCheck
V/AwesomePlayer( 1926): setAudioSink
V/StagefrightPlayer( 1926): setDataSource(26, 30501792, 10421)
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x445f27b0, 8, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/AwesomePlayer( 1926): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1926): mBitrate = -1 bits/sec
V/AwesomePlayer( 1926): current audio track index (0) is added to vector
V/AwesomePlayer( 1926): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1926): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1926): prepare
V/AwesomePlayer( 1926): prepareAsync
V/MediaPlayerService( 1926): wait for prepare
V/AwesomePlayer( 1926): onPrepareAsyncEvent
I/SecMediaClock( 1926): SecMediaClock constructor
I/SecMediaClock( 1926): reset
V/AwesomePlayer( 1926): initAudioDecoder
V/AwesomePlayer( 1926): checkOffloadExceptions is true
I/OMXCodec( 1926): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1926): mDispatchers.add
I/OMXCodec( 1926): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1926): finishAsyncPrepare_l
V/AwesomePlayer( 1926): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1926): notify(0x445f27b0, 200, 973, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x445f27b0, 5, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x445f27b0, 1, 0, 0)
V/AudioCache( 1926): prepared
V/AudioCache( 1926): wait - success
V/MediaPlayerService( 1926): start
V/StagefrightPlayer( 1926): start
V/AwesomePlayer( 1926): play
V/AwesomePlayer( 1926): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1926): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1926): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1926): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x445f27b0, 6, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): addBatteryData
V/MediaPlayerService( 1926): wait for playback complete
I/AudioPlayer( 1926): First fillBuffer call!!
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1926): postAudioEOS delayUs (0)
V/AwesomePlayer( 1926): onCheckAudioStatus
V/AwesomePlayer( 1926): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1926): onStreamDone
V/AwesomePlayer( 1926): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1926): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x445f27b0, 2, 0, 0)
V/AudioCache( 1926): playback complete - thread will wake up later
V/AwesomePlayer( 1926): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x445f27b0, 7, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1926): addBatteryData
V/AudioCache( 1926): wait - success
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x445f27b0, 8, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop() sendCommand(0x37, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1926): reset out
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1926): SecMediaClock destructor
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): ~StagefrightPlayer
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/AwesomePlayer( 1926): destructor
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/MediaPlayer( 6312): decode(59, 34044116, 34198)
V/MediaPlayerService( 1926): decode(26, 34044116, 34198)
V/MediaPlayerService( 1926): player type = 3
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): constructor
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): StagefrightPlayer
V/AwesomePlayer( 1926): setListener
V/StagefrightPlayer( 1926): initCheck
V/AwesomePlayer( 1926): setAudioSink
V/StagefrightPlayer( 1926): setDataSource(26, 34044116, 34198)
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442b0a38, 8, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/AwesomePlayer( 1926): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1926): mBitrate = -1 bits/sec
V/AwesomePlayer( 1926): current audio track index (0) is added to vector
V/AwesomePlayer( 1926): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1926): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1926): prepare
V/AwesomePlayer( 1926): prepareAsync
V/MediaPlayerService( 1926): wait for prepare
V/AwesomePlayer( 1926): onPrepareAsyncEvent
I/SecMediaClock( 1926): SecMediaClock constructor
I/SecMediaClock( 1926): reset
V/AwesomePlayer( 1926): initAudioDecoder
V/AwesomePlayer( 1926): checkOffloadExceptions is true
I/OMXCodec( 1926): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1926): mDispatchers.add
I/OMXCodec( 1926): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1926): finishAsyncPrepare_l
V/AwesomePlayer( 1926): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1926): notify(0x442b0a38, 200, 973, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442b0a38, 5, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442b0a38, 1, 0, 0)
V/AudioCache( 1926): prepared
V/AudioCache( 1926): wait - success
V/MediaPlayerService( 1926): start
V/StagefrightPlayer( 1926): start
V/AwesomePlayer( 1926): play
V/AwesomePlayer( 1926): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1926): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1926): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1926): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442b0a38, 6, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): addBatteryData
V/MediaPlayerService( 1926): wait for playback complete
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1926): postAudioEOS delayUs (0)
V/AwesomePlayer( 1926): onCheckAudioStatus
V/AwesomePlayer( 1926): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1926): onStreamDone
V/AwesomePlayer( 1926): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1926): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442b0a38, 2, 0, 0)
V/AudioCache( 1926): playback complete - thread will wake up later
V/AwesomePlayer( 1926): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442b0a38, 7, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1926): addBatteryData
V/AudioCache( 1926): wait - success
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442b0a38, 8, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop() sendCommand(0x38, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1926): reset out
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1926): SecMediaClock destructor
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): ~StagefrightPlayer
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/AwesomePlayer( 1926): destructor
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/MediaPlayer( 6312): decode(60, 30449260, 7405)
V/MediaPlayerService( 1926): decode(26, 30449260, 7405)
V/MediaPlayerService( 1926): player type = 3
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): constructor
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): StagefrightPlayer
V/AwesomePlayer( 1926): setListener
V/StagefrightPlayer( 1926): initCheck
V/AwesomePlayer( 1926): setAudioSink
V/StagefrightPlayer( 1926): setDataSource(26, 30449260, 7405)
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442bd8d8, 8, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/AwesomePlayer( 1926): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1926): mBitrate = -1 bits/sec
V/AwesomePlayer( 1926): current audio track index (0) is added to vector
V/AwesomePlayer( 1926): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1926): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1926): prepare
V/AwesomePlayer( 1926): prepareAsync
V/MediaPlayerService( 1926): wait for prepare
V/AwesomePlayer( 1926): onPrepareAsyncEvent
I/SecMediaClock( 1926): SecMediaClock constructor
I/SecMediaClock( 1926): reset
V/AwesomePlayer( 1926): initAudioDecoder
V/AwesomePlayer( 1926): checkOffloadExceptions is true
I/OMXCodec( 1926): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1926): mDispatchers.add
I/OMXCodec( 1926): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1926): finishAsyncPrepare_l
V/AwesomePlayer( 1926): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1926): notify(0x442bd8d8, 200, 973, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442bd8d8, 5, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442bd8d8, 1, 0, 0)
V/AudioCache( 1926): prepared
V/AudioCache( 1926): wait - success
V/MediaPlayerService( 1926): start
V/StagefrightPlayer( 1926): start
V/AwesomePlayer( 1926): play
V/AwesomePlayer( 1926): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1926): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1926): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1926): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442bd8d8, 6, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): addBatteryData
V/MediaPlayerService( 1926): wait for playback complete
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1926): postAudioEOS delayUs (0)
V/AwesomePlayer( 1926): onCheckAudioStatus
V/AwesomePlayer( 1926): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1926): onStreamDone
V/AwesomePlayer( 1926): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1926): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442bd8d8, 2, 0, 0)
V/AudioCache( 1926): playback complete - thread will wake up later
V/AwesomePlayer( 1926): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442bd8d8, 7, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=1)
V/AudioCache( 1926): wait - success
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): addBatteryData
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442bd8d8, 8, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop() sendCommand(0x39, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1926): reset out
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1926): SecMediaClock destructor
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): ~StagefrightPlayer
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/AwesomePlayer( 1926): destructor
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/MediaPlayer( 6312): decode(61, 34134748, 5555)
V/MediaPlayerService( 1926): decode(26, 34134748, 5555)
V/MediaPlayerService( 1926): player type = 3
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): constructor
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): StagefrightPlayer
V/AwesomePlayer( 1926): setListener
V/StagefrightPlayer( 1926): initCheck
V/AwesomePlayer( 1926): setAudioSink
V/StagefrightPlayer( 1926): setDataSource(26, 34134748, 5555)
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442c0538, 8, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/AwesomePlayer( 1926): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1926): mBitrate = -1 bits/sec
V/AwesomePlayer( 1926): current audio track index (0) is added to vector
V/AwesomePlayer( 1926): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1926): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1926): prepare
V/AwesomePlayer( 1926): prepareAsync
V/MediaPlayerService( 1926): wait for prepare
V/AwesomePlayer( 1926): onPrepareAsyncEvent
I/SecMediaClock( 1926): SecMediaClock constructor
I/SecMediaClock( 1926): reset
V/AwesomePlayer( 1926): initAudioDecoder
V/AwesomePlayer( 1926): checkOffloadExceptions is true
I/OMXCodec( 1926): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1926): mDispatchers.add
I/OMXCodec( 1926): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1926): finishAsyncPrepare_l
V/AwesomePlayer( 1926): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1926): notify(0x442c0538, 200, 973, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442c0538, 5, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442c0538, 1, 0, 0)
V/AudioCache( 1926): prepared
V/AudioCache( 1926): wait - success
V/MediaPlayerService( 1926): start
V/StagefrightPlayer( 1926): start
V/AwesomePlayer( 1926): play
V/AwesomePlayer( 1926): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1926): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1926): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1926): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442c0538, 6, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): addBatteryData
V/MediaPlayerService( 1926): wait for playback complete
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1926): postAudioEOS delayUs (0)
V/AwesomePlayer( 1926): onCheckAudioStatus
V/AwesomePlayer( 1926): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1926): onStreamDone
V/AwesomePlayer( 1926): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1926): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442c0538, 2, 0, 0)
V/AudioCache( 1926): playback complete - thread will wake up later
V/AwesomePlayer( 1926): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442c0538, 7, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1926): addBatteryData
V/AudioCache( 1926): wait - success
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442c0538, 8, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop() sendCommand(0x3a, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1926): reset out
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1926): SecMediaClock destructor
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): ~StagefrightPlayer
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/AwesomePlayer( 1926): destructor
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/MediaPlayer( 6312): decode(62, 26954540, 5085)
V/MediaPlayerService( 1926): decode(27, 26954540, 5085)
V/MediaPlayerService( 1926): player type = 3
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): constructor
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): StagefrightPlayer
V/AwesomePlayer( 1926): setListener
V/StagefrightPlayer( 1926): initCheck
V/AwesomePlayer( 1926): setAudioSink
V/StagefrightPlayer( 1926): setDataSource(27, 26954540, 5085)
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x43f41720, 8, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/AwesomePlayer( 1926): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1926): mBitrate = -1 bits/sec
V/AwesomePlayer( 1926): current audio track index (0) is added to vector
V/AwesomePlayer( 1926): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1926): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1926): prepare
V/AwesomePlayer( 1926): prepareAsync
V/MediaPlayerService( 1926): wait for prepare
V/AwesomePlayer( 1926): onPrepareAsyncEvent
I/SecMediaClock( 1926): SecMediaClock constructor
I/SecMediaClock( 1926): reset
V/AwesomePlayer( 1926): initAudioDecoder
V/AwesomePlayer( 1926): checkOffloadExceptions is true
I/OMXCodec( 1926): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1926): mDispatchers.add
I/OMXCodec( 1926): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1926): finishAsyncPrepare_l
V/AwesomePlayer( 1926): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1926): notify(0x43f41720, 200, 973, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x43f41720, 5, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x43f41720, 1, 0, 0)
V/AudioCache( 1926): prepared
V/AudioCache( 1926): wait - success
V/MediaPlayerService( 1926): start
V/StagefrightPlayer( 1926): start
V/AwesomePlayer( 1926): play
V/AwesomePlayer( 1926): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1926): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1926): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1926): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x43f41720, 6, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): addBatteryData
V/MediaPlayerService( 1926): wait for playback complete
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1926): postAudioEOS delayUs (0)
V/AwesomePlayer( 1926): onCheckAudioStatus
V/AwesomePlayer( 1926): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1926): onStreamDone
V/AwesomePlayer( 1926): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1926): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x43f41720, 2, 0, 0)
V/AudioCache( 1926): playback complete - thread will wake up later
V/AwesomePlayer( 1926): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x43f41720, 7, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=1)
V/AudioCache( 1926): wait - success
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): addBatteryData
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x43f41720, 8, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop() sendCommand(0x3b, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1926): reset out
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1926): SecMediaClock destructor
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): ~StagefrightPlayer
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/AwesomePlayer( 1926): destructor
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/MediaPlayer( 6312): decode(63, 26959684, 21552)
V/MediaPlayerService( 1926): decode(27, 26959684, 21552)
V/MediaPlayerService( 1926): player type = 3
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): constructor
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): StagefrightPlayer
V/AwesomePlayer( 1926): setListener
V/StagefrightPlayer( 1926): initCheck
V/AwesomePlayer( 1926): setAudioSink
V/StagefrightPlayer( 1926): setDataSource(27, 26959684, 21552)
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442b2ca0, 8, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/AwesomePlayer( 1926): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1926): mBitrate = -1 bits/sec
V/AwesomePlayer( 1926): current audio track index (0) is added to vector
V/AwesomePlayer( 1926): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1926): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1926): prepare
V/AwesomePlayer( 1926): prepareAsync
V/MediaPlayerService( 1926): wait for prepare
V/AwesomePlayer( 1926): onPrepareAsyncEvent
I/SecMediaClock( 1926): SecMediaClock constructor
I/SecMediaClock( 1926): reset
V/AwesomePlayer( 1926): initAudioDecoder
V/AwesomePlayer( 1926): checkOffloadExceptions is true
I/OMXCodec( 1926): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1926): mDispatchers.add
I/OMXCodec( 1926): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1926): finishAsyncPrepare_l
V/AwesomePlayer( 1926): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1926): notify(0x442b2ca0, 200, 973, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442b2ca0, 5, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442b2ca0, 1, 0, 0)
V/AudioCache( 1926): prepared
V/AudioCache( 1926): wait - success
V/MediaPlayerService( 1926): start
V/StagefrightPlayer( 1926): start
V/AwesomePlayer( 1926): play
V/AwesomePlayer( 1926): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1926): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1926): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1926): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442b2ca0, 6, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): addBatteryData
V/MediaPlayerService( 1926): wait for playback complete
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1926): postAudioEOS delayUs (0)
V/AwesomePlayer( 1926): onCheckAudioStatus
V/AwesomePlayer( 1926): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1926): onStreamDone
V/AwesomePlayer( 1926): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1926): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442b2ca0, 2, 0, 0)
V/AudioCache( 1926): playback complete - thread will wake up later
V/AwesomePlayer( 1926): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442b2ca0, 7, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1926): addBatteryData
V/AudioCache( 1926): wait - success
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442b2ca0, 8, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop() sendCommand(0x3c, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1926): reset out
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1926): SecMediaClock destructor
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): ~StagefrightPlayer
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/AwesomePlayer( 1926): destructor
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/MediaPlayer( 6312): decode(64, 34130460, 4230)
V/MediaPlayerService( 1926): decode(26, 34130460, 4230)
V/MediaPlayerService( 1926): player type = 3
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): constructor
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): StagefrightPlayer
V/AwesomePlayer( 1926): setListener
V/StagefrightPlayer( 1926): initCheck
V/AwesomePlayer( 1926): setAudioSink
V/StagefrightPlayer( 1926): setDataSource(26, 34130460, 4230)
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442bea50, 8, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/AwesomePlayer( 1926): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1926): mBitrate = -1 bits/sec
V/AwesomePlayer( 1926): current audio track index (0) is added to vector
V/AwesomePlayer( 1926): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1926): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1926): prepare
V/AwesomePlayer( 1926): prepareAsync
V/MediaPlayerService( 1926): wait for prepare
V/AwesomePlayer( 1926): onPrepareAsyncEvent
I/SecMediaClock( 1926): SecMediaClock constructor
I/SecMediaClock( 1926): reset
V/AwesomePlayer( 1926): initAudioDecoder
V/AwesomePlayer( 1926): checkOffloadExceptions is true
I/OMXCodec( 1926): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1926): mDispatchers.add
I/OMXCodec( 1926): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1926): finishAsyncPrepare_l
V/AwesomePlayer( 1926): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1926): notify(0x442bea50, 200, 973, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442bea50, 5, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442bea50, 1, 0, 0)
V/AudioCache( 1926): prepared
V/AudioCache( 1926): wait - success
V/MediaPlayerService( 1926): start
V/StagefrightPlayer( 1926): start
V/AwesomePlayer( 1926): play
V/AwesomePlayer( 1926): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1926): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] End Of Stream
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 1926): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer( 1926): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442bea50, 6, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): addBatteryData
V/AwesomePlayer( 1926): postAudioEOS delayUs (0)
V/MediaPlayerService( 1926): wait for playback complete
V/AwesomePlayer( 1926): onCheckAudioStatus
V/AwesomePlayer( 1926): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1926): onStreamDone
V/AwesomePlayer( 1926): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1926): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442bea50, 2, 0, 0)
V/AudioCache( 1926): playback complete - thread will wake up later
V/AwesomePlayer( 1926): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442bea50, 7, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=1)
V/AudioCache( 1926): wait - success
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): addBatteryData
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442bea50, 8, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop() sendCommand(0x3d, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1926): reset out
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1926): SecMediaClock destructor
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): ~StagefrightPlayer
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/AwesomePlayer( 1926): destructor
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/MediaPlayer( 6312): decode(65, 26923896, 9400)
V/MediaPlayerService( 1926): decode(27, 26923896, 9400)
V/MediaPlayerService( 1926): player type = 3
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): constructor
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): StagefrightPlayer
V/AwesomePlayer( 1926): setListener
V/StagefrightPlayer( 1926): initCheck
V/AwesomePlayer( 1926): setAudioSink
V/StagefrightPlayer( 1926): setDataSource(27, 26923896, 9400)
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442b0088, 8, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/AwesomePlayer( 1926): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1926): mBitrate = -1 bits/sec
V/AwesomePlayer( 1926): current audio track index (0) is added to vector
V/AwesomePlayer( 1926): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1926): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1926): prepare
V/AwesomePlayer( 1926): prepareAsync
V/MediaPlayerService( 1926): wait for prepare
V/AwesomePlayer( 1926): onPrepareAsyncEvent
I/SecMediaClock( 1926): SecMediaClock constructor
I/SecMediaClock( 1926): reset
V/AwesomePlayer( 1926): initAudioDecoder
V/AwesomePlayer( 1926): checkOffloadExceptions is true
I/OMXCodec( 1926): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1926): mDispatchers.add
I/OMXCodec( 1926): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1926): finishAsyncPrepare_l
V/AwesomePlayer( 1926): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1926): notify(0x442b0088, 200, 973, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442b0088, 5, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442b0088, 1, 0, 0)
V/AudioCache( 1926): prepared
V/AudioCache( 1926): wait - success
V/MediaPlayerService( 1926): start
V/StagefrightPlayer( 1926): start
V/AwesomePlayer( 1926): play
V/AwesomePlayer( 1926): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1926): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat:1, 1, 0
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat read fail(1, 1)
V/AudioCache( 1926): open(44100, 1, 0x0, 1, 4)
V/AwesomePlayer( 1926): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442b0088, 6, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): addBatteryData
V/MediaPlayerService( 1926): wait for playback complete
I/SELinux ( 6393): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6393):  
I/ActivityManager( 2404): Killing 5150:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty #43
I/ActivityManager( 2404): Killing 5155:com.android.email/u0a157 (adj 15): empty #44
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] End Of Stream
D/AndroidRuntime( 6363): 
D/AndroidRuntime( 6363): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
V/AwesomePlayer( 1926): postAudioEOS delayUs (0)
V/AwesomePlayer( 1926): onCheckAudioStatus
V/AwesomePlayer( 1926): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1926): onStreamDone
V/AwesomePlayer( 1926): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1926): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
D/AndroidRuntime( 6363): CheckJNI is OFF
V/AudioCache( 1926): notify(0x442b0088, 2, 0, 0)
V/AudioCache( 1926): playback complete - thread will wake up later
V/AwesomePlayer( 1926): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442b0088, 7, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=1)
I/SELinux ( 6393): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6393):  
I/SELinux ( 6393):  
I/SELinux ( 6393): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
V/AwesomePlayer( 1926): addBatteryData
V/AudioCache( 1926): wait - success
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): reset_l()
D/AndroidRuntime( 6363): setted country_code = Poland
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442b0088, 8, 0, 0)
V/AudioCache( 1926): ignored
E/SELinux ( 6393): [DEBUG] seapp_context_lookup: seinfoCategory = platform
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop() sendCommand(0x3e, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
E/dalvikvm( 6393): >>>>> Normal User
E/dalvikvm( 6393): >>>>> com.policydm [ userId:0 | appId:1000 ]
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
D/AndroidRuntime( 6363): setted countryiso_code = PL
D/AndroidRuntime( 6363): setted sales_code = PLS
D/AndroidRuntime( 6363): readGMSProperty: start
D/AndroidRuntime( 6363): readGMSProperty: already setted!!
D/AndroidRuntime( 6363): readGMSProperty: end
D/AndroidRuntime( 6363): addProductProperty: start
E/SELinux ( 6393): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/AudioPlayer( 1926): reset out
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1926): SecMediaClock destructor
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): ~StagefrightPlayer
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/AwesomePlayer( 1926): destructor
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/MediaPlayer( 6312): decode(66, 30512272, 44276)
V/MediaPlayerService( 1926): decode(26, 30512272, 44276)
V/MediaPlayerService( 1926): player type = 3
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): constructor
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): StagefrightPlayer
V/AwesomePlayer( 1926): setListener
V/StagefrightPlayer( 1926): initCheck
V/AwesomePlayer( 1926): setAudioSink
V/StagefrightPlayer( 1926): setDataSource(26, 30512272, 44276)
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x44188408, 8, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
D/dalvikvm( 6332): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x42273e10, skipping init
V/AwesomePlayer( 1926): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1926): mBitrate = -1 bits/sec
V/AwesomePlayer( 1926): current audio track index (0) is added to vector
V/AwesomePlayer( 1926): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1926): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1926): prepare
V/AwesomePlayer( 1926): prepareAsync
V/MediaPlayerService( 1926): wait for prepare
I/SecureStorage( 6332): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
I/SecureStorage( 6332): [INFO]: SPID(0x00000000)This device supports Secure Storage
V/AwesomePlayer( 1926): onPrepareAsyncEvent
I/SecureStorage( 1965): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 6332
I/SecureStorage( 1965): [INFO]: SPID(0x00000003)Received function mask & code: 0000010C
I/SecureStorage( 6332): [INFO]: SPID(0x00000000)SS Daemon is running
I/SecMediaClock( 1926): SecMediaClock constructor
I/SecMediaClock( 1926): reset
V/AwesomePlayer( 1926): initAudioDecoder
V/AwesomePlayer( 1926): checkOffloadExceptions is true
I/OMXCodec( 1926): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/dalvikvm( 6363): Trying to load lib libjavacore.so 0x0
I/OMX     ( 1926): mDispatchers.add
I/OMXCodec( 1926): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
D/dalvikvm( 6363): Added shared lib libjavacore.so 0x0
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1926): finishAsyncPrepare_l
V/AwesomePlayer( 1926): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1926): notify(0x44188408, 200, 973, 0)
V/AudioCache( 1926): ignored
D/dalvikvm( 6363): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6363): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6363): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
V/AwesomePlayer( 1926): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x44188408, 5, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x44188408, 1, 0, 0)
V/AudioCache( 1926): prepared
V/AudioCache( 1926): wait - success
V/MediaPlayerService( 1926): start
V/StagefrightPlayer( 1926): start
V/AwesomePlayer( 1926): play
V/AwesomePlayer( 1926): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1926): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1926): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1926): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x44188408, 6, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): addBatteryData
V/MediaPlayerService( 1926): wait for playback complete
I/SecureStorage( 6332): [INFO]: SPID(0x00000000)Processing data
D/TimaKeyStoreProvider( 6393): in addTimaSignatureService
I/SecureStorage( 1965): [INFO]: SPID(0x00000003)Credentials: uid 10016, gid 10016, pid 6332
I/SecureStorage( 1965): [INFO]: SPID(0x00000003)Received function mask & code: 00000106
D/TimaKeyStoreProvider( 6393): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6393): Added TimaKesytore provider
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1926): postAudioEOS delayUs (0)
V/AwesomePlayer( 1926): onCheckAudioStatus
V/AwesomePlayer( 1926): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1926): onStreamDone
V/AwesomePlayer( 1926): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1926): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x44188408, 2, 0, 0)
V/AudioCache( 1926): playback complete - thread will wake up later
V/AwesomePlayer( 1926): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x44188408, 7, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1926): addBatteryData
V/AudioCache( 1926): wait - success
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x44188408, 8, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop() sendCommand(0x3f, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1926): reset out
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1926): SecMediaClock destructor
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): ~StagefrightPlayer
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/AwesomePlayer( 1926): destructor
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/MediaPlayer( 6312): decode(67, 30472480, 29256)
V/MediaPlayerService( 1926): decode(26, 30472480, 29256)
V/MediaPlayerService( 1926): player type = 3
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): constructor,
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): StagefrightPlayer
V/AwesomePlayer( 1926): setListener
V/StagefrightPlayer( 1926): initCheck
V/AwesomePlayer( 1926): setAudioSink
V/StagefrightPlayer( 1926): setDataSource(26, 30472480, 29256)
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x435174f8, 8, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/AwesomePlayer( 1926): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1926): mBitrate = -1 bits/sec
V/AwesomePlayer( 1926): current audio track index (0) is added to vector
V/AwesomePlayer( 1926): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1926): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1926): prepare
V/AwesomePlayer( 1926): prepareAsync
V/MediaPlayerService( 1926): wait for prepare
V/AwesomePlayer( 1926): onPrepareAsyncEvent
I/SecMediaClock( 1926): SecMediaClock constructor
I/SecMediaClock( 1926): reset
V/AwesomePlayer( 1926): initAudioDecoder
V/AwesomePlayer( 1926): checkOffloadExceptions is true
I/OMXCodec( 1926): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1926): mDispatchers.add
I/OMXCodec( 1926): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1926): finishAsyncPrepare_l
V/AwesomePlayer( 1926): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1926): notify(0x435174f8, 200, 973, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x435174f8, 5, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x435174f8, 1, 0, 0)
V/AudioCache( 1926): prepared
V/AudioCache( 1926): wait - success
V/MediaPlayerService( 1926): start
V/StagefrightPlayer( 1926): start
V/AwesomePlayer( 1926): play
V/AwesomePlayer( 1926): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1926): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1926): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1926): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x435174f8, 6, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): addBatteryData
V/MediaPlayerService( 1926): wait for playback complete
W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1926): postAudioEOS delayUs (0)
V/AwesomePlayer( 1926): onCheckAudioStatus
V/AwesomePlayer( 1926): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1926): onStreamDone
V/AwesomePlayer( 1926): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1926): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x435174f8, 2, 0, 0)
V/AudioCache( 1926): playback complete - thread will wake up later
V/AwesomePlayer( 1926): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x435174f8, 7, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1926): addBatteryData
V/AudioCache( 1926): wait - success
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x435174f8, 8, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop() sendCommand(0x40, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1926): reset out
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1926): SecMediaClock destructor
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): ~StagefrightPlayer
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/AwesomePlayer( 1926): destructor
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/MediaPlayer( 6312): decode(68, 34078380, 52024)
V/MediaPlayerService( 1926): decode(26, 34078380, 52024)
V/MediaPlayerService( 1926): player type = 3
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): constructor
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): StagefrightPlayer
V/AwesomePlayer( 1926): setListener
V/StagefrightPlayer( 1926): initCheck
V/AwesomePlayer( 1926): setAudioSink
V/StagefrightPlayer( 1926): setDataSource(26, 34078380, 52024)
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442b5990, 8, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/AwesomePlayer( 1926): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1926): mBitrate = -1 bits/sec
V/AwesomePlayer( 1926): current audio track index (0) is added to vector
V/AwesomePlayer( 1926): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1926): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1926): prepare
V/AwesomePlayer( 1926): prepareAsync
V/MediaPlayerService( 1926): wait for prepare
V/AwesomePlayer( 1926): onPrepareAsyncEvent
I/SecMediaClock( 1926): SecMediaClock constructor
I/SecMediaClock( 1926): reset
V/AwesomePlayer( 1926): initAudioDecoder
V/AwesomePlayer( 1926): checkOffloadExceptions is true
I/OMXCodec( 1926): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
E/memtrack( 6363): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6363): failed to load memtrack module: -2
I/OMX     ( 1926): mDispatchers.add
I/OMXCodec( 1926): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1926): finishAsyncPrepare_l
V/AwesomePlayer( 1926): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1926): notify(0x442b5990, 200, 973, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442b5990, 5, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442b5990, 1, 0, 0)
V/AudioCache( 1926): prepared
V/AudioCache( 1926): wait - success
V/MediaPlayerService( 1926): start
V/StagefrightPlayer( 1926): start
V/AwesomePlayer( 1926): play
V/AwesomePlayer( 1926): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1926): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1926): open(48000, 2, 0x0, 1, 4)
V/AwesomePlayer( 1926): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442b5990, 6, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): addBatteryData
V/MediaPlayerService( 1926): wait for playback complete
I/AudioPlayer( 1926): First fillBuffer call!!
D/dalvikvm( 6363): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1926): postAudioEOS delayUs (0)
V/AwesomePlayer( 1926): onCheckAudioStatus
V/AwesomePlayer( 1926): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1926): onStreamDone
V/AwesomePlayer( 1926): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1926): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442b5990, 2, 0, 0)
V/AudioCache( 1926): playback complete - thread will wake up later
V/AwesomePlayer( 1926): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442b5990, 7, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=1)
D/AndroidRuntime( 6363): Calling main entry com.android.commands.am.Am
V/AwesomePlayer( 1926): addBatteryData
V/AudioCache( 1926): wait - success
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442b5990, 8, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop() sendCommand(0x41, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1926): reset out
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1926): SecMediaClock destructor
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): ~StagefrightPlayer
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/AwesomePlayer( 1926): destructor
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/MediaPlayer( 6312): decode(69, 30556608, 9226)
V/MediaPlayerService( 1926): decode(26, 30556608, 9226)
V/MediaPlayerService( 1926): player type = 3
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): constructor
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): StagefrightPlayer
V/AwesomePlayer( 1926): setListener
V/StagefrightPlayer( 1926): initCheck
V/AwesomePlayer( 1926): setAudioSink
V/StagefrightPlayer( 1926): setDataSource(26, 30556608, 9226)
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442c0cb0, 8, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/AwesomePlayer( 1926): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1926): mBitrate = -1 bits/sec
V/AwesomePlayer( 1926): current audio track index (0) is added to vector
V/AwesomePlayer( 1926): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1926): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1926): prepare
V/AwesomePlayer( 1926): prepareAsync
V/MediaPlayerService( 1926): wait for prepare
V/AwesomePlayer( 1926): onPrepareAsyncEvent
I/SecMediaClock( 1926): SecMediaClock constructor
I/SecMediaClock( 1926): reset
V/AwesomePlayer( 1926): initAudioDecoder
V/AwesomePlayer( 1926): checkOffloadExceptions is true
I/OMXCodec( 1926): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1926): mDispatchers.add
I/OMXCodec( 1926): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1926): finishAsyncPrepare_l
V/AwesomePlayer( 1926): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1926): notify(0x442c0cb0, 200, 973, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442c0cb0, 5, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442c0cb0, 1, 0, 0)
V/AudioCache( 1926): prepared
V/AudioCache( 1926): wait - success
V/MediaPlayerService( 1926): start
V/StagefrightPlayer( 1926): start
V/AwesomePlayer( 1926): play
V/AwesomePlayer( 1926): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1926): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1926): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1926): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442c0cb0, 6, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): addBatteryData
V/MediaPlayerService( 1926): wait for playback complete
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] End Of Stream
V/AwesomePlayer( 1926): postAudioEOS delayUs (0)
V/AwesomePlayer( 1926): onCheckAudioStatus
V/AwesomePlayer( 1926): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1926): onStreamDone
V/AwesomePlayer( 1926): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1926): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442c0cb0, 2, 0, 0)
V/AudioCache( 1926): playback complete - thread will wake up later
V/AwesomePlayer( 1926): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442c0cb0, 7, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1926): addBatteryData
V/AudioCache( 1926): wait - success
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x442c0cb0, 8, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop() sendCommand(0x42, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1926): reset out
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1926): SecMediaClock destructor
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): ~StagefrightPlayer
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/AwesomePlayer( 1926): destructor
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/MediaPlayer( 6312): decode(70, 26989388, 4509)
V/MediaPlayerService( 1926): decode(26, 26989388, 4509)
V/MediaPlayerService( 1926): player type = 3
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): constructor
V/AwesomePlayer( 1926): setDefault
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): StagefrightPlayer
V/AwesomePlayer( 1926): setListener
V/StagefrightPlayer( 1926): initCheck
V/AwesomePlayer( 1926): setAudioSink
V/StagefrightPlayer( 1926): setDataSource(26, 26989388, 4509)
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x43f417e8, 8, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/AwesomePlayer( 1926): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer( 1926): mBitrate = -1 bits/sec
V/AwesomePlayer( 1926): current audio track index (0) is added to vector
V/AwesomePlayer( 1926): setDataSource_l: Audio(1), Video(0)
I/AwesomePlayer( 1926): AwesomePlayer::setDataSource_l():: This is not a DRM content
V/MediaPlayerService( 1926): prepare
V/AwesomePlayer( 1926): prepareAsync
V/MediaPlayerService( 1926): wait for prepare
V/AwesomePlayer( 1926): onPrepareAsyncEvent
I/SecMediaClock( 1926): SecMediaClock constructor
I/SecMediaClock( 1926): reset
V/AwesomePlayer( 1926): initAudioDecoder
V/AwesomePlayer( 1926): checkOffloadExceptions is true
I/OMXCodec( 1926): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
I/OMX     ( 1926): mDispatchers.add
I/OMXCodec( 1926): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] OMXCodec::start mState=1
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
V/AwesomePlayer( 1926): finishAsyncPrepare_l
V/AwesomePlayer( 1926): notifyListner_l() msg (200-MEDIA_INFO), ext1 (973), ext2 (0)
V/AudioCache( 1926): notify(0x43f417e8, 200, 973, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): notifyListner_l() msg (5-MEDIA_SET_VIDEO_SIZE), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x43f417e8, 5, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): notifyListner_l() msg (1-MEDIA_PREPARED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x43f417e8, 1, 0, 0)
V/AudioCache( 1926): prepared
V/AudioCache( 1926): wait - success
V/MediaPlayerService( 1926): start
V/StagefrightPlayer( 1926): start
V/AwesomePlayer( 1926): play
V/AwesomePlayer( 1926): AwesomePlayer::play_l():: This is not a DRM content
V/AwesomePlayer( 1926): startAudioPlayer_l, sendErrorNotification (0)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] End Of Stream
V/ApplicationPolicy( 2404): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] 0onCmdComplete  mState =  7
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat:1, 2, 0
I/AudioPlayer( 1926):  Audioplayer kKeyAudioPCMFormat read fail(2, 1)
V/AudioCache( 1926): open(44100, 2, 0x0, 1, 4)
V/AwesomePlayer( 1926): notifyListner_l() msg (6-MEDIA_STARTED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x43f417e8, 6, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): addBatteryData
V/MediaPlayerService( 1926): wait for playback complete
D/dalvikvm( 6393): GC_CONCURRENT freed 3000K, 31% free 9567K/13740K, paused 4ms+1ms, total 78ms
D/dalvikvm( 6393): WAIT_FOR_CONCURRENT_GC blocked 64ms
V/AwesomePlayer( 1926): postAudioEOS delayUs (0)
V/AwesomePlayer( 1926): onCheckAudioStatus
V/AwesomePlayer( 1926): onCheckAudioStatus() set AUDIO_AT_EOS flag
V/AwesomePlayer( 1926): onStreamDone
V/AwesomePlayer( 1926): MEDIA_PLAYBACK_COMPLETE
V/AwesomePlayer( 1926): notifyListner_l() msg (2-MEDIA_PLAYBACK_COMPLETE), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x43f417e8, 2, 0, 0)
V/AudioCache( 1926): playback complete - thread will wake up later
V/AwesomePlayer( 1926): notifyListner_l() msg (7-MEDIA_PAUSED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x43f417e8, 7, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=1)
V/AwesomePlayer( 1926): addBatteryData
V/AudioCache( 1926): wait - success
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AudioCache( 1926): notify(0x43f417e8, 8, 0, 0)
V/AudioCache( 1926): ignored
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop mState=4
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stop() sendCommand(0x43, OMX_CommandStateSet, OMX_StateIdle)
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] Now Idle. Component sends idle done Event 
I/OMXCodec( 1926): [OMX.google.vorbis.decoder] stopOmxComponent_l() mstate = 1
I/AudioPlayer( 1926): reset out
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
I/SecMediaClock( 1926): SecMediaClock destructor
V/AwesomePlayer( 1926): mSecMediaClock clear
V/StagefrightPlayer( 1926): ~StagefrightPlayer
V/StagefrightPlayer( 1926): reset
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
V/AwesomePlayer( 1926): destructor
V/AwesomePlayer( 1926): reset_l()
V/AwesomePlayer( 1926): notifyListner_l() msg (8-MEDIA_STOPPED), ext1 (0), ext2 (0)
V/AwesomePlayer( 1926): cancelPlayerEvents (keepNotifications=0)
V/AwesomePlayer( 1926): mAudioTrackVector clear
V/AwesomePlayer( 1926): reset_l() mAudioPlayer successfully deleted
V/AwesomePlayer( 1926): mSecMediaClock clear
D/CustomFrequencyManagerService( 2404): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2404  pkgName : ACTIVITY_RESUME_BOOSTER@4
I/SurfaceFlinger( 1921): id=17 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1921): id=18 createSurf (16x16),-1 flag=20004, EimLayer
W/ActivityManager( 2404): mDVFSHelper.acquire()
I/SELinux ( 6434): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6434):  
D/PointerIcon( 2404): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2404): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2404): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2404): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 6363): Shutting down VM
D/dalvikvm( 6363): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+0ms, total 3ms
I/SELinux ( 6434): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6434):  
I/SELinux ( 6434):  
I/SELinux ( 6434): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6434): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6434): >>>>> Normal User
E/dalvikvm( 6434): >>>>> com.test.thalitest [ userId:0 | appId:10581 ]
E/SELinux ( 6434): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 6434): in addTimaSignatureService
D/TimaKeyStoreProvider( 6434): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 6434): Added TimaKesytore provider
V/WindowManager( 2404): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
I/SELinux ( 6450): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6450):  
I/PowerManagerService( 2404): [PWL] Off : 75s ago
I/ActivityManager( 2404): Killing 5177:com.sec.modem.settings/1000 (adj 15): empty #43
I/SELinux ( 6450): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6450):  
I/SELinux ( 6450):  
I/SELinux ( 6450): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6450): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 6450): >>>>> Normal User
E/dalvikvm( 6450): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10043 ]
E/SELinux ( 6450): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
I/SQLiteSecureOpenHelper( 4150): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4150): getDatabaseLocked(b,b,pwd)...
D/TimaKeyStoreProvider( 6450): in addTimaSignatureService
D/dalvikvm( 6434): GC_CONCURRENT freed 3009K, 31% free 9557K/13740K, paused 2ms+1ms, total 37ms
D/dalvikvm( 6434): WAIT_FOR_CONCURRENT_GC blocked 33ms
,D/TimaKeyStoreProvider( 6450): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6450): Added TimaKesytore provider
,I/SurfaceFlinger( 1921): id=9 Removed Mauncher (8/10)
,I/SurfaceFlinger( 1921): id=9 Removed Mauncher (-2/10)
,D/Launcher( 2769): onTrimMemory. Level: 20
,V/WebViewChromium( 6434): Binding Chromium to the background looper Looper (main, tid 1) {4227d5f0}
,I/chromium( 6434): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6434): Initializing chromium process, renderers=0
,W/chromium( 6434): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/dalvikvm( 6450): GC_CONCURRENT freed 2996K, 31% free 9578K/13748K, paused 5ms+5ms, total 28ms
,D/dalvikvm( 6450): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/libEGL  ( 6434): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 6434): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 6434): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 6434): Mali API Version : 401
,I/Mali    ( 6434): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 6434): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 6434): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 6434): VFY: replacing opcode 0x6e at 0x0016
,I/dalvikvm( 6434): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 6434): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 6434): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/StatusBarManagerService( 2404): tr p:6434,o:f
W/dalvikvm( 6434): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 6434): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 6434): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 6434): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 6434): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 6434): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 6434): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 6434): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 6434): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 6434): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 6434): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 6434): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 6434): CordovaWebView is running on device made by: samsung
,D/StatusBarManagerService( 2404): semi p:6434,o:f
D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,I/SurfaceFlinger( 1921): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2404): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2404): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2404): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2404): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2404): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2404): setHoveringSpenCustomIcon IconType is same.1
I/HWUI    ( 6434): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 6434): Enabling debug mode 0
,W/AwContents( 6434): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/AwContents( 6434): nativeOnDraw failed; clearing to background color.
D/CustomFrequencyManagerService( 2404): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2404  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/CustomFrequencyManagerService( 2404): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2404  tag : ACTIVITY_RESUME_BOOSTER@4
I/SecureStorage( 1965): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage( 1965): [INFO]: SPID(0x00000003)PID: 6332, TID: 6343
W/ActivityManager( 2404): mDVFSHelper.release()
,W/IInputConnectionWrapper( 6434): showStatusIcon on inactive InputConnection
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 6450): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,W/ActivityManager( 2404): Unable to start service Intent { cmp=com.samsung.android.sdk.samsunglink/com.sec.pcw.analytics.AnalyticsUploaderService (has extras) } U=0: not found
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 6450): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,I/SELinux ( 6499): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6499):  
,I/SELinux ( 6499): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6499):  
I/SELinux ( 6499):  
,I/SELinux ( 6499): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6499): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6499): >>>>> Normal User
,E/dalvikvm( 6499): >>>>> com.osp.app.signin [ userId:0 | appId:10044 ]
,E/SELinux ( 6499): [DEBUG] seapp_context_lookup: seinfoCategory = default
,I/SecureStorage( 6332): [INFO]: SPID(0x00000000)Processing data has been completed
I/SecureStorage( 6332): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
,I/SQLiteSecureOpenHelper( 6332): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 6332): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 6332): Open platform.db in secure mode
,D/TimaKeyStoreProvider( 6499): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6499): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6499): Added TimaKesytore provider
,D/dalvikvm( 6499): GC_CONCURRENT freed 2982K, 31% free 9584K/13744K, paused 3ms+2ms, total 20ms
,D/dalvikvm( 6499): WAIT_FOR_CONCURRENT_GC blocked 11ms
,I/SA      ( 6499): [SSP] onCreated
,I/SA      ( 6499): [TPM] There is no property file
,I/SA      ( 6499): [SCU] isHaveSA() - false
,I/SA      ( 6499): [TPM] getModelProperty : null
,I/SA      ( 6499): [TPM] getCSCProperty : null
,I/SA      ( 6499): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 6499): [DM] init START
I/SQLiteSecureOpenHelper( 6332): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 6332): ...getDatabaseLocked(b,b,pwd)
,I/SA      ( 6499): [DM] This device is not a Vodafone
,I/SA      ( 6499): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 6499): support phone number id : false
I/SA      ( 6499): [DM] init END
,I/SA      ( 6499): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 6499): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package ]
I/ActivityManager( 2404): Killing 4624:com.sec.android.provider.badge/u0a76 (adj 15): empty #43
,D/Mms/PackageInstallReceiver( 5556): loadAuthorityPref(): sEnableAuthority = true
,I/Icing.InternalIcingCorporaProvider( 5903): Updating corpora: A: com.test.thalitest, C: MAYBE
,W/ContextImpl( 4791): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:153 android.app.ActivityThread.handleReceiver:2698 
,I/SELinux ( 6523): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6523):  
,D/JsMessageQueue( 6434): Set native->JS mode to OnlineEventsBridgeMode
,I/SELinux ( 6523): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6523):  
I/SELinux ( 6523):  
,I/SELinux ( 6523): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6523): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 6523): >>>>> Normal User
,E/dalvikvm( 6523): >>>>> com.sec.android.service.cm [ userId:0 | appId:10082 ]
,E/SELinux ( 6523): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 6523): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6523): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6523): Added TimaKesytore provider
,D/dalvikvm( 6523): GC_CONCURRENT freed 3003K, 31% free 9567K/13748K, paused 4ms+2ms, total 36ms
,D/dalvikvm( 6523): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/CapabilityManagerService New( 6523): Receiver Broadcast:android.intent.action.PACKAGE_ADDED
,I/SELinux ( 6535): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6535):  
I/ActivityManager( 2404): Killing 5193:tv.peel.smartremote/u0a165 (adj 15): empty #43
,D/dalvikvm( 6434): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42276308
,D/dalvikvm( 6434): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42276308
D/jxcore_app_log( 6434): JniHelper::setJavaVM(0x4171b220), pthread_self() = 2031013760
,D/JX-Cordova( 6434): jxcore cordova android initializing
,I/SELinux ( 6535): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6535):  
I/SELinux ( 6535):  
,I/SELinux ( 6535): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6535): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6535): >>>>> Normal User
,E/dalvikvm( 6535): >>>>> com.samsung.android.app.watchmanagerstub [ userId:0 | appId:10104 ]
,E/SELinux ( 6535): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6535): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6535): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6535): Added TimaKesytore provider
,D/dalvikvm( 6535): GC_CONCURRENT freed 2990K, 31% free 9578K/13744K, paused 3ms+1ms, total 53ms
,D/dalvikvm( 6535): WAIT_FOR_CONCURRENT_GC blocked 46ms
,D/PackageIntentReceiver( 6535): ACTION_PACKAGE_ADDED
,D/PackageIntentReceiver( 6535): Not GearManger package! 
,I/SELinux ( 6547): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6547):  
I/ActivityManager( 2404): Killing 5215:org.simalliance.openmobileapi.service/1101 (adj 15): empty #43
,I/SELinux ( 6547): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6547):  
I/SELinux ( 6547):  
,I/SELinux ( 6547): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6547): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6547): >>>>> Normal User
,E/dalvikvm( 6547): >>>>> com.samsung.android.magazine.service [ userId:0 | appId:10110 ]
,E/SELinux ( 6547): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 6547): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6547): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6547): Added TimaKesytore provider
,I/Icing.InternalIcingCorporaProvider( 5903): UpdateCorporaTask done [took 498 ms] updated apps [took 497 ms] 
I/ActivityManager( 2404): Killing 5241:com.sec.android.app.taskmanager/u0a168 (adj 15): empty #43
,D/dalvikvm( 6547): GC_CONCURRENT freed 2994K, 31% free 9575K/13748K, paused 4ms+2ms, total 42ms
,D/dalvikvm( 6547): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/dalvikvm( 6434): GC_CONCURRENT freed 1281K, 18% free 11348K/13800K, paused 3ms+2ms, total 39ms
,D/dalvikvm( 6434): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 6434): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/CustomFrequencyManagerService( 2404): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2404  tag : ACTIVITY_RESUME_BOOSTER@8
,D/MagazineService Version( 6547): Magazine-Channel: 13
,D/MagazineService Version( 6547): Magazine-Provider: 13
,D/MagazineService Version( 6547): Magazine-Administrator: 11
,D/HeadlinesChannelApplication( 6547): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 6547): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
,I/SELinux ( 6561): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6561):  
,I/MagazineService::MagazineService( 6547): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,D/MagazineService::MagazineService( 6547): [onHandleIntent] Send broadcast to (com.test.thalitest).
I/ActivityManager( 2404): Killing 5255:com.samsung.android.service.travel/u0a170 (adj 15): empty #43
,I/SELinux ( 6561): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6561):  
I/SELinux ( 6561):  
,I/SELinux ( 6561): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6561): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6561): >>>>> Normal User
,E/dalvikvm( 6561): >>>>> com.samsung.helphub [ userId:0 | appId:1000 ]
,E/SELinux ( 6561): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6561): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6561): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6561): Added TimaKesytore provider
,D/dalvikvm( 6561): GC_CONCURRENT freed 3003K, 31% free 9571K/13748K, paused 2ms+2ms, total 22ms
,D/dalvikvm( 6561): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(384), More:false, Req:false Child:2
,I/SELinux ( 6575): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6575):  
,I/ActivityManager( 2404): Killing 5282:com.gameloft.android.GloftGF2H/u0a179 (adj 15): empty #43
,I/SELinux ( 6575): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6575):  
I/SELinux ( 6575):  
,I/SELinux ( 6575): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6575): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6575): >>>>> Normal User
,E/dalvikvm( 6575): >>>>> com.sec.kidsplat.installer [ userId:0 | appId:10160 ]
,E/SELinux ( 6575): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6575): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6575): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6575): Added TimaKesytore provider
,D/dalvikvm( 6575): GC_CONCURRENT freed 3001K, 31% free 9567K/13744K, paused 3ms+2ms, total 52ms
,D/dalvikvm( 6575): WAIT_FOR_CONCURRENT_GC blocked 47ms
,D/dalvikvm( 6434): GC_CONCURRENT freed 1874K, 17% free 14973K/18036K, paused 2ms+4ms, total 48ms
,D/dalvikvm( 6434): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/KidsPlatformStub( 6575): Package not found : com.sec.android.app.kidshome
,I/SELinux ( 6587): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6587):  
,I/ActivityManager( 2404): Killing 5295:com.gameloft.android.GloftKLMF/u0a180 (adj 15): empty #43
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 12% free 9504K/10724K, paused 2ms+3ms, total 31ms
,I/SELinux ( 6587): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6587):  
I/SELinux ( 6587):  
,I/SELinux ( 6587): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6587): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6587): >>>>> Normal User
,E/dalvikvm( 6587): >>>>> com.samsung.android.provider.shootingmodeprovider [ userId:0 | appId:10164 ]
,E/SELinux ( 6587): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9504K/10724K, paused 1ms+3ms, total 26ms
,D/TimaKeyStoreProvider( 6587): in addTimaSignatureService
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9504K/10724K, paused 2ms+3ms, total 25ms
,D/TimaKeyStoreProvider( 6587): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6587): Added TimaKesytore provider
,D/dalvikvm( 6587): GC_CONCURRENT freed 2998K, 31% free 9577K/13748K, paused 3ms+2ms, total 20ms
,D/dalvikvm( 6587): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/SELinux ( 6599): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6599):  
,I/ActivityManager( 2404): Killing 5308:com.gameloft.android.GloftPSHU/u0a181 (adj 15): empty #43
,I/Icing   ( 3286): Indexing 8AF1F6B88973B002A001A3BB90ED270D05322BB1 from com.google.android.googlequicksearchbox
,I/SELinux ( 6599): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6599):  
I/SELinux ( 6599):  
,I/SELinux ( 6599): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6599): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6599): >>>>> Normal User
,E/dalvikvm( 6599): >>>>> com.sec.enterprise.knox.cloudmdm.smdms [ userId:0 | appId:10171 ]
,E/SELinux ( 6599): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 6599): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6599): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6599): Added TimaKesytore provider
,D/dalvikvm( 6599): GC_CONCURRENT freed 2990K, 31% free 9579K/13744K, paused 3ms+6ms, total 34ms
,D/dalvikvm( 6599): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/Icing   ( 3286): Indexing done 8AF1F6B88973B002A001A3BB90ED270D05322BB1
,D/UMC:Core( 6599): onCreate(): 
,D/USER_AGENT( 6599): UMC/1.0.12 (SM-G800F) SAFE-5 KNOX-2.0
,D/[SAMSUNG SMARCART NATIVE]( 6599): initialize...
,D/[SAMSUNG SMARCART NATIVE]( 6599): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
,I/TZ_CCM_C_GetFunctionList: ( 6599): TZ_CCM_C_GetFunctionList was called
,D/[SAMSUNG SMARCART NATIVE]( 6599): FINISHED: initialize rv:0
,D/dalvikvm( 6434): GC_FOR_ALLOC freed 5424K, 30% free 16287K/23084K, paused 42ms, total 47ms
,D/dalvikvm( 6599): GC_CONCURRENT freed 1875K, 23% free 10777K/13824K, paused 3ms+3ms, total 53ms
,D/dalvikvm( 6599): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/UMC:SecurityUtils( 6599): Loaded server certificates: 0
,D/UMC:SecurityUtils( 6599): Loaded server certificates: 0
,D/UMC:CloudMDMSecurity( 6599): New Flow
D/TimaService( 2404): TIMA3: in ccmRegisterForDefaultCertificate
,D/TimaService( 2404): TIMA: in getTimaVersion
I/        ( 2404): CCM JNI: In ccm_register_for_default_cert
I/        ( 2404): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: ( 2404): &ctx = 0x77adb618
I/TLC_TZ_CCM: ( 2404): creating new ccm context...
I/TLC_TZ_CCM: ( 2404): initializing ccm context...
I/TLC_TZ_CCM: ( 2404): root = 0, root_strlen = 1
I/TLC_TZ_CCM: ( 2404): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: client_server_communication( 2404): input max_sendmsg_size = 19420
I/TZ: client_server_communication( 2404): input max_recvmsg_size = 19420
I/TZ: client_server_communication( 2404): root = 0, root_len = 1
I/TZ: client_server_communication( 2404): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: client_server_communication( 2404): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication( 2404): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication( 2404): Client_Server_Open was called
I/TZ: client_server_communication( 2404): IClientServer::IClientServer()
I/TZ: client_server_communication( 2404): BpClientServer::BpClientServer()
I/TZ_CCM_SERVER( 2511): BnCCM::onTransact(0) 16
I/TZ_CCM_SERVER( 2511): creating new ccm context...
I/TZ_CCM_SERVER( 2511): initializing ccm context...
I/TZ_CCM_SERVER( 2511): root = 0, root_strlen = 1
I/TZ_CCM_SERVER( 2511): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: mc_tlc_communication( 2511): input max_sendmsg_size = 19420
I/TZ: mc_tlc_communication( 2511): input max_recvmsg_size = 19420
I/TZ: mc_tlc_communication( 2511): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2511): process = ffffffff000000000000000000000012, process_strlen = 32
I/TZ: mc_tlc_communication( 2511): aligned max_sendmsg_size = 19456
I/TZ: mc_tlc_communication( 2511): aligned max_recvmsg_size = 19456
I/TZ: mc_tlc_communication( 2511): device_id = 0x0
I/TZ: mc_tlc_communication( 2511): tlc_open() was called
I/TZ: mc_tlc_communication( 2511): Opening MobiCore device
I/TZ: mc_tlc_communication( 2511): Allocating WSM for TCI
I/TZ: mc_tlc_communication( 2511): Opening the session
,I/TZ: mc_tlc_communication( 2511): tlc_open() succeeded
,I/TZ: client_server_communication( 2404): Client_Server_Open succeeded
I/TZ_CCM_C_Initialize: ( 2404): ctx = 0x7b04cd80, comm = 0x80e72f00, sendmsg = 0x80e742b8, recvmsg = 0x80e78eb8
,I/TZ_init: ( 2404): TZ_init: sending initialization request...
I/TZ_CCM_SERVER( 2511): BnCCM::onTransact(2) 16
,E/Parcel  ( 2511): nm 19456
,E/Parcel  ( 2404): nm 19456
E/TZ_init: ( 2404): TZ_init Process: Secure memory is not initialized!
E/TZ_init: ( 2404): trustlet initialization failed
,I/TZ_init: ( 2404): TZ_init_START...
,I/TZ_init: ( 2404): TZ_init_with_data: sending initialization request...
I/TZ_CCM_SERVER( 2511): BnCCM::onTransact(2) 16
,E/Parcel  ( 2511): nm 19456
,E/Parcel  ( 2404): nm 19456
,I/TZ_init: ( 2404): TZ_init: successful initialization
,I/TLC_TZ_COMMON: key_db_init: ( 2404): Exercising TZ_DB_INIT in TLC
I/TZ_CCM_SERVER( 2511): BnCCM::onTransact(2) 16
,E/Parcel  ( 2511): nm 19456
,E/Parcel  ( 2404): nm 19456
I/TZ_COMMON: tlc_key_db_util: ( 2404): DB Operation suceeded
I/TLC_TZ_CCM: register for default cert: ( 2404): Exercising TZ_CCM_register_default_TLC
I/TZ_CCM_SERVER( 2511): BnCCM::onTransact(2) 16
,E/Parcel  ( 2511): nm 19456
,E/Parcel  ( 2404): nm 19456
I/TLC_TZ_CCM: register for default cert: ( 2404): TZ_CCM_register_default_TLC_END: DB file size to update is 0
I/TLC_TZ_CCM: register for default cert: ( 2404): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
,I/TZ_CCM_C_Finalize: ( 2404): Exercising TZ_CCM_C_Finalize_TLC
I/TZ_CCM_SERVER( 2511): BnCCM::onTransact(2) 16
,E/Parcel  ( 2511): nm 19456
,E/Parcel  ( 2404): nm 19456
I/TZ: client_server_communication( 2404): Client_Server_Close was called
I/TZ_CCM_SERVER( 2511): BnCCM::onTransact(1) 16
I/TZ: mc_tlc_communication( 2511): tlc_close() was called
,I/TZ: mc_tlc_communication( 2511): Closing the session
I/TZ: mc_tlc_communication( 2511): Free WSM
,I/TZ: mc_tlc_communication( 2511): Closing MobiCore device
,I/TZ: mc_tlc_communication( 2511): tlc_close() succeeded
,I/TZ: client_server_communication( 2404): Client_Server_Close succeeded
,D/UMC:CloudMDMSecurity( 6599): TIMA service call for password change success!!
,D/UMC:AdminManager( 6599): init - start
,D/UMC:AdminManager( 6599): loadAdmins
,D/UMC:AdminManager( 6599): removeOutOfSyncProxyAdmins
,D/UMC:AdminManager( 6599): startPolicyHandlers
,I/UMC:TestPolicyHandler( 6599): Setup is called in testpolicyhandler
,D/UMC:AdminManager( 6599): init - end
,V/UMC:AlarmHandler( 6599): Enter loadList
,D/EnterpriseDeviceManagerService( 2404): Creating context as user 0
,D/SPPApp  ( 6599): [SppMessageReceiver] onReceive
,D/SPPApp  ( 6599): [SppMessageReceiver] onReceive. ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
,I/SELinux ( 6613): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6613):  
I/ActivityManager( 2404): Killing 5344:com.google.android.youtube/u0a175 (adj 15): empty #43
,I/SELinux ( 6613): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6613):  
I/SELinux ( 6613):  
,I/SELinux ( 6613): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6613): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6613): >>>>> Normal User
,E/dalvikvm( 6613): >>>>> com.n7mobile.promenadaplusa [ userId:0 | appId:10183 ]
,E/SELinux ( 6613): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 6613): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6613): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6613): Added TimaKesytore provider
,D/dalvikvm( 6613): GC_CONCURRENT freed 3001K, 31% free 9571K/13748K, paused 3ms+1ms, total 22ms
,D/dalvikvm( 6613): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/ApplicationPromenada( 6613): Application OnCreate start
,D/ApplicationPromenada( 6613): Application OnCreate po on Create
D/CrashReporter( 6613): Initing Crashreporter: com.n7mobile.promenada2.ApplicationPromenada@42278dc8
D/CrashReporter( 6613): Swaping uncaught exception handler
,D/ApplicationPromenada( 6613): Application OnCreate App Loader start
,D/ApplicationPromenada( 6613): Application OnCreate App Loader finish
,D/p2.ApplicationLoader( 6613): ############################## cached apps: 
,V/WebViewChromium( 6613): Binding Chromium to the background looper Looper (main, tid 1) {4227c340}
,I/chromium( 6613): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 6613): Initializing chromium process, renderers=0
,W/chromium( 6613): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 6613): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 6613): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 6613): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 6613): Mali API Version : 401
,I/Mali    ( 6613): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/ApplicationPromenada( 6613): Application OnCreate Finish
,D/dalvikvm( 6434): GC_CONCURRENT freed 6691K, 31% free 17732K/25652K, paused 3ms+10ms, total 74ms
,D/dalvikvm( 6434): WAIT_FOR_CONCURRENT_GC blocked 50ms
,I/SELinux ( 6644): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6644):  
,I/ActivityManager( 2404): Killing 5488:com.samsung.klmsagent/u0a18 (adj 15): empty #43
,I/SELinux ( 6644): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6644):  
I/SELinux ( 6644):  
,I/SELinux ( 6644): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6644): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 6644): >>>>> Normal User
,E/dalvikvm( 6644): >>>>> com.sec.android.app.samsungapps [ userId:0 | appId:10041 ]
,E/SELinux ( 6644): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 6644): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6644): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6644): Added TimaKesytore provider
,D/dalvikvm( 6644): GC_CONCURRENT freed 2998K, 31% free 9570K/13744K, paused 4ms+1ms, total 23ms
,D/dalvikvm( 6644): WAIT_FOR_CONCURRENT_GC blocked 5ms
,I/ActivityManager( 2404): Killing 5580:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/ChimeraCfgMgr( 3286): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3286): Module APK com.google.android.play.games already loaded
,D/PackageBroadcastService( 3286): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraCfgMgr( 3286): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3286): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 3286): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 3286): Submit a task: k
,D/ChimeraCfgMgr( 3286): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/dalvikvm( 6434): GC_FOR_ALLOC freed 1417K, 33% free 17426K/25652K, paused 48ms, total 50ms
,D/ChimeraCfgMgr( 3286): Loading module com.google.android.gms.vision from APK com.google.android.gms
I/dalvikvm-heap( 6434): Grow heap (frag case) to 21.677MB for 3688532-byte allocation
,D/k       ( 3286): Processing package: com.test.thalitest
,D/GassUtils( 3286): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
D/k       ( 3286): Found info for package com.test.thalitest in db.
D/dalvikvm( 6434): GC_FOR_ALLOC freed 11K, 29% free 21016K/29256K, paused 48ms, total 48ms
,D/dalvikvm( 6613): GC_CONCURRENT freed 1749K, 22% free 10814K/13748K, paused 3ms+12ms, total 55ms
,W/jxcore-log( 6434): Initializing JXcore engine
,W/jxcore-log( 6434): JXcore engine is ready
,W/jxcore-log( 6434): Starting JXcore engine
,D/dalvikvm( 2404): GC_EXPLICIT freed 24398K, 73% free 24465K/87680K, paused 13ms+21ms, total 303ms
,D/Finsky  ( 3857): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,W/jxcore-log( 6434): Platform android
W/jxcore-log( 6434): 
,W/jxcore-log( 6434): Process ARCH arm
W/jxcore-log( 6434): 
,D/dalvikvm( 6613): GC_CONCURRENT freed 2364K, 26% free 10424K/13964K, paused 2ms+2ms, total 29ms
D/SSRMv2:SIOP( 2404): SIOP:: AP = 350, Delta = 20
,W/ResourceType( 6613): Failure getting entry for 0x7f060000 (t=5 e=0) in package 0 (error -75)
,W/PackageManager( 6613): Failure retrieving text 0x7f060000 in package com.android.keyguard
W/PackageManager( 6613): android.content.res.Resources$NotFoundException: String resource ID #0x7f060000
W/PackageManager( 6613): 	at android.content.res.Resources.getText(Resources.java:1374)
W/PackageManager( 6613): 	at android.app.ApplicationPackageManager.getText(ApplicationPackageManager.java:1198)
W/PackageManager( 6613): 	at android.content.pm.PackageItemInfo.loadLabel(PackageItemInfo.java:135)
W/PackageManager( 6613): 	at android.app.ApplicationPackageManager.getApplicationLabel(ApplicationPackageManager.java:1242)
W/PackageManager( 6613): 	at com.n7mobile.promenada2.applications.ApplicationLoader.a(SourceFile:155)
W/PackageManager( 6613): 	at com.n7mobile.promenada2.applications.ApplicationLoader.c(SourceFile:135)
W/PackageManager( 6613): 	at com.n7mobile.promenada2.applications.ApplicationLoader.a(SourceFile:125)
W/PackageManager( 6613): 	at com.n7p.pp.run(SourceFile:52)
W/PackageManager( 6613): 	at java.lang.Thread.run(Thread.java:841)
,I/Icing   ( 3286): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
,I/Icing   ( 3286): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,D/dalvikvm( 6613): GC_CONCURRENT freed 2074K, 26% free 10366K/13964K, paused 1ms+5ms, total 35ms
,I/jxcore-log( 6434): JXcore Cordova bridge is ready!
I/jxcore-log( 6434): 
,W/jxcore-log( 6434): JXcore engine is started
,I/chromium( 6434): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 6434): Toggling radios to true
I/jxcore-log( 6434): 
,W/ActivityManager( 2404): Permission Denial: getCurrentUser() from pid=6434, uid=10581 requires android.permission.INTERACT_ACROSS_USERS
,W/BluetoothManagerService( 2404): Failed getting userId using ActivityManagerNative
W/BluetoothManagerService( 2404): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6434, uid=10581 requires android.permission.INTERACT_ACROSS_USERS
W/BluetoothManagerService( 2404): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/BluetoothManagerService( 2404): 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:620)
W/BluetoothManagerService( 2404): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
W/BluetoothManagerService( 2404): 	at android.os.Binder.execTransact(Binder.java:404)
W/BluetoothManagerService( 2404): 	at dalvik.system.NativeStart.run(Native Method)
E/DevicePolicyManagerService( 2404): getAllowBluetoothMode - value retunrs : 2
,D/BluetoothManagerService( 2404): foregroundUser: 0
D/AmoledAdjustTimer( 2404): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/BluetoothManagerService( 2404): Package is exist.
,I/WifiManager( 6434): packageName : com.test.thalitest
,I/WifiManager( 6434): setWifiEnabled : true
,I/WifiService( 2404): setWifiEnabled: true pid=6434, uid=10581
,W/WifiService( 2404): Failed getting userId using ActivityManagerNative
W/WifiService( 2404): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6434, uid=10581 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2404): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2404): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2404): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2404): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2404): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2404): 	at dalvik.system.NativeStart.run(Native Method)
,W/ActivityManager( 2404): Permission Denial: getCurrentUser() from pid=6434, uid=10581 requires android.permission.INTERACT_ACROSS_USERS
D/BluetoothAdapterState( 5068): CURRENT_STATE=OFF, MSG = USER_TURN_ON
I/BluetoothAdapterState( 5068): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 5068): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 5068): updateAdapterState state is 11
D/BluetoothAdapterService( 5068): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothAdapterService( 5068): Autoconnection is available 
D/BluetoothAdapterService( 5068): updateAdapterState prevState = 10newState = 11
D/BtConfig.SecureMode( 5068): isSecureModeOn:false
,D/BtSettings.ProfileConfig( 5068): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/InputMethodManagerService( 2404): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 2404): [BT Setting State] State =11
,D/PhoneApp( 2753): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 11
W/BluetoothAdapterService( 5068): isProfileEnabled(): profile com.android.bluetooth.gatt.GattService, state= 12
,D/BtSettings.ProfileConfig( 5068): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,I/QuickConnect[1.1][2] ( 5042): BluetoothHelper.ACTION_STATE_CHANGED - STATE_TURNING_ON
,I/SamsungIME( 3003): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,I/WifiService( 2404): disconnect: pid=6434, uid=10581
W/BluetoothAdapterService( 5068): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 5068): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,E/WifiHW  ( 2404): ##################### set firmware type 0 #####################
,I/jxcore-log( 6434): Radios toggled
I/jxcore-log( 6434): 
,W/BluetoothAdapterService( 5068): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,D/BtSettings.ProfileConfig( 5068): getProfileSaveSetting: com.android.bluetooth.hid.HidService
I/WifiHW  ( 1916): wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
E/WifiHW  ( 1916): Cannot open "/data/.cid.info": No such file or directory
I/WifiHW  ( 1916): wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
E/WifiHW  ( 1916): TEMP_FAILURE_RETRY complete
,D/SoftapController( 1916): Softap fwReload - Ok
W/BluetoothAdapterService( 5068): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,D/BtSettings.ProfileConfig( 5068): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 5068): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 5068): getProfileSaveSetting: com.android.bluetooth.pan.PanService
D/CommandListener( 1916): Setting iface cfg
,D/CommandListener( 1916): Trying to bring down wlan0
W/BluetoothAdapterService( 5068): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,D/BtSettings.ProfileConfig( 5068): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5068): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 5068): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5068): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 5068): Unable to stop service com.android.bluetooth.gatt.GattService. Invalid state: 12
W/BluetoothAdapterService( 5068): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 5068): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 5068): Not skipping com.android.bluetooth.hfp.HeadsetService
D/WifiHW  ( 2404): Skip the update_ctrl_interface
,D/WifiHW  ( 2404): Skip the update_ctrl_interface
,E/WifiHW  ( 2404): supplicant_name : p2p_supplicant
,W/BluetoothAdapterService( 5068): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 5068): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,W/BluetoothAdapterService( 5068): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/WifiMonitor( 2404): startMonitoring(wlan0) with mConnected = false
,D/HeadsetService( 5068): Received start request. Starting profile...
,W/BluetoothAdapterService( 5068): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hid.HidService
I/BluetoothHeadsetServiceJni( 5068): classInitNative: succeeds
D/HeadsetStateMachine( 5068): Version 1.5
D/HeadsetStateMachine( 5068): make
D/BtSettings.ProfileConfig( 5068): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5068): Not skipping com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 5068): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.hdp.HealthService
,D/BtSettings.ProfileConfig( 5068): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 5068): Not skipping com.android.bluetooth.hdp.HealthService
I/wpa_supplicant( 6668): wpa_supplicant v2.1-devel-4.4.22014-07-16/12:43:14
,D/QuickConnect[1.1][2] ( 5042): HeadsetProfile.onServiceConnected - Bluetooth service connected
,W/BluetoothAdapterService( 5068): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 5068): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 5068): Not skipping com.android.bluetooth.pan.PanService
I/wpa_supplicant( 6668): [wpa_supplicant_init]: use SECRIL
I/wpa_supplicant( 6668): Successfully initialized wpa_supplicant
I/wpa_supplicant( 6668): >>>>> Not GET KEY, IV <<<<<
,E/HeadsetStateMachine( 5068): # of Max HF connection is 2
,W/BluetoothAdapterService( 5068): check For Quiet mode profile 12 RadioCount =1 srv name=com.android.bluetooth.map.BluetoothMapService
,D/BtSettings.ProfileConfig( 5068): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 5068): Not skipping com.android.bluetooth.map.BluetoothMapService
E/wpa_supplicant( 6668): getIMSI cannot open file
,E/wpa_supplicant( 6668): Interworking config: - SIM READ ERROR
W/BluetoothAdapterService( 5068): check For Quiet mode profile 12 RadioCount =1 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 5068): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 5068): Not skipping com.broadcom.bt.service.sap.SapService
,I/BluetoothAdapterState( 5068): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,D/BluetoothNotiBroadcastReceiver( 5526): onReceive
,I/bluedroid( 5068): get_profile_interface handsfree
,I/SELinux ( 6670): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6670):  
I/SELinux ( 6670): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6670):  
I/SELinux ( 6670):  
I/SELinux ( 6670): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6670): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 6670): >>>>> Normal User
E/dalvikvm( 6670): >>>>> pl.k2.droidoaudioteka [ userId:0 | appId:10066 ]
,E/SELinux ( 6670): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/BluetoothAtMessage( 5068): createCMTIContentObservers
,D/HeadsetStateMachine( 5068): Enter Disconnected: -2
,E/HeadsetStateMachine( 5068): set to mRemoteBrsf = 0
D/HeadsetStateMachine( 5068): map size, before remove : 0
D/HeadsetStateMachine( 5068): map size, after remove: 0
,D/HeadsetStateMachine( 5068): mNextConnectingDevice : null
,I/wpa_supplicant( 6668): >>>>> Not GET KEY, IV <<<<<
E/wpa_supplicant( 6668): getIMSI cannot open file
E/wpa_supplicant( 6668): Interworking config: - SIM READ ERROR
,I/wpa_supplicant( 6668): >>>>> Not GET KEY, IV <<<<<
,I/wpa_supplicant( 6668): rfkill: Cannot open RFKILL control device
,I/dalvikvm( 6670): Enabling JNI app bug workarounds for target SDK version 7...
,D/BluetoothA2dp( 2404): Proxy object connected
,D/BluetoothA2dp( 5042): Proxy object connected
,D/QuickConnect[1.1][2] ( 5042): A2dpProfile.onServiceConnected - Bluetooth service connected
,D/BluetoothA2dp( 4150): Proxy object connected
D/A2dpService( 5068): Received start request. Starting profile...
I/BluetoothA2dpServiceJni( 5068): classInitNative: succeeds
,D/A2dpStateMachine( 5068): make
,I/bluedroid( 5068): get_profile_interface a2dp
,D/TimaKeyStoreProvider( 6670): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6670): Cannot add TimaSignature Service, License check Failed
,I/GKI_LINUX( 5068): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,D/ActivityThread( 6670): Added TimaKesytore provider
,D/A2dpStateMachine( 5068): Enter Disconnected: -2
,I/BluetoothAvrcpServiceJni( 5068): classInitNative: succeeds
,I/bluedroid( 5068): get_profile_interface avrcp
,D/MediaFocusControl( 2404): >>> registerRemoteControlDisplay
,I/BluetoothHidServiceJni( 5068): classInitNative: succeeds
,D/BluetoothInputDevice( 5042): Proxy object connected
,D/HidService( 5068): Received start request. Starting profile...
,I/bluedroid( 5068): get_profile_interface hidhost
,D/HidService( 5068): setHidService(): set to: null
,I/BluetoothHealthServiceJni( 5068): classInitNative: succeeds
,D/QuickConnect[1.1][2] ( 5042): HidProfile.onServiceConnected - Bluetooth service connected
,D/HealthService( 5068): Received start request. Starting profile...
,I/bluedroid( 5068): get_profile_interface health
D/p2.ApplicationLoader( 6613): Process time: 2895
D/p2.ApplicationLoader( 6613): ##############################  apps after loading: 
,I/BluetoothPanServiceJni( 5068): classInitNative(L105): succeeds
,D/BluetoothPan( 2404): BluetoothPAN Proxy object connected
D/PanService( 5068): Received start request. Starting profile...
D/BluetoothPanServiceJni( 5068): initializeNative(L110): pan
,I/bluedroid( 5068): get_profile_interface pan
,D/BluetoothTethering( 2404): got CMD_CHANNEL_HALF_CONNECTED
,D/BluetoothMapService( 5068): Received start request. Starting profile...
,W/BluetoothMapMasInstance( 5068): mAccount : null
,I/BluetoothSAPServiceJni( 5068): classInitNative(L204): succeeds
D/SapService( 5068): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 5068): initializeNative(L209): sap
,I/bluedroid( 5068): get_profile_interface sap
,D/HeadsetPhoneState( 5068): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,D/HeadsetStateMachine( 5068): Disconnected process message: 11
,D/HeadsetStateMachine( 5068): Try to query the phonestate on bind
D/HeadsetPhoneState( 5068): sendDeviceDataStateChanged
D/HeadsetPhoneState( 5068): Signal level : previous=0 curr=0
,D/HeadsetStateMachine( 5068): Proxy object connected
D/BluetoothPhoneService( 2753): handleMessage: 4
,V/BluetoothPhoneService( 2753): Call state Converted2: IDLE/IDLE -> 6
W/BluetoothHeadset( 2753): Proxy not attached to service
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BluetoothAdapterService( 5068): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5068): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5068): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5068): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 5068): Profile still not running:com.broadcom.bt.service.sap.SapService
D/HeadsetStateMachine( 5068): Disconnected process message: 20
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
D/HeadsetPhoneState( 5068): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,D/HeadsetStateMachine( 5068): Disconnected process message: 11
,D/BluetoothAdapterService( 5068): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterState( 5068): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,I/bluedroid( 5068): enable
,D/GKI_LINUX( 5068): acquire_my_wake_lock(), g_wake_lock_fd:-1, g_wake_unlock_fd:-1, wake_lock_acquired:0
,E/bt-btif ( 5068): Calling BTA_HhEnable
,E/bt-btif ( 5068): btif_storage_get_adapter_property service_mask:0x160040
E/BluetoothServiceJni( 5068): populateRssiValuesNative
I/bluedroid( 5068): getModelRssiValues
,E/BluetoothServiceJni( 5068): model_rssi_values_callback: low = -75, mid = -65, high = 127
,E/BluetoothRemoteDevices( 5068): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 10
,D/BtConfig.SecureMode( 5068): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5068): devicePropertyChangedCallback: bdDevice: 34:FC:EF:9D:93:0B, value is empty for type: 241
,E/BluetoothRemoteDevices( 5068): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 10
,D/BtConfig.SecureMode( 5068): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5068): devicePropertyChangedCallback: bdDevice: 10:D3:8A:FB:85:D4, value is empty for type: 241
,E/BluetoothRemoteDevices( 5068): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 10
,D/BtConfig.SecureMode( 5068): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5068): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:3C:51, value is empty for type: 241
,E/BluetoothRemoteDevices( 5068): devicePropertyChangedCallback: bdDevice: F8:CF:C5:D9:E5:61, value is empty for type: 10
,D/BtConfig.SecureMode( 5068): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5068): devicePropertyChangedCallback: bdDevice: F8:CF:C5:D9:E5:61, value is empty for type: 241
,E/BluetoothRemoteDevices( 5068): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 10
,D/BtConfig.SecureMode( 5068): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5068): devicePropertyChangedCallback: bdDevice: 7C:F9:0E:34:8A:A0, value is empty for type: 241
,E/BluetoothRemoteDevices( 5068): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 10
,D/BtConfig.SecureMode( 5068): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5068): devicePropertyChangedCallback: bdDevice: F4:F1:E1:5C:3B:E2, value is empty for type: 241
,E/BluetoothRemoteDevices( 5068): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 10
,D/BtConfig.SecureMode( 5068): isSecureModeOn:false
,E/BluetoothRemoteDevices( 5068): devicePropertyChangedCallback: bdDevice: F8:95:C7:87:85:54, value is empty for type: 241
,E/BluetoothRemoteDevices( 5068): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 10
,D/BtConfig.SecureMode( 5068): isSecureModeOn:false
E/BluetoothRemoteDevices( 5068): devicePropertyChangedCallback: bdDevice: 58:2A:F7:ED:96:BE, value is empty for type: 241
E/bt-btif ( 5068): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:2
E/bt-btif ( 5068): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:1
E/bt-btif ( 5068): btif_sock_init: !radio_req && !rfc_init
,D/IOP_DB_BT( 5068): db_open: file /etc/bluetooth/iop_bt.db
D/IOP_DB_BT( 5068): db_open: db_open : handle 2010190892l, read 9734 bytes onto local cache
D/IOP_DB_BT( 5068): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 5068): db_query: result 1
I/        ( 5068): iop_db_open: iop_db_open status 0
,I/bte_conf( 5068): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 5068): [1] primary_record=1 vendor_id=0x0075 vendor_id_source=0x0001 product_id=0x0100 version=0x0200
I/bte_conf( 5068): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 5068): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/BluetoothAdapterState( 5068): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 5068): ScanMode =  20
,D/BluetoothAdapterProperties( 5068): State =  11
D/BtConfig.SecureMode( 5068): isSecureModeOn:false
D/BtConfig.SecureMode( 5068): isSecureModeOn:false
D/BtConfig.SecureMode( 5068): isSecureModeOn:false
D/BtConfig.SecureMode( 5068): isSecureModeOn:false
D/BtConfig.SecureMode( 5068): isSecureModeOn:false
D/BtConfig.SecureMode( 5068): isSecureModeOn:false
D/BtConfig.SecureMode( 5068): isSecureModeOn:false
D/BtConfig.SecureMode( 5068): isSecureModeOn:false
,I/BluetoothAdapterState( 5068): Bluetooth adapter state changed: 11-> 12
,D/BluetoothAdapterService( 5068): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 5068): updateAdapterState state is 12
,D/BluetoothAdapterService( 5068): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothA2dp( 2404): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 4150): onBluetoothStateChange: up=true
,D/BluetoothAdapterService(1109960344)( 5068): Register RemoteMessageListener
,D/HeadsetService( 5068): registerMessageListener
D/HeadsetStateMachine( 5068): Disconnected process message: 70
D/HeadsetStateMachine( 5068): processRegisterMessageListener : 2, com.android.bluetooth.btservice.RemoteDevices$1@422f3370
D/BluetoothAdapterService( 5068): Autoconnection is available 
D/BluetoothAdapterService( 5068): updateAdapterState prevState = 11newState = 12
,D/BluetoothAdapterService( 5068): starting service from this receiver
,D/BluetoothInputDevice( 5042): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 5042): onBluetoothStateChange: up=true
,W/ContextImpl( 5068): Implicit intents with startService are not safe: Intent { act=com.samsung.ble.ACTION_SERVICE_BLE_AUTO_CONNECT } android.content.ContextWrapper.startService:506 com.android.bluetooth.btservice.AdapterService.updateAdapterState:653 com.android.bluetooth.btservice.AdapterState.notifyAdapterStateChange:586 
,D/BluetoothAdapterService( 5068): initWakeLock, pfd lock: {ParcelFileDescriptor: FileDescriptor[85]}, pfd unlock: {ParcelFileDescriptor: FileDescriptor[86]}
,D/bluedroid( 5068): init_wake_lock lock_fd:85, unlock_fd:86
,I/BluetoothAdapterState( 5068): Entering On State from state = 11
W/InputMethodManagerService( 2404): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService( 2404): [BT Setting State] State =12
,I/InputMethodManagerService( 2404): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
D/BluetoothAdapterService(1109960344)( 5068): Get Bonded Devices being called
I/BluetoothPbapService( 5068): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
D/PhoneApp( 2753): mReceiver: BluetoothAdapter.ACTION_STATE_CHANGED: 12
I/SamsungIME( 3003): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
D/BluetoothHeadset( 2753): registerListener : 11, listenercom.android.phone.PhoneGlobals$MessageListener@42431138, true
I/QuickConnect[1.1][2] ( 5042): BluetoothHelper.ACTION_STATE_CHANGED - STATE_ON
D/BluetoothHeadset( 2753): registerMessageListener
D/BluetoothPanServiceJni( 5068): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
D/HeadsetService( 5068): registerMessageListener
D/HeadsetService( 5068): registerMessageListener
D/PhoneApp( 2753): registerMessageListener
D/HeadsetStateMachine( 5068): Disconnected process message: 70
D/HeadsetStateMachine( 5068): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@42363758
,I/BluetoothPbapService( 5068): Handler(): got msg=1
,V/BluetoothPbapService( 5068): PBAP Service initSocket try: 0
,W/BluetoothAdapter( 5068): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 5068): SOCK FLAG = 1 ***********************
,D/BluetoothPbapService( 5068): PBAP Socket is BluetoothServerSocket
,D/BluetoothMapMasInstance( 5068): set MAP SDP message type : 1
D/dalvikvm( 6670): GC_CONCURRENT freed 3001K, 31% free 9568K/13748K, paused 22ms+2ms, total 49ms
,D/dalvikvm( 6670): WAIT_FOR_CONCURRENT_GC blocked 16ms
,W/BluetoothAdapter( 5068): getBluetoothService() called with no BluetoothManagerCallback
,D/STATUSBAR-IconMerger( 2581): checkOverflow(336), More:false, Req:false Child:2
E/BluetoothServiceJni( 5068): SOCK FLAG = 3 ***********************
,W/System.err( 6670): java.io.FileNotFoundException: /system/etc/vold.fstab: open failed: ENOENT (No such file or directory)
,W/System.err( 6670): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 6670): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err( 6670): 	at java.util.Scanner.<init>(Scanner.java:158)
W/System.err( 6670): 	at java.util.Scanner.<init>(Scanner.java:138)
W/System.err( 6670): 	at pl.k2.droidoaudioteka.common.helpers.StorageOptions.readVoldFile(StorageOptions.java:107)
W/System.err( 6670): 	at pl.k2.droidoaudioteka.common.helpers.StorageOptions.determineStorageOptions(StorageOptions.java:31)
W/System.err( 6670): 	at pl.k2.droidoaudioteka.uipl.managers.impl.ResManager.<init>(ResManager.java:81)
W/System.err( 6670): 	at pl.k2.droidoaudioteka.uipl.managers.impl.ResManager.<init>(ResManager.java:129)
,W/System.err( 6670): 	at pl.k2.droidoaudioteka.ui.AudiotekaApplication.onCreate(AudiotekaApplication.java:171)
,W/System.err( 6670): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
,W/System.err( 6670): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
,W/System.err( 6670): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 6670): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
,W/System.err( 6670): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 6670): 	at android.os.Looper.loop(Looper.java:146)
,W/System.err( 6670): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
,W/System.err( 6670): 	at java.lang.reflect.Method.invokeNative(Native Method)
,W/System.err( 6670): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 6670): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
,W/System.err( 6670): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 6670): 	at dalvik.system.NativeStart.main(Native Method)
,W/System.err( 6670): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
,W/System.err( 6670): 	at libcore.io.Posix.open(Native Method)
,W/System.err( 6670): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
,W/System.err( 6670): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 6670): 	... 20 more
,W/System.err( 6670): file res dir: /data/data/pl.k2.droidoaudioteka/files
,W/System.err( 6670): Excternal dir: /mnt/sdcard
,D/GKI_LINUX( 5068): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,V/MaBo    ( 6670): preinstalledFolder externalSD nie istnieje /mnt/sdcard/Android/data/pl.k2.droidoaudioteka/_preinstalled
,D/dalvikvm( 6613): GC_CONCURRENT freed 2210K, 28% free 10103K/13964K, paused 6ms+3ms, total 161ms
,I/System.out( 6670): Katalog z preintalacją NIE istnieje!!!! /storage/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6670): Katalog z preintalacją NIE istnieje!!!! /mnt/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6670): moge zapisać w resDir?true
,V/MaBo    ( 6670): preinstalledFolder externalSD nie istnieje /mnt/sdcard/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6670): Katalog z preintalacją NIE istnieje!!!! /storage/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,I/System.out( 6670): Katalog z preintalacją NIE istnieje!!!! /mnt/emmc/Android/data/pl.k2.droidoaudioteka/_preinstalled
,W/GAV2    ( 6670): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/GAV2    ( 6670): Thread[main,5,main]: ExceptionReporter created, original handler is pl.k2.droidoaudioteka.common.helpers.AudiotekaExceptionHandler
,I/AUDIOTEKA_GA( 6670): init tracking...
,I/AUDIOTEKA_GA( 6670): app started!
,D/AuthorizationBluetoothService( 2851): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/BugSenseHandler( 6670): Registering default exceptions handler
,I/DownloadService( 6670): Tworzenie serwisu - onCreate()
,I/DownloadService( 6670): Start serwisu - onStart()
,I/BugSenseHandler( 6670): Registering default exceptions handler
,I/PlayerService( 6670): Tworzenie serwisu - onCreate()
,I/MediaFocusControl( 2404):   Remote Control   registerMediaButtonIntent() for PendingIntent{42e4e6f8: PendingIntentRecord{45f9ae08 pl.k2.droidoaudioteka broadcastIntent}}
,V/KeyguardUpdateMonitor( 2581): handleSetGenerationId(g=2, clear=true)
,V/AUDIOTEKA_MB( 6670): new AudioManagerFocusWrapper in playerservice oncreate
,I/PlayerService( 6670): Start serwisu - onStart()
,I/BugSenseHandler( 6670): Flushing...
,I/BugSenseHandler( 6670): Registering default exceptions handler
,I/BugSenseHandler( 6670): Flushing...
,I/BugSenseHandler( 6670): Registering default exceptions handler
,I/knox    ( 4982): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 4982): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,I/knox    ( 4982): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
,D/knox    ( 4982): KNOXAgentService : onCreate()
D/knox    ( 4982): KNOXAgentService : set alarms for deniallog and usage data upload
,D/knox    ( 4982): KNOXAgentService. startJobThread() start
D/knox    ( 4982): KNOXAgentService. JobThread()
,D/knox    ( 4982): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 4982): KNOXAgentService. startJobThread() wait
,I/SELinux ( 6712): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6712):  
,D/Tethering( 2404): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2404): interfaceStatusChanged wlan0, true
,E/Tethering( 2404): No numeric data
,I/ConnectivityService( 2404): defaultVal : 1, tetherEnabledInSettings : true
I/wpa_supplicant( 6668): wlan0: Setting scan request: 0 sec 100000 usec
D/Tethering( 2404): sendTetherStateChangedBroadcast 1, 0, 0
I/SELinux ( 6712): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6712):  
I/SELinux ( 6712):  
,I/SELinux ( 6712): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6712): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6712): >>>>> Normal User
,E/dalvikvm( 6712): >>>>> tv.peel.smartremote [ userId:0 | appId:10165 ]
,E/SELinux ( 6712): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/Tethering( 2404): interfaceLinkStateChanged wlan0, true
D/Tethering( 2404): interfaceStatusChanged wlan0, true
,D/knox    ( 4982): KNOXAgentService : onDestroy().
,D/knox    ( 4982): ModuleBase.cancelAllAlarmManageModule()
,D/NtpTrustedTime( 2404): forceRefresh() from cache miss
,D/NtpTrustedTime( 2404): forceRefresh Fail.
,V/NetworkStats( 2404): performPollLocked(flags=0x1)
I/wpa_supplicant( 6668): >>>>> Not GET KEY, IV <<<<<
I/wpa_supplicant( 6668): >>>>> Not GET KEY, IV <<<<<
I/wpa_supplicant( 6668): rfkill: Cannot open RFKILL control device
D/Tethering( 2404): interfaceLinkStateChanged p2p0, true
D/Tethering( 2404): interfaceStatusChanged p2p0, true
D/Tethering( 2404): interfaceLinkStateChanged p2p0, true
,D/Tethering( 2404): interfaceStatusChanged p2p0, true
,D/NtpTrustedTime( 2404): forceRefresh() from cache miss
,D/NtpTrustedTime( 2404): forceRefresh Fail.
,V/NetworkStats( 2404): performPollLocked() took 19ms
D/TimaKeyStoreProvider( 6712): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6712): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6712): Added TimaKesytore provider
,I/wpa_supplicant( 6668): CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 6668): P2P: initialized channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
I/wpa_supplicant( 6668): CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 6668): Skip scan - bUseNetwork false
,D/WifiStateMachine( 2404): skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
D/WifiNative( 2404): callSECApiString - ID [21]
I/wpa_supplicant( 6668): HOTSPOT20_ENABLE called
I/wpa_supplicant( 6668): wlan0: HS20_DISABLED_COMPLETE normal
,D/WifiNative( 2404): callSECApiInt - ID [65]
,D/dalvikvm( 6712): GC_CONCURRENT freed 2901K, 30% free 9549K/13628K, paused 3ms+2ms, total 33ms
,E/WifiConfigStore( 2404): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative( 2404): callSECApiBoolean - ID [13]
,I/wpa_supplicant( 6668): USE_NETWORK : USE_NETWORK ON
I/wpa_supplicant( 6668): reset timer : RESET_TIMER 0
I/wpa_supplicant( 6668): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 6668): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 6668): First Scan Start
,W/Settings( 5321): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/wpa_supplicant( 6668): Scan requested (ret=0) - scan timeout 30 seconds
,E/WifiStateMachine( 2404): Set the Nv default ccode
,I/System.out( 6670): Thread-594(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6670): Thread-599(ApacheHTTPLog):isShipBuild true
,D/WifiStateMachine( 2404): skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,E/WifiStateMachine( 2404): HS20_DISABLED_COMPLETEnormal
,I/System.out( 6670): Thread-599(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/WifiP2pService( 2404): P2pDisabledState{ what=131203 }
,D/CommandListener( 1916): Setting iface cfg
,D/CommandListener( 1916): Trying to bring up p2p0
,D/WifiMonitor( 2404): startMonitoring(p2p0) with mConnected = true
,I/System.out( 6670): Thread-594(ApacheHTTPLog):isShipBuild true
D/WifiP2pService( 2404): P2pEnablingState
D/WifiP2pService( 2404): P2pEnablingState{ what=147457 }
D/WifiP2pService( 2404): P2p socket connection successful
,D/WifiP2pService( 2404): P2pEnabledState
E/WifiStateMachine( 2404): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,I/System.out( 6670): Thread-594(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/QuickConnect[1.1][2] ( 5042): SconnectManager.INetworkStateListener, onEnabled - mNetworkState : 4
,D/WifiP2pService( 2404): sending p2p connection changed broadcast: IDLE
D/WifiDisplayController( 2404): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
D/WifiDisplayController( 2404): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 2404): disconnect
D/WifiDisplayController( 2404): updateConnection
D/WifiDisplayController( 2404): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,D/WifiDisplayAdapter( 2404): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/QuickConnect[1.1][2] ( 5042): P2pHelper.onReceive - ACTION_WIFI_DISPLAY_STATUS_CHANGED :0
,D/QuickConnect[1.1][2] ( 5042): P2pHelper.onReceive - P2P_CONNECTION_CHANGED : 
D/WifiDisplayAdapter( 2404): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
W/WifiP2pStateTracker( 2404): WifiP2pStateReceiver : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
D/WifiDisplayController( 2404): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=NetworkInfo: type: WIFI_P2P[], state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/wpa_supplicant( 6668): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,D/QuickConnect[1.1][2] ( 5042): SconnectManager.INetworkStateListener, onDisconnected - networkType : 4
,D/WifiDisplayController( 2404): Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: S5mini-1
D/WifiDisplayController( 2404):  deviceAddress: 02:f4:6f:30:e0:6d
D/WifiDisplayController( 2404):  primary type: 10-0050F204-5
D/WifiDisplayController( 2404):  secondary type: null
D/WifiDisplayController( 2404):  wps: 0
D/WifiDisplayController( 2404):  grpcapab: 0
D/WifiDisplayController( 2404):  devcapab: 0
D/WifiDisplayController( 2404):  status: 3
D/WifiDisplayController( 2404):  wfdInfo: null
D/WifiDisplayController( 2404):  groupownerAddress: null
D/WifiDisplayController( 2404):  GOdeviceName: null
D/WifiDisplayController( 2404):  interfaceAddress: 
D/WifiDisplayController( 2404):  SConnectInfo : null
,D/WifiP2pService( 2404): DeviceAddress: 02:e0:6d
,I/System.out( 6670): pool-1-thread-1 calls detatch()
W/BugSenseHandler( 6670): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
I/System.out( 6670): pool-1-thread-2 calls detatch()
,W/BugSenseHandler( 6670): Transmitting ping Exception Unable to resolve host "ticks2.bugsense.com": No address associated with hostname
D/WifiP2pService( 2404): sending p2p persistent groups changed broadcast
D/WifiP2pService( 2404): InactiveState
,D/QuickConnect[1.1][2] ( 5042): P2pHelper.requestGroupInfo  - onGroupInfoAvailable- null
D/WifiP2pService( 2404): InactiveState{ what=139287 }
D/WifiP2pService( 2404): P2pEnabledState{ what=139287 }
D/WifiP2pService( 2404): DefaultState{ what=139287 }
,W/ContextImpl( 5526): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,D/LocalBluetoothProfileManager( 5526): Adding local A2DP profile
,D/LocalBluetoothProfileManager( 5526): Adding local HEADSET profile
W/ContextImpl( 5526): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothA2dp.doBind:221 android.bluetooth.BluetoothA2dp.<init>:214 android.bluetooth.BluetoothAdapter.getProfileProxy:1412 
,E/BluetoothHeadset( 5526): BTStateChangeCB is registed
,E/BluetoothHeadset( 5526): BluetoothHeadset service is binded
W/ContextImpl( 5526): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothHeadset.doBind:304 android.bluetooth.BluetoothHeadset.<init>:297 android.bluetooth.BluetoothAdapter.getProfileProxy:1409 
,D/Bluetoothsap( 5526): bindService called to Bluetooth SAP Service
W/ContextImpl( 5526): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,W/ContextImpl( 5526): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1415 
,W/ContextImpl( 5526): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPan.doBind:173 android.bluetooth.BluetoothPan.<init>:162 android.bluetooth.BluetoothAdapter.getProfileProxy:1418 
D/LocalBluetoothProfileManager( 5526): PANU : true
D/LocalBluetoothProfileManager( 5526): Adding local MAP profile
,D/BluetoothMap( 5526): Create BluetoothMap proxy object
W/ContextImpl( 5526): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1424 
,W/ContextImpl( 5526): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:68 
,W/ContextImpl( 5526): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1930 android.content.ContextWrapper.bindService:529 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
D/Bluetoothsap( 5526): bindService called to Bluetooth SAP Service
D/LocalBluetoothProfileManager( 5526): LocalBluetoothProfileManager construction complete
,D/DockEventReceiver( 5526): finishStartingService: stopping service
,D/BluetoothNotiBroadcastReceiver( 5526): onReceive
,D/BluetoothA2dp( 5526): Proxy object connected
,D/BtConfig.SecureMode( 5068): isSecureModeOn:false
,D/A2dpProfile( 5526): Bluetooth service connected
,D/AuthorizationBluetoothService( 2851): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 2851): Proximity feature is not enabled.
,D/HeadsetProfile( 5526): Bluetooth service connected
,D/Bluetoothsap( 5526): BluetoothSAP Proxy object connected
D/SapProfile( 5526): Bluetooth service connected
,D/Bluetoothsap( 5526): getConnectedDevices()
,D/BluetoothInputDevice( 5526): Proxy object connected
,D/HidProfile( 5526): Bluetooth service connected
,D/BluetoothPan( 5526): BluetoothPAN Proxy object connected
D/PanProfile( 5526): Bluetooth service connected
,W/BluetoothAdapter( 5068): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 5068): SOCK FLAG = 0 ***********************
,D/GKI_LINUX( 5068): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,I/BtOppRfcommListener( 5068): Accept thread started.
,D/BluetoothMap( 5526): Proxy object connected
,D/MapProfile( 5526): Bluetooth service connected
,D/BluetoothPbap( 5526): Proxy object connected
,D/PbapServerProfile( 5526): Bluetooth service connected
D/Bluetoothsap( 5526): BluetoothSAP Proxy object connected
D/SapProfile( 5526): Bluetooth service connected
,D/Bluetoothsap( 5526): getConnectedDevices()
,I/ActivityManager( 2404): Killing 5678:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,I/knox    ( 4982): MainReceiver.onReceive() : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
W/ContextImpl( 4982): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
,D/knox    ( 4982): GSLBThreadManager.NetworkStateChanged : NETWORK_STATE_CHAGED. Upload Call Log Data
,I/knox    ( 4982): MainReceiver.onReceive() END - - - - - : Intent { act=android.net.wifi.WIFI_STATE_CHANGED flg=0x4000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver (has extras) }
D/knox    ( 4982): KNOXAgentService : onCreate()
,D/knox    ( 4982): KNOXAgentService : set alarms for deniallog and usage data upload
,D/knox    ( 4982): KNOXAgentService. startJobThread() start
,D/knox    ( 4982): KNOXAgentService. JobThread()
D/knox    ( 4982): KNOXAgentService. JobThread. notifyAll().
,D/knox    ( 4982): KNOXAgentService. startJobThread() wait
,D/knox    ( 4982): KNOXAgentService : onDestroy().
,D/knox    ( 4982): ModuleBase.cancelAllAlarmManageModule()
,D/NearbySettings( 5526): MountReceiver.onReceive - Create HandlerThread
,D/NearbySettings( 5526): MountReceiver.onReceive - Start HandlerThread
,D/NearbySettings( 5526): MountReceiver.onReceive - Create mPrefHandler
,D/NearbySettings( 5526): MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,V/NearbySettings( 5526): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5526): DMSUtil.isNetworkConnected - WIFI: IDLE
I/NearbySettings( 5526): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5526): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5526): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 5526): MountReceiver.mPrefHandler - 7002
,D/FileShare-Server( 5921): ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,D/FileShare-Server( 5921): ServerBroadcastReceiver.onReceive - netInfo.getDetailedState() IDLE
,D/GKI_LINUX( 5068): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,I/wpa_supplicant( 6668): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,I/wpa_supplicant( 6668): nl80211: Received scan results (7 BSSes)
,I/wpa_supplicant( 6668): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 6668): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 6668): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/Tethering( 2404): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2404): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 6668): P2P: updated channels: 81:1,2,3,4,5,6,7,8,9,10,11,12,13 115:36,40,44,48
,E/WifiStateMachine( 2404): Error! unhandled message{ when=-5ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,I/wpa_supplicant( 6668): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,D/Tethering( 2404): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2404): interfaceStatusChanged wlan0, true
D/Tethering( 2404): interfaceLinkStateChanged wlan0, true
D/Tethering( 2404): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 6668): Associated with C0.AA.48
D/Tethering( 2404): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2404): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 6668): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 6668): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 6668): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 6668): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 6668): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2404): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2404): interfaceStatusChanged wlan0, true
,D/WifiNative( 2404): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 6746): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6746):  
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 6746): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6746):  
I/SELinux ( 6746):  
,I/SELinux ( 6746): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6746): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6746): >>>>> Normal User
,E/dalvikvm( 6746): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 6746): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 6746): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6746): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6746): Added TimaKesytore provider
,D/WifiP2pService( 2404): InactiveState{ what=143375 }
,D/WifiP2pService( 2404): P2pEnabledState{ what=143375 }
,D/dalvikvm( 6746): GC_CONCURRENT freed 2985K, 31% free 9585K/13748K, paused 3ms+1ms, total 24ms
,D/dalvikvm( 6746): WAIT_FOR_CONCURRENT_GC blocked 11ms
,I/System.out( 6746): Inside WakeupProvider
,I/System.out( 6746): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 6746): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 6746): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 6746): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,I/dhcpcd  ( 6760): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 6760): bssid match
,D/NearbySettings( 5526): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 5526): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 5526): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
,I/NearbySettings( 5526): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5526): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5526): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 5526): MountReceiver.mPrefHandler - 7002
,I/ActivityManager( 2404): Killing 5798:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
D/DialogFlow( 6746): initQueue()
,D/PackageManager( 2404): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/WifiP2pService( 2404): InactiveState{ what=143375 }
,D/WifiP2pService( 2404): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2404): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2404): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2404): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2404): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2404): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2404): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2404): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2404): evaluateTrafficStatsPolling
D/ConnectivityService( 2404): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2404): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2404): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
D/NearbySettings( 5526): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 5526): MountReceiver.onReceive - Keep current state
D/ConnectivityService( 2404): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,D/NearbySettings( 5526): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 5526): DMSUtil.isNetworkConnected - flag-null, state-null
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,I/NearbySettings( 5526): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 5526): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 5526): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 5526): MountReceiver.onReceive - Keep current state
,V/NetworkStats( 2404): updateIfacesLocked()
,V/NetworkStats( 2404): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2404): forceRefresh() from cache miss
,W/ProcessCpuTracker( 2404): Skipping unknown process pid 6796
,V/NetworkStats( 2404): performPollLocked() took 18ms
,D/NtpTrustedTime( 2404): requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1451923543051 mCachedNtpElapsedRealtime : 155133 mCachedNtpCertainty : 7
,D/NtpTrustedTime( 2404): currentTimeMillis() cache hit
D/NtpTrustedTime( 2404): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2404): currentTimeMillis() cache hit
D/NtpTrustedTime( 2404): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2404): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2404): currentTimeMillis() cache hit
,V/NetworkStats( 2404): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NearbySettings( 5526): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 5526): MountReceiver.onReceive - Keep current state
,I/SurfaceFlinger( 1921): id=20 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 2404): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2404
,D/Tethering( 2404): Tethering got CONNECTIVITY_ACTION
,D/CaptivePortalTracker( 2404): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
,D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
D/NtpTrustedTime( 2404): currentTimeMillis() cache hit
D/        ( 2404): Setting time of day to sec=1451923543
D/        ( 2404): Trying to open a file
D/Tethering( 2404): MasterInitialState.processMessage what=3
D/        ( 2404): File Open Success
D/        ( 2404): File Close Success
,I/        ( 2404): DRM_TIME_PATH CHMOD 660 for resetState done 
V/AlarmManager( 2404): waitForAlarm result :65536
,I/PCWCLIENTTRACE_PushUtil( 6282): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6282): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6282): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6282): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/DBG_DM  ( 4656): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/DBG_DM  ( 4656): [3.19.140541][Line:609][onReceive] ----------- XEVENT_DM_INIT WIFI ok
,I/SELinux ( 6808): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6808):  
,I/DBG_DM  ( 4656): [3.19.140541][Line:214][xdmAgentTaskHandler] XEVENT_DM_INIT
,I/DBG_DM  ( 4656): [3.19.140541][Line:432][xdmInitAdpWaitSystemRootingCheck] Check completed.
,I/DBG_DM  ( 4656): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/SELinux ( 6808): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6808):  
I/SELinux ( 6808):  
I/SELinux ( 6808): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 6808): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6808): >>>>> Normal User
E/dalvikvm( 6808): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 6808): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_SET
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
D/StatusBar-DoNotDistrub( 2581): Received intent with android.intent.action.TIME_SET action
,D/StatusBar-DoNotDistrub( 2581): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
D/NotificationMgr( 2753): updateNotificationsAtStartup()...
D/NotificationMgr( 2753): - start call log query...
W/Settings( 2404): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/TimaKeyStoreProvider( 6808): in addTimaSignatureService
,E/Parcel  ( 2404): nm 23
,I/AudioService( 2404): getStreamVolume 5 index 110
I/PrGenericPlugin( 1925): [A] ENTER onAcquireDrmInfo : 0x961
,I/PrGenericPlugin( 1925): [A] LEAVE onAcquireDrmInfo : 0x961
,I/DrmEventService( 2404):  no response from SecureClock 
D/StatusBar-DoNotDistrub( 2581): sendBroadcast android.intent.action.DORMANT_MODE_OFF
,D/TimaKeyStoreProvider( 6808): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6808): Added TimaKesytore provider
,I/SensorManagerA( 2404): getReportingMode :: sensor.mType = 5
D/Sensors ( 2404): LightSensor setDelay = 200000000
,D/Sensors ( 2404): LightSensor setSensorDelay = 200000000
D/StatusBar-DoNotDistrub( 2581): The STREAM NOTIFICATION volume is 0
D/STATUSBAR-StatusBarManagerService( 2404): manageDisableList what=0x0 pkg=com.android.systemui
D/STATUSBAR-NotificationService( 2404): received android.intent.action.DORMANT_MODE_OFF
D/LightsService( 2404): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2404) 
,D/LightsService( 2404): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/Sensors ( 2404): Light sensor flush: not enabled 0
D/Sensors ( 2404): LightSensor enable = 1
D/Sensors ( 2404): LightSensor enableSensor = 1
D/SensorManager( 2404): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/NotificationMgr( 2753): call log query complete.
D/NotificationMgr( 2753): call log cursor count : 0
,D/NotificationMgr( 2753): call log cursor count2 : null
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,I/SELinux ( 6822): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6822):  
,I/DBG_DM  ( 4656): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 4656): [3.19.140541][Line:78][xdmFeatureGetBearerSettingFromCSCFotaDataBase] 
,I/SELinux ( 6822): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6822):  
I/SELinux ( 6822):  
,I/SELinux ( 6822): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6822): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 6822): >>>>> Normal User
,E/dalvikvm( 6822): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
,E/SELinux ( 6822): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 6822): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6822): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6822): Added TimaKesytore provider
,I/DBG_DM  ( 4656): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
I/dalvikvm( 4656): Total arena pages for JIT: 11
,I/dalvikvm( 4656): Total arena pages for JIT: 12
,D/LightsService( 2404): [SvcLED]  onSensorChanged::light value = 0
D/Sensors ( 2404): LightSensor enable = 0
D/Sensors ( 2404): LightSensor enableSensor = 0
,D/SensorManager( 2404): unregisterListener ::   
D/LightsService( 2404): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/dalvikvm( 4656): Total arena pages for JIT: 13
I/dalvikvm( 4656): Total arena pages for JIT: 14
I/dalvikvm( 4656): Total arena pages for JIT: 15
I/dalvikvm( 4656): Total arena pages for JIT: 16
I/dalvikvm( 4656): Total arena pages for JIT: 17
,I/DBG_DM  ( 4656): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,D/dalvikvm( 6808): GC_CONCURRENT freed 3007K, 31% free 9569K/13748K, paused 3ms+1ms, total 32ms
,D/dalvikvm( 6808): WAIT_FOR_CONCURRENT_GC blocked 28ms
,W/dalvikvm( 2736): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2736): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/DBG_DM  ( 4656): [3.19.140541][Line:5949][xdbGetFUMOInitiatedType] Initiated Type: 2
,I/DBG_DM  ( 4656): [3.19.140541][Line:119][xdmInitAdpEXTInit] nStatus [220]
,W/dalvikvm( 2736): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 2736): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 2736): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2736): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 2736): Using platform SSLCertificateSocketFactory
,I/DBG_DM  ( 4656): [3.19.140541][Line:463][xdmGetEnableLiveDemoFromCSCFeature] enable LiveDemo : false
,E/DBG_DM  ( 4656): Warning!!! [3.19.140541][Line:65][xdmInitAdpGetSIMLockState] SIM Status is not ready
,I/DBG_DM  ( 4656): [3.19.140541][Line:261][xdmInitAdpEXTInit] XDL_STATE_READY_TO_UPDATE
,D/dalvikvm( 6822): GC_CONCURRENT freed 2993K, 31% free 9571K/13740K, paused 3ms+1ms, total 122ms
,D/dalvikvm( 6822): WAIT_FOR_CONCURRENT_GC blocked 117ms
,I/DBG_DM  ( 4656): [3.19.140541][Line:769][xdmUIEvent] XUI_DL_UPDATE_START
,I/DBG_DM  ( 4656): [3.19.140541][Line:369][handleMessage] event ->214
,I/DBG_DM  ( 4656): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 4656): [3.19.140541][Line:271][xdmAgentTaskHandler] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 4656): [3.19.140541][Line:2008][xdmCallUiFotaInstall] 
,I/DBG_DM  ( 4656): [3.19.140541][Line:1854][xdmAgentCheckResumeNoti] 
,I/DBG_DM  ( 4656): [3.19.140541][Line:318][xdmBroadcastGetIsSavedNfcMode] m_IsSavedNfcMode : false
,I/DBG_DM  ( 4656): [3.19.140541][Line:546][xuiAdpGetUpdateReport] Get bUpdateReport = false
,I/DBG_DM  ( 4656): [3.19.140541][Line:890][xdmUnRegisterBatteryReceiver] 
,E/DBG_DM  ( 4656): Warning!!! [3.19.140541][Line:898][xdmUnRegisterBatteryReceiver] didn't register
W/ContextImpl( 4656): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 com.wssyncmldm.XDMService.xdmCallUiFotaInstall:2023 com.wssyncmldm.XDMService$1.handleMessage:372 android.os.Handler.dispatchMessage:102 
,E/DBG_DM  ( 4656): Warning!!! [3.19.140541][Line:899][xdmUnRegisterBatteryReceiver] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.XDMService$3@4238fa10
,I/DBG_DM  ( 4656): [3.19.140541][Line:729][xdmUIEvent] XUI_DL_UPDATE_CONFIRM
,I/DBG_DM  ( 4656): [3.19.140541][Line:1320][xdmCheckIdleScreen] Idle Screen : false
,I/dalvikvm( 4656): Total arena pages for JIT: 18
,I/DBG_DM  ( 4656): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4372, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2404): stay LED for fully charged
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/DBG_DM  ( 4656): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,E/dalvikvm( 6822): Could not find class 'android.app.Notification$Action$Builder', referenced from method b.a
,W/dalvikvm( 6822): VFY: unable to resolve new-instance 406 (Landroid/app/Notification$Action$Builder;) in Lb;
,D/dalvikvm( 6822): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm( 6822): Unable to resolve superclass of Lal; (749)
,I/SELinux ( 6844): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6844):  
W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2404): sendNotification(1) - 4
W/ResourceType( 2581): Attempt to retrieve bag 0x01030068 which is invalid or in a cycle.
W/ResourceType( 2581): Attempt to retrieve bag 0x01030067 which is invalid or in a cycle.
,D/ProgressBar( 2581): setProgressDrawable drawableHeight = 12
,I/HarmonyEASService( 2404): Updating for all 1
,W/dalvikvm( 6822): Link of class 'Lal;' failed
E/dalvikvm( 6822): Could not find class 'al', referenced from method b.a
W/dalvikvm( 6822): VFY: unable to resolve new-instance 304 (Lal;) in Lb;
,D/dalvikvm( 6822): VFY: replacing opcode 0x22 at 0x0006
,W/dalvikvm( 6822): Unable to resolve superclass of Lan; (749)
W/dalvikvm( 6822): Link of class 'Lan;' failed
E/dalvikvm( 6822): Could not find class 'an', referenced from method b.a
W/dalvikvm( 6822): VFY: unable to resolve new-instance 358 (Lan;) in Lb;
,D/dalvikvm( 6822): VFY: replacing opcode 0x22 at 0x002a
I/SELinux ( 6844): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6844):  
I/SELinux ( 6844):  
,I/SELinux ( 6844): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/GAV2    ( 6670): Thread[GAThread,5,main]: connecting to Analytics service
,E/SELinux ( 6844): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6844): >>>>> Normal User
,E/dalvikvm( 6844): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,W/ContextImpl( 6670): Implicit intents with startService are not safe: Intent { act=com.google.android.gms.analytics.service.START (has extras) } android.content.ContextWrapper.bindService:529 com.google.analytics.tracking.android.AnalyticsGmsCoreClient.connect:82 com.google.analytics.tracking.android.GAServiceProxy.connectToService:279 
,E/SELinux ( 6844): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/ProgressBar( 2581): setProgressDrawable drawableHeight = 12
,I/GAV2    ( 6670): Thread[GAThread,5,main]: connect: bindService returned true for Intent { act=com.google.android.gms.analytics.service.START (has extras) }
I/dalvikvm( 6822): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method b.a
,W/dalvikvm( 6822): VFY: unable to resolve virtual method 5407: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 6822): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 6822): Could not find method android.view.View.getTransitionName, referenced from method b.a
W/dalvikvm( 6822): VFY: unable to resolve virtual method 5231: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 6822): VFY: replacing opcode 0x6e at 0x0006
,I/GAV2    ( 6670): Thread[GAThread,5,main]: No campaign data found.
,D/GAV2    ( 6670): Thread[main,5,main]: service connected, binder: android.os.BinderProxy@42449908
,D/GAV2    ( 6670): Thread[main,5,main]: bound to service
,I/GAV2    ( 6670): Thread[main,5,main]: Connected to service
D/PhoneStatusBar( 2581): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@422df810
,I/GAV2    ( 6670): Thread[GAThread,5,main]: putHit called
,I/GAV2    ( 6670): Thread[GAThread,5,main]: Sending hit to service
,W/dalvikvm( 6822): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
,D/TimaKeyStoreProvider( 6844): in addTimaSignatureService
,E/dalvikvm( 6822): Could not find class 'android.app.RemoteInput[]', referenced from method b.a
W/dalvikvm( 6822): VFY: unable to resolve new-array 12200 ([Landroid/app/RemoteInput;) in Lb;
,D/dalvikvm( 6822): VFY: replacing opcode 0x23 at 0x0005
,D/TimaKeyStoreProvider( 6844): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6844): Added TimaKesytore provider
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 6822): DexOpt: unable to opt direct call 0x090f at 0x0e in Lb;.a
W/dalvikvm( 6822): Unable to resolve superclass of Lal; (749)
W/dalvikvm( 6822): Link of class 'Lal;' failed
,D/dalvikvm( 6822): DexOpt: unable to opt direct call 0x068d at 0x08 in Lb;.a
,W/dalvikvm( 6822): Unable to resolve superclass of Lan; (749)
,W/dalvikvm( 6822): Link of class 'Lan;' failed
D/dalvikvm( 6822): DexOpt: unable to opt direct call 0x0802 at 0x2c in Lb;.a
,D/dalvikvm( 6822): DexOpt: unable to opt direct call 0x0957 at 0x13 in Lb;.a
,I/dalvikvm( 6822): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method dyp.a
W/dalvikvm( 6822): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6822): VFY: replacing opcode 0x6e at 0x000d
,I/SELinux ( 6862): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6862):  
,I/SELinux ( 6862): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6862):  
I/SELinux ( 6862):  
,I/SELinux ( 6862): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6862): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 6862): >>>>> Normal User
,E/dalvikvm( 6862): >>>>> com.android.chrome [ userId:0 | appId:10085 ]
,E/SELinux ( 6862): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/dalvikvm( 6822): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6822): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6822): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 6822): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 6822): VFY: unable to resolve instance field 36
,D/dalvikvm( 6822): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 6822): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 6822): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 6822): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 6822): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 6822): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 6822): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4230dd68
,D/dalvikvm( 6822): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4230dd68
,D/dalvikvm( 6822): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4230dd68, skipping init
,D/dalvikvm( 6822): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4230dd68
,D/TimaKeyStoreProvider( 6862): in addTimaSignatureService
,D/dalvikvm( 6822): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4230dd68
,V/JNIHelp ( 6822): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/TimaKeyStoreProvider( 6862): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6862): Added TimaKesytore provider
,D/dalvikvm( 2404): GC_EXPLICIT freed 2844K, 72% free 24623K/87680K, paused 9ms+18ms, total 209ms
,D/libgps  ( 2404): agps_ril_update_network_state: Waiting for IPC connection...
,D/dalvikvm( 6844): GC_CONCURRENT freed 2997K, 31% free 9567K/13740K, paused 7ms+5ms, total 39ms
,D/dalvikvm( 6844): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/dalvikvm( 3286): GC_CONCURRENT freed 2049K, 21% free 12395K/15616K, paused 20ms+6ms, total 86ms
,D/dalvikvm( 6862): GC_CONCURRENT freed 3000K, 31% free 9567K/13744K, paused 3ms+2ms, total 38ms
,D/dalvikvm( 6862): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 6822): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4230dd68
,D/dalvikvm( 6822): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x4230dd68
,D/dalvikvm( 6822): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4230dd68
,D/dalvikvm( 6822): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4230dd68
,D/btif_config_util( 5068): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,I/dalvikvm( 2736): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 2736): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2736): VFY: replacing opcode 0x6e at 0x003d
,I/SELinux ( 6886): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6886):  
,I/SELinux ( 6886): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6886):  
I/SELinux ( 6886):  
,I/SELinux ( 6886): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6886): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6886): >>>>> Normal User
,E/dalvikvm( 6886): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 6886): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1922): GC_EXPLICIT freed 42K, 12% free 9504K/10724K, paused 2ms+4ms, total 31ms
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9504K/10724K, paused 3ms+3ms, total 26ms
,D/TimaKeyStoreProvider( 6886): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6886): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6886): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9504K/10724K, paused 2ms+3ms, total 26ms
,I/ProviderInstaller( 6822): Installed default security provider GmsCore_OpenSSL
,I/System.out( 2736): Thread-122(HTTPLog):isShipBuild true
,I/System.out( 2736): Thread-122(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/dalvikvm( 6822): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 6822): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6822): VFY: replacing opcode 0x6e at 0x000d
,E/YouTube MDX( 6822): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/dalvikvm( 6886): GC_CONCURRENT freed 2997K, 31% free 9573K/13744K, paused 3ms+1ms, total 34ms
,D/dalvikvm( 6886): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/dalvikvm( 6822): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
,W/dalvikvm( 6822): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 6822): VFY: replacing opcode 0x71 at 0x004e
,D/KLMS-2.3.201 : ( 6886): KLMSValidator() : checkQATesting()
,D/dalvikvm( 6822): DexOpt: --- BEGIN 'ads-1611533435.jar' (bootstrap=0) ---
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 6822): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/KLMS-2.3.201 : ( 6886): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1451923545541
,I/KLMS-2.3.201 : ( 6886): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/ActivityManager( 2404): Killing 5822:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 6925): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6925):  
D/dalvikvm( 6822): GC_CONCURRENT freed 1848K, 22% free 10721K/13740K, paused 6ms+8ms, total 53ms
I/LocationTagReadyService( 3443): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3443): [Slink platform] The state of Slink geocode service is true
,I/SELinux ( 6925): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6925):  
I/SELinux ( 6925):  
,I/SELinux ( 6925): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/dalvikvm( 6844): Total arena pages for JIT: 11
,E/SELinux ( 6925): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 6925): >>>>> Normal User
E/dalvikvm( 6925): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,I/dalvikvm( 6844): Total arena pages for JIT: 12
,I/dalvikvm( 6844): Total arena pages for JIT: 13
I/dalvikvm( 6844): Total arena pages for JIT: 14
,I/dalvikvm( 6844): Total arena pages for JIT: 15
,I/dalvikvm( 6844): Total arena pages for JIT: 16
E/SELinux ( 6925): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/dalvikvm( 6844): Total arena pages for JIT: 17
,D/GalaxyFinderApplication( 3443): [Slink platform] The state of Slink geocode service is true
,D/TimaKeyStoreProvider( 6925): in addTimaSignatureService
,D/TimaKeyStoreProvider( 6925): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6925): Added TimaKesytore provider
,D/GalaxyFinderApplication( 3443): [Slink platform] The state of Slink geocode service is true
,D/PackageManager( 2404): [MSG] SEND_PENDING_BROADCAST
,D/PackageManager( 2404): Sending to user 0: act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000000 Bundle[{android.intent.extra.changed_component_name=com.sec.enterprise.knox.cloudmdm.smdms.core.CoreReceiver, android.intent.extra.DONT_KILL_APP=true, android.intent.extra.UID=10171, android.intent.extra.changed_component_name_list=[Ljava.lang.String;@460d7e38, com.samsung.android.intent.extra.SECRET_APP=false, android.intent.extra.user_handle=0}]
,I/InputReader( 2404): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 2404):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2404):   Scheme: "sms"
I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 6925): GC_CONCURRENT freed 2990K, 31% free 9577K/13744K, paused 6ms+2ms, total 79ms
,D/dalvikvm( 6925): WAIT_FOR_CONCURRENT_GC blocked 73ms
,I/PackageManager( 2404):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2404):   Scheme: "smsto"
,I/PackageManager( 2404):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2404):   Scheme: "mms"
I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 6940): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6940):  
,D/SO_AGENT( 6925): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,D/RegisteredServicesCache( 2758): empty dynamic service
,I/SELinux ( 6940): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6940):  
I/SELinux ( 6940):  
,I/SELinux ( 6940): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6940): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6940): >>>>> Normal User
,E/dalvikvm( 6940): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 6940): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/libgps  ( 2404): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2404): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2404): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2404): agps_ril_update_network_availability: Waiting for IPC connection...
I/PackageManager( 2404):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2404):   Scheme: "mmsto"
,I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 6916): DexOpt: load 4ms, verify+opt 155ms, 194052 bytes
,I/SO_AGENT( 6925): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 3571): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,D/TimaKeyStoreProvider( 6940): in addTimaSignatureService
,I/PackageManager( 2404):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2404):   Scheme: "sms"
I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/TimaKeyStoreProvider( 6940): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6940): Added TimaKesytore provider
,I/dalvikvm( 6822): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm( 6822): VFY: unable to resolve virtual method 2614: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 6822): VFY: replacing opcode 0x6e at 0x0002
,I/dalvikvm( 6822): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
,I/PackageManager( 2404):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2404):   Scheme: "smsto"
I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 6822): DexOpt: --- END 'ads-1611533435.jar' (success) ---
,D/dalvikvm( 6822): DEX prep '/data/data/com.google.android.youtube/cache/ads-1611533435.jar': unzip in 0ms, rewrite 644ms
,I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2404):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2404):   Scheme: "mms"
,I/PackageManager( 2404):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2404):   Scheme: "mmsto"
I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 6957): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6957):  
,D/dalvikvm( 6940): GC_CONCURRENT freed 2994K, 31% free 9575K/13748K, paused 3ms+10ms, total 43ms
,D/dalvikvm( 6940): WAIT_FOR_CONCURRENT_GC blocked 31ms
,I/SELinux ( 6957): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6957):  
I/SELinux ( 6957):  
,I/SELinux ( 6957): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 6957): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6957): >>>>> Normal User
,E/dalvikvm( 6957): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 6957): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 6393): No JNI_OnLoad found in /system/lib/libsecure_storage_jni.so 0x4227d428, skipping init
,I/SA      ( 6499): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,D/TimaKeyStoreProvider( 6957): in addTimaSignatureService
,W/dalvikvm( 6822): VFY: unable to resolve virtual method 2615: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 6822): VFY: replacing opcode 0x6e at 0x0002
,D/TimaKeyStoreProvider( 6957): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 6957): Added TimaKesytore provider
,I/dalvikvm( 6822): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 6822): VFY: unable to resolve virtual method 2622: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 6822): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 6822): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm( 6822): VFY: unable to resolve virtual method 2623: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 6822): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 6822): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method agv.getLeanbackLaunchIntentForPackage
W/dalvikvm( 6822): VFY: unable to resolve virtual method 2639: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm( 6822): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 6822): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method agv.getPackageInstaller
W/dalvikvm( 6822): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 6822): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 6822): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method agv.getUserBadgedDrawableForDensity
W/dalvikvm( 6822): VFY: unable to resolve virtual method 2659: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 6822): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 6822): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method agv.getUserBadgedIcon
W/dalvikvm( 6822): VFY: unable to resolve virtual method 2660: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
D/dalvikvm( 6822): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm( 6822): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method agv.getUserBadgedLabel
W/dalvikvm( 6822): VFY: unable to resolve virtual method 2661: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
,D/dalvikvm( 6822): VFY: replacing opcode 0x6e at 0x0002
,I/SecureStorage( 6393): [INFO]: SPID(0x00000000)Processing data
I/SecureStorage( 1965): [INFO]: SPID(0x00000004)Credentials: uid 1000, gid 1000, pid 6393
,I/SecureStorage( 1965): [INFO]: SPID(0x00000004)Received function mask & code: 00000106
,E/WifiStateMachine( 2404): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/ActivityManager( 2404): Killing 5851:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,D/dalvikvm( 6957): GC_CONCURRENT freed 3003K, 31% free 9568K/13748K, paused 33ms+1ms, total 60ms
,D/dalvikvm( 6957): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/SA      ( 6499): [BDLM] already registered in spp
,I/SA      ( 6499): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,V/KVNProvider( 6957): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 6957): getFindoCursor query string : 
,I/SA      ( 6499): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,V/KVNProvider( 6957): getTagSearchCursor() tagSearchCursor count : 0
,I/ActivityManager( 2404): Killing 5501:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,I/SA      ( 6499): [SLFUCHKMGR] constructor called
,I/SA      ( 6499): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 6499): [OR] == isSIMCardReady false ==
,I/SA      ( 6499): [SCU] == networkStateCheck == true
I/SA      ( 6499): [DM] getCountryCodeFromCSC : PL
I/SA      ( 6499): isChinaCountryCode : false
,I/SA      ( 6499): [OR] == networkStateCheck true ==
,I/SA      ( 6499): [OR] GetMyCountryZoneTask
,I/SA      ( 6499): [OR] onReceive END
,I/SA      ( 6499): [SRS] prepareGetMyCountryZone
I/ActivityManager( 2404): Killing 5712:com.android.calendar/u0a144 (adj 15): empty #43
,I/SA      ( 6499): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/ActivityManager( 2404): Killing 5731:com.android.providers.calendar/u0a45 (adj 15): empty #43
I/SA      ( 6499): [SSP] query invoked
,I/SurfaceFlinger( 1921): id=20 Removed Uoast (10/11)
,I/SurfaceFlinger( 1921): id=20 Removed Uoast (-2/11)
,D/PowerManagerService( 2404): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2404) eventTime = 158662
,D/PowerManagerService( 2404): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2404 (0x0)
,D/PowerManagerService( 2404): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2404, ws=WorkSource{1000}) (elapsedTime=3495)
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
I/SELinux ( 6977): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 6977):  
,W/ContextImpl( 6822): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,I/System.out( 6844): Thread-601(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 6822): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
I/SurfaceFlinger( 1921): id=21 createSurf (1x1),1 flag=4, Uoast
I/SELinux ( 6977): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 6977):  
I/SELinux ( 6977):  
I/SELinux ( 6977): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
E/SELinux ( 6977): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 6977): >>>>> Normal User
E/dalvikvm( 6977): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 6977): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 6822): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,I/SA      ( 6499): [TPMU] GetMccFromDB : null
I/SA      ( 6499): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6499): [TPM] isNoProxy(default) : true
,D/TimaKeyStoreProvider( 6977): in addTimaSignatureService
D/PowerManagerService( 2404): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2404
,D/TimaKeyStoreProvider( 6977): Cannot add TimaSignature Service, License check Failed
,I/SA      ( 6499): [RC New] Execute method=[GET] start
,D/ActivityThread( 6977): Added TimaKesytore provider
,W/InstanceID/Rpc( 6822): Found 10012
,I/System.out( 6844): Thread-601(ApacheHTTPLog):isShipBuild true
E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,I/System.out( 6844): Thread-601(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 6822): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/ActivityManager( 2404): Killing 5735:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/dalvikvm( 2736): GC_CONCURRENT freed 1604K, 20% free 11800K/14648K, paused 9ms+10ms, total 88ms
,I/System.out( 6844): AsyncTask #1 calls detatch()
,D/ChimeraCfgMgr( 3286): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3286): Module APK com.google.android.play.games already loaded
,W/ApplicationsProvider( 2965): Could not fetch usage stats
W/ApplicationsProvider( 2965): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2965): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2965): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2965): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2965): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2965): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2965): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2965): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2965): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:212)
W/ApplicationsProvider( 2965): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2965): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2965): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/dalvikvm( 6977): GC_CONCURRENT freed 2995K, 31% free 9578K/13748K, paused 9ms+6ms, total 39ms
,D/dalvikvm( 6977): WAIT_FOR_CONCURRENT_GC blocked 30ms
,I/System.out( 6822): Thread-658(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6822): Thread-658(ApacheHTTPLog):isShipBuild true
,I/System.out( 6822): Thread-658(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/sCloudBackupApp( 6977): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 6977): Other Intent
I/ActivityManager( 2404): Killing 5604:com.google.android.music:main/u0a125 (adj 15): empty #43
,I/SELinux ( 7022): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7022):  
,I/SELinux ( 7022): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7022):  
I/SELinux ( 7022):  
,I/SELinux ( 7022): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7022): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7022): >>>>> Normal User
,E/dalvikvm( 7022): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7022): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/GamesSyncServiceMain( 3286): Found unexpected GCM tag when scheduling; aborting
,D/dalvikvm( 6844): GC_CONCURRENT freed 2579K, 28% free 9971K/13740K, paused 3ms+11ms, total 71ms
,W/GamesSyncServiceMain( 3286): Failed to execute periodic sync, missing client context - aborting
,D/TimaKeyStoreProvider( 7022): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7022): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7022): Added TimaKesytore provider
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 350, Delta = 0
,I/dalvikvm( 6844): Total arena pages for JIT: 18
,W/WifiP2pStateTracker( 2404): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2404): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2404):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2404): handleConnectivityChange: setting default proxy info 
,D/dalvikvm( 7022): GC_FOR_ALLOC freed 3023K, 31% free 9548K/13744K, paused 49ms, total 49ms
D/ConnectivityService( 2404): updateSourceRoutes : no source routing conditions
,D/dalvikvm( 7022): GC_CONCURRENT freed 203K, 31% free 9574K/13744K, paused 4ms+2ms, total 33ms
,I/SecureStorage( 1965): [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,I/SecureStorage( 1965): [INFO]: SPID(0x00000004)PID: 6393, TID: 6438
,I/System.out( 6499): Thread-560(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/com.samsung.app( 7022): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7022): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7022): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7022): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7022): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7022): [KK AccuPhone]>>> RM:136 [0:0]  V init 
D/libgps  ( 2404): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2404): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2404): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/System.out( 6499): Thread-560(ApacheHTTPLog):isShipBuild true
,I/System.out( 6499): Thread-560(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/daemonapp( 5267): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7022): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5267): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7022): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5267): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7022): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7022): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,I/SELinux ( 7041): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7041):  
,I/dalvikvm( 3286): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 3286): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 3286): VFY: replacing opcode 0x6e at 0x003d
,I/SELinux ( 7041): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7041):  
I/SELinux ( 7041):  
,I/SELinux ( 7041): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7041): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7041): >>>>> Normal User
,E/dalvikvm( 7041): >>>>> com.samsung.android.internal.headlines [ userId:0 | appId:10110 ]
,E/SELinux ( 7041): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SecureStorage( 6393): [INFO]: SPID(0x00000000)Processing data has been completed
,D/TimaKeyStoreProvider( 7041): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7041): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7041): Added TimaKesytore provider
,D/DelayedSyncController( 6862): Delaying sync.
E/ActivityThread( 3286): Failed to find provider info for com.android.contacts.metadata
,W/PhenotypeConfigurator( 2736): Server returned 404
,D/dalvikvm( 6822): GC_CONCURRENT freed 1302K, 18% free 11361K/13836K, paused 10ms+4ms, total 117ms
,D/dalvikvm( 7041): GC_CONCURRENT freed 3003K, 31% free 9568K/13748K, paused 4ms+14ms, total 38ms
,D/dalvikvm( 7041): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/HeadlinesChannelApplication( 7041): [onCreate]
,D/Headlines( 7041): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 7041): getCountryCode(): countryCode = PL
,I/System.out( 6822): Thread-658 calls detatch()
,D/Headlines( 7041): Breath.onCreate
,D/HeadlinesCardManager( 7041): HeadlinesCardManager : constructor
,E/HeadlinesCardManager( 7041): HeadlinesCardManager : ctor = image_cache size is 42MB
,D/SA Version( 7041): CardProvider Library : 13
,I/SELinux ( 7059): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7059):  
,I/SELinux ( 7059): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7059):  
I/SELinux ( 7059):  
,I/SELinux ( 7059): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7059): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7059): >>>>> Normal User
,E/dalvikvm( 7059): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7059): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/MagazineService::CardProviderContentProvider( 6547): insertProvider: provider already exists.: com.samsung.android.app.headlines
,D/MagazineService::CardProviderContentProvider( 6547): insertProvider: provider is updated.: com.samsung.android.app.headlines
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 7041): registerCardProvider: provider already exists.
,D/TimaKeyStoreProvider( 7059): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7059): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7059): Added TimaKesytore provider
,I/Headlines( 7041): HeadlinesDataCenter ctor
I/Headlines( 7041): HeadlinesDataCenter. mLocale = en_US
,D/HeadlinesChannelUtil( 7041): getCountryCode(): countryCode = PL
,D/HeadlinesCardManager( 7041): HeadlinesCardManager : constructor welcome :YES
,D/dalvikvm( 2404): GC_EXPLICIT freed 2250K, 72% free 24715K/87680K, paused 8ms+20ms, total 203ms
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6282): mConnectivityHandler : connected
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Headlines( 7041): Breath timer started. interval : 30000
,D/Headlines( 7041): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 7041): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 7041): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 7041): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 7041): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 7041): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 7041): requestUpdateNewsWelcomeCard !!! no welcome card
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/PCWCLIENTTRACE_AccountUtil( 6282): [hasSamungAccount] - No Samsung Account
,D/AmoledAdjustTimer( 2404): prevTemp = 280, currTemp = 281, prevStep = 4, currStep = 4
,D/dalvikvm( 7059): GC_CONCURRENT freed 2989K, 31% free 9573K/13740K, paused 4ms+2ms, total 28ms
,D/dalvikvm( 7059): WAIT_FOR_CONCURRENT_GC blocked 24ms
,V/AlarmManager( 2404): waitForAlarm result :4
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/PCWCLIENTTRACE_SecurePreferencesJNI( 6282): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6282): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6282): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6282): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6282): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6282): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6282): [ensureRegistration] - No Samsung account
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Auth.Api.Credentials( 3286): [CredentialSyncAdapter] Unknown sync event.
,V/WebViewChromium( 7059): Binding Chromium to the background looper Looper (main, tid 1) {42281288}
,I/chromium( 7059): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7059): Initializing chromium process, renderers=0
,I/System.out( 6844): AsyncTask #1 calls detatch()
,I/System.out( 6822): Thread-641 calls detatch()
,I/SA      ( 6499): [RC New] [v2liruge] api execute + 2143
,I/SA      ( 6499): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 6499): AsyncTask #1 calls detatch()
,W/chromium( 7059): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/libEGL  ( 7059): loaded /system/lib/egl/libEGL_mali.so
,I/SA      ( 6499): [TPMU] getNetworkMcc : 
,D/libEGL  ( 7059): loaded /system/lib/egl/libGLESv1_CM_mali.so
,I/SA      ( 6499): [SCU] saveMccToPreferece Start
,I/SA      ( 6499): [SCU] RegionMCC : 260
,I/SA      ( 6499): [SSP] query invoked
,D/libEGL  ( 7059): loaded /system/lib/egl/libGLESv2_mali.so
,I/SA      ( 6499): [TPMU] GetMccFromDB : null
I/SA      ( 6499): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 6499): [SCU] saveMccToPreferece End
,I/SA      ( 6499): [RC New] executeRequest [v2liruge] end. 2219
,I/SA      ( 6499): [RC New] Execute end
,I/Mali    ( 7059): Mali API Version : 401
I/SA      ( 6499): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 6499): [OR] GetMyCountryZoneTask Success
,I/Mali    ( 7059): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
W/BackupManagerService( 2404): dataChanged but no participant pkg='com.android.providers.settings' uid=10011
,W/ActivityThread( 6393): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/BackupManagerService( 2404): dataChanged but no participant pkg='com.android.providers.settings' uid=10011
,W/System.err( 6844): com.sec.android.fota.osp.http.RestClientException
,W/System.err( 6844): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
,W/System.err( 6844): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
,W/System.err( 6844): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
,W/System.err( 6844): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 6844): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 6844): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 6844): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 6844): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 6844): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 6844): Caused by: java.lang.NullPointerException
,W/System.err( 6844): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
,W/System.err( 6844): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 6844): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 6844): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 6844): 	... 8 more
,I/ActivityManager( 2404): Killing 5794:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,I/System.out( 6393): Thread-551(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7059): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/GAV2    ( 7059): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/System.out( 6393): Thread-551(ApacheHTTPLog):isShipBuild true
I/System.out( 6393): Thread-551(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/dalvikvm( 6393): Total arena pages for JIT: 11
,I/dalvikvm( 6393): Total arena pages for JIT: 12
I/dalvikvm( 6393): Total arena pages for JIT: 13
,I/dalvikvm( 6393): Total arena pages for JIT: 14
I/dalvikvm( 6393): Total arena pages for JIT: 15
,I/dalvikvm( 6393): Total arena pages for JIT: 16
,I/dalvikvm( 6393): Total arena pages for JIT: 17
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/NtpTrustedTime( 2404): getCachedNtpTime() cache hit
,I/ActivityManager( 2404): Killing 5321:com.google.android.talk/u0a109 (adj 15): empty #43
,I/NSApplication( 7059): Starting up...
,D/SyncManager( 2404): failed sync operation 
,D/SyncManager( 2404): not retrying sync operation because the error is a hard error: 
,I/dalvikvm( 6393): Total arena pages for JIT: 18
,I/System.out( 6393): Thread-551 calls detatch()
,V/AlarmManager( 2404): waitForAlarm result :4
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/ImageResourceManager( 5692): ImageResourceManager: uninitalized
,D/dalvikvm( 5692): GC_FOR_ALLOC freed 1102K, 28% free 9905K/13744K, paused 31ms, total 35ms
,I/dalvikvm-heap( 5692): Grow heap (frag case) to 12.847MB for 2129936-byte allocation
,D/dalvikvm( 5692): GC_FOR_ALLOC freed 4K, 25% free 11981K/15828K, paused 19ms, total 19ms
,I/iu.Environment( 5692): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/dalvikvm( 5692): GC_CONCURRENT freed 33K, 25% free 11958K/15828K, paused 5ms+3ms, total 36ms
,I/iu.SyncManager( 5692): SYNC; picasa accounts
,I/ActivityManager( 2404): Killing 5775:com.sec.phone/1001 (adj 15): empty #43
,D/QuickConnect[1.1][2] ( 5042): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5042): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5042): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42289560
,D/dalvikvm( 5692): GC_FOR_ALLOC freed 24K, 25% free 11935K/15828K, paused 23ms, total 23ms
,I/SELinux ( 7111): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7111):  
,D/dalvikvm( 3857): GC_CONCURRENT freed 2388K, 25% free 10919K/14488K, paused 3ms+13ms, total 81ms
,D/dalvikvm( 3857): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/iu.UploadsManager( 5692): num queued entries: 0
,I/iu.UploadsManager( 5692): num updated entries: 0
,I/iu.SyncManager( 5692): NEXT; no task
,I/SELinux ( 7111): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7111):  
I/SELinux ( 7111):  
,I/SELinux ( 7111): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7111): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7111): >>>>> Normal User
,E/dalvikvm( 7111): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7111): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7111): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7111): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7111): Added TimaKesytore provider
,D/dalvikvm( 7111): GC_CONCURRENT freed 2993K, 31% free 9576K/13744K, paused 3ms+1ms, total 26ms
,D/dalvikvm( 7111): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/RCPManagerService( 2404): exchangeData() failure , invalid userId
,D/RCPManagerService( 2404): exchangeData() failure , invalid userId
,D/RCPManagerService( 2404): exchangeData() failure , invalid userId
,I/System.out( 6822): Thread-648 calls detatch()
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/RCPManagerService( 2404): exchangeData() failure , invalid userId
,I/SELinux ( 7135): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7135):  
,D/RCPManagerService( 2404): exchangeData() failure , invalid userId
W/ActivityManager( 2404): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 7135): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7135):  
I/SELinux ( 7135):  
,I/SELinux ( 7135): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7135): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7135): >>>>> Normal User
,E/dalvikvm( 7135): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7135): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/RCPManagerService( 2404): exchangeData() failure , invalid userId
,I/SurfaceFlinger( 1921): id=21 Removed Uoast (10/11)
,I/SurfaceFlinger( 1921): id=21 Removed Uoast (-2/11)
,D/TimaKeyStoreProvider( 7135): in addTimaSignatureService
,D/PowerManagerService( 2404): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2404) eventTime = 162167
,D/PowerManagerService( 2404): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2404 (0x0)
,D/PowerManagerService( 2404): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2404, ws=WorkSource{1000}) (elapsedTime=3408)
D/TimaKeyStoreProvider( 7135): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7135): Added TimaKesytore provider
,I/System.out( 6822): Thread-647 calls detatch()
I/ActivityManager( 2404): Killing 5950:com.sec.knox.bridge/1000 (adj 15): empty #43
,D/dalvikvm( 7135): GC_CONCURRENT freed 3004K, 31% free 9570K/13748K, paused 3ms+2ms, total 26ms
,D/dalvikvm( 7135): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/SELinux ( 7152): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7152):  
,I/SELinux ( 7152): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7152):  
I/SELinux ( 7152):  
I/SELinux ( 7152): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7152): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7152): >>>>> Normal User
E/dalvikvm( 7152): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7152): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/BadgeProvider( 7135): onCreate
,D/BadgeProvider( 7135): DatabaseHelper
,D/TimaKeyStoreProvider( 7152): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7152): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7152): Added TimaKesytore provider
,D/BadgeProvider( 7135): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 2769): reloadBadges entered.
,D/BadgeProvider( 7135): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7135): sendNotify, [notify] : null
D/BadgeProvider( 7135): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7135): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7135): update, [UpdateCount] : 1
,I/System.out( 6822): Thread-649 calls detatch()
,D/dalvikvm( 7152): GC_CONCURRENT freed 3001K, 31% free 9567K/13744K, paused 6ms+2ms, total 40ms
,D/dalvikvm( 7152): WAIT_FOR_CONCURRENT_GC blocked 34ms
,D/PicasaService( 3571): start picasa sync
,I/ActivityManager( 2404): Killing 6223:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/PicasaService( 3571): end picasa sync
,I/SELinux ( 7170): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7170):  
,I/ActivityManager( 2404): Killing 5927:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,I/SELinux ( 7170): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7170):  
I/SELinux ( 7170):  
,I/SELinux ( 7170): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 12% free 9504K/10724K, paused 2ms+3ms, total 38ms
E/SELinux ( 7170): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7170): >>>>> Normal User
E/dalvikvm( 7170): >>>>> com.google.android.talk [ userId:0 | appId:10109 ]
,E/SELinux ( 7170): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9504K/10724K, paused 2ms+2ms, total 26ms
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9504K/10724K, paused 2ms+3ms, total 25ms
,D/TimaKeyStoreProvider( 7170): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7170): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7170): Added TimaKesytore provider
,D/DelayedSyncController( 6862): Delaying sync.
,D/dalvikvm( 5692): GC_FOR_ALLOC freed 51K, 20% free 16095K/19996K, paused 29ms, total 32ms
,I/dalvikvm-heap( 5692): Grow heap (frag case) to 18.891MB for 2129936-byte allocation
,D/dalvikvm( 7170): GC_FOR_ALLOC freed 3004K, 31% free 9564K/13744K, paused 19ms, total 19ms
,D/dalvikvm( 7170): GC_CONCURRENT freed 256K, 31% free 9573K/13744K, paused 1ms+4ms, total 35ms
,D/dalvikvm( 5692): GC_FOR_ALLOC freed <1K, 18% free 18174K/22080K, paused 67ms, total 67ms
,D/dalvikvm( 5692): GC_CONCURRENT freed 6K, 18% free 18171K/22080K, paused 3ms+5ms, total 42ms
,I/dalvikvm( 7170): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N
W/dalvikvm( 7170): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 7170): VFY: replacing opcode 0x6e at 0x0008
,I/PeopleSync( 3286): onPerformSync() [5005f081]
,E/dalvikvm( 7170): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7170): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7170): VFY: replacing opcode 0x22 at 0x0000
,E/dalvikvm( 7170): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a
W/dalvikvm( 7170): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
,D/dalvikvm( 7170): VFY: replacing opcode 0x22 at 0x0037
,I/ActivityManager( 2404): Killing 6256:com.samsung.groupcast/u0a15 (adj 15): empty #43
,W/dalvikvm( 7170): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7170): Link of class 'Ldqp;' failed
,W/dalvikvm( 7170): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7170): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7170): Link of class 'Ldqp;' failed
I/dalvikvm( 7170): Could not find method dqp.q, referenced from method g.a
W/dalvikvm( 7170): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
,D/dalvikvm( 7170): VFY: replacing opcode 0x6e at 0x0000
,D/GCM     ( 2851): GcmService start Intent { act=com.google.android.c2dm.intent.REGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.REGISTER
,I/GCM     ( 2851): GCM config loaded
,E/dalvikvm( 7170): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7170): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7170): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm( 7170): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7170): Link of class 'Ldqp;' failed
,W/dalvikvm( 7170): VFY: unable to find class referenced in signature (Ldqp;)
,W/dalvikvm( 7170): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7170): Link of class 'Ldqp;' failed
,I/dalvikvm( 7170): Could not find method dqp.getState, referenced from method g.a
W/dalvikvm( 7170): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
,D/dalvikvm( 7170): VFY: replacing opcode 0x6e at 0x0008
,E/dalvikvm( 7170): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
W/dalvikvm( 7170): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
,D/dalvikvm( 7170): VFY: replacing opcode 0x1c at 0x0026
,W/InstanceID/Rpc( 2851): Found 10012
W/dalvikvm( 7170): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 7170): Link of class 'Ldqp;' failed
W/dalvikvm( 7170): VFY: unable to find class referenced in signature (Ldqp;)
,W/dalvikvm( 7170): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
W/dalvikvm( 7170): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7170): Link of class 'Ldqp;' failed
I/dalvikvm( 7170): Could not find method dqp.d, referenced from method g.a
,W/dalvikvm( 7170): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
,D/dalvikvm( 7170): VFY: replacing opcode 0x6e at 0x0003
,W/dalvikvm( 7170): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7170): Link of class 'Lax;' failed
E/dalvikvm( 7170): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 7170): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
,D/dalvikvm( 7170): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 7170): Unable to resolve superclass of Laz; (841)
,W/dalvikvm( 7170): Link of class 'Laz;' failed
E/dalvikvm( 7170): Could not find class 'az', referenced from method g.a
W/dalvikvm( 7170): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
,D/dalvikvm( 7170): VFY: replacing opcode 0x22 at 0x002c
I/dalvikvm( 7170): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
W/dalvikvm( 7170): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7170): VFY: replacing opcode 0x6e at 0x0008
,I/dalvikvm( 7170): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a
W/dalvikvm( 7170): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
,D/dalvikvm( 7170): VFY: replacing opcode 0x6e at 0x000c
,I/dalvikvm( 7170): Could not find method android.view.View.getTransitionName, referenced from method g.a
W/dalvikvm( 7170): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7170): VFY: replacing opcode 0x6e at 0x0006
,I/System.out( 3286): Thread-182(HTTPLog):isShipBuild true
,I/System.out( 3286): Thread-182(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/dalvikvm( 7170): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
W/dalvikvm( 7170): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
,D/dalvikvm( 7170): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 7170): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 7170): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
,D/dalvikvm( 7170): VFY: replacing opcode 0x72 at 0x0000
,I/dalvikvm( 7170): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
W/dalvikvm( 7170): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
,D/dalvikvm( 7170): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7170): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
,W/dalvikvm( 7170): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 7170): VFY: replacing opcode 0x72 at 0x0000
,W/dalvikvm( 7170): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
,E/dalvikvm( 7170): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
W/dalvikvm( 7170): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
,D/dalvikvm( 7170): VFY: replacing opcode 0x23 at 0x0005
,I/dalvikvm( 7170): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b
W/dalvikvm( 7170): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7170): VFY: replacing opcode 0x6e at 0x0009
,W/dalvikvm( 7170): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764)
I/System.out( 2851): Thread-89(HTTPLog):isShipBuild true
,I/System.out( 2851): Thread-89(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,W/dalvikvm( 7170): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
E/dalvikvm( 7170): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 7170): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;
,D/dalvikvm( 7170): VFY: replacing opcode 0x1c at 0x0002
E/dalvikvm( 7170): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 7170): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
,D/dalvikvm( 7170): VFY: replacing opcode 0x1f at 0x000c
,D/dalvikvm( 7170): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 7170): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7170): VFY: replacing opcode 0x62 at 0x0006
,D/dalvikvm( 7170): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7170): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a
,D/dalvikvm( 7170): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
D/dalvikvm( 7170): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
,D/dalvikvm( 7170): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a
,W/dalvikvm( 7170): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7170): Link of class 'Lax;' failed
,D/dalvikvm( 7170): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
,W/dalvikvm( 7170): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 7170): Link of class 'Laz;' failed
,D/dalvikvm( 7170): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
,D/dalvikvm( 7170): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a
,D/dalvikvm( 7170): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l
,D/dalvikvm( 7170): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x4227ec08
,D/dalvikvm( 7170): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x4227ec08
,D/dalvikvm( 2851): GC_EXPLICIT freed 1724K, 22% free 10908K/13864K, paused 17ms+12ms, total 120ms
,I/PeopleSync( 3286): Setting subscription: result=true [5005f081]
,D/Finsky  ( 3857): [214] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,I/PeopleSync( 3286): Starting sync, feed=null [5005f081]
,D/Finsky  ( 3857): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/dalvikvm( 7170): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b
W/dalvikvm( 7170): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
,D/dalvikvm( 7170): VFY: replacing opcode 0x6e at 0x0076
,I/Babel_SMS( 7170): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7170): MmsConfig.loadMmsSettings
I/Babel_SMS( 7170): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,I/Babel_SMS( 7170): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7170): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7170): MmsConfig.loadFromResources
,E/Babel_SMS( 7170): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7170): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,W/dalvikvm( 7170): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 7170): Link of class 'Lfzc;' failed
E/dalvikvm( 7170): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
W/dalvikvm( 7170): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
,D/dalvikvm( 7170): VFY: replacing opcode 0x22 at 0x0033
W/dalvikvm( 7170): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7170): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7170): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
,W/dalvikvm( 7170): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,I/dalvikvm( 7170): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
W/dalvikvm( 7170): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
,D/dalvikvm( 7170): VFY: replacing opcode 0x74 at 0x006d
,I/dalvikvm( 7170): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
,W/dalvikvm( 7170): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
,D/dalvikvm( 7170): VFY: replacing opcode 0x6e at 0x0033
I/dalvikvm( 7170): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
W/dalvikvm( 7170): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
,D/dalvikvm( 7170): VFY: replacing opcode 0x6e at 0x0030
W/dalvikvm( 7170): Unable to resolve superclass of Lfzc; (613)
,W/dalvikvm( 7170): Link of class 'Lfzc;' failed
,D/dalvikvm( 7170): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
E/SensorService( 2404): Permission Denial : SEC Private Sensor 
E/SensorService( 2404): Permission Denial : SEC Private Sensor 
,D/ExynosCameraInterface( 1926): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1926): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
,D/ExynosCameraInterface( 1926): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1926): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
,W/Settings( 7170): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7170): startup - clean
,I/Babel   ( 7170): deleted: false for 0
,I/dalvikvm( 7170): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
,W/dalvikvm( 7170): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7170): VFY: replacing opcode 0x6e at 0x000d
,W/dalvikvm( 7170): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
I/dalvikvm( 7170): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 7170): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
,D/dalvikvm( 7170): VFY: replacing opcode 0x6e at 0x004e
W/dalvikvm( 7170): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7170): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7170): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
W/dalvikvm( 7170): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
,D/dalvikvm( 7170): VFY: replacing opcode 0x22 at 0x0071
,W/dalvikvm( 7170): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7170): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7170): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7170): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7170): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 7170): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
,D/dalvikvm( 7170): VFY: replacing opcode 0x1f at 0x0021
,W/dalvikvm( 7170): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,D/dalvikvm( 7170): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
,D/dalvikvm( 7170): GC_CONCURRENT freed 1948K, 20% free 11827K/14772K, paused 4ms+3ms, total 108ms
,I/dalvikvm( 7170): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
W/dalvikvm( 7170): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
,D/dalvikvm( 7170): VFY: replacing opcode 0x6e at 0x0074
,D/WaitQueueForNetworkActivate( 6644): notifyNetworkActivated
,W/BaseAppContext( 3286): Using Auth Proxy for data requests.
,I/vclib   ( 7170): onServiceConnected
,W/Babel   ( 7170): Attempted to change video mute state without an active call.
,W/ContextImpl( 6644): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ActivityManager( 2404): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,D/dalvikvm( 2404): GC_EXPLICIT freed 3275K, 72% free 24662K/87680K, paused 13ms+21ms, total 210ms
,W/BaseAppContext( 3286): Using Auth Proxy for data requests.
,D/dalvikvm( 7170): GC_FOR_ALLOC freed 841K, 19% free 12209K/14980K, paused 56ms, total 58ms
,D/dalvikvm( 7170): GC_FOR_ALLOC freed 144K, 20% free 12326K/15236K, paused 47ms, total 47ms
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/BaseAppContext( 3286): Using Auth Proxy for data requests.
,I/PeopleSync( 3286): Sync start: cannotHavePeople=true isPageExistenceCheckOnly=false
,D/dalvikvm( 7170): GC_FOR_ALLOC freed 1016K, 23% free 12647K/16316K, paused 33ms, total 34ms
,I/System.out( 7170): Thread-650(HTTPLog):isShipBuild true
,I/System.out( 7170): Thread-650(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/RemindersSync( 3286): Found sync condition that we don't recognize, aborting. [T SyncAdapterThread-1:id=248:priority=5:group=main]
,W/dalvikvm( 2851): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 2851): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 2851): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/dalvikvm( 2851): VFY: replacing opcode 0x1f at 0x0011
I/dalvikvm( 2851): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 2851): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2851): VFY: replacing opcode 0x6e at 0x003d
,D/hcjo    ( 6644): AutoUpdateManager:IDLE:execute
,I/Babel   ( 7170): connection state changed from UNKNOWN to CONNECTED
,I/CheckinService( 3286): Checkin interval check for package: unspecified last checkin: 1451252271153 min interval config: 0 actual interval: 671281746
,I/dalvikvm( 6644): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
W/dalvikvm( 6644): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 6644): VFY: replacing opcode 0x6e at 0x0024
,D/InitializeManagerStateMachine( 6644): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6644): exit::IDLE
,D/InitializeManagerStateMachine( 6644): entry::NETWORK_CHECK
I/CheckinService( 3286): Checking schedule, now: 1451923552929 next: 1451810614047
,I/CheckinService( 3286): active receiver: enabled
D/InitializeManagerStateMachine( 6644): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6644): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6644): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6644): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6644): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6644): entry::SUCCESS
,D/hcjo    ( 6644): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6644): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/CheckinService( 3286): Preparing to send checkin request
,I/EventLogService( 3286): Accumulating logs since 1451922056207
,I/Volley  ( 6644): RestApi Request Add : 2307
,I/iu.SyncManager( 3286): SYNC; picasa accounts
,D/NetworkLogImpl( 3286): Loaded NetworkSpeedPredictor
,I/iu.Environment( 3286): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 3286): num queued entries: 0
,I/iu.UploadsManager( 3286): num updated entries: 0
,I/iu.SyncManager( 3286): NEXT; no task
,E/SPPClientService( 5461): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5461): [SystemStateMoniter] Current Time : 165216
,E/SPPClientService( 5461): [SystemStateMoniter] No Connect : false
,I/SELinux ( 7235): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7235):  
,I/SELinux ( 7235): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7235):  
I/SELinux ( 7235):  
,I/SELinux ( 7235): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7235): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7235): >>>>> Normal User
,E/dalvikvm( 7235): >>>>> com.android.calendar [ userId:0 | appId:10144 ]
,E/SELinux ( 7235): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7235): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7235): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7235): Added TimaKesytore provider
,D/dalvikvm( 3286): GC_CONCURRENT freed 1704K, 20% free 12616K/15616K, paused 5ms+30ms, total 89ms
,D/dalvikvm( 2851): GC_CONCURRENT freed 1896K, 23% free 10952K/14088K, paused 10ms+6ms, total 64ms
,D/dalvikvm( 7235): GC_CONCURRENT freed 2990K, 31% free 9573K/13740K, paused 3ms+7ms, total 78ms
,D/dalvikvm( 7235): WAIT_FOR_CONCURRENT_GC blocked 49ms
,D/CaptivePortalTracker( 2404): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker( 2404): Checking http://216.58.209.46/generate_204
D/ConnectivityService( 2404): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/ActivityThread( 2404): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/System.out( 2404): Thread-161(HTTPLog):isShipBuild true
,I/System.out( 2404): Thread-161(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/CaptivePortalTracker( 2404): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker( 2404): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2404): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2404): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2404): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/CheckinRequestBuilder( 3286): Checkin reason type: 12 attempt count: 1
,I/ActivityManager( 2404): Killing 6268:com.android.musicfx/u0a24 (adj 15): empty #43
,D/BootCompletedReceiver( 2404): onReceive
,E/ActivityThread( 3286): Failed to find provider info for com.google.android.wearable.settings
,I/dalvikvm( 3286): Could not find method android.content.Context.getNoBackupFilesDir, referenced from method com.google.android.gms.iid.n.<init>
W/dalvikvm( 3286): VFY: unable to resolve virtual method 378: Landroid/content/Context;.getNoBackupFilesDir ()Ljava/io/File;
,D/dalvikvm( 3286): VFY: replacing opcode 0x6e at 0x002c
I/dalvikvm( 3286): Could not find method android.content.Context.getDrawable, referenced from method android.support.v4.content.g.a
W/dalvikvm( 3286): VFY: unable to resolve virtual method 287: Landroid/content/Context;.getDrawable (I)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 3286): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 3286): Could not find method android.content.Context.getColor, referenced from method android.support.v4.content.g.b
W/dalvikvm( 3286): VFY: unable to resolve virtual method 283: Landroid/content/Context;.getColor (I)I
,D/dalvikvm( 3286): VFY: replacing opcode 0x6e at 0x0006
,I/KLMS-2.3.201 : ( 6886): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/dalvikvm( 3286): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm( 3286): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm( 3286): VFY: replacing opcode 0x71 at 0x004e
,D/dalvikvm( 3286): DexOpt: --- BEGIN 'ads-577242176.jar' (bootstrap=0) ---
,I/KLMS-2.3.201 : ( 6886): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1451923553977
,I/KLMS-2.3.201 : ( 6886): StateImplV2() : dateTimeChanged() : Mon Jan 04 17:05:53 CET 2016
,D/ConnectivityService( 2404): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
,D/STATUSBAR-NetworkController( 2581): updateDataNetType()
,D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,D/SO_AGENT( 6925): [ServerTimeReceiver.java(Line:44/Method:onReceive)] Receive broadcast meassage:android.intent.action.TIME_SET
,I/SO_AGENT( 6925): [ServerTimeReceiver.java(Line:47/Method:onReceive)] No action is available before server time settings
,D/dalvikvm( 7258): DexOpt: load 3ms, verify+opt 53ms, 194052 bytes
,I/SA      ( 6499): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,D/dalvikvm( 3286): DexOpt: --- END 'ads-577242176.jar' (success) ---
,D/dalvikvm( 3286): DEX prep '/data/data/com.google.android.gms/cache/ads-577242176.jar': unzip in 0ms, rewrite 198ms
,D/dalvikvm( 6644): GC_CONCURRENT freed 2564K, 27% free 10085K/13788K, paused 14ms+3ms, total 72ms
,D/Mms/MessagingNotification( 5556): [start]    nonBlockingUpdateMessageIndicator()
,D/Mms/MessagingNotification( 5556): sDisableVibrateForCamera = false
D/Mms/MessagingNotification( 5556): isBlockingModeEnable() = false
,D/Mms/TelephonyPermission( 5556): isDefault true
,I/GAV2    ( 7059): Thread[GAThread,5,main]: No campaign data found.
,I/SELinux ( 7270): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7270):  
,D/TP/MmsSmsProvider( 2753): match 200:Elapsed time : 1.511 ms
,D/TP/MmsSmsProvider( 2753): match 8:Elapsed time : 41.835 ms
I/SELinux ( 7270): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7270):  
I/SELinux ( 7270):  
,I/SELinux ( 7270): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7270): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7270): >>>>> Normal User
,E/dalvikvm( 7270): >>>>> com.samsung.android.scloud.sync [ userId:0 | appId:10064 ]
,E/SELinux ( 7270): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7270): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7270): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7270): Added TimaKesytore provider
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/BadgeProvider( 7135): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/Launcher.Model( 2769): reloadBadges entered.
D/BadgeProvider( 7135): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 7135): sendNotify, [notify] : null
D/BadgeProvider( 7135): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 7135): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7135): update, [UpdateCount] : 1
,D/Mms/MessagingNotification( 5556): setBadgeCount(), count=0
,D/MessagingNotification( 5556): remove alarm
,D/Mms/MessagingNotification( 5556): updateAllHistoryAsRead()
,D/Mms/MessagingNotification( 5556): [end]    nonBlockingUpdateMessageIndicator()
,D/dalvikvm( 7270): GC_CONCURRENT freed 2994K, 31% free 9571K/13740K, paused 6ms+2ms, total 43ms
,D/dalvikvm( 7270): WAIT_FOR_CONCURRENT_GC blocked 36ms
,D/com.samsung.app( 7022): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidintentactionTIME_SET
,D/com.samsung.app( 7022): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2404): Waited long enough for: ServiceRecord{46791ef0 u0 pl.k2.droidoaudioteka/.services.DownloadService}
,I/SELinux ( 7286): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7286):  
,I/ Time Manager ( 7270): Time Difference not stored. TIME_DIFFERENCE
I/ActivityManager( 2404): Killing 6296:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
I/ActivityManager( 2404): Waited long enough for: ServiceRecord{4678cf28 u0 pl.k2.droidoaudioteka/.services.PlayerService}
,I/SELinux ( 7286): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7286):  
I/SELinux ( 7286):  
,I/SELinux ( 7286): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7286): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7286): >>>>> Normal User
,E/dalvikvm( 7286): >>>>> com.sec.android.app.clockpackage [ userId:0 | appId:10088 ]
,E/SELinux ( 7286): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7286): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7286): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7286): Added TimaKesytore provider
,D/dalvikvm( 7286): GC_CONCURRENT freed 2991K, 31% free 9576K/13744K, paused 3ms+1ms, total 27ms
D/dalvikvm( 7286): WAIT_FOR_CONCURRENT_GC blocked 16ms
D/dalvikvm( 6644): GC_CONCURRENT freed 2049K, 28% free 10010K/13788K, paused 13ms+4ms, total 38ms
I/SELinux ( 7301): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7301):  
I/ActivityManager( 2404): Killing 6332:com.sec.android.service.health/u0a16 (adj 15): empty #43
I/SELinux ( 7301): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7301):  
I/SELinux ( 7301):  
I/SELinux ( 7301): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7301): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7301): >>>>> Normal User
E/dalvikvm( 7301): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
E/SELinux ( 7301): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 7301): in addTimaSignatureService
D/TimaKeyStoreProvider( 7301): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7301): Added TimaKesytore provider
D/dalvikvm( 7301): GC_CONCURRENT freed 3011K, 31% free 9556K/13744K, paused 3ms+3ms, total 33ms
D/dalvikvm( 7301): WAIT_FOR_CONCURRENT_GC blocked 27ms
D/elm:14132( 7301): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
D/elm:14132( 7301): ELMEngine.ELMEngine( context ).
D/elm:14132( 7301): MDMBridge.setEnterpriseBridge()
D/elm:14132( 7301): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
I/knox    ( 4982): MainReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
D/elm:14132( 7301): ElmAgentService : onCreate()
D/elm:14132( 7301): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
W/ContextImpl( 4982): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.sec.knox.seandroid.receiver.MainReceiver.onReceive:142 android.app.ActivityThread.handleReceiver:2698 
D/knox    ( 4982): MainReceiver.listeningToTimeDateChanges( context, intent ).
I/knox    ( 4982): MainReceiver.onReceive() END - - - - - : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.knox.seandroid/.receiver.MainReceiver }
D/knox    ( 4982): KNOXAgentService : onCreate()
D/knox    ( 4982): KNOXAgentService : set alarms for deniallog and usage data upload
D/knox    ( 4982): KNOXAgentService. startJobThread() start
D/knox    ( 4982): KNOXAgentService. JobThread()
D/knox    ( 4982): KNOXAgentService. JobThread. notifyAll().
D/knox    ( 4982): KNOXAgentService. startJobThread() wait
I/SELinux ( 7317): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7317):  
D/elm:14132( 7301): ELMAgentService.listeningToTimeDateChanges( context, intent ).
D/elm:14132( 7301): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
D/elm:14132( 7301): ModuleBase.resetCalllogAPIAlarm()
D/knox    ( 4982): KNOXAgentService : onDestroy().
D/knox    ( 4982): ModuleBase.cancelAllAlarmManageModule()
D/elm:14132( 7301): ModuleBase.ModifySetAlarm()
D/elm:14132( 7301): MDMBridge.getInstance()
D/elm:14132( 7301): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132( 7301): ElmAgentService : onDestroy().
I/ActivityManager( 2404): Killing 6450:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty #43
I/SELinux ( 7317): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7317):  
I/SELinux ( 7317):  
I/SELinux ( 7317): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7317): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7317): >>>>> Normal User
E/dalvikvm( 7317): >>>>> com.sec.android.widgetapp.SPlannerAppWidget [ userId:0 | appId:10145 ]
E/SELinux ( 7317): [DEBUG] seapp_context_lookup: seinfoCategory = shared
D/TimaKeyStoreProvider( 7317): in addTimaSignatureService
D/TimaKeyStoreProvider( 7317): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7317): Added TimaKesytore provider
D/dalvikvm( 6644): GC_CONCURRENT freed 1806K, 26% free 10239K/13788K, paused 3ms+12ms, total 46ms
,D/dalvikvm( 2404): GC_EXPLICIT freed 1728K, 72% free 24723K/87680K, paused 8ms+18ms, total 195ms
,I/SELinux ( 7331): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7331):  
,D/InitializeManagerStateMachine( 6644): exit::SUCCESS
,D/InitializeManagerStateMachine( 6644): entry::IDLE
,I/System.out( 6644): Thread-586(HTTPLog):isShipBuild true
,I/System.out( 6644): Thread-586(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/SELinux ( 7331): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7331):  
I/SELinux ( 7331):  
,I/SELinux ( 7331): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7331): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7331): >>>>> Normal User
,E/dalvikvm( 7331): >>>>> com.google.android.gms.unstable [ userId:0 | appId:10012 ]
,E/SELinux ( 7331): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7331): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7331): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7331): Added TimaKesytore provider
,D/dalvikvm( 7317): GC_CONCURRENT freed 3005K, 31% free 9568K/13748K, paused 10ms+1ms, total 52ms
,D/dalvikvm( 7317): WAIT_FOR_CONCURRENT_GC blocked 33ms
,I/VacuumService( 2736): Vacuum at: now=1451923555781 tag=VacuumService
,I/SELinux ( 7349): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7349):  
,I/ActivityManager( 2404): Killing 5903:com.google.android.googlequicksearchbox:search/u0a59 (adj 15): empty #43
,I/SELinux ( 7349): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7349):  
I/SELinux ( 7349):  
,I/SELinux ( 7349): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7349): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7349): >>>>> Normal User
,E/dalvikvm( 7349): >>>>> com.sec.android.app.taskmanager [ userId:0 | appId:10168 ]
,E/SELinux ( 7349): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 7331): GC_CONCURRENT freed 3009K, 31% free 9561K/13748K, paused 2ms+8ms, total 32ms
,D/dalvikvm( 7331): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/TimaKeyStoreProvider( 7349): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7349): Cannot add TimaSignature Service, License check Failed
W/dalvikvm( 7331): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 7331): VFY: replacing opcode 0x60 at 0x000b
,D/ActivityThread( 7349): Added TimaKesytore provider
,I/dalvikvm( 7331): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 7331): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 7331): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 7331): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 7331): install
,I/MultiDex( 7331): MultiDexExtractor.load(/data/app/com.google.android.gms-5.apk, false)
,I/MultiDex( 7331): loading existing secondary dex files
,I/MultiDex( 7331): load found 3 secondary dex files
,I/MultiDex( 7331): install done
,D/dalvikvm( 7349): GC_CONCURRENT freed 3013K, 31% free 9561K/13748K, paused 6ms+3ms, total 31ms
,D/dalvikvm( 7349): WAIT_FOR_CONCURRENT_GC blocked 26ms
,E/Watchdog( 2404): !@Sync 5
,D/dalvikvm( 7331): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7331): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7331): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 7331): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 7331): VFY: unable to resolve instance field 36
,D/dalvikvm( 7331): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 7331): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7331): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7331): VFY: replacing opcode 0x62 at 0x0047
,I/ActivityManager( 2404): Killing 4791:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #43
D/dalvikvm( 7331): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 7331): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 7331): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422d0808
D/dalvikvm( 7331): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422d0808
D/dalvikvm( 7331): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422d0808, skipping init
D/dalvikvm( 7331): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x422d0808
D/dalvikvm( 7331): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x422d0808
V/JNIHelp ( 7331): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/daemonapp( 5267): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5267): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5267): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5267): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5267): [MSC_Daemon]>>> WDSM:44 [0:0] Act : androidintentactionTIME_SET, run:true
D/comsamsunglog( 5267): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5267): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5267): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5267): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5267): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5267): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5267): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 5267): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 5267): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5267): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5267): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/dalvikvm( 7331): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422d0808
,D/dalvikvm( 7331): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x422d0808
D/dalvikvm( 7331): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x422d0808
,D/dalvikvm( 7331): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x422d0808
,D/hcjo    ( 6644): AutoUpdateTriggerManager:REQUEST2:setInterval:345600000
,D/hcjo    ( 6644): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
D/hcjo    ( 6644): AutoUpdateManager:UPD_CHECK_TIMING:onUpdateTime
,D/hcjo    ( 6644): SelfUpdateManager:IDLE:execute
,D/comdaemonstockapp( 5267): [Daemon_Stock]>>> StockclockDaemonService.java:60 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 5267): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] appServiceStatus: 0
,D/hcjo    ( 6644): SelfUpdateManager:CONDITION_CHECK:onUpdateCondition
,I/ProviderInstaller( 7331): Installed default security provider GmsCore_OpenSSL
,I/CheckinService( 3286): Checkin interval check for package: unspecified last checkin: 1451252271153 min interval config: 0 actual interval: 671285066
,I/Volley  ( 6644): RestApi Request Add : 2346
,E/SPPClientService( 5461): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
I/dalvikvm( 7331): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.mz.b
W/dalvikvm( 7331): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 7331): VFY: replacing opcode 0x6e at 0x00ce
I/dalvikvm( 7331): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 7331): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7331): VFY: replacing opcode 0x6e at 0x000d
,I/dalvikvm( 7331): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 7331): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 7331): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 7331): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,D/dalvikvm( 7331): VFY: replacing opcode 0x22 at 0x0000
I/dalvikvm( 7331): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.j.b.b
W/dalvikvm( 7331): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 7331): VFY: replacing opcode 0x6e at 0x0036
I/dalvikvm( 7331): Failed resolving Lcom/google/android/gms/common/j/c; interface 122 'Landroid/content/pm/PackageManager$OnPermissionsChangedListener;'
,W/dalvikvm( 7331): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/dalvikvm( 7331): DexOpt: unable to opt direct call 0x32c7 at 0x02 in Lcom/google/android/gms/common/j/b;.a
,E/Parcel  ( 1926): nm 16
,D/WVCdm   ( 1926): Instantiating CDM.
,I/WVCdm   ( 1926): Level3 Library Nov 20 2013 18:09:31
,E/wv_dash ( 1926): chunk TEE virt: 0x200908
,D/WVCdm   ( 1926): OEMCrypto_Initialize Level 1 success. I will use level 1.
,I/WVCdm   ( 1926): CdmEngine::OpenSession
,I/WVCdm   ( 1926): CdmEngine::QueryKeyControlInfo
,E/Parcel  ( 7331): nm 16
,E/Parcel  ( 1926): nm 16
E/Parcel  ( 1926): nm 1
,I/WVCdm   ( 1926): CdmEngine::GenerateKeyRequest
,E/SPPClientService( 5461): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
D/WVCdm   ( 1926): PrepareKeyRequest: nonce=1318511154
,I/SELinux ( 7373): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7373):  
,I/SELinux ( 7373): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7373):  
I/SELinux ( 7373):  
,I/SELinux ( 7373): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7373): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/dalvikvm( 7373): >>>>> Normal User
,E/dalvikvm( 7373): >>>>> com.google.android.googlequicksearchbox:search [ userId:0 | appId:10059 ]
,E/SELinux ( 7373): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7373): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7373): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7373): Added TimaKesytore provider
,I/chromium( 6434): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/SPPClientService( 5461): [a] [ConnectionManager] Connection is already disconnected.
V/AlarmManager( 2404): waitForAlarm result :4
V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/dalvikvm( 7331): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 7331): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 7331): VFY: replacing opcode 0x6e at 0x003d
,W/dalvikvm( 7331): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 7331): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 7331): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/dalvikvm( 7331): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 7331): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 7331): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 7331): Using platform SSLCertificateSocketFactory
,E/Parcel  ( 7331): nm 1834
E/Parcel  ( 1926): nm 16
,I/WVCdm   ( 1926): CdmEngine::CloseSession
,D/dalvikvm( 7373): GC_CONCURRENT freed 2993K, 31% free 9578K/13744K, paused 6ms+2ms, total 38ms
,D/dalvikvm( 7373): WAIT_FOR_CONCURRENT_GC blocked 32ms
,I/System.out( 7331): Thread-655(HTTPLog):isShipBuild true
,I/System.out( 7331): Thread-655(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/PeopleSync( 3286): Sync finished, successful=true, took 4222ms
,I/PeopleContactsSync( 3286): CP2 sync start [5005f081]
,D/dalvikvm( 7331): GC_CONCURRENT freed 1617K, 21% free 11002K/13792K, paused 2ms+20ms, total 99ms
,D/dalvikvm( 3286): GC_CONCURRENT freed 1640K, 18% free 12913K/15724K, paused 6ms+6ms, total 124ms
,W/SQLiteConnectionPool( 3286): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/Icing.InternalIcingCorporaProvider( 7373): Updating corpora: A: com.sec.enterprise.knox.cloudmdm.smdms, C: MAYBE
,D/FileShare-Server( 5921): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,I/SELinux ( 7392): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7392):  
,I/PeopleContactsSync( 3286): CP2 sync: diff=PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/SELinux ( 7398): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7398):  
,I/PeopleContactsSync( 3286): Syncing people to contacts: PeopleSyncDiffs: circlesSync disabled; evergreenSync disabled; unchanged [5005f081]
,I/SELinux ( 7392): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7392):  
I/SELinux ( 7392):  
,I/SELinux ( 7392): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7392): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7392): >>>>> Normal User
E/dalvikvm( 7392): >>>>> com.sec.knox.bridge [ userId:0 | appId:1000 ]
,E/SELinux ( 7392): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 7398): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7398):  
I/SELinux ( 7398):  
,I/SELinux ( 7398): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7398): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7398): >>>>> Normal User
,E/dalvikvm( 7398): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ]
,E/SELinux ( 7398): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7392): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7398): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7398): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7398): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 7392): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7392): Added TimaKesytore provider
,D/LocationManagerService( 2404): getProviders()=[passive]
,D/NativeLibraryUtils( 7331): Install completed successfully. count=14 extracted=0
,D/dalvikvm( 7398): GC_CONCURRENT freed 3000K, 31% free 9569K/13744K, paused 3ms+1ms, total 26ms
,D/dalvikvm( 7398): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/qtaguid ( 6644): Failed write_ctrl(u -1) res=-1 errno=9
I/qtaguid ( 6644): Untagging socket -1 failed errno=-9
,W/NetworkManagementSocketTagger( 6644): untagSocket(-1) failed with errno -9
,D/dalvikvm( 7392): GC_CONCURRENT freed 3002K, 31% free 9567K/13744K, paused 4ms+7ms, total 54ms
,D/dalvikvm( 7392): WAIT_FOR_CONCURRENT_GC blocked 37ms
,D/hcjo    ( 6644): SelfUpdateManager:REQUEST_UPD_CHECK:onUpdateCheckSuccessAndNoNeedUpdate
,D/hcjo    ( 6644): AutoUpdateManager:CHECK_SELF_UPD:onSelfUpdateResult:T
,D/hcjo    ( 6644): SellerAppAutoUpdate:clearFlag
,D/SellerAppAutoUpdateManagerStateMachine( 6644): execute::IDLE:EXECUTE
D/SellerAppAutoUpdateManagerStateMachine( 6644): exit::IDLE
,D/SellerAppAutoUpdateManagerStateMachine( 6644): entry::TOKENCHECK
,I/PeopleContactsSync( 3286): CP2 cleanup done, kept= duration=309 ms
D/SellerAppAutoUpdateManagerStateMachine( 6644): execute::TOKENCHECK:TOKEN_RECEIVED
D/SellerAppAutoUpdateManagerStateMachine( 6644): exit::TOKENCHECK
D/SellerAppAutoUpdateManagerStateMachine( 6644): entry::FAILED
D/hcjo    ( 6644): AutoUpdateManager:SELLER_UPD:onSellerAutoUpdateFailed
D/SellerAppAutoUpdateManagerStateMachine( 6644): exit::FAILED
,D/SellerAppAutoUpdateManagerStateMachine( 6644): entry::IDLE
,I/ActivityManager( 2404): Killing 6523:com.sec.android.service.cm/u0a82 (adj 15): empty #43
D/BezelQuickConnect( 5054): BezelBroadcastReceiver - onReceive : android.intent.action.PACKAGE_CHANGED
D/BezelQuickConnect( 5054): BezelBroadcastReceiver - packageName : com.sec.enterprise.knox.cloudmdm.smdms
,D/PackageBroadcastService( 3286): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,I/PeopleContactsSync( 3286): ===CP2 sync finished, success=true, time=457,0,0,0,0,0 rc=0,0,0,0 av=0,0,0,0,0,0 [5005f081]
,I/ActivityManager( 2404): Killing 6535:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty #43
,D/dalvikvm( 7331): GC_CONCURRENT freed 1414K, 19% free 11631K/14224K, paused 9ms+13ms, total 99ms
,D/dalvikvm( 7331): WAIT_FOR_CONCURRENT_GC blocked 38ms
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 360, Delta = 10
I/SELinux ( 7430): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7430):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 42K, 12% free 9504K/10724K, paused 3ms+4ms, total 37ms
I/SELinux ( 7430): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7430):  
I/SELinux ( 7430):  
,I/SELinux ( 7430): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7430): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7430): >>>>> Normal User
,E/dalvikvm( 7430): >>>>> com.android.providers.calendar [ userId:0 | appId:10045 ]
,E/SELinux ( 7430): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9504K/10724K, paused 2ms+3ms, total 27ms
,D/TimaKeyStoreProvider( 7430): in addTimaSignatureService
,I/PeopleSync( 3286): ***Sync finished***, duration: 6564 [5005f081]
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 12% free 9504K/10724K, paused 2ms+3ms, total 26ms
,D/TimaKeyStoreProvider( 7430): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7430): Added TimaKesytore provider
,D/dalvikvm( 7331): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x423b0f30
D/dalvikvm( 7331): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x423b0f30
,D/dalvikvm( 7331): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x423b0f30, skipping init
,D/dalvikvm( 7430): GC_CONCURRENT freed 2997K, 31% free 9576K/13748K, paused 3ms+3ms, total 32ms
,D/dalvikvm( 7430): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/Icing.InternalIcingCorporaProvider( 7373): UpdateCorporaTask done [took 829 ms] updated apps [took 829 ms] 
I/ActivityManager( 2404): Killing 6561:com.samsung.helphub/1000 (adj 15): empty #43
,D/Headlines( 7041): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 7041): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7041): Breath 9636 latestRequest time : 1451923548551 current time : 1451923558187
,I/DBG_DM  ( 4656): [3.19.140541][Line:2663][xdmDbsqlGetFUMOStatus] xdbsqlGetFUMOStatus : 220
,I/DBG_DM  ( 4656): [3.19.140541][Line:1835][xtpAdpGetUserCancel] flag is : false
,I/DBG_DM  ( 4656): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
,I/DBG_DM  ( 4656): [3.19.140541][Line:174][onReceive] sec.fota.polling.intent.RECEIVE
,I/DBG_DM  ( 4656): [3.19.140541][Line:536][xdmBroadCastCheckReceivedNfcMode] nMode : 0
,I/DBG_DM  ( 4656): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
,I/DBG_DM  ( 4656): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4656): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
,I/DBG_DM  ( 4656): [3.19.140541][Line:258][xuiAdpUserInitiate] 
,I/DBG_DM  ( 4656): [3.19.140541][Line:3767][xdbGetWifiOnlyFlag] Wifi_Only_flag : true
,I/DBG_DM  ( 4656): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/DBG_DM  ( 4656): [3.19.140541][Line:283][xuiAdpUserInitiate] bWifiOnly flag : true
,I/DBG_DM  ( 4656): [3.19.140541][Line:3627][xdbGetFUMOStatus] FUMO_Status : 220
,I/DBG_DM  ( 4656): [3.19.140541][Line:1835][xtpAdpGetUserCancel] flag is : false
,I/DBG_DM  ( 4656): [3.19.140541][Line:1733][xfotaDlAgentHdlrGetUpdateProcessingState] bUpdateProcessing : false
,I/DBG_DM  ( 4656): [3.19.140541][Line:769][xdmUIEvent] XUI_DL_UPDATE_START
,I/DBG_DM  ( 4656): [3.19.140541][Line:369][handleMessage] event ->214
,I/DBG_DM  ( 4656): [3.19.140541][Line:1222][xdmGetTopActivityName] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 4656): [3.19.140541][Line:2008][xdmCallUiFotaInstall] 
,I/DBG_DM  ( 4656): [3.19.140541][Line:729][xdmUIEvent] XUI_DL_UPDATE_CONFIRM
,I/DBG_DM  ( 4656): [3.19.140541][Line:1320][xdmCheckIdleScreen] Idle Screen : false
W/ContextImpl( 4656): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 com.wssyncmldm.XDMService.xdmCallUiFotaInstall:2023 com.wssyncmldm.XDMService$1.handleMessage:372 android.os.Handler.dispatchMessage:102 
,I/DBG_DM  ( 4656): [3.19.140541][Line:890][xdmUnRegisterBatteryReceiver] 
,E/DBG_DM  ( 4656): Warning!!! [3.19.140541][Line:898][xdmUnRegisterBatteryReceiver] didn't register
,E/DBG_DM  ( 4656): Warning!!! [3.19.140541][Line:899][xdmUnRegisterBatteryReceiver] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.XDMService$3@4238fa10
,I/DBG_DM  ( 4656): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4656): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2404): sendNotification(2) - 4
,I/SurfaceFlinger( 1921): id=22 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 2404): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2404
,D/WVMDrmPlugIn( 1925): WVMDrmPlugin::onInitialize : 3639
,D/WVMDrmPlugIn( 1925): WVMDrmPlugin::onSetOnInfoListener : add 3639
I/PrGenericPlugin( 1925): [A] ENTER onInitialize : 0xe37
,I/PrGenericPlugin( 1925): [A] LEAVE onInitialize : 0xe37
,D/WVMDrmPlugIn( 1925): WVMDrmPlugin::onGetSupportInfo : 0
,I/PrGenericPlugin( 1925): [A] ENTER onGetSupportInfo : 0
,I/PrGenericPlugin( 1925): [A] LEAVE onGetSupportInfo : 0
,E/Parcel  ( 1926): nm 16
,I/WVCdm   ( 1926): CdmEngine::OpenSession
,I/WVCdm   ( 1926): CdmEngine::QueryKeyControlInfo
,E/Parcel  ( 7331): nm 16
,E/Parcel  ( 1926): nm 16
,E/Parcel  ( 1926): nm 16
E/Parcel  ( 1926): nm 16
E/Parcel  ( 1926): nm 1
,I/WVCdm   ( 1926): CdmEngine::GenerateKeyRequest
,D/AmoledAdjustTimer( 2404): prevTemp = 281, currTemp = 283, prevStep = 4, currStep = 4
D/WVCdm   ( 1926): PrepareKeyRequest: nonce=2544109249
,I/Icing   ( 3286): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
,I/Icing   ( 3286): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,D/dalvikvm( 2851): GC_EXPLICIT freed 1684K, 23% free 10974K/14088K, paused 6ms+8ms, total 71ms
,E/Parcel  ( 7331): nm 1869
E/Parcel  ( 1926): nm 16
,I/WVCdm   ( 1926): CdmEngine::CloseSession
,W/Settings( 7331): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PhenotypeConfigurator( 2736): Scheduling Phenotype for one-off execution 799 seconds from now (1451923558945)
,D/GCM     ( 2851): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,D/dalvikvm( 7331): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/Mms/MessagesLockscreen( 5556): onReceive() action = com.android.mms.ui.MessagesLockscreenmSimSlot : [0] Mms = false count = 0
,D/GetConfigurationSnapshotOperation( 2736): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
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
,D/WearableService( 2736): callingUid 10012, callindPid: 2736
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
,E/MDM     ( 2736): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 3286): Restart initialization of location
,D/AuthorizationBluetoothService( 2851): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 2851): Proximity feature is not enabled.
,D/dalvikvm( 7455): DexOpt: load 7ms, verify+opt 18ms, 123556 bytes
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 7331): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 7331): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 1ms, rewrite 196ms
,D/libEGL  ( 7331): loaded /system/lib/egl/libEGL_mali.so
,I/PhenotypeFlagCommitter( 2736): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,D/libEGL  ( 7331): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7331): loaded /system/lib/egl/libGLESv2_mali.so
,I/ActivityManager( 2404): Killing 6575:com.sec.kidsplat.installer/u0a160 (adj 15): empty #43
W/GCoreFlp( 2736): No location to return for getLastLocation()
I/Mali    ( 7331): Mali API Version : 401
I/Mali    ( 7331): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
W/FusedLocationProvider( 2736): location=null
,I/GoogleURLConnFactory( 2736): Using platform SSLCertificateSocketFactory
,I/Mali    ( 7331): Mali API Version : 401
,I/Mali    ( 7331): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/dalvikvm( 2404): GC_EXPLICIT freed 1895K, 72% free 24755K/87680K, paused 14ms+19ms, total 286ms
,D/LocationManagerService( 2404): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,E/SPPClientService( 5461): [g] getNetMCC return empty string
,E/SPPClientService( 5461): [g] getNetMNC return empty string
I/Mali    ( 7331): Mali API Version : 401
,I/Mali    ( 7331): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/ChimeraCfgMgr( 3286): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3286): Module APK com.google.android.play.games already loaded
,W/PlaySystemBroadcastReceiver( 3286): Processed handlePeopleChanged at 171580
,D/ChimeraCfgMgr( 3286): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3286): Module APK com.google.android.play.games already loaded
,W/DataBroker( 3286): No player ID found and calling context is not the dest app
,I/CheckinRequestBuilder( 3286): Classify the device as Phone.
,I/dalvikvm( 3286): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.isUninstalledAppPossiblyUpdating
,W/dalvikvm( 3286): VFY: unable to resolve virtual method 490: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 3286): VFY: replacing opcode 0x6e at 0x000d
,D/LocationManagerService( 2404): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 3286): GC_CONCURRENT freed 1906K, 20% free 13025K/16088K, paused 9ms+9ms, total 105ms
,I/CheckinTask( 3286): Sending checkin request (11983 bytes)
,D/dalvikvm( 2736): GC_CONCURRENT freed 1871K, 21% free 11911K/15028K, paused 11ms+8ms, total 86ms
,I/CheckinRequestBuilder( 3286): Checkin reason type: 12 attempt count: 1
E/ActivityThread( 3286): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 3286): Classify the device as Phone.
,I/CheckinTask( 3286): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 3286): Checking schedule, now: 1451923560841 next: 1452481903813
,I/CheckinService( 3286): active receiver: disabled
,D/EnterpriseDeviceManagerService( 2404): Creating context as user 0
,D/CheckinService( 3286): Recording last checkin time for package unspecified as 1451923560879
,D/GCM     ( 2851): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/LocationManagerService( 2404): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService( 2404): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService( 2404): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService( 2404): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService( 2404): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/SurfaceFlinger( 1921): id=22 Removed Uoast (10/11)
,I/SurfaceFlinger( 1921): id=22 Removed Uoast (-2/11)
,D/PowerManagerService( 2404): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2404) eventTime = 174028
,D/PowerManagerService( 2404): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2404 (0x0)
,D/PowerManagerService( 2404): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2404, ws=WorkSource{1000}) (elapsedTime=3481)
,D/LocationManagerService( 2404): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,E/SPPClientService( 5461): [b] __ProvisionReply__
,D/LocationManagerService( 2404): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,E/SPPClientService( 5461): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5461): [d] null
,E/SPPClientService( 5461): [g] getPLMN return empty string
,E/SPPClientService( 5461): [b] SharedConstants.WHAT_PROV_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5461): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 5461): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5461): [g] getNetMCC return empty string
,I/PowerManagerService( 2404): [PWL] Off : 105s ago
,D/dalvikvm( 5461): GC_CONCURRENT freed 2108K, 25% free 10418K/13744K, paused 9ms+4ms, total 86ms
,D/PreloadUpdateManagerStateMachine( 6644): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 6644): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6644): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 6644): AutoUpdateTriggerManager:REQUEST2:requestInterval
,D/hcjo    ( 6644): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    ( 6644): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/PreloadUpdateManagerStateMachine( 6644): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
D/PreloadUpdateManagerStateMachine( 6644): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6644): entry::REQ_UPDATE_CHECK
,I/Volley  ( 6644): RestApi Request Add : 2315
,I/qtaguid ( 6644): Failed write_ctrl(t -1 8764893202948816896 -1) res=-1 errno=9
,I/qtaguid ( 6644): Tagging socket -1 with tag 79a327ee00000000(2040735726) for uid -1 failed errno=-9
,I/NetworkManagementSocketTagger( 6644): tagSocketFd(-1, 2040735726, -1) failed with errno-9
,I/qtaguid ( 6644): Failed write_ctrl(u -1) res=-1 errno=9
I/qtaguid ( 6644): Untagging socket -1 failed errno=-9
,W/NetworkManagementSocketTagger( 6644): untagSocket(-1) failed with errno -9
,D/PreloadUpdateManagerStateMachine( 6644): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
D/PreloadUpdateManagerStateMachine( 6644): exit::REQ_UPDATE_CHECK
D/PreloadUpdateManagerStateMachine( 6644): entry::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 6644): exit::NOTIFY_NOTIFICATION
,D/PreloadUpdateManagerStateMachine( 6644): entry::FINISH
D/PreloadUpdateManagerStateMachine( 6644): exit::FINISH
,D/PreloadUpdateManagerStateMachine( 6644): entry::IDLE
,I/ActivityManager( 2404): Waited long enough for: ServiceRecord{442fec28 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5068): Disconnected process message: 10
,E/SPPClientService( 5461): [b] __InitReply__
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/ActivityManager( 2404): Killing 6587:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty #43
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 340, Delta = -20
,D/AmoledAdjustTimer( 2404): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
,D/PackageManager( 2404): [MSG] SEND_PENDING_BROADCAST
,D/PackageManager( 2404): Sending to user 0: act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000000 Bundle[{android.intent.extra.changed_component_name=com.google.android.gms.checkin.CheckinService$ActiveReceiver, android.intent.extra.DONT_KILL_APP=true, android.intent.extra.UID=10012, android.intent.extra.changed_component_name_list=[Ljava.lang.String;@43160130, com.samsung.android.intent.extra.SECRET_APP=false, android.intent.extra.user_handle=0}]
,I/InputReader( 2404): Reconfiguring input devices.  changes=0x00000010
,D/RegisteredServicesCache( 2758): empty dynamic service
,I/PackageManager( 2404):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2404):   Scheme: "sms"
I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2404):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2404):   Scheme: "smsto"
I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2404):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2404):   Scheme: "mms"
I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2404):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2404):   Scheme: "mmsto"
I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2404):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2404):   Scheme: "sms"
I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2404):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2404):   Scheme: "smsto"
I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2404):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2404):   Scheme: "mms"
I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2404):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2404):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2404):   Scheme: "mmsto"
I/PackageManager( 2404): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/ActivityManager( 2404): Waited long enough for: ServiceRecord{45fbe2c0 u0 com.sec.spp.push/.PushClientService}
,I/Icing.InternalIcingCorporaProvider( 7373): Updating corpora: A: com.google.android.gms, C: MAYBE
,D/dalvikvm( 7170): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7170): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7170): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 7170): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 7170): VFY: unable to resolve instance field 36
,D/dalvikvm( 7170): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 7170): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7170): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7170): VFY: replacing opcode 0x62 at 0x0047
,D/FileShare-Server( 5921): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
D/dalvikvm( 7170): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 7170): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 7170): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42d7a9e8
D/dalvikvm( 7170): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42d7a9e8
,D/dalvikvm( 7170): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42d7a9e8, skipping init
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 7170): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42d7a9e8
,D/dalvikvm( 7170): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42d7a9e8
,V/JNIHelp ( 7170): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/BezelQuickConnect( 5054): BezelBroadcastReceiver - onReceive : android.intent.action.PACKAGE_CHANGED
,D/BezelQuickConnect( 5054): BezelBroadcastReceiver - packageName : com.google.android.gms
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageBroadcastService( 3286): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 3286): Null package name or gms related package.  Ignoreing.
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 7170): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42d7a9e8
,D/dalvikvm( 7170): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x42d7a9e8
D/dalvikvm( 7170): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42d7a9e8
,D/dalvikvm( 7170): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42d7a9e8
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2404): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/Icing   ( 3286): updateResources: need to parse f{com.google.android.gms}
,I/ProviderInstaller( 7170): Installed default security provider GmsCore_OpenSSL
,I/GCoreNlp( 2736): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/dalvikvm( 2736): GC_CONCURRENT freed 1658K, 20% free 12202K/15112K, paused 4ms+21ms, total 77ms
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/ApplicationsProvider( 2965): Could not fetch usage stats
W/ApplicationsProvider( 2965): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2965): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2965): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2965): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2965): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2965): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2965): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2965): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2965): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:212)
W/ApplicationsProvider( 2965): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2965): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2965): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/LocationProviderProxy( 2404): applying state to connected service
,D/LocationProviderProxy( 2404): applying state to connected service
,D/dalvikvm( 7170): Trying to load lib /data/app-lib/com.google.android.talk-1/libcronet.so 0x4227ec08
,D/dalvikvm( 7170): Added shared lib /data/app-lib/com.google.android.talk-1/libcronet.so 0x4227ec08
,I/Icing.InternalIcingCorporaProvider( 7373): UpdateCorporaTask done [took 1030 ms] updated apps [took 1030 ms] 
,D/dalvikvm( 7170): GC_CONCURRENT freed 6259K, 32% free 15850K/23280K, paused 5ms+6ms, total 99ms
,D/dalvikvm( 7170): WAIT_FOR_CONCURRENT_GC blocked 50ms
,D/dalvikvm( 7170): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 7170): VFY: unable to resolve instance field 1289
D/dalvikvm( 7170): VFY: replacing opcode 0x54 at 0x000c
D/dalvikvm( 7170): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 7170): DexOpt: unable to optimize instance field ref 0x0509 at 0x10 in Lorg/chromium/base/BuildInfo;.hasApkSplits
,I/Icing   ( 3286): Indexing 6A548C4C54436306D2E4399E19355D4210F156F8 from com.google.android.gms
,I/Icing   ( 3286): Indexing done 6A548C4C54436306D2E4399E19355D4210F156F8
,D/dalvikvm( 3286): GC_CONCURRENT freed 1745K, 18% free 13312K/16232K, paused 6ms+8ms, total 73ms
,I/Icing   ( 3286): Indexing 8AF1F6B88973B002A001A3BB90ED270D05322BB1 from com.google.android.googlequicksearchbox
,I/Icing   ( 3286): Indexing done 8AF1F6B88973B002A001A3BB90ED270D05322BB1
,I/Babel   ( 7170): Account registration complete:1-Redacted-21
,I/Babel   ( 7170): ProcessRegisterDeviceResponse
,I/Babel   ( 7170): Perform warm sync in case there are messages missed before the device is registered for account Redacted-21
,V/AlarmManager( 2404): waitForAlarm result :4
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/Babel   ( 7170): Invalid server experiment type 3 for BabelExperiment{id='dd8c17d9', experimentType=0, defaultBoolean=null, defaultLong=null}
,E/Babel   ( 7170): Invalid server experiment type 3 for BabelExperiment{id='6412be77', experimentType=0, defaultBoolean=null, defaultLong=null}
,D/dalvikvm( 7170): GC_CONCURRENT freed 1915K, 32% free 16053K/23280K, paused 6ms+8ms, total 91ms
,D/dalvikvm( 7170): WAIT_FOR_CONCURRENT_GC blocked 65ms
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): stay LED for fully charged
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2404): waitForAlarm result :4
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 330, Delta = -10
,V/AlarmManager( 2404): waitForAlarm result :8
,D/Headlines( 7041): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 7041): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7041): Breath 30031 latestRequest time : 1451923548551 current time : 1451923578582
,D/AmoledAdjustTimer( 2404): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:3, health:9, present:true, voltage: 4371, temperature: 284, technology: Li-ion, AC powered:false, USB powered:false, Wireless powered:false, icon:17303678, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/LightsService( 2404): [api] [SvcLED] turnOff:: id = 3 (uid: 0 pid: 0) 
,D/LightsService( 2404): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
,D/lights  ( 2404): led_pattern : 0 +
D/LightsService( 2404): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/lights  ( 2404): led_pattern : 0 -
,D/lights  ( 2404): button : 1 +
,D/lights  ( 2404): button : 1 -
D/BatteryService( 2404): turn off LED
D/PowerManagerService( 2404): [api] updateIsPoweredLocked : mIsPowered: false mPlugType: 0
I/PowerManagerService( 2404): !@[ps] Screen__On :  powered change
I/PowerManagerService( 2404): Waking up from sleep...
D/PowerManagerService( 2404): Screen Readiness Inspection requested: mNestCount=1
D/PowerManagerService( 2404): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 2404): [s] WAKEFULNESS_AWAKE
D/LightsService( 2404): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/PowerManagerService( 2404): [s] UserActivityState : 0 -> 1
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/PowerManagerService( 2404): [PWL] sb acquire: PowerManagerService.Display
D/DisplayPowerController( 2404): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
I/DisplayPowerController( 2404): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
I/DisplayPowerController( 2404): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
,I/SensorManagerA( 2404): getReportingMode :: sensor.mType = 5
D/DisplayPowerController( 2404): [DAB] setLightSensorEnabled : registerListener mLightSensor
D/PowerUI ( 2581): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/DisplayPowerController( 2404): [DAB] setLightSensorEnabled : updateAutoBrightnessSEC(false)
D/DisplayPowerController( 2404): [DAB] no lux value from sensor manager
D/DisplayPowerController( 2404): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/Sensors ( 2404): LightSensor setDelay = 200000000
,D/Sensors ( 2404): LightSensor setSensorDelay = 200000000
I/libsuspend( 2404): !@[s] autosuspend_autosleep_disable
I/libsuspend( 2404): !@[s] autosuspend_autosleep_disable done
D/Sensors ( 2404): Light sensor flush: not enabled 0
,D/Sensors ( 2404): LightSensor enable = 1
D/PowerManagerService( 2404): unblankAllDisplays() is called.
,D/PowerManagerService( 2404): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
D/Sensors ( 2404): LightSensor enableSensor = 1
V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5068): Disconnected process message: 10
D/SurfaceFlinger( 1921): Screen acquired, type=0 flinger=0x41226550
,D/SensorManager( 2404): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/SensorManagerA( 2404): getReportingMode :: sensor.mType = 1
,D/PowerManagerService( 2404): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 13ms
,I/Sensors ( 2404): HAL: batch Dry Run is complete
,I/Sensors ( 2404): HAL:resetDataRates mEnabled=4
D/UsbDeviceManager( 2404): handleMessage -> MSG_POWER_STATE = 0
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/RampAnimator( 2404): Light Animator Finished currentValue=8
D/PowerManagerService( 2404): [api] [s] wakeUp (uid: 10019 pid: 2581) eventTime = 196779
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:3 health:9
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.removeNotification:712 com.android.server.NotificationManagerService.cancelNotificationLocked:2470 com.android.server.NotificationManagerService.access$5100:162 
I/SensorManagerA( 2404): getReportingMode :: sensor.mType = 65558
,D/SensorManager( 2404): registerListener :: 2, MPL Accelerometer, 200000, 0,  
D/PowerManagerService( 2404): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 21ms
D/SensorService( 2404): AutoRotationSensor::changed settle time to [1]
D/SensorService( 2404): AutoRotationSensor::activate (ident=0x812f6328, enabled=1)
D/SensorService( 2404): AutoRotationSensor::AR_init
,I/Sensors ( 2404): HAL: batch Dry Run is complete
,D/NotificationService( 2404): cancelNotificationLocked
D/UsbDeviceManager( 2404): sending intent : ACTION_USB_CABLE_STATE : connected = false
,D/STATUSBAR-StatusBarManagerService( 2404): sendNotification(3) - 5
D/NotificationService( 2404):  hasClearableItems
D/NotificationService( 2404):  has clearable items no 
D/NotificationService( 2404): cancelNotificationLocked: cancel alarm
D/NotificationService( 2404): cancelNotificationLocked: cancel alarm
,I/Sensors ( 2404): HAL:resetDataRates mEnabled=4
D/LightsService( 2404): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2404) 
D/LightsService( 2404): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/UsbDeviceManager( 2404): received ACTION_POWER_DISCONNECTED = -1
D/LightsService( 2404): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 2404): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorManager( 2404): registerListener :: 1600221811, Screen Orientation Sensor, 66667, 0,  
,V/KeyguardServiceDelegate( 2404): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$32@43315440)
,D/KeyguardViewMediator( 2581): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 2581): notifyScreenOnLocked
D/KeyguardViewMediator( 2581): handleNotifyScreenOn
,D/KeyguardViewManager( 2581): onScreenTurnedOn()
I/KeyguardEffectViewMain( 2581): *** KeyguardEffectView getInstance ***
V/KeyguardViewManager( 2581): send wm null token: host was null
V/KeyguardServiceDelegate( 2404): **** SHOWN CALLED ****
,D/VisualEffectParticleEffect( 2581): KeyguardEffectViewParticleSpace : screenTurnedOn
D/InputDispatcher( 2404): setInputDispatchMode: enabled=1, frozen=0
,D/VisualEffectParticleEffect( 2581): screenOnAnimationStart
,I/WindowManager( 2404): No lock screen! windowToken=null
I/SELinux ( 7696): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7696):  
,D/PowerManagerNotifier( 2404): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
,D/PowerManagerService( 2404): Screen Readiness Inspection completed: mNestCount=0
,D/DisplayPowerController( 2404): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/DisplayPowerController( 2404): !@ElectronBeam exit
I/SurfaceFlinger( 1921): id=14 Removed FlectronBea (10/10)
I/SurfaceFlinger( 1921): id=14 Removed FlectronBea (-2/10)
,D/PowerManagerService( 2404): Excessive delay in ElectronBeam exit: 10ms
D/lights  ( 2404): lcd : 8 +
,D/lights  ( 2404): lcd : 8 -
D/DisplayPowerController( 2404): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2404): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/LockPatternUtils( 2581): isPcwEnable = 10
,D/BatteryMeterView( 2581): onDraw batteryColor : -1
,I/SELinux ( 7696): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7696):  
I/SELinux ( 7696):  
,I/SELinux ( 7696): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7696): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7696): >>>>> Normal User
,E/dalvikvm( 7696): >>>>> com.sec.android.Kies [ userId:0 | appId:1000 ]
,E/SELinux ( 7696): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/SensorService( 2404): AutoRotationSensor::process: Acc  eventTimestamp = 196875549678, previousAccTimestamp = 69160346893, difference = 127715202785 
,D/SensorService( 2404): AutoRotationSensor::reset oldrotation = [100], initState = [1]
,D/TimaKeyStoreProvider( 7696): in addTimaSignatureService
D/DisplayPowerController( 2404): [api] [DAB] onSensorChanged : 1st lux : 0.0
D/DisplayPowerController( 2404): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 0.0 < 15.0 (0.0)
,D/TimaKeyStoreProvider( 7696): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7696): Added TimaKesytore provider
,D/SurfaceControl( 2404): Excessive delay in unblankDisplay() while turning screen on: 229ms
,D/MISC PowerHAL( 2404): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/PowerManagerService( 2404): Excessive delay in mDisplayManagerService.unblankAllDisplaysFromPowerManager(): 233ms
D/MISC PowerHAL( 2404): sysfs_write +: /sys/class/input/input1/enabled: 1
D/SensorService( 2404): AutoRotationSensor::process: Acc  eventTimestamp = 196942213024, previousAccTimestamp = 69160346893, difference = 127781866131 
D/SensorService( 2404):  [AR] 0.3 -0.0 9.9
D/SensorService( 2404): AutoRotationSensor::process: Ar_SensorChanged oldrotation = [100], rotation = [255]
,D/LockPatternUtils( 2581): isPcwEnable = 10
,D/MISC PowerHAL( 2404): sysfs_write -: /sys/class/input/input1/enabled: 1
D/MISC PowerHAL( 2404): miscpower_set_interactive: /sys/class/input/input0/enabled
,D/MISC PowerHAL( 2404): sysfs_write +: /sys/class/input/input0/enabled: 1
,I/FPMS_FingerprintManagerService( 2601): onReceive: android.intent.action.USER_PRESENT
,I/NfcService( 2758): applyRouting return - 2 
,E/NfcService( 2758): callback == null
D/LightsService( 2404): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2404) 
D/LightsService( 2404): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService( 2404): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/PalmMotionService( 2404): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,D/PalmMotionService( 2404): SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService( 2404):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/LightsService( 2404): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SSRMv2:TSP:AirViewOnOff( 2404): SettingsAirViewInfo:: 000000000
,D/SamsungIME( 3003): showDlgMsgBox : false true true
,I/chromium( 6434): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/WifiTrafficPoller( 2404): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2404): ACTION_SCREEN_ON
,D/LightsService( 2404): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2404) 
D/LightsService( 2404): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2404): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2404): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/chromium( 6434): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
D/MISC PowerHAL( 2404): sysfs_write -: /sys/class/input/input0/enabled: 1
I/AudioHardwareTinyALSA( 1926): setParameters(screen_state=on)
D/MISC PowerHAL( 2404): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 2404): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 2404): Excessive delay in MISC setInteractive(true) while turning screen on: 165ms
D/SEC PowerHAL( 2404): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2404): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2404): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2404): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2404): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2404): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2404): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
,D/SEC PowerHAL( 2404): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
D/PowerManagerService( 2404): Excessive delay in nativeSetInteractive(true): 166ms
D/PowerManagerService( 2404): SecHardwareInterface.setBatteryADC : true
,I/SecExternalDisplayIntents_Java( 2404): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,E/libGLESv2( 6434): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 6434): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,D/IpRemoteDisplayController( 2404): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 2404): Bridge Server is not available
,D/dalvikvm( 7696): GC_CONCURRENT freed 2996K, 31% free 9567K/13740K, paused 7ms+3ms, total 62ms
,D/dalvikvm( 7696): WAIT_FOR_CONCURRENT_GC blocked 48ms
,D/PersonaManagerService( 2404): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 2404): MSG_ACTION_SCREEN_ON called
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/StatusBarManagerService( 2404): semi p:6434,o:f
,I/KIES_RECEIVE( 7696): [APK BnR] Receive KIES_USB_DISCONNECT
,W/ContextImpl( 7696): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 android.content.ContextWrapper.stopService:511 com.sec.android.Kies.kies_receiver.onReceive:170 android.app.ActivityThread.handleReceiver:2698 
D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,I/NfcService( 2758): NFC: Screen On & Cover Open
,I/NfcService( 2758): applyRouting return - 2 
E/TranscodeReceiver( 6940): onReceive : android.intent.action.ACTION_POWER_DISCONNECTED
E/libGLESv2( 6434): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 6434): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/NfcService( 2758): callback == null
,D/videowall-Global( 6940): core_num = 4
,E/libGLESv2( 6434): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 6434): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,D/dalvikvm( 6940): No JNI_OnLoad found in /system/lib/libsavsff.so 0x422ce720, skipping init
,D/STATUSBAR-NetworkController( 2581): onSignalStrengthsChanged signalStrength=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0x0 level=0
,W/linker  ( 6940): libvwengine.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/videowall-Global( 6940): density : 2.0 width : 720 height : 1280 Raw width : 720 Raw height : 1280
,D/videowall-Global( 6940): dsp : 720, swkey : false, Cores : 4, Clock : 0
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = -10
,I/SELinux ( 7713): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7713):  
,D/QuickConnect[1.1][2] ( 5042): PeriphService.mBroadcastReceiver - SCREEN_ON when user = 0
V/QuickConnect[1.1][2] ( 5042): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5042): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5042): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42289560
V/QuickConnect[1.1][2] ( 5042): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42289560
V/QuickConnect[1.1][2] ( 5042): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 5042): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42289560
V/QuickConnect[1.1][2] ( 5042): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42289560
V/QuickConnect[1.1][2] ( 5042): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42289560
D/QuickConnect[1.1][2] ( 5042): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 5042): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 5042): BleHelper.startScan - shouldScanBleBg = false
D/QuickConnect[1.1][2] ( 5042): BleHelper.startScan - shouldScanBleFg = false
I/SELinux ( 7713): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7713):  
I/SELinux ( 7713):  
I/SELinux ( 7713): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7713): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7713): >>>>> Normal User
E/dalvikvm( 7713): >>>>> com.google.android.apps.uploader [ userId:0 | appId:10117 ]
,E/SELinux ( 7713): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/daemonapp( 5267): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5267): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5267): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionSCREEN_ON
,D/PowerManagerService( 2404): [PWL] sb release: PowerManagerService.Broadcasts
,D/TimaKeyStoreProvider( 7713): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7713): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7713): Added TimaKesytore provider
,D/dalvikvm( 7713): GC_CONCURRENT freed 3001K, 31% free 9572K/13748K, paused 2ms+2ms, total 23ms
,D/dalvikvm( 7713): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 2404): GC_CONCURRENT freed 3579K, 72% free 24910K/87680K, paused 18ms+20ms, total 231ms
,I/iu.Environment( 5692): update battery state; isPlugged? false*
I/ActivityManager( 2404): Killing 6599:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty #43
,I/iu.Environment( 3286): update battery state; isPlugged? false*
,I/iu.UploadsManager( 3286): num queued entries: 0
,I/iu.UploadsManager( 5692): num queued entries: 0
,I/iu.UploadsManager( 3286): num updated entries: 0
I/iu.UploadsManager( 5692): num updated entries: 0
,I/iu.SyncManager( 3286): NEXT; no task
,I/iu.SyncManager( 5692): NEXT; no task
,I/GCoreUlr( 2736): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_DISCONNECTED}]
,D/PicasaUploader( 7713):    wifiOnlyPhoto changed to true
D/PicasaUploader( 7713):    wifiOnlyVideo changed to true
I/GCoreUlr( 2736): DispatchingService.onCreate()
,D/PicasaUploader( 7713):    syncOnBattery changed to true
,D/PicasaUploaderSync( 7713): sync account database
,D/PicasaUploaderSync( 7713): accounts in DB=1
,D/PicasaUploaderSyncManager( 7713): active network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PicasaUploaderSyncManager( 7713): background data: true
,D/PicasaUploaderSyncManager( 7713): battery info: false
,I/GCoreUlr( 2736): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_DISCONNECTED
,D/LockPatternUtils( 2581): isPcwEnable = 10
,D/daemonapp( 5267): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5267): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5267): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5267): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5267): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 5267): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5267): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5267): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 5267): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5267): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5267): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 5267): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5267): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 5267): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1451943240000
D/daemonapp( 5267): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1451923585870
,D/daemonapp( 5267): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5267): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,I/GCoreUlr( 2736): WorldUpdater:android.intent.action.ACTION_POWER_DISCONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2736): Unbound from all location providers
,I/GCoreUlr( 2736): Place inference reporting - stopped
,D/daemonapp( 5267): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5267): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5267): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5267): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/GCoreUlr( 2736): DispatchingService.onDestroy()
,I/GCoreUlr( 2736): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2736): Unbound from all location providers
,I/GCoreUlr( 2736): Place inference reporting - stopped
,D/dalvikvm( 5267): GC_CONCURRENT freed 2613K, 28% free 10031K/13816K, paused 18ms+6ms, total 116ms
,D/dalvikvm( 5267): WAIT_FOR_CONCURRENT_GC blocked 39ms
,E/Watchdog( 2404): !@Sync 6
D/daemonapp( 5267): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 5267): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 5267): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5267): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5267): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 5267): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5267): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5267): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 5267): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 5267): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5267): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 5267): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5267): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5267): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 5267): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5267): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/SSRMv2:TSP:AirViewOnOff( 2404): SettingsAirViewInfo:: 000000000
,D/lights  ( 2404): button : 0 +
,D/lights  ( 2404): button : 0 -
,D/SensorService( 2404):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer( 2404): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2404):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2404):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService( 2404): level:100, scale:100, status:2, health:2, present:true, voltage: 4355, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/PowerManagerService( 2404): [api] updateIsPoweredLocked : mIsPowered: true mPlugType: 2
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/PowerUI ( 2581): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/PowerManagerService( 2404): [api] [s] wakeUp (uid: 10019 pid: 2581) eventTime = 206689
D/PowerUI ( 2581): playSound : 1
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
D/UsbDeviceManager( 2404): handleMessage -> MSG_POWER_STATE = 1
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,V/Vibrator( 2581): Called vibrateImmVibe(int) API - PUID: 10019, PackageName: com.android.keyguard
,V/Vibrator( 2581): vibrateImmVibe - PUID: 10019, PackageName: com.android.keyguard, type: 10, magType: TouchMagnitude
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
I/EntropyMixer( 2404): Writing entropy...
V/VibratorService( 2404): vibrateImmVibeMagnitudeType - magnitudeType: TouchMagnitude
V/VibratorService( 2404): vibrate - package: com.android.keyguard, ms: 100, token: null
D/VibratorService( 2404): JNI vibratorOff()
D/VibratorService( 2404): JNI vibratorOn() : 100
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
D/PowerUI ( 2581): RINGER_MODE_VIBRATE
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,E/TranscodeReceiver( 6940): onReceive : android.intent.action.ACTION_POWER_CONNECTED
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
D/UsbDeviceManager( 2404): sending intent : ACTION_USB_CABLE_STATE : connected = true
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,D/BatteryMeterView( 2581): onDraw batteryColor : -1
I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,D/TranscodeService( 6940): onCreate()
,I/SCloudBackupReceiver( 6977): Other Intent
,D/dalvikvm( 6940): No JNI_OnLoad found in /system/lib/libsavsvc.so 0x422ce720, skipping init
,D/dalvikvm( 6940): No JNI_OnLoad found in /system/lib/libsavscmn.so 0x422ce720, skipping init
D/PicasaUploaderSyncManager( 7713): battery info: true
D/dalvikvm( 6940): No JNI_OnLoad found in /system/lib/libsthmb.so 0x422ce720, skipping init
,I/iu.Environment( 5692): update battery state; isPlugged? true*
D/TranscodeService( 6940): power? : true / screen off : false
,D/TranscodeService( 6940): releaseTranscodeThread.
,I/iu.UploadsManager( 5692): num queued entries: 0
,I/iu.UploadsManager( 5692): num updated entries: 0
,I/iu.SyncManager( 5692): NEXT; no task
,D/VibratorService( 2404): JNI vibratorOff()
I/iu.FingerprintManager( 5692): Start processing all media
I/iu.FingerprintManager( 5692): Start processing media store URI: content://media/external/images/media
,I/iu.Environment( 3286): update battery state; isPlugged? true*
,I/iu.UploadsManager( 3286): num queued entries: 0
,I/iu.UploadsManager( 3286): num updated entries: 0
,I/iu.FingerprintManager( 5692): Start processing media store URI: content://media/external/video/media
,I/iu.SyncManager( 3286): NEXT; no task
,E/NetworkScheduler.SchedulerReceiver( 2851): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 2851): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/GCoreUlr( 2736): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_CONNECTED}]
,I/GCoreUlr( 2736): DispatchingService.onCreate()
,I/iu.FingerprintManager( 3286): Start processing all media
,I/iu.FingerprintManager( 5692): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 3286): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 5692): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 3286): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 5692): Finished generating fingerprints; 0.078 seconds
,I/iu.FingerprintManager( 5692):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/iu.FingerprintManager( 3286): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 3286): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 3286): Finished generating fingerprints; 0.057 seconds
,I/iu.FingerprintManager( 3286):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/GCoreUlr( 2736): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_CONNECTED
,I/GCoreUlr( 2736): WorldUpdater:android.intent.action.ACTION_POWER_CONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2736): Unbound from all location providers
,I/GCoreUlr( 2736): Place inference reporting - stopped
,I/GCoreUlr( 2736): DispatchingService.onDestroy()
,I/GCoreUlr( 2736): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2736): Unbound from all location providers
,I/GCoreUlr( 2736): Place inference reporting - stopped
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/SensorService( 2404):   0.2 -0.0 9.8
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer( 2404): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,I/ActivityManager( 2404): Waited long enough for: ServiceRecord{44b1da10 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,D/SensorService( 2404):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2404):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/PowerManagerService( 2404): [api] acquire WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2581
W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-StatusBarManagerService( 2404): sendNotification(1) - 5
,D/NotificationService( 2404): Sending broadcast with sbn as extra = StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=5 tag=null score=0: Notification(pri=0 icon=7f0200a5 contentView=com.android.systemui/0x1090080 vibrate=null sound=null defaults=0x0 flags=0x2 when=0 ledARGB=0x0 contentIntent=Y deleteIntent=N contentTitle=4 contentText=38 originalPackageName=N tickerText=38 kind=[null]))
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.NotificationManagerService$7.run:2187 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:146 
D/RCPManagerService( 2404): NotificationReceiver onReceive()
D/RCPManagerService( 2404):  NotificationReceiver sbn.getPackageName() com.android.systemui sbn.getUser().getIdentifier() -1
D/RCPManagerService( 2404): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-sanitize-data ; token = 4294967298404
D/RCPManagerService( 2404): getPolicy: policy value returned = false
,D/RCPManagerService( 2404): going to get the app label for pkg == com.android.systemui
D/RCPManagerService( 2404): app label == com.android.systemui
,D/RCPManagerService( 2404): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-export-data ; token = 4294967298404
D/RCPManagerService( 2404): getPolicy: policy value returned = true
D/UserManagerService( 2404): User -1does not exists!!
D/RCPManagerService( 2404): Calling User is -1
,D/RCPManagerService( 2404): userid of SBN ==-1
E/PersonaManagerService( 2404): returning null in  getPersonasForUser
,D/ProgressBar( 2581): setProgressDrawable drawableHeight = 12
,D/PhoneStatusBar( 2581): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@422df810
,V/AlarmManager( 2404): waitForAlarm result :4
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/ChimeraCfgMgr( 3286): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3286): Module APK com.google.android.play.games already loaded
,D/BatteryMeterView( 2581): onDraw batteryColor : -1
,E/ActivityThread( 3286): Failed to find provider info for com.android.contacts.metadata
,I/dalvikvm( 3286): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.server.GmsNetworkTrafficStats.setThreadStatsTag
W/dalvikvm( 3286): VFY: unable to resolve virtual method 1312: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 3286): VFY: replacing opcode 0x6e at 0x0033
,D/SyncManager( 2404): failed sync operation 
,D/SyncManager( 2404): not retrying sync operation because the error is a hard error: 
,V/AccountUtils( 3286): 0 accounts found with uca feature
,I/GamesSyncAdapter( 3286): Starting sync for 3a3529a
,I/GamesSyncAdapter( 3286): Sync duration for 3a3529a: 8
,D/ChimeraCfgMgr( 3286): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3286): Module APK com.google.android.play.games already loaded
,I/dalvikvm( 3286): Could not find method android.content.Context.checkSelfPermission, referenced from method com.google.android.gms.common.permission.PermissionUtils.getMissingPermissionGroups
W/dalvikvm( 3286): VFY: unable to resolve virtual method 340: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,D/dalvikvm( 3286): VFY: replacing opcode 0x6e at 0x0036
,D/ChimeraCfgMgr( 3286): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3286): Module APK com.google.android.play.games already loaded
,E/dalvikvm( 3286): Could not find class 'android.graphics.drawable.RippleDrawable', referenced from method com.google.android.gms.games.ui.util.UiUtils.constructButtonBackground
W/dalvikvm( 3286): VFY: unable to resolve new-instance 178 (Landroid/graphics/drawable/RippleDrawable;) in Lcom/google/android/gms/games/ui/util/UiUtils;
,D/dalvikvm( 3286): VFY: replacing opcode 0x22 at 0x0013
,D/dalvikvm( 3286): DexOpt: unable to opt direct call 0x0396 at 0x1a in Lcom/google/android/gms/games/ui/util/UiUtils;.constructButtonBackground
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/SensorService( 2404):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,V/AlarmManager( 2404): waitForAlarm result :8
,D/Headlines( 7041): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 7041): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 7041): Breath 60016 latestRequest time : 1451923548551 current time : 1451923608567
,D/AmoledAdjustTimer( 2404): prevTemp = 283, currTemp = 285, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,I/ActivityManager( 2404): Waited long enough for: ServiceRecord{431e0920 u0 com.sec.android.app.videoplayer/.videowall.TranscodeService}
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/dalvikvm( 3286): Note: class Lcom/google/android/gms/games/internal/IGamesService$Stub; has 208 unimplemented (abstract) methods
,D/SensorService( 2404):   0.3 -0.0 9.9
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2404):   0.3 -0.0 9.8
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2404): !@Sync 7
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2404):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/PowerManagerService( 2404): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 2404): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2404): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/lights  ( 2404): lcd : 2 +
D/RampAnimator( 2404): Light Animator Finished currentValue=2
,D/lights  ( 2404): lcd : 2 -
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/daemonapp( 5267): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5267): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5267): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionTIME_TICK
,D/daemonapp( 5267): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5267): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5267): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5267): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5267): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 5267): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 5267): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5267): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5267): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 5267): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 5267): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 5267): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 5267): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5267): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 5267): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5267): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/SensorService( 2404):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2404):   0.2 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/PowerManagerService( 2404): [s] UserActivityState : 2 -> 0
I/PowerManagerService( 2404): [PWL] On : 196750 (39935 ms ago)
,I/PowerManagerService( 2404): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
,I/PowerManagerService( 2404): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=2581, ws=null) (elapsedTime=19942)
,D/PowerManagerService( 2404): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2581 (0x0)
I/PowerManagerService( 2404): Nap time...
,D/PowerManagerService( 2404): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2404): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2404): Going to sleep due to screen timeout...
D/PowerManagerService( 2404): [s] WAKEFULNESS_ASLEEP
D/DisplayPowerController( 2404): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/DisplayPowerController( 2404): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/Sensors ( 2404): LightSensor enable = 0
,D/Sensors ( 2404): LightSensor enableSensor = 0
D/DisplayPowerController( 2404): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,I/DisplayPowerController( 2404): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
,I/SurfaceFlinger( 1921): id=23 createSurf (720x1280),-1 flag=20004, FlectronBea
D/SensorManager( 2404): unregisterListener ::   
I/Sensors ( 2404): HAL:resetDataRates mEnabled=4
,D/DisplayPowerController( 2404): !@ElectronBeam entry
,D/SensorManager( 2404): unregisterListener ::   
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/lights  ( 2404): lcd : 0 +
,D/lights  ( 2404): lcd : 0 -
D/MISC PowerHAL( 2404): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2404): sysfs_write +: /sys/class/input/input1/enabled: 0,
D/PowerManagerService( 2404): blankAllDisplays() is called.
D/MISC PowerHAL( 2404): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2404): miscpower_set_interactive: /sys/class/input/input0/enabled
D/MISC PowerHAL( 2404): sysfs_write +: /sys/class/input/input0/enabled: 0
D/PowerManagerService( 2404): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/PowerManagerService( 2404): [PWL] sb acquire: PowerManagerService.Broadcasts
V/WindowOrientationListener( 2404): WindowOrientationListener disabled
D/SensorService( 2404): AutoRotationSensor::activate (ident=0x812f6328, enabled=0)
,I/Sensors ( 2404): HAL: batch Dry Run is complete
D/MISC PowerHAL( 2404): sysfs_write -: /sys/class/input/input0/enabled: 0
,D/MISC PowerHAL( 2404): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
,D/MISC PowerHAL( 2404): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,D/PowerManagerService( 2404): [PWL] sb release: PowerManagerService.Display
D/SEC PowerHAL( 2404): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2404): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/KeyguardViewMediator( 2581): onScreenTurnedOff(3)
D/SEC PowerHAL( 2404): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2404): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2404): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2404): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SensorManager( 2404): unregisterListener ::   
D/SEC PowerHAL( 2404): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
D/InputDispatcher( 2404): setInputDispatchMode: enabled=0, frozen=0
,D/SEC PowerHAL( 2404): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/PowerManagerService( 2404): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/SurfaceFlinger( 1921): Screen released, type=0 flinger=0x41226550
,D/LockPatternUtils( 2581): isPcwEnable = 10
,D/LockPatternUtils( 2581): isPcwEnable = 10
,D/SurfaceControl( 2404): Excessive delay in blankDisplay() while turning screen off: 211ms
,I/libsuspend( 2404): !@[s] autosuspend_autosleep_enable
,I/libsuspend( 2404): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2404): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 214ms
D/PowerManagerService( 2404): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService( 2404): [PWL] Off : 0s ago
I/PowerManagerService( 2404): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2404): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2404): [PWL]       PARTIAL_WAKE_LOCK              'ActivityManager-Sleep' (uid=1000, pid=2404, ws=null) (elapsedTime=212)
I/PowerManagerService( 2404): [PWL]   PowerManagerService.Broadcasts: ref count=1
,D/KeyguardViewMediator( 2581): setting alarm to turn off keyguard, seq = 2
,I/SensorManagerA( 2404): getReportingMode :: sensor.mType = 5
D/LightsService( 2404): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2404) 
,D/LightsService( 2404): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/Sensors ( 2404): LightSensor setDelay = 200000000
D/Sensors ( 2404): LightSensor setSensorDelay = 200000000
D/Sensors ( 2404): Light sensor flush: not enabled 0
D/Sensors ( 2404): LightSensor enable = 1
D/Sensors ( 2404): LightSensor enableSensor = 1
,D/SensorManager( 2404): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/BatteryService( 2404): turn on LED for fully charged
I/SQLiteSecureOpenHelper( 4150): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4150): getDatabaseLocked(b,b,pwd)...
D/VibratorService( 2404): JNI vibratorOff()
,I/WifiTrafficPoller( 2404): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2404): ACTION_SCREEN_OFF
D/LightsService( 2404): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2404) 
,D/LightsService( 2404): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/AudioHardwareTinyALSA( 1926): setParameters(screen_state=off)
I/SecExternalDisplayIntents_Java( 2404): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2404): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2404): Bridge Server is not available
,D/PersonaManagerService( 2404): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2404): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2581):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2581): makeExpandedInvisible
D/PhoneStatusBarView( 2581): marqueeStatusBar:122, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2581):      ACTION_SCREEN_OFF is finished!!!! 
,I/NfcService( 2758): applyRouting return - 2 
,E/NfcService( 2758): callback == null
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/LockPatternUtils( 2581): isPcwEnable = 10
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 320, Delta = 0
D/QuickConnect[1.1][2] ( 5042): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
V/QuickConnect[1.1][2] ( 5042): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5042): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5042): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42289560
V/QuickConnect[1.1][2] ( 5042): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42289560
D/QuickConnect[1.1][2] ( 5042): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 5042): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 5042): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 5042): stopLeScan()
D/QuickConnect[1.1][2] ( 5042): BleHelper.stopScan - call stopLeScan() complete
,E/TranscodeReceiver( 6940): onReceive : android.intent.action.SCREEN_OFF
,D/TranscodeService( 6940): power? : true / screen off : true
D/PowerManagerService( 2404): [PWL] sb release: PowerManagerService.Broadcasts
,D/TranscodeService( 6940): Music is = false
,D/TranscodeService( 6940): runvideoplayer is false
,D/TranscodeService( 6940): Thread start
D/TranscodeService( 6940): WakeLock.acquire()
,D/videowall-FileMgr( 6940): thumbnailDBSync -1
D/Sensors ( 2404): LightSensor enable = 0
,D/Sensors ( 2404): LightSensor enableSensor = 0
D/SensorManager( 2404): unregisterListener ::   
,D/lights  ( 2404): led_pattern : 5 +
D/LightsService( 2404): [SvcLED]  onSensorChanged::light value = 0
,D/lights  ( 2404): led_pattern : 5 -
D/LightsService( 2404): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/WVMDrmPlugIn( 1925): WVMDrmPlugin::onInitialize : 2229
D/WVMDrmPlugIn( 1925): WVMDrmPlugin::onSetOnInfoListener : add 2229
I/PrGenericPlugin( 1925): [A] ENTER onInitialize : 0x8b5
,I/PrGenericPlugin( 1925): [A] LEAVE onInitialize : 0x8b5
,D/TranscodeService( 6940): Thread end
,D/TranscodeService( 6940): WakeLock.release()
,D/TranscodeService( 6940): onDestroy()
,D/TranscodeService( 6940): releaseTranscodeThread.
,V/ApplicationPolicy( 2404): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
,D/AmoledAdjustTimer( 2404): prevTemp = 286, currTemp = 288, prevStep = 4, currStep = 4,
,V/AlarmManager( 2404): waitForAlarm result :4,
,D/KeyguardViewMediator( 2581): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2,
,D/LockPatternUtils( 2581): isPcwEnable = 10,
,D/KeyguardViewMediator( 2581): in doKeyguardLocked mIsRollUp false null,
,D/PersonaManager( 2581): isKioskContainerExistOnDevice,
,D/LockPatternUtils( 2581): isPcwEnable = 10,
D/LockPatternUtils( 2581): isPcwEnable = 10
,D/KeyguardViewMediator( 2581): doKeyguard: not showing because lockscreen is off,
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/PowerManagerService( 2404): [PWL] Off : 5s ago,
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2404): waitForAlarm result :4,
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2404): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2404): [PWL] Off : 15s ago,
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/BatteryService( 2404): stay LED for fully charged
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5068): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0,
,E/Watchdog( 2404): !@Sync 8,
,D/AmoledAdjustTimer( 2404): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4,
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
,D/BatteryService( 2404): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,I/PowerManagerService( 2404): [PWL] Off : 30s ago,
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0,
,V/AlarmManager( 2404): waitForAlarm result :4,
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/Headlines( 7041): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 7041): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 7041): Breath 106862 latestRequest time : 1451923548551 current time : 1451923655413,
,D/AmoledAdjustTimer( 2404): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4,
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0,
,V/AlarmManager( 2404): waitForAlarm result :8,
,D/Headlines( 7041): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 7041): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
D/Headlines( 7041): Breath 120026 latestRequest time : 1451923548551 current time : 1451923668577
,D/Headlines( 7041): stop ,
,D/Headlines( 7041): Breath.onDestroy : ,
I/ActivityManager( 2404): Killing 6613:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty #43
,D/AmoledAdjustTimer( 2404): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4,
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2404): mCoverManager.getCoverState() : true,
,D/BatteryService( 2404): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5068): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2404): [PWL] Off : 50s ago,
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0,
,E/Watchdog( 2404): !@Sync 9,
,I/ClearcutLoggerApiImpl( 3286): disconnect managed GoogleApiClient,
,D/AmoledAdjustTimer( 2404): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4,
,V/AlarmManager( 2404): waitForAlarm result :8,
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4380, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2404): stay LED for fully charged,
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 5068): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4,
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2404): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/TimaService( 2404): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2404): TimaServiceHandler.handleMessage what =1
,D/TimaService( 2404): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 2404): initializing...
,I/TLC_TIMA_PKM_initialize( 2404): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 2404): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2404): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2404): input max_recvmsg_size = 262196
,I/TZ: mc_tlc_communication( 2404): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2404): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2404): aligned max_sendmsg_size = 262208
,I/TZ: mc_tlc_communication( 2404): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2404): device_id = 0x0
,I/TZ: mc_tlc_communication( 2404): tlc_open() was called
,I/TZ: mc_tlc_communication( 2404): Opening MobiCore device
,I/TZ: mc_tlc_communication( 2404): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 2404): Opening the session
,I/TZ: mc_tlc_communication( 2404): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 2404): Trustlet response is completed
,I/PowerManagerService( 2404): [PWL] Off : 75s ago
I/PowerManagerService( 2404): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2404): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2404): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2404, ws=null) (elapsedTime=398)
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2404): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2404): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 284, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 310, Delta = 0
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AmoledAdjustTimer( 2404): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/dalvikvm( 2404): GC_CONCURRENT freed 3129K, 71% free 25543K/87268K, paused 24ms+20ms, total 269ms
,I/PowerManagerService( 2404): [PWL] Off : 105s ago
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = -10
,E/Watchdog( 2404): !@Sync 11
,D/AmoledAdjustTimer( 2404): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2404): waitForAlarm result :4
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 8318): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8318):  
,I/SELinux ( 8318): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8318):  
I/SELinux ( 8318):  
,I/SELinux ( 8318): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8318): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 8318): >>>>> Normal User
,E/dalvikvm( 8318): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 8318): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 8318): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8318): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8318): Added TimaKesytore provider
,D/dalvikvm( 8318): GC_CONCURRENT freed 2998K, 31% free 9567K/13740K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 8318): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/ActivityManager( 2404): Killing 5868:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty #43
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2404): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2404): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :4
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/Parcel  ( 2404): Class not found when unmarshalling: com.sec.spp.push.notisvc.alarm.DVCRegistrationAlarmHandler
E/Parcel  ( 2404): java.lang.ClassNotFoundException: com.sec.spp.push.notisvc.alarm.DVCRegistrationAlarmHandler
E/Parcel  ( 2404): 	at java.lang.Class.classForName(Native Method)
E/Parcel  ( 2404): 	at java.lang.Class.forName(Class.java:251)
E/Parcel  ( 2404): 	at java.lang.Class.forName(Class.java:216)
E/Parcel  ( 2404): 	at android.os.Parcel.readParcelableCreator(Parcel.java:2133)
E/Parcel  ( 2404): 	at android.os.Parcel.readParcelable(Parcel.java:2097)
E/Parcel  ( 2404): 	at android.os.Parcel.readValue(Parcel.java:2013)
E/Parcel  ( 2404): 	at android.os.Parcel.readArrayMapInternal(Parcel.java:2314)
E/Parcel  ( 2404): 	at android.os.Bundle.unparcel(Bundle.java:249)
E/Parcel  ( 2404): 	at android.os.Bundle.putAll(Bundle.java:331)
E/Parcel  ( 2404): 	at android.content.Intent.fillIn(Intent.java:7170)
E/Parcel  ( 2404): 	at com.android.server.am.PendingIntentRecord.sendInner(PendingIntentRecord.java:212)
E/Parcel  ( 2404): 	at com.android.server.am.PendingIntentRecord.send(PendingIntentRecord.java:194)
E/Parcel  ( 2404): 	at android.app.PendingIntent.send(PendingIntent.java:705)
E/Parcel  ( 2404): 	at android.app.PendingIntent.send(PendingIntent.java:659)
E/Parcel  ( 2404): 	at com.android.server.AlarmManagerService$AlarmThread.run(AlarmManagerService.java:1570)
E/Parcel  ( 2404): Caused by: java.lang.NoClassDefFoundError: com/sec/spp/push/notisvc/alarm/DVCRegistrationAlarmHandler
E/Parcel  ( 2404): 	... 15 more
E/Parcel  ( 2404): Caused by: java.lang.ClassNotFoundException: Didn't find class "com.sec.spp.push.notisvc.alarm.DVCRegistrationAlarmHandler" on path: DexPathList[[directory "."],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
E/Parcel  ( 2404): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:67)
E/Parcel  ( 2404): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:497)
E/Parcel  ( 2404): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:457)
E/Parcel  ( 2404): 	... 15 more
,W/Intent  ( 2404): Failure filling in extras
W/Intent  ( 2404): android.os.BadParcelableException: ClassNotFoundException when unmarshalling: com.sec.spp.push.notisvc.alarm.DVCRegistrationAlarmHandler
W/Intent  ( 2404): 	at android.os.Parcel.readParcelableCreator(Parcel.java:2147)
W/Intent  ( 2404): 	at android.os.Parcel.readParcelable(Parcel.java:2097)
W/Intent  ( 2404): 	at android.os.Parcel.readValue(Parcel.java:2013)
W/Intent  ( 2404): 	at android.os.Parcel.readArrayMapInternal(Parcel.java:2314)
W/Intent  ( 2404): 	at android.os.Bundle.unparcel(Bundle.java:249)
W/Intent  ( 2404): 	at android.os.Bundle.putAll(Bundle.java:331)
W/Intent  ( 2404): 	at android.content.Intent.fillIn(Intent.java:7170)
W/Intent  ( 2404): 	at com.android.server.am.PendingIntentRecord.sendInner(PendingIntentRecord.java:212)
W/Intent  ( 2404): 	at com.android.server.am.PendingIntentRecord.send(PendingIntentRecord.java:194)
W/Intent  ( 2404): 	at android.app.PendingIntent.send(PendingIntent.java:705)
W/Intent  ( 2404): 	at android.app.PendingIntent.send(PendingIntent.java:659)
W/Intent  ( 2404): 	at com.android.server.AlarmManagerService$AlarmThread.run(AlarmManagerService.java:1570)
V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 8444): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8444):  
,I/SELinux ( 8444): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8444):  
I/SELinux ( 8444):  
,I/SELinux ( 8444): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8444): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 8444): >>>>> Normal User
,E/dalvikvm( 8444): >>>>> com.sec.spp.push:RemoteNotiProcess [ userId:0 | appId:10039 ]
,E/SELinux ( 8444): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 8444): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8444): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8444): Added TimaKesytore provider
,D/dalvikvm( 8444): GC_CONCURRENT freed 3001K, 31% free 9570K/13748K, paused 2ms+3ms, total 28ms
,D/dalvikvm( 8444): WAIT_FOR_CONCURRENT_GC blocked 25ms
,E/SPPClientService( 8444): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 8444): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 8444): PushLog.txt file is not deleted.
,D/SPPClientService( 8444): PushLog.txt file is not deleted.
,D/SPPClientService( 8444): ============PushLog. stop!
,I/SELinux ( 8467): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8467):  
I/ActivityManager( 2404): Killing 6282:com.sec.pcw.device/1000 (adj 15): empty #43
,I/SELinux ( 8467): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8467):  
I/SELinux ( 8467):  
,I/SELinux ( 8467): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8467): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 8467): >>>>> Normal User
,E/dalvikvm( 8467): >>>>> com.sec.spp.push:RemoteDlcProcess [ userId:0 | appId:10039 ]
,E/SELinux ( 8467): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 8467): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8467): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8467): Added TimaKesytore provider
,D/dalvikvm( 8467): GC_CONCURRENT freed 3005K, 31% free 9561K/13744K, paused 3ms+3ms, total 27ms
,D/dalvikvm( 8467): WAIT_FOR_CONCURRENT_GC blocked 24ms
,E/SPPClientService( 5461): [b] __PingReply__
,E/SPPClientService( 8467): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 8467): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 8467): PushLog.txt file is not deleted.
,D/SPPClientService( 8467): PushLog.txt file is not deleted.
,D/SPPClientService( 8467): ============PushLog. stop!
,I/System.out( 8467): Thread-692(HTTPLog):isShipBuild true
,I/System.out( 8467): Thread-692(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 8444): Thread-687(HTTPLog):isShipBuild true
,I/System.out( 8444): Thread-687(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/ActivityManager( 2404): Killing 5972:com.sec.android.diagmonagent/1000 (adj 15): empty #43
,I/PowerManagerService( 2404): [PWL] Off : 140s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2404): !@Sync 12
,D/AmoledAdjustTimer( 2404): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2404): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2404): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2404): !@Sync 13
,D/AmoledAdjustTimer( 2404): prevTemp = 279, currTemp = 280, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2404): [PWL] Off : 180s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2404): prevTemp = 280, currTemp = 281, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2404): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2404): !@Sync 14
,D/AmoledAdjustTimer( 2404): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2404): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2404): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/System.out( 6822): Thread-658 calls detatch()
,I/System.out( 6822): Thread-658 calls detatch()
,I/System.out( 6822): Thread-658 calls detatch()
,D/AmoledAdjustTimer( 2404): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,I/PowerManagerService( 2404): [PWL] Off : 225s ago
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2404): !@Sync 15
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2404): !@Sync 16
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,I/PowerManagerService( 2404): [PWL] Off : 275s ago
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,I/dalvikvm( 3286): Jit: resizing JitTable from 4096 to 8192
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2404): stay LED for fully charged
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2404): !@Sync 17
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2404): prevTemp = 276, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.,
D/BatteryService( 2404): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 278, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2404): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2404): !@Sync 18
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2404): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2404): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2404): !@Sync 19
,D/AmoledAdjustTimer( 2404): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2404): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,D/TimaService( 2404): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2404): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2404): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2404): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2404): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2404): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2404): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,W/ContextImpl( 2404): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2404): !@Sync 21
,D/AmoledAdjustTimer( 2404): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2404): !@Sync 22
,D/AmoledAdjustTimer( 2404): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService( 2404): [PWL] Off : 455s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2404): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 23
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2404): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2404): <AppSync3 Whitelist>
,V/AlarmManager( 2404): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4077): GC_CONCURRENT freed 2887K, 30% free 9726K/13788K, paused 11ms+2ms, total 68ms
,D/dalvikvm( 2404): GC_CONCURRENT freed 3898K, 71% free 25676K/87268K, paused 43ms+20ms, total 291ms
,D/dalvikvm( 2404): WAIT_FOR_CONCURRENT_GC blocked 154ms
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 24
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2404): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2404): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,I/GAV2    ( 6670): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 6670): Thread[disconnect check,5,main]: Disconnected from service
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,I/PowerManagerService( 2404): [PWL] Off : 525s ago
,E/Watchdog( 2404): !@Sync 25
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2404): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2404): prevTemp = 272, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 26
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2404): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2404): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 27
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2404): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2404): stay LED for fully charged
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2404): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 28
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 29
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/TimaService( 2404): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2404): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2404): TimaServiceHandler.handleMessage what =1
,I/PowerManagerService( 2404): [PWL] Off : 680s ago
I/PowerManagerService( 2404): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2404): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2404): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2404, ws=null) (elapsedTime=5461)
,E/Watchdog( 2404): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 31
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2404): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2404): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :4
,I/SensorManagerA( 2404): getReportingMode :: sensor.mType = 5
,D/LightsService( 2404): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2404): LightSensor setDelay = 200000000
D/Sensors ( 2404): LightSensor setSensorDelay = 200000000
D/Sensors ( 2404): Light sensor flush: not enabled 0
D/Sensors ( 2404): LightSensor enable = 1
D/Sensors ( 2404): LightSensor enableSensor = 1
D/SensorManager( 2404): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5461): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,I/EventLogService( 3286): Aggregate from 1451923553463 (log), 1451922056207 (data)
,D/Sensors ( 2404): LightSensor enable = 0
,D/Sensors ( 2404): LightSensor enableSensor = 0
,D/SensorManager( 2404): unregisterListener ::   
D/LightsService( 2404): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2404): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/Watchdog( 2404): !@Sync 32
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,I/PowerManagerService( 2404): [PWL] Off : 765s ago
,E/Watchdog( 2404): !@Sync 33
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2404): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 34
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2404): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :4
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/GCM     ( 3286): Message from null null
,E/GCM     ( 3286): Dropping message from null
,D/ConnectivityService( 2404): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
,D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
,D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,E/Watchdog( 2404): !@Sync 35
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,I/PowerManagerService( 2404): [PWL] Off : 855s ago
,E/Watchdog( 2404): !@Sync 36
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2404): prevTemp = 270, currTemp = 269, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 37
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2404): prevTemp = 269, currTemp = 270, prevStep = 4, currStep = 4
,D/dalvikvm( 2404): GC_CONCURRENT freed 4079K, 71% free 25556K/87268K, paused 9ms+16ms, total 210ms
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/AmoledAdjustTimer( 2404): prevTemp = 270, currTemp = 269, prevStep = 4, currStep = 4,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2404): !@Sync 38
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,I/PowerManagerService( 2404): [PWL] Off : 950s ago
,E/Watchdog( 2404): !@Sync 39
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = -10
,D/AmoledAdjustTimer( 2404): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 10
,D/AmoledAdjustTimer( 2404): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = -10
,D/AmoledAdjustTimer( 2404): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/TimaService( 2404): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2404): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2404): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2404): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 300, Delta = 10
,D/AmoledAdjustTimer( 2404): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = -10
,D/AmoledAdjustTimer( 2404): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2404): !@Sync 41
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :4
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5461): [b] __PingReply__
,E/Watchdog( 2404): !@Sync 42
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2404): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2404): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 43
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2404): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2404): <AppSync3 Whitelist>
,V/AlarmManager( 2404): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2404): stay LED for fully charged
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 44
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 269, currTemp = 268, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2404): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2404): !@Sync 45
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 268, currTemp = 269, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2404): stay LED for fully charged
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 269, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,I/PowerManagerService( 2404): [PWL] Off : 1155s ago
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2404): !@Sync 46
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2404): !@Sync 47
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4077): GC_CONCURRENT freed 2048K, 30% free 9724K/13788K, paused 16ms+2ms, total 37ms
,D/dalvikvm( 2769): GC_CONCURRENT freed 9179K, 41% free 18051K/30172K, paused 9ms+7ms, total 103ms
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2404): !@Sync 48
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 49
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,I/PowerManagerService( 2404): [PWL] Off : 1265s ago
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/TimaService( 2404): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2404): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2404): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2404): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2404): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2404): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 5461): GC_CONCURRENT freed 1913K, 25% free 10425K/13720K, paused 7ms+4ms, total 58ms
,E/Watchdog( 2404): !@Sync 51
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/AmoledAdjustTimer( 2404): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2404): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/dalvikvm( 2404): GC_CONCURRENT freed 3880K, 71% free 25598K/87268K, paused 20ms+19ms, total 250ms
,D/AmoledAdjustTimer( 2404): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2404): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :8
,D/LightsService( 2404): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/SensorManagerA( 2404): getReportingMode :: sensor.mType = 5
D/Sensors ( 2404): LightSensor setDelay = 200000000
D/Sensors ( 2404): LightSensor setSensorDelay = 200000000
D/Sensors ( 2404): Light sensor flush: not enabled 0
D/Sensors ( 2404): LightSensor enable = 1
D/Sensors ( 2404): LightSensor enableSensor = 1
D/SensorManager( 2404): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2404): LightSensor enable = 0
,D/Sensors ( 2404): LightSensor enableSensor = 0
,D/SensorManager( 2404): unregisterListener ::   
D/LightsService( 2404): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2404): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2404): stay LED for fully charged
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2404): !@Sync 52
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 268, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2404): !@Sync 53
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2404): prevTemp = 268, currTemp = 267, prevStep = 4, currStep = 4
,I/PowerManagerService( 2404): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 268, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): stay LED for fully charged
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2404): !@Sync 54
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 268, currTemp = 267, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 55
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2404): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2404): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2404): !@Sync 56
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 57
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,I/PowerManagerService( 2404): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2404): !@Sync 58
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 59
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/TimaService( 2404): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2404): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2404): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 2404): Skipping unknown process pid 12736
,E/Watchdog( 2404): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2404): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2404): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/BatteryService( 2404): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2404): !@Sync 61
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2404): Prepared write state in 56ms
,I/ProcessStatsService( 2404): Prepared write state in 30ms
,I/ProcessStatsService( 2404): Pruning old procstats: /data/system/procstats/state-2016-01-03-14-31-31.bin
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,I/PowerManagerService( 2404): [PWL] Off : 1625s ago
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :4
,V/NetworkStats( 2404): performPollLocked(flags=0x3)
,D/NtpTrustedTime( 2404): currentTimeMillis() cache hit
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2404): currentTimeMillis() cache hit
V/NetworkStats( 2404): performPollLocked() took 59ms
,D/NtpTrustedTime( 2404): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2404): currentTimeMillis() cache hit
,I/SELinux (12867): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12867):  
,I/SELinux (12867): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12867):  
I/SELinux (12867):  
,I/SELinux (12867): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (12867): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(12867): >>>>> Normal User
,E/dalvikvm(12867): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (12867): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(12867): in addTimaSignatureService
,D/TimaKeyStoreProvider(12867): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(12867): Added TimaKesytore provider
,D/dalvikvm(12867): GC_CONCURRENT freed 3009K, 31% free 9560K/13748K, paused 3ms+1ms, total 28ms
,D/dalvikvm(12867): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/@ WidgetProvider(12867): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(12867): onUpdate called for widgetId : 0
,D/@ WidgetProvider(12867): Widget random data : 5
,D/@ WidgetProvider(12867): onUpdate called for widgetId : 5
,D/@ WidgetProvider(12867): Widget random data : 2
,E/dalvikvm(12867): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
W/dalvikvm(12867): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12867): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12867): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(12867): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(12867): VFY: replacing opcode 0x22 at 0x0038
,E/dalvikvm(12867): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(12867): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(12867): VFY: replacing opcode 0x22 at 0x0038
,E/dalvikvm(12867): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(12867): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12867): VFY: replacing opcode 0x22 at 0x0038
I/ActivityManager( 2404): Killing 6746:com.vlingo.midas/u0a34 (adj 15): empty #43
,D/dalvikvm(12867): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
,D/dalvikvm(12867): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
D/dalvikvm(12867): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(12867): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2851): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SPPClientService( 5461): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,I/System.out(12867): Thread-690(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(12867): Thread-690(ApacheHTTPLog):isShipBuild true
,I/System.out(12867): Thread-690(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out(12867): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(12867): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(12867): Max ALLOWED memory (MB): 128
V/ImageManager(12867): Max SHOULD USE memory (MB): 128
,V/ImageManager(12867): Max Image Cache memory (MB): 32
,D/skia    (12867): getTotalSize : Do not get file length
,D/@ WidgetProvider(12867): Building widget : 5
,E/Watchdog( 2404): !@Sync 62
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2404): !@Sync 63
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2404): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2404): <AppSync3 Whitelist>
,V/AlarmManager( 2404): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2404): stay LED for fully charged
,D/UiModeManager( 2404): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :4
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/dalvikvm( 2851): GC_EXPLICIT freed 1757K, 23% free 10971K/14088K, paused 9ms+9ms, total 67ms
,D/dalvikvm( 2404): GC_CONCURRENT freed 3837K, 71% free 25698K/87268K, paused 13ms+19ms, total 219ms
,D/dalvikvm( 2724): GC_EXPLICIT freed 343K, 28% free 9970K/13732K, paused 8ms+6ms, total 75ms
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,E/Watchdog( 2404): !@Sync 64
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,V/AlarmManager( 2404): waitForAlarm result :4
,V/AlarmManager( 2404): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/BatteryService( 2404): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2404): stay LED for fully charged
,D/BatteryService( 2404): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2404): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,V/HeadsetService( 5068): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5068): Disconnected process message: 10
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 2404): Killing 6886:com.samsung.klmsagent/u0a18 (adj 15): empty for 1800s
,I/ActivityManager( 2404): Killing 6844:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1800s
,I/ActivityManager( 2404): Killing 7152:com.samsung.android.service.travel/u0a170 (adj 15): empty for 1803s
,I/ActivityManager( 2404): Killing 6712:tv.peel.smartremote/u0a165 (adj 15): empty for 1803s
,I/ActivityManager( 2404): Killing 7135:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1803s
,I/ActivityManager( 2404): Killing 7111:com.android.email/u0a157 (adj 15): empty for 1804s
,I/ActivityManager( 2404): Killing 7059:com.google.android.apps.magazines/u0a115 (adj 15): empty for 1805s
,I/ActivityManager( 2404): Killing 6547:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1805s
,I/ActivityManager( 2404): Killing 6957:com.sec.android.app.voicenote/1000 (adj 15): empty for 1807s
,I/ActivityManager( 2404): Killing 6393:com.policydm/1000 (adj 15): empty for 1807s
,D/ConnectivityService( 2404): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
,D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,E/Watchdog( 2404): !@Sync 65
,D/SSRMv2:SIOP( 2404): SIOP:: AP = 290, Delta = 0
,V/AlarmManager( 2404): waitForAlarm result :8
,V/AlarmManager( 2404): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
I/ActivityManager( 2404): Killing 7317:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty for 1800s
,I/ActivityManager( 2404): Killing 7430:com.android.providers.calendar/u0a45 (adj 15): empty for 1800s
,I/ActivityManager( 2404): Killing 7235:com.android.calendar/u0a144 (adj 15): empty for 1800s
,I/ActivityManager( 2404): Killing 5556:com.android.mms/u0a49 (adj 15): empty for 1801s
,I/ActivityManager( 2404): Killing 7398:com.google.android.partnersetup/u0a14 (adj 15): empty for 1802s
,I/ActivityManager( 2404): Killing 7349:com.sec.android.app.taskmanager/u0a168 (adj 15): empty for 1804s
,I/ActivityManager( 2404): Killing 7301:com.sec.esdk.elm/u0a98 (adj 15): empty for 1804s
,I/ActivityManager( 2404): Killing 7286:com.sec.android.app.clockpackage/u0a88 (adj 15): empty for 1805s
,I/ActivityManager( 2404): Killing 7022:com.sec.android.widgetapp.ap.hero.accuweather/u0a68 (adj 15): empty for 1805s
I/ActivityManager( 2404): Killing 7270:com.samsung.android.scloud.sync/u0a64 (adj 15): empty for 1805s
,I/ActivityManager( 2404): Killing 6499:com.osp.app.signin/u0a44 (adj 15): empty for 1805s
,I/ActivityManager( 2404): Killing 6925:com.sec.android.soagent/u0a38 (adj 15): empty for 1805s
,I/ActivityManager( 2404): Killing 6312:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1805s
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/CountryDetector( 2404): No listener is left
,D/AmoledAdjustTimer( 2404): prevTemp = 267, currTemp = 267, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1800000ms)
```
