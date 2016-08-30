#### Test 82642184ea62b6e_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-30 23:10:59.636  2851  2851 I CloudHub: [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19944
08-30 23:10:59.685  1909  1909 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
08-30 23:10:59.686  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-08-30 23:10:59.685 DNS addrs= 192.168.1.1, 0.0.0.0, 
08-30 23:10:59.693  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 23:10:59.693  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 23:10:59.693  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-30 23:10:59.933  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 23:10:59.937  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 23:10:59.937  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
--------- beginning of system
08-30 23:11:00.002   892  1285 D PowerManagerServiceEx: acquireWakeLockInternal: lock=203800917, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=892
08-30 23:11:00.018  2835  2835 D WeatherService: 2 : TimeTick Intent has been received, Time(hour:min:sec) 23:11:0
08-30 23:11:00.021  2835  2835 D WeatherService: 2 : TimeTick Intent And Screen On
08-30 23:11:00.021  2835  2835 D WeatherService: 2 : SDK version : 21
08-30 23:11:00.022   892  1973 W ActivityManager: getTasks: caller 10074 does not hold GET_TASKS; limiting output
08-30 23:11:00.025  2835  2835 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
08-30 23:11:00.034  2835  2835 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
08-30 23:11:00.034  2835  2835 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
08-30 23:11:00.034  2835  2835 D WeatherService: 2 : requestRefreshAppWidget, isUpdateStart : false
08-30 23:11:00.038  1380  1380 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-30 23:11:00.038  1380  1380 I KeyguardUpdateMonitor: called onTimeUpdated()
08-30 23:11:00.038  2835  2835 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-30 23:11:00.039  2835  2835 D WeatherService: 2 : requestRefreshAppWidget, isUpdating : false
08-30 23:11:00.039  2835  2835 D WeatherAncestor: 2 : buildUpdate, appWidgetId: 2
08-30 23:11:00.039  2835  2835 D WeatherTheme: 2 : Current Theme Name: com.lge.launcher2.theme.optimus
08-30 23:11:00.039  2835  2835 D WeatherTheme: 2 : Fixed theme : optimus
08-30 23:11:00.076  2835  2835 D WeatherReflect: 2 : Map key string is -2
08-30 23:11:00.079  1380  1380 I [SystemUI]Clock: called onTimeUpdated()
08-30 23:11:00.082  1380  1380 I LgeClockWidgetControlView: called onTimeUpdated()
08-30 23:11:00.087  1380  1380 I [SystemUI]DateView: called onTimeUpdated()
08-30 23:11:00.091  2835  2835 D lim     : 2 : time = 23:11
08-30 23:11:00.100  2835  2835 I WeatherReflect: Model Name : LG-D722
08-30 23:11:00.100  2835  2835 D WeatherTheme: 2 : Different view - status_min_formatted : 10 != 11
08-30 23:11:00.101  2835  2835 D WeatherTheme: 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
08-30 23:11:00.101  1380  1380 I [SystemUI]DateView: called onTimeUpdated()
08-30 23:11:00.102  1380  1380 D KeyguardUpdateMonitor: handleTimeUpdate
08-30 23:11:00.103  2835  2835 D WeatherReflect: 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
08-30 23:11:00.106  2835  2835 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-30 23:11:00.106  2835  2835 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-30 23:11:00.106  2835  2835 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-30 23:11:00.106  2835  2835 D Weather4x2_optimus: currentPackage=com.lge.sizechangable.weather.theme.optimus
08-30 23:11:00.156  2835  2835 D Weather4x2_optimus: [[[[[[Theme package!!]]]]]] RemoteViews are created 2
08-30 23:11:00.156  2835  2835 D Weather4x2_optimus: widgetType = 1, orientation = 1
08-30 23:11:00.156  2835  2835 D Weather4x2_optimus: forecast size is 0
08-30 23:11:00.156  2835  2835 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-30 23:11:00.157  2835  2835 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-30 23:11:00.157  2835  2835 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-30 23:11:00.158  2835  2835 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-30 23:11:00.158  2835  2835 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-30 23:11:00.158  2835  2835 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-30 23:11:00.158  2835  2835 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-30 23:11:00.158  2835  2835 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-30 23:11:00.158  2835  2835 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-30 23:11:00.158  2835  2835 I Theme_WeatherAncestor_optimus: WEATHER_CP_ACCU : 
08-30 23:11:00.158  2835  2835 I Theme_WeatherAncestor_optimus: weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
08-30 23:11:00.158  2835  2835 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-30 23:11:00.158  2835  2835 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-30 23:11:00.158  2835  2835 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-30 23:11:00.159  2835  2835 D Theme_WeatherAncestor_optimus: setTouchIntent, appWidgetId: 2
08-30 23:11:00.160  2835  2835 D Theme_WeatherAncestor_optimus: url is : null
08-30 23:11:00.162  2835  2835 D Theme   : strTheme: com.lge.launcher2.theme.optimus
08-30 23:11:00.162  2835  2835 D Theme   : EnableTheme(home): com.lge.launcher2.theme.optimus
08-30 23:11:00.162  2835  2835 D Theme   : EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
08-30 23:11:00.163  2835  2835 D WeatherAncestor: 2 : update view, appWidgetId: 2
08-30 23:11:00.170  2835  2835 D WeatherService: 2 : TimeTick Intent has been processed, Time(hour:min:sec) 23:11:0
08-30 23:11:00.182   892   892 D PowerManagerServiceEx: releaseWakeLockInternal: lock=203800917 [*alarm*], flags=0x0
08-30 23:11:00.193  6427  6427 D AndroidRuntime: 
08-30 23:11:00.193  6427  6427 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 23:11:00.207  6427  6427 D AndroidRuntime: CheckJNI is OFF
08-30 23:11:00.309  1950  1950 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
08-30 23:11:00.392  1950  1950 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-30 23:11:00.468  6427  6427 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-30 23:11:00.486   892  2088 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 23:11:00.537   892  2088 D ActivityManager: setTaskToReturnTo : TaskRecord{9b9676a #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 23:11:00.540   892  2088 D ActivityManager: setTaskToReturnTo : TaskRecord{9b9676a #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 23:11:00.557   892  2088 D WindowStateEx: AppWindowTokenEx init.. 
08-30 23:11:00.566   892  1055 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-30 23:11:00.580  1950  1950 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-30 23:11:00.586   892  1055 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-30 23:11:00.588   892  2088 D InputDispatcher: Focus left window: Window{1c5c507e u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-30 23:11:00.591  6427  6427 D AndroidRuntime: Shutting down VM
08-30 23:11:00.603   892  1055 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-30 23:11:00.603   892  1055 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-30 23:11:00.617   892  1055 D SplitWindow: check instance of lgWin Window{b9b79c2 u0 Starting com.test.thalitest}
08-30 23:11:00.654   892  1641 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6453 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 23:11:00.674  1950  1950 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-30 23:11:00.722  2029  2029 I HotwordDetector: Closing mic
08-30 23:11:00.726  1950  1950 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-30 23:11:00.736  2029  2577 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.u@32cf4657
08-30 23:11:00.736  2029  2577 V AudioRecord: stop()
08-30 23:11:00.736  2029  2577 D AudioRecord: AudioRecord->stop()
08-30 23:11:00.737   285   285 V AudioFlinger: RecordHandle::stop()
08-30 23:11:00.737   285   285 V AudioFlinger: RecordThread::stop
08-30 23:11:00.737   285   285 V AudioFlinger: Record stopped OK
08-30 23:11:00.740   285   285 V AudioPolicyManager: stopInput() input 17
08-30 23:11:00.741   285   285 V AudioPolicyService: AudioCommandThread() adding release patch delay 0
08-30 23:11:00.741   285   285 V AudioPolicyService: inserting command: 8 at index 0, num commands 0
08-30 23:11:00.741   285  1061 V AudioPolicyService: AudioCommandThread() waking up
08-30 23:11:00.741   285  1061 V AudioPolicyService: AudioCommandThread() processing release audio patch
08-30 23:11:00.741   285  1061 V AudioFlinger::PatchPanel: releaseAudioPatch handle 18
08-30 23:11:00.741   285  1061 V AudioFlinger::PatchPanel: releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
08-30 23:11:00.741   285  1061 V AudioFlinger: ThreadBase::setParameters() routing=0
08-30 23:11:00.742   285  1061 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-30 23:11:00.742   285  2602 V AudioFlinger: processConfigEvents_l() remaining events 1
08-30 23:11:00.742   285  2602 V AudioFlinger: processConfigEvents_l() DONE thread 0xb39e9000
08-30 23:11:00.744   892   968 I WindowStateAnimator: Starting window displayed
08-30 23:11:00.745   285  2602 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
08-30 23:11:00.750   892  1053 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
08-30 23:11:00.753   892  1053 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :win == null
08-30 23:11:00.754   892  1053 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-30 23:11:00.755   892  1053 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-30 23:11:00.755   892  1053 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-30 23:11:00.755   892  1053 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1f89cce2,  pkg=WindowManager.LayoutParams
08-30 23:11:00.755   892  1053 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-30 23:11:00.757  1380  1380 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-30 23:11:00.760  1380  1380 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-30 23:11:00.760  1380  1380 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-30 23:11:00.760  1380  1380 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-30 23:11:00.791   285  2602 V audio_hw_primary: stop_input_stream: enter: usecase(7: audio-record)
08-30 23:11:00.792   285  2602 V audio_hw_primary: disable_audio_route: enter: usecase(7)
08-30 23:11:00.792   285  2602 V msm8974_platform_lge: LGE_platform_add_backend_name: enter: 144
08-30 23:11:00.792   285  2602 V audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-30 23:11:00.798   285  2602 V audio_hw_primary: disable_audio_route: exit
08-30 23:11:00.798   285  2602 E audio_hw_primary: disable_snd_device: enter 144
08-30 23:11:00.798   285  2602 D hardware_info: hw_info_append_hw_type : device_name = lg-vr-handset-mic
08-30 23:11:00.798   285  2602 V audio_hw_primary: disable_snd_device: snd_device(144: lg-vr-handset-mic)
08-30 23:11:00.802   285  2602 V audio_hw_primary: stop_input_stream: exit: status(0)
08-30 23:11:00.802   285  2602 V audio_hw_primary: in_standby: exit:  status(0)
08-30 23:11:00.802   285  2602 V AudioFlinger: RecordThread: loop stopping
08-30 23:11:00.803   285  1061 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 23:11:00.803   285   285 V AudioPolicyManager: resetInputDevice() releaseAudioPatch returned -22
08-30 23:11:00.803   285   285 V AudioPolicyManager: removeAudioPatch() handle 18 af handle 18
08-30 23:11:00.803   285   285 V AudioPolicyService: AudioCommandThread() adding update audio patch list
08-30 23:11:00.803   285   285 V AudioPolicyService: inserting command: 10 at index 0, num commands 0
08-30 23:11:00.805   285   285 V AudioPolicyService: AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
08-30 23:11:00.805   285   285 V AudioPolicyService: inserting command: 3 at index 0, num commands 0
08-30 23:11:00.805   285  1061 V AudioPolicyService: AudioCommandThread() waking up
08-30 23:11:00.805   285  1061 V AudioPolicyService: AudioCommandThread() processing set parameters string hotword_active=0, io 17
08-30 23:11:00.805   285  1061 V AudioFlinger: setParameters(): io 17, keyvalue hotword_active=0, calling pid 285
08-30 23:11:00.805   285  1061 V AudioFlinger: ThreadBase::setParameters() hotword_active=0
08-30 23:11:00.805   285  1061 V AudioFlinger: sendConfigEvent_l() num events 1 event 2
08-30 23:11:00.805   285  2602 V AudioFlinger: RecordThread: loop starting
08-30 23:11:00.805   285  2602 V AudioFlinger: processConfigEvents_l() remaining events 1
08-30 23:11:00.805   285  2602 D audio_hw_primary: in_set_parameters: enter: kvpairs=hotword_active=0
,08-30 23:11:00.805   285  2602 V audio_hw_primary: in_set_parameters: exit: status(0)
08-30 23:11:00.806   285  2602 V AudioFlinger: processConfigEvents_l() DONE thread 0xb39e9000
08-30 23:11:00.806   285  2602 V AudioFlinger: RecordThread: loop stopping
08-30 23:11:00.807   285  1061 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 23:11:00.808   285  1062 V AudioPolicyService: AudioCommandThread() waking up
08-30 23:11:00.808   285  1062 V AudioPolicyService: AudioCommandThread() processing update audio patch list
08-30 23:11:00.808   285  1062 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 23:11:00.815  2029  2577 V AudioRecord: stop()
08-30 23:11:00.823  2029  2577 V AudioRecord: stop()
08-30 23:11:00.823  2029  2577 V AudioRecord: stop()
08-30 23:11:00.825   285  1352 V AudioFlinger: RecordHandle::stop()
08-30 23:11:00.825   285  1352 V AudioFlinger: RecordThread::stop
08-30 23:11:00.825   285  1352 V AudioPolicyManager: releaseInput() 17
08-30 23:11:00.825   285  1352 V AudioPolicyManager: closeInput(17)
08-30 23:11:00.825   285  1352 V AudioFlinger: closeInput() 17
08-30 23:11:00.825   285  1352 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-30 23:11:00.825   285  1352 V AudioFlinger: ThreadBase::exit
08-30 23:11:00.825  2082  2098 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-30 23:11:00.825  2851  2868 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-30 23:11:00.825   285  2602 V AudioFlinger: RecordThread: loop starting
08-30 23:11:00.826   285  2602 V AudioFlinger: RecordThread 0xb39e9000 exiting
08-30 23:11:00.826   892  1949 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-30 23:11:00.826   285  1352 D audio_hw_primary: adev_close_input_stream: enter:stream_handle(0xb546dd40)
08-30 23:11:00.826   285  1352 D audio_hw_primary: in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
08-30 23:11:00.826   285  1352 V audio_hw_primary: in_standby: exit:  status(0)
08-30 23:11:00.826   285  1352 V AudioPolicyService: AudioCommandThread() adding update audio port list
08-30 23:11:00.826   285  1352 V AudioPolicyService: inserting command: 9 at index 0, num commands 0
08-30 23:11:00.827   285  1062 V AudioPolicyService: AudioCommandThread() waking up
08-30 23:11:00.827   285  1062 V AudioPolicyService: AudioCommandThread() processing update audio port list
08-30 23:11:00.827   285  1062 V AudioPolicyService: AudioCommandThread() going to sleep
08-30 23:11:00.827  1773  3601 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-30 23:11:00.827   285  1352 V AudioPolicyManager: releaseInput() exit
08-30 23:11:00.827   285  1352 V AudioFlinger: virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
08-30 23:11:00.827   285  1352 V AudioFlinger: removeClient_l() pid 2029, calling pid 285
08-30 23:11:00.828  3120  3136 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-30 23:11:00.828  1380  2012 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-30 23:11:00.828  2029  2055 V AudioSystem: ioConfigChanged() event 4, ioHandle 17
08-30 23:11:00.828   285  1297 V AudioFlinger: releasing 16 from 2029 for -1
08-30 23:11:00.829   285  1297 V AudioFlinger:  decremented refcount to 0
08-30 23:11:00.829   285  1297 V AudioFlinger: purging stale effects
08-30 23:11:00.833  2029  2587 I HotwordRecognitionRnr: Stopping hotword detection.
08-30 23:11:00.837  2029  2594 I HotwordRecognitionRnr: Hotword detection finished
08-30 23:11:00.888   892  1285 V AlarmManager: ELAPSED_WAKEUP set : Alarm{35b27f1a type 2 when 120000 com.google.android.gms} when 120000
08-30 23:11:00.894  6453  6453 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-30 23:11:01.022  6453  6453 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
08-30 23:11:01.094  6453  6453 I LibraryLoader: Time to load native libraries: 11 ms (timestamps 208-219)
08-30 23:11:01.094  6453  6453 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 23:11:01.133  6453  6453 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2ed09e56}
08-30 23:11:01.134  6453  6453 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 23:11:01.139  6453  6453 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 23:11:01.154  6453  6453 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 23:11:01.157  6453  6453 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 23:11:01.161  6453  6453 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 23:11:01.249  6453  6453 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-30 23:11:01.257  6453  6453 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 23:11:01.257  6453  6453 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 23:11:01.259  6453  6453 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 23:11:01.259  6453  6453 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 23:11:01.259  6453  6453 I Adreno-EGL: Build Date: 03/02/15 Mon
08-30 23:11:01.259  6453  6453 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-30 23:11:01.259  6453  6453 I Adreno-EGL: Remote Branch: 
08-30 23:11:01.259  6453  6453 I Adreno-EGL: Local Patches: 
08-30 23:11:01.259  6453  6453 I Adreno-EGL: Reconstruct Branch: 
08-30 23:11:01.377   285  1352 V AudioPolicyService: registerClient() client 0xb4027d40, uid 10030
08-30 23:11:01.392   892  1054 D BluetoothManagerService: Message: 20
08-30 23:11:01.393   892  1054 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@441a7c3:true
08-30 23:11:01.405  2082  2099 D BluetoothAdapterService(622379972): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@386d333a
,08-30 23:11:01.533  6453  6453 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 23:11:01.546  6453  6453 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 23:11:01.558  6453  6453 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,08-30 23:11:01.562  6453  6453 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-30 23:11:01.562  6453  6453 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-30 23:11:01.579  6453  6453 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-30 23:11:01.587  6453  6453 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 23:11:01.587  6453  6453 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 23:11:01.651  6453  6453 I Activity: Activity.onPostResume() called 
,08-30 23:11:01.659  6453  6504 D OpenGLRenderer: Render dirty regions requested: true
08-30 23:11:01.659  6453  6504 I OpenGLRenderer: Initialized EGL, version 1.4
08-30 23:11:01.665  6453  6504 D OpenGLRenderer: Enabling debug mode 0
,08-30 23:11:01.688  6453  6453 D Atlas   : Validating map...
,08-30 23:11:01.693   892  1641 D SplitWindow: check instance of lgWin Window{324c07b3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 23:11:01.703  6453  6491 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-30 23:11:01.746   892  1641 D InputDispatcher: Focus entered window: Window{324c07b3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 23:11:01.807   892  1973 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,08-30 23:11:01.816   892  1055 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +1s210ms
08-30 23:11:01.817   892  1055 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{76f845b u0 com.test.thalitest/.MainActivity t259} time:120942
08-30 23:11:01.832  6453  6453 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2c722d60 time:120957
,08-30 23:11:01.933  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 23:11:01.933  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 23:11:01.933  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-30 23:11:01.953  6453  6453 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6453
,08-30 23:11:02.485  6453  6453 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 23:11:02.709  6453  6507 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1635609344
,08-30 23:11:02.737  6453  6507 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 23:11:02.737  6453  6507 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 23:11:02.737  6453  6507 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 23:11:02.737  6453  6507 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 23:11:02.737  6453  6507 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 23:11:02.738  6453  6507 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30e19b8d added. We now have 1 listener(s)
08-30 23:11:02.750   892   968 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-30 23:11:02.755  6453  6507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
08-30 23:11:02.756  6453  6507 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
08-30 23:11:02.758  6453  6507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 23:11:02.758  6453  6507 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 23:11:02.764  6453  6507 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 23:11:02.764  6453  6507 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 23:11:02.764  6453  6507 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 23:11:02.764  6453  6507 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-30 23:11:02.764  6453  6507 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 23:11:02.764  6453  6507 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 23:11:02.764  6453  6507 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 23:11:02.764  6453  6507 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 23:11:02.764  6453  6507 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 23:11:02.764  6453  6507 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 23:11:02.764  6453  6507 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 23:11:02.764  6453  6507 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 23:11:02.764  6453  6507 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 23:11:02.764  6453  6507 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 23:11:02.764  6453  6507 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@189bae90 added. We now have 1 listener(s)
08-30 23:11:02.765  6453  6507 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 23:11:02.781  6453  6507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 23:11:02.781  6453  6507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 23:11:02.782  6453  6507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 23:11:02.782  6453  6507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 23:11:02.782  6453  6507 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 23:11:02.786  6453  6507 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 23:11:02.787   892  1641 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 23:11:02.787  6453  6507 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-30 23:11:02.800  2082  3643 D BluetoothAdapterService(622379972): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@386d333a
,08-30 23:11:02.803  6453  6507 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 23:11:02.803  6453  6507 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 23:11:02.803  6453  6507 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 23:11:02.803  6453  6507 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 23:11:02.803  6453  6507 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 23:11:02.803  6453  6507 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 23:11:02.803  6453  6507 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 23:11:02.803  6453  6507 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 23:11:02.803  6453  6507 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 23:11:02.803  6453  6507 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 23:11:02.803  6453  6507 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 23:11:02.805  6453  6507 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 23:11:02.806  6453  6453 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 23:11:02.807  6453  6453 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 23:11:02.849  6453  6453 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 23:11:02.933  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,08-30 23:11:02.934  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,08-30 23:11:02.934  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
08-30 23:11:02.960  6453  6467 I art     : CheckpointMarkThreadRoots callback created = 0x99715160
,08-30 23:11:02.996  6453  6467 I art     : CheckpointMarkThreadRoots callback created = 0x99715130
,08-30 23:11:03.662  6453  6528 W jxcore-log: Initializing JXcore engine
,08-30 23:11:03.664  6453  6528 W jxcore-log: JXcore engine is ready
08-30 23:11:03.789  6528  6528 W Thread-769: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6640]" dev="sockfs" ino=6640 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-30 23:11:03.789  6528  6528 W Thread-769: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 23:11:03.789  6528  6528 W Thread-769: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[4886]" dev="sockfs" ino=4886 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-30 23:11:03.789  6528  6528 W Thread-769: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-30 23:11:03.789  6528  6528 W Thread-769: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-30 23:11:03.789  6528  6528 W Thread-769: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[31056]" dev="sockfs" ino=31056 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-30 23:11:03.818  6453  6528 W jxcore-log: Starting JXcore engine
,08-30 23:11:03.984  6453  6528 W jxcore-log: Platform android
08-30 23:11:03.984  6453  6528 W jxcore-log: 
08-30 23:11:03.984  6453  6528 W jxcore-log: Process ARCH arm
08-30 23:11:03.984  6453  6528 W jxcore-log: 
,08-30 23:11:04.250   297   359 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-30 23:11:04.280  6453  6528 I jxcore-log: JXcore Cordova bridge is ready!
08-30 23:11:04.280  6453  6528 I jxcore-log: 
08-30 23:11:04.280  6453  6528 W jxcore-log: JXcore engine is started
,08-30 23:11:04.284  6453  6507 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-30 23:11:04.286  6453  6453 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-30 23:11:04.939  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 23:11:04.940  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 23:11:04.940  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-30 23:11:05.731  1909  1909 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,08-30 23:11:05.733  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-08-30 23:11:05.733 DNS addrs= 192.168.1.1, 0.0.0.0, 
08-30 23:11:05.736  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 23:11:05.736  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 23:11:05.736  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-30 23:11:05.794   892  1285 V AlarmManager: RTC_WAKEUP set : Alarm{1fb1f6d2 type 0 when 1472591465789 com.google.android.googlequicksearchbox} when 1472591465789
,08-30 23:11:05.939  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 23:11:05.939  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,08-30 23:11:05.940  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-30 23:11:07.943  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 23:11:07.943  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 23:11:07.943  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-30 23:11:07.981  1380  1380 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,08-30 23:11:07.983  1380  1380 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-30 23:11:07.987  1856  1856 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-30 23:11:07.988  1380  1380 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-30 23:11:07.988  1380  1380 I [SystemUI]LGPowerUI: On Skip Timer : true
08-30 23:11:08.010  1380  1380 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 312
08-30 23:11:08.011  1380  1380 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-30 23:11:08.012  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,08-30 23:11:08.013  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-30 23:11:08.013  1380  1380 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 312
08-30 23:11:08.017  1856  2046 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-30 23:11:08.017  1856  2046 D LEDHandler: Battery Level Remaining: 100%
08-30 23:11:08.017  1856  2046 D LEDHandler: Battery Temp: 312, mChargingStatus=5, mChargingStop=false
08-30 23:11:08.019  2082  3474 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 23:11:08.020  1380  1380 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-30 23:11:08.021   892   892 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 23:11:08.021   892   892 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 23:11:08.023   892  1314 D WifiController: battery changed pluggedType: 2
08-30 23:11:08.024   480   480 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-30 23:11:08.024  6317  6317 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-30 23:11:09.255   297   359 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-30 23:11:12.048   892  1285 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3f94ae1e type 2 when 131163 com.google.android.gms} when 131163
,08-30 23:11:12.077  1745  1745 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-30 23:11:12.265  3311  6589 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-30 23:11:12.265  3311  6589 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-30 23:11:12.287  1745  1745 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 23:11:12.798   892  1949 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6596 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,08-30 23:11:12.925   892  1973 I ActivityManager: Process com.android.contacts (pid 6026) has died
,08-30 23:11:12.952  6596  6596 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 23:11:12.953  6596  6596 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 23:11:13.015  6596  6596 I MultiDex: VM with version 2.1.0 has multidex support
08-30 23:11:13.016  6596  6596 I MultiDex: install
08-30 23:11:13.016  6596  6596 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 23:11:13.084   892  1889 I ActivityManager: Process com.lge.lockscreensettings (pid 6080) has died
,08-30 23:11:13.107  6596  6596 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-30 23:11:13.181  6596  6596 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-30 23:11:13.181  6596  6596 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d9ed69a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-30 23:11:13.182  6596  6596 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-30 23:11:13.186  6596  6596 I NotificationManager: com.google.android.gms: cancel(10436) by com.google.android.gms
08-30 23:11:13.186  6596  6596 I NotificationManager: com.google.android.gms: cancel(39789) by com.google.android.gms
08-30 23:11:13.208  6596  6596 D ChimeraCfgMgr: Reading stored module config
,08-30 23:11:13.379  6596  6610 I art     : Background sticky concurrent mark sweep GC freed 20304(1020KB) AllocSpace objects, 2(32KB) LOS objects, 6% free, 10MB/11MB, paused 9.268ms total 108.508ms
,08-30 23:11:13.396  1745  2334 I art     : Explicit concurrent mark sweep GC freed 61128(3MB) AllocSpace objects, 19(304KB) LOS objects, 40% free, 14MB/24MB, paused 9.163ms total 227.316ms
,08-30 23:11:13.425  6596  6596 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-30 23:11:13.425  6596  6596 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
08-30 23:11:13.440  6596  6610 I art     : CheckpointMarkThreadRoots callback created = 0xb002d370
08-30 23:11:13.460  6596  6615 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-30 23:11:13.497  6596  6610 I art     : CheckpointMarkThreadRoots callback created = 0xb002d360
,08-30 23:11:13.527  1745  1745 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=abfbffb8-0583-40e5-800f-7908ba73944b
,08-30 23:11:13.546   892  1020 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-30 23:11:13.546   892  1020 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-30 23:11:13.546   892  1020 D sensors_hal_Time: tsOffsetIs: Apps: 132670750839; DSPS: 4445187; Offset : -2993603550
,08-30 23:11:13.563  1745  1745 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-30 23:11:13.565  1745  1745 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-30 23:11:13.619   285  1354 D WVCdm   : Instantiating CDM.
,08-30 23:11:13.620   285  1352 I WVCdm   : CdmEngine::OpenSession
08-30 23:11:13.620   285  1352 I WVCdm   : Level3 Library Dec 11 2014 16:13:16
,08-30 23:11:13.653   285  1352 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
08-30 23:11:13.654   285  1352 W WVCdm   : Properties::GetOEMCryptoPath: null. applies level3
08-30 23:11:13.654   285  1352 W WVCdm   : L1 library not specified. Falling Back to L3
08-30 23:11:13.734  1745  2548 W GCoreFlp: No location to return for getLastLocation()
,08-30 23:11:13.752   285  1352 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-30 23:11:13.754   285  1297 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-30 23:11:13.754   285  1297 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-30 23:11:13.754   285  1297 I WVCdm   : CdmEngine::GenerateKeyRequest
08-30 23:11:13.771   285  1297 D WVCdm   : PrepareKeyRequest: nonce=2979807179
,08-30 23:11:13.788  3311  6590 D UdcContextInitService: registered all accounts: true
08-30 23:11:13.791  1745  2493 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 23:11:13.809  1745  2387 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-30 23:11:13.833   892  1361 I art     : Explicit concurrent mark sweep GC freed 56297(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.917ms total 175.849ms
08-30 23:11:13.926  6596  6611 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 23:11:13.926  6596  6611 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-30 23:11:13.926  6596  6611 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 23:11:13.926  6596  6611 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-30 23:11:13.927   281  1006 E BandwidthController: [LG DATA] No such appUid: 10006
08-30 23:11:13.927   281  1006 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
08-30 23:11:13.927   281  6630 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-30 23:11:13.927   281  6630 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-30 23:11:13.928   281  6630 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
,08-30 23:11:13.929   281  6630 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-30 23:11:13.956  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 23:11:13.957  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 23:11:13.957  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,08-30 23:11:13.976   281  6630 D libc-netbsd: res_queryN name = xxxxx succeed
,08-30 23:11:13.978  6596  6611 I System.out: propertyValue:false
08-30 23:11:14.045  6596  6611 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,08-30 23:11:14.046  6596  6611 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-30 23:11:14.261   297   359 I ThermalEngine: Sensor:pa_therm0:33000 mC
,08-30 23:11:14.738  6634  6634 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-30 23:11:14.833  6634  6634 I dex2oat : dex2oat took 92.700ms (threads: 4)
,08-30 23:11:14.851  6596  6611 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 23:11:14.851  6596  6611 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 23:11:14.851  6596  6611 I Adreno-EGL: Build Date: 03/02/15 Mon
08-30 23:11:14.851  6596  6611 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-30 23:11:14.851  6596  6611 I Adreno-EGL: Remote Branch: 
08-30 23:11:14.851  6596  6611 I Adreno-EGL: Local Patches: 
08-30 23:11:14.851  6596  6611 I Adreno-EGL: Reconstruct Branch: 
08-30 23:11:14.960  6596  6611 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 23:11:14.960  6596  6611 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 23:11:14.960  6596  6611 I Adreno-EGL: Build Date: 03/02/15 Mon
08-30 23:11:14.960  6596  6611 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-30 23:11:14.960  6596  6611 I Adreno-EGL: Remote Branch: 
08-30 23:11:14.960  6596  6611 I Adreno-EGL: Local Patches: 
08-30 23:11:14.960  6596  6611 I Adreno-EGL: Reconstruct Branch: 
,08-30 23:11:15.082  6596  6611 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 23:11:15.082  6596  6611 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 23:11:15.082  6596  6611 I Adreno-EGL: Build Date: 03/02/15 Mon
08-30 23:11:15.082  6596  6611 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-30 23:11:15.082  6596  6611 I Adreno-EGL: Remote Branch: 
08-30 23:11:15.082  6596  6611 I Adreno-EGL: Local Patches: 
08-30 23:11:15.082  6596  6611 I Adreno-EGL: Reconstruct Branch: 
,08-30 23:11:15.588  1745  6592 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 23:11:15.589  1745  6592 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-30 23:11:15.589  1745  6592 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 23:11:15.589  1745  6592 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-30 23:11:15.589   281  1006 E BandwidthController: [LG DATA] No such appUid: 10006
08-30 23:11:15.589   281  1006 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
08-30 23:11:15.595   281  6649 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-30 23:11:15.595   281  6649 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-30 23:11:15.595   281  6649 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-30 23:11:15.595   281  6649 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-30 23:11:15.595   281  6649 D libc-netbsd: res_queryN name = xxxxx succeed
,08-30 23:11:15.597  1745  6592 I System.out: propertyValue:false
08-30 23:11:15.653  1745  6592 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 23:11:15.653  1745  6592 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,08-30 23:11:15.926  1745  2387 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-30 23:11:15.937  1745  2387 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
08-30 23:11:15.942  1745  2387 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-30 23:11:13.930+0200, stopTime=2016-08-30 23:11:15.938+0200, duration=2008ms
,08-30 23:11:16.005  1745  6651 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 23:11:16.006  1745  6651 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-30 23:11:16.006  1745  6651 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 23:11:16.006  1745  6651 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-30 23:11:16.006   281  1006 E BandwidthController: [LG DATA] No such appUid: 10006
08-30 23:11:16.006   281  1006 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
,08-30 23:11:16.006   281  6656 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-30 23:11:16.006   281  6656 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-30 23:11:16.007   281  6656 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-30 23:11:16.007   281  6656 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-30 23:11:16.007   281  6656 D libc-netbsd: res_queryN name = xxxxx succeed
08-30 23:11:16.011  1745  6651 I System.out: propertyValue:false
08-30 23:11:16.015   285  1354 I WVCdm   : CdmEngine::CloseSession
08-30 23:11:16.019   285  1354 I WVCdm   : L3 Terminate.
,08-30 23:11:16.025   892  1917 I ActivityManager: Process com.google.android.apps.docs (pid 6274) has died
,08-30 23:11:16.083  3948  4254 I art     : Explicit concurrent mark sweep GC freed 1323(44KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.204ms total 35.935ms
,08-30 23:11:16.487  1745  2387 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-30 23:11:16.676  1745  6671 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-30 23:11:16.678  1745  6669 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-30 23:11:16.700  1745  6671 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-30 23:11:16.703  1745  6669 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-30 23:11:16.733  1745  6671 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-30 23:11:16.735  1745  6669 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-30 23:11:16.735  1745  6669 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
08-30 23:11:16.739  1745  6669 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
08-30 23:11:16.785   892  1347 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 23:11:16.879  1745  6669 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 23:11:16.879  1745  6669 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-30 23:11:16.879  1745  6669 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-30 23:11:16.879  1745  6669 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-30 23:11:16.880   281  1006 E BandwidthController: [LG DATA] No such appUid: 10006
08-30 23:11:16.880   281  1006 D DnsProxyListener: App 10006 tries DNS query. Accept family:0 protocol:0
08-30 23:11:16.880   281  6676 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-30 23:11:16.880   281  6676 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,08-30 23:11:16.880   281  6676 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-30 23:11:16.881   281  6676 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-30 23:11:16.881   281  6676 D libc-netbsd: res_queryN name = xxxxx succeed
08-30 23:11:16.882  1745  6669 I System.out: propertyValue:false
08-30 23:11:17.201   892   968 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 23:11:17.439   892  1347 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 23:11:17.664   892   968 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 23:11:17.848   892  2185 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 23:11:18.089   892  1347 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-30 23:11:18.286  1745  2387 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-30 23:11:18.506  1745  2387 I art     : Explicit concurrent mark sweep GC freed 49279(2MB) AllocSpace objects, 25(422KB) LOS objects, 40% free, 15MB/25MB, paused 1.783ms total 141.831ms
08-30 23:11:18.506  1745  1766 I art     : WaitForGcToComplete blocked for 110.033ms for cause HeapTrim
,08-30 23:11:19.266   297   359 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-30 23:11:19.585  2851  2851 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,08-30 23:11:19.599  2851  2851 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,08-30 23:11:19.967  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 23:11:19.967  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 23:11:19.967  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-30 23:11:20.799  1909  1909 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,08-30 23:11:20.802  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-08-30 23:11:20.802 DNS addrs= 192.168.1.1, 0.0.0.0, 
08-30 23:11:20.804  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 23:11:20.804  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 23:11:20.804  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-30 23:11:23.065  1380  1380 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,08-30 23:11:23.067  1380  1380 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-30 23:11:23.068  1380  1380 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-30 23:11:23.068  1380  1380 I [SystemUI]LGPowerUI: On Skip Timer : true
08-30 23:11:23.068  1856  1856 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-30 23:11:23.121  1380  1380 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 314
08-30 23:11:23.121  1380  1380 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-30 23:11:23.121  1380  1380 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 314
,08-30 23:11:23.122  1380  1380 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-30 23:11:23.123  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-30 23:11:23.124  1856  2046 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-30 23:11:23.124  1856  2046 D LEDHandler: Battery Level Remaining: 100%
08-30 23:11:23.124  1856  2046 D LEDHandler: Battery Temp: 314, mChargingStatus=5, mChargingStop=false
08-30 23:11:23.126  2082  3474 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 23:11:23.126  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-30 23:11:23.128   892   892 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 23:11:23.128   892   892 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 23:11:23.128   892  1314 D WifiController: battery changed pluggedType: 2
08-30 23:11:23.132  6317  6317 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-30 23:11:23.134   480   480 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-30 23:11:23.161  1380  1380 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 314
08-30 23:11:23.161  1380  1380 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-30 23:11:23.161  1380  1380 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 314
,08-30 23:11:23.164  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-30 23:11:23.164  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-30 23:11:23.165  1856  2046 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-30 23:11:23.165  1856  2046 D LEDHandler: Battery Level Remaining: 100%
08-30 23:11:23.165  1856  2046 D LEDHandler: Battery Temp: 314, mChargingStatus=5, mChargingStop=false
08-30 23:11:23.167  1380  1380 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-30 23:11:23.167  2082  3474 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-30 23:11:23.169   892   892 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 23:11:23.169   892   892 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 23:11:23.169   892  1314 D WifiController: battery changed pluggedType: 2
08-30 23:11:23.170  6317  6317 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-30 23:11:23.830  1909  1909 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,08-30 23:11:23.832  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 23:11:23.832  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 23:11:23.832  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-30 23:11:23.832  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-08-30 23:11:23.832 DNS addrs= 192.168.1.1, 0.0.0.0, 
08-30 23:11:23.971  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 23:11:23.971  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 23:11:23.972  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-30 23:11:24.271   297   359 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-30 23:11:24.973  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 23:11:24.973  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 23:11:24.974  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-30 23:11:26.865   892  1057 I PowerManagerService: ALS enabled for SRE
08-30 23:11:26.865   892  1057 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (25990 ms ago)
,08-30 23:11:26.921   892  1348 D qdlights: set_light_backlight: 252
,08-30 23:11:26.928   892  1348 D qdlights: set_light_backlight: 249
08-30 23:11:26.945   892  1348 D qdlights: set_light_backlight: 245
,08-30 23:11:26.961   892  1348 D qdlights: set_light_backlight: 242
,08-30 23:11:26.978  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 23:11:26.978   892  1348 D qdlights: set_light_backlight: 239
08-30 23:11:26.978  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 23:11:26.978  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,08-30 23:11:26.995   892  1348 D qdlights: set_light_backlight: 235
,08-30 23:11:27.011   892  1348 D qdlights: set_light_backlight: 232
,08-30 23:11:27.028   892  1348 D qdlights: set_light_backlight: 229
,08-30 23:11:27.045   892  1348 D qdlights: set_light_backlight: 225
,08-30 23:11:27.061   892  1348 D qdlights: set_light_backlight: 222
,08-30 23:11:27.078   892  1348 D qdlights: set_light_backlight: 219
,08-30 23:11:27.096   892  1348 D qdlights: set_light_backlight: 215
,08-30 23:11:27.111   892  1348 D qdlights: set_light_backlight: 212
,08-30 23:11:27.128   892  1348 D qdlights: set_light_backlight: 209
,08-30 23:11:27.145   892  1348 D qdlights: set_light_backlight: 205
,08-30 23:11:27.161   892  1348 D qdlights: set_light_backlight: 202
,08-30 23:11:27.178   892  1348 D qdlights: set_light_backlight: 199
,08-30 23:11:27.195   892  1348 D qdlights: set_light_backlight: 195
,08-30 23:11:27.211   892  1348 D qdlights: set_light_backlight: 192
,08-30 23:11:27.228   892  1348 D qdlights: set_light_backlight: 189
,08-30 23:11:27.245   892  1348 D qdlights: set_light_backlight: 185
,08-30 23:11:27.261   892  1348 D qdlights: set_light_backlight: 182
,08-30 23:11:27.278   892  1348 D qdlights: set_light_backlight: 179
,08-30 23:11:27.295   892  1348 D qdlights: set_light_backlight: 175
,08-30 23:11:27.311   892  1348 D qdlights: set_light_backlight: 172
,08-30 23:11:27.328   892  1348 D qdlights: set_light_backlight: 169
,08-30 23:11:27.345   892  1348 D qdlights: set_light_backlight: 165
,08-30 23:11:27.361   892  1348 D qdlights: set_light_backlight: 162
,08-30 23:11:27.378   892  1348 D qdlights: set_light_backlight: 159
,08-30 23:11:27.395   892  1348 D qdlights: set_light_backlight: 155
,08-30 23:11:27.411   892  1348 D qdlights: set_light_backlight: 152
,08-30 23:11:27.428   892  1348 D qdlights: set_light_backlight: 149
,08-30 23:11:27.445   892  1348 D qdlights: set_light_backlight: 145
,08-30 23:11:27.461   892  1348 D qdlights: set_light_backlight: 142
,08-30 23:11:27.478   892  1348 D qdlights: set_light_backlight: 139
,08-30 23:11:27.495   892  1348 D qdlights: set_light_backlight: 135
,08-30 23:11:27.511   892  1348 D qdlights: set_light_backlight: 132
,08-30 23:11:27.528   892  1348 D qdlights: set_light_backlight: 129
,08-30 23:11:27.545   892  1348 D qdlights: set_light_backlight: 125
,08-30 23:11:27.561   892  1348 D qdlights: set_light_backlight: 122
,08-30 23:11:27.578   892  1348 D qdlights: set_light_backlight: 119
,08-30 23:11:27.595   892  1348 D qdlights: set_light_backlight: 115
,08-30 23:11:27.611   892  1348 D qdlights: set_light_backlight: 112
,08-30 23:11:27.628   892  1348 D qdlights: set_light_backlight: 109
,08-30 23:11:27.645   892  1348 D qdlights: set_light_backlight: 105
,08-30 23:11:27.661   892  1348 D qdlights: set_light_backlight: 102
,08-30 23:11:27.678   892  1348 D qdlights: set_light_backlight: 99
,08-30 23:11:27.696   892  1348 D qdlights: set_light_backlight: 95
,08-30 23:11:27.711   892  1348 D qdlights: set_light_backlight: 92
,08-30 23:11:27.728   892  1348 D qdlights: set_light_backlight: 89
,08-30 23:11:27.745   892  1348 D qdlights: set_light_backlight: 85
,08-30 23:11:27.761   892  1348 D qdlights: set_light_backlight: 82
,08-30 23:11:27.778   892  1348 D qdlights: set_light_backlight: 79
,08-30 23:11:27.795   892  1348 D qdlights: set_light_backlight: 75
,08-30 23:11:27.811   892  1348 D qdlights: set_light_backlight: 72
,08-30 23:11:27.828   892  1348 D qdlights: set_light_backlight: 69
,08-30 23:11:27.845   892  1348 D qdlights: set_light_backlight: 65
,08-30 23:11:27.861   892  1348 D qdlights: set_light_backlight: 62
,08-30 23:11:27.878   892  1348 D qdlights: set_light_backlight: 59
,08-30 23:11:27.895   892  1348 D qdlights: set_light_backlight: 55
,08-30 23:11:27.911   892  1348 D qdlights: set_light_backlight: 52
,08-30 23:11:27.928   892  1348 D qdlights: set_light_backlight: 49
,08-30 23:11:27.945   892  1348 D qdlights: set_light_backlight: 45
,08-30 23:11:27.961   892  1348 D qdlights: set_light_backlight: 42
,08-30 23:11:27.978   892  1348 D qdlights: set_light_backlight: 39
,08-30 23:11:27.995   892  1348 D qdlights: set_light_backlight: 35
,08-30 23:11:28.011   892  1348 D qdlights: set_light_backlight: 32
,08-30 23:11:28.028   892  1348 D qdlights: set_light_backlight: 29
,08-30 23:11:28.045   892  1348 D qdlights: set_light_backlight: 25
,08-30 23:11:28.061   892  1348 D qdlights: set_light_backlight: 22
,08-30 23:11:28.078   892  1348 D qdlights: set_light_backlight: 19
,08-30 23:11:28.095   892  1348 D qdlights: set_light_backlight: 15
,08-30 23:11:28.111   892  1348 D qdlights: set_light_backlight: 12
,08-30 23:11:28.129   892  1348 D qdlights: set_light_backlight: 10
,08-30 23:11:28.286  6453  6528 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 23:11:28.286  6453  6528 I jxcore-log: 
,08-30 23:11:28.290  6453  6528 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 23:11:28.290  6453  6528 I jxcore-log: 
08-30 23:11:28.296  2082  3643 D BluetoothAdapterService(622379972): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@386d333a
08-30 23:11:28.296  6453  6528 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 23:11:28.296  6453  6528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 23:11:28.296  6453  6528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 23:11:28.296  6453  6528 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 23:11:28.296  6453  6528 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 23:11:28.296  6453  6528 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 23:11:28.296  6453  6528 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 23:11:28.296  6453  6528 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 23:11:28.298  2082  3643 D BluetoothAdapterService(622379972): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@386d333a
,08-30 23:11:28.303  6453  6528 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 23:11:28.306  6453  6528 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 23:11:28.306  6453  6528 I jxcore-log: 
08-30 23:11:28.308  6453  6528 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 23:11:28.308  6453  6528 I jxcore-log: 
,08-30 23:11:28.883  6453  6528 I jxcore-log: Running unit tests
08-30 23:11:28.883  6453  6528 I jxcore-log: 
,08-30 23:11:28.884  6453  6528 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-30 23:11:28.884  6453  6528 I jxcore-log: Failed to execute UT.
08-30 23:11:28.884  6453  6528 I jxcore-log: 
08-30 23:11:28.886  6453  6528 I jxcore-log: Unit Test app is loaded
08-30 23:11:28.886  6453  6528 I jxcore-log: 
08-30 23:11:28.900  6453  6528 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 23:11:28.900  6453  6528 I jxcore-log: 
,08-30 23:11:28.906  6453  6528 I jxcore-log: My device name is: LGE-LG-D722
08-30 23:11:28.906  6453  6528 I jxcore-log: 
08-30 23:11:28.908  6453  6528 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 23:11:28.908  6453  6528 I jxcore-log: 
08-30 23:11:28.909  6453  6453 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 23:11:28.984  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 23:11:28.984  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 23:11:28.984  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,08-30 23:11:29.275   297   359 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-30 23:11:29.859  1909  1909 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,08-30 23:11:29.859  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-08-30 23:11:29.859 DNS addrs= 192.168.1.1, 0.0.0.0, 
08-30 23:11:29.861  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 23:11:29.862  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 23:11:29.862  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-30 23:11:32.872  1909  1909 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,08-30 23:11:32.875  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-08-30 23:11:32.875 DNS addrs= 192.168.1.1, 0.0.0.0, 
08-30 23:11:32.876  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 23:11:32.876  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 23:11:32.876  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
08-30 23:11:33.022  6453  6528 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 23:11:33.022  6453  6528 I jxcore-log: 
,08-30 23:11:33.546   892  1020 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-30 23:11:33.546   892  1020 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-30 23:11:33.546   892  1020 D sensors_hal_Time: tsOffsetIs: Apps: 152671537394; DSPS: 5100572; Offset : -2993579935
,08-30 23:11:33.748  6453  6528 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 23:11:33.748  6453  6528 I jxcore-log: 
,08-30 23:11:33.790  6453  6528 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 23:11:33.790  6453  6528 I jxcore-log: 
,08-30 23:11:33.864   892  1057 I PowerManagerService: ALS enabled for SRE
08-30 23:11:33.865   892  1057 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (32990 ms ago)
,08-30 23:11:33.865   892  1057 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-30 23:11:33.887   892  1057 I PowerManagerService: ALS enabled for SRE
08-30 23:11:33.887   892  1057 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (33012 ms ago)
,08-30 23:11:33.899   892  1057 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,08-30 23:11:33.907   892  1057 I PowerManagerService: Sleeping (uid 1000)...
08-30 23:11:33.908   892  1057 D LPWGController: [updateScreenState] screen on = false
08-30 23:11:33.916   892  1057 D LPWGController: disable proximity sensor
,08-30 23:11:33.916   892  1057 D LPWGController: enable proximity sensor
08-30 23:11:33.939   892  1057 I SensorManager: registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@34a894d5] by com.android.server.power.ProximitySensorListener.enable():120
,08-30 23:11:33.949   892  1057 I sensors_hal_Ctx: batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
08-30 23:11:33.949   892  1057 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
08-30 23:11:33.949   892  1057 D sensors_hal_SAM: batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
08-30 23:11:33.949   892  1057 I sensors_hal_Ctx: activate: handle is 48, enable
08-30 23:11:33.950   892  1057 V sensors_hal_Ctx: activate sensors is 1400000000000
08-30 23:11:33.950   892  1057 D sensors_hal_Thresh: enable: handle=48
08-30 23:11:33.950   892  1057 I sensors_hal_SAM: sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
08-30 23:11:33.950   892  1057 D sensors_hal_Util: waitForResponse: timeout=1000
08-30 23:11:33.957   892  1021 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
08-30 23:11:33.957   892  1021 D sensors_hal_Thresh: processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
,08-30 23:11:33.958   892  1057 D sensors_hal_Thresh: enable: Received response: 0
08-30 23:11:33.958   892  1057 D PowerManagerServiceEx: updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (33084 ms ago)
08-30 23:11:33.980   892  1057 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 23:11:33.980   892  1057 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 23:11:33.980   892  1057 I Adreno-EGL: Build Date: 03/02/15 Mon
08-30 23:11:33.980   892  1057 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-30 23:11:33.980   892  1057 I Adreno-EGL: Remote Branch: 
08-30 23:11:33.980   892  1057 I Adreno-EGL: Local Patches: 
08-30 23:11:33.980   892  1057 I Adreno-EGL: Reconstruct Branch: 
,08-30 23:11:34.005   246  1287 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1109 us)
,08-30 23:11:34.186   425  1012 I Sensors : sns_pwr.c(273):acquiring wakelock
,08-30 23:11:34.188   892  1021 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
08-30 23:11:34.190   892  1021 I sensors_hal_SAM: SAMSensor_sensor1_cb: acquired wakelock sensor_ind
08-30 23:11:34.190   892  1021 D sensors_hal_Thresh: processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
08-30 23:11:34.190   892  1021 D sensors_hal_Thresh: processInd: handle 48, count=1
08-30 23:11:34.190   892  1021 V sensors_hal_Thresh: processInd:sensor android.sensor.proximity (wake_up)
08-30 23:11:34.190   892  1021 I sensors_hal_Thresh: processInd : proximity state changed - FAR
08-30 23:11:34.190   892  1049 D sensors_hal_Ctx: poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
08-30 23:11:34.190   892  1049 D sensors_hal_Ctx: poll: count: 256
08-30 23:11:34.190   892  1049 I sensors_hal_Ctx: poll: released wakelock sensor_ind
08-30 23:11:34.190   892  1049 D sensors_hal_Util: waitForResponse: timeout=0
08-30 23:11:34.191   892  1057 D LPWGController: proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
08-30 23:11:34.192   892  1057 I LPWGController: current mode = 1  value = 1 1
08-30 23:11:34.192   892  1057 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
08-30 23:11:34.280   297   359 I ThermalEngine: Sensor:pa_therm0:34000 mC
,08-30 23:11:34.293   892  1057 I LPWGController: [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,08-30 23:11:34.530   892  1348 D qdlights: set_light_backlight: 0
,08-30 23:11:34.548   892  1057 I SensorManager: removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,08-30 23:11:34.555   892  1057 I sensors_hal_Ctx: activate: handle is 46, disable
08-30 23:11:34.555   892  1057 V sensors_hal_Ctx: activate sensors is 1000000000000
08-30 23:11:34.555   892  1057 D sensors_hal_LP2: enable: handle=46
08-30 23:11:34.555   892  1057 D sensors_hal_LP2: enable: Disabling sensor handle=46
08-30 23:11:34.555   892  1057 I sensors_hal_SAM: sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
08-30 23:11:34.557   246   246 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6482000
08-30 23:11:34.557   246   246 D qdhwcomposer: hwc_blank: Blanking display: 0
08-30 23:11:34.563   892  1055 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
08-30 23:11:34.564   892   892 V ActivityManager: Display changed displayId=0
,08-30 23:11:34.619  1773  1773 D DSDPConnection: Display #0 changed.
,08-30 23:11:34.665   892  1045 V sensors_hal_SAM: SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
08-30 23:11:34.665   892  1045 D sensors_hal_LP2: processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,08-30 23:11:34.781   246   246 D qdhwcomposer: hwc_blank: Done blanking display: 0
08-30 23:11:34.781   892  1348 D SurfaceControl: Excessive delay in setPowerMode(): 224ms
,08-30 23:11:34.783   246   697 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
08-30 23:11:34.783   892  1348 I QCOM PowerHAL: Got set_interactive hint
08-30 23:11:34.794  6453  6453 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-30 23:11:34.794  6453  6453 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-30 23:11:34.800  1380  1805 D KeyguardViewMediator: onScreenTurnedOff(3)
08-30 23:11:34.806  1330  1346 D SmartCoverViewMediator: onScreenTurnedOff(3)
,08-30 23:11:34.817  1330  1346 D SmartCoverViewMediator: notifyScreenOffLocked
08-30 23:11:34.818  1330  1330 D SmartCoverViewMediator: handleNotifyScreenOFF
08-30 23:11:34.818  1380  1805 D KeyguardViewMediator: notifyScreenOffLocked
,08-30 23:11:34.835  6453  6453 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@240ac75c Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@9b2a7d3, 16908290=android.view.AbsSavedState$1@9b2a7d3}, android:focusedViewId=100}]}]
08-30 23:11:34.835  6453  6453 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-30 23:11:34.836  6453  6453 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-30 23:11:34.836  6453  6453 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-30 23:11:34.840  1380  1805 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 1, timeout = 5000
08-30 23:11:34.841  1380  1380 D KeyguardViewMediator: handleNotifyScreenOff
08-30 23:11:34.871  1380  1380 D ScreenTurnOffBySensor: unregisterProximitySensor
,08-30 23:11:34.885  1909  1909 I QCNEJ   : |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,08-30 23:11:34.887  1909  1909 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-08-30 23:11:34.887 DNS addrs= 192.168.1.1, 0.0.0.0, 
08-30 23:11:34.894  1380  1380 D StatusBarWindowView: onScreenTurnedOff why = 3
08-30 23:11:34.901  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 23:11:34.901  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 23:11:34.901  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
08-30 23:11:34.902   892   892 D WifiServerServiceExt: sendKtScanInterval  mRtspPlay : false
08-30 23:11:34.908   285  1297 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=on, calling pid 892
08-30 23:11:34.909   285  1297 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-30 23:11:34.909   285  1297 V voice   : voice_set_parameters: enter: screen_state=on
08-30 23:11:34.908  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
08-30 23:11:34.910  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
08-30 23:11:34.910   285  1297 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=on
08-30 23:11:34.910   285  1297 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 23:11:34.910   285  1297 V voice   : voice_set_parameters: exit with code(0)
08-30 23:11:34.910   285  1297 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=on
08-30 23:11:34.911   285  1297 V msm8974_platform: platform_set_parameters: enter: screen_state=on
08-30 23:11:34.911   285  1297 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 23:11:34.911   285  1297 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 23:11:34.911   285  1297 E lge_audio_pcm_dump: lge_set_dump_config: exit dump_config : 0
08-30 23:11:34.911   285  1297 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
08-30 23:11:34.911   285  1297 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 23:11:34.911  1380  1380 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,08-30 23:11:34.922  1380  1380 D KeyguardUpdateMonitor: handleTimeUpdate
08-30 23:11:34.922  1380  1380 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_ON
08-30 23:11:34.923   892  1308 I WifiServerServiceExt: set CMD_KT_SCAN_INTERVAL
08-30 23:11:35.460   892  1044 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
,08-30 23:11:35.504   892  1973 D SplitWindow: check instance of lgWin Window{1b82ce78 u0 SearchPanel}
,08-30 23:11:35.513  1909  1909 I QCNEJ   : |CORE| sendScreenState: state:true
,08-30 23:11:35.523  1856  2046 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
08-30 23:11:35.526  1856  2046 D LEDService: stopPatternFlashing()
,08-30 23:11:35.528  1856  2046 D qdlights: set_light_notifications: 0,0,0,0,3
08-30 23:11:35.529  1856  2046 I LEDService: getCurrentHighestLGLedRecord : size = 1
08-30 23:11:35.529  1856  2046 D qdlights: set_light_notifications: 0,0,0,0,3
08-30 23:11:35.531  1856  2046 I LEDService: updateLightsLocked : turn off led
08-30 23:11:35.531  1856  2046 D qdlights: set_light_notifications: 0,0,0,0,3
08-30 23:11:35.532  1856  2046 D LEDHandler: RESTART MSG
08-30 23:11:35.533   892  1995 D InputDispatcher: Window went away: Window{200a3977 u0 SearchPanel}
08-30 23:11:35.536  1380  1380 I [SystemUI]Clock: onReceive = android.intent.action.SCREEN_ON
08-30 23:11:35.559  1380  1380 I LgeClockWidgetControlView: time changed, timezoneChanged : false
,08-30 23:11:35.571  1856  1856 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,08-30 23:11:35.573  1856  1856 D Cliptray Service: lockStatus = 0
08-30 23:11:35.577  1826  1826 D LNfcService: action : android.intent.action.SCREEN_ON
08-30 23:11:35.584  1826  6702 D NfcServiceNXP: mScreenState : 3, mInProvisionMode : false
,08-30 23:11:35.586  1826  6702 D NfcServiceNXP: Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
08-30 23:11:35.586  1826  6702 D LNfcService: isRequireNfcCRouting() return true
08-30 23:11:35.586  1826  6702 D LNfcService: isHCERoutingtoHost() return : true
08-30 23:11:35.586  1826  6702 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
08-30 23:11:35.586  1826  6702 D NfcService: mEnableLPD: true
08-30 23:11:35.586  1826  6702 D NfcService: mEnableReader: false
08-30 23:11:35.586  1826  6702 D NfcService: mEnableHostRouting: true
08-30 23:11:35.586  1826  6702 D NfcService: newParams.techmask= mTechMask: default
08-30 23:11:35.586  1826  6702 D NfcService: mEnableLPD: true
08-30 23:11:35.586  1826  6702 D NfcService: mEnableReader: false
08-30 23:11:35.586  1826  6702 D NfcService: mEnableHostRouting: true
08-30 23:11:35.586  1826  6702 D NfcService: screenState= 3
08-30 23:11:35.586  1826  6702 D NfcService: Discovery configuration equal, not updating.
08-30 23:11:35.589   892   892 D Ulp_jni : JNI:system_update. Event-0
,08-30 23:11:35.636  1773  1773 V PhoneApp: onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
08-30 23:11:35.648   892   892 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 23:11:35.648   892   892 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-30 23:11:35.648   892   892 D WifiOffDelayIfNotUsed: ACTION_SCREEN_ON
08-30 23:11:35.654  2835  2835 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 23:11:35
08-30 23:11:35.656  2835  2835 D WeatherService: 2 : ACTION screen on
08-30 23:11:35.658  2835  2835 D WeatherService: 2 : shouldTimeTickRegistered : false
08-30 23:11:35.668  2835  2835 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-30 23:11:35.668  2835  2835 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 23:11:35
,08-30 23:11:35.678  4064  4064 D AppCleanupService: android.intent.action.SCREEN_ON
08-30 23:11:35.686   425   443 I Sensors : sns_pwr.c(301):releasing wakelock
,08-30 23:11:35.701   285  1354 V AudioFlinger: setParameters(): io 0, keyvalue screen_state=off, calling pid 892
,08-30 23:11:35.705   285  1354 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-30 23:11:35.705   285  1354 V voice   : voice_set_parameters: enter: screen_state=off
08-30 23:11:35.705   285  1354 V compress_voip: voice_extn_compress_voip_set_parameters: enter: screen_state=off
08-30 23:11:35.705   285  1354 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-30 23:11:35.705   285  1354 V voice   : voice_set_parameters: exit with code(0)
08-30 23:11:35.705   285  1354 V msm8974_platform_lge: LGE_platform_set_parameters: enter: screen_state=off
08-30 23:11:35.705   285  1354 V msm8974_platform: platform_set_parameters: enter: screen_state=off
08-30 23:11:35.705   285  1354 V msm8974_platform: platform_set_parameters: exit with code(0)
08-30 23:11:35.705   285  1354 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-30 23:11:35.705   285  1354 D audio_hw_extn: audio_extn_set_anc_parameters: anc_enabled:0
08-30 23:11:35.705   285  1354 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-30 23:11:35.707   892  1314 D WifiController: CMD_SCREEN_OFF 
08-30 23:11:35.707   892  1314 D WifiController: shouldWifiStayAwake TRUE
08-30 23:11:35.712  1380  1380 I [SystemUI]LGPowerUI: onReceive = android.intent.action.SCREEN_OFF
08-30 23:11:35.713   892  1044 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,08-30 23:11:35.747  1909  1909 I QCNEJ   : |CORE| sendScreenState: state:false
08-30 23:11:35.748  1856  2046 I LEDService: getCurrentHighestLGLedRecord() start. size = 1
08-30 23:11:35.749  1856  2046 D LEDService: stopPatternFlashing()
08-30 23:11:35.749  1856  2046 D qdlights: set_light_notifications: 0,0,0,0,3
,08-30 23:11:35.750  1856  2046 I LEDService: getCurrentHighestLGLedRecord : size = 1
08-30 23:11:35.750  1856  2046 D qdlights: set_light_notifications: 0,0,0,0,3
08-30 23:11:35.752  1856  2046 I LEDService: updateLightsLocked : turn on led
08-30 23:11:35.753  1856  2046 E LEDService: parsePattern()::Unknown Pattern ID or invalid PatternFilePath
08-30 23:11:35.753  1856  2046 E LEDService: Can't handle this request of patternId:0
08-30 23:11:35.753  1856  2046 D LEDHandler: RESTART MSG
08-30 23:11:35.754  1856  1856 D VolumeVibrator: clear
08-30 23:11:35.756  1856  1856 I Cliptray Service: cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
08-30 23:11:35.756  1826  1826 D LNfcService: action : android.intent.action.SCREEN_OFF
,08-30 23:11:35.766  1826  2202 D NfcServiceNXP: mScreenState : 1, mInProvisionMode : false
08-30 23:11:35.779  1950  1950 I [LGHome]EVENT: [Launcher.java:1711:onReceive()]Screen Off
,08-30 23:11:35.792  1773  1773 V PhoneApp: onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,08-30 23:11:35.798   892   892 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 23:11:35.798   892   892 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-30 23:11:35.798   892   892 D WifiOffDelayIfNotUsed: ACTION_SCREEN_OFF
08-30 23:11:35.799  2835  2835 D WeatherService: 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 23:11:35
08-30 23:11:35.799  2835  2835 D WeatherService: 2 : ACTION screen off
08-30 23:11:35.803  2835  2835 D WeatherService: 2 : TimeTick Receiver Unregister
,08-30 23:11:35.805  2835  2835 D WeatherService: 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 23:11:35
08-30 23:11:35.808  4064  4064 D AppCleanupService: android.intent.action.SCREEN_OFF
08-30 23:11:35.818  4064  6705 D AppCleanupService: AppUsageStatsSaveTask
,08-30 23:11:35.867  1826  2676 E NxpNfcJni: getReconnectState = 0x0
,08-30 23:11:35.925   892  1347 I ActivityManager: Process com.google.android.apps.plus (pid 6099) has died
,08-30 23:11:35.927  1826  2202 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-30 23:11:35.927  1826  2202 D LCardEmulationManager: getDefaultRoute
08-30 23:11:35.927  1826  2202 D LNfcService: isRequireNfcCRouting() return true
08-30 23:11:35.928  1826  2202 D LNfcService: isHCERoutingtoHost() return : true
08-30 23:11:35.928  1826  2202 D NfcService: mCurrentDiscoveryParameters.techmask= mTechMask: default
08-30 23:11:35.928  1826  2202 D NfcService: mEnableLPD: true
08-30 23:11:35.928  1826  2202 D NfcService: mEnableReader: false
08-30 23:11:35.928  1826  2202 D NfcService: mEnableHostRouting: true
08-30 23:11:35.928  1826  2202 D NfcService: newParams.techmask= mTechMask: 0
08-30 23:11:35.928  1826  2202 D NfcService: mEnableLPD: true
08-30 23:11:35.928  1826  2202 D NfcService: mEnableReader: false
08-30 23:11:35.928  1826  2202 D NfcService: mEnableHostRouting: true
08-30 23:11:35.928  1826  2202 D NfcService: screenState= 1
08-30 23:11:35.988  1826  2676 E NxpNfcJni: getReconnectState = 0x0
,08-30 23:11:36.558  6453  6528 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 23:11:36.558  6453  6528 I jxcore-log: 
,08-30 23:11:36.950  6453  6528 I jxcore-log: ERROR runTests: 
08-30 23:11:36.950  6453  6528 I jxcore-log: 
,08-30 23:11:36.958  6453  6528 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 23:11:36.958  6453  6528 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
08-30 23:11:36.959  6453  6528 I jxcore-log: WARN testUtils: logCallback not set!
08-30 23:11:36.959  6453  6528 I jxcore-log: 
08-30 23:11:36.975  6453  6528 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 23:11:36.975  6453  6528 I jxcore-log:     _functionName: 'loadFile',
08-30 23:11:36.975  6453  6528 I jxcore-log:     _lineNumber: '26',
08-30 23:11:36.975  6453  6528 I jxcore-log:     _columnNumber: '11',
08-30 23:11:36.975  6453  6528 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 23:11:36.975  6453  6528 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 23:11:36.975  6453  6528 I jxcore-log:     _functionName: '',
08-30 23:11:36.975  6453  6528 I jxcore-log:     _lineNumber: '38',
08-30 23:11:36.975  6453  6528 I jxcore-log:     _columnNumber: '7',
08-30 23:11:36.975  6453  6528 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 23:11:36.975  6453  6528 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 23:11:36.975  6453  6528 I jxcore-log:     _functionName: '',
08-30 23:11:36.975  6453  6528 I jxcore-log:     _lineNumber: '35',
08-30 23:11:36.975  6453  6528 I jxcore-log:     _columnNumber: '3',
08-30 23:11:36.975  6453  6528 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 23:11:36.975  6453  6528 I jxcore-log:   { _fileName: 'module.js',
08-30 23:11:36.975  6453  6528 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 23:11:36.975  6453  6528 I jxcore-log:     _lineNumber: '621',
08-30 23:11:36.975  6453  6528 I jxcore-log:     _columnNumber: '8',
08-30 23:11:36.975  6453  6528 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 23:11:36.975  6453  6528 I jxcore-log:   { _fileName: 'module.js',
08-30 23:11:36.975  6453  6528 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 23:11:36.975  6453  6528 I jxcore-log:     _lineNumber: '651',
08-30 23:11:36.975  6453  6528 I jxcore-log:     _columnNumber: '1',
08-30 23:11:36.975  6453  6528 I jxcore-log:    
08-30 23:11:36.975  6453  6528 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 23:11:36.975  6453  6528 I jxcore-log: 
08-30 23:11:36.975  6453  6528 E jxcore-log: Error: 
,08-30 23:11:36.975  6453  6528 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 23:11:36.975  6453  6528 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 23:11:36.975  6453  6528 E jxcore-log: 
08-30 23:11:37.114   892  2038 I ActivityManager: Process com.lge.eula (pid 6197) has died
,08-30 23:11:37.327  6715  6715 D AndroidRuntime: 
08-30 23:11:37.327  6715  6715 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-30 23:11:37.331  6715  6715 D AndroidRuntime: CheckJNI is OFF
08-30 23:11:37.434   285   285 V AudioFlinger: 2851 died, releasing its sessions
08-30 23:11:37.434   285   285 V AudioFlinger:  pid 1773 @ 0
08-30 23:11:37.434   285   285 V AudioFlinger:  pid 3120 @ 1
08-30 23:11:37.434   285   285 V AudioFlinger:  pid 3120 @ 2
,08-30 23:11:37.465   892  1347 I ActivityManager: Process com.lge.music (pid 2851) has died
,08-30 23:11:37.542  6218  6218 I Finsky  : [1] com.google.android.finsky.utils.dv.onTrimMemory(25): Memory trim requested to level 60
,08-30 23:11:37.545  1773  1773 I PhoneApp: onTrimMemory: 10
08-30 23:11:37.547  1773  1773 I PhoneApp: trim memory
08-30 23:11:37.553  2029  2029 I BackgroundMemoryTrimmer: Trimming objects from memory, since app is in the background.
,08-30 23:11:37.581  6715  6715 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 23:11:37.623   892  1048 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
,08-30 23:11:37.623   892  1048 I ActivityManager: Killing 6453:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
08-30 23:11:37.684   892  1641 I WindowState: WIN DEATH: Window{324c07b3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 23:11:37.689  1773  1773 I art     : Explicit concurrent mark sweep GC freed 28637(1594KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 11MB/18MB, paused 956us total 135.518ms
08-30 23:11:37.690   892  1641 D InputDispatcher: Focus left window: Window{324c07b3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 23:11:37.690   892  1641 D InputDispatcher: Window went away: Window{324c07b3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 23:11:37.718   892  1064 W PackageSettings: Skipping PackageSetting{3840d840 com.example.hello/10317} due to missing metadata
,08-30 23:11:37.837   892  1048 I ActivityManager:   Force finishing activity ActivityRecord{76f845b u0 com.test.thalitest/.MainActivity t259}
,08-30 23:11:37.847   892   892 V ActivityManager: Display changed displayId=0
08-30 23:11:37.848  1773  1773 D DSDPConnection: Display #0 changed.
,08-30 23:11:37.857   892  1064 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
08-30 23:11:37.858   892  1064 I ActivityManager:   Force finishing activity ActivityRecord{76f845b u0 com.test.thalitest/.MainActivity t259 f}
08-30 23:11:37.858   892  1064 W ActivityManager: Duplicate finish request for ActivityRecord{76f845b u0 com.test.thalitest/.MainActivity t259 f}
,08-30 23:11:37.899   892  2185 W ActivityManager: Spurious death for ProcessRecord{3a6aa951 6453:com.test.thalitest/u0a30}, curProc for 6453: null
08-30 23:11:37.925  1380  1380 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-30 23:11:37.935  1950  1950 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
08-30 23:11:37.939  1745  2493 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 23:11:37.940  1909  1909 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,08-30 23:11:37.943   892  1289 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-30 23:11:37.953  1950  1950 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
08-30 23:11:37.958  2029  2029 I art     : Explicit concurrent mark sweep GC freed 2607(244KB) AllocSpace objects, 1(23KB) LOS objects, 39% free, 12MB/20MB, paused 12.700ms total 97.086ms
,08-30 23:11:37.964  3595  3595 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-30 23:11:37.966  3595  3595 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-30 23:11:37.967  3595  3595 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-30 23:11:37.967  3595  3595 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-30 23:11:37.967  3595  3595 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 23:11:37.967  3595  3595 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 23:11:37.967  3595  3595 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 23:11:37.969  3595  3595 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-30 23:11:37.970  3595  3595 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,08-30 23:11:37.970  3595  3595 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 23:11:37.973  3595  3595 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-30 23:11:37.973  3595  3595 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-30 23:11:37.973   892  1048 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6742 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-30 23:11:38.025   892  1973 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=6753 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,08-30 23:11:38.036  3311  3311 I art     : Explicit concurrent mark sweep GC freed 17486(1056KB) AllocSpace objects, 4(64KB) LOS objects, 25% free, 16MB/22MB, paused 2.033ms total 163.618ms
,08-30 23:11:38.087  1950  1950 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-30 23:11:38.108  1950  1950 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-30 23:11:38.108  1950  1950 I Activity: Activity.onPostResume() called 
08-30 23:11:38.108  1380  1380 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-30 23:11:38.114  1773  1773 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 23:11:38.118  1950  1950 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
,08-30 23:11:38.146  1950  6783 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
08-30 23:11:38.148   892  1053 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
,08-30 23:11:38.150   892  1053 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
08-30 23:11:38.151   892  1053 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-30 23:11:38.151   892  1053 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-30 23:11:38.151   892  1053 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-30 23:11:38.151   892  1053 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1f89cce2,  pkg=WindowManager.LayoutParams
08-30 23:11:38.151   892  1053 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-30 23:11:38.153   892  1641 D InputDispatcher: Focus entered window: Window{1c5c507e u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-30 23:11:38.169   892   892 I art     : Explicit concurrent mark sweep GC freed 42618(2MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 24MB/36MB, paused 5.739ms total 299.990ms
08-30 23:11:38.170   892  1064 I art     : WaitForGcToComplete blocked for 137.433ms for cause Explicit
,08-30 23:11:38.173  1950  1950 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 23:11:38.176  1380  1380 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-30 23:11:38.176  1380  1380 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-30 23:11:38.176  1380  1380 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-30 23:11:38.176  1380  1380 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-30 23:11:38.176  1380  1380 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-30 23:11:38.176  1380  1380 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-30 23:11:38.176  1950  1950 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 23:11:38.177  1950  1950 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
08-30 23:11:38.178  6742  6742 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 23:11:38.178  6742  6742 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 23:11:38.180  6742  6742 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 23:11:38.190  1950  1950 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
,08-30 23:11:38.195  6753  6753 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
08-30 23:11:38.197  1950  1950 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
08-30 23:11:38.198  1950  1950 I PhoneWindow: [setNavigationBarColor] color=0x 0
08-30 23:11:38.211   892  2185 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,08-30 23:11:38.227  1380  1511 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,08-30 23:11:38.227  1380  1511 D KeyguardModel: createShortcutInfo...
08-30 23:11:38.232   892  2185 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6453 uid 10030
08-30 23:11:38.236  1380  1511 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 23:11:38.236  1380  1511 D KeyguardModel: createShortcutInfo...
08-30 23:11:38.242  1380  1511 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 23:11:38.242  1380  1511 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-30 23:11:38.244  1380  1511 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 23:11:38.248  1380  1511 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 23:11:38.250  1380  1511 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 23:11:38.250  1380  1511 D KeyguardModel: createShortcutInfo...
08-30 23:11:38.253   892   892 D administrator: Handling package changes for user 0
08-30 23:11:38.276  1380  1511 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-30 23:11:38.278  1380  1511 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 23:11:38.278  1380  1511 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-30 23:11:38.279  1380  1511 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 23:11:38.279  1380  1511 D KeyguardModel: createShortcutInfo...
08-30 23:11:38.290  1380  1511 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-30 23:11:38.291  1380  1511 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 23:11:38.292  1380  1511 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-30 23:11:38.296  1380  1511 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 23:11:38.296  1380  1511 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 23:11:38.298  1380  1511 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
,08-30 23:11:38.298  1380  1511 D KeyguardModel: createShortcutInfo...
08-30 23:11:38.306  1380  1380 D KeyguardModel: handleShortcutListChanged...
,08-30 23:11:38.315  1950  1950 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
08-30 23:11:38.320  1380  1511 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 23:11:38.320  1380  1511 D KeyguardModel: createShortcutInfo...
,08-30 23:11:38.327  1950  1950 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2fdd66b4 time:157452
08-30 23:11:38.328  1635  1635 E b       : Unable to connect to the editor to retrieve text... will retry later
08-30 23:11:38.328  1380  1511 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 23:11:38.328  1380  1511 D KeyguardModel: createShortcutInfo...
08-30 23:11:38.330  1380  1511 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 23:11:38.330  1380  1511 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 23:11:38.331  1380  1511 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 23:11:38.331  1380  1511 D KeyguardModel: createShortcutInfo...
08-30 23:11:38.332  1380  1511 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 23:11:38.333  1380  1511 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-30 23:11:38.335  1380  1511 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 23:11:38.335  1380  1511 D KeyguardModel: createShortcutInfo...
08-30 23:11:38.337  1380  1511 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 23:11:38.337   892  1055 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1a57ca10 u0 com.lge.launcher2/.Launcher t258} time:157462
08-30 23:11:38.337  1380  1511 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 23:11:38.339  1380  1511 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 23:11:38.339  1380  1511 D KeyguardModel: createShortcutInfo...
08-30 23:11:38.350  1380  1380 D KeyguardModel: handleShortcutListChanged...
,08-30 23:11:38.383  1950  1950 I art     : Explicit concurrent mark sweep GC freed 3060(188KB) AllocSpace objects, 4(645KB) LOS objects, 39% free, 15MB/25MB, paused 1.461ms total 55.158ms
08-30 23:11:38.383  1950  1950 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-30 23:11:38.501   892  1044 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 23:11:38.504   892   892 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-30 23:11:38.504   892   892 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-30 23:11:38.507   892   892 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-30 23:11:38.519   892  1349 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
,08-30 23:11:38.524  6742  6742 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-30 23:11:38.551  6742  6742 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,08-30 23:11:38.562   892  1064 I art     : Explicit concurrent mark sweep GC freed 11424(1096KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.485ms total 391.879ms
,08-30 23:11:38.576  1826  1826 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-30 23:11:38.576  1826  1826 D LCardEmulationManager: getDefaultRoute
,08-30 23:11:38.645  6715  6715 D AndroidRuntime: Shutting down VM
,08-30 23:11:38.686   892  1044 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-30 23:11:38.696   892  1064 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6789 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-30 23:11:38.716  1950  1950 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-30 23:11:38.781  6742  6742 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-30 23:11:38.828   892  2185 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6812 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-30 23:11:38.851   309   309 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 21.420ms
,08-30 23:11:38.872   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 21.402ms
,08-30 23:11:38.895   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 20.690ms
,08-30 23:11:38.899  6812  6812 I AppUp4:AppBoxCP: onCreate
08-30 23:11:38.902  6812  6812 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-30 23:11:38.927  6812  6812 I AppUp4:DB:  setFingerPrint start
08-30 23:11:38.928  6812  6812 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
,08-30 23:11:38.939  6812  6812 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
08-30 23:11:38.939  6812  6812 I AppUp4:DB:  SDK version = 21
08-30 23:11:38.939  6812  6812 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-30 23:11:38.940  6812  6812 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-30 23:11:39.023  6812  6812 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-30 23:11:39.060   892  1995 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6832 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a

```
