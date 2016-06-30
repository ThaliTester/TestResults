#### Test 7578926851a8f91_thali01_LGE-LG-D722 Logs


```
--------- beginning of system
06-30 12:51:47.995   243   313 W Vold    : Returning OperationFailed - no handler for errno 0
--------- beginning of main
06-30 12:51:47.996  6151  6498 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.gms/files
06-30 12:51:48.116  6151  6498 W DriveInitializer: Background init thread ended
06-30 12:51:48.170  6151  6511 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
06-30 12:51:48.170  6151  6511 D SchedPeriodicTask: Scheduled AdAttestation task.
06-30 12:51:48.189  2386  2386 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 12:51:48.223  6151  6509 W InstanceID/Rpc: Found 10006
,06-30 12:51:48.547  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-30 12:51:48.547  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 12:51:48.547  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
06-30 12:51:48.610   857   876 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6523 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
06-30 12:51:48.612  6518  6518 D AndroidRuntime: 
06-30 12:51:48.612  6518  6518 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-30 12:51:48.620  6518  6518 D AndroidRuntime: CheckJNI is OFF
06-30 12:51:48.689  6523  6523 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-30 12:51:48.689  6523  6523 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
06-30 12:51:48.739  6523  6523 I MultiDex: VM with version 2.1.0 has multidex support
06-30 12:51:48.739  6523  6523 I MultiDex: install
06-30 12:51:48.739  6523  6523 I MultiDex: VM has multidex support, MultiDex support library is disabled.
06-30 12:51:48.777  6523  6523 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
06-30 12:51:48.841  6523  6523 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
06-30 12:51:48.841  6523  6523 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@267d879f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
06-30 12:51:48.842  6523  6523 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
06-30 12:51:48.843  6523  6523 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
06-30 12:51:48.844  6523  6523 I NotificationManager: com.google.android.gms: cancel(39789) by com.google.android.gms
06-30 12:51:48.851  6523  6523 D ChimeraCfgMgr: Reading stored module config
06-30 12:51:48.876  6518  6518 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-30 12:51:48.900   857  2174 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-30 12:51:48.902  2386  2420 I art     : Explicit concurrent mark sweep GC freed 59944(3MB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 14MB/24MB, paused 2.032ms total 127.239ms
06-30 12:51:48.960   857  2174 D ActivityManager: setTaskToReturnTo : TaskRecord{33317a5 #241 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
06-30 12:51:48.962   857  2174 D ActivityManager: setTaskToReturnTo : TaskRecord{33317a5 #241 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
06-30 12:51:48.982   857  2174 D WindowStateEx: AppWindowTokenEx init.. 
06-30 12:51:48.983  6523  6552 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
06-30 12:51:48.998   857  1054 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
06-30 12:51:49.017   857  2174 D InputDispatcher: Focus left window: Window{19624832 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
06-30 12:51:49.020  6518  6518 D AndroidRuntime: Shutting down VM
06-30 12:51:49.026  1950  1950 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
06-30 12:51:49.035   857  1054 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
06-30 12:51:49.047   857  1054 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
06-30 12:51:49.047   857  1054 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
06-30 12:51:49.067   857  1054 D SplitWindow: check instance of lgWin Window{ee4c3a0 u0 Starting com.test.thalitest}
06-30 12:51:49.078  6523  6523 I art     : Rejecting re-init on previously-failed class java.lang.Class<inz>
06-30 12:51:49.078  6523  6523 I art     : Rejecting re-init on previously-failed class java.lang.Class<inz>
06-30 12:51:49.115   857  1909 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6556 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
06-30 12:51:49.145  1950  1950 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
06-30 12:51:49.192   276  1303 D WVCdm   : Instantiating CDM.
06-30 12:51:49.195   276  1354 I WVCdm   : CdmEngine::OpenSession
06-30 12:51:49.195   276  1354 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
06-30 12:51:49.205  1950  1950 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
06-30 12:51:49.216   857  1996 I WindowStateAnimator: Starting window displayed
06-30 12:51:49.221   857  1052 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
06-30 12:51:49.227   857  1052 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
06-30 12:51:49.228  2027  2027 I HotwordDetector: Closing mic
06-30 12:51:49.232   857  1052 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
06-30 12:51:49.232   857  1052 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
06-30 12:51:49.232   857  1052 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-30 12:51:49.232   857  1052 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1e0e7aad,  pkg=WindowManager.LayoutParams
06-30 12:51:49.232   857  1052 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
06-30 12:51:49.246  1379  1379 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
06-30 12:51:49.249  1379  1379 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
06-30 12:51:49.249  1379  1379 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
06-30 12:51:49.249  1379  1379 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
06-30 12:51:49.257   276  1354 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
06-30 12:51:49.258   276  1354 W WVCdm   : Properties::GetOEMCryptoPath: null. applies level3
06-30 12:51:49.258   276  1354 W WVCdm   : L1 library not specified. Falling Back to L3
06-30 12:51:49.265  2027  2604 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@27efdd9d
06-30 12:51:49.265  2027  2604 V AudioRecord: stop()
06-30 12:51:49.265  2027  2604 D AudioRecord: AudioRecord->stop()
06-30 12:51:49.265   276  1303 V AudioFlinger: RecordHandle::stop()
06-30 12:51:49.265   276  1303 V AudioFlinger: RecordThread::stop
06-30 12:51:49.270   276  1303 V AudioFlinger: Record stopped OK
06-30 12:51:49.279   276  1303 V AudioPolicyManager: stopInput() input 17
06-30 12:51:49.281   276  1303 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
06-30 12:51:49.282   276  2633 D audio_hw_primary: in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
06-30 12:51:49.282   276  1303 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
06-30 12:51:49.282   276  1067 V AudioPolicyService: AudioCommandThread() waking up
06-30 12:51:49.282   276  1067 V AudioPolicyService: AudioCommandThread() processing release audio patch
06-30 12:51:49.282   276  1067 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
06-30 12:51:49.282   276  1067 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
06-30 12:51:49.282   276  1067 V AudioFlinger: ThreadBase::setParameters() routing=0
06-30 12:51:49.291  2386  2386 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=f4f5219b-198d-4a36-9bd4-cf6403928b09
06-30 12:51:49.293  6523  6537 I art     : CheckpointMarkThreadRoots callback created = 0xb042d370
06-30 12:51:49.323   276  2633 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
06-30 12:51:49.323   276  2633 V audio_hw_primary: disable_audio_route: enter: usecase(7)
06-30 12:51:49.323   276  2633 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
06-30 12:51:49.323   276  2633 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
06-30 12:51:49.325   276  2633 V audio_hw_primary: disable_audio_route: exit
06-30 12:51:49.325   276  2633 E audio_hw_primary: disable_snd_device: enter 144
06-30 12:51:49.325   276  2633 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
06-30 12:51:49.325   276  2633 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
06-30 12:51:49.329  6556  6556 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
06-30 12:51:49.329   276  2633 V audio_hw_primary: stop_input_stream: exit: status(0)
06-30 12:51:49.329   276  2633 V audio_hw_primary: in_standby: exit:  status(0)
06-30 12:51:49.329   276  2633 V AudioFlinger: RecordThread: loop stopping
06-30 12:51:49.329   276  1067 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
06-30 12:51:49.329   276  2633 V AudioFlinger: RecordThread: loop starting
06-30 12:51:49.329   276  2633 V AudioFlinger: processConfigEvents_l() remaining events 1
06-30 12:51:49.330   276  2633 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3852000
06-30 12:51:49.330   276  2633 V AudioFlinger: RecordThread: loop stopping
06-30 12:51:49.330   276  1067 V AudioPolicyService: AudioCommandThread() going to sleep
06-30 12:51:49.330   276  1303 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
06-30 12:51:49.330   276  1303 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
06-30 12:51:49.330   276  1303 V AudioPolicyService: AudioCommandThread() adding update audio patch list
06-30 12:51:49.330   276  1303 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
06-30 12:51:49.330   276  1068 V AudioPolicyService: AudioCommandThread() waking up
06-30 12:51:49.330   276  1068 V AudioPolicyService: AudioCommandThread() processing update audio patch list
06-30 12:51:49.331   276  1068 V AudioPolicyService: AudioCommandThread() going to sleep
06-30 12:51:49.333   276  1303 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
06-30 12:51:49.333   276  1303 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
06-30 12:51:49.334   276  1067 V AudioPolicyService: AudioCommandThread() waking up
06-30 12:51:49.334   276  1067 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
06-30 12:51:49.334   276  1067 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 276
06-30 12:51:49.334   276  1067 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
06-30 12:51:49.334   276  1067 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
06-30 12:51:49.334   276  2633 V AudioFlinger: RecordThread: loop starting
06-30 12:51:49.334   276  2633 V AudioFlinger: processConfigEvents_l() remaining events 1
06-30 12:51:49.334   276  2633 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
06-30 12:51:49.334   276  2633 V audio_hw_primary: in_set_parameters: exit: status(0)
06-30 12:51:49.334   276  2633 V AudioFlinger: processConfigEvents_l() DONE thread 0xb3852000
06-30 12:51:49.334   276  2633 V AudioFlinger: RecordThread: loop stopping
06-30 12:51:49.334   276  1067 V AudioPolicyService: AudioCommandThread() going to sleep
06-30 12:51:49.340  6523  6537 I art     : CheckpointMarkThreadRoots callback created = 0xb042d360
06-30 12:51:49.349  2386  2386 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 12:51:49.352  2386  2386 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
06-30 12:51:49.352  2027  2604 V AudioRecord: stop()
06-30 12:51:49.353  2027  2604 V AudioRecord: stop()
06-30 12:51:49.353  2027  2604 V AudioRecord: stop()
06-30 12:51:49.355   276   276 V AudioFlinger: RecordHandle::stop()
06-30 12:51:49.355   276   276 V AudioFlinger: RecordThread::stop
06-30 12:51:49.355   276   276 V AudioPolicyManager: releaseInput() 17
06-30 12:51:49.355   276   276 V AudioPolicyManager: closeInput(17)
06-30 12:51:49.355   276   276 V AudioFlinger: closeInput() 17
06-30 12:51:49.356   276   276 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
06-30 12:51:49.356  1379  2096 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
06-30 12:51:49.356   276   276 V AudioFlinger: ThreadBase::exit
06-30 12:51:49.356  2861  2877 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
06-30 12:51:49.356  2077  3456 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
06-30 12:51:49.356   857  1615 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
06-30 12:51:49.356  1824  2331 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
06-30 12:51:49.356  2027  2049 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
06-30 12:51:49.357  3136  3152 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
06-30 12:51:49.357   276  2633 V AudioFlinger: RecordThread: loop starting
06-30 12:51:49.357   276  2633 V AudioFlinger: RecordThread 0xb3852000 exiting
06-30 12:51:49.357   276   276 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb546e240)
06-30 12:51:49.357   276   276 D audio_hw_primary: in_standby: enter: stream (0xb546e240) usecase(7: audio-record)
06-30 12:51:49.357   276  1641 V AudioFlinger: releasing 16 from 2027 for -1
06-30 12:51:49.357   276   276 V audio_hw_primary: in_standby: exit:  status(0)
06-30 12:51:49.357   276  1641 V AudioFlinger:  decremented refcount to 0
06-30 12:51:49.357   276  1641 V AudioFlinger: purging stale effects
06-30 12:51:49.358   276   276 V AudioPolicyService: AudioCommandThread() adding update audio port list
06-30 12:51:49.358   276   276 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
06-30 12:51:49.358   276   276 V AudioPolicyManager: releaseInput() exit
06-30 12:51:49.358   276  1068 V AudioPolicyService: AudioCommandThread() waking up
06-30 12:51:49.358   276  1068 V AudioPolicyService: AudioCommandThread() processing update audio port list
06-30 12:51:49.358   276  1068 V AudioPolicyService: AudioCommandThread() going to sleep
06-30 12:51:49.358   276   276 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
06-30 12:51:49.358   276   276 V AudioFlinger: removeClient_l() pid 2027, calling pid 276
06-30 12:51:49.364  2027  2616 I HotwordRecognitionRnr: Stopping hotword detection.
06-30 12:51:49.375  6523  6537 I art     : Background partial concurrent mark sweep GC freed 1825(267KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 10MB/17MB, paused 8.648ms total 84.257ms
06-30 12:51:49.380  2027  2624 I HotwordRecognitionRnr: Hotword detection finished
06-30 12:51:49.390  6523  6539 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 12:51:49.390  6523  6539 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 12:51:49.392  6523  6539 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 12:51:49.392  6523  6539 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 12:51:49.393   272  1043 E BandwidthController: [LG DATA] No such appUid: 10006
06-30 12:51:49.393   272  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-30 12:51:49.396   272  6579 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 12:51:49.396   272  6579 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 12:51:49.396   272  6579 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 12:51:49.397   272  6579 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 12:51:49.397   272  6579 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 12:51:49.397  5544  5559 I art     : Explicit concurrent mark sweep GC freed 2497(95KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 806us total 32.894ms
06-30 12:51:49.398  6523  6539 I System.out: propertyValue:false
06-30 12:51:49.411   276  1354 I WVCdm   : CdmEngine::QueryKeyControlInfo
06-30 12:51:49.414   276  1303 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
06-30 12:51:49.414   276  1303 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
06-30 12:51:49.414   276  1303 I WVCdm   : CdmEngine::GenerateKeyRequest
06-30 12:51:49.422   276  1303 D WVCdm   : PrepareKeyRequest: nonce=129639986
06-30 12:51:49.486  6523  6539 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 12:51:49.486  6523  6539 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 12:51:49.491  6556  6556 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
06-30 12:51:49.545  6556  6556 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1487-1491)
06-30 12:51:49.546  6556  6556 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 12:51:49.551  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-30 12:51:49.551  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 12:51:49.552  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
06-30 12:51:49.596  2386  2748 W GCoreFlp: No location to return for getLastLocation()
06-30 12:51:49.598  6556  6556 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2334fceb}
06-30 12:51:49.599  6556  6556 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 12:51:49.606  6556  6556 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 12:51:49.636  6556  6556 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-30 12:51:49.637  6556  6556 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 12:51:49.642  6556  6556 E SysUtils: ApplicationContext is null in ApplicationStatus
06-30 12:51:49.654  2386  2729 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
06-30 12:51:49.658  6151  6520 D UdcContextInitService: registered all accounts: true
06-30 12:51:49.683  2386  2670 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
06-30 12:51:49.695  6151  6520 I GAv4-SVC: Google Analytics 9.2.56 is starting up.
06-30 12:51:49.735  6556  6556 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
06-30 12:51:49.747  6556  6556 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 12:51:49.747  6556  6556 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 12:51:49.751  6556  6556 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 12:51:49.751  6556  6556 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 12:51:49.751  6556  6556 I Adreno-EGL: Build Date: 03/02/15 Mon
06-30 12:51:49.751  6556  6556 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
06-30 12:51:49.751  6556  6556 I Adreno-EGL: Remote Branch: 
06-30 12:51:49.751  6556  6556 I Adreno-EGL: Local Patches: 
06-30 12:51:49.751  6556  6556 I Adreno-EGL: Reconstruct Branch: 
06-30 12:51:49.888   276  1641 V AudioPolicyService: registerClient() client 0xb383eee0, uid 10030
06-30 12:51:49.907   857  1053 D BluetoothManagerService: Message: 20
,06-30 12:51:49.909   857  1053 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f0e9956:true
06-30 12:51:49.916  2077  2094 D BluetoothAdapterService(124989665): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@110e3dbf
06-30 12:51:50.054  6556  6556 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 12:51:50.066  6556  6556 W AwContents: onDetachedFromWindow called when already detached. Ignoring
06-30 12:51:50.072  6556  6556 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
06-30 12:51:50.076  6556  6556 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
06-30 12:51:50.076  6556  6556 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
06-30 12:51:50.098  6556  6556 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
06-30 12:51:50.109  6556  6556 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 12:51:50.109  6556  6556 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 12:51:50.161  6556  6556 I Activity: Activity.onPostResume() called 
06-30 12:51:50.172  6556  6610 D OpenGLRenderer: Render dirty regions requested: true
06-30 12:51:50.172  6556  6610 I OpenGLRenderer: Initialized EGL, version 1.4
06-30 12:51:50.192  6556  6610 D OpenGLRenderer: Enabling debug mode 0
06-30 12:51:50.222  6556  6556 D Atlas   : Validating map...
06-30 12:51:50.227   857  1922 D SplitWindow: check instance of lgWin Window{20e358f4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 12:51:50.240  6556  6597 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
06-30 12:51:50.263  6611  6611 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=41 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
06-30 12:51:50.273   857  1922 D InputDispatcher: Focus entered window: Window{20e358f4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 12:51:50.328   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 12:51:50.328   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 12:51:50.329   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 132274696204; DSPS: 4425942; Offset : -2803206482
06-30 12:51:50.372   857   876 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
06-30 12:51:50.378  6611  6611 I dex2oat : dex2oat took 111.866ms (threads: 4)
06-30 12:51:50.380   857  1054 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s310ms
06-30 12:51:50.383   857  1054 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1c93877a u0 com.test.thalitest/.MainActivity t241} time:132326
06-30 12:51:50.399  6523  6539 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 12:51:50.399  6523  6539 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 12:51:50.399  6523  6539 I Adreno-EGL: Build Date: 03/02/15 Mon
06-30 12:51:50.399  6523  6539 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
06-30 12:51:50.399  6523  6539 I Adreno-EGL: Remote Branch: 
06-30 12:51:50.399  6523  6539 I Adreno-EGL: Local Patches: 
06-30 12:51:50.399  6523  6539 I Adreno-EGL: Reconstruct Branch: 
06-30 12:51:50.416  6556  6556 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@e09a48d time:132362
06-30 12:51:50.468  6556  6556 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6556
06-30 12:51:50.630  6523  6539 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 12:51:50.630  6523  6539 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 12:51:50.630  6523  6539 I Adreno-EGL: Build Date: 03/02/15 Mon
06-30 12:51:50.630  6523  6539 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
06-30 12:51:50.630  6523  6539 I Adreno-EGL: Remote Branch: 
06-30 12:51:50.630  6523  6539 I Adreno-EGL: Local Patches: 
06-30 12:51:50.630  6523  6539 I Adreno-EGL: Reconstruct Branch: 
,06-30 12:51:50.695  6556  6556 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
06-30 12:51:50.702  6523  6539 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 12:51:50.702  6523  6539 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 12:51:50.702  6523  6539 I Adreno-EGL: Build Date: 03/02/15 Mon
06-30 12:51:50.702  6523  6539 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
06-30 12:51:50.702  6523  6539 I Adreno-EGL: Remote Branch: 
06-30 12:51:50.702  6523  6539 I Adreno-EGL: Local Patches: 
06-30 12:51:50.702  6523  6539 I Adreno-EGL: Reconstruct Branch: 
,06-30 12:51:50.870  2386  6521 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 12:51:50.870  2386  6521 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 12:51:50.870  2386  6521 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 12:51:50.870  2386  6521 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,06-30 12:51:50.871   272  1043 E BandwidthController: [LG DATA] No such appUid: 10006
06-30 12:51:50.871   272  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-30 12:51:50.871   272  6627 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 12:51:50.871   272  6627 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 12:51:50.871   272  6627 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 12:51:50.871   272  6627 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 12:51:50.872   272  6627 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 12:51:50.875  2386  6521 I System.out: propertyValue:false
06-30 12:51:50.948  2386  6521 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-30 12:51:50.949  2386  6521 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 12:51:51.119   241   241 E lowmemorykiller: Error writing /proc/6325/oom_score_adj; errno=22
,06-30 12:51:51.216  6556  6620 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426248960
,06-30 12:51:51.236  6556  6620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 12:51:51.236  6556  6620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 12:51:51.236  6556  6620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 12:51:51.236  6556  6620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 12:51:51.236  6556  6620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,06-30 12:51:51.237  6556  6620 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d958766 added. We now have 1 listener(s)
06-30 12:51:51.254   857  1640 I ActivityManager: Process com.google.android.apps.docs (pid 6325) has died
,06-30 12:51:51.256   857  1615 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 12:51:51.266  6556  6620 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
06-30 12:51:51.267  6556  6620 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
06-30 12:51:51.268  6556  6620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 12:51:51.269  6556  6620 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-30 12:51:51.275  6556  6620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 12:51:51.275  6556  6620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 12:51:51.275  6556  6620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 12:51:51.275  6556  6620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
06-30 12:51:51.275  6556  6620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 12:51:51.275  6556  6620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 12:51:51.275  6556  6620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 12:51:51.275  6556  6620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 12:51:51.275  6556  6620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 12:51:51.275  6556  6620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 12:51:51.275  6556  6620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 12:51:51.275  6556  6620 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3df9cafd added. We now have 1 listener(s)
06-30 12:51:51.275  6556  6620 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 12:51:51.292  2077  2095 D BluetoothAdapterService(124989665): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@110e3dbf
,06-30 12:51:51.293  6556  6620 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
06-30 12:51:51.307  2386  2670 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,06-30 12:51:51.317  2386  2670 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
06-30 12:51:51.318  6556  6620 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
06-30 12:51:51.319  6556  6620 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
06-30 12:51:51.320  2386  2670 V BaseAppContext: GmsRequestQueue started.
,06-30 12:51:51.323  6556  6620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-30 12:51:51.324   857  1922 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 12:51:51.325  6556  6620 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
06-30 12:51:51.329  2386  2670 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-06-30 12:51:49.764+0200, stopTime=2016-06-30 12:51:51.320+0200, duration=1556ms
06-30 12:51:51.335  2077  3461 D BluetoothAdapterService(124989665): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@110e3dbf
,06-30 12:51:51.336  6556  6620 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 12:51:51.336  6556  6620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 12:51:51.336  6556  6620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 12:51:51.336  6556  6620 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 12:51:51.336  6556  6620 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 12:51:51.336  6556  6620 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-30 12:51:51.336  6556  6620 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-30 12:51:51.336  6556  6620 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-30 12:51:51.336  6556  6620 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 12:51:51.337  6556  6620 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 12:51:51.339  6556  6620 I io.jxcore.node.LifeCycleMonitor: start: OK
06-30 12:51:51.345   291   352 I ThermalEngine: Sensor:pa_therm0:32000 mC
06-30 12:51:51.365  2386  6634 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 12:51:51.365  2386  6634 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 12:51:51.366  2386  6634 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 12:51:51.366  2386  6634 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 12:51:51.366   272  1043 E BandwidthController: [LG DATA] No such appUid: 10006
06-30 12:51:51.366   272  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-30 12:51:51.367   272  6638 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 12:51:51.367   272  6638 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 12:51:51.368   272  6638 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 12:51:51.369   272  6638 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 12:51:51.369   272  6638 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 12:51:51.378  2386  6634 I System.out: propertyValue:false
,06-30 12:51:51.399  6556  6556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-30 12:51:51.404  6556  6556 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 12:51:51.407  6556  6556 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
06-30 12:51:51.492  6151  6248 V UdcCtxListenerSrv: handle intent
,06-30 12:51:51.597  6556  6571 I art     : CheckpointMarkThreadRoots callback created = 0xb07faf50
,06-30 12:51:51.628  6556  6571 I art     : CheckpointMarkThreadRoots callback created = 0xb07faf20
,06-30 12:51:51.803  2386  2670 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,06-30 12:51:51.962  2386  6642 E CommitToConfigurationOperation: Malformed snapshot token (size): 
06-30 12:51:51.963  2386  6640 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,06-30 12:51:51.989  2386  6642 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,06-30 12:51:51.991   276  1641 I WVCdm   : CdmEngine::CloseSession
06-30 12:51:51.991  2386  6640 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
06-30 12:51:51.996   276  1641 I WVCdm   : L3 Terminate.
06-30 12:51:52.012  2386  6642 E CommitToConfigurationOperation: Malformed snapshot token (size): 
06-30 12:51:52.014  2386  6640 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
06-30 12:51:52.014  2386  6640 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,06-30 12:51:52.031  2386  6640 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,06-30 12:51:52.076   857   875 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 12:51:52.137  2386  6640 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 12:51:52.137  2386  6640 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 12:51:52.137  2386  6640 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 12:51:52.137  2386  6640 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 12:51:52.138   272  1043 E BandwidthController: [LG DATA] No such appUid: 10006
,06-30 12:51:52.138   272  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
,06-30 12:51:52.138   272  6645 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 12:51:52.138   272  6645 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 12:51:52.138   272  6645 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 12:51:52.139   272  6645 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 12:51:52.139   272  6645 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 12:51:52.139  2386  6640 I System.out: propertyValue:false
06-30 12:51:52.144   857  2043 I art     : Explicit concurrent mark sweep GC freed 64141(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.262ms total 189.291ms
06-30 12:51:52.284  6556  6637 W jxcore-log: Initializing JXcore engine
,06-30 12:51:52.285  6556  6637 W jxcore-log: JXcore engine is ready
06-30 12:51:52.375  6637  6637 W Thread-789: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5638]" dev="sockfs" ino=5638 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
06-30 12:51:52.375  6637  6637 W Thread-789: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,06-30 12:51:52.375  6637  6637 W Thread-789: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8488]" dev="sockfs" ino=8488 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
06-30 12:51:52.375  6637  6637 W Thread-789: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
06-30 12:51:52.375  6637  6637 W Thread-789: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
06-30 12:51:52.375  6637  6637 W Thread-789: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[30765]" dev="sockfs" ino=30765 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
06-30 12:51:52.410  6556  6637 W jxcore-log: Starting JXcore engine
,06-30 12:51:52.513   857  2174 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 12:51:52.564  6556  6637 W jxcore-log: Platform android
06-30 12:51:52.564  6556  6637 W jxcore-log: 
,06-30 12:51:52.564  6556  6637 W jxcore-log: Process ARCH arm
06-30 12:51:52.564  6556  6637 W jxcore-log: 
06-30 12:51:52.664   857  1365 I ActivityManager: Process com.uei.lg.quicksetsdk.lite (pid 6277) has died
,06-30 12:51:52.845  6556  6637 I jxcore-log: JXcore Cordova bridge is ready!
06-30 12:51:52.845  6556  6637 I jxcore-log: 
,06-30 12:51:52.845  6556  6637 W jxcore-log: JXcore engine is started
06-30 12:51:52.849   857  1943 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
06-30 12:51:52.855  6556  6620 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
06-30 12:51:52.859  6556  6556 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,06-30 12:51:53.083   857  1365 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 12:51:53.174   857  1996 I ActivityManager: Process com.lge.lockscreensettings (pid 6127) has died
,06-30 12:51:53.493   857  1065 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 12:51:53.644   857  1909 I ActivityManager: Process com.lge.eula (pid 6301) has died
,06-30 12:51:53.658   857  2014 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
06-30 12:51:53.735  2386  2670 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,06-30 12:51:53.770  6151  6248 V UdcCtxListenerSrv: handle intent
,06-30 12:51:53.936   857   875 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 12:51:54.374   857   875 I ActivityManager: Process com.android.vending (pid 5527) has died
,06-30 12:51:54.396   857  1289 V AlarmManager: RTC_WAKEUP set : Alarm{2d018645 type 0 when 1467283914341 com.google.android.googlequicksearchbox} when 1467283914341
,06-30 12:51:54.417  1824  1824 I PhoneApp: onTrimMemory: 10
06-30 12:51:54.417  1824  1824 I PhoneApp: trim memory
,06-30 12:51:54.430  2027  2027 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,06-30 12:51:55.564  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-30 12:51:55.564  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 12:51:55.564  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,06-30 12:51:56.350   291   352 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 12:51:56.565  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-30 12:51:56.565  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 12:51:56.565  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,06-30 12:51:57.554  2861  2861 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,06-30 12:51:57.563  2861  2861 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
06-30 12:51:57.568  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,06-30 12:51:57.568  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 12:51:57.568  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,06-30 12:51:59.533  2386  2650 I art     : Explicit concurrent mark sweep GC freed 51138(3MB) AllocSpace objects, 26(439KB) LOS objects, 39% free, 15MB/25MB, paused 2.769ms total 105.998ms
,06-30 12:51:59.571  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-30 12:51:59.571  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,06-30 12:51:59.571  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
06-30 12:52:00.006   857  1289 D PowerManagerServiceEx: acquireWakeLockInternal: lock=549011905, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=857
,06-30 12:52:00.010  2844  2844 D WeatherService: 2 : TimeTick Intent has been received, Time(hour:min:sec) 12:52:0
06-30 12:52:00.011  2844  2844 D WeatherService: 2 : TimeTick Intent And Screen On
06-30 12:52:00.011  2844  2844 D WeatherService: 2 : SDK version : 21
06-30 12:52:00.012   857   875 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
06-30 12:52:00.013  2844  2844 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
06-30 12:52:00.013  2844  2844 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
06-30 12:52:00.013  2844  2844 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
06-30 12:52:00.013  2844  2844 D WeatherService: 2 : requestRefreshAppWidget, isUpdateStart : false
06-30 12:52:00.015  2844  2844 D UpdateThreadPoolManager: 2 : This is isUpdating : false
06-30 12:52:00.015  2844  2844 D WeatherService: 2 : requestRefreshAppWidget, isUpdating : false
06-30 12:52:00.015  2844  2844 D WeatherAncestor: 2 : buildUpdate, appWidgetId: 2
06-30 12:52:00.016  2844  2844 D WeatherTheme: 2 : Current Theme Name: com.lge.launcher2.theme.optimus
06-30 12:52:00.016  2844  2844 D WeatherTheme: 2 : Fixed theme : optimus
06-30 12:52:00.023  2844  2844 D WeatherReflect: 2 : Map key string is -2
,06-30 12:52:00.027  2844  2844 D lim     : 2 : time = 12:52
06-30 12:52:00.031  2844  2844 I WeatherReflect: Model Name : LG-D722
06-30 12:52:00.031  2844  2844 D WeatherTheme: 2 : Different view - status_min_formatted : 51 != 52
06-30 12:52:00.031  2844  2844 D WeatherTheme: 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
06-30 12:52:00.032  2844  2844 D WeatherReflect: 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
06-30 12:52:00.033  2844  2844 D Theme   : strTheme: com.lge.launcher2.theme.optimus
06-30 12:52:00.033  2844  2844 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
06-30 12:52:00.033  2844  2844 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
06-30 12:52:00.033  2844  2844 D Weather4x2_optimus: currentPackage=com.lge.sizechangable.weather.theme.optimus
06-30 12:52:00.049  1379  1379 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 12:52:00.049  1379  1379 I KeyguardUpdateMonitor: called onTimeUpdated()
,06-30 12:52:00.054  1379  1379 I [SystemUI]Clock: called onTimeUpdated()
06-30 12:52:00.055  1379  1379 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 12:52:00.055  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 12:52:00.058  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 12:52:00.059  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 12:52:00.072  2844  2844 D Weather4x2_optimus: [[[[[[Theme package!!]]]]]] RemoteViews are created 2
06-30 12:52:00.072  2844  2844 D Weather4x2_optimus: widgetType = 1, orientation = 1
,06-30 12:52:00.072  2844  2844 D Weather4x2_optimus: forecast size is 0
06-30 12:52:00.072  2844  2844 D Theme   : strTheme: com.lge.launcher2.theme.optimus
06-30 12:52:00.072  2844  2844 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
06-30 12:52:00.072  2844  2844 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
06-30 12:52:00.073  2844  2844 D Theme   : strTheme: com.lge.launcher2.theme.optimus
06-30 12:52:00.073  2844  2844 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
06-30 12:52:00.073  2844  2844 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
06-30 12:52:00.073  2844  2844 D Theme   : strTheme: com.lge.launcher2.theme.optimus
06-30 12:52:00.073  2844  2844 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
06-30 12:52:00.073  2844  2844 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
06-30 12:52:00.073  2844  2844 I Theme_WeatherAncestor_optimus: WEATHER_CP_ACCU : 
06-30 12:52:00.073  2844  2844 I Theme_WeatherAncestor_optimus: weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
06-30 12:52:00.073  2844  2844 D Theme   : strTheme: com.lge.launcher2.theme.optimus
06-30 12:52:00.073  2844  2844 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
,06-30 12:52:00.073  2844  2844 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
06-30 12:52:00.074  2844  2844 D Theme_WeatherAncestor_optimus: setTouchIntent, appWidgetId: 2
06-30 12:52:00.075  2844  2844 D Theme_WeatherAncestor_optimus: url is : null
06-30 12:52:00.085  2844  2844 D Theme   : strTheme: com.lge.launcher2.theme.optimus
06-30 12:52:00.085  2844  2844 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
06-30 12:52:00.085  2844  2844 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
06-30 12:52:00.086  2844  2844 D WeatherAncestor: 2 : update view, appWidgetId: 2
,06-30 12:52:00.092  2844  2844 D WeatherService: 2 : TimeTick Intent has been processed, Time(hour:min:sec) 12:52:0
06-30 12:52:00.103   857   857 D PowerManagerServiceEx: releaseWakeLockInternal: lock=549011905 [*alarm*], flags=0x0
,06-30 12:52:00.215  1950  1950 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,06-30 12:52:00.296  1950  1950 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,06-30 12:52:01.354   291   352 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 12:52:01.577  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-30 12:52:01.577  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 12:52:01.577  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,06-30 12:52:02.576  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-30 12:52:02.577  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 12:52:02.577  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,06-30 12:52:03.579  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-30 12:52:03.579  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 12:52:03.579  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,06-30 12:52:03.667   857  1056 I PowerManagerService: ALS enabled for SRE
06-30 12:52:03.667   857  1056 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (25614 ms ago)
,06-30 12:52:03.694   857  1349 D qdlights: set_light_backlight: 254
,06-30 12:52:03.706   857  1349 D qdlights: set_light_backlight: 250
,06-30 12:52:03.723   857  1349 D qdlights: set_light_backlight: 247
,06-30 12:52:03.740   857  1349 D qdlights: set_light_backlight: 244
,06-30 12:52:03.756   857  1349 D qdlights: set_light_backlight: 240
,06-30 12:52:03.773   857  1349 D qdlights: set_light_backlight: 237
,06-30 12:52:03.790   857  1349 D qdlights: set_light_backlight: 234
06-30 12:52:03.806   857  1349 D qdlights: set_light_backlight: 230
,06-30 12:52:03.823   857  1349 D qdlights: set_light_backlight: 227
,06-30 12:52:03.840   857  1349 D qdlights: set_light_backlight: 224
06-30 12:52:03.856   857  1349 D qdlights: set_light_backlight: 220
,06-30 12:52:03.873   857  1349 D qdlights: set_light_backlight: 217
,06-30 12:52:03.890   857  1349 D qdlights: set_light_backlight: 214
,06-30 12:52:03.906   857  1349 D qdlights: set_light_backlight: 210
,06-30 12:52:03.923   857  1349 D qdlights: set_light_backlight: 207
,06-30 12:52:03.940   857  1349 D qdlights: set_light_backlight: 204
,06-30 12:52:03.956   857  1349 D qdlights: set_light_backlight: 200
,06-30 12:52:03.973   857  1349 D qdlights: set_light_backlight: 197
,06-30 12:52:03.990   857  1349 D qdlights: set_light_backlight: 194
,06-30 12:52:04.007   857  1349 D qdlights: set_light_backlight: 190
,06-30 12:52:04.023   857  1349 D qdlights: set_light_backlight: 187
,06-30 12:52:04.040   857  1349 D qdlights: set_light_backlight: 184
,06-30 12:52:04.057   857  1349 D qdlights: set_light_backlight: 180
,06-30 12:52:04.073   857  1349 D qdlights: set_light_backlight: 177
,06-30 12:52:04.090   857  1349 D qdlights: set_light_backlight: 174
,06-30 12:52:04.107   857  1349 D qdlights: set_light_backlight: 170
,06-30 12:52:04.123   857  1349 D qdlights: set_light_backlight: 167
,06-30 12:52:04.140   857  1349 D qdlights: set_light_backlight: 164
,06-30 12:52:04.157   857  1349 D qdlights: set_light_backlight: 160
,06-30 12:52:04.173   857  1349 D qdlights: set_light_backlight: 157
,06-30 12:52:04.190   857  1349 D qdlights: set_light_backlight: 154
,06-30 12:52:04.206   857  1349 D qdlights: set_light_backlight: 150
,06-30 12:52:04.223   857  1349 D qdlights: set_light_backlight: 147
,06-30 12:52:04.240   857  1349 D qdlights: set_light_backlight: 144
,06-30 12:52:04.256   857  1349 D qdlights: set_light_backlight: 140
,06-30 12:52:04.273   857  1349 D qdlights: set_light_backlight: 137
,06-30 12:52:04.290   857  1349 D qdlights: set_light_backlight: 134
,06-30 12:52:04.306   857  1349 D qdlights: set_light_backlight: 130
,06-30 12:52:04.323   857  1349 D qdlights: set_light_backlight: 127
,06-30 12:52:04.340   857  1349 D qdlights: set_light_backlight: 124
,06-30 12:52:04.356   857  1349 D qdlights: set_light_backlight: 120
,06-30 12:52:04.373   857  1349 D qdlights: set_light_backlight: 117
,06-30 12:52:04.390   857  1349 D qdlights: set_light_backlight: 114
,06-30 12:52:04.406   857  1349 D qdlights: set_light_backlight: 110
,06-30 12:52:04.423   857  1349 D qdlights: set_light_backlight: 107
,06-30 12:52:04.440   857  1349 D qdlights: set_light_backlight: 104
,06-30 12:52:04.456   857  1349 D qdlights: set_light_backlight: 100
,06-30 12:52:04.473   857  1349 D qdlights: set_light_backlight: 97
,06-30 12:52:04.490   857  1349 D qdlights: set_light_backlight: 94
,06-30 12:52:04.506   857  1349 D qdlights: set_light_backlight: 90
,06-30 12:52:04.523   857  1349 D qdlights: set_light_backlight: 87
,06-30 12:52:04.540   857  1349 D qdlights: set_light_backlight: 84
06-30 12:52:04.557   857  1349 D qdlights: set_light_backlight: 80
,06-30 12:52:04.573   857  1349 D qdlights: set_light_backlight: 77
,06-30 12:52:04.593   857  1349 D qdlights: set_light_backlight: 74
,06-30 12:52:04.606   857  1349 D qdlights: set_light_backlight: 70
,06-30 12:52:04.623   857  1349 D qdlights: set_light_backlight: 67
,06-30 12:52:04.640   857  1349 D qdlights: set_light_backlight: 64
,06-30 12:52:04.656   857  1349 D qdlights: set_light_backlight: 60
,06-30 12:52:04.673   857  1349 D qdlights: set_light_backlight: 57
,06-30 12:52:04.690   857  1349 D qdlights: set_light_backlight: 54
,06-30 12:52:04.707   857  1349 D qdlights: set_light_backlight: 50
,06-30 12:52:04.723   857  1349 D qdlights: set_light_backlight: 47
,06-30 12:52:04.740   857  1349 D qdlights: set_light_backlight: 44
,06-30 12:52:04.756   857  1349 D qdlights: set_light_backlight: 40
,06-30 12:52:04.773   857  1349 D qdlights: set_light_backlight: 37
,06-30 12:52:04.790   857  1349 D qdlights: set_light_backlight: 34
,06-30 12:52:04.806   857  1349 D qdlights: set_light_backlight: 30
,06-30 12:52:04.823   857  1349 D qdlights: set_light_backlight: 27
,06-30 12:52:04.840   857  1349 D qdlights: set_light_backlight: 24
,06-30 12:52:04.857   857  1349 D qdlights: set_light_backlight: 20
,06-30 12:52:04.873   857  1349 D qdlights: set_light_backlight: 17
,06-30 12:52:04.890   857  1349 D qdlights: set_light_backlight: 14
,06-30 12:52:04.907   857  1349 D qdlights: set_light_backlight: 10
,06-30 12:52:05.582  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-30 12:52:05.582  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 12:52:05.582  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,06-30 12:52:06.359   291   352 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 12:52:06.584  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-30 12:52:06.584  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 12:52:06.584  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,06-30 12:52:08.588  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-30 12:52:08.588  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 12:52:08.588  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,06-30 12:52:09.418  6556  6637 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
06-30 12:52:09.418  6556  6637 I jxcore-log: 
,06-30 12:52:09.423  6556  6637 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
06-30 12:52:09.423  6556  6637 I jxcore-log: 
06-30 12:52:09.427  2077  3456 D BluetoothAdapterService(124989665): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@110e3dbf
06-30 12:52:09.427  6556  6637 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 12:52:09.427  6556  6637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 12:52:09.427  6556  6637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 12:52:09.427  6556  6637 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 12:52:09.427  6556  6637 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 12:52:09.427  6556  6637 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-30 12:52:09.427  6556  6637 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-30 12:52:09.427  6556  6637 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-30 12:52:09.430  2077  2095 D BluetoothAdapterService(124989665): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@110e3dbf
06-30 12:52:09.431  6556  6637 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
06-30 12:52:09.434  6556  6637 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
06-30 12:52:09.434  6556  6637 I jxcore-log: 
,06-30 12:52:09.437  6556  6637 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
06-30 12:52:09.437  6556  6637 I jxcore-log: 
06-30 12:52:09.590  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-30 12:52:09.590  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 12:52:09.590  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,06-30 12:52:09.965  6556  6637 I jxcore-log: Unit Test app is loaded
06-30 12:52:09.965  6556  6637 I jxcore-log: 
,06-30 12:52:09.974  6556  6637 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
06-30 12:52:09.974  6556  6637 I jxcore-log: 
06-30 12:52:09.979  6556  6637 I jxcore-log: My device name is: LGE-LG-D722
06-30 12:52:09.979  6556  6637 I jxcore-log: 
06-30 12:52:09.982  6556  6556 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
06-30 12:52:09.982  6556  6637 I jxcore-log: WARN testUtils: myNameCallback not set!
06-30 12:52:09.982  6556  6637 I jxcore-log: 
,06-30 12:52:10.331   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 12:52:10.331   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 12:52:10.331   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 152276729216; DSPS: 5081368; Offset : -2803185833
,06-30 12:52:10.592  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-30 12:52:10.592  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 12:52:10.593  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,06-30 12:52:10.664   857  1056 I PowerManagerService: ALS enabled for SRE
06-30 12:52:10.664   857  1056 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (32610 ms ago)
,06-30 12:52:10.670   857  1056 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
06-30 12:52:10.680   857  1056 I PowerManagerService: ALS enabled for SRE
06-30 12:52:10.680   857  1056 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (32626 ms ago)
,06-30 12:52:10.687   857  1056 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
06-30 12:52:10.692   857  1056 I PowerManagerService: Sleeping (uid 1000)...
06-30 12:52:10.692   857  1056 D LPWGController: [updateScreenState] screen on = false
,06-30 12:52:10.699   857  1056 D LPWGController: disable proximity sensor
06-30 12:52:10.699   857  1056 D LPWGController: enable proximity sensor
06-30 12:52:10.707   857  1056 I SensorManager: registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@3d2ffd66] by com.android.server.power.ProximitySensorListener.enable():120
,06-30 12:52:10.719   857  1056 I sensors_hal_Ctx: batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
06-30 12:52:10.719   857  1056 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
06-30 12:52:10.719   857  1056 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
06-30 12:52:10.719   857  1056 I sensors_hal_Ctx: activate: handle is 48, enable
,06-30 12:52:10.720   857  1056 V sensors_hal_Ctx: activate sensors is 1400000000000
06-30 12:52:10.720   857  1056 D sensors_hal_Thresh: enable: handle=48
06-30 12:52:10.720   857  1056 I sensors_hal_SAM: sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
06-30 12:52:10.721   857  1056 D sensors_hal_Util: waitForResponse: timeout=1000
06-30 12:52:10.726   857  1012 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
06-30 12:52:10.726   857  1012 D sensors_hal_Thresh: processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
06-30 12:52:10.726   857  1056 D sensors_hal_Thresh: enable: Received response: 0
06-30 12:52:10.727   857  1056 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (32673 ms ago)
06-30 12:52:10.741   857  1056 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 12:52:10.741   857  1056 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 12:52:10.741   857  1056 I Adreno-EGL: Build Date: 03/02/15 Mon
06-30 12:52:10.741   857  1056 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
06-30 12:52:10.741   857  1056 I Adreno-EGL: Remote Branch: 
06-30 12:52:10.741   857  1056 I Adreno-EGL: Local Patches: 
06-30 12:52:10.741   857  1056 I Adreno-EGL: Reconstruct Branch: 
,06-30 12:52:10.769   244   283 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1088 us)
,06-30 12:52:10.954   435  1001 I Sensors : sns_pwr.c(273):acquiring wakelock
06-30 12:52:10.955   857  1012 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,06-30 12:52:10.959   857  1012 I sensors_hal_SAM: SAMSensor_sensor1_cb: acquired wakelock sensor_ind
06-30 12:52:10.959   857  1012 D sensors_hal_Thresh: processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
06-30 12:52:10.959   857  1012 D sensors_hal_Thresh: processInd: handle 48, count=1
06-30 12:52:10.959   857  1012 V sensors_hal_Thresh: processInd:sensor android.sensor.proximity (wake_up)
06-30 12:52:10.959   857  1012 I sensors_hal_Thresh: processInd : proximity state changed - FAR
06-30 12:52:10.959   857  1057 D sensors_hal_Ctx: poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
06-30 12:52:10.960   857  1057 D sensors_hal_Ctx: poll: count: 256
06-30 12:52:10.960   857  1057 I sensors_hal_Ctx: poll: released wakelock sensor_ind
06-30 12:52:10.960   857  1057 D sensors_hal_Util: waitForResponse: timeout=0
06-30 12:52:10.962   857  1056 D LPWGController: proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
06-30 12:52:10.962   857  1056 I LPWGController: current mode = 1  value = 1 1
06-30 12:52:10.963   857  1056 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
06-30 12:52:11.067   857  1056 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,06-30 12:52:11.292   857  1349 D qdlights: set_light_backlight: 0
,06-30 12:52:11.314   857  1056 I SensorManager: removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,06-30 12:52:11.316   857  1056 I sensors_hal_Ctx: activate: handle is 46, disable
06-30 12:52:11.316   857  1056 V sensors_hal_Ctx: activate sensors is 1000000000000
06-30 12:52:11.317   857  1056 D sensors_hal_LP2: enable: handle=46
06-30 12:52:11.317   857  1056 D sensors_hal_LP2: enable: Disabling sensor handle=46
06-30 12:52:11.317   857  1056 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
06-30 12:52:11.319   244   244 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
06-30 12:52:11.319   244   244 D qdhwcomposer: hwc_blank: Blanking display: 0
06-30 12:52:11.324   857  1054 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
06-30 12:52:11.324   857   857 V ActivityManager: Display changed displayId=0
,06-30 12:52:11.364   291   352 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 12:52:11.366   857  1038 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
06-30 12:52:11.366   857  1038 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
06-30 12:52:11.373  1824  1824 D DSDPConnection: Display #0 changed.
,06-30 12:52:11.558   244   244 D qdhwcomposer: hwc_blank: Done blanking display: 0
06-30 12:52:11.559   857  1349 D SurfaceControl: Excessive delay in setPowerMode(): 239ms
,06-30 12:52:11.561   244   702 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
06-30 12:52:11.561   857  1349 I QCOM PowerHAL: Got set_interactive hint
06-30 12:52:11.578  1379  1406 D KeyguardViewMediator: onScreenTurnedOff(3)
,06-30 12:52:11.586  6556  6556 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
06-30 12:52:11.586  6556  6556 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
06-30 12:52:11.588  1332  1347 D SmartCoverViewMediator: onScreenTurnedOff(3)
06-30 12:52:11.600  1379  1406 D KeyguardViewMediator: notifyScreenOffLocked
,06-30 12:52:11.606  1332  1347 D SmartCoverViewMediator: notifyScreenOffLocked
06-30 12:52:11.608  6556  6556 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3bc81b19 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@17f37014, 16908290=android.view.AbsSavedState$1@17f37014}, android:focusedViewId=100}]}]
06-30 12:52:11.608  6556  6556 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
06-30 12:52:11.608  6556  6556 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
06-30 12:52:11.608  6556  6556 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
06-30 12:52:11.612  1332  1332 D SmartCoverViewMediator: handleNotifyScreenOFF
,06-30 12:52:11.620  1379  1406 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1, timeout = 5000
06-30 12:52:11.620  1379  1379 D KeyguardViewMediator: handleNotifyScreenOff
06-30 12:52:11.647  1379  1379 D ScreenTurnOffBySensor: unregisterProximitySensor
,06-30 12:52:11.654   857   857 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
06-30 12:52:11.659   276  1303 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 857
06-30 12:52:11.659  1379  1379 D StatusBarWindowView: onScreenTurnedOff why = 3
,06-30 12:52:11.660   276  1303 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
06-30 12:52:11.660   276  1303 V voice   : voice_set_parameters: enter: screen_state=on
06-30 12:52:11.662   276  1303 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
06-30 12:52:11.662   276  1303 V compress_voip: voice_extn_compress_voip_set_parameters: exit
06-30 12:52:11.662   276  1303 V voice   : voice_set_parameters: exit with code(0)
06-30 12:52:11.662   276  1303 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
06-30 12:52:11.662   276  1303 V msm8974_platform: platform_set_parameters: enter: screen_state=on
06-30 12:52:11.662   276  1303 V msm8974_platform: platform_set_parameters: exit with code(0)
06-30 12:52:11.662   276  1303 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
06-30 12:52:11.662   276  1303 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
06-30 12:52:11.662   276  1303 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
06-30 12:52:11.662   276  1303 V audio_hw_primary: adev_set_parameters: exit with code(0)
06-30 12:52:11.665  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
06-30 12:52:11.665  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
06-30 12:52:11.665  1379  1379 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
06-30 12:52:11.675   857  1311 I WifiServerServiceExt: set CMD_KT_SCAN_INTERVAL
,06-30 12:52:11.683  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 12:52:11.685  1379  1379 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
06-30 12:52:12.141   857   892 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,06-30 12:52:12.187   857  2202 D SplitWindow: check instance of lgWin Window{22d738fd u0 SearchPanel}
06-30 12:52:12.195  1912  1912 I QCNEJ   : |CORE| sendScreenState: state:true
06-30 12:52:12.202  1876  2050 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
,06-30 12:52:12.205  1876  2050 D LEDService: stopPatternFlashing()
06-30 12:52:12.206  1876  2050 D qdlights: set_light_notifications: 0,0,0,0,3
06-30 12:52:12.207  1876  2050 I LEDService: getCurrentHighestLGLedRecord : size = 1
06-30 12:52:12.207  1876  2050 D qdlights: set_light_notifications: 0,0,0,0,3
06-30 12:52:12.209  1876  2050 I LEDService: updateLightsLocked : turn off led
06-30 12:52:12.209  1876  2050 D qdlights: set_light_notifications: 0,0,0,0,3
06-30 12:52:12.212  1876  2050 D LEDHandler: RESTART MSG
06-30 12:52:12.219   857  2033 D InputDispatcher: Window went away: Window{1ba8834f u0 SearchPanel}
,06-30 12:52:12.224  1379  1379 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
06-30 12:52:12.242  1379  1379 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,06-30 12:52:12.251  1876  1876 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
06-30 12:52:12.252  1876  1876 D Cliptray Service: lockStatus = 0
06-30 12:52:12.266  1859  1859 D LNfcService: action : android.intent.action.SCREEN_ON
,06-30 12:52:12.275  1859  6729 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
06-30 12:52:12.275  1859  6729 D NfcServiceNXP: Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
06-30 12:52:12.275  1859  6729 D LNfcService: isRequireNfcCRouting() return true
06-30 12:52:12.276  1859  6729 D LNfcService: isHCERoutingtoHost() return : true
06-30 12:52:12.276  1859  6729 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
06-30 12:52:12.276  1859  6729 D NfcService: mEnableLPD: true
06-30 12:52:12.276  1859  6729 D NfcService: mEnableReader: false
06-30 12:52:12.276  1859  6729 D NfcService: mEnableHostRouting: true
06-30 12:52:12.276  1859  6729 D NfcService: newParams.techmask= mTechMask: default
06-30 12:52:12.276  1859  6729 D NfcService: mEnableLPD: true
06-30 12:52:12.276  1859  6729 D NfcService: mEnableReader: false
06-30 12:52:12.276  1859  6729 D NfcService: mEnableHostRouting: true
06-30 12:52:12.276  1859  6729 D NfcService: screenState= 3
06-30 12:52:12.276  1859  6729 D NfcService: Discovery configuration equal, not updating.
06-30 12:52:12.283   857   857 D Ulp_jni : JNI:system_update. Event-0
,06-30 12:52:12.303  1824  1824 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
06-30 12:52:12.320   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 12:52:12.320   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 12:52:12.321   857   857 D WifiOffDelayIfNotUsed: ACTION_SCREEN_ON
,06-30 12:52:12.325  2844  2844 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:52:12
06-30 12:52:12.327  2844  2844 D WeatherService: 2 : ACTION screen on
06-30 12:52:12.329  2844  2844 D WeatherService: 2 : shouldTimeTickRegistered : false
06-30 12:52:12.335  2844  2844 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
06-30 12:52:12.335  2844  2844 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:52:12
,06-30 12:52:12.345  4117  4117 D AppCleanupService: android.intent.action.SCREEN_ON
,06-30 12:52:12.378   276  1641 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 857
06-30 12:52:12.378   276  1641 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
06-30 12:52:12.378   276  1641 V voice   : voice_set_parameters: enter: screen_state=off
06-30 12:52:12.378   276  1641 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
06-30 12:52:12.378   276  1641 V compress_voip: voice_extn_compress_voip_set_parameters: exit
06-30 12:52:12.378   276  1641 V voice   : voice_set_parameters: exit with code(0)
06-30 12:52:12.378   276  1641 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
06-30 12:52:12.378   276  1641 V msm8974_platform: platform_set_parameters: enter: screen_state=off
06-30 12:52:12.378   276  1641 V msm8974_platform: platform_set_parameters: exit with code(0)
06-30 12:52:12.378   276  1641 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
06-30 12:52:12.378   276  1641 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
06-30 12:52:12.378   276  1641 V audio_hw_primary: adev_set_parameters: exit with code(0)
06-30 12:52:12.380   857  1316 D WifiController: CMD_SCREEN_OFF 
06-30 12:52:12.380   857  1316 D WifiController: shouldWifiStayAwake TRUE
06-30 12:52:12.384  1379  1379 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
,06-30 12:52:12.387   857   892 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,06-30 12:52:12.406  1912  1912 I QCNEJ   : |CORE| sendScreenState: state:false
06-30 12:52:12.408  1876  2050 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
06-30 12:52:12.408  1876  2050 D LEDService: stopPatternFlashing()
06-30 12:52:12.408  1876  2050 D qdlights: set_light_notifications: 0,0,0,0,3
06-30 12:52:12.410  1876  2050 I LEDService: getCurrentHighestLGLedRecord : size = 1
06-30 12:52:12.410  1876  2050 D qdlights: set_light_notifications: 0,0,0,0,3
06-30 12:52:12.411  1876  2050 I LEDService: updateLightsLocked : turn on led
06-30 12:52:12.414  1876  2050 E LEDService: parsePattern()::Unknown Pattern ID or invalid PatternFilePath
06-30 12:52:12.414  1876  2050 E LEDService: Can't handle this request of patternId:0
06-30 12:52:12.414  1876  2050 D LEDHandler: RESTART MSG
06-30 12:52:12.417  1876  1876 D VolumeVibrator: clear
06-30 12:52:12.418  1876  1876 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
06-30 12:52:12.418  1859  1859 D LNfcService: action : android.intent.action.SCREEN_OFF
,06-30 12:52:12.422  1859  2236 D NfcServiceNXP: mScreenState : 1, mInProvisionMode : false
06-30 12:52:12.435  1950  1950 I [LGHome]EVENT: [Launcher.java:1711:onReceive()]Screen Off
,06-30 12:52:12.449  1824  1824 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,06-30 12:52:12.454   435   451 I Sensors : sns_pwr.c(301):releasing wakelock
06-30 12:52:12.455   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 12:52:12.456   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 12:52:12.456   857   857 D WifiOffDelayIfNotUsed: ACTION_SCREEN_OFF
06-30 12:52:12.457  2844  2844 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:52:12
06-30 12:52:12.457  2844  2844 D WeatherService: 2 : ACTION screen off
06-30 12:52:12.459  2844  2844 D WeatherService: 2 : TimeTick Receiver Unregister
06-30 12:52:12.459  2844  2844 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:52:12
06-30 12:52:12.467  4117  4117 D AppCleanupService: android.intent.action.SCREEN_OFF
,06-30 12:52:12.469  4117  6741 D AppCleanupService: AppUsageStatsSaveTask
,06-30 12:52:12.512  1859  2733 E NxpNfcJni: getReconnectState = 0x0
,06-30 12:52:12.516  1859  2236 D LCardEmulationManager: getHceAppCount hostAppNum : 0
06-30 12:52:12.516  1859  2236 D LCardEmulationManager: getDefaultRoute
06-30 12:52:12.517  1859  2236 D LNfcService: isRequireNfcCRouting() return true
06-30 12:52:12.517  1859  2236 D LNfcService: isHCERoutingtoHost() return : true
06-30 12:52:12.517  1859  2236 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
06-30 12:52:12.517  1859  2236 D NfcService: mEnableLPD: true
06-30 12:52:12.517  1859  2236 D NfcService: mEnableReader: false
06-30 12:52:12.517  1859  2236 D NfcService: mEnableHostRouting: true
06-30 12:52:12.517  1859  2236 D NfcService: newParams.techmask= mTechMask: 0
06-30 12:52:12.517  1859  2236 D NfcService: mEnableLPD: true
06-30 12:52:12.517  1859  2236 D NfcService: mEnableReader: false
06-30 12:52:12.517  1859  2236 D NfcService: mEnableHostRouting: true
06-30 12:52:12.517  1859  2236 D NfcService: screenState= 1
06-30 12:52:12.577  1859  2733 E NxpNfcJni: getReconnectState = 0x0
,06-30 12:52:16.368   291   352 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 12:52:16.612   857  1289 V AlarmManager: ELAPSED_WAKEUP set : Alarm{39ae89f2 type 2 when 158549 com.android.systemui} when 158549
,06-30 12:52:16.613  1379  1379 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
06-30 12:52:16.629  1824  1841 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
06-30 12:52:16.633  1824  1841 D PhoneUtils: getPhoneCount() sPhoneCount = 1
06-30 12:52:16.633  1824  1841 D PhoneUtils: getPhoneCount() sPhoneCount = 1
06-30 12:52:16.642  1824  1841 V TelecomServiceImpl: getCallState : 0
,06-30 12:52:16.644  1824  1840 D PhoneUtils: getSubIdUsingSlotId() slotId:0 -> subId:-1
06-30 12:52:16.644  1824  1840 D PhoneUtils: getPhoneCount() sPhoneCount = 1
06-30 12:52:16.644  1824  1840 D PhoneUtils: getPhoneCount() sPhoneCount = 1
06-30 12:52:16.645  1379  1379 D KeyguardUpdateMonitor: isHdmiPluggedIn :false
06-30 12:52:16.653  1379  1379 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
06-30 12:52:16.699  6556  6637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
06-30 12:52:16.699  6556  6637 I jxcore-log: 
,06-30 12:52:17.313  6556  6637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
06-30 12:52:17.313  6556  6637 I jxcore-log: 
,06-30 12:52:17.351  6556  6637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
06-30 12:52:17.351  6556  6637 I jxcore-log: 
,06-30 12:52:17.358  6556  6637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
06-30 12:52:17.358  6556  6637 I jxcore-log: 
06-30 12:52:17.381  6556  6637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
06-30 12:52:17.381  6556  6637 I jxcore-log: 
,06-30 12:52:17.387  6556  6637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
06-30 12:52:17.387  6556  6637 I jxcore-log: 
06-30 12:52:20.569  6556  6637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
06-30 12:52:20.569  6556  6637 I jxcore-log: 
,06-30 12:52:20.593  6556  6637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
06-30 12:52:20.593  6556  6637 I jxcore-log: 
,06-30 12:52:20.606  6556  6637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
06-30 12:52:20.606  6556  6637 I jxcore-log: 
,06-30 12:52:20.849  6556  6637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
06-30 12:52:20.849  6556  6637 I jxcore-log: 
,06-30 12:52:20.976  6556  6637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
06-30 12:52:20.976  6556  6637 I jxcore-log: 
,06-30 12:52:21.068  6556  6637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
06-30 12:52:21.068  6556  6637 I jxcore-log: 
,06-30 12:52:21.078  6556  6637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
06-30 12:52:21.078  6556  6637 I jxcore-log: 
06-30 12:52:21.373   291   352 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 12:52:21.383  6556  6637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
06-30 12:52:21.383  6556  6637 I jxcore-log: 
06-30 12:52:21.415  6556  6637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
06-30 12:52:21.415  6556  6637 I jxcore-log: 
,06-30 12:52:21.422  6556  6637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
06-30 12:52:21.422  6556  6637 I jxcore-log: 
06-30 12:52:21.430  6556  6637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
06-30 12:52:21.430  6556  6637 I jxcore-log: 
,06-30 12:52:21.454  6556  6637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
06-30 12:52:21.454  6556  6637 I jxcore-log: 
,06-30 12:52:21.484  6556  6637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
06-30 12:52:21.484  6556  6637 I jxcore-log: 
,06-30 12:52:21.617  6556  6637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
06-30 12:52:21.617  6556  6637 I jxcore-log: 
,06-30 12:52:21.625  6556  6637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
06-30 12:52:21.625  6556  6637 I jxcore-log: 
06-30 12:52:21.664  6556  6637 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
06-30 12:52:21.664  6556  6637 I jxcore-log: 
,06-30 12:52:21.678  2077  3456 D BluetoothAdapterService(124989665): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@110e3dbf
,06-30 12:52:21.679  6556  6637 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
06-30 12:52:21.683  6556  6637 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
06-30 12:52:21.683  6556  6637 I jxcore-log: 
06-30 12:52:26.378   291   352 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 12:52:30.331   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 12:52:30.331   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 12:52:30.331   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 172277498949; DSPS: 5736754; Offset : -2803209479
,06-30 12:52:31.382   291   352 I ThermalEngine: Sensor:pa_therm0:33000 mC
,06-30 12:52:36.387   291   352 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 12:52:41.391   291   352 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 12:52:42.480   857  1289 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2084a843 type 2 when 184414 com.google.android.gms} when 184414
,06-30 12:52:44.780  2386  3417 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 12:52:45.316   486   486 D charger_monitor: init target 500000
,06-30 12:52:45.323   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 12:52:45.326  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 12:52:45.326  1379  1379 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 12:52:45.326  1379  1379 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 12:52:45.326  1379  1379 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 12:52:45.327  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 12:52:45.362  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
,06-30 12:52:45.366  1912  1912 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 12:52:45.367  1876  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 12:52:45.367  1876  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 12:52:45.367  1876  2050 D LEDHandler: Battery Temp: 300, mChargingStatus=5, mChargingStop=false
06-30 12:52:45.367  2077  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 12:52:45.368  1912  1912 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 12:52:45.370  1379  1379 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 12:52:45.370  1379  1379 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 300
06-30 12:52:45.379   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 12:52:45.379   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 12:52:45.382   857  1316 D WifiController: battery changed pluggedType: 2
06-30 12:52:45.383  1379  1379 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 12:52:45.388  6414  6414 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
06-30 12:52:46.396   291   352 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 12:52:50.332   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 12:52:50.332   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 12:52:50.332   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 192278193785; DSPS: 6392136; Offset : -2803186134
,06-30 12:52:50.603  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,06-30 12:52:50.606  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 12:52:50.606  1379  1379 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 12:52:50.606  1379  1379 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 12:52:50.606  1379  1379 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 12:52:50.630   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 12:52:50.664   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 12:52:50.668  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 12:52:50.668  1379  1379 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 12:52:50.668  1379  1379 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 12:52:50.668  1379  1379 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 12:52:50.673  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 12:52:50.743  2077  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-30 12:52:50.747  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
06-30 12:52:50.747  1379  1379 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 12:52:50.747  1379  1379 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 300
06-30 12:52:50.748  1912  1912 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 12:52:50.748  1912  1912 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 12:52:50.749  1876  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 12:52:50.749  1876  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 12:52:50.749  1876  2050 D LEDHandler: Battery Temp: 300, mChargingStatus=5, mChargingStop=false
06-30 12:52:50.752  1379  1379 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 12:52:50.754   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 12:52:50.754   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 12:52:50.755   857  1316 D WifiController: battery changed pluggedType: 2
,06-30 12:52:50.760  6414  6414 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
06-30 12:52:50.794  2077  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-30 12:52:50.797  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
06-30 12:52:50.797  1379  1379 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 12:52:50.797  1379  1379 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 300
06-30 12:52:50.798  1912  1912 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 12:52:50.798  1912  1912 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 12:52:50.799  1876  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 12:52:50.800  1876  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 12:52:50.800  1876  2050 D LEDHandler: Battery Temp: 300, mChargingStatus=5, mChargingStop=false
06-30 12:52:50.805   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 12:52:50.805   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 12:52:50.806   857  1316 D WifiController: battery changed pluggedType: 2
,06-30 12:52:50.809  1379  1379 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 12:52:50.810  6414  6414 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
06-30 12:52:51.401   291   352 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 12:52:52.641   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 12:52:52.649  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 12:52:52.649  1379  1379 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 12:52:52.649  1379  1379 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 12:52:52.649  1379  1379 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 12:52:52.651  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 12:52:56.405   291   352 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 12:53:00.043  1379  1379 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 12:53:00.043  1379  1379 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 12:53:00.043  1379  1379 I [SystemUI]Clock: called onTimeUpdated()
,06-30 12:53:00.047  1379  1379 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 12:53:00.047  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 12:53:00.048  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 12:53:00.049  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 12:53:01.410   291   352 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 12:53:06.414   291   352 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 12:53:10.333   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 12:53:10.333   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 12:53:10.333   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 212278895340; DSPS: 7047519; Offset : -2803186430
,06-30 12:53:11.419   291   352 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 12:53:16.423   291   352 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 12:53:21.428   291   352 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 12:53:24.548   857  1289 D PowerManagerServiceEx: acquireWakeLockInternal: lock=549011905, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=857
,06-30 12:53:24.552   857  1289 V AlarmManager: ELAPSED_WAKEUP set : Alarm{2a923ec0 type 2 when 210873 android} when 210873
06-30 12:53:24.692   857   857 D PowerManagerServiceEx: releaseWakeLockInternal: lock=549011905 [*alarm*], flags=0x0
,06-30 12:53:26.433   291   352 I ThermalEngine: Sensor:pa_therm0:32000 mC
,06-30 12:53:30.333   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 12:53:30.334   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 12:53:30.334   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 232279664030; DSPS: 7702905; Offset : -2803211198
,06-30 12:53:31.437   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:53:36.442   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:53:41.446   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:53:45.474   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 12:53:45.478  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 12:53:45.478  1379  1379 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 12:53:45.478  1379  1379 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 12:53:45.478  1379  1379 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 12:53:45.479  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 12:53:45.516  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 298
06-30 12:53:45.516  1379  1379 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 12:53:45.516  1379  1379 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 298
,06-30 12:53:45.519  1912  1912 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 12:53:45.519  1912  1912 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 12:53:45.520  1876  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 12:53:45.520  1876  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 12:53:45.520  1876  2050 D LEDHandler: Battery Temp: 298, mChargingStatus=5, mChargingStop=false
06-30 12:53:45.523  2077  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 12:53:45.526   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 12:53:45.526   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 12:53:45.527   857  1316 D WifiController: battery changed pluggedType: 2
06-30 12:53:45.528  1379  1379 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,06-30 12:53:45.531  6414  6414 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
06-30 12:53:46.451   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:53:50.335   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 12:53:50.335   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 12:53:50.335   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 252280793814; DSPS: 8358302; Offset : -2803210747
,06-30 12:53:51.455   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:53:56.460   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:54:00.039  1379  1379 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 12:54:00.039  1379  1379 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 12:54:00.039  1379  1379 I [SystemUI]Clock: called onTimeUpdated()
,06-30 12:54:00.043  1379  1379 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 12:54:00.043  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 12:54:00.044  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 12:54:00.045  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 12:54:01.464   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:54:06.469   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:54:10.335   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 12:54:10.335   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 12:54:10.335   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 272281503651; DSPS: 9013685; Offset : -2803202449
,06-30 12:54:11.474   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:54:16.478   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:54:21.483   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:54:26.487   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:54:30.336   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 12:54:30.336   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 12:54:30.336   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 292282216403; DSPS: 9669068; Offset : -2803191836
,06-30 12:54:31.492   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:54:36.496   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:54:41.501   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:54:45.634   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 12:54:45.638  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 12:54:45.638  1379  1379 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 12:54:45.638  1379  1379 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 12:54:45.638  1379  1379 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 12:54:45.639  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 12:54:45.676  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 297
06-30 12:54:45.676  1379  1379 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 12:54:45.676  1379  1379 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 297
,06-30 12:54:45.679  1912  1912 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 12:54:45.679  1912  1912 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 12:54:45.680  1876  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 12:54:45.680  1876  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 12:54:45.680  1876  2050 D LEDHandler: Battery Temp: 297, mChargingStatus=5, mChargingStop=false
06-30 12:54:45.682  1379  1379 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 12:54:45.684  2077  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 12:54:45.686   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 12:54:45.686   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 12:54:45.687   857  1316 D WifiController: battery changed pluggedType: 2
06-30 12:54:45.688  6414  6414 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,06-30 12:54:46.506   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:54:50.337   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 12:54:50.337   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 12:54:50.337   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 312283064885; DSPS: 10324456; Offset : -2803197612
,06-30 12:54:51.510   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:54:56.515   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:55:00.039  1379  1379 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 12:55:00.039  1379  1379 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 12:55:00.039  1379  1379 I [SystemUI]Clock: called onTimeUpdated()
,06-30 12:55:00.043  1379  1379 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 12:55:00.043  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 12:55:00.044  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 12:55:00.045  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 12:55:01.519   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:55:06.524   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:55:10.338   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 12:55:10.338   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 12:55:10.338   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 332283832690; DSPS: 10979841; Offset : -2803193032
,06-30 12:55:11.528   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:55:16.533   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:55:19.413   857  3171 I LocationManagerService: remove fc6da9d
,06-30 12:55:19.416   857  3171 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
06-30 12:55:19.417   857  3171 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-30 12:55:19.417   857  3171 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
06-30 12:55:19.419   857  3171 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
06-30 12:55:19.421   857  3171 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,06-30 12:55:20.220  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 12:55:20.220  1379  1379 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 12:55:20.221  1379  1379 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 12:55:20.221  1379  1379 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 12:55:20.223  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 12:55:20.239   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 12:55:20.275  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
06-30 12:55:20.275  1379  1379 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 12:55:20.276  1379  1379 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
,06-30 12:55:20.278  1912  1912 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 12:55:20.278  1912  1912 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 12:55:20.279  1876  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 12:55:20.279  1876  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 12:55:20.279  1876  2050 D LEDHandler: Battery Temp: 296, mChargingStatus=5, mChargingStop=false
06-30 12:55:20.283  2077  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 12:55:20.286   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 12:55:20.286   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 12:55:20.287   857  1316 D WifiController: battery changed pluggedType: 2
06-30 12:55:20.288  6414  6414 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,06-30 12:55:20.291  1379  1379 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 12:55:20.327  2077  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-30 12:55:20.330  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
06-30 12:55:20.330  1379  1379 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 12:55:20.330  1379  1379 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
06-30 12:55:20.331  1912  1912 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 12:55:20.332  1912  1912 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 12:55:20.333  1876  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 12:55:20.333  1876  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 12:55:20.333  1876  2050 D LEDHandler: Battery Temp: 296, mChargingStatus=5, mChargingStop=false
06-30 12:55:20.336  1379  1379 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 12:55:20.340   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 12:55:20.340   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 12:55:20.344   857  1316 D WifiController: battery changed pluggedType: 2
06-30 12:55:20.345  6414  6414 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
06-30 12:55:21.544   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:55:26.549   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:55:30.344   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 12:55:30.344   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 12:55:30.344   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 352289993255; DSPS: 11635403; Offset : -2803198633
,06-30 12:55:31.553   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:55:36.558   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:55:41.562   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:55:45.796  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 12:55:45.796  1379  1379 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 12:55:45.796  1379  1379 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 12:55:45.796  1379  1379 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 12:55:45.799  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 12:55:45.800   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 12:55:46.567   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:55:50.344   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 12:55:50.345   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 12:55:50.345   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 372290746113; DSPS: 12290788; Offset : -2803207073
,06-30 12:55:51.572   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:55:56.576   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:56:00.039  1379  1379 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 12:56:00.039  1379  1379 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 12:56:00.039  1379  1379 I [SystemUI]Clock: called onTimeUpdated()
,06-30 12:56:00.043  1379  1379 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 12:56:00.044  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 12:56:00.045  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 12:56:00.045  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 12:56:01.581   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:56:06.585   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:56:10.345   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 12:56:10.345   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 12:56:10.345   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 392291459334; DSPS: 12946171; Offset : -2803195601
,06-30 12:56:11.590   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:56:16.594   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:56:21.599   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:56:26.604   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:56:30.346   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 12:56:30.346   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 12:56:30.346   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 412292175368; DSPS: 13601555; Offset : -2803212093
,06-30 12:56:31.608   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:56:36.613   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:56:41.617   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:56:45.983  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,06-30 12:56:45.986   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 12:56:45.986  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 12:56:45.986  1379  1379 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 12:56:45.987  1379  1379 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 12:56:45.987  1379  1379 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 12:56:46.020  2077  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-30 12:56:46.024  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
06-30 12:56:46.024  1379  1379 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 12:56:46.024  1379  1379 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
06-30 12:56:46.025  1912  1912 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 12:56:46.026  1912  1912 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 12:56:46.027  1876  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 12:56:46.027  1876  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 12:56:46.027  1876  2050 D LEDHandler: Battery Temp: 295, mChargingStatus=5, mChargingStop=false
06-30 12:56:46.029  1379  1379 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 12:56:46.034   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 12:56:46.034   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,06-30 12:56:46.037   857  1316 D WifiController: battery changed pluggedType: 2
06-30 12:56:46.038  6414  6414 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
06-30 12:56:46.622   291   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,06-30 12:56:50.347   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 12:56:50.347   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 12:56:50.347   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 432292885465; DSPS: 14256938; Offset : -2803203588
,06-30 12:56:51.626   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:56:56.631   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:57:00.001   857  1289 D PowerManagerServiceEx: acquireWakeLockInternal: lock=549011905, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=857
,06-30 12:57:00.024   857   857 D PowerManagerServiceEx: releaseWakeLockInternal: lock=549011905 [*alarm*], flags=0x0
,06-30 12:57:00.040  1379  1379 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 12:57:00.040  1379  1379 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 12:57:00.040  1379  1379 I [SystemUI]Clock: called onTimeUpdated()
,06-30 12:57:00.044  1379  1379 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 12:57:00.044  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 12:57:00.045  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 12:57:00.046  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 12:57:00.565   857  1943 I ActivityManager: Process com.google.android.apps.plus (pid 6385) has died
,06-30 12:57:00.585  1824  1824 I PhoneApp: onTrimMemory: 10
06-30 12:57:00.585  1824  1824 I PhoneApp: trim memory
,06-30 12:57:00.589  2027  2027 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
06-30 12:57:01.636   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:57:06.640   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:57:10.348   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 12:57:10.348   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 12:57:10.348   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 452293689780; DSPS: 14912324; Offset : -2803192861
,06-30 12:57:11.645   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:57:16.649   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:57:21.654   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:57:26.658   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:57:30.348   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 12:57:30.348   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 12:57:30.348   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 472294404876; DSPS: 15567708; Offset : -2803210473
,06-30 12:57:31.663   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:57:36.668   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:57:41.672   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:57:46.126   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 12:57:46.134  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 12:57:46.135  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 12:57:46.135  1379  1379 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 12:57:46.135  1379  1379 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 12:57:46.135  1379  1379 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 12:57:46.677   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:57:50.349   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 12:57:50.349   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 12:57:50.349   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 492295195702; DSPS: 16223094; Offset : -2803212817
,06-30 12:57:51.681   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:57:56.686   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:58:00.039  1379  1379 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 12:58:00.039  1379  1379 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 12:58:00.039  1379  1379 I [SystemUI]Clock: called onTimeUpdated()
,06-30 12:58:00.043  1379  1379 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 12:58:00.043  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 12:58:00.045  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 12:58:00.046  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 12:58:01.690   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:58:06.695   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:58:10.350   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 12:58:10.350   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 12:58:10.350   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 512295882100; DSPS: 16878476; Offset : -2803197935
,06-30 12:58:11.700   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:58:16.704   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:58:21.709   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:58:26.713   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:58:30.350   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 12:58:30.350   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 12:58:30.351   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 532296610895; DSPS: 17533860; Offset : -2803201432
,06-30 12:58:31.718   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:58:36.722   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:58:41.727   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:58:46.273   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 12:58:46.282  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 12:58:46.282  1379  1379 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 12:58:46.282  1379  1379 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 12:58:46.282  1379  1379 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 12:58:46.283  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 12:58:46.732   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:58:50.351   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 12:58:50.351   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 12:58:50.351   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 552297310679; DSPS: 18189243; Offset : -2803203736
,06-30 12:58:51.736   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:58:56.741   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:59:00.040  1379  1379 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 12:59:00.040  1379  1379 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 12:59:00.040  1379  1379 I [SystemUI]Clock: called onTimeUpdated()
,06-30 12:59:00.044  1379  1379 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 12:59:00.045  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 12:59:00.045  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 12:59:00.046  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 12:59:01.745   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:59:06.750   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:59:10.352   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 12:59:10.352   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 12:59:10.352   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 572298024942; DSPS: 18844626; Offset : -2803191402
,06-30 12:59:11.755   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:59:16.759   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:59:21.764   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:59:26.768   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:59:30.353   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 12:59:30.353   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 12:59:30.353   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 592298731184; DSPS: 19500009; Offset : -2803187065
,06-30 12:59:31.773   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:59:36.777   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:59:41.782   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:59:46.433   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 12:59:46.442  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 12:59:46.442  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 12:59:46.442  1379  1379 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 12:59:46.443  1379  1379 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 12:59:46.443  1379  1379 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 12:59:46.477  2077  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,06-30 12:59:46.481  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
06-30 12:59:46.481  1379  1379 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 12:59:46.481  1379  1379 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 294
06-30 12:59:46.482  1912  1912 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 12:59:46.482  1912  1912 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 12:59:46.484  1876  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 12:59:46.484  1876  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 12:59:46.484  1876  2050 D LEDHandler: Battery Temp: 294, mChargingStatus=5, mChargingStop=false
06-30 12:59:46.488   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 12:59:46.488   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 12:59:46.489   857  1316 D WifiController: battery changed pluggedType: 2
,06-30 12:59:46.494  1379  1379 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 12:59:46.495  6414  6414 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
06-30 12:59:46.787   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:59:50.354   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 12:59:50.354   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 12:59:50.354   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 612299463937; DSPS: 20155394; Offset : -2803216860
,06-30 12:59:51.791   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 12:59:56.796   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:00:00.039  1379  1379 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:00:00.039  1379  1379 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:00:00.039  1379  1379 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:00:00.043  1379  1379 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:00:00.043  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:00:00.044  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:00:00.045  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:00:01.800   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:00:06.805   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:00:10.354   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:00:10.354   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:00:10.354   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 632300478565; DSPS: 20810787; Offset : -2803209860
,06-30 13:00:11.809   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:00:16.814   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:00:21.819   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:00:24.550   857  1289 D PowerManagerServiceEx: acquireWakeLockInternal: lock=549011905, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=857
,06-30 13:00:24.563   857  1289 V AlarmManager: ELAPSED_WAKEUP set : Alarm{37e367f9 type 2 when 588198 com.google.android.gms} when 588198
,06-30 13:00:24.637   857   893 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6816 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,06-30 13:00:24.698   304   304 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 428us total 55.298ms
,06-30 13:00:24.740   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 415us total 40.888ms
,06-30 13:00:24.773   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 466us total 31.927ms
,06-30 13:00:24.797  2386  2386 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:00:24.825  2386  2386 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:00:24.828  2386  2386 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 13:00:24.936  2386  3651 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 13:00:24.937  2386  3651 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 13:00:24.939  2386  3651 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 13:00:24.940  2386  3651 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 13:00:24.940   272  1043 E BandwidthController: [LG DATA] No such appUid: 10006
06-30 13:00:24.941   272  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-30 13:00:24.941   272  6850 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 13:00:24.941   272  6850 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 13:00:24.942   272  6850 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 13:00:24.943   272  6850 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 13:00:24.982  6816  6816 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,06-30 13:00:24.988   272  6850 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 13:00:24.990  2386  3651 I System.out: propertyValue:false
06-30 13:00:24.995  6816  6816 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@318102cf
,06-30 13:00:24.999   857   857 D PowerManagerServiceEx: releaseWakeLockInternal: lock=549011905 [*alarm*], flags=0x0
06-30 13:00:25.052  2386  3651 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,06-30 13:00:25.052  2386  3651 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
06-30 13:00:25.257   857  1909 I NotificationManager: android: cancelAsUser(2) by android
,06-30 13:00:25.282  2386  3651 I NotificationManager: com.google.android.gms: cancel(0) by com.google.android.gms
,06-30 13:00:26.105   276   276 V AudioFlinger: 2861 died, releasing its sessions
06-30 13:00:26.105   276   276 V AudioFlinger:  pid 1824 @ 0
,06-30 13:00:26.105   276   276 V AudioFlinger:  pid 3136 @ 1
06-30 13:00:26.105   276   276 V AudioFlinger:  pid 3136 @ 2
06-30 13:00:26.168   857  2033 I ActivityManager: Process com.lge.music (pid 2861) has died
,06-30 13:00:26.643   857   876 I ActivityManager: Process com.lge.bnr (pid 6414) has died
,06-30 13:00:26.652  1824  1824 I PhoneApp: onTrimMemory: 15
06-30 13:00:26.652  1824  1824 I PhoneApp: trim memory
06-30 13:00:26.823   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:00:27.103  2027  2027 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,06-30 13:00:27.112  2027  2027 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
06-30 13:00:27.124  2027  2027 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,06-30 13:00:27.133  6151  6844 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 13:00:27.133  6151  6844 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 13:00:27.134  6151  6844 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 13:00:27.134  6151  6844 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 13:00:27.134   272  1043 E BandwidthController: [LG DATA] No such appUid: 10006
,06-30 13:00:27.134   272  1043 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
06-30 13:00:27.134   272  6878 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
06-30 13:00:27.134   272  6878 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
06-30 13:00:27.135   272  6878 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
06-30 13:00:27.135   272  6878 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
06-30 13:00:27.183   272  6878 D libc-netbsd: res_queryN name = xxxxx succeed
06-30 13:00:27.184  6151  6844 I System.out: propertyValue:false
,06-30 13:00:27.261  6151  6844 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
06-30 13:00:27.261  6151  6844 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,06-30 13:00:27.528  2027  2027 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,06-30 13:00:30.355   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:00:30.355   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:00:30.355   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 652301221423; DSPS: 21466171; Offset : -2803199814
,06-30 13:00:31.828   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:00:36.832   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:00:41.837   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:00:46.593   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 13:00:46.596  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 13:00:46.603  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 13:00:46.603  1379  1379 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 13:00:46.603  1379  1379 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 13:00:46.603  1379  1379 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 13:00:46.841   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:00:50.356   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:00:50.356   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:00:50.356   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 672302010321; DSPS: 22121557; Offset : -2803203332
,06-30 13:00:51.846   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:00:56.851   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:01:00.039  1379  1379 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:01:00.039  1379  1379 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:01:00.039  1379  1379 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:01:00.044  1379  1379 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:01:00.044  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:01:00.045  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:01:00.046  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:01:01.855   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:01:06.860   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:01:10.357   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:01:10.357   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:01:10.357   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 692302706875; DSPS: 22776940; Offset : -2803208786
,06-30 13:01:11.864   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:01:16.869   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:01:21.876   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:01:26.880   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:01:30.357   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:01:30.357   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:01:30.357   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 712303479524; DSPS: 23432325; Offset : -2803199362
,06-30 13:01:31.885   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:01:36.889   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:01:41.894   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:01:46.754   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 13:01:46.757  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 13:01:46.758  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 13:01:46.758  1379  1379 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 13:01:46.758  1379  1379 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 13:01:46.758  1379  1379 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 13:01:46.898   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:01:50.358   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:01:50.358   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:01:50.358   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 732304253579; DSPS: 24087710; Offset : -2803188403
,06-30 13:01:51.903   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:01:56.908   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:02:00.040  1379  1379 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:02:00.040  1379  1379 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:02:00.040  1379  1379 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:02:00.044  1379  1379 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:02:00.044  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:02:00.045  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:02:00.046  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:02:01.912   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:02:06.917   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:02:10.359   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:02:10.359   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:02:10.359   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 752305011436; DSPS: 24743095; Offset : -2803193251
,06-30 13:02:11.921   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:02:16.926   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:02:21.930   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:02:26.935   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:02:30.360   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:02:30.360   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:02:30.360   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 772305843355; DSPS: 25398482; Offset : -2803185151
,06-30 13:02:31.940   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:02:36.944   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:02:41.949   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:02:46.914  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 13:02:46.914  1379  1379 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 13:02:46.914  1379  1379 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 13:02:46.914  1379  1379 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 13:02:46.916   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 13:02:46.923  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 13:02:46.953   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:02:50.360   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:02:50.360   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:02:50.360   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 792306549650; DSPS: 26053866; Offset : -2803211539
,06-30 13:02:51.958   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:02:56.962   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:03:00.039  1379  1379 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:03:00.039  1379  1379 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:03:00.039  1379  1379 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:03:00.043  1379  1379 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:03:00.043  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:03:00.045  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:03:00.045  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:03:01.967   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:03:06.972   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:03:10.361   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:03:10.361   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:03:10.361   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 812307252507; DSPS: 26709249; Offset : -2803210507
,06-30 13:03:11.976   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:03:16.981   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:03:21.985   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:03:26.990   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:03:30.362   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:03:30.362   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:03:30.362   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 832307954009; DSPS: 27364632; Offset : -2803210961
,06-30 13:03:31.995   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:03:36.999   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:03:42.004   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:03:47.008   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:03:47.075   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 13:03:47.077  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 13:03:47.078  1379  1379 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 13:03:47.078  1379  1379 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 13:03:47.078  1379  1379 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 13:03:47.079  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 13:03:47.116  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
06-30 13:03:47.116  1379  1379 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 13:03:47.116  1379  1379 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 293
,06-30 13:03:47.119  1912  1912 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 13:03:47.119  1912  1912 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 13:03:47.120  1876  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 13:03:47.120  1876  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 13:03:47.120  1876  2050 D LEDHandler: Battery Temp: 293, mChargingStatus=5, mChargingStop=false
06-30 13:03:47.124  2077  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 13:03:47.126   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:03:47.126   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:03:47.127   857  1316 D WifiController: battery changed pluggedType: 2
06-30 13:03:47.130  1379  1379 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,06-30 13:03:50.363   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:03:50.363   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:03:50.363   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 852308748324; DSPS: 28020018; Offset : -2803210052
,06-30 13:03:52.013   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:03:57.017   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:04:00.039  1379  1379 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:04:00.039  1379  1379 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:04:00.039  1379  1379 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:04:00.043  1379  1379 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:04:00.043  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:04:00.044  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:04:00.045  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:04:02.022   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:04:07.027   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:04:10.363   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:04:10.363   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:04:10.363   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 872309537327; DSPS: 28675404; Offset : -2803214610
,06-30 13:04:12.031   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:04:17.036   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:04:22.040   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:04:27.045   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:04:30.364   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:04:30.364   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:04:30.364   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 892310547268; DSPS: 29330797; Offset : -2803211489
,06-30 13:04:32.049   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:04:37.054   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:04:42.059   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:04:47.063   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:04:47.234   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 13:04:47.237  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 13:04:47.238  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 13:04:47.238  1379  1379 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 13:04:47.238  1379  1379 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 13:04:47.238  1379  1379 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 13:04:50.365   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:04:50.365   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:04:50.365   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 912311252782; DSPS: 29986180; Offset : -2803208087
,06-30 13:04:52.068   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:04:57.072   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:05:00.039  1379  1379 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:05:00.039  1379  1379 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:05:00.039  1379  1379 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:05:00.043  1379  1379 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:05:00.043  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:05:00.044  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:05:00.045  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:05:02.077   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:05:07.081   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:05:10.366   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:05:10.366   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:05:10.366   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 932312008607; DSPS: 30641564; Offset : -2803184581
,06-30 13:05:12.086   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:05:17.091   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:05:22.095   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:05:23.790   857  1289 D PowerManagerServiceEx: acquireWakeLockInternal: lock=549011905, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=857
,06-30 13:05:23.797   857  1289 V AlarmManager: ELAPSED_WAKEUP set : Alarm{e1b148f type 2 when 945727 com.android.bluetooth} when 945727
06-30 13:05:23.927   857   857 D PowerManagerServiceEx: releaseWakeLockInternal: lock=549011905 [*alarm*], flags=0x0
,06-30 13:05:23.960  2077  3601 W bt-smp  : Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
06-30 13:05:23.961  2077  3601 W bt-smp  : Plain text(LSB ~ MSB) = 63 a1 62 00 00 00 00 00 00 00 00 00 00 00 00 00 
,06-30 13:05:23.963  2077  3601 W bt-smp  : Encrypted text(LSB ~ MSB) = 44 41 68 c0 82 e9 8b 40 5a b9 06 55 6e af 7c 15 
06-30 13:05:23.963  2077  3601 W bt-btm  : Stopping oneshot timer
06-30 13:05:27.100   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:05:30.367   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:05:30.367   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:05:30.367   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 952312792349; DSPS: 31296950; Offset : -2803194373
,06-30 13:05:32.104   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:05:37.109   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:05:42.124   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:05:47.129   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:05:47.393   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 13:05:47.396  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 13:05:47.399  1379  1379 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 13:05:47.399  1379  1379 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 13:05:47.399  1379  1379 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 13:05:47.400  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 13:05:50.367   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:05:50.367   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:05:50.367   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 972313497082; DSPS: 31952333; Offset : -2803191440
,06-30 13:05:52.133   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:05:57.138   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:06:00.039  1379  1379 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:06:00.039  1379  1379 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:06:00.039  1379  1379 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:06:00.044  1379  1379 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:06:00.044  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:06:00.045  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:06:00.046  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:06:02.142   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:06:07.147   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:06:10.368   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:06:10.368   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:06:10.368   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 992314271449; DSPS: 32607719; Offset : -2803212510
,06-30 13:06:12.152   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:06:17.156   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:06:22.161   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:06:27.165   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:06:30.369   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:06:30.369   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:06:30.369   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 1012315048420; DSPS: 33263104; Offset : -2803196577
,06-30 13:06:32.170   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:06:37.175   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:06:42.179   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:06:47.184   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:06:47.553   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 13:06:47.556  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 13:06:47.562  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 13:06:47.562  1379  1379 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 13:06:47.562  1379  1379 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 13:06:47.563  1379  1379 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 13:06:50.370   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:06:50.370   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:06:50.370   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 1032315757006; DSPS: 33918487; Offset : -2803189661
,06-30 13:06:52.188   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:06:57.193   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:07:00.040  1379  1379 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:07:00.040  1379  1379 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:07:00.040  1379  1379 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:07:00.045  1379  1379 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:07:00.045  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:07:00.046  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:07:00.046  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:07:02.197   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:07:07.202   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:07:10.370   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:07:10.370   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:07:10.370   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 1052316535123; DSPS: 34573873; Offset : -2803207084
,06-30 13:07:12.206   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:07:17.211   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:07:22.216   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:07:27.224   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:07:30.371   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:07:30.371   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:07:30.371   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 1072317293866; DSPS: 35229258; Offset : -2803209223
,06-30 13:07:32.229   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:07:37.234   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:07:42.238   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:07:47.243   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:07:47.713   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 13:07:47.716  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 13:07:47.722  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 13:07:47.722  1379  1379 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 13:07:47.723  1379  1379 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 13:07:47.723  1379  1379 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 13:07:50.372   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:07:50.372   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:07:50.372   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 1092318059796; DSPS: 35884643; Offset : -2803206103
,06-30 13:07:52.247   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:07:57.252   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:08:00.039  1379  1379 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:08:00.039  1379  1379 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:08:00.039  1379  1379 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:08:00.043  1379  1379 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:08:00.044  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:08:00.045  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:08:00.045  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:08:02.256   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:08:07.261   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:08:10.373   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:08:10.373   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:08:10.373   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 1112318832809; DSPS: 36540028; Offset : -2803196003
,06-30 13:08:12.265   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:08:17.270   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:08:22.275   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:08:27.279   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:08:30.373   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:08:30.373   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:08:30.374   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 1132319609416; DSPS: 37195414; Offset : -2803213348
,06-30 13:08:32.284   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:08:37.288   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:08:42.293   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:08:47.297   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:08:47.874  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 13:08:47.874  1379  1379 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 13:08:47.874  1379  1379 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 13:08:47.874  1379  1379 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 13:08:47.876   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 13:08:47.877  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 13:08:50.374   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:08:50.374   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:08:50.374   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 1152320613836; DSPS: 37850806; Offset : -2803185569
,06-30 13:08:52.302   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:08:57.307   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:09:00.039  1379  1379 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:09:00.039  1379  1379 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:09:00.039  1379  1379 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:09:00.043  1379  1379 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:09:00.043  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:09:00.044  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:09:00.045  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:09:02.311   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:09:07.316   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:09:10.375   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:09:10.375   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:09:10.375   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 1172321368776; DSPS: 38506191; Offset : -2803193515
,06-30 13:09:12.320   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:09:17.325   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:09:22.329   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:09:27.334   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:09:30.376   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:09:30.376   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:09:30.376   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 1192322065331; DSPS: 39161574; Offset : -2803198499
,06-30 13:09:32.339   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:09:37.343   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:09:42.348   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:09:47.352   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:09:48.034  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 13:09:48.034  1379  1379 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 13:09:48.034  1379  1379 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 13:09:48.034  1379  1379 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 13:09:48.036   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 13:09:48.037  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 13:09:48.075  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
06-30 13:09:48.075  1379  1379 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 13:09:48.076  1379  1379 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
,06-30 13:09:48.078  1912  1912 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
06-30 13:09:48.079  1912  1912 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
06-30 13:09:48.080  1876  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 13:09:48.080  1876  2050 D LEDHandler: Battery Level Remaining: 100%
06-30 13:09:48.080  1876  2050 D LEDHandler: Battery Temp: 292, mChargingStatus=5, mChargingStop=false
06-30 13:09:48.083  2077  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 13:09:48.084  1379  1379 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 13:09:48.086   857   857 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:09:48.086   857   857 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:09:48.087   857  1316 D WifiController: battery changed pluggedType: 2
06-30 13:09:50.377   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:09:50.377   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:09:50.377   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 1212322855792; DSPS: 39816960; Offset : -2803201653
,06-30 13:09:52.357   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:09:57.361   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:10:00.039  1379  1379 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:10:00.039  1379  1379 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:10:00.039  1379  1379 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:10:00.043  1379  1379 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:10:00.044  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:10:00.045  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:10:00.045  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:10:01.985   857   892 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 13:10:02.366   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:10:07.371   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:10:10.377   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:10:10.377   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:10:10.377   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 1232323541825; DSPS: 40472342; Offset : -2803188490
,06-30 13:10:12.375   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:10:17.380   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:10:22.384   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:10:27.397   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:10:30.378   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:10:30.378   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:10:30.378   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 1252324248172; DSPS: 41127726; Offset : -2803212898
,06-30 13:10:32.402   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:10:37.407   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:10:42.411   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:10:47.416   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:10:48.194   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 13:10:48.197  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 13:10:48.198  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 13:10:48.198  1379  1379 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 13:10:48.198  1379  1379 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 13:10:48.198  1379  1379 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 13:10:50.379   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:10:50.379   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:10:50.379   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 1272325032071; DSPS: 41783111; Offset : -2803192486
,06-30 13:10:52.420   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:10:57.425   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:11:00.040  1379  1379 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:11:00.040  1379  1379 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:11:00.040  1379  1379 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:11:00.044  1379  1379 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:11:00.045  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:11:00.045  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:11:00.046  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:11:02.429   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:11:07.434   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:11:10.379   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:11:10.380   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:11:10.380   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 1292325724720; DSPS: 42438494; Offset : -2803201248
,06-30 13:11:12.439   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:11:17.443   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:11:22.448   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:11:27.452   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:11:30.380   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:11:30.380   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:11:30.380   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 1312326408566; DSPS: 43093876; Offset : -2803188606
,06-30 13:11:32.457   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:11:37.461   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:11:42.466   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:11:47.471   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:11:48.353   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 13:11:48.356  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 13:11:48.362  1379  1379 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 13:11:48.362  1379  1379 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 13:11:48.362  1379  1379 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 13:11:48.363  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 13:11:50.381   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:11:50.381   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:11:50.381   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 1332327184079; DSPS: 43749262; Offset : -2803207018
,06-30 13:11:52.475   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:11:57.480   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:12:00.039  1379  1379 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:12:00.039  1379  1379 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:12:00.039  1379  1379 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:12:00.044  1379  1379 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:12:00.044  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:12:00.045  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:12:00.046  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:12:02.484   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:12:07.489   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:12:10.382   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:12:10.382   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:12:10.382   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 1352327873394; DSPS: 44404644; Offset : -2803188777
,06-30 13:12:12.493   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:12:17.498   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:12:22.503   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:12:27.507   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:12:30.382   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:12:30.382   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:12:30.383   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 1372328652137; DSPS: 45060030; Offset : -2803203777
,06-30 13:12:32.512   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:12:37.518   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:12:42.523   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:12:47.527   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:12:48.513  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 13:12:48.514  1379  1379 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 13:12:48.514  1379  1379 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 13:12:48.514  1379  1379 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 13:12:48.516   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 13:12:48.517  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 13:12:50.383   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:12:50.383   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:12:50.383   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 1392329345410; DSPS: 45715413; Offset : -2803212227
,06-30 13:12:52.532   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:12:57.537   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:13:00.040  1379  1379 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:13:00.040  1379  1379 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:13:00.040  1379  1379 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:13:00.045  1379  1379 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:13:00.045  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:13:00.046  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:13:00.047  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:13:02.541   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:13:07.546   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:13:10.384   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:13:10.384   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:13:10.384   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 1412330449310; DSPS: 46370809; Offset : -2803206933
,06-30 13:13:12.550   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:13:17.555   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:13:22.560   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:13:27.564   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:13:30.385   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:13:30.385   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:13:30.385   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 1432331203052; DSPS: 47026193; Offset : -2803185639
,06-30 13:13:32.569   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:13:37.573   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:13:42.578   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:13:47.582   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:13:48.674  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 13:13:48.674  1379  1379 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 13:13:48.674  1379  1379 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 13:13:48.674  1379  1379 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 13:13:48.676   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
06-30 13:13:48.677  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 13:13:50.386   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:13:50.386   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:13:50.386   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 1452331885805; DSPS: 47681576; Offset : -2803204974
,06-30 13:13:52.587   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:13:57.592   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:14:00.040  1379  1379 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:14:00.040  1379  1379 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:14:00.040  1379  1379 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:14:00.044  1379  1379 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:14:00.045  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:14:00.045  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:14:00.046  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:14:02.596   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:14:07.601   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:14:10.386   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:14:10.387   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:14:10.387   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 1472332706422; DSPS: 48336963; Offset : -2803208148
,06-30 13:14:12.605   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:14:17.610   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:14:22.621   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:14:27.625   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:14:30.387   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:14:30.387   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:14:30.387   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 1492333555164; DSPS: 48992350; Offset : -2803185126
,06-30 13:14:32.630   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:14:37.635   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:14:42.639   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:14:47.644   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:14:48.833   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,06-30 13:14:48.836  1876  1876 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
06-30 13:14:48.842  1379  1379 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
06-30 13:14:48.842  1379  1379 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 13:14:48.843  1379  1379 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
06-30 13:14:48.843  1379  1379 I [SystemUI]LGPowerUI: On Skip Timer : true
06-30 13:14:50.388   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:14:50.388   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:14:50.388   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 1512334337761; DSPS: 49647736; Offset : -2803194605
,06-30 13:14:52.648   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:14:57.653   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:15:00.039  1379  1379 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:15:00.039  1379  1379 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:15:00.039  1379  1379 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:15:00.043  1379  1379 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:15:00.043  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:15:00.045  1379  1379 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:15:00.045  1379  1379 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:15:02.657   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:15:07.662   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:15:10.389   857  1011 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
06-30 13:15:10.389   857  1011 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
06-30 13:15:10.389   857  1011 D sensors_hal_Time: tsOffsetIs: Apps: 1532335037701; DSPS: 50303119; Offset : -2803196388
,06-30 13:15:12.667   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,06-30 13:15:17.671   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,TIME-OUT KILL (timeout was 1400000ms),06-30 13:15:21.564  7001  7001 D AndroidRuntime: 
06-30 13:15:21.564  7001  7001 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-30 13:15:21.581  7001  7001 D AndroidRuntime: CheckJNI is OFF
06-30 13:15:22.007  7001  7001 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
06-30 13:15:22.078   857   893 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
06-30 13:15:22.078   857   893 I ActivityManager: Killing 6556:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
06-30 13:15:22.142   857  1882 I WindowState: WIN DEATH: Window{20e358f4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 13:15:22.154   857  1882 D InputDispatcher: Focus left window: Window{20e358f4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 13:15:22.154   857  1882 D InputDispatcher: Window went away: Window{20e358f4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 13:15:22.187   857  1063 W PackageSettings: Skipping PackageSetting{e19a622 com.example.hello/10317} due to missing metadata
06-30 13:15:22.289   857   893 I ActivityManager:   Force finishing activity ActivityRecord{1c93877a u0 com.test.thalitest/.MainActivity t241}
06-30 13:15:22.300   857   857 V ActivityManager: Display changed displayId=0
06-30 13:15:22.305  1824  1824 D DSDPConnection: Display #0 changed.
06-30 13:15:22.319   857  2033 W ActivityManager: Spurious death for ProcessRecord{3765831c 6556:com.test.thalitest/u0a30}, curProc for 6556: null
06-30 13:15:22.320   857  1063 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
06-30 13:15:22.323   857  1063 I ActivityManager:   Force finishing activity ActivityRecord{1c93877a u0 com.test.thalitest/.MainActivity t241 f}
06-30 13:15:22.323   857  1063 W ActivityManager: Duplicate finish request for ActivityRecord{1c93877a u0 com.test.thalitest/.MainActivity t241 f}
06-30 13:15:22.391  1379  1379 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
06-30 13:15:22.404  2027  2027 I art     : Explicit concurrent mark sweep GC freed 2862(255KB) AllocSpace objects, 1(23KB) LOS objects, 40% free, 12MB/21MB, paused 1.836ms total 78.306ms
06-30 13:15:22.415  2386  2729 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
06-30 13:15:22.419  3656  3656 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
06-30 13:15:22.426  1912  1912 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
06-30 13:15:22.432   857  1291 I InputReader: Reconfiguring input devices.  changes=0x00000010
06-30 13:15:22.433  3656  3656 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
06-30 13:15:22.434  3656  3656 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
06-30 13:15:22.434  3656  3656 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
06-30 13:15:22.434  3656  3656 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
06-30 13:15:22.434  3656  3656 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-30 13:15:22.434  3656  3656 W System.err: 	at android.os.Looper.loop(Looper.java:135)
06-30 13:15:22.434  3656  3656 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
06-30 13:15:22.434  3656  3656 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 13:15:22.434  3656  3656 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 13:15:22.434  3656  3656 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
06-30 13:15:22.434  3656  3656 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
06-30 13:15:22.459  6151  6151 I art     : Explicit concurrent mark sweep GC freed 521(33KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 14MB/19MB, paused 849us total 132.346ms
06-30 13:15:22.476   857   893 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7032 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
06-30 13:15:22.484  1950  1950 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
06-30 13:15:22.530   857  2174 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7038 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
06-30 13:15:22.536  1950  1950 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
06-30 13:15:22.590  1379  1379 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
06-30 13:15:22.624  1950  1950 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
06-30 13:15:22.638  1950  1950 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
06-30 13:15:22.638  1950  1950 I Activity: Activity.onPostResume() called 
06-30 13:15:22.647  1950  1950 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
06-30 13:15:22.653  7032  7032 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 13:15:22.653  7032  7032 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
06-30 13:15:22.654  7032  7032 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
06-30 13:15:22.668   857   857 I art     : Explicit concurrent mark sweep GC freed 59401(3MB) AllocSpace objects, 16(256KB) LOS objects, 33% free, 24MB/36MB, paused 12.999ms total 311.400ms
06-30 13:15:22.675  1950  7067 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
06-30 13:15:22.676   291   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
06-30 13:15:22.681   857  1063 I art     : WaitForGcToComplete blocked for 142.581ms for cause Explicit
06-30 13:15:22.692  1379  1379 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
06-30 13:15:22.692  1379  1379 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
06-30 13:15:22.700  7038  7038 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
06-30 13:15:22.716   857  1922 D InputDispatcher: Focus entered window: Window{19624832 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
06-30 13:15:22.728   857  1052 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
06-30 13:15:22.728   857  1052 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
06-30 13:15:22.730   857  1052 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
06-30 13:15:22.730   857  1052 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
06-30 13:15:22.730   857  1052 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-30 13:15:22.730   857  1052 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1e0e7aad,  pkg=WindowManager.LayoutParams
06-30 13:15:22.730   857  1052 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
06-30 13:15:22.731  1379  1379 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
06-30 13:15:22.731  1379  1379 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
06-30 13:15:22.731  1379  1379 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
06-30 13:15:22.731  1379  1379 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
06-30 13:15:22.739  1950  1950 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
06-30 13:15:22.740  1950  1950 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
06-30 13:15:22.743  1950  1950 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
06-30 13:15:22.753  1379  1497 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
06-30 13:15:22.753  1379  1497 D KeyguardModel: createShortcutInfo...
06-30 13:15:22.758  1379  1497 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
06-30 13:15:22.758  1379  1497 D KeyguardModel: createShortcutInfo...
06-30 13:15:22.762  1379  1497 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 13:15:22.768  1379  1497 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
06-30 13:15:22.770  1379  1497 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
06-30 13:15:22.770  1379  1497 D KeyguardModel: createShortcutInfo...
06-30 13:15:22.772  1379  1497 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 13:15:22.772  1379  1497 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
06-30 13:15:22.772  1950  1950 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
06-30 13:15:22.774  1950  1950 I PhoneWindow: [setNavigationBarColor] color=0x 0
06-30 13:15:22.774  1379  1497 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
06-30 13:15:22.775  1379  1497 D KeyguardModel: createShortcutInfo...
06-30 13:15:22.777  1379  1497 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 13:15:22.777  1379  1497 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
06-30 13:15:22.778  1379  1497 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
06-30 13:15:22.778  1379  1497 D KeyguardModel: createShortcutInfo...
06-30 13:15:22.785  1379  1379 D KeyguardModel: handleShortcutListChanged...
06-30 13:15:22.792  1379  1497 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
06-30 13:15:22.792  1379  1497 D KeyguardModel: createShortcutInfo...
06-30 13:15:22.796  1379  1497 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
06-30 13:15:22.796  1379  1497 D KeyguardModel: createShortcutInfo...
06-30 13:15:22.798  1379  1497 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 13:15:22.798  1379  1497 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
06-30 13:15:22.800  1379  1497 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
06-30 13:15:22.800  1379  1497 D KeyguardModel: createShortcutInfo...
06-30 13:15:22.803   857   857 D administrator: Handling package changes for user 0
06-30 13:15:22.812  1379  1497 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 13:15:22.813  1379  1497 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
06-30 13:15:22.815  1379  1497 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
06-30 13:15:22.815  1379  1497 D KeyguardModel: createShortcutInfo...
06-30 13:15:22.817  1379  1497 W ResourceType: No package identifier when getting value for resource number 0x00000000
06-30 13:15:22.818  1379  1497 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
06-30 13:15:22.820  1379  1497 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
06-30 13:15:22.820  1379  1497 D KeyguardModel: createShortcutInfo...
06-30 13:15:22.825  1379  1379 D KeyguardModel: handleShortcutListChanged...
06-30 13:15:22.846  1859  1873 I art     : Background sticky concurrent mark sweep GC freed 75743(4MB) AllocSpace objects, 0(0B) LOS objects, 28% free, 10MB/14MB, paused 9.959ms total 70.328ms
06-30 13:15:22.891   857  1943 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
06-30 13:15:22.894   857  1943 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6556 uid 10030
06-30 13:15:22.990  1950  1950 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
06-30 13:15:22.991  1950  1950 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
06-30 13:15:22.996  2027  2027 I HotwordDetector: Closing mic
06-30 13:15:23.001  1950  1950 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@25a3fa11 time:1544947
06-30 13:15:23.013   857  1054 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{191c6372 u0 com.lge.launcher2/.Launcher t240} time:1544959
06-30 13:15:23.018  2027  2616 I HotwordRecognitionRnr: Stopping hotword detection.
06-30 13:15:23.026  1634  1634 E b       : Unable to connect to the editor to retrieve text... will retry later
06-30 13:15:23.054  1950  1950 I art     : Explicit concurrent mark sweep GC freed 7793(423KB) AllocSpace objects, 4(645KB) LOS objects, 39% free, 15MB/25MB, paused 1.030ms total 51.287ms
06-30 13:15:23.055  1950  1950 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
06-30 13:15:23.070   857  1063 I art     : Explicit concurrent mark sweep GC freed 15734(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 4.731ms total 385.406ms
06-30 13:15:23.118  7032  7032 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
06-30 13:15:23.144  7032  7032 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
06-30 13:15:23.182  1859  1859 D LCardEmulationManager: getHceAppCount hostAppNum : 0
06-30 13:15:23.182  1859  1859 D LCardEmulationManager: getDefaultRoute
06-30 13:15:23.212  7001  7001 D AndroidRuntime: Shutting down VM
06-30 13:15:23.229   857   857 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
06-30 13:15:23.229   857   857 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
06-30 13:15:23.232   857   857 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
06-30 13:15:23.264   857  1063 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7072 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
06-30 13:15:23.267   857  1350 D TaskPersister: removeObsoleteFile: deleting file=241_task.xml
06-30 13:15:23.289   857   892 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 13:15:23.412   857   892 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
06-30 13:15:23.423  1950  1950 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
06-30 13:15:23.434  7032  7032 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
06-30 13:15:23.450   857   892 W ProcessCpuTracker: Skipping unknown process pid 7001
06-30 13:15:23.485   857  1065 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7093 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
06-30 13:15:23.631  7093  7093 I AppUp4:AppBoxCP: onCreate
06-30 13:15:23.633  7093  7093 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: Failed to open database '/data/data/com.lge.appbox.client/databases/appbox.db'.
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
06-30 13:15:23.646  7093  7093 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
06-30 13:15:23.646  7093  7093 D AndroidRuntime: Shutting down VM
--------- beginning of crash
06-30 13:15:23.647  7093  7093 E AndroidRuntime: FATAL EXCEPTION: main
06-30 13:15:23.647  7093  7093 E AndroidRuntime: Process: com.lge.appbox.client, PID: 7093
06-30 13:15:23.647  7093  7093 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.lge.appbox.databases.AppBoxContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
06-30 13:15:23.647  7093  7093 E AndroidRuntime: 	... 11 more
06-30 13:15:23.667   857  7112 E DropBoxManagerService: Can't write: system_app_crash
06-30 13:15:23.667   857  7112 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
06-30 13:15:23.667   857  7112 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:15:23.667   857  7112 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:15:23.667   857  7112 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 13:15:23.667   857  7112 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
06-30 13:15:23.667   857  7112 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
06-30 13:15:23.667   857  7112 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12621)
06-30 13:15:23.667   857  7112 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:15:23.667   857  7112 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
06-30 13:15:23.667   857  7112 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:15:23.667   857  7112 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:15:23.667   857  7112 E DropBoxManagerService: 	... 5 more

```
