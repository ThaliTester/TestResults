#### Test 50388019b27d54e_thali03_LGE-LG-D855 Logs


```--------- beginning of main
11-17 18:21:32.227  5940  5987 D UEI.SmartControl: Internal timer expired: 1
11-17 18:21:32.227  5940  5987 D UEI.SmartControl: unbind internal service
11-17 18:21:32.244  5940  5940 D UEI.SmartControl: Service.onUnbind: IControl
,11-17 18:21:32.246  5940  5940 D UEI.SmartControl: Service.onDestroy
11-17 18:21:32.246  5940  5940 D UEI.SmartControl: Lock is in USE false
11-17 18:21:32.246  5940  5940 D UEI.SmartControl: unbind internal service
11-17 18:21:32.247  5940  5940 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@302e16b4
11-17 18:21:32.247  5940  5940 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
11-17 18:21:32.247  5940  5940 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
11-17 18:21:32.247  5940  5940 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
11-17 18:21:32.247  5940  5940 W System.err: 	at com.uei.control.Service.c(Unknown Source)
11-17 18:21:32.247  5940  5940 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
11-17 18:21:32.247  5940  5940 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
11-17 18:21:32.247  5940  5940 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
11-17 18:21:32.247  5940  5940 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
11-17 18:21:32.247  5940  5940 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:21:32.248  5940  5940 W System.err: 	at android.os.Looper.loop(Looper.java:135)
11-17 18:21:32.248  5940  5940 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
11-17 18:21:32.248  5940  5940 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:21:32.248  5940  5940 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:21:32.248  5940  5940 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
11-17 18:21:32.248  5940  5940 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
11-17 18:21:32.248  5940  5940 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@302e16b4
11-17 18:21:32.250  5940  5940 D serial_port: close(fd = 25)
11-17 18:21:32.253  5940  5940 I UEI.SmartControl: Serial port is closed.
11-17 18:21:32.253  5940  5940 I UEI.SmartControl: Serial port is closed.
11-17 18:21:32.253  5940  5940 D UEI.SmartControl: Blaster closed
11-17 18:21:32.253  5940  5940 D UEI.SmartControl: Shut down QS...
11-17 18:21:32.253  5940  5940 D UEI.SmartControl: Stopping QS lib
11-17 18:21:32.254  5940  5940 D UEI.SmartControl: QS lib stop result = true
11-17 18:21:32.254  5940  5940 D UEI.SmartControl: Stopped QS lib
11-17 18:21:32.255  5940  5940 D UEI.SmartControl: Stopped file observer...
11-17 18:21:32.255  5940  5940 D UEI.SmartControl: QS shutdown complete
11-17 18:21:33.119  6000  6000 D AndroidRuntime: 
11-17 18:21:33.119  6000  6000 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
11-17 18:21:33.127  6000  6000 D AndroidRuntime: CheckJNI is OFF
11-17 18:21:33.328  6000  6000 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-17 18:21:33.338  1032  1429 I ActivityManager: START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
11-17 18:21:33.347  1955  1970 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
11-17 18:21:33.352  1032  1429 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
11-17 18:21:33.353  1032  1429 V ActivityStackEx: create ActivityStackEx
11-17 18:21:33.371  1032  1429 D ActivityManager: setTaskToReturnTo : TaskRecord{37364fe4 #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
11-17 18:21:33.371  1032  1429 D ActivityManager: setTaskToReturnTo : TaskRecord{37364fe4 #2 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
11-17 18:21:33.373  1032  1429 D WindowStateEx: AppWindowTokenEx init.. 
11-17 18:21:33.374   351   375 E GBMv2   : DFP En is all cleared set to be enabled
11-17 18:21:33.389  1412  1412 D QuickStatusbarLayout: Notification difference=198
11-17 18:21:33.389  1412  1412 D QuickStatusbarLayout: child = android.widget.LinearLayout{b1d81b0 V.E..... ......ID 0,0-798,100 #7f0f0041 app:id/notification_icon_area} ,w = 798
11-17 18:21:33.393  1412  1412 D LgeAbsQuickCoverView: mCoverXPos: 0 ,mCoverYPos: 0
11-17 18:21:33.393  1412  1412 D LgeAbsQuickCoverView: mCoverWidth: 0 ,mCoverHeight: 0
11-17 18:21:33.411  1032  1429 I ActivityManager: Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6015 uid=10318 gids={50318, 9997, 3003, 3001, 3002} abi=armeabi-v7a
11-17 18:21:33.412  6000  6000 D AndroidRuntime: Shutting down VM
11-17 18:21:33.461  1032  1032 V ActivityManager: Display changed displayId=0
11-17 18:21:33.468  1867  1867 D DSDPConnection: Display #0 changed.
11-17 18:21:33.511  1955  1971 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
11-17 18:21:33.512  1955  1971 D SplitWindowPolicy: topRunningActivity=ActivityInfo{16e28c79 co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
11-17 18:21:33.513  1955  1970 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
11-17 18:21:33.514  1955  1970 D SplitWindowPolicy: topRunningActivity=ActivityInfo{23d8ddbe co.....MainActivity}, taskId=2, activityType=0, bIsSplit=false
,11-17 18:21:33.666  1032  1761 I art     : Explicit concurrent mark sweep GC freed 16924(773KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 3.078ms total 147.777ms
,11-17 18:21:33.704  6015  6015 D ContextHelper: convertTheme. context->name=com.example.hello themeResourceId=16973833
,11-17 18:21:33.815  6015  6015 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,11-17 18:21:33.827  6015  6015 I LibraryLoader: Loading: webviewchromium
,11-17 18:21:33.836  6015  6015 I LibraryLoader: Time to load native libraries: 10 ms (timestamps 9735-9745)
11-17 18:21:33.836  6015  6015 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:21:33.860  6015  6015 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e87d9fa}
,11-17 18:21:33.862  6015  6015 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 18:21:33.862  6015  6015 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
11-17 18:21:33.871  6015  6015 I BrowserStartupController: Initializing chromium process, renderers=0
,11-17 18:21:33.872  6015  6015 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:21:33.877  6015  6057 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
11-17 18:21:33.885  6015  6015 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,11-17 18:21:33.887  6015  6015 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
11-17 18:21:33.887  6015  6015 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
11-17 18:21:33.889   331  1668 V AudioPolicyService: registerClient() client 0xb151e0c0, uid 10318
11-17 18:21:33.893  1032  1108 D BluetoothManagerService: Message: 20
11-17 18:21:33.893  1032  1108 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f094d4e:true
11-17 18:21:33.894  6015  6061 D BluetoothAdapter: 631122859: getState() :  mService = null. Returning STATE_OFF
11-17 18:21:33.904  6015  6015 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
11-17 18:21:33.904  6015  6015 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
11-17 18:21:33.904  6015  6015 I Adreno-EGL: Build Date: 12/12/14 금
11-17 18:21:33.904  6015  6015 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
11-17 18:21:33.904  6015  6015 I Adreno-EGL: Remote Branch: 
11-17 18:21:33.904  6015  6015 I Adreno-EGL: Local Patches: 
11-17 18:21:33.904  6015  6015 I Adreno-EGL: Reconstruct Branch: 
,11-17 18:21:33.994  6015  6067 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
11-17 18:21:33.997  6015  6015 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,11-17 18:21:34.006  1032  1089 W ActivityManager: Activity pause timeout for ActivityRecord{3ccfac4d u0 com.example.hello/.MainActivity t2}
11-17 18:21:34.017  6015  6015 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,11-17 18:21:34.022  6015  6015 W AwContents: onDetachedFromWindow called when already detached. Ignoring
11-17 18:21:34.042  6015  6015 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,11-17 18:21:34.049  6015  6015 W art     : Attempt to remove local handle scope entry from IRT, ignoring
11-17 18:21:34.049  6015  6015 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,11-17 18:21:34.075  6015  6079 D OpenGLRenderer: Render dirty regions requested: true
11-17 18:21:34.076  6015  6079 I OpenGLRenderer: Initialized EGL, version 1.4
11-17 18:21:34.087  6015  6079 D OpenGLRenderer: Enabling debug mode 0
,11-17 18:21:34.101  6015  6015 D Atlas   : Validating map...
,11-17 18:21:34.106  1032  1047 D SplitWindow: check instance of lgWin Window{2432e298 u0 com.example.hello/com.example.hello.MainActivity}
,11-17 18:21:34.153  6015  6077 D LgDataFeature: LgDataFeature() Constructor: none
,11-17 18:21:34.153  6015  6077 D LgDataFeature: LgDataFeature() Constructor Done, null
11-17 18:21:34.170  1032  1107 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
,11-17 18:21:34.172  1032  1107 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
11-17 18:21:34.172  1032  1107 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
11-17 18:21:34.172  1032  1107 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:21:34.172  1032  1107 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@f5a90af,  pkg=WindowManager.LayoutParams
11-17 18:21:34.172  1032  1107 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
11-17 18:21:34.173  1468  1468 D PhoneStatusBar: setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
11-17 18:21:34.173  1468  1468 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
11-17 18:21:34.173  1468  1468 I [SystemUI]NavigationThemeResource:  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
11-17 18:21:34.173  1468  1468 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
11-17 18:21:34.223  1032  1953 I ActivityManager: Killing 5577:com.lge.email/u0a23 (adj 15): empty #17
,11-17 18:21:34.240  6015  6015 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2e5559b time:80149
11-17 18:21:34.279  6015  6015 I chromium: [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,11-17 18:21:34.281  6015  6073 E AndroidProtocolHandler: Unable to open asset URL: file:///android_asset/www/jxcore.js
11-17 18:21:34.284  1032  1109 I ActivityManager: Displayed com.example.hello/.MainActivity: +778ms (total +909ms)
11-17 18:21:34.285  1032  1109 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3ccfac4d u0 com.example.hello/.MainActivity t2} time:80194
11-17 18:21:34.286  1032  1720 W libprocessgroup: failed to open /acct/uid_10023/pid_5577/cgroup.procs: No such file or directory
11-17 18:21:34.348  6015  6015 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
11-17 18:21:34.348  6015  6015 I chromium: 
,11-17 18:21:34.372  6015  6015 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-17 18:21:34.451  6015  6077 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
11-17 18:21:34.451  6015  6077 I chromium: 
,11-17 18:21:34.583  6015  6089 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435336448
11-17 18:21:34.583  6015  6089 D JX-Cordova: jxcore cordova android initializing
,11-17 18:21:34.657  6015  6015 W jxcore-log: Initializing JXcore engine
11-17 18:21:34.658  6015  6015 W jxcore-log: JXcore engine is ready
,11-17 18:21:34.665  6015  6015 W jxcore-log: Starting JXcore engine
,11-17 18:21:34.742  6015  6015 W m.example.hello: type=1400 audit(0.0:148): avc: denied { ioctl } for path="socket:[9633]" dev="sockfs" ino=9633 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,11-17 18:21:34.742  6015  6015 W m.example.hello: type=1400 audit(0.0:149): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,11-17 18:21:34.742  6015  6015 W m.example.hello: type=1400 audit(0.0:150): avc: denied { ioctl } for path="socket:[7676]" dev="sockfs" ino=7676 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
11-17 18:21:34.742  6015  6015 W m.example.hello: type=1400 audit(0.0:151): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,11-17 18:21:34.742  6015  6015 W m.example.hello: type=1400 audit(0.0:152): avc: denied { ioctl } for path="socket:[29567]" dev="sockfs" ino=29567 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
11-17 18:21:34.889   351   377 E GBMv2   : DFP En is all cleared set to be enabled
,11-17 18:21:34.890   351   377 E GBMv2   : Set value is all cleared set the max
11-17 18:21:34.890   351   377 I GBMv2   : DFP Enabled. Ignore VFP set
,11-17 18:21:34.930  6015  6015 W jxcore-log: Platform android
11-17 18:21:34.930  6015  6015 W jxcore-log: 
,11-17 18:21:34.930  6015  6015 W jxcore-log: Process ARCH arm
11-17 18:21:34.930  6015  6015 W jxcore-log: 
,11-17 18:21:35.010  6015  6015 I jxcore-log: JXcore Cordova bridge is ready!
11-17 18:21:35.010  6015  6015 I jxcore-log: 
,11-17 18:21:35.011  6015  6015 W jxcore-log: JXcore engine is started
11-17 18:21:35.091  6015  6015 E jxcore-log: >> LGE-LG-D855
11-17 18:21:35.091  6015  6015 E jxcore-log: 
11-17 18:21:35.093  6015  6015 I jxcore-log: Total memory 2995761152
11-17 18:21:35.093  6015  6015 I jxcore-log: 
11-17 18:21:35.094  6015  6015 I jxcore-log: Free memory 671342592
11-17 18:21:35.094  6015  6015 I jxcore-log: 
11-17 18:21:35.094  6015  6015 I jxcore-log: execPath /data/data/com.example.hello/files/www/jxcore
11-17 18:21:35.094  6015  6015 I jxcore-log: 
11-17 18:21:35.094  6015  6015 I jxcore-log: process.cwd /data/data/com.example.hello/files/www/jxcore
11-17 18:21:35.094  6015  6015 I jxcore-log: 
,11-17 18:21:35.104  6015  6015 I jxcore-log: userPath [ 'www' ]
11-17 18:21:35.104  6015  6015 I jxcore-log: 
11-17 18:21:35.109  6015  6015 I jxcore-log: Size 1440 2392
11-17 18:21:35.109  6015  6015 I jxcore-log: 
11-17 18:21:35.113  6015  6015 I jxcore-log: Screen Brightness 50
11-17 18:21:35.113  6015  6015 I jxcore-log: 
,11-17 18:21:35.114  6015  6015 E jxcore-log: Dummy Error Log.
11-17 18:21:35.114  6015  6015 E jxcore-log: 
,11-17 18:21:35.661  6015  6015 I jxcore-log: getBuffer is called!!!!
11-17 18:21:35.661  6015  6015 I jxcore-log: 
,11-17 18:21:35.730  4882  4931 D InitAlarmsService: Clearing and rescheduling alarms.
,11-17 18:21:35.840  1032  1999 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6093 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi
,11-17 18:21:35.933  6093  6093 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,11-17 18:21:35.967  6093  6093 D CalendarProvider2: [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@3686dcee
,11-17 18:21:35.984  6093  6093 D CalendarProvider2: [getOrCreateCalendarAlarmManager]
11-17 18:21:35.986  6093  6093 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@259e2bab(com.android.providers.calendar.CalendarProvider2@3686dcee)
,11-17 18:21:35.991  6093  6123 D CalendarProvider2: Scheduling check of next Alarm
11-17 18:21:35.994  6093  6123 D CalendarProvider2: SCHEDULE_ALARM_REMOVE
11-17 18:21:36.000  1032  1047 I ActivityManager: Killing 4882:com.android.calendar/u0a13 (adj 15): empty #17
,11-17 18:21:36.125  1032  1953 W libprocessgroup: failed to open /acct/uid_10013/pid_4882/cgroup.procs: No such file or directory
,11-17 18:21:36.998  6093  6093 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,11-17 18:21:36.999  6093  6093 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,11-17 18:21:37.063  1032  1089 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6139 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
,11-17 18:21:37.076  1032  1429 I ActivityManager: Killing 5193:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,11-17 18:21:37.204  1032  1954 W libprocessgroup: failed to open /acct/uid_1000/pid_5193/cgroup.procs: No such file or directory
,11-17 18:21:37.243  6139  6139 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,11-17 18:21:37.277  6139  6139 D CalendarApplication: CalendarApplication.onCreate()
,11-17 18:21:37.290  6139  6139 D PreferenceKeysParser: [debug_displayParseInfos] preference keys.size() = 44,
,11-17 18:21:37.293  6139  6139 D PreferenceKeysParser: [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@3cafe01c, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@1ed32425, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@e87d9fa, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@259e2bab, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@26e8e208, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2036dda1, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@3a699bc6, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@d91d787, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@302e16b4, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@11c2b2dd, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@1653ae52, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@262a6523, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@6efea20, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@23c9fd9, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@275a5d9e, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@1034307f, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@e39884c, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@cce6095, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1d8ab5aa, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@2e5559b, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@2c9cdd38, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@1b817111, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@2ab68276, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@28b9b077, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@1dde94e4, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@157b0d4d, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@3a005002, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@2e0edd13, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@33621b50, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@34f83149, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@14276a4e, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@1d80376f, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@2f559c7c, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@1099905, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@3c93dd5a, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@2602db8b, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@269e0468, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@270fc081, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@13227526, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@26c1a567, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@1582ff14, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$Ke,yData@2ff6e3
11-17 18:21:37.297  6139  6139 D GeneralPreferenceUtils: [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
11-17 18:21:37.307  6139  6139 D Config  : [init]
,11-17 18:21:37.310  6139  6139 I Config  : LGCalendar ver.4.40.16
11-17 18:21:37.310  6139  6139 I Config  : start check model
11-17 18:21:37.311  6139  6139 I Config  : start check native_ca
11-17 18:21:37.312  6139  6139 I Config  : Config Operator=OPEN, Country=EU
11-17 18:21:37.312  6139  6139 D Config  : [setDefaultValuesToPref]
11-17 18:21:37.312  6139  6139 D Config  : [parseProfiles]
11-17 18:21:37.317  6139  6139 D ProfilesParser: [debug_displayParseInfos] profile.country = null
11-17 18:21:37.317  6139  6139 D ProfilesParser: [debug_displayParseInfos] profile.operator = null
11-17 18:21:37.318  6139  6139 D Config  : [updateProfiletoCountryInfo]
11-17 18:21:37.319  6139  6139 D GeneralPreference: [checkAndMigrateOldPreference]
,11-17 18:21:37.329  6139  6139 D AlertReceiver: onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
11-17 18:21:37.344  6139  6158 I InitNotificationRingtoneService: Start InitializeAlertRingtoneService.onHandleIntent
,11-17 18:21:37.353  6139  6158 I AlertUtils: [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
11-17 18:21:37.375  6139  6158 I AlertUtils: [getCalendarNotiSoundURIFromCursor] getCount()= 21
,11-17 18:21:37.384  6139  6158 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
11-17 18:21:37.389  6139  6158 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,11-17 18:21:37.395  6139  6158 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
11-17 18:21:37.401  6139  6158 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,11-17 18:21:37.406  6139  6158 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
11-17 18:21:37.411  6139  6158 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
11-17 18:21:37.416  6139  6158 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,11-17 18:21:37.422  6139  6158 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
11-17 18:21:37.427  6139  6158 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,11-17 18:21:37.432  6139  6158 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
11-17 18:21:37.438  6139  6158 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
11-17 18:21:37.455  6139  6158 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,11-17 18:21:37.466  6139  6158 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
11-17 18:21:37.470  6139  6158 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
11-17 18:21:37.474  6139  6158 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
11-17 18:21:37.474  6139  6158 I AlertUtils: [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
,11-17 18:21:37.478  6139  6158 I AlertUtils: set default noti to content://media/internal/audio/media/41
11-17 18:21:37.483  6139  6158 I InitNotificationRingtoneService: End InitializeAlertRingtoneService.onHandleIntent
11-17 18:21:37.580  6139  6166 W HolidayIntentService: onHandleIntent
,11-17 18:21:37.586  6139  6166 D HolidayDataLoader: readJsonAsset : holiday.json
11-17 18:21:37.597  6139  6167 D AlertService: 0 Action = android.intent.action.PROVIDER_CHANGED
,11-17 18:21:37.606  6139  6139 E AgendaWidgetManager: [updateWidgets] 
11-17 18:21:37.612  6139  6139 D MonthWidgetProvider: [onReceive]
11-17 18:21:37.612  6139  6139 D CalendarWidgetProvider: [onReceive]
11-17 18:21:37.613  6139  6139 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
11-17 18:21:37.618  6139  6139 D CalendarTypeController: [onCreate] mContext.getPackageName() = com.android.calendar
,11-17 18:21:37.623  6139  6139 D WeekWidgetProvider: [onReceive]
11-17 18:21:37.623  6139  6139 D CalendarWidgetProvider: [onReceive]
11-17 18:21:37.623  6139  6139 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
11-17 18:21:37.627  6139  6139 D CalendarTypeController: [onCreate] mContext.getPackageName() = com.android.calendar
11-17 18:21:37.674  6139  6166 E HolidayIntentService: onHandleIntent:holiday data empty
,11-17 18:21:39.229  1032  1089 I ActivityManager: Waited long enough for: ServiceRecord{10cbbbb7 u0 com.google.android.music/.wear.WearMetadataSyncService}
,11-17 18:21:40.133  1032  2082 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
11-17 18:21:40.134  1032  2082 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
,11-17 18:21:40.139  1032  1108 D BluetoothManagerService: Message: 2
11-17 18:21:40.154  1032  1398 D WifiService: New client listening to asynchronous messages
,11-17 18:21:40.163  1032  1998 D WifiServiceImplEx: setWifiEnabled: false pid=6015, uid=10318, package= com.example.hello, App Lable : HelloWorld
11-17 18:21:40.163  1032  1998 D WifiService: setWifiEnabled: false pid=6015, uid=10318
11-17 18:21:40.163  1032  1998 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-17 18:21:40.165  6015  6015 I jxcore-log: ****TEST TOOK:  5081  ms ****
11-17 18:21:40.165  6015  6015 I jxcore-log: 
11-17 18:21:40.166  6015  6015 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
11-17 18:21:40.166  6015  6015 I jxcore-log: 
11-17 18:21:41.005  1032  1374 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1f021c8 type 2 when 86888 com.android.providers.calendar} when 86888
,11-17 18:21:41.016  6093  6093 D CalendarProviderBroadcastReceiver: Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
11-17 18:21:41.018  6093  6093 D CalendarProviderBroadcastReceiver: [IntentService] WakeLock acquire, start IntentSerivce
11-17 18:21:41.034  6093  6093 D CalendarProvider2: CalendarProviderIntentService.onCreate()
,11-17 18:21:41.037  6093  6173 D CalendarProvider2: Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
11-17 18:21:41.038  6093  6173 D CalendarProvider2: [getOrCreateCalendarAlarmManager]
11-17 18:21:41.041  6093  6173 E SQLiteLog: (284) automatic index on view_events(_id)
11-17 18:21:41.063  1032  1374 V AlarmManager: RTC_WAKEUP set : Alarm{43c4186 type 0 when 1447780867713 com.lge.ia.task.mrgdblogger} when 1447780867713
,11-17 18:21:41.068  2690  2690 D LIA_MrGDBLogger_MrGIntentReceiverDBCleaning: [dreamwood]onReceive
11-17 18:21:41.073  2690  2690 D LIA_MrGDBLogger_MrGDBCleaner: [dreamwood]onReceive
11-17 18:21:41.077   326  6174 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,11-17 18:21:41.089  1032  1106 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,11-17 18:21:41.093  2690  6175 D LIA_MrGDBLogger_MrGDBManager: [dreamwood]dbFileSize : 77824
11-17 18:21:41.101  2690  6175 D LIA_MrGDBLogger_DBCleanerUtil: [dreamwood]cleanOldRecord : APP_USAGE
11-17 18:21:41.105  2690  6175 D LIA_MrGDBLogger_DBCleanerUtil: [dreamwood]LimitedDate : 2015-10-18 19:21:41, count : 0
11-17 18:21:41.105  2690  6175 D LIA_MrGDBLogger_DBCleanerUtil: [dreamwood]cleanOldRecord : CONCIERGE_BOARD
,11-17 18:21:41.122  2690  6175 D LIA_MrGDBLogger_DBCleanerUtil: [dreamwood]LimitedDate : 2015-10-18 19:21:41, count : 0
11-17 18:21:41.122  2690  6175 D LIA_MrGDBLogger_DBCleanerUtil: [dreamwood]cleanOldRecord : INFORMANT_FEATURE_STATUS_INFO
11-17 18:21:41.124  2690  6175 D LIA_MrGDBLogger_DBCleanerUtil: [dreamwood]LimitedDate : 2015-10-18 19:21:41, count : 0
11-17 18:21:41.124  2690  6175 D LIA_MrGDBLogger_MrGDBManager: [dreamwood]dbFileSize : 77824
,11-17 18:21:41.141  6093  6173 D CalendarProvider2: [IntentService] Release Lock
,11-17 18:21:41.157  6093  6093 D CalendarProvider2: CalendarProviderIntentService.onDestroy()
,11-17 18:21:41.357  6176  6176 D AndroidRuntime: 
11-17 18:21:41.357  6176  6176 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,11-17 18:21:41.362  6176  6176 D AndroidRuntime: CheckJNI is OFF
11-17 18:21:41.671  6176  6176 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-17 18:21:41.688  1032  1089 I ActivityManager: Force stopping com.example.hello appid=10318 user=-1: uninstall pkg
11-17 18:21:41.689  1032  1089 I ActivityManager: Killing 6015:com.example.hello/u0a318 (adj 0): stop com.example.hello
,11-17 18:21:41.762  1032  1761 I WindowState: WIN DEATH: Window{2432e298 u0 com.example.hello/com.example.hello.MainActivity}
11-17 18:21:41.762  1032  1398 D WifiService: Client connection lost with reason: 4
,11-17 18:21:41.768  1032  1761 D InputDispatcher: Window went away: Window{2432e298 u0 com.example.hello/com.example.hello.MainActivity}
11-17 18:21:41.777  1032  1121 W PackageSettings: Skipping PackageSetting{2e7994b9 com.test.thalitest/10311} due to missing metadata
,11-17 18:21:41.916  1032  1089 I ActivityManager:   Force finishing activity ActivityRecord{3ccfac4d u0 com.example.hello/.MainActivity t2}
,11-17 18:21:41.964   351   375 E GBMv2   : DFP En is all cleared set to be enabled
,11-17 18:21:41.972  1032  1953 W ActivityManager: Spurious death for ProcessRecord{1d42ea47 6015:com.example.hello/u0a318}, curProc for 6015: null
11-17 18:21:41.974  1032  1121 I ActivityManager: Force stopping com.example.hello appid=10318 user=0: pkg removed
,11-17 18:21:41.978  1032  1121 I ActivityManager:   Force finishing activity ActivityRecord{3ccfac4d u0 com.example.hello/.MainActivity t2 f}
11-17 18:21:41.978  1032  1121 W ActivityManager: Duplicate finish request for ActivityRecord{3ccfac4d u0 com.example.hello/.MainActivity t2 f}
,11-17 18:21:42.009  2083  2083 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
11-17 18:21:42.009  1955  1970 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
11-17 18:21:42.009  1955  1970 D SplitWindowPolicy: topRunningActivity=ActivityInfo{15da7e1f co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
11-17 18:21:42.011  2083  2083 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
11-17 18:21:42.014  1955  2579 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
11-17 18:21:42.015  1955  2579 D SplitWindowPolicy: topRunningActivity=ActivityInfo{b6f556c co.....Launcher}, taskId=1, activityType=1, bIsSplit=false
11-17 18:21:42.017  1032  1089 D SplitWindowManager: removeStackAndNeedHomeResume ActivityStack{12c99274 stackId=1, 0 tasks}
11-17 18:21:42.021  1468  1468 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,11-17 18:21:42.030  2027  2027 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.example.hello
11-17 18:21:42.030  2690  2690 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.example.hello
11-17 18:21:42.036  1032  1376 I InputReader: Reconfiguring input devices.  changes=0x00000010
11-17 18:21:42.038  1829  2448 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-17 18:21:42.046  4214  4214 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.example.hello
11-17 18:21:42.046  4214  4214 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
,11-17 18:21:42.046  4214  4214 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
11-17 18:21:42.046  4214  4214 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
11-17 18:21:42.046  4214  4214 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
11-17 18:21:42.046  4214  4214 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 18:21:42.047  4214  4214 W System.err: 	at android.os.Looper.loop(Looper.java:135)
11-17 18:21:42.047  4214  4214 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
11-17 18:21:42.047  4214  4214 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:21:42.047  4214  4214 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:21:42.047  4214  4214 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
11-17 18:21:42.047  4214  4214 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,11-17 18:21:42.080  1032  1089 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=6233 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,11-17 18:21:42.084  2083  2083 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
11-17 18:21:42.086  1884  1884 D SplitUIManager: split_name #11 / not available #0
11-17 18:21:42.087  1884  1884 D SplitUIService: removed split : 
11-17 18:21:42.088  2083  2155 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
11-17 18:21:42.088  1468  1468 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
11-17 18:21:42.092  1918  1918 D ActionManagerService: notifyUserLog: 1000003
11-17 18:21:42.092  2083  2083 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
11-17 18:21:42.093  2690  4168 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
11-17 18:21:42.094  1468  1646 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
11-17 18:21:42.094  1468  1646 D KeyguardModel: createShortcutInfo...
11-17 18:21:42.098  1468  1646 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
11-17 18:21:42.098  1468  1646 D KeyguardModel: createShortcutInfo...
,11-17 18:21:42.101  2083  2083 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
11-17 18:21:42.103  2083  2083 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
11-17 18:21:42.105  2083  2083 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
11-17 18:21:42.109  1918  1918 D ActionManagerService: notifyUserLog: 1000004
11-17 18:21:42.109  2083  2083 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
11-17 18:21:42.110  2690  4168 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
11-17 18:21:42.111  2690  2707 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
11-17 18:21:42.112  1468  1468 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
11-17 18:21:42.112  1468  1468 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
11-17 18:21:42.113  4255  4255 I art     : Explicit concurrent mark sweep GC freed 17339(972KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 678us total 110.346ms
11-17 18:21:42.115  2083  2083 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
11-17 18:21:42.115  2083  2083 I GBoardWebViewUtils: , create_time: 1430558575574
11-17 18:21:42.115  2083  2083 I GBoardWebViewUtils: , expire_time: 0
11-17 18:21:42.115  2083  2083 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
11-17 18:21:42.115  2083  2083 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
11-17 18:21:42.115  2083  2083 I GBoardWebViewUtils: , display: false
11-17 18:21:42.115  2083  2083 I GBoardWebViewUtils: , animation: false }
11-17 18:21:42.115  2083  2083 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
11-17 18:21:42.115  2083  2083 I GBoardWebViewUtils: , create_time: 1430558575600
11-17 18:21:42.115  2083  2083 I GBoardWebViewUtils: , expire_time: 0
11-17 18:21:42.115  2083  2083 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
11-17 18:21:42.115  2083  2083 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
11-17 18:21:42.115  2083  2083 I GBoardWebViewUtils: , display: false
11-17 18:21:42.115  2083  2083 I GBoardWebViewUtils: , animation: false }
11-17 18:21:42.115  2083  2083 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1447331016048
11-17 18:21:42.115  2083  2083 I GBoardWebViewUtils: , create_time: 1447331016852
11-17 18:21:42.115  2083  2083 I GBoardWebViewUtils: , expire_time: 0
11-17 18:21:42.115  2083  2083 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide.html?id=guide_1111111111116_1447331016048&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
11-17 18:21:42.115  2083  2083 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
11-17 18:21:42.115  2083  2083 I GBoardWebViewUtils: , display: false
11-17 18:21:42.115  2083  2083 I GBoardWebViewUtils: , animation: false }
,11-17 18:21:42.117  1468  1646 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
11-17 18:21:42.117  1468  1646 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
11-17 18:21:42.117  1468  1646 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
11-17 18:21:42.118  1468  1646 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
11-17 18:21:42.119  1468  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
11-17 18:21:42.119  1468  1646 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
11-17 18:21:42.124  2083  6250 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
11-17 18:21:42.135  1468  1646 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
11-17 18:21:42.136  1468  1646 D KeyguardModel: createShortcutInfo...
,11-17 18:21:42.143  1884  1884 D SplitUIManager: split_name #11 / not available #0
11-17 18:21:42.143  1884  1884 I SplitUIService: split app #11
11-17 18:21:42.143  1032  1107 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
11-17 18:21:42.144  1032  1107 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
11-17 18:21:42.144  1032  1107 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
11-17 18:21:42.144  1032  1107 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
11-17 18:21:42.144  1032  1107 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@f5a90af,  pkg=WindowManager.LayoutParams
11-17 18:21:42.144  1032  1107 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
11-17 18:21:42.148  1468  1646 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
11-17 18:21:42.148  1468  1646 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,11-17 18:21:42.150  1468  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
11-17 18:21:42.150  1468  1646 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
11-17 18:21:42.153  1468  1646 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
11-17 18:21:42.153  1468  1646 D KeyguardModel: createShortcutInfo...
11-17 18:21:42.166  1468  1646 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
11-17 18:21:42.166  2083  2083 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
11-17 18:21:42.166  1468  1646 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
11-17 18:21:42.166  1468  1646 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
11-17 18:21:42.166  1468  1646 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
11-17 18:21:42.166  2083  2083 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,11-17 18:21:42.168  1468  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
11-17 18:21:42.168  1468  1646 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
11-17 18:21:42.181  1468  1646 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
,11-17 18:21:42.182  1468  1646 D KeyguardModel: createShortcutInfo...
11-17 18:21:42.187  1468  1468 D KeyguardModel: handleShortcutListChanged...
11-17 18:21:42.188  1032  1637 V SIM_STK : Menu title from STK is T-Mobile
11-17 18:21:42.189  1468  1646 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
11-17 18:21:42.189  1468  1646 D KeyguardModel: createShortcutInfo...
11-17 18:21:42.192  1468  1646 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
11-17 18:21:42.192  1468  1646 D KeyguardModel: createShortcutInfo...
,11-17 18:21:42.194  1468  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
11-17 18:21:42.194  1468  1646 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
11-17 18:21:42.200  1468  1646 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
11-17 18:21:42.200  1468  1646 D KeyguardModel: createShortcutInfo...
11-17 18:21:42.205  6233  6233 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,11-17 18:21:42.218  1032  1032 I art     : Explicit concurrent mark sweep GC freed 13295(999KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 44MB/66MB, paused 2.886ms total 212.582ms
11-17 18:21:42.218  1468  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
11-17 18:21:42.218  1468  1646 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,11-17 18:21:42.221  1032  1121 I art     : WaitForGcToComplete blocked for 204.567ms for cause Explicit
11-17 18:21:42.222  1468  1646 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
11-17 18:21:42.222  1468  1646 D KeyguardModel: createShortcutInfo...
11-17 18:21:42.224  1468  1646 W ResourceType: No package identifier when getting value for resource number 0x00000000
11-17 18:21:42.224  1468  1646 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
11-17 18:21:42.235  1468  1646 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
11-17 18:21:42.236  1468  1646 D KeyguardModel: createShortcutInfo...
,11-17 18:21:42.245  6233  6233 D PluginManager: init()
,11-17 18:21:42.259  1468  1468 D KeyguardModel: handleShortcutListChanged...
11-17 18:21:42.264  1032  1032 D administrator: Handling package changes for user 0
11-17 18:21:42.281  2083  2083 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,11-17 18:21:42.357  1032  1047 V SIM_STK : Menu title from STK is T-Mobile
,11-17 18:21:42.372  2083  2083 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,11-17 18:21:42.376  2083  2083 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
11-17 18:21:42.378  2083  2083 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
11-17 18:21:42.379  2083  2083 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
11-17 18:21:42.381  2083  2083 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
11-17 18:21:42.383  2083  2083 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
11-17 18:21:42.394  1032  1109 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{127c4f1f u0 com.lge.launcher2/.Launcher t1} time:88304
,11-17 18:21:42.408  2083  2083 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
11-17 18:21:42.408  2083  2083 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
11-17 18:21:42.414  2083  2572 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
11-17 18:21:42.415  2083  2572 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
11-17 18:21:42.428  1032  1032 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
11-17 18:21:42.428  1032  1032 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
11-17 18:21:42.429  1032  1032 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
11-17 18:21:42.430  2083  2083 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,11-17 18:21:42.431  2083  2083 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
11-17 18:21:42.431  2083  2083 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
11-17 18:21:42.432  1468  1468 D PhoneStatusBar: setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
11-17 18:21:42.433  1468  1468 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
11-17 18:21:42.433  1468  1468 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
11-17 18:21:42.433  1468  1468 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
11-17 18:21:42.433  1032  1431 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
11-17 18:21:42.440  2083  2083 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
11-17 18:21:42.442  2609  2609 D [Concierge]Service: onStartCommand(). Type : 8
11-17 18:21:42.442  2609  2609 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,11-17 18:21:42.443  2609  2609 D [Concierge]Service: Update widget ID : 11
11-17 18:21:42.444  2083  2083 D [Concierge]WidgetView: change position of spinner
11-17 18:21:42.455  2083  2083 I [Concierge]WidgetView: initWebView(). Time : 1447780902454
,11-17 18:21:42.456  2609  2609 D [Concierge]Service: onStartCommand(). Type : 0
11-17 18:21:42.470  2083  2083 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 180591904
11-17 18:21:42.470  2083  2083 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
11-17 18:21:42.470  2083  2083 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,11-17 18:21:42.473  2083  2083 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@49d0b10
11-17 18:21:42.473  2083  2083 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
11-17 18:21:42.474  2083  2083 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
11-17 18:21:42.474  2083  2083 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
11-17 18:21:42.480  2083  2083 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
11-17 18:21:42.480  2083  2083 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
11-17 18:21:42.481  2083  2083 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
11-17 18:21:42.490  2083  2083 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1447780842126, New one : 1447780902454
11-17 18:21:42.490  2083  2083 D [Concierge]WidgetView: Unregister all receivers
11-17 18:21:42.490  2083  2083 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
11-17 18:21:42.491  2083  2083 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
11-17 18:21:42.493  2083  2083 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
11-17 18:21:42.494  2083  2083 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
11-17 18:21:42.495  2083  2083 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
11-17 18:21:42.496  2083  2083 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
11-17 18:21:42.497  2083  2083 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
11-17 18:21:42.498  2083  2083 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
11-17 18:21:42.498  2083  2083 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,11-17 18:21:42.543  2083  2083 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,11-17 18:21:42.557  2083  2083 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
11-17 18:21:42.557  2083  2083 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,11-17 18:21:42.560  2083  2083 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
11-17 18:21:42.580  2083  2083 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1e37955b time:88489
,11-17 18:21:42.583  1032  1121 I art     : Explicit concurrent mark sweep GC freed 8653(456KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 4.064ms total 359.375ms
11-17 18:21:42.598  6139  6167 D AlertService: Beginning updateAlertNotification
,11-17 18:21:42.606  6139  6167 D AlertService: No fired or scheduled alerts
11-17 18:21:42.622  6139  6167 D AlertService: Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,11-17 18:21:42.636  6139  6167 D AlarmScheduler: No events found starting within 1 week.
11-17 18:21:42.642  1032  1720 I ActivityManager: Killing 5643:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,11-17 18:21:42.652  6176  6176 D AndroidRuntime: Shutting down VM
11-17 18:21:42.679  1032  1088 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,11-17 18:21:42.688  1032  1088 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
11-17 18:21:42.732  1032  1429 W libprocessgroup: failed to open /acct/uid_10061/pid_5643/cgroup.procs: No such file or directory
,11-17 18:21:42.747  2083  2083 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,11-17 18:21:42.779  6233  6233 W ExternalStrings: load override strings
11-17 18:21:42.779  6233  6233 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
11-17 18:21:42.779  6233  6233 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
11-17 18:21:42.779  6233  6233 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
11-17 18:21:42.779  6233  6233 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
11-17 18:21:42.779  6233  6233 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
11-17 18:21:42.779  6233  6233 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
11-17 18:21:42.779  6233  6233 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
11-17 18:21:42.779  6233  6233 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
11-17 18:21:42.779  6233  6233 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
11-17 18:21:42.779  6233  6233 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
11-17 18:21:42.779  6233  6233 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
11-17 18:21:42.779  6233  6233 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:21:42.779  6233  6233 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
11-17 18:21:42.779  6233  6233 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
11-17 18:21:42.779  6233  6233 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:21:42.779  6233  6233 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:21:42.779  6233  6233 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
11-17 18:21:42.779  6233  6233 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,11-17 18:21:42.781  6233  6233 D StatusProvider: onCreate
11-17 18:21:42.828  2083  2083 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,11-17 18:21:42.850  6233  6233 V Signer  : override build config not found
,11-17 18:21:42.851  6233  6233 D Signer  : value of property debug is false
11-17 18:21:42.901  2083  2802 I GBoardtInterface: onReloaded()
,11-17 18:21:42.904  2083  2083 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
11-17 18:21:42.907  2690  2737 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
11-17 18:21:42.912  2690  2709 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
11-17 18:21:42.914  6233  6233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
,11-17 18:21:42.914  6233  6233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
11-17 18:21:42.915  6233  6233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
11-17 18:21:42.915  6233  6233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
11-17 18:21:42.915  6233  6233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
11-17 18:21:42.922  6233  6233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
11-17 18:21:42.923  6233  6233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
11-17 18:21:42.923  6233  6233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
11-17 18:21:42.923  6233  6233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
11-17 18:21:42.923  6233  6233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
11-17 18:21:42.924  6233  6233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
11-17 18:21:42.924  6233  6233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
11-17 18:21:42.924  6233  6233 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
11-17 18:21:42.929  1918  1918 D ActionManagerService: notifyUserLog: 1000001
,11-17 18:21:42.932  2690  4168 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
11-17 18:21:42.932  2690  4168 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
11-17 18:21:42.939  6233  6233 V LGMDMManager: Create singleton instance
11-17 18:21:42.940  1918  1918 D ActionManagerService: notifyUserLog: 1000001
11-17 18:21:42.942  2690  4168 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
11-17 18:21:42.942  2690  4168 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
11-17 18:21:42.942  2690  4168 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
11-17 18:21:42.942  2690  4168 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
,11-17 18:21:42.949  2690  2709 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
11-17 18:21:42.954  2083  2083 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
,11-17 18:21:42.958  2083  2083 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
11-17 18:21:42.963  2083  2083 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
11-17 18:21:42.963  2083  2083 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
11-17 18:21:42.966  2083  2083 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1447331016048&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
11-17 18:21:42.966  2083  2083 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/3/userguide2.html?id=guide_1111111111116_1447331016048&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,11-17 18:21:43.024  6233  6233 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,11-17 18:21:43.135  6233  6233 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,11-17 18:21:43.143  6233  6262 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
11-17 18:21:43.144  5534  5534 E SQLiteLog: (3850) statement aborts at 24: [INSERT INTO exclude_apps(package) VALUES (?)] disk I/O error
11-17 18:21:43.146  5534  5534 E SQLiteDatabase: Error inserting package=com.example.hello
11-17 18:21:43.146  5534  5534 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-17 18:21:43.146  5534  5534 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
11-17 18:21:43.146  5534  5534 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
11-17 18:21:43.146  5534  5534 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
11-17 18:21:43.146  5534  5534 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
11-17 18:21:43.146  5534  5534 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
11-17 18:21:43.146  5534  5534 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
11-17 18:21:43.146  5534  5534 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.insert(AppBoxContentProvider.java:220)
11-17 18:21:43.146  5534  5534 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
11-17 18:21:43.146  5534  5534 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
11-17 18:21:43.146  5534  5534 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeApp(PreloadListManagerHelper.java:134)
11-17 18:21:43.146  5534  5534 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.addExcludeAppInternal(PreloadListManagerHelper.java:115)
11-17 18:21:43.146  5534  5534 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onRemoveAppEvent(PreloadListManagerHelper.java:100)
11-17 18:21:43.146  5534  5534 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.updateExDb(PreloadListManagerHelper.java:65)
11-17 18:21:43.146  5534  5534 E SQLiteDatabase: 	at com.lge.appbox.manager.PreloadListManagerHelper.onReceive(PreloadListManagerHelper.java:46)
11-17 18:21:43.146  5534  5534 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2586)
11-17 18:21:43.146  5534  5534 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:148)
11-17 18:21:43.146  5534  5534 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1360)
11-17 18:21:43.146  5534  5534 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 18:21:43.146  5534  5534 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
11-17 18:21:43.146  5534  5534 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
11-17 18:21:43.146  5534  5534 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 18:21:43.146  5534  5534 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
11-17 18:21:43.146  5534  5534 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
11-17 18:21:43.146  5534  5534 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
```
