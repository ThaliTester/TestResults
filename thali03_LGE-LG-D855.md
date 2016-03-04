#### Test 61703351a2a4153_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
E/AgendaWidgetManager( 5210): [updateWidgets] 
D/MonthWidgetProvider( 5210): [onReceive]
D/CalendarWidgetProvider( 5210): [onReceive]
D/CalendarWidgetProvider( 5210): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 5210): [onUpdateAndInitCalendarTime]
D/WeekWidgetProvider( 5210): [onReceive]
D/CalendarWidgetProvider( 5210): [onReceive]
D/CalendarWidgetProvider( 5210): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 5210): [onUpdateAndInitCalendarTime]
--------- beginning of system
I/ActivityManager( 1037): Waited long enough for: ServiceRecord{2de20877 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
I/DisplayManagerService( 1037): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1440 x 2560, 60.0 fps, supportedRefreshRates [60.0], density 640, 537.882 x 541.866 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  279): Set power mode=0, type=0 flinger=0xb6082000
V/ActivityManager( 1037): Display changed displayId=0
D/qdhwcomposer(  279): hwc_blank: Blanking display: 0
D/DSDPConnection( 1876): Display #0 changed.
V/QRemote ( 5715): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 5715): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 5715): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,D/LgDataFeature( 5715): LgDataFeature() Constructor: none
D/LgDataFeature( 5715): LgDataFeature() Constructor Done, null
V/SoundPool( 5715): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 5715): load: fd=30, offset=10857164, length=17813, priority=1
V/SoundPool( 5715): create sampleID=1, fd=31, offset=17813 length=10857164
V/SoundPool( 5715): doLoad: loading sample sampleID=1
I/QRemote ( 5715): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 5715): Start decode
V/MediaPlayer[Native]( 5715): decode(31, 10857164, 17813)
V/MediaPlayerService(  314): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  314): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  314): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  314): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  314): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  314): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  314): player type = 3
V/AwesomePlayer(  314): AwesomePlayer create()
V/AwesomePlayer(  314): reset_l() 
V/AwesomePlayer(  314): cancelPlayerEvents
V/AwesomePlayer(  314): setAudioSink() 
V/AwesomePlayer(  314): reset_l() 
V/AudioCache(  314): notify(0xb5474640, 8, 0, 0)
V/AudioCache(  314): ignored
V/AwesomePlayer(  314): cancelPlayerEvents
D/Utils   (  314): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  314): setDataSource_l dataSource
V/LGParserOSAL(  314): SniffLGParser start
V/LGParserOSAL(  314): MainType:5, SubType=0
V/LGParserOSAL(  314): #### check Mime : application/ogg
V/LGParserOSAL(  314): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  314): Use LGExtractor :application/ogg 
V/LGParserOSAL(  314): supported mime: application/ogg
V/AwesomePlayer(  314): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  314): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  314): mBitrate = -1 bits/sec
V/AwesomePlayer(  314): AudioTrack Setting
V/AwesomePlayer(  314): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  314): setAudioSource() 
V/MediaPlayerService(  314): prepare
V/AwesomePlayer(  314): prepareAsync_l() 
V/MediaPlayerService(  314): wait for prepare
V/AwesomePlayer(  314): onPrepareAsyncEvent() 
V/AwesomePlayer(  314): initAudioDecoder() 
W/Utils   (  314): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  314): isOffloadSupported()
V/AudioPolicyManager(  314): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  314): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  314): isAudioPlaybackHookOn() false
V/AwesomePlayer(  314): getUseOffload() = 0 
V/OMXCodec(  314): OMXCodec::Create
V/OMXCodec(  314): findMatchingCodecs()
V/OMXCodec(  314): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  314): matchingCodecs.size()=1
V/OMXCodec(  314): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  314): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  314): LG Codec Adapter start
V/OMXCodec(  314): OMXCodec Createtor
V/OMXCodec(  314): setComponentRole
V/OMXCodec(  314): configureCodec protected=0
V/LGCodecAdapter(  314): called getLGCodecSpecificData
V/LGCodecOSAL(  314): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  314): Called LGconfigureCodecMETA
V/LGCodecOSAL(  314): Called LGconfigureCodecMSG
V/LGCodecOSAL(  314): Not support LGCodec
V/OMXCodec(  314): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  314): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  314): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  314): Could not offload audio decode, try pcm offload
W/Utils   (  314): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  314): isOffloadSupported()
V/AudioPolicyManager(  314): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  314): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  314): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  314): init()
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  314): allocateBuffers
V/OMXCodec(  314): allocateBuffersOnPort portIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
V/OMXCodec(  314): allocateBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb57c2330 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb57c2420 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb57c24c0 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb57c2510 on output port
V/OMXCodec(  314): init() mAsyncCompletion wait!!! 
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  314): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  314): finishAsyncPrepare_l() 
V/AudioCache(  314): notify(0xb5474640, 5, 0, 0)
V/AudioCache(  314): ignored
V/AudioCache(  314): notify(0xb5474640, 1, 0, 0)
V/AudioCache(  314): prepared
V/AudioCache(  314): wait - success
V/MediaPlayerService(  314): start
V/AwesomePlayer(  314): play_l() 
V/AwesomePlayer(  314): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  314): createAudioPlayer_l
V/AwesomePlayer(  314): seekAudioIfNecessary_l() 
V/AwesomePlayer(  314): startAudioPlayer_l() 
D/AudioPlayer(  314): start of Playback, useOffload 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  314): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
I/ActivityManager( 1037): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=5805 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/QRemote ( 5715): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
V/OMXCodec(  314): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  314): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044811568
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044811808
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044811968
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3044812048
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  314): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  314): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  314): allocateBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
E/QRemote ( 5715): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb57c24c0 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb57c2420 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb57c2330 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb57c26f0 on output port
D/QRemote ( 5715): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
V/OMXCodec(  314): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  314): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  314): notify(0xb5474640, 6, 0, 0)
V/AudioCache(  314): ignored
V/MediaPlayerService(  314): wait for playback complete
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac104000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac105000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac106000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac107000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac108000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac109000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac10a000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac10b000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac10c000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac10d000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac10e000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac10f000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac110000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac111000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac112000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac113000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac114000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac115000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac116000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac117000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac118000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac119000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac11a000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac11b000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac11c000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac11d000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac11e000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac11f000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac120000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac121000, 0xb1699000, 4096)
V/LGMDMManager( 5715): Create singleton instance
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac122000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac123000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac124000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac125000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac126000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac127000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac128000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac129000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac12a000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac12b000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac12c000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac12d000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac12e000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac12f000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac130000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac131000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac132000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac133000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac134000, 0xb1699000, 4096)
V/AudioCache(  314): write(0xb1699000, 4096)
V/AudioCache(  314): memcpy(0xac135000, 0xb1699000, 4096)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  314): postAudioEOS() 
V/AudioCache(  314): write(0xb1699000, 280)
V/AudioCache(  314): memcpy(0xac136000, 0xb1699000, 280)
V/AwesomePlayer(  314): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  314): onStreamDone
V/AwesomePlayer(  314): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  314): notify(0xb5474640, 2, 0, 0)
V/AudioCache(  314): playback complete
V/AwesomePlayer(  314): pause_l() 
V/AudioCache(  314): notify(0xb5474640, 7, 0, 0)
V/AudioCache(  314): ignored
V/AwesomePlayer(  314): cancelPlayerEvents
V/AudioCache(  314): wait - success
V/MediaPlayerService(  314): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  314): Pause Playback at 1068125
V/AwesomePlayer(  314): reset_l() 
V/AudioCache(  314): notify(0xb5474640, 8, 0, 0)
V/AudioCache(  314): ignored
V/AwesomePlayer(  314): cancelPlayerEvents
D/AudioPlayer(  314): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  314): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  314): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb57c26f0 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb57c2330 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb57c2420 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb57c24c0 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  314): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  314): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  314): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  314): AudioPlayer releasing audio source
D/AudioPlayer(  314): AudioPlayer done releasing audio source
V/AwesomePlayer(  314): reset_l() 
V/AwesomePlayer(  314): cancelPlayerEvents
V/AwesomePlayer(  314): ~AwesomePlayer call
V/AwesomePlayer(  314): reset_l() 
V/AwesomePlayer(  314): cancelPlayerEvents
V/SoundPool( 5715): close(31)
V/SoundPool( 5715): pointer = 0x9ff3a000, size = 205080, sampleRate = 48000, numChannels = 2
D/UEI.SmartControl( 5805): Quickset Services start...
I/UEI.SmartControl( 5805): Manufacture = LGE
D/UEI.SmartControl( 5805): Id = LGNevo
D/UEI.SmartControl( 5805): File observer start...
E/UEI.SmartControl( 5805): IR Port is disabled: false
D/UEI.SmartControl( 5805): Starting file observer...
D/UEI.SmartControl( 5805): Extracting JNI libs...
D/UEI.SmartControl( 5805): --- this system supports 32-bit or 64-bit only
I/qdhwcomposer(  279): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  279): hwc_blank: Done blanking display: 0
D/SurfaceControl( 1037): Excessive delay in setPowerMode(): 285ms
E/QCOM PowerHAL( 1037): Invalid hint ID.
I/QCOM PowerHAL( 1037): Got set_interactive hint
D/QRemote ( 5715): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 5715): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 5715): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:8874
V/QRemote ( 5715): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 5715): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 5715): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 5715): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 5715): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 5715): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 5715): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:2148
D/PostponalbeReceiver( 3697): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
D/PostponalbeReceiver( 3697): WSAndroidSystemIntentReceiver is now processing the previously postponed broadcast action 'android.net.wifi.STATE_CHANGE'.
V/QRemote ( 5715): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 5715): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 5715): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 5715): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 5715): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 5715): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 5715): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 5715): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
D/UEI.SmartControl( 5805): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5805): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5805): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/ActivityManager( 1037): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5826 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/MtpService( 3444): updating state; isCurrentUser=true, mMtpLocked=false
D/AndroidRuntime( 5802): 
D/AndroidRuntime( 5802): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5802): CheckJNI is OFF
I/UEI.SmartControl( 5805): --- Selecting new region: 6
I/UEI.SmartControl( 5805): Model = LG-D855
D/UEI.SmartControl( 5805): QS Service created
I/UEI.SmartControl( 5805): Service initServices...
D/UEI.SmartControl( 5805): QS start get config
E/ThermalEngine(  330): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 578000000
D/UEI.SmartControl( 5805): Loading JNI Libs...
I/PCSuite ( 5826): [StartReceiver]USB CONNECTED ver UsbManger : ptp_only
I/PCSuite ( 5826): [StartReceiver]isUsbPCSuiteMode : false
D/PCSuite ( 5826): [StartReceiver][checkEUTStatus] eutStatus = 
D/PCSuite ( 5826): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5826): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager( 1037): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=5856 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1037): Killing 5237:com.nuance.voicemate/u0a117 (adj 15): empty #17
D/AndroidRuntime( 5802): Calling main entry com.android.commands.am.Am
W/libprocessgroup( 1037): failed to open /acct/uid_10117/pid_5237/cgroup.procs: No such file or directory
I/ActivityManager( 1037): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1969): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1037): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{3cb292e4 #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1037): setTaskToReturnTo : TaskRecord{3cb292e4 #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1037): AppWindowTokenEx init.. 
E/GBMv2   (  336): DFP En is all cleared set to be enabled
W/ResourcesManager( 5856): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5856): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5856): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5856): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 5856): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5856): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/ActivityManager( 1037): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5876 uid=10319 gids={50319, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/InputDispatcher( 1037): Focus left window: Window{b4a8153 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5802): Shutting down VM
I/[LGHome]EVENT( 2089): [Launcher.java:5833:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{1e77f950 type 0 when 1457094120545 com.lge.ia.task.mrgdblogger} when 1457094120545
I/art     (  351): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 460us total 21.298ms
V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{2aebb749 type 2 when 63143 com.google.android.gms} when 63143
I/art     (  351): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 405us total 17.910ms
D/DSDPConnection( 1876): Display #0 changed.
V/ActivityManager( 1037): Display changed displayId=0
I/art     (  351): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 401us total 17.784ms
D/SplitWindowPolicy( 1969): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1969): topRunningActivity=ActivityInfo{bf64360 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1969): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1969): topRunningActivity=ActivityInfo{1ca22019 co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/ContextHelper( 5876): convertTheme. context->name=com.example.hello themeResourceId=16973833
I/UEI.SmartControl( 5805): Supports setup maps: true
D/UEI.SmartControl( 5805): QS start statue = true Error code = 0
I/UEI.SmartControl( 5805): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 5805): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 5805): ### init IR Blaster...
D/serial_port( 5805): Configuring serial port
D/UsbSettingsReceiver( 5856): [AUTORUN] onReceive() : action = android.hardware.usb.action.USB_STATE
D/UsbSettingsReceiver( 5856): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5856): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5856): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5856): [AUTORUN] onReceive() : app userid = 0, current userid = 0
E/UEI.SmartControl( 5805): UEIBLaster setting for 616
I/UEI.SmartControl( 5805): Setting serial record hearder size = 2
I/UEI.SmartControl( 5805): configuring settings for MAXQ616
I/UEI.SmartControl( 5805): Get version...
D/UsbSettingsReceiver( 5856): [AUTORUN] onReceive() : getDefaultFunction = ptp_only
D/UsbSettingsReceiver( 5856): [AUTORUN] onReceive() : USB_FUNCTION_CDROM_STORAGE = false
D/UsbSettingsReceiver( 5856): [AUTORUN] onReceive() : mDirectAutorun = true
D/UsbSettingsReceiver( 5856): [AUTORUN] onReceive() : mActivityUsbModeChange = false
D/UsbSettingsReceiver( 5856): [AUTORUN] onReceive() : mActivityFinish = false
D/UsbSettingsReceiver( 5856): [AUTORUN] onReceive() : ===== USB Configured =====
D/UsbSettingsControl( 5856): [AUTORUN] setUsbConnected() : connected=true
D/UsbSettingsReceiver( 5856): [AUTORUN] onReceive() : checkQmicm = ptp_only,adb
D/UEI.SmartControl( 5805): serial port data available: 21
D/UsbSettingsReceiver( 5856): [AUTORUN] : topPackageName=com.example.hello
D/UsbSettingsReceiver( 5856): [AUTORUN] : topClassName=com.example.hello.MainActivity
D/UsbSettingsReceiver( 5856): [AUTORUN] Not exist com.android.LGSetupWizard
D/UsbSettingsReceiver( 5856): [AUTORUN] setUsbConnect() : mUsbSettingsRun = false
D/UsbSettingsReceiver( 5856): [AUTORUN] startUsbSettings() : deviceProvisioned=1
D/WeatherAncestor( 5047): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 13:22:7
D/Weather.Utils( 5047): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 5047): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 5047): 2 : This is isUpdating : false
D/WeatherAncestor( 5047): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 13:22:7
I/ActivityManager( 1037): Killing 4292:com.android.defcontainer/u0a4 (adj 15): empty #17
D/UEI.SmartControl( 5805): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 5805): IR Blaster version: 256702256704300002
I/UEI.SmartControl( 5805): QS saving settings...
D/UEI.SmartControl( 5805): IR Blaster version: 25672567
I/Sensors (  497): sns_pwr.c(301):releasing wakelock
D/UEI.SmartControl( 5805): serial port data available: 4
I/WebViewFactory( 5876): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,I/UEI.SmartControl( 5805): Device manager: loading config....
D/UEI.SmartControl( 5805): ----------- loading internal config...
W/ContextImpl( 5805): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
W/libprocessgroup( 1037): failed to open /acct/uid_10004/pid_4292/cgroup.procs: No such file or directory
E/UEI.SmartControl( 5805): Services init done
D/UEI.SmartControl( 5805): QS Service init finished
D/UEI.SmartControl( 5805): QS Service version name: 2.1.91
D/UEI.SmartControl( 5805): QS Service version code: 201091
D/UEI.SmartControl( 5805): Service requested: Control
V/UserPresentBroadcastReceiver( 1841): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
E/UEI.SmartControl( 5805): Loading SETTINGS...
D/UEI.SmartControl( 5805): Request IControl service: devices are loaded...
D/UEI.SmartControl( 5805): -- Open brand translation xml: brands_translations_ko
I/LibraryLoader( 5876): Loading: webviewchromium
I/LibraryLoader( 5876): Time to load native libraries: 3 ms (timestamps 3381-3384)
I/LibraryLoader( 5876): Expected native library version number "",actual native library version number ""
I/QRemote ( 5715): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
D/UEI.SmartControl( 5805): Internal service binding...
I/UEI.SmartControl( 5805): ------ IControl API: 11
I/UEI.SmartControl( 5805): Registering callback...
I/UEI.SmartControl( 5805): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5805): -----service ready thread exits
I/UEI.SmartControl( 5805): ------ IControl API: 19
I/UEI.SmartControl( 5805): Registering Services Ready callback...
I/UEI.SmartControl( 5805): Notify client services are ready...
I/QRemote ( 5715): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 5715): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 5715): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 5715): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 5715): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 5805): ------ IControl API: 8
D/QRemote ( 5715): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 5715): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 5715): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 5715): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 5715): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 5715): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/QRemote ( 5715): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
D/QRemote ( 5715): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1037): Killing 5262:com.android.vending/u0a44 (adj 15): empty #17
V/WebViewChromiumFactoryProvider( 5876): Binding Chromium to main looper Looper (main, tid 1) {11d0400e}
I/LibraryLoader( 5876): Expected native library version number "",actual native library version number ""
I/chromium( 5876): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5876): Initializing chromium process, renderers=0
W/art     ( 5876): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  314): registerClient() client 0xb558aac0, uid 10319
D/BluetoothManagerService( 1037): Message: 20
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@19485b67:true
W/chromium( 5876): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 5876): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 5876): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/ActivityManager( 1037): Killing 5310:com.google.android.gms:car/u0a5 (adj 15): empty #18
I/Adreno-EGL( 5876): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5876): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5876): Build Date: 12/12/14 금
I/Adreno-EGL( 5876): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 5876): Remote Branch: 
I/Adreno-EGL( 5876): Local Patches: 
I/Adreno-EGL( 5876): Reconstruct Branch: 
W/libprocessgroup( 1037): failed to open /acct/uid_10044/pid_5262/cgroup.procs: No such file or directory
W/libprocessgroup( 1037): failed to open /acct/uid_10005/pid_5310/cgroup.procs: No such file or directory
D/QRemote ( 5715): [LgIrMdmPolicyReceiver.java:20:onReceive()] oooooo LG IR MDM receiver action: com.lge.mdm.intent.action.ACTION_IR_PORT_POLICY_CHANGED
D/QRemote ( 5715): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
V/QRemote ( 5715): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 5715): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:5489
I/DigitalAppWidgetProvider( 5740): onReceive: android.intent.action.ALARM_CHANGED
D/WeatherAncestor( 5047): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 13:22:7
D/Weather.Utils( 5047): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 5047): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 5047): 2 : This is isUpdating : false
D/Weather_cast( 5047): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 5047): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 13:22:7
W/chromium( 5876): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 5876): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 5876): Attempt to remove local handle scope entry from IRT, ignoring
I/ActivityManager( 1037): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=5919 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
W/AwContents( 5876): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5876): CordovaWebView is running on device made by: LGE
W/art     ( 5876): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5876): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager( 1037): Activity pause timeout for ActivityRecord{122334d u0 com.example.hello/.MainActivity t4}
D/OpenGLRenderer( 5876): Render dirty regions requested: true
I/OpenGLRenderer( 5876): Initialized EGL, version 1.4
D/OpenGLRenderer( 5876): Enabling debug mode 0
D/Atlas   ( 5876): Validating map...
D/SplitWindow( 1037): check instance of lgWin Window{1628e29 u0 com.example.hello/com.example.hello.MainActivity}
E/ActivityThread( 5919): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 5919): No ProfileInfo entries
I/LG Account v2.2( 5919): isEnabled: false
I/Feature ( 5919): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 5919): [Lifetracker]Country: EU
I/Feature ( 5919): [Lifetracker]Operator: OPEN
I/Feature ( 5919): [Lifetracker]Ranking support: false
I/Feature ( 5919): [Lifetracker]Comfort support: false
I/Feature ( 5919): [Lifetracker]Accessory: true
I/Feature ( 5919): [Lifetracker]Health device: true
I/Feature ( 5919): [Lifetracker]Extra Pedometer: false
I/Feature ( 5919): [Lifetracker]Blood glucose device: false
I/Feature ( 5919): [Lifetracker]Device Number: 3
I/ActivityManager( 1037): Killing 5375:com.lge.bnr/1000 (adj 15): empty #17
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.example.hello
D/PhoneStatusBar( 1472): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=8600 newVal=8000 diff=600
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@107ac837,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
D/PhoneStatusBar( 1472): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
I/[SystemUI]NavigationThemeResource( 1472): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1472):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1472): , Keyguard show=false, IME shown=false, Panel expanded=false
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@107ac837,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher( 1037): Focus entered window: Window{1628e29 u0 com.example.hello/com.example.hello.MainActivity}
D/LgDataFeature( 5876): LgDataFeature() Constructor: none
D/LgDataFeature( 5876): LgDataFeature() Constructor Done, null
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_5375/cgroup.procs: No such file or directory
D/LGDMClient( 4387): [DmUtil.java] [getMDMFlag()] : [694] : getMDMFlag : 1
D/InputMethodManagerService( 1037): setImestate : 0
I/ActivityManager( 1037): Displayed com.example.hello/.MainActivity: +681ms (total +800ms)
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{122334d u0 com.example.hello/.MainActivity t4} time:63892
W/IInputConnectionWrapper( 5876): showStatusIcon on inactive InputConnection
W/IInputConnectionWrapper( 5876): getTextBeforeCursor on inactive InputConnection
I/Timeline( 5876): Timeline: Activity_idle id: android.os.BinderProxy@23d2c8be time:63893
E/b       ( 1712): Unable to connect to the editor to retrieve text... will retry later
D/LGDMClient( 4387): [DmUtil.java] [getWhatsNewString()] : [251] : Update contents : Enhancements:
D/LGDMClient( 4387): 1. Usability improvements through Google patch.��
W/IInputConnectionWrapper( 5876): getTextAfterCursor on inactive InputConnection
V/NotificationService( 1037): enqueueNotificationInternal: pkg=com.lge.lgdmsclient id=61184 notification=Notification(pri=0 contentView=null vibrate=[100,250,100,500] sound=default defaults=0x1 flags=0x2 color=0x00000000 vis=PRIVATE)
D/ZenLog  ( 1037): intercepted: 0|com.lge.lgdmsclient|61184|null|1000,none
D/PostponalbeReceiver( 3697): OasSdCardChangedReceiver is processing the broadcast action 'android.intent.action.MEDIA_SCANNER_STARTED'.
V/NotificationService( 1037): pkg=com.lge.lgdmsclient canInterrupt=false intercept=true
I/NotificationServiceEx( 1037): LED remove() : mLights=0|com.lge.lgdmsclient|61184|null|1000
D/NotificationServiceEx( 1037): updateLightListLocked :r=0|com.lge.lgdmsclient|61184|null|1000, action=2
D/NotificationServiceEx( 1037): notification=Notification(pri=0 contentView=null vibrate=[100,250,100,500] sound=default defaults=0x1 flags=0x2 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1419): onNotificationPosted
D/LgeQuickCoverNLService( 1419): onNotificationPosted isNotClearable
D/LgeQuickCoverNLService( 1419): onNotificationPosted isOngoing
I/chromium( 5876): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/ActivityManager( 1037): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.MediaScanReceiver: pid=5952 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
D/SmartCoverUpdateMonitor( 1419): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1419): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1419): handleNotificationPosted(true)
D/QuickCircle( 1419): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1419): post() sbn.getKey(): 0|com.lge.lgdmsclient|61184|null|1000
D/LgeQuickCoverNotificationData( 1419): post() sbn.getGroupKey(): 0|com.lge.lgdmsclient|61184|null|1000
D/LgeQuickCoverNotificationData( 1419): post do NOT update Ongoing, NoClear or low score job
D/LgeQuickCoverNotificationData( 1419): showAll3
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1419): showAll() ID : 2130839078,-1|com.android.systemui|2130839078|null|10020
E/AndroidProtocolHandler( 5876): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/JsMessageQueue( 5876): Set native->JS mode to OnlineEventsBridgeMode
E/MediaScanReceiver( 5952): media scanning start or checking
I/ActivityManager( 1037): Killing 5417:com.lge.qmemoplus/1000 (adj 15): empty #17
W/MainApplication( 5952): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/chromium( 5876): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 5876): 
I/[SystemUI]SafeModeBroadcastReceiver( 1472): onReceive = com.lge.statusbar.bootcompleted
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_5417/cgroup.procs: No such file or directory
D/ToneMappingReceiver( 5740): Enter doAlarmRingToneUriMapping()
D/ToneMappingReceiver( 5740): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5740): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
D/jxcore_app_log( 5876): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435317504
D/CommonUtil( 5740): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5740): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5740): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5740): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5740): Alarm Success count is 0
D/ToneMappingReceiver( 5740): Timer Success count is 0
I/MediaScannerReceiver( 5210): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///system/media
I/InitNotificationRingtoneService( 5210): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 5210): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
E/MediaScanReceiver( 5952): media scanning finished
I/chromium( 5876): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5876): 
I/com.lge.bnr.receiver.MediaScanReceiver( 5952): android.intent.action.MEDIA_SCANNER_FINISHED
I/AlertUtils( 5210): [getCalendarNotiSoundURIFromCursor] getCount()= 21
D/PostponalbeReceiver( 3697): OasSdCardChangedReceiver is processing the broadcast action 'android.intent.action.MEDIA_SCANNER_STARTED'.
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
E/MediaScanReceiver( 5952): media scanning start or checking
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
D/ToneMappingReceiver( 5740): Enter doAlarmRingToneUriMapping()
D/ToneMappingReceiver( 5740): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5740): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
D/CommonUtil( 5740): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5740): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5740): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5740): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5740): Alarm Success count is 0
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
D/ToneMappingReceiver( 5740): Timer Success count is 0
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/MediaScannerReceiver( 5210): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///storage/emulated/0
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
E/MediaScanReceiver( 5952): media scanning finished
I/com.lge.bnr.receiver.MediaScanReceiver( 5952): android.intent.action.MEDIA_SCANNER_FINISHED
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/[LGHome]LGNumberBadgeReceiver( 2089): [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = lge.intent.action.UNREAD_MESSAGES
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/[LGHome]NumberBadge.LGBroadCastBadge( 2089): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 2089): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 2089): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 2089): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
W/jxcore-log( 5876): Initializing JXcore engine
W/jxcore-log( 5876): JXcore engine is ready
I/[LGHome]LGNumberBadgeReceiver( 2089): [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = lge.intent.action.UNREAD_MESSAGES
I/[LGHome]NumberBadge.LGBroadCastBadge( 2089): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 2089): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 2089): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 2089): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
D/WeatherAncestor( 5047): 2 : onReceive, action: com.lge.concierge.action.CONCIERGE_PONG, Time(hour:min:sec) 13:22:8
D/Weather.Utils( 5047): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 5047): 2 : All the weather widget is gone.
D/UpdateThreadPoolManager( 5047): 2 : This is isUpdating : false
D/PostponalbeReceiver( 3697): WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
I/art     ( 3444): Explicit concurrent mark sweep GC freed 6165(411KB) AllocSpace objects, 0(0B) LOS objects, 36% free, 27MB/43MB, paused 751us total 44.964ms
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 5210): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
W/Thread-679( 5972): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10773]" dev="sockfs" ino=10773 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-679( 5972): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/Thread-679( 5972): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7551]" dev="sockfs" ino=7551 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/Thread-679( 5972): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/Thread-679( 5972): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[27073]" dev="sockfs" ino=27073 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
W/jxcore-log( 5876): Starting JXcore engine
I/ActivityManager( 1037): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5983 uid=10008 gids={50008, 9997, 3003} abi=armeabi-v7a
I/AlertUtils( 5210): set default noti to content://media/internal/audio/media/41
I/InitNotificationRingtoneService( 5210): End InitializeAlertRingtoneService.onHandleIntent
I/InitNotificationRingtoneService( 5210): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 5210): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
I/AlertUtils( 5210): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
W/jxcore-log( 5876): Platform android
W/jxcore-log( 5876): 
W/jxcore-log( 5876): Process ARCH arm
W/jxcore-log( 5876): 
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/jxcore-log( 5876): JXcore Cordova bridge is ready!
I/jxcore-log( 5876): 
,W/jxcore-log( 5876): JXcore engine is started
,E/jxcore-log( 5876): >> LGE-LG-D855
E/jxcore-log( 5876): 
,I/jxcore-log( 5876): Total memory 2995761152
I/jxcore-log( 5876): 
I/jxcore-log( 5876): Free memory 613183488
I/jxcore-log( 5876): 
I/jxcore-log( 5876): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5876): 
I/jxcore-log( 5876): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5876): 
I/art     ( 1037): Explicit concurrent mark sweep GC freed 10627(565KB) AllocSpace objects, 3(54KB) LOS objects, 33% free, 44MB/66MB, paused 2.770ms total 132.107ms
I/jxcore-log( 5876): userPath [ 'www', 'www' ]
I/jxcore-log( 5876): 
I/jxcore-log( 5876): Size 1440 2392
I/jxcore-log( 5876): 
,I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/jxcore-log( 5876): Screen Brightness 50
I/jxcore-log( 5876): 
E/jxcore-log( 5876): Dummy Error Log.
E/jxcore-log( 5876): 
,I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 5210): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 5210): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
,I/AlertUtils( 5210): set default noti to content://media/internal/audio/media/41
I/InitNotificationRingtoneService( 5210): End InitializeAlertRingtoneService.onHandleIntent
I/ActivityManager( 1037): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6003 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/MediaStoreImporter( 5455): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager( 1037): Killing 5545:com.lge.formmanager/u0a26 (adj 15): empty #17
E/WifiStateMachine( 1037):  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2442 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:1100215455] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1037):  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2442 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1100215457] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
W/libprocessgroup( 1037): failed to open /acct/uid_10026/pid_5545/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1037):  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2442 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:25] from screen [on:0 period:1100215483] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,E/WifiStateMachine( 1037):  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-48 f=2442 sc=60 link=72 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:1100215485] gl rssi=-48 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
W/ResourcesManager( 6003): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6003): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6003): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 6003): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6003): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
E/GBMv2   (  336): DFP En is all cleared set to be enabled
E/GBMv2   (  336): Set value is all cleared set the max
I/GBMv2   (  336): DFP Enabled. Ignore VFP set
,I/SystemConfig( 6003): BUILD Country: EU
,I/SystemConfig( 6003): BUILD Operator: OPEN
I/GAV4    ( 5625): Thread[GAThread,5,main]: No campaign data found.
,I/SystemConfig( 6003): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6003): existFile = false
I/SystemConfig( 6003): canReadFile = false
I/SystemConfig( 6003): systemFeature RCS result false
D/SystemConfig( 6003): refreshRcsSupport() :false
,I/ActivityManager( 1037): Killing 5568:com.android.chrome/u0a57 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_10057/pid_5568/cgroup.procs: No such file or directory
,I/PackageChangeReceiver( 5524): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
I/ActivityManager( 1037): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6027 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/jxcore-log( 5876): getBuffer is called!!!!
I/jxcore-log( 5876): 
,W/ResourcesManager( 6027): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6027): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6027): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 6027): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/AppConfig( 6027): Total System Memory = 2995761152
,D/SystemHelper( 6027): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager( 1037): Killing 5598:com.lge.drmservice/u0a62 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10062/pid_5598/cgroup.procs: No such file or directory
D/LIA_Service_NativeEventReceiver( 2035): onReceive action : android.intent.action.PACKAGE_ADDED = package:com.example.hello
,I/LIA_Service_PlatformUtil( 2035): startLIAService() : Trying to start LIA service ...
D/LIA_Service_LIAService( 2035): onStartCommand() : LIAService started! - id :3, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
D/PostponalbeReceiver( 3697): OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_ADDED'.
,W/ContextImpl( 3697): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsm.mss.OasPackageScanReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2586 
I/UpdateIcingCorporaServi( 4591): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/ActivityManager( 1037): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6048 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/DocsApplication( 6048): Installing DEX configuration.
,D/DexInstaller( 6048): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper( 6048): Provided clientMode=RELEASE, packageInfo=PackageInfo{321349c2 com.google.android.apps.docs}
D/TAG     ( 6048): onCreate()
,D/CrossAppStateProvider( 6048): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,I/UpdateIcingCorporaServi( 4591): UpdateCorporaTask done [took 401 ms] updated apps [took 401 ms] 
,I/ActivityManager( 1037): Killing 5625:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,W/libprocessgroup( 1037): failed to open /acct/uid_10093/pid_5625/cgroup.procs: No such file or directory
,V/AlarmManager( 1037): ELAPSED_WAKEUP set : Alarm{1b9617b1 type 2 when 66685 com.android.systemui} when 66685
,I/[SystemUI]QPairHandler( 1472): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]QSlideListController( 1472): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1472): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]EVENT( 2089): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/InputReader( 1037): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,D/administrator( 1037): Handling package changes for user 0
,I/NotificationService( 1037): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService( 1037): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService( 1037): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService( 1037): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService( 1037): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService( 1037): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1050a2e2
,W/ResourcesManager( 1037): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1037): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2089): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/GmsNetworkLocationProvi( 1841): DISABLE
,I/GCoreNlp( 1841): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/LocationProviderProxy( 1037): applying state to connected service
,I/ActivityManager( 1037): Waited long enough for: ServiceRecord{3a043566 u0 com.lge.springcleaning/.service.AppCleanupService}
,D/LgDataFeature( 6048): LgDataFeature() Constructor: none
D/LgDataFeature( 6048): LgDataFeature() Constructor Done, null
,I/[SystemUI]LGPowerUI( 1472): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1472): On Skip Timer : true
,D/WifiController( 1037): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1472): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
I/[SystemUI]LGPowerUI( 1472): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1969): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1969): Battery Level Remaining: 100%
D/LEDHandler( 1969): Battery Temp: 294, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 3868): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1472): onReceive = android.intent.action.BATTERY_CHANGED
,D/LGDMClient( 4387): [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.intent.action.BATTERY_CHANGED
D/LGDMClient( 4387): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/MainApplication( 5952): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/[SystemUI]LGPowerUI( 1472): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1472): On Skip Timer : true
W/GAV2    ( 6048): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager( 1037): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6106 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,I/LockScreenSettings( 6106): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/LockScreenSettings( 6106): New app installed broadcast received ..
,I/LockScreenSettings( 6106): Number of installed packages  1
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,D/UEI.SmartControl( 5805): Internal timer expired: 1
D/UEI.SmartControl( 5805): unbind internal service
,I/ActivityManager( 1037): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=6137 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
W/GAV2    ( 6048): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager( 1037): Killing 5772:com.qualcomm.timeservice/1000 (adj 15): empty #17
,D/serial_port( 5805): close(fd = 25)
,I/UEI.SmartControl( 5805): Serial port is closed.
I/ActivityManager( 1037): Killing 5826:com.lge.sync/1000 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_5772/cgroup.procs: No such file or directory
,W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_5826/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1037):  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
E/WifiStateMachine( 1037):  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,D/EulaProviderUpdateObserver( 6137): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 6137): uri : package:com.example.hello
,I/ActivityManager( 1037): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6158 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1037): Killing 5856:com.android.settings/1000 (adj 15): empty #17
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_5856/cgroup.procs: No such file or directory
,D/Finsky  ( 6158): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/LgDataFeature( 6158): LgDataFeature() Constructor: none
,D/LgDataFeature( 6158): LgDataFeature() Constructor Done, null
,D/Finsky  ( 6158): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/ActivityManager( 1037): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6197 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/Settings( 6158): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6158): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/ResourcesManager( 6197): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6197): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/DownloadManager( 3444): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3444): created cursor android.database.sqlite.SQLiteCursor@29475b34 on behalf of 6158
I/ActivityManager( 1037): Killing 5805:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
I/QRemote ( 5715): [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
,W/System.err( 5715): android.os.DeadObjectException
W/System.err( 5715): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5715): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5715): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5715): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
W/System.err( 5715): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 5715): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 5715): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5715): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5715): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5715): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 5715): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5715): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5715): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 5715): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 5715): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5715): android.os.DeadObjectException
W/System.err( 5715): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5715): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5715): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5715): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
W/System.err( 5715): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
W/System.err( 5715): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
W/System.err( 5715): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5715): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5715): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5715): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 5715): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5715): 	at java.lang.reflect.Method.invoke(Method.java:372)
I/MultiDex( 6197): VM with version 2.1.0 has multidex support
W/System.err( 5715): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 5715): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/MultiDex( 6197): install
I/MultiDex( 6197): VM has multidex support, MultiDex support library is disabled.
E/UEI.SmartControl( 5715): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/QRemote ( 5715): [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
W/libprocessgroup( 1037): failed to open /acct/uid_1000/pid_5805/cgroup.procs: No such file or directory
W/ActivityManager( 1037): Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,D/QRemote ( 5715): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
I/QRemote ( 5715): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
I/ActivityManager( 1037): Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=6234 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/QRemote ( 5715): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,D/BluetoothManagerService( 1037): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1037): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@afedf9 mBinding = false
I/ActivityManager( 1037): Waited long enough for: ServiceRecord{34f042bd u0 com.android.calendar/.alerts.InitAlarmsService}
D/PackageBroadcastService( 2373): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
D/ChimeraCfgMgr( 2373): Loading module com.google.android.gms.games from APK com.google.android.gms
,I/art     (  351): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 467us total 22.040ms
D/ChimeraCfgMgr( 2373): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Finsky  ( 6158): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Vision  ( 2373): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 2373): Failed to find package metadata for com.example.hello
D/Vision  ( 2373): No vision deps
,D/BluetoothManagerService( 1037): Message: 2
D/LocationManagerService( 1037): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1037): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1037): JNI:system_update. Event-4
D/BluetoothManagerService( 1037): Sending off request.
D/LGBluetoothServiceAdapter( 3868): [BTUI] Precleanup
D/BluetoothAdapterState( 3868): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3868): Setting state to 13
I/BluetoothAdapterState( 3868): Bluetooth adapter state changed: 12-> 13
D/BluetoothManagerService( 1037): Message: 60
D/BluetoothManagerService( 1037): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1037): Bluetooth State Change Intent: 12 -> 13
D/BluetoothAdapterProperties( 3868): onBluetoothDisable()
I/BluetoothAdapterState( 3868): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/WifiService( 1037): New client listening to asynchronous messages
,I/art     (  351): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 464us total 20.560ms
D/Finsky  ( 6158): [1] 2.run: Finished loading 1 libraries.
I/art     (  351): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 415us total 19.817ms
,I/ActivityManager( 1037): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=6254 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/WifiServiceImplEx( 1037): setWifiEnabled: false pid=5876, uid=10319, package= com.example.hello, App Lable : HelloWorld
D/WifiService( 1037): setWifiEnabled: false pid=5876, uid=10319
E/WifiService( 1037): Invoking mWifiStateMachine.setWifiEnabled
D/BluetoothAdapterProperties( 3868): Scan Mode:20
D/BluetoothAdapterState( 3868): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/BtOppRfcommListener( 3868): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-l2cap( 3868): L2CAP - L2CA_Deregister() called for PSM: 0x000f
D/btif_config_util( 3868): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/bt-btif ( 3868): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
V/BluetoothFtpService:RfcommSocketAcceptThread( 3868): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothSapService( 3868): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothPbapService( 3868): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3868): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3868): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3868): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 3868): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 3868): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 3868): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3868): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3868): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
D/[BNRAppListMgrReceiver]( 5952): android.intent.action.PACKAGE_ADDED : com.example.hello
,W/bt-l2cap( 3868): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3868): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3868): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3868): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3868): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3868): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3868): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3868): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3868): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3868): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3868): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 3868): bta_gattc_deregister Deregister Failedm unknown client cif
E/WifiStateMachine( 1037):  ConnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1037):  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1037):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1037):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1037): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1037): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1037): doBoolean: SET_NETWORK 0 bssid any
I/jxcore-log( 5876): ****TEST TOOK:  5220  ms ****
I/jxcore-log( 5876): 
D/WifiNative-wlan0( 1037): SET_NETWORK 0 bssid any: returned true
,D/WifiNative-wlan0( 1037): doBoolean: SAVE_CONFIG
D/LocationManagerService( 1037): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1037): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1037): JNI:system_update. Event-4
I/jxcore-log( 5876): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5876): 
D/Finsky  ( 6158): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ConfigFetchService( 2373): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/[SystemUI]BluetoothHandler( 1472): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
I/BluetoothMapService( 3868): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 3868): STATE_TURNING_OFF
V/BtOppService( 3868): Receiver DISABLED_ACTION 
V/BluetoothMapService( 3868): Handler(): got msg=4
D/BluetoothMapService( 3868): MAP Service closeService in
D/BluetoothMapMasInstance( 3868): MAP Service shutdown
D/LGBluetoothMapAdapter( 3868): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3868): MAP Service closeService out
D/LGBluetoothAPIService( 1969): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/BtOppRfcommListener( 3868): stopping Accept Thread
V/BtOppRfcommListener( 3868): close mBtServerSocket
V/BtOppRfcommListener( 3868): waiting for thread to terminate
I/BtOppRfcommListener( 3868): BluetoothSocket listen thread finished
V/BtOppRfcommListener( 3868): done waiting for thread to terminate
D/WifiNative-wlan0( 1037): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2714): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/CommandListener(  309): Clearing all IP addresses on wlan0
D/DhcpStateMachine( 1037): RunningState{ when=-19ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,I/art     (  351): Background concurrent mark sweep GC freed 808(34KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 6.128ms total 25.439ms
I/ConfigFetchService( 2373): launchTask
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1037): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,I/ActivityManager( 1037): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6271 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,V/BtOppService( 3868): onDestroy
D/LGBluetoothOppAdapter( 3868): [BTUI] LGBluetoothOppAdapter cleanup
E/WifiStateMachine( 1037):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
D/LGWifiP2pService( 1037): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiMonitor( 1037): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1ea98a3
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
D/LGWifiP2pService( 1037): P2pDisablingState
D/LGWifiP2pService( 1037): P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): p2p socket connection lost
D/LGWifiP2pService( 1037): P2pDisabledState
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1037): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1037):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiScanningService( 1037): SCAN_AVAILABLE : 1
D/RttService( 1037): SCAN_AVAILABLE : 1
D/RttService( 1037): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiScanningService( 1037): DefaultState got{ when=-3ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1037):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1037):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/LGWifiP2pService( 1037): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1037): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1037): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2714): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1037): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1037): doBoolean: SET ps 1
D/WifiNative-wlan0( 1037): SET ps 1: returned true
D/CommandListener(  309): Clearing all IP addresses on wlan0
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService( 1037): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1037): disableDataServiceNotify
D/DSQN    ( 1037): stop dsqn bin
,D/ConnectivityService( 1037): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1037): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1037): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1472): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1037): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker( 1037): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1037): Disconnected - quitting
V/WfdStateTracker( 1969): handleWifiStateChangedEvent: 0
V/WfdStateTracker( 1969): WfdStateTracker handleDirectStateChangedEvent: 0
,D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiNative-p2p0( 1037): doBoolean: TERMINATE
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/WifiNative-p2p0( 1037): TERMINATE: returned true
E/WifiStateMachine( 1037): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1037): useWiFiOffloading() : false
E/WifiStateMachine( 1037): CONFIG_LGE_WLAN_PATH : true
D/WfdsService( 1969): WifiP2pState is changed : false
D/WfdsService( 1969): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1969): Set the WFDS Monitor: false
D/WifiHS20( 1037): hidePasspointNotification off =false
W/Settings( 1037): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
W/Settings( 1037): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1037): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/WfdsMonitor( 1969): WFDS Monitor is stopped
D/WfdsService( 1969): STATE : WfdsDisabledState - enter
V/WfdStateTracker( 1969): WfdStateTracker handleDirectStateChangedEvent: 6
D/CtrlSupplicant( 1969): Received on exit socket, terminate
E/CtrlSupplicant( 1969): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1969): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1969): WfdsMonitorThread is received the interrupt - closing
W/WfdsSession:Controller( 1969): DefaultState - msg [9441355] is not handled
W/WfdsService( 1969): DefaultState - msg [9445378] is not handled
,I/WifiServerServiceExt( 1037): WIFI_STATE_CHANGED_ACTION [0]
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
D/WifiServerServiceExt( 1037): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1037): setSupplicantStateDISCONNECTED
D/ConnectivityService( 1037): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1037): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1037): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService( 1037): Removing idletimer
,W/Settings( 1037): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyNetworkFactory-1( 1876): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1876):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
V/ConfigFetchTask( 2373): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1VPhRfDQm5srjPREIyYt44KKwTmXfqnunlYelK5WavhrhpUpAhWO4Azjy6YmAnluxpDmKZub62RbBlTk5JdBYo_l_nQIT7wj6NIxI9YBVJ5pZktAB6WzoZkifoCiyofkfvEqXUHzORaKzOVYsvJUoN99JUoT_WJv_YzxDVuitm4JEW09Y_0jeteNTQ9mo7RltcIS2B9iMfU_GbNEe5kKQL5XALBLhCicNaXbXqKrh7RpsRXCuo
E/ConnectivityService( 1037): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/WIFI    ( 1037): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1037):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy( 1037): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1037): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1037): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1037): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1037): ignore wifi update if we are not in OPENING or CLOSING
V/JNIHelp ( 6197): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,W/ResourcesManager( 6271): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6271): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6271): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6271): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
,W/ResourcesManager( 6271): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6254): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6254): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1472): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1472): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
W/ResourcesManager( 6271): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/GoogleURLConnFactory( 2373): Using platform SSLCertificateSocketFactory
I/PeopleContactsSync( 2373): CP2 sync disabled
D/Finsky  ( 6158): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/MultiDex( 6254): VM with version 2.1.0 has multidex support
I/MultiDex( 6254): install
I/MultiDex( 6254): VM has multidex support, MultiDex support library is disabled.
,I/wpa_supplicant( 2714): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 2714): monitor socket send errors count : 1
I/wpa_supplicant( 2714): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1969-2\x00 that cannot receive messages
D/UEI.SmartControl( 6234): Quickset Services start...
,D/WifiMonitor( 1037): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1037): Dropping event because (p2p0) is stopped
I/ActivityManager( 1037): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6305 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/UEI.SmartControl( 6234): Manufacture = LGE
D/UEI.SmartControl( 6234): Id = LGNevo
D/DhcpStateMachine( 1037): StoppedState
D/DhcpStateMachine( 1037): StoppedState{ when=-178ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/AlarmManager( 1037): RTC_WAKEUP set : Alarm{169e3f97 type 0 when 1457094134160 com.android.vending} when 1457094134160
,D/Finsky  ( 6158): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
E/WifiStateMachine( 1037):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_ON_QUIT 0 0
D/UEI.SmartControl( 6234): File observer start...
E/UEI.SmartControl( 6234): IR Port is disabled: false
,D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
,I/wpa_supplicant( 2714): wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
W/wpa_supplicant( 2714): USIM:  scard_deinit function
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
E/WifiMonitor( 1037): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,E/WifiMonitor( 1037): WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
E/WifiStateMachine( 1037):  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=70142
E/WifiStateMachine( 1037):  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=70142
V/JNIHelp ( 6254): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
E/WifiStateMachine( 1037):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=70143  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1037):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=70143  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
D/Tethering( 1037): InitialState.processMessage what=4
D/Tethering( 1037): sendTetherStateChangedBroadcast 0, 0, 0
E/WifiStateMachine( 1037):  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1037):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/AndroidRuntime( 6287): 
D/AndroidRuntime( 6287): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6287): CheckJNI is OFF
,D/TelephonyIcons( 1472): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
D/UEI.SmartControl( 6234): Starting file observer...
D/UEI.SmartControl( 6234): Extracting JNI libs...
D/UEI.SmartControl( 6234): --- this system supports 32-bit or 64-bit only
,W/ActivityThread( 6197): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6197): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16d29391: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6197): Installed default security provider GmsCore_OpenSSL
,W/ActivityThread( 6254): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6254): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16d29391: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6254): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 6271): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,D/BluetoothManagerService( 1037): Message: 20
V/BluetoothPbapReceiver( 3868): PbapReceiver onReceive 
D/BluetoothManagerService( 1037): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@467f125:true
V/BluetoothPbapReceiver( 3868): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3868): ***********state = 13
V/BluetoothPbapReceiver( 3868): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3868): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 3868): state: 13
V/BluetoothPbapService( 3868): Pbap Service closeService in
,V/BluetoothPbapService( 3868): successfully stopped pbap service
V/BluetoothPbapService( 3868): Pbap Service closeService out
V/BluetoothPbapService( 3868): Pbap Service onDestroy
V/BluetoothPbapService( 3868): Pbap Service closeService in
V/BluetoothPbapService( 3868): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 3868): [BTUI] cleanup
I/wpa_supplicant( 2714): wlan0: CTRL-EVENT-TERMINATING 
,D/WifiMonitor( 1037): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1037): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
D/UEI.SmartControl( 6234): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6234): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6234): --- Extracting JNI libs: libqs_armeabi-v7a.zip
E/WifiStateMachine( 1037):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
D/WifiMonitor( 1037): Disconnecting from the supplicant, no more events
D/WifiOffDelayIfNotUsed( 1037): stopMonitoring
E/WifiStateMachine( 1037): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1037): useWiFiOffloading() : false
E/WifiStateMachine( 1037): CONFIG_LGE_WLAN_PATH : true
D/WfdsService( 1969): Supplicant Connection state is changed : false
V/WfdStateTracker( 1969): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 1969): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1969): Set the WFDS Monitor: false
D/WfdsMonitor( 1969): WFDS Monitor is stopped
I/WifiServerServiceExt( 1037): WIFI_STATE_CHANGED_ACTION [1]
W/Settings( 1841): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiServerServiceExt( 1037): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1037): batteryPsActivateMsgHandler : this is not treated
D/StatusBar.NetworkController( 1472): refreshViews: Data not connected!! Set no data type icon / Roaming
I/art     ( 2138): Explicit concurrent mark sweep GC freed 11886(674KB) AllocSpace objects, 3(432KB) LOS objects, 51% free, 30MB/62MB, paused 13.984ms total 88.584ms
,D/AndroidRuntime( 6287): Calling main entry com.android.commands.pm.Pm
W/NativeLibraryUtils( 6254): Install did not work
W/NativeLibraryUtils( 6254): java.io.IOException: fcntl failed: EAGAIN (Try again)
W/NativeLibraryUtils( 6254): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:123)
W/NativeLibraryUtils( 6254): 	at java.nio.FileChannelImpl.tryLock(FileChannelImpl.java:181)
W/NativeLibraryUtils( 6254): 	at java.nio.channels.FileChannel.tryLock(FileChannel.java:584)
W/NativeLibraryUtils( 6254): 	at com.google.android.gms.common.util.ax.a(SourceFile:314)
W/NativeLibraryUtils( 6254): 	at com.google.android.gms.common.app.a.run(SourceFile:136)
W/NativeLibraryUtils( 6254): Caused by: android.system.ErrnoException: fcntl failed: EAGAIN (Try again)
W/NativeLibraryUtils( 6254): 	at libcore.io.Posix.fcntlFlock(Native Method)
W/NativeLibraryUtils( 6254): 	at libcore.io.ForwardingOs.fcntlFlock(ForwardingOs.java:70)
W/NativeLibraryUtils( 6254): 	at java.nio.FileChannelImpl.basicLock(FileChannelImpl.java:121)
W/NativeLibraryUtils( 6254): 	... 4 more
,I/UEI.SmartControl( 6234): --- Selecting new region: 6
I/UEI.SmartControl( 6234): Model = LG-D855
,D/UEI.SmartControl( 6234): QS Service created
D/libc-netbsd(  309): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1037): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/ConfigFetchTask( 2373): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 2373): fetch service done; releasing wakelock
,I/art     ( 1037): Explicit concurrent mark sweep GC freed 53629(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 44MB/66MB, paused 2.320ms total 187.220ms
,I/ConfigFetchService( 2373): stopping self
D/BluetoothManagerService( 1037): Message: 30
,D/BluetoothManagerService( 1037): Message: 30
D/LocalBluetoothProfileManager( 6271): Adding local MAP profile
D/BluetoothMap( 6271): Create BluetoothMap proxy object
D/BluetoothManagerService( 1037): Message: 30
D/BluetoothManagerService( 1037): Message: 30
,I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/LocalBluetoothProfileManager( 6271): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 6271):  get() - isFeatureLoaded : false
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/UEI.SmartControl( 6234): Service initServices...
I/ActivityManager( 1037): Force stopping com.example.hello appid=10319 user=-1: uninstall pkg
I/ActivityManager( 1037): Killing 5876:com.example.hello/u0a319 (adj 0): stop com.example.hello
,D/UEI.SmartControl( 6234): QS start get config
I/WindowState( 1037): WIN DEATH: Window{1628e29 u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService( 1037): Client connection lost with reason: 4
,D/InputDispatcher( 1037): Focus left window: Window{1628e29 u0 com.example.hello/com.example.hello.MainActivity}
,D/InputDispatcher( 1037): Window went away: Window{1628e29 u0 com.example.hello/com.example.hello.MainActivity}
D/UEI.SmartControl( 6234): Loading JNI Libs...
,W/PackageSettings( 1037): Skipping PackageSetting{3e62c4d2 com.test.thalitest/10311} due to missing metadata
,E/libprocessgroup( 1037): failed to kill 1 processes for processgroup 5876
I/ActivityManager( 1037):   Force finishing activity ActivityRecord{122334d u0 com.example.hello/.MainActivity t4}
,W/bt-btif ( 3868): ag scb idx 1 not allocated
,E/bt-btif ( 3868): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3868): L2CAP - L2CA_Deregister() called for PSM: 0x0019
D/bt_hci_bdroid( 3868): cleanup
W/bt-l2cap( 3868): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3868): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3868): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3868): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3868): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3868): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3868): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3868): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3868): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3868): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3868): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3868): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3868): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3868): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3868): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3868): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3868): L2CAP - PSM: 0x001b not found for deregistration
E/bt-btif ( 3868): bta_gattc_deregister Deregister Failedm unknown client cif
I/bt_lpm  ( 3868): LPM is already off!!!
I/bt_userial_mct( 3868): exiting userial_read_thread
D/bt_userial_mct( 3868): Leaving userial_evt_read_thread()
D/bt_userial_mct( 3868): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 3868): hw_epilog_process
D/bt_hci_bdroid( 3868): cleanup Finalizing cleanup
D/bt_userial_mct( 3868): userial_close
E/bt_userial_mct( 3868): pthread_join() FAILED result:3
I/bt_vendor( 3868): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
E/GBMv2   (  336): DFP En is all cleared set to be enabled
,D/SplitWindowPolicy( 1969): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
W/ActivityManager( 1037): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/SplitWindowPolicy( 1969): topRunningActivity=ActivityInfo{216c358c co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
W/ActivityManager( 1037): Spurious death for ProcessRecord{2708e605 5876:com.example.hello/u0a319}, curProc for 5876: null
D/LGBluetoothUserBindClient( 6271): [BTUI] initUserBindClient
I/ActivityManager( 1037): Force stopping com.example.hello appid=10319 user=0: pkg removed
,I/ActivityManager( 1037):   Force finishing activity ActivityRecord{122334d u0 com.example.hello/.MainActivity t4 f}
W/ActivityManager( 1037): Duplicate finish request for ActivityRecord{122334d u0 com.example.hello/.MainActivity t4 f}
W/ContextImpl( 6271): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/SplitWindowPolicy( 1969): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1969): topRunningActivity=ActivityInfo{29aba4d5 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
,D/KeyguardModel( 1472): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
D/LIA_Service_RemotePackageHandler( 2035): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.example.hello
D/LIA_MrGDBLogger_PackageInfoDetector( 3801): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.example.hello
W/System.err( 4535): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 4535): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4535): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4535): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4535): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4535): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4535): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4535): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4535): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4535): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4535): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4535): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
W/GeofencerStateMachine( 1841): Ignoring removeGeofence because network location is disabled.
,I/[LGHome]EVENT( 2089): [Launcher.java:5338:onStart()]onStart
I/[LGHome]EVENT( 2089): [Launcher.java:903:onResume()]onResume
,I/[LGHome]EVENT( 2089): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
E/LGBluetoothAvrcpQcomAdapter( 3868): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3868): [BTUI] [+] updateMediaPlayerInfo
I/[LGHome]Launcher.Model( 2089): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/DockEventReceiver( 6271): finishStartingService: stopping service
,D/ActivityThread( 6305): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
I/art     ( 4591): Explicit concurrent mark sweep GC freed 10204(560KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 618us total 97.480ms
,D/bt_hci_bdroid( 3868): set_power 0
I/bt_vendor( 3868): bt-vendor : BT_VND_OP_POWER_CTRL: Off
,I/bt_vendor( 3868): bluetooth satus is on
I/bt_vendor( 3868): bt-vendor : resetting BT status
I/bt_vendor( 3868): Starting hciattach daemon
I/bt_vendor( 3868): try to set false
I/bt_vendor( 3868): Starting hciattach daemon
I/bt_vendor( 3868): try to set false
I/bt_vendor( 3868): cleanup
I/GKI_LINUX( 3868): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3868): GKI_exit_task 0 done
I/GKI_LINUX( 3868): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3868): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/administrator( 1037): Handling package changes for user 0
,D/ActivityThread( 6305): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
D/ActionManagerService( 1927): notifyUserLog: 1000003
D/LIA_Informant_ActionManagerMessageHandler( 3801): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]GBoardWebView( 2089): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
I/[SystemUI]QSlideListController( 1472): onReceive = android.intent.action.PACKAGE_REMOVED
D/BluetoothInputDevice( 6271): Proxy object connected
D/HidProfile( 6271): Bluetooth service connected
D/BluetoothPan( 6271): BluetoothPAN Proxy object connected
D/PanProfile( 6271): Bluetooth service connected
I/InputReader( 1037): Reconfiguring input devices.  changes=0x00000010
,D/BluetoothMap( 6271): Proxy object connected
D/MapProfile( 6271): Bluetooth service connected
D/BluetoothMap( 6271): getConnectedDevices()
W/ActivityManager( 1037): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/BluetoothMap( 6271): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 6271): [BTUI] onServiceConnected
I/[LGHome]LGActivityUtil( 2089): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/KeyguardModel( 1472): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1472): createShortcutInfo...
D/LGBluetoothAuthorization( 6271): [BTUI] cancel All Notification
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
D/BluetoothAdapterState( 3868): Stopping profile services that were post enabled
D/BluetoothPermissionRequest( 6271): onReceive
D/LGBluetoothAuthorization( 6271): [BTUI] cancel All Notification
,D/LGBluetoothResetSettingReceiver( 6271): return without doing reset settings.
W/ActivityManager( 1037): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager( 1037): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/[LGHome]EVENT( 2089): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2089): [Launcher.java:1114:onPause()]onPause
D/KeyguardModel( 1472): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1472): createShortcutInfo...
D/ActionManagerService( 1927): notifyUserLog: 1000004
I/[LGHome]GBoardWebView( 2089): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,D/LIA_Informant_ActionManagerMessageHandler( 3801): handleMessage: what(1000) actionID(0x1000004)
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.android.mms: Resource ID #0x0
V/BoardContentProvider( 3801): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/KeyguardModel( 1472): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1472): createShortcutInfo...
I/GBoardWebViewUtils( 2089): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2089): , create_time: 1430558575574
I/GBoardWebViewUtils( 2089): , expire_time: 0
I/GBoardWebViewUtils( 2089): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2089): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2089): , display: false
I/GBoardWebViewUtils( 2089): , animation: false }
I/GBoardWebViewUtils( 2089): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2089): , create_time: 1430558575600
I/GBoardWebViewUtils( 2089): , expire_time: 0
I/GBoardWebViewUtils( 2089): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2089): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2089): , display: false
I/GBoardWebViewUtils( 2089): , animation: false }
D/SplitUIManager( 1893): split_name #11 / not available #0
I/GBoardWebViewUtils( 2089): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1455195784986
I/GBoardWebViewUtils( 2089): , create_time: 1455195785688
I/GBoardWebViewUtils( 2089): , expire_time: 0
I/GBoardWebViewUtils( 2089): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1455195784986&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2089): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2089): , display: false
I/GBoardWebViewUtils( 2089): , animation: false }
D/SplitUIService( 1893): removed split : 
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1472): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1472): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/ActivityManager( 1037): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/WallpaperManager( 2089): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@107ac837,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1472): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1472): createShortcutInfo...
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/SystemUI[Framework]( 1037): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx( 1037): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1037): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1037): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@107ac837,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1037): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher( 1037): Focus entered window: Window{b4a8153 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/Gmail   ( 6305): Observing account changes for notifications
W/ActivityManager( 1037): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/KeyguardModel( 1472): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1472): createShortcutInfo...
I/ActivityManager( 1037): Killing 5715:com.lge.qremote/u0a112 (adj 15): empty #17
,D/SplitUIManager( 1893): split_name #11 / not available #0
I/SplitUIService( 1893): split app #11
V/Finsky  ( 6158): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/[LGHome]EVENT( 2089): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2089): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
I/Gmail   ( 6305): getAccountsCursor
,I/NotificationService( 1037): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1037): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 1037): Receieved: android.intent.action.PACKAGE_REMOVED
,V/SIM_STK ( 1037): Menu title from STK is T-Mobile
,I/UEI.SmartControl( 6234): Supports setup maps: true
D/UEI.SmartControl( 6234): QS start statue = true Error code = 0
I/UEI.SmartControl( 6234): QS version = v2.7.10.1_RC1
I/UEI.SmartControl( 6234): QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
I/UEI.SmartControl( 6234): ### init IR Blaster...
,D/serial_port( 6234): Configuring serial port
D/KeyguardModel( 1472): handleShortcutListChanged...
W/libprocessgroup( 1037): failed to open /acct/uid_10112/pid_5715/cgroup.procs: No such file or directory
W/Finsky  ( 6158): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
W/ActivityManager( 1037): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,D/LGBluetoothAvrcpQcomAdapter( 3868): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3868): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3868): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3868): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3868): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3868): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3868): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3868): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3868): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3868): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3868): [BTUI] [-] updateMediaPlayerInfo
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/HeadsetService( 3868): Received stop request...Stopping profile...
D/PhoneStatusBar( 1472): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/PhoneStatusBar( 1472): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
W/ActivityManager( 1037): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/LGBluetoothHfpAdapter( 3868): [BTUI] LGBluetoothHfpAdapter cleanup
I/[SystemUI]NavigationThemeResource( 1472): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1472):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1472): , Keyguard show=false, IME shown=false, Panel expanded=false
W/LGBluetoothHeadsetServiceJni( 3868): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3868): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3521b9c5
D/HeadsetStateMachine( 3868): Exit Disconnected: -1
W/ActivityManager( 1037): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/BluetoothHeadset( 1037): Proxy object disconnected
D/AudioService( 1037): onServiceDisconnected: Bluetooth profile: 1
D/BluetoothHeadset( 1876): Proxy object disconnected
D/BluetoothHeadset( 1876): Proxy object disconnected
D/BluetoothHeadset( 1876): Proxy object disconnected
D/TaskPersister( 1037): removeObsoleteFile: deleting file=4_task.xml
I/[LGHome]EVENT( 2089): [Launcher.java:5349:onStop()]onStop
D/KeyguardModel( 1472): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1472): createShortcutInfo...
D/A2dpService( 3868): Received stop request...Stopping profile...
D/A2dpStateMachine( 3868): Exit Disconnected: -1
D/LGBluetoothAvrcpQcomAdapter( 3868): [BTUI] cleanup
D/KeyguardModel( 1472): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1472): createShortcutInfo...
,W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1472): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1472): createShortcutInfo...
I/art     ( 1037): Explicit concurrent mark sweep GC freed 19339(1312KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 44MB/66MB, paused 2.679ms total 361.996ms
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/LGBluetoothA2dpAdapter( 3868): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 3868): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3868): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3521b9c5
E/UEI.SmartControl( 6234): UEIBLaster setting for 616
I/UEI.SmartControl( 6234): Setting serial record hearder size = 2
D/KeyguardModel( 1472): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
I/UEI.SmartControl( 6234): configuring settings for MAXQ616
D/KeyguardModel( 1472): createShortcutInfo...
I/UEI.SmartControl( 6234): Get version...
D/BluetoothA2dp( 1037): Proxy object disconnected
D/AudioService( 1037): onServiceDisconnected: Bluetooth profile: 2
D/HidService( 3868): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3868): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3521b9c5
D/BluetoothInputDevice( 6271): Proxy object disconnected
W/ResourceType( 1472): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1472): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/HidProfile( 6271): Bluetooth service disconnected
D/HealthService( 3868): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3868): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3521b9c5
D/PanService( 3868): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3868): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3521b9c5
D/BtGatt.DebugUtils( 3868): handleDebugAction() action=null
D/BtGatt.GattService( 3868): Received stop request...Stopping profile...
D/BtGatt.GattService( 3868): stop()
D/BtGatt.AdvertiseManager( 3868): advertise clients cleared
D/KeyguardModel( 1472): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1472): createShortcutInfo...
D/BluetoothAdapterService( 3868): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3521b9c5
D/BluetoothPan( 6271): BluetoothPAN Proxy object disconnected
D/PanProfile( 6271): Bluetooth service disconnected
,D/UEI.SmartControl( 6234): serial port data available: 21
D/BluetoothMapService( 3868): Received stop request...Stopping profile...
D/BluetoothMapService( 3868): stop()
D/BluetoothMapEmailAppObserver( 3868): deinitObservers()
D/BluetoothMapEmailAppObserver( 3868): removeReceiver()
D/BluetoothAdapterService( 3868): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3521b9c5
V/BluetoothOppReceiver( 3868): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 3868): [BTUI] cancel opp incoming file confirm notification
D/BluetoothOppNotification( 3868): [BTUI] cancel opp active transfer file notification
D/HeadsetStateMachine( 3868): Unbinding service...
D/KeyguardModel( 1472): handleShortcutListChanged...
,D/BluetoothMap( 6271): Proxy object disconnected
D/MapProfile( 6271): Bluetooth service disconnected
D/AndroidRuntime( 6287): Shutting down VM
D/UEI.SmartControl( 6234): MAXQ616 A2-X4 software.
I/UEI.SmartControl( 6234): IR Blaster version: 256702256704300002
W/GAV2    ( 6305): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/UEI.SmartControl( 6234): QS saving settings...
D/UEI.SmartControl( 6234): IR Blaster version: 25672567
,D/HeadsetPhoneState( 3868): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3868): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 3868): [BTUI] listenForPhoneState : start = false
W/ActivityManager( 1037): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/LGBluetoothHfpManager( 3868): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 3868): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3868): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 3868): [BTUI] LGBluetoothHfpAdapter cleanup
I/BluetoothA2dpServiceJni( 3868): cleanupNative
I/GKI_LINUX( 3868): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3868): GKI_exit_task 2 done
I/GKI_LINUX( 3868): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3868): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3868): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3868): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3868): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 3868): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3868): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3868): Cleaning up Bluetooth PAN callback object
I/[LGHome]EVENT( 2089): [Launcher.java:5833:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 2089): [setNavigationBarColor] color=0x 0
D/[Concierge]WidgetView( 2089): notifyExtViewAvailable
,V/BluetoothMapService( 3868): Handler(): got msg=4
D/BluetoothMapService( 3868): MAP Service closeService in
D/LGBluetoothMapAdapter( 3868): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3868): MAP Service closeService out
D/BluetoothMapService( 3868): cleanup()
D/BluetoothMapService( 3868): MAP Service closeService in
D/LGBluetoothMapAdapter( 3868): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3868): MAP Service closeService out
D/BluetoothAdapterState( 3868): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3868): Setting state to 10
I/BluetoothAdapterState( 3868): Bluetooth adapter state changed: 13-> 10
I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/BluetoothFtpReceiver( 3868): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 3868): BluetoothFtpReceiver Start Service
D/BluetoothManagerService( 1037): Message: 60
D/BluetoothManagerService( 1037): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1037): Broadcasting onBluetoothStateChange(false) to 9 receivers.
D/UEI.SmartControl( 6234): serial port data available: 4
I/BluetoothAdapterState( 3868): Entering OffState
D/BluetoothPan( 6271): onBluetoothStateChange on: false
V/BluetoothFtpService( 3868): Ftp Service onStartCommand
V/BluetoothFtpService( 3868): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 3868): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 3868): Shutdown
D/BluetoothHeadset( 1876): onBluetoothStateChange: up=false
V/BluetoothFtpService( 3868): successfully stopped ftp service
V/BluetoothSapReceiver( 3868): [BTUI] checkServiceStart
D/BluetoothPbap( 6271): onBluetoothStateChange: up=false
V/BluetoothSapReceiver( 3868): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 3868): SapReceiver onReceive 
V/BluetoothSapReceiver( 3868): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3868):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3868): Calling SAP service start service with action = null
D/BluetoothHeadset( 1876): onBluetoothStateChange: up=false
V/BluetoothFtpService( 3868): Ftp Service onDestroy
V/BluetoothFtpService( 3868): Ftp Service closeService
D/BluetoothHeadset( 1876): onBluetoothStateChange: up=false
,V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/InputMethodManagerService( 1037): setImestate : 0
W/InputMethodManagerService( 1037): Got RemoteException sending setActive(false) notification to pid 5876 uid 10319
I/[LGHome]Launcher.Model( 2089): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,W/ContextImpl( 6234): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
I/UEI.SmartControl( 6234): Device manager: loading config....
D/UEI.SmartControl( 6234): ----------- loading internal config...
E/UEI.SmartControl( 6234): Loading SETTINGS...
,I/ActivityManager( 1037): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6382 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/BluetoothA2dp( 1037): onBluetoothStateChange: up=false
V/BluetoothSapService( 3868): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3868): state: 13
V/BluetoothSapService( 3868): Stopping SAP server process
V/BluetoothSapService( 3868): Sap Service closeSapService in
V/BluetoothSapService( 3868): Close listen Socket : 
V/BluetoothSapService( 3868): Close rfcomm Socket : 
V/BluetoothSapService( 3868): Close sapd  Socket : 
D/BluetoothHeadset( 1037): onBluetoothStateChange: up=false
D/BluetoothMap( 6271): onBluetoothStateChange: up=false
,V/BluetoothSapService( 3868): Sap Service closeSapService out
V/BluetoothSapService( 3868): Sap Service onDestroy
V/BluetoothSapService( 3868): Sap Service closeSapService in
V/BluetoothSapService( 3868): Close listen Socket : 
V/BluetoothSapService( 3868): Close rfcomm Socket : 
V/BluetoothSapService( 3868): Close sapd  Socket : 
V/BluetoothSapService( 3868): Sap Service closeSapService out
E/UEI.SmartControl( 6234): Services init done
D/UEI.SmartControl( 6234): QS Service init finished
D/UEI.SmartControl( 6234): QS Service version name: 2.1.91
D/UEI.SmartControl( 6234): QS Service version code: 201091
D/BluetoothInputDevice( 6271): onBluetoothStateChange: up=false
D/UEI.SmartControl( 6234): Service requested: Control
D/BluetoothManagerService( 1037): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1037): Broadcasting onBluetoothServiceDown() to 7 receivers.
D/UEI.SmartControl( 6234): Service.onUnbind: IControl
D/UEI.SmartControl( 6234): Service.onDestroy
D/UEI.SmartControl( 6234): Lock is in USE false
D/UEI.SmartControl( 6234): unbind internal service
D/serial_port( 6234): close(fd = 25)
D/BluetoothManagerService( 1037): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1037): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1037): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@afedf9 mBinding = false
D/BluetoothManagerService( 1037): Sending unbind request.
I/UEI.SmartControl( 6234): Serial port is closed.
I/UEI.SmartControl( 6234): Serial port is closed.
D/BluetoothManagerService( 1037): Bluetooth State Change Intent: 13 -> 10
D/UEI.SmartControl( 6234): Blaster closed
D/UEI.SmartControl( 6234): Shut down QS...
D/UEI.SmartControl( 6234): Stopping QS lib
D/UEI.SmartControl( 6234): QS lib stop result = true
D/UEI.SmartControl( 6234): Stopped QS lib
D/UEI.SmartControl( 6234): Stopped file observer...
D/UEI.SmartControl( 6234): QS shutdown complete
D/UEI.SmartControl( 6234): QS Service created
D/LGBluetoothAPIService( 1969): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1969): Message: 2
D/LGBluetoothAPIService( 1969): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@1c0c44ea mBinding = false
I/[SystemUI]BluetoothHandler( 1472): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
I/Timeline( 1037): Timeline: Activity_windows_visible id: ActivityRecord{a1bb28c u0 com.lge.launcher2/.Launcher t3} time:71423
D/BluetoothAdapter( 1472): 982271741: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1472): 982271741: getState() :  mService = null. Returning STATE_OFF
W/IInputConnectionWrapper( 2089): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 2089): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/GKI_LINUX( 3868): gki_task task_id=1 [BTIF] terminating
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/LGBluetoothAPIService( 1969): Sending unbind request.
I/GKI_LINUX( 3868): GKI_exit_task 1 done
I/GKI_LINUX( 3868): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3868): cleanupNative: return from cleanup
I/art     ( 3868): --- WEIRD: removing null entry 246
W/art     ( 3868): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 3868): Cleaning up Bluetooth Service callback object
D/LGBluetoothFeatureConfig( 6271): isPrivacyLogsEnabled : true
E/LGBluetoothEventManager( 6271): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 6271): [BTUI] clear device connection state
I/UEI.SmartControl( 6234): Notify AllClients services are ready: 11
D/UEI.SmartControl( 6234): -----service ready thread exits
D/LGBluetoothSettingsDBObserver( 3868): [BTUI] unregister observer for LG device name DB
I/art     ( 3868): System.exit called, status: 0
,I/AndroidRuntime( 3868): VM exiting with result code 0, cleanup skipped.
D/UEI.SmartControl( 6234): -- Open brand translation xml: brands_translations_ko
E/b       ( 1712): Unable to connect to the editor to retrieve text... will retry later
V/AudioFlinger(  314): 3868 died, releasing its sessions
V/AudioFlinger(  314):  pid 1876 @ 0
V/AudioFlinger(  314):  pid 2202 @ 1
V/AudioFlinger(  314):  pid 3417 @ 2
V/AudioFlinger(  314):  pid 3417 @ 3
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LGBluetoothUserBindClient( 6271): [BTUI] onServiceDisconnected
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2089): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2089): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/UEI.SmartControl( 6234): Service initServices...
D/UEI.SmartControl( 6234): QS start get config
W/ResourcesManager( 1037): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 2089): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 2089): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
,I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourceType( 1037): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[Concierge]WidgetView( 2089): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,I/ActivityManager( 1037): Process com.android.bluetooth (pid 3868) has died
,W/ActivityManager( 1037): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
D/[Concierge]WidgetView( 2089): change position of spinner
,D/[Concierge]Service( 2631): onStartCommand(). Type : 8
D/[Concierge]Service( 2631): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2631): Update widget ID : 11
W/ActivityManager( 1037): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/[Concierge]WidgetView( 2089): initWebView(). Time : 1457094135614
,W/ResourcesManager( 6382): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/[Concierge]Service( 2631): onStartCommand(). Type : 0
I/ActivityManager( 1037): Killing 5740:com.lge.clock/u0a10 (adj 15): empty #17
,E/Gmail   ( 6305): Error finding the version of the Email provider.....
E/Gmail   ( 6305): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6305): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6305): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1235)
E/Gmail   ( 6305): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:187)
E/Gmail   ( 6305): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6305): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6305): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6305): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Gmail   ( 6305): getAccountsCursor
W/EmailMigration( 6305): We do not support migrating this version of the Email provider.
I/GLSUser ( 2138): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2138): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2138): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2138): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/AuthorizationBluetoothService( 2138): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,W/libprocessgroup( 1037): failed to open /acct/uid_10010/pid_5740/cgroup.procs: No such file or directory
V/GLSActivity( 2138): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ContextImpl( 6271): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/DockEventReceiver( 6271): finishStartingService: stopping service
,I/ActivityManager( 1037): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6408 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,W/Finsky  ( 6158): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/ActivityManager( 1037): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=6430 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/[Concierge]WebView( 2089): Return exist ConciergeWebView. Reuse : 65856980
D/[Concierge]WidgetView( 2089): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2089): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
I/[LgeWidgetLib]ExtViewHost( 2089): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@21c647ad
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2089): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
E/UEI.SmartControl( 6234): unzip: java.io.IOException: write failed: EBADF (Bad file number)
I/UEI.SmartControl( 6234): Specific region DB is not found, use default...
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]EVENT( 2089): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,D/[Concierge]WidgetView( 2089): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2089): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
W/[Concierge]WidgetView( 2089): Widget kill message received. Destory myself. My : 1457094093334, New one : 1457094135614
D/[Concierge]WidgetView( 2089): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2089): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2089): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
V/SIM_STK ( 1037): Menu title from STK is T-Mobile
W/ResourcesManager( 6408): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 6408): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6408): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2089): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 6408): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/UEI.SmartControl( 6234): unzip: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.maxq616/app_korea/dac1a: open failed: EROFS (Read-only file system)
I/UEI.SmartControl( 6234): Supports setup maps: true
W/System.err( 6234): java.lang.NullPointerException: Attempt to get length of null array
W/System.err( 6234): 	at com.uei.control.core.ab.b(Unknown Source)
W/System.err( 6234): 	at com.uei.control.core.ab.a(Unknown Source)
W/System.err( 6234): 	at com.uei.control.core.ab.a(Unknown Source)
W/System.err( 6234): 	at com.uei.control.Service.a(Unknown Source)
W/System.err( 6234): 	at com.uei.control.Service.onCreate(Unknown Source)
W/System.err( 6234): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
W/System.err( 6234): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
W/System.err( 6234): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
W/System.err( 6234): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6234): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6234): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 6234): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6234): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6234): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 6234): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6234): java.lang.NullPointerException: Attempt to get length of null array
E/UEI.SmartControl( 6234): 	at com.uei.control.core.ab.b(Unknown Source)
E/UEI.SmartControl( 6234): 	at com.uei.control.core.ab.a(Unknown Source)
E/UEI.SmartControl( 6234): 	at com.uei.control.core.ab.a(Unknown Source)
E/UEI.SmartControl( 6234): 	at com.uei.control.Service.a(Unknown Source)
E/UEI.SmartControl( 6234): 	at com.uei.control.Service.onCreate(Unknown Source)
E/UEI.SmartControl( 6234): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
E/UEI.SmartControl( 6234): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/UEI.SmartControl( 6234): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/UEI.SmartControl( 6234): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UEI.SmartControl( 6234): 	at android.os.Looper.loop(Looper.java:135)
E/UEI.SmartControl( 6234): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/UEI.SmartControl( 6234): 	at java.lang.reflect.Method.invoke(Native Method)
E/UEI.SmartControl( 6234): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/UEI.SmartControl( 6234): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/UEI.SmartControl( 6234): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
E/UEI.SmartControl( 6234): 
E/UEI.SmartControl( 6234): java.lang.NullPointerException: Attempt to get length of null array
E/UEI.SmartControl( 6234): 	at com.uei.control.core.ab.b(Unknown Source)
E/UEI.SmartControl( 6234): 	at com.uei.control.core.ab.a(Unknown Source)
E/UEI.SmartControl( 6234): 	at com.uei.control.core.ab.a(Unknown Source)
E/UEI.SmartControl( 6234): 	at com.uei.control.Service.a(Unknown Source)
E/UEI.SmartControl( 6234): 	at com.uei.control.Service.onCreate(Unknown Source)
E/UEI.SmartControl( 6234): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
E/UEI.SmartControl( 6234): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/UEI.SmartControl( 6234): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/UEI.SmartControl( 6234): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UEI.SmartControl( 6234): 	at android.os.Looper.loop(Looper.java:135)
E/UEI.SmartControl( 6234): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/UEI.SmartControl( 6234): 	at java.lang.reflect.Method.invoke(Native Method)
E/UEI.SmartControl( 6234): 	at java.lang.reflect.Method.invoke(Met,hod.java:372)
E/UEI.SmartControl( 6234): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/UEI.SmartControl( 6234): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/UEI.SmartControl( 6234): ### init IR Blaster...
D/serial_port( 6234): Configuring serial port
E/UEI.SmartControl( 6234): UEIBLaster setting for 616
I/UEI.SmartControl( 6234): Setting serial record hearder size = 2
I/UEI.SmartControl( 6234): configuring settings for MAXQ616
I/UEI.SmartControl( 6234): Get version...
D/BluetoothAdapterApp( 6408): Loading JNI Library
,E/GBMv2   (  336): DFP En is all cleared set to be enabled
E/GBMv2   (  336): Set value is all cleared set the max
I/GBMv2   (  336): DFP Enabled. Ignore VFP set
E/SQLiteLog( 6305): (283) recovered 1712 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
D/UEI.SmartControl( 6234): serial port data available: 21
D/BluetoothAdapterApp( 6408): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@321349c2 Instance Count = 1
W/FileUtils( 6305): Failed to chmod(/data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)

```
