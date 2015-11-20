#### Test 50388019aa1a16d_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
D/QRemote ( 6612): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
D/Finsky  ( 6483): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/QRemote ( 6612): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6612): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6612): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6612): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6612): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6612): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6612): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/Finsky  ( 6483): [1] GearheadStateMonitor.onReady: sIsProjecting:false
V/QRemote ( 6612): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,D/QRemote ( 6612): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
I/art     ( 2127): Explicit concurrent mark sweep GC freed 16316(903KB) AllocSpace objects, 6(864KB) LOS objects, 51% free, 30MB/62MB, paused 1.430ms total 49.068ms
D/LgDataFeature( 6612): LgDataFeature() Constructor: none
D/LgDataFeature( 6612): LgDataFeature() Constructor Done, null
V/SoundPool( 6612): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6612): load: fd=27, offset=10857164, length=17813, priority=1
V/SoundPool( 6612): create sampleID=1, fd=28, offset=17813 length=10857164
V/SoundPool( 6612): doLoad: loading sample sampleID=1
I/QRemote ( 6612): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 6612): Start decode
V/MediaPlayer[Native]( 6612): decode(28, 10857164, 17813)
V/MediaPlayerService(  318): decode(24, 10857164, 17813)
W/BrunchPlayerTypeImpl(  318): [SelectPlayer] LocalType
W/BrunchPlayerTypeImpl(  318): [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
W/BrunchPlayerTypeImpl(  318): [FindUsePlayer] type = [application/ogg]
W/BrunchPlayerTypeImpl(  318): [FindUsePlayer] componentName = [9101]
W/MediaPlayerFactory(  318): [getPlayerType:fd] nType = 3
V/MediaPlayerService(  318): player type = 3
V/AwesomePlayer(  318): AwesomePlayer create()
V/AwesomePlayer(  318): reset_l() 
V/AwesomePlayer(  318): cancelPlayerEvents
V/AwesomePlayer(  318): setAudioSink() 
V/AwesomePlayer(  318): reset_l() 
V/AudioCache(  318): notify(0xb122d600, 8, 0, 0)
V/AudioCache(  318): ignored
V/AwesomePlayer(  318): cancelPlayerEvents
D/Utils   (  318): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  318): setDataSource_l dataSource
V/LGParserOSAL(  318): SniffLGParser start
V/LGParserOSAL(  318): MainType:5, SubType=0
V/LGParserOSAL(  318): #### check Mime : application/ogg
V/LGParserOSAL(  318): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  318): Use LGExtractor :application/ogg 
D/QRemote ( 6612): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 6612): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
--------- beginning of system
V/LGMDMManager( 6612): Create singleton instance
I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/LGParserOSAL(  318): supported mime: application/ogg
V/AwesomePlayer(  318): setDataSource_l() extractor countTracks=1
V/AwesomePlayer(  318): track of type 'audio/vorbis' does not publish bitrate
V/AwesomePlayer(  318): mBitrate = -1 bits/sec
V/AwesomePlayer(  318): AudioTrack Setting
V/AwesomePlayer(  318): AudioTrack Setting channelCount = 2
V/AwesomePlayer(  318): setAudioSource() 
V/MediaPlayerService(  318): prepare
V/AwesomePlayer(  318): prepareAsync_l() 
V/MediaPlayerService(  318): wait for prepare
V/AwesomePlayer(  318): onPrepareAsyncEvent() 
V/AwesomePlayer(  318): initAudioDecoder() 
W/Utils   (  318): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  318): isOffloadSupported()
V/AudioPolicyManager(  318): isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  318): isOffloadSupported: stream_type != MUSIC, returning false
I/AudioFlinger(  318): isAudioPlaybackHookOn() false
V/AwesomePlayer(  318): getUseOffload() = 0 
V/OMXCodec(  318): OMXCodec::Create
V/OMXCodec(  318): findMatchingCodecs()
V/OMXCodec(  318): matching 'OMX.google.vorbis.decoder' quirks 0x00000000
V/OMXCodec(  318): matchingCodecs.size()=1
V/OMXCodec(  318): Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
D/OMXCodec(  318): Successfully allocated OMX node 'OMX.google.vorbis.decoder'
V/LGCodecAdapter(  318): LG Codec Adapter start
V/OMXCodec(  318): OMXCodec Createtor
V/OMXCodec(  318): setComponentRole
V/OMXCodec(  318): configureCodec protected=0
V/LGCodecAdapter(  318): called getLGCodecSpecificData
V/LGCodecOSAL(  318): Called LGgetCodecSpecificDataMETA
V/LGCodecOSAL(  318): Called LGconfigureCodecMETA
V/LGCodecOSAL(  318): Called LGconfigureCodecMSG
V/LGCodecOSAL(  318): Not support LGCodec
V/OMXCodec(  318): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  318): Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
V/OMXCodec(  318): Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
I/AwesomePlayer(  318): Could not offload audio decode, try pcm offload
W/Utils   (  318): bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
V/AudioSystem(  318): isOffloadSupported()
V/AudioPolicyManager(  318): isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
D/AudioPolicyManager(  318): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  318): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  318): init()
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  318): allocateBuffers
V/OMXCodec(  318): allocateBuffersOnPort portIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14343d0 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14344c0 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb1434560 on input port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14345b0 on input port
V/OMXCodec(  318): allocateBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb1434650 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14346f0 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb1434740 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb1434880 on output port
V/OMXCodec(  318): init() mAsyncCompletion wait!!! 
V/OMXCodec(  318): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  318): init() mAsyncCompletion wait!!! 
V/OMXCodec(  318): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  318): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  318): finishAsyncPrepare_l() 
V/AudioCache(  318): notify(0xb122d600, 5, 0, 0)
V/AudioCache(  318): ignored
V/AudioCache(  318): notify(0xb122d600, 1, 0, 0)
V/AudioCache(  318): prepared
V/AudioCache(  318): wait - success
V/MediaPlayerService(  318): start
V/AwesomePlayer(  318): play_l() 
V/AwesomePlayer(  318): play_l m_isDivXDRM=0, bpurchasefile:0
V/AwesomePlayer(  318): createAudioPlayer_l
V/AwesomePlayer(  318): seekAudioIfNecessary_l() 
V/AwesomePlayer(  318): startAudioPlayer_l() 
D/AudioPlayer(  318): start of Playback, useOffload 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  318): [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
V/OMXCodec(  318): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  318): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976144
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976304
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976384
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2973976704
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  318): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  318): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  318): allocateBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb1434740 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb14346f0 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb1434650 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] allocated buffer 0xb115f7e0 on output port
V/OMXCodec(  318): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  318): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  318): notify(0xb122d600, 6, 0, 0)
V/AudioCache(  318): ignored
V/MediaPlayerService(  318): wait for playback complete
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae806000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae807000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae808000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae809000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae80a000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae80b000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae80c000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae80d000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae80e000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae80f000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae810000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae811000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae812000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae813000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae814000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae815000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae816000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae817000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae818000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae819000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae81a000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae81b000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae81c000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae81d000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae81e000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae81f000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae820000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae821000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae822000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae823000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae824000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae825000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae826000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae827000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae828000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae829000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae82a000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae82b000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae82c000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae82d000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae82e000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae82f000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae830000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae831000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae832000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae833000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae834000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae835000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae836000, 0xb57f7000, 4096)
V/AudioCache(  318): write(0xb57f7000, 4096)
V/AudioCache(  318): memcpy(0xae837000, 0xb57f7000, 4096)
V/OMXCodec(  318): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  318): postAudioEOS() 
V/AudioCache(  318): write(0xb57f7000, 280)
V/AudioCache(  318): memcpy(0xae838000, 0xb57f7000, 280)
V/AwesomePlayer(  318): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  318): onStreamDone
V/AwesomePlayer(  318): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  318): notify(0xb122d600, 2, 0, 0)
V/AudioCache(  318): playback complete
V/AwesomePlayer(  318): pause_l() 
V/AudioCache(  318): notify(0xb122d600, 7, 0, 0)
V/AudioCache(  318): ignored
V/AwesomePlayer(  318): cancelPlayerEvents
D/AudioPlayer(  318): Pause Playback at 1068125
V/AudioCache(  318): wait - success
V/MediaPlayerService(  318): return size 205080, sampleRate=48000, channelCount = 2, format = 1
V/AwesomePlayer(  318): reset_l() 
V/AudioCache(  318): notify(0xb122d600, 8, 0, 0)
V/AudioCache(  318): ignored
V/AwesomePlayer(  318): cancelPlayerEvents
D/AudioPlayer(  318): reset: mPlaying=0 mReachedEOS=1 useOffload=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] stop mState=4
V/OMXCodec(  318): [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=4 , newState=5
V/OMXCodec(  318): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  318): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb14345b0 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb1434560 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb14344c0 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb14343d0 on port 0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb115f7e0 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb1434650 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb14346f0 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeing buffer 0xb1434740 on port 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
V/OMXCodec(  318): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  318): [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
V/OMXCodec(  318): [OMX.google.vorbis.decoder] onStateChange 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] Now Loaded.
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=6 , newState=1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
V/OMXCodec(  318): [OMX.google.vorbis.decoder] stopped in state 1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
V/OMXCodec(  318): [OMX.google.vorbis.decoder] setState mState=1 , newState=0
D/AudioPlayer(  318): AudioPlayer releasing audio source
D/AudioPlayer(  318): AudioPlayer done releasing audio source
V/AwesomePlayer(  318): reset_l() 
V/AwesomePlayer(  318): cancelPlayerEvents
V/AwesomePlayer(  318): ~AwesomePlayer call
V/AwesomePlayer(  318): reset_l() 
V/AwesomePlayer(  318): cancelPlayerEvents
V/SoundPool( 6612): close(28)
V/SoundPool( 6612): pointer = 0xaf202000, size = 205080, sampleRate = 48000, numChannels = 2
W/Finsky  ( 6483): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:4116
D/QRemote ( 6612): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/QRemote ( 6612): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
I/QRemote ( 6612): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6369): ------ IControl API: 11
D/UEI.SmartControl( 6369): File observer start...
E/UEI.SmartControl( 6369): IR Port is disabled: false
D/UEI.SmartControl( 6369): Starting file observer...
I/UEI.SmartControl( 6369): Registering callback...
I/UEI.SmartControl( 6369): ------ IControl API: 19
I/UEI.SmartControl( 6369): Registering Services Ready callback...
I/UEI.SmartControl( 6369): Notify client services are ready...
I/QRemote ( 6612): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6612): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6612): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6612): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6612): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6369): ------ IControl API: 8
D/QRemote ( 6612): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6612): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
D/QRemote ( 6612): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
D/QRemote ( 6612): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6612): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6612): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
D/AndroidRuntime( 6648): 
D/AndroidRuntime( 6648): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6648): CheckJNI is OFF
I/art     ( 1036): Explicit concurrent mark sweep GC freed 21079(1002KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.589ms total 165.208ms
D/QRemote ( 6612): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
I/ActivityManager( 1036): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=6656 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/QRemote ( 6612): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 6648): Calling main entry com.android.commands.am.Am
I/ActivityManager( 1036): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1967): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1036): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
V/ActivityStackEx( 1036): create ActivityStackEx
D/ActivityManager( 1036): setTaskToReturnTo : TaskRecord{f642076 #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1036): setTaskToReturnTo : TaskRecord{f642076 #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1036): AppWindowTokenEx init.. 
E/GBMv2   (  349): DFP En is all cleared set to be enabled
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{270c3cbf V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
D/LgeAbsQuickCoverView( 1418): mCoverXPos: 0 ,mCoverYPos: 0
D/LgeAbsQuickCoverView( 1418): mCoverWidth: 0 ,mCoverHeight: 0
I/MusicStore( 6656): Database version: 100
I/ActivityManager( 1036): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6691 uid=10318 gids={50318, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AndroidRuntime( 6648): Shutting down VM
W/Finsky  ( 6483): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
V/ActivityManager( 1036): Display changed displayId=0
D/DSDPConnection( 1871): Display #0 changed.
D/SplitWindowPolicy( 1967): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1967): topRunningActivity=ActivityInfo{10ea6da1 co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1967): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1967): topRunningActivity=ActivityInfo{cbdebc6 co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
D/ContextHelper( 6691): convertTheme. context->name=com.example.hello themeResourceId=16973833
V/SIM_STK ( 1036): Menu title from STK is T-Mobile
D/LgDataFeature( 6656): LgDataFeature() Constructor: none
D/LgDataFeature( 6656): LgDataFeature() Constructor Done, null
I/ConfigStore( 6656): Config Database version: 1
I/WebViewFactory( 6691): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/LibraryLoader( 6691): Loading: webviewchromium
I/LibraryLoader( 6691): Time to load native libraries: 3 ms (timestamps 7252-7255)
I/LibraryLoader( 6691): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6691): Binding Chromium to main looper Looper (main, tid 1) {12e0f591}
I/LibraryLoader( 6691): Expected native library version number "",actual native library version number ""
E/PlayEventLogger( 6656): Invalid device id bea67b7c50ddc6a9
I/chromium( 6691): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6691): Initializing chromium process, renderers=0
W/art     ( 6691): Attempt to remove local handle scope entry from IRT, ignoring
V/AudioPolicyService(  318): registerClient() client 0xb14c8a00, uid 10318
D/BluetoothManagerService( 1036): Message: 20
D/BluetoothManagerService( 1036): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b5919bd:true
,E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6656): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/chromium( 6691): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6691): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6691): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
I/Adreno-EGL( 6691): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6691): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6691): Build Date: 12/12/14 금
I/Adreno-EGL( 6691): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6691): Remote Branch: 
I/Adreno-EGL( 6691): Local Patches: 
I/Adreno-EGL( 6691): Reconstruct Branch: 
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6656): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  278): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  278): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  278): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6656): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/chromium( 6691): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
I/MediaRouter( 6656): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
W/chromium( 6691): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6691): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6691): onDetachedFromWindow called when already detached. Ignoring
I/NetworkMonitor( 6656): type=WIFI subType= reason=null isConnected=true
D/SystemWebViewEngine( 6691): CordovaWebView is running on device made by: LGE
W/art     ( 6691): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6691): Attempt to remove local handle scope entry from IRT, ignoring
D/OpenGLRenderer( 6691): Render dirty regions requested: true
I/OpenGLRenderer( 6691): Initialized EGL, version 1.4
D/OpenGLRenderer( 6691): Enabling debug mode 0
D/Atlas   ( 6691): Validating map...
V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SplitWindow( 1036): check instance of lgWin Window{19fb712f u0 com.example.hello/com.example.hello.MainActivity}
I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LgDataFeature( 6691): LgDataFeature() Constructor: none
D/LgDataFeature( 6691): LgDataFeature() Constructor Done, null
D/WearableService( 6139): callingUid 10005, callindPid: 6139
V/QRemote ( 6612): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
I/NetworkMonitor( 6656): type=WIFI subType= reason=null isConnected=true
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
I/SystemUI[Framework]( 1036): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
D/PhoneStatusBar( 1465): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
W/PhoneWindowManagerEx( 1036): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1036): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1036): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2dc3de81,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/Finsky  ( 6483): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
I/[SystemUI]NavigationThemeResource( 1465): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1465):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1465): , Keyguard show=false, IME shown=false, Panel expanded=false
E/QRemote ( 6612): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/Finsky  ( 6483): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6612): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1448020246682]
V/QRemote ( 6612): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6612): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/Finsky  ( 6483): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6612): [RemoteAppWidgetManager.java:36:startLoading()] oooooo 140518:startLoading:sWidgetHandler has [3] at [1448020246693]. skip
D/Finsky  ( 6483): [1] DailyHygiene.reschedule: Giving up. (failures=6)
D/KeyguardViewMediator( 1465): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
I/MusicLeanback( 6656): Stop autocaching.
I/MusicLeanback( 6656): Stop autocaching.
D/QRemote ( 6612): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
D/KeyguardUpdateMonitor( 1465): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1465): doKeyguard: not showing because lockscreen is off
D/DeviceConnectionService( 1836): client connected with version: 7571000
I/Timeline( 6691): Timeline: Activity_idle id: android.os.BinderProxy@1996501 time:77698
I/ActivityManager( 1036): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6749 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1036): Displayed com.example.hello/.MainActivity: +565ms (total +673ms)
I/Timeline( 1036): Timeline: Activity_windows_visible id: ActivityRecord{20c9f677 u0 com.example.hello/.MainActivity t2} time:77714
I/GoogleHttpClient( 6656): Falling back to old http client 0 java.lang.NoSuchMethodException: <init> [class android.content.Context, class java.lang.String, boolean, boolean]
I/chromium( 6691): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/MusicLeanback( 6656): Stop autocaching.
I/MusicLeanback( 6656): Stop autocaching.
E/AndroidProtocolHandler( 6691): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/MusicLeanback( 6656): Conditions not met for autocaching.
I/MusicLeanback( 6656): Stop autocaching.
D/WearableClient( 6656): WearableClientImpl.onPostInitHandler: done
D/WearableClient( 6656): WearableClientImpl.onPostInitHandler: done
D/WearableClient( 6656): WearableClientImpl.onPostInitHandler: done
E/GmsUtils( 6656): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
E/GmsUtils( 6656): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
I/chromium( 6691): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6691): 
D/JsMessageQueue( 6691): Set native->JS mode to OnlineEventsBridgeMode
W/ActivityManager( 1036): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/CheckinService( 2399): Done disabling old GoogleServicesFramework version
D/ActivityThread( 6749): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
W/ActivityManager( 1036): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/chromium( 6691): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6691): 
W/ActivityManager( 1036): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager( 1036): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager( 1036): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager( 1036): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 6749): Observing account changes for notifications
I/Gmail   ( 6749): getAccountsCursor
V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6749): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/jxcore_app_log( 6691): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435221760
D/JX-Cordova( 6691): jxcore cordova android initializing
W/ActivityManager( 1036): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 6749): Error finding the version of the Email provider.....
E/Gmail   ( 6749): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6749): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6749): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1235)
E/Gmail   ( 6749): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:187)
E/Gmail   ( 6749): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6749): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6749): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6749): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6749): We do not support migrating this version of the Email provider.
I/Gmail   ( 6749): getAccountsCursor
V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/jxcore-log( 6691): Initializing JXcore engine
W/jxcore-log( 6691): JXcore engine is ready
W/jxcore-log( 6691): Starting JXcore engine
I/ActivityManager( 1036): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6798 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager( 1036): Killing 6222:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/sensors_hal_Time( 1036): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1036): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time( 1036): tsOffsetIs: Apps: 78135095077; DSPS: 2701066; Offset : -4308235928
W/m.example.hello( 6691): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7528]" dev="sockfs" ino=7528 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 6691): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/m.example.hello( 6691): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9507]" dev="sockfs" ino=9507 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 6691): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/m.example.hello( 6691): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31941]" dev="sockfs" ino=31941 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
I/art     ( 1036): Explicit concurrent mark sweep GC freed 13291(599KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 3.134ms total 139.738ms
W/libprocessgroup( 1036): failed to open /acct/uid_10011/pid_6222/cgroup.procs: No such file or directory
I/GAV2    ( 6324): Thread[GAThread,5,main]: No campaign data found.
W/ResourcesManager( 6798): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
E/SQLiteLog( 6749): (283) recovered 388 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
W/jxcore-log( 6691): Platform android
W/jxcore-log( 6691): 
W/jxcore-log( 6691): Process ARCH arm
W/jxcore-log( 6691): 
,I/jxcore-log( 6691): JXcore Cordova bridge is ready!
I/jxcore-log( 6691): 
W/jxcore-log( 6691): JXcore engine is started
,D/LgDataFeature( 6798): LgDataFeature() Constructor: none
D/LgDataFeature( 6798): LgDataFeature() Constructor Done, null
,I/Gmail   ( 6749): getAccountsCursor
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6749): notifyAccountChanged
E/jxcore-log( 6691): >> LGE-LG-D855
E/jxcore-log( 6691): 
,I/Gmail   ( 6749): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/jxcore-log( 6691): Total memory 2995761152
I/jxcore-log( 6691): 
I/jxcore-log( 6691): Free memory 558751744
I/jxcore-log( 6691): 
I/jxcore-log( 6691): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6691): 
I/jxcore-log( 6691): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6691): 
I/Gmail   ( 6749): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/jxcore-log( 6691): userPath [ 'www' ]
I/jxcore-log( 6691): 
I/jxcore-log( 6691): Size 1440 2392
I/jxcore-log( 6691): 
I/jxcore-log( 6691): Screen Brightness 50
I/jxcore-log( 6691): 
E/jxcore-log( 6691): Dummy Error Log.
E/jxcore-log( 6691): 
I/Gmail   ( 6749): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6749): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6749): getAccountsCursor
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Babel   ( 6798): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6798): MmsConfig.loadMmsSettings
,I/Babel   ( 6798): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6798): MmsConfig.loadFromDatabase
,E/Babel   ( 6798): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6798): MmsConfig.loadFromResources
E/Babel   ( 6798): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6798): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,W/Settings( 6798): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/AudioCapabilities( 6798): Unsupported mime audio/evrc
W/AudioCapabilities( 6798): Unsupported mime audio/qcelp
W/VideoCapabilities( 6798): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6798): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6798): Unsupported mime audio/qcelp
W/AudioCapabilities( 6798): Unsupported mime audio/evrc
W/VideoCapabilities( 6798): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6798): Unsupported mime video/divx
W/VideoCapabilities( 6798): Unsupported mime video/divx311
W/VideoCapabilities( 6798): Unsupported mime video/divx4
I/ActivityManager( 1036): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6835 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/VideoCapabilities( 6798): Unsupported mime video/mp4v-esdp
,I/ActivityManager( 1036): Killing 6245:com.android.contacts/u0a19 (adj 15): empty #17
I/VideoCapabilities( 6798): Unsupported profile 4 for video/mp4v-es
W/AudioCapabilities( 6798): Unsupported mime audio/eac3
W/AudioCapabilities( 6798): Unsupported mime audio/ac3
W/AudioCapabilities( 6798): Unsupported mime audio/g726
,W/AudioCapabilities( 6798): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6798): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6798): Unsupported mime audio/adpcm
W/VideoCapabilities( 6798): Unsupported mime video/theora
W/VideoCapabilities( 6798): Unsupported mime video/mjpg
E/UEI.SmartControl( 6369): file observer is disposed!
,I/AppUp4:AppBoxCP( 6835): onCreate
W/AppUp4:DB( 6835):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6835):  setFingerPrint start
I/AppUp4:DB( 6835):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,I/AppUp4:DB( 6835):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
I/AppUp4:DB( 6835):  SDK version = 21
I/AppUp4:DB( 6835):  beforefinger == newfinger no write in DB
W/libprocessgroup( 1036): failed to open /acct/uid_10019/pid_6245/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 6835): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6835): onReceive
,E/GBMv2   (  349): DFP En is all cleared set to be enabled
E/GBMv2   (  349): Set value is all cleared set the max
I/GBMv2   (  349): DFP Enabled. Ignore VFP set
,D/LgDataFeature( 6835): LgDataFeature() Constructor: none
D/LgDataFeature( 6835): LgDataFeature() Constructor Done, null
D/AppUp4:CustFacade( 6835): Context : android.app.ReceiverRestrictedContext@346da3b8
D/AppUp4:CustFacade( 6835): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6835): isPhone : true
,D/AppUp4:CustModeStarterReceiver( 6835): begin check event
I/AppUp4:CustModeStarterReceiver( 6835): Event For Nothing, skip.
I/ActivityManager( 1036): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6858 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager( 1036): Killing 5509:com.android.defcontainer/u0a4 (adj 15): empty #17
W/libprocessgroup( 1036): failed to open /acct/uid_10004/pid_5509/cgroup.procs: No such file or directory
,I/jxcore-log( 6691): getBuffer is called!!!!
I/jxcore-log( 6691): 
,W/ResourcesManager( 6858): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6858): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6858): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6858): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6858): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 6858): BUILD Country: EU
I/SystemConfig( 6858): BUILD Operator: OPEN
,I/ActivityManager( 1036): Killing 6282:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_10023/pid_6282/cgroup.procs: No such file or directory
,I/SystemConfig( 6858): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6858): existFile = false
,I/SystemConfig( 6858): canReadFile = false
I/SystemConfig( 6858): systemFeature RCS result false
D/SystemConfig( 6858): refreshRcsSupport() :false
,I/ActivityManager( 1036): Killing 4968:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_4968/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 4663): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/LockScreenSettings( 6401): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6401): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6401): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6401): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6401): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
D/LockScreenSettings( 6401): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,D/PackageBroadcastService( 2399): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/GCM     ( 2127): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/PackageBroadcastService( 2399): Null package name or gms related package.  Ignoreing.
D/AuthorizationBluetoothService( 2127): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2399): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/Icing   ( 2399): updateResources: need to parse f{com.google.android.gms}
,E/MDM     ( 1836): [82] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
V/QRemote ( 6612): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:9016
,D/LocationInitializer( 2399): Restart initialization of location
D/GCM     ( 2127): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 2127): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2399): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager( 1036): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=6892 uid=10054 gids={50054, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/MDM     ( 1836): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 2399): Restart initialization of location
,I/ReaderUtils( 6892): PortraitW 1440 LandscapeW 2392 SmallestSize 1340 LargestSize 2392 textZoom 4.4999995 isTablet false Memory 256
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/QRemote ( 6612): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
,E/QRemote ( 6612): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6612): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1448020249062]
V/QRemote ( 6612): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.syncadapters.contacts, service: cp
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> cp without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/QRemote ( 6612): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
E/QRemote ( 6612): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6612): [RemoteAppWidgetManager.java:36:startLoading()] oooooo 140518:startLoading:sWidgetHandler has [3] at [1448020249108]. skip
V/QRemote ( 6612): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 6612): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
V/SIM_STK ( 1036): Menu title from STK is T-Mobile
,D/QRemote ( 6612): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
V/QRemote ( 6612): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
E/QRemote ( 6612): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
I/UpdateIcingCorporaServi( 4663): UpdateCorporaTask done [took 588 ms] updated apps [took 588 ms] 
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6612): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
,D/QRemote ( 6612): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
W/GAV2    ( 6892): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/UEI.SmartControl( 6369): Internal timer expired: 3
D/UEI.SmartControl( 6369): unbind internal service
,D/serial_port( 6369): close(fd = 24)
,I/UEI.SmartControl( 6369): Serial port is closed.
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
W/GLSActivity( 2127): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2127): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2127): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2127): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839081,-1|com.android.systemui|2130839081|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/ContactsSyncAdapter( 2127): innerSync failed
D/ContactsSyncAdapter( 2127): com.google.wireless.gdata2.client.AuthenticationException: unable to get auth token android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2127): 	at com.google.android.syncadapters.contacts.AuthInfo.getAuthToken(AuthInfo.java:45)
D/ContactsSyncAdapter( 2127): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.innerPerformSync(ContactsSyncAdapter.java:263)
D/ContactsSyncAdapter( 2127): 	at com.google.android.syncadapters.contacts.ContactsSyncAdapter.onPerformLoggedSync(ContactsSyncAdapter.java:168)
D/ContactsSyncAdapter( 2127): 	at com.google.android.common.LoggingThreadedSyncAdapter.onPerformSync(LoggingThreadedSyncAdapter.java:33)
D/ContactsSyncAdapter( 2127): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
D/ContactsSyncAdapter( 2127): Caused by: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
D/ContactsSyncAdapter( 2127): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
D/ContactsSyncAdapter( 2127): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
D/ContactsSyncAdapter( 2127): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
D/ContactsSyncAdapter( 2127): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
D/ContactsSyncAdapter( 2127): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
I/art     ( 2127): Explicit concurrent mark sweep GC freed 16160(919KB) AllocSpace objects, 1(144KB) LOS objects, 50% free, 30MB/62MB, paused 3.539ms total 81.346ms
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{270c3cbf V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,D/SyncManager( 1036): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 75516, reason: 10019, SyncResult: stats [ numAuthExceptions: 1]
I/BooksApp( 6892): Created application version: 3.2.35 (30235)
D/SyncManager( 1036): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts, LOCAL, currentRunTime 143653, reason: 10019
,I/BooksSync( 6892): Starting books sync
,D/BooksSync( 6892): started syncMyEbooks
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,W/GLSActivity( 2127): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2127): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2127): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2127): 	at android.os.Binder.execTransact(Binder.java:446)
D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839081,-1|com.android.systemui|2130839081|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/BooksAccountManager( 6892): Authentication error
E/BooksAccountManager( 6892): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6892): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6892): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6892): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6892): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6892): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6892): null auth token
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  310): res_queryN name = www.googleapis.com, class = 1, type = 1
D/libc-netbsd(  310): res_queryN name = www.googleapis.com succeed
,D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{270c3cbf V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
,I/ConfigService( 2127): onDestroy
,W/ApiaryClient( 6892): Error response from books API: {
W/ApiaryClient( 6892):  "error": {
W/ApiaryClient( 6892):   "errors": [
W/ApiaryClient( 6892):    {
W/ApiaryClient( 6892):     "domain": "global",
W/ApiaryClient( 6892):     "reason": "required",
W/ApiaryClient( 6892):     "message": "Login Required",
W/ApiaryClient( 6892):     "locationType": "header",
W/ApiaryClient( 6892):     "location": "Authorization"
W/ApiaryClient( 6892):    }
W/ApiaryClient( 6892):   ],
W/ApiaryClient( 6892):   "code": 401,
W/ApiaryClient( 6892):   "message": "Login Required"
W/ApiaryClient( 6892):  }
W/ApiaryClient( 6892): }
,W/ApiaryClient( 6892): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6892): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4395334527093499953&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6892): Headers:
W/ApiaryClient( 6892): accept-encoding: [gzip]
W/ApiaryClient( 6892): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6892): gdata-version: 2
V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1036): Explicit concurrent mark sweep GC freed 16410(724KB) AllocSpace objects, 3(304KB) LOS objects, 33% free, 44MB/66MB, paused 3.296ms total 171.814ms
,I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
,V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/LgeQuickCoverNLService( 1418): onNotificationPosted
,D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
,D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839081,-1|com.android.systemui|2130839081|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
W/GLSActivity( 2127): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2127): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2127): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2127): 	at android.os.Binder.execTransact(Binder.java:446)
E/BooksAccountManager( 6892): Authentication error
E/BooksAccountManager( 6892): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6892): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6892): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6892): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6892): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6892): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6892): null auth token
,E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{270c3cbf V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
W/ApiaryClient( 6892): Error response from books API: {
W/ApiaryClient( 6892):  "error": {
W/ApiaryClient( 6892):   "errors": [
W/ApiaryClient( 6892):    {
W/ApiaryClient( 6892):     "domain": "global",
W/ApiaryClient( 6892):     "reason": "required",
W/ApiaryClient( 6892):     "message": "Login Required",
W/ApiaryClient( 6892):     "locationType": "header",
W/ApiaryClient( 6892):     "location": "Authorization"
W/ApiaryClient( 6892):    }
W/ApiaryClient( 6892):   ],
W/ApiaryClient( 6892):   "code": 401,
W/ApiaryClient( 6892):   "message": "Login Required"
W/ApiaryClient( 6892):  }
W/ApiaryClient( 6892): }
,W/ApiaryClient( 6892): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 6892): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4395334527093499953&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6892): Headers:
W/ApiaryClient( 6892): accept-encoding: [gzip]
W/ApiaryClient( 6892): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6892): gdata-version: 2
D/WearableClient( 6656): WearableClientImpl.onPostInitHandler: done
D/WearableClient( 6656): WearableClientImpl.onPostInitHandler: done
I/MusicLeanback( 6656): Conditions not met for autocaching.
I/MusicLeanback( 6656): Stop autocaching.
,E/GmsUtils( 6656): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
I/GAV2    ( 6749): Thread[GAThread,5,main]: No campaign data found.
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2127): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 2127): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2127): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2127): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 2127): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/BluetoothManagerService( 1036): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService( 1036): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1446a308 mBinding = false
D/LocationManagerService( 1036): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1036): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,D/BluetoothManagerService( 1036): Message: 2
D/Ulp_jni ( 1036): JNI:system_update. Event-4
D/BluetoothManagerService( 1036): Sending off request.
D/LGBluetoothServiceAdapter( 3855): [BTUI] Precleanup
D/BluetoothAdapterState( 3855): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3855): Setting state to 13
I/BluetoothAdapterState( 3855): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 3855): onBluetoothDisable()
I/BluetoothAdapterState( 3855): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothAdapterProperties( 3855): Scan Mode:20
,D/BluetoothAdapterState( 3855): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
V/BluetoothMapMasInstance( 3855): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3855): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3855): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 3855): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 3855): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 3855): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3855): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3855): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
V/BluetoothPbapService( 3855): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/BtOppRfcommListener( 3855): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothFtpService:RfcommSocketAcceptThread( 3855): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothSapService( 3855): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/btif_config_util( 3855): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/bt-l2cap( 3855): L2CAP - L2CA_Deregister() called for PSM: 0x000f
W/bt-btif ( 3855): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
,W/bt-l2cap( 3855): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3855): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3855): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3855): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3855): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3855): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3855): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3855): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3855): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3855): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3855): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 3855): bta_gattc_deregister Deregister Failedm unknown client cif
,D/BluetoothManagerService( 1036): Message: 60
D/BluetoothManagerService( 1036): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1036): Bluetooth State Change Intent: 12 -> 13
D/WifiService( 1036): New client listening to asynchronous messages
,I/ActivityManager( 1036): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6981 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/WifiServiceImplEx( 1036): setWifiEnabled: false pid=6691, uid=10318, package= com.example.hello, App Lable : HelloWorld
D/WifiService( 1036): setWifiEnabled: false pid=6691, uid=10318
E/WifiService( 1036): Invoking mWifiStateMachine.setWifiEnabled
D/LGBluetoothAPIService( 1967): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/BluetoothMapService( 3855): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 3855): STATE_TURNING_OFF
V/BluetoothMapService( 3855): Handler(): got msg=4
D/BluetoothMapService( 3855): MAP Service closeService in
D/BluetoothMapMasInstance( 3855): MAP Service shutdown
D/LGBluetoothMapAdapter( 3855): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3855): MAP Service closeService out
I/[SystemUI]BluetoothHandler( 1465): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
V/BtOppService( 3855): Receiver DISABLED_ACTION 
I/BtOppRfcommListener( 3855): stopping Accept Thread
V/BtOppRfcommListener( 3855): close mBtServerSocket
V/BtOppRfcommListener( 3855): waiting for thread to terminate
I/BtOppRfcommListener( 3855): BluetoothSocket listen thread finished
V/BtOppRfcommListener( 3855): done waiting for thread to terminate
D/LocationManagerService( 1036): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1036): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1036): JNI:system_update. Event-4
,E/WifiStateMachine( 1036):  ConnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1036):  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
I/jxcore-log( 6691): ****TEST TOOK:  5164  ms ****
I/jxcore-log( 6691): 
E/WifiStateMachine( 1036):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
I/jxcore-log( 6691): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6691): 
E/WifiStateMachine( 1036):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1036): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1036): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1036): doBoolean: SET_NETWORK 0 bssid any
D/WifiNative-wlan0( 1036): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1036): doBoolean: SAVE_CONFIG
D/WifiNative-wlan0( 1036): SAVE_CONFIG: returned true
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2688): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/LGWifiP2pService( 1036): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
D/WifiNative-wlan0( 1036): SET ps 1: returned true
D/CommandListener(  310): Clearing all IP addresses on wlan0
,D/DhcpStateMachine( 1036): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
V/NativeCrypto( 2127): Read error: ssl=0xaf4d6a00: I/O error during system call, Connection timed out
V/NativeCrypto( 2127): SSL shutdown failed: ssl=0xaf4d6a00: I/O error during system call, Broken pipe
,I/ActivityManager( 1036): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7000 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
V/BtOppService( 3855): onDestroy
D/LGBluetoothOppAdapter( 3855): [BTUI] LGBluetoothOppAdapter cleanup
,D/ConnectivityService( 1036): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Checking http://clients3.google.com/generate_204 on "NG700"
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1036): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
E/WifiStateMachine( 1036):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/WifiNetworkAgent( 1036): NetworkAgent: NetworkAgent channel lost
,D/LGWifiP2pService( 1036): InactiveState{ when=-5ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): P2pEnabledState{ when=-5ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiMonitor( 1036): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@b36f765
D/LGWifiP2pService( 1036): P2pDisablingState
,D/LGWifiP2pService( 1036): P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): p2p socket connection lost
D/LGWifiP2pService( 1036): P2pDisabledState
D/WifiHS20( 1036): hidePasspointNotification off =false
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/WfdStateTracker( 1967): handleWifiStateChangedEvent: 0
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WifiHS20( 1036): hidePasspointNotification off =false
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine( 1036):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/LGWifiP2pService( 1036): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1036): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1036): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2688): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1036): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1036): doBoolean: SET ps 1
D/WifiNative-wlan0( 1036): SET ps 1: returned true
D/DSQN    ( 1036): Dns fail occured do internet check.
D/WifiScanningService( 1036): SCAN_AVAILABLE : 1
D/WifiScanningService( 1036): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/DSQN    ( 1036): EVENT_INTERNET_CHECK_REQUEST received
,D/DSQN    ( 1036): try Internet connection check
D/RttService( 1036): SCAN_AVAILABLE : 1
D/RttService( 1036): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
V/WfdStateTracker( 1967): WfdStateTracker handleDirectStateChangedEvent: 0
D/WfdsService( 1967): WifiP2pState is changed : false
D/WfdsService( 1967): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1967): Set the WFDS Monitor: false
D/WfdsMonitor( 1967): WFDS Monitor is stopped
D/CtrlSupplicant( 1967): Received on exit socket, terminate
D/WfdsService( 1967): STATE : WfdsDisabledState - enter
E/CtrlSupplicant( 1967): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1967): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1967): WfdsMonitorThread is received the interrupt - closing
W/WfdsSession:Controller( 1967): DefaultState - msg [9441355] is not handled
W/WfdsService( 1967): DefaultState - msg [9445378] is not handled
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
V/NotificationService( 1036): enqueueNotificationInternal: pkg=com.google.android.gms id=1 notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
V/NotificationService( 1036): pkg=com.google.android.gms canInterrupt=false intercept=true
I/NotificationServiceEx( 1036): LED remove() : mLights=0|com.google.android.gms|1|null|10005
D/NotificationServiceEx( 1036): updateLightListLocked :r=0|com.google.android.gms|1|null|10005, action=2
D/NotificationServiceEx( 1036): notification=Notification(pri=0 contentView=null vibrate=null sound=null defaults=0x0 flags=0x10 color=0x00000000 vis=PRIVATE)
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/LgeQuickCoverNLService( 1418): onNotificationPosted
D/SmartCoverUpdateMonitor( 1418): received broadcast com.lge.intent.action.NLDataPosted
E/SmartCoverUpdateMonitor( 1418): MSG_NOTIFICATION_POSTED
D/SmartCoverUpdateMonitor( 1418): handleNotificationPosted(true)
,D/QuickCircle( 1418): onNotificationPosted() : isPosted true
D/LgeQuickCoverNotificationData( 1418): post() sbn.getKey(): 0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): post() sbn.getGroupKey(): 0|com.google.android.gms|1|null|10005
W/GLSActivity( 2127): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 2127): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 2127): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 2127): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 2127): 	at android.os.Binder.execTransact(Binder.java:446)
D/LgeQuickCoverNotificationData( 1418): post do just update job
D/LgeQuickCoverNotificationData( 1418): showAll3
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 1,0|com.google.android.gms|1|null|10005
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 262082,0|com.lge.eula|262082|null|1000
D/LgeQuickCoverNotificationData( 1418): showAll() ID : 2130839081,-1|com.android.systemui|2130839081|null|10020
E/LgeQuickCoverOverlayWindow( 1418): showNotificationWithSetupData: display=false
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  0
,D/CommandListener(  310): Clearing all IP addresses on wlan0
D/ConnectivityService( 1036): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1036): disableDataServiceNotify
D/DSQN    ( 1036): stop dsqn bin
D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
D/DSQN    ( 1036): ThreadTCPConnectionCheck DNS fail internet is not possible
D/DSQN    ( 1036): ThreadInternetCheck internet check NOK 
D/DSQN    ( 1036): InternetcheckProgress is not set don't send DS quality intent
D/DSQN    ( 1036): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
I/StatusBar.NetworkController( 1465): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1465): mWifiConnected = false, mWifiLevel = 0
,D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/ConnectivityService( 1036): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1036): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1036): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1036): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1465): CM callback handler got msg 524292
D/WifiHS20( 1036): hidePasspointNotification off =false
W/Settings( 1036): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1036): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1036): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiNative-p2p0( 1036): doBoolean: TERMINATE
D/CSLegacyTypeTracker( 1036): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,fe80::c69a:2ff:fe7b:60ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/WifiNative-p2p0( 1036): TERMINATE: returned true
D/CSLegacyTypeTracker( 1036): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
E/WifiStateMachine( 1036): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1036): useWiFiOffloading() : false
E/WifiStateMachine( 1036): CONFIG_LGE_WLAN_PATH : true
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/WfdStateTracker( 1967): WfdStateTracker handleDirectStateChangedEvent: 6
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  1
,I/WifiServerServiceExt( 1036): WIFI_STATE_CHANGED_ACTION [0]
D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1036): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1036): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
D/ConnectivityService( 1036): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1036): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1036):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt( 1036): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1036): setSupplicantStateDISCONNECTED
V/NetworkPolicy( 1036): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy( 1036): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1036): Sending msg: 4 arg1:0 arg2:1
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/LocSvc_java( 1036): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java( 1036): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1036): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1036): ignore wifi update if we are not in OPENING or CLOSING
D/NetworkManagementService( 1036): Removing idletimer
W/Settings( 1036): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1036): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
E/ConnectivityService( 1036): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyNetworkFactory-1( 1871): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1871):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/LgeQuickCoverOverlayWindow( 1418): [native noti] inex =  2
D/LgeQuickCoverNotificationData( 1418): isNotificationForCurrentUser : true
E/LgeQuickCoverOverlayWindow( 1418): updateNotificationData: count=3
D/QuickStatusbarLayout( 1418): Notification difference=198
D/QuickStatusbarLayout( 1418): child = android.widget.LinearLayout{270c3cbf V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
E/BooksAccountManager( 6892): Authentication error
E/BooksAccountManager( 6892): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 6892): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
E/BooksAccountManager( 6892): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/BooksAccountManager( 6892): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
E/BooksAccountManager( 6892): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/BooksAccountManager( 6892): 	at android.os.Binder.execTransact(Binder.java:446)
E/HttpHelper( 6892): null auth token
,D/libc-netbsd(  310): default dns: query_ipv6=0, query_ipv4=0
W/ResourcesManager( 7000): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7000): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
D/DSQN    ( 1036): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/ResourcesManager( 7000): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7000): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7000): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 7000): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,W/ApiaryClient( 6892): errCount = 3: com.google.android.apps.books.net.HttpHelper$OfflineIoException: java.net.UnknownHostException: URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3Djd5AIC8R9Qo&nonce=4395334527093499953&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 6892): Headers:
W/ApiaryClient( 6892): accept-encoding: [gzip]
W/ApiaryClient( 6892): user-agent: [BooksAndroid Dalvik/2.1.0 (Linux; U; Android 5.0; LG-D855 Build/LRX21R.A1421650137) com.google.android.apps.books/3.2.35 (30235) Safari/]
W/ApiaryClient( 6892): gdata-version: 2
,D/TelephonyIcons( 1465): null signal icon name: drawable/stat_sys_signal_null
E/BooksSync( 6892): Soft error: 
E/BooksSync( 6892): Sync error
I/BooksSync( 6892): Finished books sync
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/SyncManager( 1036): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 78143, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,I/ActivityManager( 1036): Killing 6324:com.google.android.apps.docs/u0a61 (adj 15): empty #17
D/DhcpStateMachine( 1036): StoppedState
,D/DhcpStateMachine( 1036): StoppedState{ when=-150ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/AndroidRuntime( 7023): 
D/AndroidRuntime( 7023): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7023): CheckJNI is OFF
I/wpa_supplicant( 2688): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 2688): monitor socket send errors count : 1
I/wpa_supplicant( 2688): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1967-2\x00 that cannot receive messages
D/WifiMonitor( 1036): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1036): Dropping event because (p2p0) is stopped
W/libprocessgroup( 1036): failed to open /acct/uid_10061/pid_6324/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1036):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_ON_QUIT 0 0
I/wpa_supplicant( 2688): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1036): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1036): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
W/wpa_supplicant( 2688): USIM:  scard_deinit function
D/Tethering( 1036): InitialState.processMessage what=4
,D/Tethering( 1036): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/WifiStateMachine( 1036):  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=84013
E/WifiStateMachine( 1036):  DefaultState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=84015
D/TelephonyIcons( 1465): null signal icon name: drawable/stat_sys_signal_null
E/WifiStateMachine( 1036):  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
E/WifiStateMachine( 1036):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
E/WifiStateMachine( 1036):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=84018  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/WifiStateMachine( 1036):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=84019  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
E/ActivityThread( 6981): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6981): No ProfileInfo entries
I/LG Account v2.2( 6981): isEnabled: false
I/Feature ( 6981): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6981): [Lifetracker]Country: EU
I/Feature ( 6981): [Lifetracker]Operator: OPEN
I/Feature ( 6981): [Lifetracker]Ranking support: false
I/Feature ( 6981): [Lifetracker]Comfort support: false
,I/Feature ( 6981): [Lifetracker]Accessory: true
I/Feature ( 6981): [Lifetracker]Health device: true
I/Feature ( 6981): [Lifetracker]Extra Pedometer: false
I/Feature ( 6981): [Lifetracker]Blood glucose device: false
I/Feature ( 6981): [Lifetracker]Device Number: 3
I/ActivityManager( 1036): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=7043 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1036): Killing 6455:com.lge.eula/1000 (adj 15): empty #17
,I/art     (  353): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 4.600ms total 23.937ms
,I/art     (  353): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 344us total 15.621ms
,W/ContextImpl( 7000): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
I/art     (  353): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 288us total 13.448ms
,I/wpa_supplicant( 2688): wlan0: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1036): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
,E/WifiMonitor( 1036): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
D/WifiMonitor( 1036): Disconnecting from the supplicant, no more events
E/WifiStateMachine( 1036):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_6455/cgroup.procs: No such file or directory
,D/AndroidRuntime( 7023): Calling main entry com.android.commands.pm.Pm
V/BluetoothPbapReceiver( 3855): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3855): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3855): ***********state = 13
V/BluetoothPbapReceiver( 3855): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 3855): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 3855): state: 13
V/BluetoothPbapService( 3855): Pbap Service closeService in
V/BluetoothPbapService( 3855): successfully stopped pbap service
V/BluetoothPbapService( 3855): Pbap Service closeService out
V/BluetoothPbapService( 3855): Pbap Service onDestroy
V/BluetoothPbapService( 3855): Pbap Service closeService in
V/BluetoothPbapService( 3855): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 3855): [BTUI] cleanup
,I/ActivityManager( 1036): Force stopping com.example.hello appid=10318 user=-1: uninstall pkg
D/BluetoothManagerService( 1036): Message: 20
D/BluetoothManagerService( 1036): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2f1b6752:true
I/ActivityManager( 1036): Killing 6691:com.example.hello/u0a318 (adj 0): stop com.example.hello
I/WindowState( 1036): WIN DEATH: Window{19fb712f u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService( 1036): Client connection lost with reason: 4
W/PackageSettings( 1036): Skipping PackageSetting{1893d55c com.test.thalitest/10311} due to missing metadata
D/InputDispatcher( 1036): Window went away: Window{19fb712f u0 com.example.hello/com.example.hello.MainActivity}
,W/ResourcesManager( 7043): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/PluginManager( 7043): init()
,I/ActivityManager( 1036):   Force finishing activity ActivityRecord{20c9f677 u0 com.example.hello/.MainActivity t2}
,E/GBMv2   (  349): DFP En is all cleared set to be enabled
,W/ActivityManager( 1036): Spurious death for ProcessRecord{3764a69e 6691:com.example.hello/u0a318}, curProc for 6691: null
D/WifiOffDelayIfNotUsed( 1036): stopMonitoring
E/WifiStateMachine( 1036): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1036): useWiFiOffloading() : false
E/WifiStateMachine( 1036): CONFIG_LGE_WLAN_PATH : true
D/SplitWindowPolicy( 1967): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1967): topRunningActivity=ActivityInfo{2bd7e787 co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
I/ActivityManager( 1036): Force stopping com.example.hello appid=10318 user=0: pkg removed
I/ActivityManager( 1036):   Force finishing activity ActivityRecord{20c9f677 u0 com.example.hello/.MainActivity t2 f}
W/ActivityManager( 1036): Duplicate finish request for ActivityRecord{20c9f677 u0 com.example.hello/.MainActivity t2 f}
D/SplitWindowPolicy( 1967): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
,D/SplitWindowPolicy( 1967): topRunningActivity=ActivityInfo{ce2e6b4 co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
D/BluetoothManagerService( 1036): Message: 30
,D/SplitWindowManager( 1036): removeStackAndNeedHomeResume ActivityStack{45b794c stackId=1, 0 tasks}
,D/WfdsService( 1967): Supplicant Connection state is changed : false
D/WfdsService( 1967): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1967): Set the WFDS Monitor: false
D/WfdsMonitor( 1967): WFDS Monitor is stopped
V/WfdStateTracker( 1967): WfdStateTracker handleDirectStateChangedEvent: 0
D/StatusBar.NetworkController( 1465): refreshViews: Data not connected!! Set no data type icon / Roaming
E/LGBluetoothAvrcpQcomAdapter( 3855): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3855): [BTUI] [+] updateMediaPlayerInfo
D/LIA_Service_RemotePackageHandler( 2031): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.example.hello
I/[LGHome]EVENT( 2082): [Launcher.java:5338:onStart()]onStart
D/LIA_MrGDBLogger_PackageInfoDetector( 3770): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.example.hello
W/Settings( 1836): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[LGHome]EVENT( 2082): [Launcher.java:903:onResume()]onResume
D/bt_hci_bdroid( 3855): cleanup
I/bt_lpm  ( 3855): LPM is already off!!!
I/bt_userial_mct( 3855): exiting userial_read_thread
D/bt_userial_mct( 3855): Leaving userial_evt_read_thread()
W/bt-btif ( 3855): ag scb idx 1 not allocated
E/bt-btif ( 3855): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 3855): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3855): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3855): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3855): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3855): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3855): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3855): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3855): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3855): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3855): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3855): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3855): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3855): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3855): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3855): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3855): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3855): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3855): L2CAP - PSM: 0x001b not found for deregistration
E/bt-btif ( 3855): bta_gattc_deregister Deregister Failedm unknown client cif
D/bt_userial_mct( 3855): userial_close_reader Joined userial reader thread: 0
I/bt_vendor( 3855): hw_epilog_process
D/bt_hci_bdroid( 3855): cleanup Finalizing cleanup
D/bt_userial_mct( 3855): userial_close
E/bt_userial_mct( 3855): pthread_join() FAILED result:3
I/bt_vendor( 3855): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
I/InputReader( 1036): Reconfiguring input devices.  changes=0x00000010
D/KeyguardModel( 1465): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/Settings( 6798): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/SIM_STK ( 1036): Menu title from STK is T-Mobile
,I/art     ( 4663): Explicit concurrent mark sweep GC freed 7718(449KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 643us total 88.188ms
W/GeofencerStateMachine( 1836): Ignoring removeGeofence because network location is disabled.
I/WifiServerServiceExt( 1036): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt( 1036): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1036): batteryPsActivateMsgHandler : this is not treated
,W/System.err( 4616): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 4616): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4616): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4616): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
W/System.err( 4616): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4616): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4616): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4616): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4616): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4616): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4616): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4616): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/[LGHome]EVENT( 2082): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/BluetoothManagerService( 1036): Message: 30
I/[SystemUI]QSlideListController( 1465): onReceive = android.intent.action.PACKAGE_REMOVED
,I/[LGHome]GBoardWebView( 2082): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1931): notifyUserLog: 1000003
I/[LGHome]LGActivityUtil( 2082): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/LIA_Informant_ActionManagerMessageHandler( 3770): handleMessage: what(1000) actionID(0x1000003)
I/[LGHome]EVENT( 2082): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2082): [Launcher.java:1114:onPause()]onPause
D/LocalBluetoothProfileManager( 7000): Adding local MAP profile
D/BluetoothMap( 7000): Create BluetoothMap proxy object
,D/ActionManagerService( 1931): notifyUserLog: 1000004
,I/[LGHome]GBoardWebView( 2082): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/LIA_Informant_ActionManagerMessageHandler( 3770): handleMessage: what(1000) actionID(0x1000004)
D/BluetoothManagerService( 1036): Message: 30
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1465): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1465): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
V/BoardContentProvider( 3770): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
D/KeyguardModel( 1465): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1465): createShortcutInfo...
D/BluetoothManagerService( 1036): Message: 30
I/GBoardWebViewUtils( 2082): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2082): , create_time: 1430558575574
I/GBoardWebViewUtils( 2082): , expire_time: 0
I/GBoardWebViewUtils( 2082): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2082): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2082): , display: false
I/GBoardWebViewUtils( 2082): , animation: false }
I/GBoardWebViewUtils( 2082): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2082): , create_time: 1430558575600
I/GBoardWebViewUtils( 2082): , expire_time: 0
I/GBoardWebViewUtils( 2082): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2082): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2082): , display: false
I/GBoardWebViewUtils( 2082): , animation: false }
I/GBoardWebViewUtils( 2082): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1447937693376
I/GBoardWebViewUtils( 2082): , create_time: 1447937694406
I/GBoardWebViewUtils( 2082): , expire_time: 0
I/GBoardWebViewUtils( 2082): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1447937693376&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2082): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2082): , display: false
I/GBoardWebViewUtils( 2082): , animation: false }
D/WallpaperManager( 2082): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,D/LocalBluetoothProfileManager( 7000): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 7000):  get() - isFeatureLoaded : false
D/KeyguardModel( 1465): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1465): createShortcutInfo...
I/SystemUI[Framework]( 1036): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1036): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1036): setLGSystemUiVisibility(0x0)
,D/StatusBarManagerServiceEx( 1036): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2dc3de81,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1036): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourcesManager( 1465): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1465): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1465): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1465): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
D/SplitUIManager( 1895): split_name #11 / not available #0
D/SplitUIService( 1895): removed split : 
W/ResourceType( 1465): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1465): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1465): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1465): createShortcutInfo...
D/LGBluetoothUserBindClient( 7000): [BTUI] initUserBindClient
,W/ContextImpl( 7000): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
V/SIM_STK ( 1036): Menu title from STK is T-Mobile
V/SIM_STK ( 1036): Menu title from STK is T-Mobile
W/ResourcesManager( 1465): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1465): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]GBoardWebView( 2082): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
W/ResourceType( 1465): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1465): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1465): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1465): createShortcutInfo...
,D/SplitUIManager( 1895): split_name #11 / not available #0
I/SplitUIService( 1895): split app #11
W/ResourcesManager( 1465): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1465): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 1465): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1465): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
D/DockEventReceiver( 7000): finishStartingService: stopping service
W/ResourceType( 1465): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1465): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1465): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1465): createShortcutInfo...
D/KeyguardModel( 1465): handleShortcutListChanged...
,D/KeyguardModel( 1465): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1465): createShortcutInfo...
V/SIM_STK ( 1036): Menu title from STK is T-Mobile
D/KeyguardModel( 1465): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1465): createShortcutInfo...
W/ResourceType( 1465): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1465): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1465): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1465): createShortcutInfo...
W/ResourceType( 1465): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1465): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/bt_hci_bdroid( 3855): set_power 0
I/bt_vendor( 3855): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 3855): bluetooth satus is on
I/bt_vendor( 3855): bt-vendor : resetting BT status
I/bt_vendor( 3855): Starting hciattach daemon
I/bt_vendor( 3855): try to set false
I/bt_vendor( 3855): Starting hciattach daemon
I/bt_vendor( 3855): try to set false
D/KeyguardModel( 1465): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1465): createShortcutInfo...
I/bt_vendor( 3855): cleanup
,I/GKI_LINUX( 3855): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3855): GKI_exit_task 0 done
I/GKI_LINUX( 3855): GKI_shutdown(): task [BTU] terminated
W/ResourceType( 1465): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1465): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/BluetoothAdapterState( 3855): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/KeyguardModel( 1465): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1465): createShortcutInfo...
D/BluetoothAdapterState( 3855): Stopping profile services that were post enabled
W/ActivityManager( 1036): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
D/KeyguardModel( 1465): handleShortcutListChanged...
D/LGBluetoothAvrcpQcomAdapter( 3855): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3855): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3855): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3855): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3855): [BTUI]          packageName: com.lge.music
,D/LGBluetoothAvrcpQcomAdapter( 3855): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3855): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3855): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3855): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3855): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3855): [BTUI] [-] updateMediaPlayerInfo
D/BluetoothInputDevice( 7000): Proxy object connected
D/HeadsetService( 3855): Received stop request...Stopping profile...
D/HidProfile( 7000): Bluetooth service connected
I/LGBluetoothHfpAdapter( 3855): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 3855): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3855): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c354364
D/HeadsetStateMachine( 3855): Exit Disconnected: -1
D/BluetoothPan( 7000): BluetoothPAN Proxy object connected
D/PanProfile( 7000): Bluetooth service connected
D/BluetoothHeadset( 1871): Proxy object disconnected
D/BluetoothHeadset( 1871): Proxy object disconnected
D/BluetoothHeadset( 1871): Proxy object disconnected
D/A2dpService( 3855): Received stop request...Stopping profile...
D/A2dpStateMachine( 3855): Exit Disconnected: -1
D/LGBluetoothAvrcpQcomAdapter( 3855): [BTUI] cleanup
D/LGBluetoothA2dpAdapter( 3855): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 3855): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3855): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c354364
D/BluetoothMap( 7000): Proxy object connected
D/HidService( 3855): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3855): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c354364
D/HealthService( 3855): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3855): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c354364
D/PanService( 3855): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3855): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c354364
D/BtGatt.DebugUtils( 3855): handleDebugAction() action=null
D/BtGatt.GattService( 3855): Received stop request...Stopping profile...
D/BtGatt.GattService( 3855): stop()
D/BtGatt.AdvertiseManager( 3855): advertise clients cleared
,D/BluetoothAdapterService( 3855): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c354364
W/ExternalStrings( 7043): load override strings
W/ExternalStrings( 7043): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 7043): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 7043): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 7043): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 7043): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 7043): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 7043): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 7043): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 7043): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 7043): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 7043): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 7043): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 7043): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 7043): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 7043): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 7043): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 7043): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 7043): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/BluetoothMapService( 3855): Received stop request...Stopping profile...
D/BluetoothMapService( 3855): stop()
D/BluetoothMapEmailAppObserver( 3855): deinitObservers()
D/BluetoothMapEmailAppObserver( 3855): removeReceiver()
D/BluetoothAdapterService( 3855): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1c354364
D/StatusProvider( 7043): onCreate
D/HeadsetStateMachine( 3855): Unbinding service...
D/HeadsetPhoneState( 3855): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3855): [BTUI] listenForMultiSimPhoneState : start = false
,D/HeadsetPhoneState( 3855): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3855): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 3855): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3855): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 3855): [BTUI] LGBluetoothHfpAdapter cleanup
I/BluetoothA2dpServiceJni( 3855): cleanupNative
I/GKI_LINUX( 3855): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3855): GKI_exit_task 2 done
I/GKI_LINUX( 3855): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3855): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3855): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3855): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3855): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 3855): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3855): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3855): Cleaning up Bluetooth PAN callback object
D/MapProfile( 7000): Bluetooth service connected
D/BluetoothMap( 7000): getConnectedDevices()
I/[LGHome]EVENT( 2082): [Launcher.java:5349:onStop()]onStop
V/BluetoothMapService( 3855): Handler(): got msg=4
D/BluetoothMapService( 3855): MAP Service closeService in
D/LGBluetoothMapAdapter( 3855): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3855): MAP Service closeService out
D/BluetoothAdapterState( 3855): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3855): Setting state to 10
I/BluetoothAdapterState( 3855): Bluetooth adapter state changed: 13-> 10
D/BluetoothMapService( 3855): cleanup()
D/BluetoothMapService( 3855): MAP Service closeService in
D/LGBluetoothMapAdapter( 3855): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3855): MAP Service closeService out
D/BluetoothManagerService( 1036): Message: 60
D/BluetoothManagerService( 1036): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1036): Broadcasting onBluetoothStateChange(false) to 9 receivers.
I/BluetoothAdapterState( 3855): Entering OffState
D/BluetoothMap( 7000): Bluetooth is Not enabled
D/BluetoothHeadset( 1871): onBluetoothStateChange: up=false
,D/LGBluetoothUserBindClient( 7000): [BTUI] onServiceConnected
D/BluetoothA2dp( 1036): onBluetoothStateChange: up=false
D/BluetoothPan( 7000): onBluetoothStateChange on: false
D/BluetoothHeadset( 1871): onBluetoothStateChange: up=false
D/LGBluetoothAuthorization( 7000): [BTUI] cancel All Notification
D/BluetoothHeadset( 1871): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1036): onBluetoothStateChange: up=false
D/BluetoothMap( 7000): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 7000): onBluetoothStateChange: up=false
D/BluetoothPbap( 7000): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1036): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1036): Broadcasting onBluetoothServiceDown() to 7 receivers.
D/BluetoothManagerService( 1036): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1036): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1036): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1446a308 mBinding = false
D/BluetoothManagerService( 1036): Sending unbind request.
D/BluetoothManagerService( 1036): Bluetooth State Change Intent: 13 -> 10
,D/LGBluetoothAPIService( 1967): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1465): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/BluetoothAdapter( 1465): 245163342: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1465): 245163342: getState() :  mService = null. Returning STATE_OFF
D/LGBluetoothAPIService( 1967): Message: 2
D/LGBluetoothAPIService( 1967): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@21f42dd mBinding = false
D/LGBluetoothAPIService( 1967): Sending unbind request.
D/LGBluetoothFeatureConfig( 7000): isPrivacyLogsEnabled : true
I/GKI_LINUX( 3855): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 3855): GKI_exit_task 1 done
I/GKI_LINUX( 3855): GKI_shutdown(): task [BTIF] terminated
D/LGBluetoothUtils( 7000): [BTUI] resetProperty - success
E/LGBluetoothEventManager( 7000): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 7000): [BTUI] clear device connection state
I/BluetoothServiceJni( 3855): cleanupNative: return from cleanup
I/art     ( 3855): --- WEIRD: removing null entry 246
W/art     ( 3855): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 3855): Cleaning up Bluetooth Service callback object
D/administrator( 1036): Handling package changes for user 0
,D/LGBluetoothSettingsDBObserver( 3855): [BTUI] unregister observer for LG device name DB
D/BluetoothPermissionRequest( 7000): onReceive
I/art     ( 3855): System.exit called, status: 0
I/AndroidRuntime( 3855): VM exiting with result code 0, cleanup skipped.
D/LGBluetoothAuthorization( 7000): [BTUI] cancel All Notification
D/LGBluetoothResetSettingReceiver( 7000): return without doing reset settings.
I/ActivityManager( 1036): Killing 6008:com.lge.bnr/1000 (adj 15): empty #17
,V/AudioFlinger(  318): 3855 died, releasing its sessions
V/AudioFlinger(  318):  pid 1871 @ 0
V/AudioFlinger(  318):  pid 2194 @ 1
V/AudioFlinger(  318):  pid 3375 @ 2
V/AudioFlinger(  318):  pid 3375 @ 3
D/LGBluetoothUserBindClient( 7000): [BTUI] onServiceDisconnected
V/Signer  ( 7043): override build config not found
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
D/Signer  ( 7043): value of property debug is false
,I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,W/BroadcastQueue( 1036): Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
W/BroadcastQueue( 1036): android.os.DeadObjectException
W/BroadcastQueue( 1036): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 1036): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue( 1036): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:857)
W/BroadcastQueue( 1036): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:252)
W/BroadcastQueue( 1036): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:939)
W/BroadcastQueue( 1036): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:16582)
W/BroadcastQueue( 1036): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:473)
W/BroadcastQueue( 1036): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
W/BroadcastQueue( 1036): 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
W/BroadcastQueue( 1036): 	at android.os.Binder.execTransact(Binder.java:446)
,I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2082): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2082): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[Concierge]WidgetView( 2082): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
W/ActivityManager( 1036): Scheduling restart of crashed service com.android.bluetooth/com.qcom.bluetooth.service.ftp.BluetoothFtpService in 1000ms
W/ActivityManager( 1036): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
W/ActivityManager( 1036): Scheduling restart of crashed service com.android.bluetooth/com.qcom.bluetooth.service.sap.BluetoothSapService in 21000ms
,I/NotificationService( 1036): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService( 1036): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 1036): Receieved: android.intent.action.PACKAGE_REMOVED
I/art     ( 1036): Explicit concurrent mark sweep GC freed 45597(2MB) AllocSpace objects, 5(336KB) LOS objects, 33% free, 44MB/67MB, paused 2.525ms total 372.725ms
,I/ActivityManager( 1036): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7087 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
W/ActivityManager( 1036): Spurious death for ProcessRecord{5c08f 7087:com.android.bluetooth/1002}, curProc for 3855: null
W/libprocessgroup( 1036): failed to open /acct/uid_1000/pid_6008/cgroup.procs: No such file or directory
,D/[Concierge]Service( 2587): onStartCommand(). Type : 8
D/[Concierge]Service( 2587): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/LGMDMWrapper( 7043): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/DSQN    ( 1036): EVENT_INTERNET_CHECK_ENABLE received
D/[Concierge]Service( 2587): Update widget ID : 11
I/Timeline( 1036): Timeline: Activity_windows_visible id: ActivityRecord{115f40c6 u0 com.lge.launcher2/.Launcher t1} time:84995
D/PhoneStatusBar( 1465): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1465): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1465):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1465): , Keyguard show=false, IME shown=false, Panel expanded=false
D/[Concierge]WidgetView( 2082): change position of spinner
D/TaskPersister( 1036): removeObsoleteFile: deleting file=2_task.xml
D/LGMDMWrapper( 7043): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 7043): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 7043): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 7043): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 7043): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 7043): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 7043): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
,D/LGMDMWrapper( 7043): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 7043): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 7043): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 7043): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 7043): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
V/LGMDMManager( 7043): Create singleton instance
I/[Concierge]WidgetView( 2082): initWebView(). Time : 1448020254065
D/[Concierge]Service( 2587): onStartCommand(). Type : 0
,W/ResourcesManager( 7087): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 7087): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7087): Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 7087): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/[Concierge]WebView( 2082): Return exist ConciergeWebView. Reuse : 985578697
D/[Concierge]WidgetView( 2082): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2082): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
D/AndroidRuntime( 7023): Shutting down VM
I/[LgeWidgetLib]ExtViewHost( 2082): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@296e1997
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 2082): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/BluetoothAdapterApp( 7087): Loading JNI Library
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
D/[Concierge]WidgetView( 2082): isWidgetUpdateSkippable ? true
D/[Concierge]WidgetBroadcastReceiver( 2082): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,W/[Concierge]WidgetView( 2082): Widget kill message received. Destory myself. My : 1448020197014, New one : 1448020254065
D/[Concierge]WidgetView( 2082): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2082): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
,I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/LGMDMWrapper( 7043): LG MDM library v4.0.0 is available on this device.
D/BluetoothAdapterApp( 7087): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@5a69d15 Instance Count = 1
,D/BluetoothAdapterApp( 7087): onCreate
D/ProfileConfigQcom( 7087): [BTUI] HeadsetService is supported
D/ProfileConfigQcom( 7087): Adding HeadsetService
D/ProfileConfigQcom( 7087): [BTUI] A2dpService is supported
D/ProfileConfigQcom( 7087): Adding A2dpService
D/ProfileConfigQcom( 7087): [BTUI] HidService is supported
D/ProfileConfigQcom( 7087): Adding HidService
D/ProfileConfigQcom( 7087): [BTUI] HealthService is supported
D/ProfileConfigQcom( 7087): Adding HealthService
D/LGBluetoothFeatureConfig( 7087): isSupportPan() :  mTargetOp=OPEN
,D/ProfileConfigQcom( 7087): [BTUI] PanService is supported
D/ProfileConfigQcom( 7087): Adding PanService
D/ProfileConfigQcom( 7087): [BTUI] GattService is supported
D/ProfileConfigQcom( 7087): Adding GattService
D/ProfileConfigQcom( 7087): [BTUI] BluetoothMapService is supported
D/ProfileConfigQcom( 7087): Adding BluetoothMapService
D/ProfileConfigQcom( 7087): [BTUI] HeadsetClientService is NOT supported
D/LGBluetoothOppAdapter( 7087): [BTUI] getInstance : create [LGBluetoothOppAdapter]
V/BluetoothOppReceiver( 7087): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 7087): [BTUI] cancel opp incoming file confirm notification
D/BluetoothOppNotification( 7087): [BTUI] cancel opp active transfer file notification
I/GAV2    ( 6892): Thread[GAThread,5,main]: No campaign data found.
I/[LgeWidgetLib]LgeAppWidgetHostView( 2082): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 2082): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2082): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2082): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/LGBluetoothServiceJni( 7087): classInitNative: succeeds
V/BluetoothFtpService( 7087): Ftp Service onCreate
I/BluetoothFtpService( 7087): Ftp Service onCreate
D/BluetoothManagerService( 1036): Message: 20
D/BluetoothManagerService( 1036): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@31283db3:true
V/BluetoothFtpService( 7087): Ftp Service onStartCommand
V/LGMDMManagerInternal( 7087): Create singleton instance
D/LGBluetoothUserBindClient( 7000): [BTUI] onServiceConnected
,I/Timeline( 2082): Timeline: Activity_idle id: android.os.BinderProxy@186d4266 time:85149
W/ResourcesManager( 1036): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType( 1036): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 2082): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,D/PostponalbeReceiver( 7043): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,W/ContextImpl( 7043): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/ActivityManager( 1036): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7113 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,I/ActivityManager( 1036): Killing 6564:com.lge.clock/u0a10 (adj 15): empty #17
W/ActivityThread( 7043): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,V/BluetoothFtpReceiver( 7087): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,W/libprocessgroup( 1036): failed to open /acct/uid_10010/pid_6564/cgroup.procs: No such file or directory
V/BluetoothFtpReceiver( 7087): BluetoothFtpReceiver Start Service
V/BluetoothFtpService( 7087): Ftp Service onStartCommand
V/BluetoothFtpService( 7087): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 7087): Ftp Service closeService
,V/BluetoothFtpService( 7087): successfully stopped ftp service
V/BluetoothSapReceiver( 7087): [BTUI] checkServiceStart
V/BluetoothSapReceiver( 7087): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 7087): SapReceiver onReceive 
V/BluetoothSapReceiver( 7087): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 7087):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 7087): Calling SAP service start service with action = null
V/BluetoothFtpService( 7087): Ftp Service onDestroy
V/BluetoothFtpService( 7087): Ftp Service closeService
I/chromium( 2082): [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,I/PCSuite ( 7113): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,I/ActivityManager( 1036): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7136 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/PCSuite ( 7113): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7113): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/GBoardtInterface( 2082): onReloaded()
,I/GBoardWebViewClient( 2082): onPageFinished url:file:///android_asset/www/main.html
V/BoardContentProvider( 3770): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
V/BluetoothSapService( 7087): Sap Service onCreate
V/BluetoothSapService( 7087): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 7087): state: 13
V/WiFiOffLoadBroadcast( 7000): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/FileUtils( 7043): Failed to chmod(/data/data/com.wsandroid.suite.lge/databases/WSAndroid): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
V/BoardContentProvider( 3770): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
W/FileUtils( 7113): Failed to chmod(/data/data/com.lge.sync/databases/lgds.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,D/LgDataFeature( 7000): LgDataFeature() Constructor: none
D/LgDataFeature( 7000): LgDataFeature() Constructor Done, null
,D/WiFiOffLoadBroadcast( 7000): MCCMNC not supported: null
D/QRemote ( 6612): [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,D/QRemote ( 6612): [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,E/SQLiteDatabase( 7043): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/lockedapplications'.
E/SQLiteDatabase( 7043): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7043): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7043): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 7043): 	at com.mcafee.applock.a.a(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.applock.d.d(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.applock.d.<init>(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.applock.d.a(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.modes.adapt.a.a(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.applock.h.<init>(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.applock.f.<init>(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.applock.f.a(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7043): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7043): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7043): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7043): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7043): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7043): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7043): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteOpenHelper( 7043): Couldn't open lockedapplications for writing (will try read-only):
E/SQLiteOpenHelper( 7043): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7043): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7043): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteOpenHelper( 7043): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteOpenHelper( 7043): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQ,LiteConnectionPool.java:463)
E/SQLiteOpenHelper( 7043): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 7043): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 7043): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteOpenHelper( 7043): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteOpenHelper( 7043): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteOpenHelper( 7043): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteOpenHelper( 7043): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteOpenHelper( 7043): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 7043): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 7043): 	at com.mcafee.applock.a.a(Unknown Source)
E/SQLiteOpenHelper( 7043): 	at com.mcafee.applock.d.d(Unknown Source)
E/SQLiteOpenHelper( 7043): 	at com.mcafee.applock.d.<init>(Unknown Source)
E/SQLiteOpenHelper( 7043): 	at com.mcafee.applock.d.a(Unknown Source)
E/SQLiteOpenHelper( 7043): 	at com.mcafee.modes.adapt.a.<init>(Unknown Source)
E/SQLiteOpenHelper( 7043): 	at com.mcafee.modes.adapt.a.a(Unknown Source)
E/SQLiteOpenHelper( 7043): 	at com.mcafee.modes.adapt.ModesLockHelper.a(Unknown Source)
E/SQLiteOpenHelper( 7043): 	at com.mcafee.applock.h.<init>(Unknown Source)
E/SQLiteOpenHelper( 7043): 	at com.mcafee.applock.f.<init>(Unknown Source)
E/SQLiteOpenHelper( 7043): 	at com.mcafee.applock.f.a(Unknown Source)
E/SQLiteOpenHelper( 7043): 	at com.mcafee.applock.AppLockComponent.d(Unknown Source)
E/SQLiteOpenHelper( 7043): 	at com.mcafee.applock.AppLockComponent.a_(Unknown Source)
E/SQLiteOpenHelper( 7043): 	at com.mcafee.applock.AppLockComponent.a(Unknown Source)
E/SQLiteOpenHelper( 7043): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteOpenHelper( 7043): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteOpenHelper( 7043): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteOpenHelper( 7043): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteOpenHelper( 7043): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteOpenHelper( 7043): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteOpenHelper( 7043): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 7043): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 7043): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteOpenHelper( 7043): 	at com.mcafee.d.c.run(Unknown Source)
D/ActionManagerService( 1931): notifyUserLog: 1000001
W/ResourcesManager( 7136): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/SQLiteOpenHelper( 7043): Opened lockedapplications in read-only mode
D/LIA_Informant_ActionManagerMessageHandler( 3770): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3770): onEvent() : ACTION_BOARD_ENABLED
D/ActionManagerService( 1931): notifyUserLog: 1000001
D/LIA_Informant_ActionManagerMessageHandler( 3770): handleMessage: what(1000) actionID(0x1000001)
D/LIA_Informant_Tips_SmartTipsActionManager( 3770): onEvent() : ACTION_BOARD_ENABLED
D/LIA_Informant_Tips_FormEventRepository( 3770): getSize() : size - 0
D/LIA_Informant_Tips_SmartTipsActionManager( 3770): onSettingEvent() : GBoard On - add scheduler - 0
V/BoardContentProvider( 3770): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/QRemote ( 6612): [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
D/PostponalbeReceiver( 7043): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,W/ContextImpl( 7043): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/ActivityManager( 1036): Killing 6591:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
I/PCSuite ( 7113): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 7113): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 7113): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
E/SQLiteDatabase( 7043): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7043): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7043): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7043): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7043): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.wsstorage.ConfigManager.b(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.notificationtray.e.<init>(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.notificationtray.e.a(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.notificationtray.NotificationComponent.a(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7043): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7043): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7043): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7043): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7043): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7043): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7043): 	at com.mcafee.d.c.run(Unknown Source)
D/AuthorizationBluetoothService( 2127): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,V/WiFiOffLoadBroadcast( 7000): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/GBoardUriUtils( 2082): fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
D/GBoardWebViewUtils( 2082): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
W/libprocessgroup( 1036): failed to open /acct/uid_10085/pid_6591/cgroup.procs: No such file or directory
D/GBoardUriUtils( 2082): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
D/GBoardWebViewUtils( 2082): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
D/WiFiOffLoadBroadcast( 7000): MCCMNC not supported: null
D/GBoardUriUtils( 2082): fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1447937693376&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
D/GBoardWebViewUtils( 2082): changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1447937693376&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/ActivityManager( 1036): Killing 6798:com.google.android.talk/u0a72 (adj 15): empty #17
W/ContextImpl( 7000): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,E/SQLiteDatabase( 7043): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7043): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7043): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7043): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7043): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.wsstorage.ConfigManager.a(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.wavesecure.utils.CommonPhoneUtils.o(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.wavesecure.utils.y.v(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7043): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7043): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7043): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7043): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7043): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7043): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7043): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7043): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7043): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7043): 	at androi,d.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7043): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7043): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7043): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.wsstorage.ConfigManager.d(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.wavesecure.utils.CommonPhoneUtils.o(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.wavesecure.utils.y.v(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7043): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7043): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7043): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7043): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7043): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7043): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7043): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 7043): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 7043): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 7043): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 7043): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 7043): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 7043): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.wsstorage.ConfigManager.m(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 7043): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 7043): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 7043): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 7043): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 7043): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 7043): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 7043): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 7043): 	at com.mcafee.d.c.run(Unknown Source)

```
