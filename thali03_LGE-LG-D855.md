#### Test 55634150e857e16_thali03_LGE-LG-D855 Logs


```
--------- beginning of main
I/UEI.SmartControl( 6269): Device manager: loading config....
D/UEI.SmartControl( 6269): ----------- loading internal config...
--------- beginning of system
W/ContextImpl( 6269): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
E/UEI.SmartControl( 6269): Loading SETTINGS...
,D/UEI.SmartControl( 6269): -- Open brand translation xml: brands_translations_ko
I/UEI.SmartControl( 6269): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6269): -----service ready thread exits
W/libprocessgroup( 1038): failed to open /acct/uid_10010/pid_5708/cgroup.procs: No such file or directory
E/UEI.SmartControl( 6269): Services init done
D/UEI.SmartControl( 6269): QS Service init finished
D/UEI.SmartControl( 6269): QS Service version name: 2.1.91
D/UEI.SmartControl( 6269): QS Service version code: 201091
D/UEI.SmartControl( 6269): Service requested: Control
I/ActivityManager( 1038): Killing 5438:com.google.android.music:main/u0a92 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10092/pid_5438/cgroup.procs: No such file or directory
E/ActivityThread( 6269): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@380cd214 that was originally bound here
E/ActivityThread( 6269): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.g@380cd214 that was originally bound here
E/ActivityThread( 6269): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1167)
E/ActivityThread( 6269): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1061)
E/ActivityThread( 6269): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1839)
E/ActivityThread( 6269): 	at android.app.ContextImpl.bindService(ContextImpl.java:1822)
E/ActivityThread( 6269): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6269): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6269): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6269): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6269): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2738)
E/ActivityThread( 6269): 	at android.app.ActivityThread.access$1800(ActivityThread.java:148)
E/ActivityThread( 6269): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1366)
E/ActivityThread( 6269): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6269): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6269): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
E/ActivityThread( 6269): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6269): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6269): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
E/ActivityThread( 6269): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/UEI.SmartControl( 6269): Internal service binding...
D/Finsky  ( 6398): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/LgDataFeature( 6398): LgDataFeature() Constructor: none
D/LgDataFeature( 6398): LgDataFeature() Constructor Done, null
D/AndroidRuntime( 6424): 
D/AndroidRuntime( 6424): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6424): CheckJNI is OFF
D/AndroidRuntime( 6424): Calling main entry com.android.commands.am.Am
D/Finsky  ( 6398): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
I/ActivityManager( 1038): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
V/SplitWindowPolicy( 1978): checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
D/SplitInfo( 1038): new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{11aca27b #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager( 1038): setTaskToReturnTo : TaskRecord{11aca27b #4 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx( 1038): AppWindowTokenEx init.. 
E/GBMv2   (  336): DFP En is all cleared set to be enabled
I/ActivityManager( 1038): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=6461 uid=10319 gids={50319, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/AndroidRuntime( 6424): Shutting down VM
V/ActivityManager( 1038): Display changed displayId=0
D/DSDPConnection( 1873): Display #0 changed.
D/SplitWindowPolicy( 1978): updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1978): topRunningActivity=ActivityInfo{2590ae2a co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
D/SplitWindowPolicy( 1978): updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
D/SplitWindowPolicy( 1978): topRunningActivity=ActivityInfo{3227241b co.....MainActivity}, taskId=4, activityType=0, bIsSplit=false
I/ActivityManager( 1038): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6482 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
D/ContextHelper( 6461): convertTheme. context->name=com.example.hello themeResourceId=16973833
W/Settings( 6398): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6398): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ResourcesManager( 6482): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6482): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/DownloadManager( 3396): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3396): created cursor android.database.sqlite.SQLiteCursor@fe3933f on behalf of 6398
,I/MultiDex( 6482): VM with version 2.1.0 has multidex support
I/MultiDex( 6482): install
I/MultiDex( 6482): VM has multidex support, MultiDex support library is disabled.
I/WebViewFactory( 6461): Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
I/ActivityManager( 1038): Killing 5924:com.google.android.gm/u0a64 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10064/pid_5924/cgroup.procs: No such file or directory
D/Finsky  ( 6398): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6398): [1] 2.run: Finished loading 1 libraries.
I/LibraryLoader( 6461): Loading: webviewchromium
I/LibraryLoader( 6461): Time to load native libraries: 4 ms (timestamps 4817-4821)
I/LibraryLoader( 6461): Expected native library version number "",actual native library version number ""
D/Finsky  ( 6398): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 2372): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
D/ChimeraCfgMgr( 2372): Loading module com.google.android.gms.games from APK com.google.android.gms
D/Finsky  ( 6398): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ConfigFetchService( 2372): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
V/JNIHelp ( 6482): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
V/WebViewChromiumFactoryProvider( 6461): Binding Chromium to main looper Looper (main, tid 1) {392f085a}
I/ConfigFetchService( 2372): launchTask
I/LibraryLoader( 6461): Expected native library version number "",actual native library version number ""
I/chromium( 6461): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6461): Initializing chromium process, renderers=0
D/ChimeraCfgMgr( 2372): Loading module com.google.android.gms.vision from APK com.google.android.gms
W/art     ( 6461): Attempt to remove local handle scope entry from IRT, ignoring
D/Vision  ( 2372): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 2372): Failed to find package metadata for com.example.hello
D/Vision  ( 2372): No vision deps
V/ConfigFetchTask( 2372): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1U9egEzJkyiqPHc0MwNdXJXVo0UvAe7u66FZA0YJ7ezsMEwt_JOtPYZ3mWf82_XBt6bSakez_43sC-Ais8otULRzLpilCFNvb415yvi7f0D8l_ZoOJzFs8wmvN0iMxFi2O44nNMi4Tjcpu1DEmhcVxm2exOUVM1ZHJRXAAECaEfjMfzDpk9Loa4ZyH_u--eJG4PDr2CE7NIPKVeMy8F4j-WMntx0_Tdup0FevMPG5BK94CCfhY
V/AudioPolicyService(  314): registerClient() client 0xb57be360, uid 10319
I/GoogleURLConnFactory( 2372): Using platform SSLCertificateSocketFactory
W/chromium( 6461): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 6461): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
I/chromium( 6461): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
D/BluetoothManagerService( 1038): Message: 20
D/BluetoothManagerService( 1038): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1666874:true
W/ActivityThread( 6482): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6482): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1d99660d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6482): Installed default security provider GmsCore_OpenSSL
I/Adreno-EGL( 6461): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6461): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6461): Build Date: 12/12/14 금
I/Adreno-EGL( 6461): Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
I/Adreno-EGL( 6461): Remote Branch: 
I/Adreno-EGL( 6461): Local Patches: 
I/Adreno-EGL( 6461): Reconstruct Branch: 
I/ActivityManager( 1038): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6525 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
I/PeopleContactsSync( 2372): CP2 sync disabled
W/chromium( 6461): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=1
D/libc-netbsd(  308): res_queryN name = android.clients.google.com, class = 1, type = 1
W/chromium( 6461): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
W/art     ( 6461): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 6461): onDetachedFromWindow called when already detached. Ignoring
D/libc-netbsd(  308): res_queryN name = android.clients.google.com succeed
D/SystemWebViewEngine( 6461): CordovaWebView is running on device made by: LGE
W/art     ( 6461): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 6461): Attempt to remove local handle scope entry from IRT, ignoring
I/DigitalAppWidgetProvider( 6525): onReceive: android.intent.action.ALARM_CHANGED
W/ActivityManager( 1038): Activity pause timeout for ActivityRecord{624d898 u0 com.example.hello/.MainActivity t4}
D/OpenGLRenderer( 6461): Render dirty regions requested: true
I/OpenGLRenderer( 6461): Initialized EGL, version 1.4
D/OpenGLRenderer( 6461): Enabling debug mode 0
D/Atlas   ( 6461): Validating map...
D/SplitWindow( 1038): check instance of lgWin Window{1bf72fc5 u0 com.example.hello/com.example.hello.MainActivity}
I/ActivityManager( 1038): Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6562 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 5972:com.google.android.talk/u0a72 (adj 15): empty #17
I/art     (  340): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 261us total 12.354ms
D/LgDataFeature( 6461): LgDataFeature() Constructor: none
D/LgDataFeature( 6461): LgDataFeature() Constructor Done, null
I/art     (  340): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 250us total 11.728ms
I/art     (  340): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 257us total 11.857ms
W/libprocessgroup( 1038): failed to open /acct/uid_10072/pid_5972/cgroup.procs: No such file or directory
I/ConfigFetchService( 2372): fetch service done; releasing wakelock
I/ConfigFetchService( 2372): stopping self
I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.android.systemui
W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3d8c3edd,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/art     ( 6562): Almond Protected OAT
I/art     ( 1038): Explicit concurrent mark sweep GC freed 20226(978KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 2.110ms total 147.957ms
I/art     ( 1038): WaitForGcToComplete blocked for 107.729ms for cause HeapTrim
D/WeatherApplication( 6562): removeAccount
D/PhoneStatusBar( 1474): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8000 newVal=0 diff=8000
I/[SystemUI]NavigationThemeResource( 1474): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1474):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1474): , Keyguard show=false, IME shown=false, Panel expanded=false
D/WeatherApplication( 6562): Account.length = 0
E/WeatherApplication( 6562): OPERATOR:OPEN
D/WeatherAncestor( 6562): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 17:10:49
D/Weather.Utils( 6562): 2 : the weather widgets(using time tick) are gone.
D/Weather.Utils( 6562): 2 : All the weather widget is gone.
I/ActivityManager( 1038): Killing 6051:com.android.providers.calendar/u0a14 (adj 15): empty #17
D/UpdateThreadPoolManager( 6562): 2 : This is isUpdating : false
I/Timeline( 6461): Timeline: Activity_idle id: android.os.BinderProxy@3b0a3c0a time:75431
I/chromium( 6461): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 6461): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/ActivityManager( 1038): Displayed com.example.hello/.MainActivity: +905ms (total +1s31ms)
I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{624d898 u0 com.example.hello/.MainActivity t4} time:75485
D/JsMessageQueue( 6461): Set native->JS mode to OnlineEventsBridgeMode
V/AlarmManager( 1038): RTC_WAKEUP set : Alarm{139170ca type 0 when 1452528649365 com.android.vending} when 1452528649365
W/libprocessgroup( 1038): failed to open /acct/uid_10014/pid_6051/cgroup.procs: No such file or directory
D/Weather_cast( 6562): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 6562): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 17:10:49
I/chromium( 6461): [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
I/chromium( 6461): 
I/ActivityManager( 1038): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6587 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
D/Finsky  ( 6398): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 2140): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/Finsky  ( 6398): [1] GearheadStateMonitor.onReady: sIsProjecting:false
I/art     ( 2140): Explicit concurrent mark sweep GC freed 15948(885KB) AllocSpace objects, 6(864KB) LOS objects, 51% free, 30MB/62MB, paused 1.583ms total 30.360ms
W/ResourcesManager( 6587): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/jxcore_app_log( 6461): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435341568
D/JX-Cordova( 6461): jxcore cordova android initializing
I/GLSUser ( 2140): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2140): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2140): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2140): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2140): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/QRemote ( 6587): [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
W/Finsky  ( 6398): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
W/jxcore-log( 6461): Initializing JXcore engine
W/jxcore-log( 6461): JXcore engine is ready
V/GLSActivity( 2140): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/jxcore-log( 6461): Starting JXcore engine
D/QRemote ( 6587): [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
I/QRemote ( 6587): [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 6587): [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 6587): [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 6587): [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 6587): [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 6587): [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
I/GLSUser ( 2140): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 2140): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2140): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2140): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/QRemote ( 6587): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
D/QRemote ( 6587): [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
V/GLSActivity( 2140): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/m.example.hello( 6461): type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8419]" dev="sockfs" ino=8419 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 6461): type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
W/m.example.hello( 6461): type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10016]" dev="sockfs" ino=10016 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
W/m.example.hello( 6461): type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
W/m.example.hello( 6461): type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[30459]" dev="sockfs" ino=30459 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
V/GLSActivity( 2140): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LgDataFeature( 6587): LgDataFeature() Constructor: none
D/LgDataFeature( 6587): LgDataFeature() Constructor Done, null
V/SoundPool( 6587): SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
V/SoundPool( 6587): load: fd=27, offset=10857164, length=17813, priority=1
,V/SoundPool( 6587): create sampleID=1, fd=28, offset=17813 length=10857164
V/SoundPool( 6587): doLoad: loading sample sampleID=1
I/QRemote ( 6587): [RemoteControlManager.java:157:onBindIRService()] oooooo bind
V/SoundPool( 6587): Start decode
V/MediaPlayer[Native]( 6587): decode(28, 10857164, 17813)
I/GLSUser ( 2140): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
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
V/AudioCache(  314): notify(0xb54749c0, 8, 0, 0)
V/AudioCache(  314): ignored
V/AwesomePlayer(  314): cancelPlayerEvents
D/Utils   (  314): printFileName fd(25) -> /data/preload/LGQRemote/LGQRemote.apk
V/AwesomePlayer(  314): setDataSource_l dataSource
V/LGParserOSAL(  314): SniffLGParser start
V/LGParserOSAL(  314): MainType:5, SubType=0
V/LGParserOSAL(  314): #### check Mime : application/ogg
V/LGParserOSAL(  314): Detector mimeType:application/ogg, Confidence=1.000000
E/MediaExtractor(  314): Use LGExtractor :application/ogg 
D/QRemote ( 6587): [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
E/QRemote ( 6587): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
I/GLSUser ( 2140): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2140): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2140): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/LGMDMManager( 6587): Create singleton instance
,V/GLSActivity( 2140): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 6398): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
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
,D/AudioPolicyManager(  314): isOffloadSupported: stream_type != MUSIC, returning false
V/OMXCodec(  314): [OMX.google.vorbis.decoder] start mState=1
V/OMXCodec(  314): init()
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=1 , newState=2
V/OMXCodec(  314): allocateBuffers
V/OMXCodec(  314): allocateBuffersOnPort portIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc970 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14fc9c0 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14fca10 on input port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcc40 on input port
V/OMXCodec(  314): allocateBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcdd0 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcec0 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcf10 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcf60 on output port
V/OMXCodec(  314): init() mAsyncCompletion wait!!! 
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Idle.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=2 , newState=3
V/OMXCodec(  314): init() mAsyncCompletion wait!!! 
V/OMXCodec(  314): [OMX.google.vorbis.decoder] onStateChange 3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Now Executing.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=3 , newState=4
V/OMXCodec(  314): init() mAsyncCompletion wait free! 
V/AwesomePlayer(  314): finishAsyncPrepare_l() 
V/AudioCache(  314): notify(0xb54749c0, 5, 0, 0)
V/AudioCache(  314): ignored
V/AudioCache(  314): notify(0xb54749c0, 1, 0, 0)
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
V/OMXCodec(  314): [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=4 , newState=7
V/OMXCodec(  314): [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974797264
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974797504
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974797584
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 2974797664
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] PORT_DISABLED(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] initOutputFormat()
V/OMXCodec(  314): [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
V/OMXCodec(  314): [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
V/OMXCodec(  314): allocateBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcf10 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcec0 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb14fcdd0 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] allocated buffer 0xb54f7d80 on output port
V/OMXCodec(  314): [OMX.google.vorbis.decoder] PORT_ENABLED(1)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=7 , newState=4
V/AudioCache(  314): open(48000, 2, 0x0, 1, 4)
V/AudioCache(  314): notify(0xb54749c0, 6, 0, 0)
V/AudioCache(  314): ignored
V/MediaPlayerService(  314): wait for playback complete
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac602000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac603000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac604000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac605000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac606000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac607000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac608000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac609000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac60a000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac60b000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac60c000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac60d000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac60e000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac60f000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac610000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac611000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac612000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac613000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac614000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac615000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac616000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac617000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac618000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac619000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac61a000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac61b000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac61c000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac61d000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac61e000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac61f000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac620000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac621000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac622000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac623000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac624000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac625000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac626000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac627000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac628000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac629000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac62a000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac62b000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac62c000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac62d000, 0xb57fc000, 4096)
,W/jxcore-log( 6461): Platform android
W/jxcore-log( 6461): 
W/jxcore-log( 6461): Process ARCH arm
W/jxcore-log( 6461): 
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac62e000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac62f000, 0xb57fc000, 4096)
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac630000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac631000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac632000, 0xb57fc000, 4096)
V/AudioCache(  314): write(0xb57fc000, 4096)
V/AudioCache(  314): memcpy(0xac633000, 0xb57fc000, 4096)
V/OMXCodec(  314): [OMX.google.vorbis.decoder] No more output data.
V/OMXCodec(  314): [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
V/AwesomePlayer(  314): postAudioEOS() 
V/AudioCache(  314): write(0xb57fc000, 280)
V/AudioCache(  314): memcpy(0xac634000, 0xb57fc000, 280)
V/AwesomePlayer(  314): postStreamDoneEvent_l() -> status:-1011 
V/AwesomePlayer(  314): onStreamDone
V/AwesomePlayer(  314): MEDIA_PLAYBACK_COMPLETE
V/AudioCache(  314): notify(0xb54749c0, 2, 0, 0)
V/AudioCache(  314): playback complete
V/AwesomePlayer(  314): pause_l() 
V/AudioCache(  314): notify(0xb54749c0, 7, 0, 0)
V/AudioCache(  314): wait - success
V/AudioCache(  314): ignored
V/AwesomePlayer(  314): cancelPlayerEvents
V/MediaPlayerService(  314): return size 205080, sampleRate=48000, channelCount = 2, format = 1
D/AudioPlayer(  314): Pause Playback at 1068125
V/AwesomePlayer(  314): reset_l() 
V/AudioCache(  314): notify(0xb54749c0, 8, 0, 0)
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
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb14fcc40 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb14fca10 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc9c0 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb14fc970 on port 0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb54f7d80 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb14fcdd0 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb14fcec0 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeing buffer 0xb14fcf10 on port 1
V/OMXCodec(  314): [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
V/OMXCodec(  314): [OMX.google.vorbis.decoder] setState mState=5 , newState=6
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
V/SoundPool( 6587): close(28)
V/SoundPool( 6587): pointer = 0x9ff28000, size = 205080, sampleRate = 48000, numChannels = 2
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3165
D/QRemote ( 6587): [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
D/QRemote ( 6587): [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
I/QRemote ( 6587): [RemoteControlManager.java:183:onServiceConnected()] oooooo start
I/UEI.SmartControl( 6269): ------ IControl API: 11
D/UEI.SmartControl( 6269): File observer start...
E/UEI.SmartControl( 6269): IR Port is disabled: false
D/UEI.SmartControl( 6269): Starting file observer...
I/UEI.SmartControl( 6269): Registering callback...
I/UEI.SmartControl( 6269): ------ IControl API: 19
I/UEI.SmartControl( 6269): Registering Services Ready callback...
I/UEI.SmartControl( 6269): Notify client services are ready...
I/QRemote ( 6587): [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
D/QRemote ( 6587): [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
D/QRemote ( 6587): [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
D/QRemote ( 6587): [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
D/QRemote ( 6587): [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
I/UEI.SmartControl( 6269): ------ IControl API: 8
,D/QRemote ( 6587): [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
D/QRemote ( 6587): [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
E/GBMv2   (  336): DFP En is all cleared set to be enabled
D/QRemote ( 6587): [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
E/GBMv2   (  336): Set value is all cleared set the max
I/GBMv2   (  336): DFP Enabled. Ignore VFP set
D/QRemote ( 6587): [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
D/QRemote ( 6587): [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
D/QRemote ( 6587): [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
I/jxcore-log( 6461): JXcore Cordova bridge is ready!
I/jxcore-log( 6461): 
W/jxcore-log( 6461): JXcore engine is started
,I/ActivityManager( 1038): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=6616 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/chromium( 6461): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 6461): 
D/QRemote ( 6587): [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
D/QRemote ( 6587): [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
I/ActivityManager( 1038): Killing 6073:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,E/jxcore-log( 6461): >> LGE-LG-D855
E/jxcore-log( 6461): 
,I/jxcore-log( 6461): Total memory 2995761152
I/jxcore-log( 6461): 
I/jxcore-log( 6461): Free memory 571428864
I/jxcore-log( 6461): 
I/jxcore-log( 6461): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6461): 
I/jxcore-log( 6461): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 6461): 
I/jxcore-log( 6461): userPath [ 'www', 'www' ]
I/jxcore-log( 6461): 
I/jxcore-log( 6461): Size 1440 2392
I/jxcore-log( 6461): 
I/jxcore-log( 6461): Screen Brightness 50
I/jxcore-log( 6461): 
E/jxcore-log( 6461): Dummy Error Log.
E/jxcore-log( 6461): 
W/libprocessgroup( 1038): failed to open /acct/uid_10008/pid_6073/cgroup.procs: No such file or directory
,V/GLSActivity( 2140): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 2140): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 2140): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 2140): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 2140): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 2140): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/Finsky  ( 6398): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6398): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
D/Finsky  ( 6398): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6398): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
I/ActivityManager( 1038): Killing 6115:com.android.contacts/u0a19 (adj 15): empty #17
,D/DeviceConnectionService( 1838): client connected with version: 7571000
I/MusicStore( 6616): Database version: 100
,I/ActivityManager( 1038): Killing 6094:com.lge.appbox.client/u0a11 (adj 15): empty #18
,W/libprocessgroup( 1038): failed to open /acct/uid_10019/pid_6115/cgroup.procs: No such file or directory
,W/libprocessgroup( 1038): failed to open /acct/uid_10011/pid_6094/cgroup.procs: No such file or directory
D/LgDataFeature( 6616): LgDataFeature() Constructor: none
,D/LgDataFeature( 6616): LgDataFeature() Constructor Done, null
I/ConfigStore( 6616): Config Database version: 1
,E/PlayEventLogger( 6616): Invalid device id bea67b7c50ddc6a9
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6616): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/jxcore-log( 6461): getBuffer is called!!!!
I/jxcore-log( 6461): 
,E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6616): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  280): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  280): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  280): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6616): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/MediaRouter( 6616): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/NetworkMonitor( 6616): type=WIFI subType= reason=null isConnected=true
,D/WearableService( 6023): callingUid 10005, callindPid: 6023
,V/QRemote ( 6587): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6587): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
I/NetworkMonitor( 6616): type=WIFI subType= reason=null isConnected=true
D/QRemote ( 6587): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1452528650756]
V/QRemote ( 6587): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,D/QRemote ( 6587): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6587): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
,D/QRemote ( 6587): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6587): [RemoteAppWidgetManager.java:36:startLoading()] oooooo 140518:startLoading:sWidgetHandler has [3] at [1452528650765]. skip
D/QRemote ( 6587): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,I/ActivityManager( 1038): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6661 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicLeanback( 6616): Stop autocaching.
I/MusicLeanback( 6616): Stop autocaching.
,I/GoogleHttpClient( 6616): Falling back to old http client 0 java.lang.NoSuchMethodException: <init> [class android.content.Context, class java.lang.String, boolean, boolean]
I/MusicLeanback( 6616): Stop autocaching.
,I/MusicLeanback( 6616): Stop autocaching.
I/MusicLeanback( 6616): Conditions not met for autocaching.
I/MusicLeanback( 6616): Stop autocaching.
D/WearableClient( 6616): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 6616): WearableClientImpl.onPostInitHandler: done
D/WearableClient( 6616): WearableClientImpl.onPostInitHandler: done
E/GmsUtils( 6616): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,E/GmsUtils( 6616): Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
W/ActivityManager( 1038): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityThread( 6661): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
W/ActivityManager( 1038): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6661): getAccountsCursor
,V/GLSActivity( 2140): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1038): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager( 1038): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager( 1038): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 6661): Observing account changes for notifications
,W/ActivityManager( 1038): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/GAV2    ( 6661): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager( 1038): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6661): Error finding the version of the Email provider.....
E/Gmail   ( 6661): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6661): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6661): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1235)
E/Gmail   ( 6661): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:187)
E/Gmail   ( 6661): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6661): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6661): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6661): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6661): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6661): getAccountsCursor
,I/CheckinService( 2372): Done disabling old GoogleServicesFramework version
,I/art     ( 1038): Explicit concurrent mark sweep GC freed 13500(599KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 44MB/66MB, paused 2.588ms total 146.730ms
,V/GLSActivity( 2140): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/KeyguardViewMediator( 1474): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardUpdateMonitor( 1474): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1474): doKeyguard: not showing because lockscreen is off
D/GCM     ( 2140): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,V/GLSActivity( 2140): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AuthorizationBluetoothService( 2140): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2372): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/MDM     ( 1838): [83] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 2372): Restart initialization of location
,E/UEI.SmartControl( 6269): file observer is disposed!
E/SQLiteLog( 6661): (283) recovered 1137 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/ActivityManager( 1038): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6716 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/sensors_hal_Time( 1038): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time( 1038): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time( 1038): tsOffsetIs: Apps: 77719016797; DSPS: 2688014; Offset : -4328069380
W/ResourcesManager( 6716): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/GAV2    ( 6214): Thread[GAThread,5,main]: No campaign data found.
I/Gmail   ( 6661): getAccountsCursor
,I/Gmail   ( 6661): notifyAccountChanged
V/GLSActivity( 2140): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6661): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6661): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/LgDataFeature( 6716): LgDataFeature() Constructor: none
D/LgDataFeature( 6716): LgDataFeature() Constructor Done, null
,I/Gmail   ( 6661): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6661): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6661): getAccountsCursor
,V/GLSActivity( 2140): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Babel   ( 6716): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6716): MmsConfig.loadMmsSettings
I/Babel   ( 6716): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
I/Babel   ( 6716): MmsConfig.loadFromDatabase
,E/Babel   ( 6716): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6716): MmsConfig.loadFromResources
E/Babel   ( 6716): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6716): MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,W/Settings( 6716): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/AudioCapabilities( 6716): Unsupported mime audio/evrc
W/AudioCapabilities( 6716): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6716): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6716): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6716): Unsupported mime audio/qcelp
W/AudioCapabilities( 6716): Unsupported mime audio/evrc
I/ActivityManager( 1038): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6751 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/VideoCapabilities( 6716): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6716): Unsupported mime video/divx
W/VideoCapabilities( 6716): Unsupported mime video/divx311
W/VideoCapabilities( 6716): Unsupported mime video/divx4
,W/VideoCapabilities( 6716): Unsupported mime video/mp4v-esdp
,I/AppUp4:AppBoxCP( 6751): onCreate
,W/AppUp4:DB( 6751):  [AppBoxDatabaseHelper] construct
I/VideoCapabilities( 6716): Unsupported profile 4 for video/mp4v-es
I/AppUp4:DB( 6751):  setFingerPrint start
I/AppUp4:DB( 6751):  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
W/AudioCapabilities( 6716): Unsupported mime audio/eac3
W/AudioCapabilities( 6716): Unsupported mime audio/ac3
W/AudioCapabilities( 6716): Unsupported mime audio/g726
W/AudioCapabilities( 6716): Unsupported mime audio/wma-voice
W/AudioCapabilities( 6716): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6716): Unsupported mime audio/adpcm
W/VideoCapabilities( 6716): Unsupported mime video/theora
W/VideoCapabilities( 6716): Unsupported mime video/mjpg
I/AppUp4:DB( 6751):  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
,I/AppUp4:DB( 6751):  SDK version = 21
I/AppUp4:DB( 6751):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6751): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6751): onReceive
,D/LgDataFeature( 6751): LgDataFeature() Constructor: none
D/LgDataFeature( 6751): LgDataFeature() Constructor Done, null
,D/AppUp4:CustFacade( 6751): Context : android.app.ReceiverRestrictedContext@2dba9005
D/AppUp4:CustFacade( 6751): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6751): isPhone : true
D/AppUp4:CustModeStarterReceiver( 6751): begin check event
I/AppUp4:CustModeStarterReceiver( 6751): Event For Nothing, skip.
I/ActivityManager( 1038): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6774 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager( 1038): Killing 5373:com.android.defcontainer/u0a4 (adj 15): empty #17
W/libprocessgroup( 1038): failed to open /acct/uid_10004/pid_5373/cgroup.procs: No such file or directory
,W/ResourcesManager( 6774): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6774): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6774): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 6774): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6774): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 6774): BUILD Country: EU
I/SystemConfig( 6774): BUILD Operator: OPEN
,I/ActivityManager( 1038): Killing 6148:com.lge.email/u0a23 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_10023/pid_6148/cgroup.procs: No such file or directory
,I/SystemConfig( 6774): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6774): existFile = false
I/SystemConfig( 6774): canReadFile = false
I/SystemConfig( 6774): systemFeature RCS result false
D/SystemConfig( 6774): refreshRcsSupport() :false
,I/ActivityManager( 1038): Killing 4878:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_4878/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 4571): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
D/LockScreenSettings( 6312): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6312): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6312): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6312): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6312): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,D/LockScreenSettings( 6312): Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
D/PackageBroadcastService( 2372): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,V/QRemote ( 6587): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:5508
I/PackageBroadcastService( 2372): Null package name or gms related package.  Ignoreing.
D/GCM     ( 2140): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 2140): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2372): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
E/MDM     ( 1838): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/Icing   ( 2372): updateResources: need to parse f{com.google.android.gms}
D/LocationInitializer( 2372): Restart initialization of location
,V/QRemote ( 6587): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6587): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6587): [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1452528652783]
,V/QRemote ( 6587): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
E/QRemote ( 6587): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
D/QRemote ( 6587): [RemoteAppWidgetManager.java:36:startLoading()] oooooo 140518:startLoading:sWidgetHandler has [3] at [1452528652793]. skip
V/QRemote ( 6587): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 6587): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6587): [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,V/QRemote ( 6587): [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,E/QRemote ( 6587): [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
D/QRemote ( 6587): [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
D/UEI.SmartControl( 6269): Internal timer expired: 2
D/UEI.SmartControl( 6269): unbind internal service
,D/serial_port( 6269): close(fd = 24)
,I/UEI.SmartControl( 6269): Serial port is closed.
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,I/UpdateIcingCorporaServi( 4571): UpdateCorporaTask done [took 336 ms] updated apps [took 336 ms] 
,I/ConfigService( 2140): onDestroy
,D/BluetoothManagerService( 1038): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService( 1038): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@d054481 mBinding = false
,D/LocationManagerService( 1038): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1038): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,D/Ulp_jni ( 1038): JNI:system_update. Event-4
D/BluetoothManagerService( 1038): Message: 2
D/BluetoothManagerService( 1038): Sending off request.
D/LGBluetoothServiceAdapter( 3787): [BTUI] Precleanup
D/BluetoothAdapterState( 3787): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 3787): Setting state to 13
I/BluetoothAdapterState( 3787): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterProperties( 3787): onBluetoothDisable()
I/BluetoothAdapterState( 3787): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothAdapterProperties( 3787): Scan Mode:20
,D/BluetoothAdapterState( 3787): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/btif_config_util( 3787): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
V/BluetoothMapMasInstance( 3787): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 3787): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 3787): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 3787): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 3787): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 3787): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 3787): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 3787): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
,V/BluetoothPbapService( 3787): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/BtOppRfcommListener( 3787): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothFtpService:RfcommSocketAcceptThread( 3787): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothSapService( 3787): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/bt-l2cap( 3787): L2CAP - L2CA_Deregister() called for PSM: 0x000f
W/bt-btif ( 3787): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
W/bt-l2cap( 3787): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3787): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3787): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3787): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3787): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3787): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3787): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3787): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3787): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3787): L2CAP - L2CA_Deregister() called for PSM: 0x0011
W/bt-l2cap( 3787): L2CAP - L2CA_Deregister() called for PSM: 0x0013
E/bt-btif ( 3787): bta_gattc_deregister Deregister Failedm unknown client cif
D/BluetoothManagerService( 1038): Message: 60
D/BluetoothManagerService( 1038): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService( 1038): Bluetooth State Change Intent: 12 -> 13
,D/WifiService( 1038): New client listening to asynchronous messages
,I/ActivityManager( 1038): Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6813 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/WifiServiceImplEx( 1038): setWifiEnabled: false pid=6461, uid=10319, package= com.example.hello, App Lable : HelloWorld
D/WifiService( 1038): setWifiEnabled: false pid=6461, uid=10319
E/WifiService( 1038): Invoking mWifiStateMachine.setWifiEnabled
I/BluetoothMapService( 3787): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 3787): STATE_TURNING_OFF
V/BluetoothMapService( 3787): Handler(): got msg=4
D/BluetoothMapService( 3787): MAP Service closeService in
D/BluetoothMapMasInstance( 3787): MAP Service shutdown
D/LGBluetoothMapAdapter( 3787): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3787): MAP Service closeService out
D/LGBluetoothAPIService( 1978): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1474): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,V/BtOppService( 3787): Receiver DISABLED_ACTION 
I/BtOppRfcommListener( 3787): stopping Accept Thread
V/BtOppRfcommListener( 3787): close mBtServerSocket
I/BtOppRfcommListener( 3787): BluetoothSocket listen thread finished
V/BtOppRfcommListener( 3787): waiting for thread to terminate
V/BtOppRfcommListener( 3787): done waiting for thread to terminate
E/WifiStateMachine( 1038):  ConnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1038):  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1038):  ConnectModeState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1038):  DriverStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
E/WifiStateMachine( 1038): WifiStateMachine: Leaving Connected state
E/WifiConfigStore( 1038): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WifiNative-wlan0( 1038): doBoolean: SET_NETWORK 0 bssid any
,D/LocationManagerService( 1038): getAllProviders()=[passive, gps, network]
D/Ulp_jni ( 1038): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni ( 1038): JNI:system_update. Event-4
I/jxcore-log( 6461): ****TEST TOOK:  5198  ms ****
I/jxcore-log( 6461): 
I/jxcore-log( 6461): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 6461): 
D/WifiNative-wlan0( 1038): SET_NETWORK 0 bssid any: returned true
D/WifiNative-wlan0( 1038): doBoolean: SAVE_CONFIG
,D/WifiNative-wlan0( 1038): SAVE_CONFIG: returned true
D/LGWifiP2pService( 1038): InactiveState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2623): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/DhcpStateMachine( 1038): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,I/ActivityManager( 1038): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6838 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
D/CommandListener(  308): Clearing all IP addresses on wlan0
V/BtOppService( 3787): onDestroy
,D/LGBluetoothOppAdapter( 3787): [BTUI] LGBluetoothOppAdapter cleanup
V/NativeCrypto( 2140): Read error: ssl=0xaf4d6a00: I/O error during system call, Connection timed out
,V/NativeCrypto( 2140): SSL shutdown failed: ssl=0xaf4d6a00: I/O error during system call, Broken pipe
E/WifiStateMachine( 1038):  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService( 1038): ignoring duplicate network state non-change
D/ConnectivityService( 1038): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,D/LGWifiP2pService( 1038): InactiveState{ when=-6ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): P2pEnabledState{ when=-6ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiHS20( 1038): hidePasspointNotification off =false
V/WfdStateTracker( 1978): handleWifiStateChangedEvent: 0
D/WifiMonitor( 1038): stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@201cdc5e
D/ConnectivityService( 1038): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Forcing reevaluation
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Checking http://clients3.google.com/generate_204 on <unknown ssid>
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20( 1038): hidePasspointNotification off =false
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/WifiScanningService( 1038): SCAN_AVAILABLE : 1
D/RttService( 1038): SCAN_AVAILABLE : 1
D/LGWifiP2pService( 1038): P2pDisablingState
D/LGWifiP2pService( 1038): P2pDisablingState{ when=-15ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): p2p socket connection lost
,D/LGWifiP2pService( 1038): P2pDisabledState
V/WfdStateTracker( 1978): WfdStateTracker handleDirectStateChangedEvent: 0
D/WifiScanningService( 1038): DefaultState got{ when=-4ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1978): WifiP2pState is changed : false
D/RttService( 1038): EnabledState got{ when=-4ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
D/WfdsService( 1978): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsService( 1978): Set the WFDS Monitor: false
,D/WfdsMonitor( 1978): WFDS Monitor is stopped
D/WfdsService( 1978): STATE : WfdsDisabledState - enter
D/CtrlSupplicant( 1978): Received on exit socket, terminate
E/CtrlSupplicant( 1978): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
W/WfdsSession:Controller( 1978): DefaultState - msg [9441355] is not handled
D/WfdsMonitor( 1978): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1978): WfdsMonitorThread is received the interrupt - closing
W/WfdsService( 1978): DefaultState - msg [9445378] is not handled
D/WifiNetworkAgent( 1038): NetworkAgent: NetworkAgent channel lost
E/WifiStateMachine( 1038):  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
D/LGWifiP2pService( 1038): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService( 1038): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0( 1038): doBoolean: DRIVER BTCOEXMODE 2
I/wpa_supplicant( 2623): wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
D/WifiNative-wlan0( 1038): DRIVER BTCOEXMODE 2: returned true
D/WifiNative-wlan0( 1038): doBoolean: SET ps 1
,D/WifiNative-wlan0( 1038): SET ps 1: returned true
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/CommandListener(  308): Clearing all IP addresses on wlan0
D/ConnectivityService( 1038): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    ( 1038): disableDataServiceNotify
D/DSQN    ( 1038): stop dsqn bin
D/libc-netbsd(  308): default dns: query_ipv6=0, query_ipv4=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
,D/DSQN    ( 1038): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/WifiNative-p2p0( 1038): doBoolean: TERMINATE
D/WifiNative-p2p0( 1038): TERMINATE: returned true
E/WifiStateMachine( 1038): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1038): useWiFiOffloading() : false
E/WifiStateMachine( 1038): CONFIG_LGE_WLAN_PATH : true
D/WifiHS20( 1038): hidePasspointNotification off =false
D/ConnectivityService( 1038): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService( 1038): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat( 1038): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
W/Settings( 1038): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings( 1038): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed( 1038): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/CSLegacyTypeTracker( 1038): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::c69a:2ff:fe7b:60ac/64,192.168.1.141/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/ConnectivityManager.CallbackHandler( 1474): CM callback handler got msg 524292
D/CSLegacyTypeTracker( 1038): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService( 1038): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 1038): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService( 1038): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): EvaluatingState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null]( 1038): Disconnected - quitting
D/WIFI    ( 1038): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    ( 1038):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1873): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1,873):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy( 1038): [LG_RESTRICTED] !!!isConnected  type  :1
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
,D/LocSvc_java( 1038): Sending msg: 4 arg1:0 arg2:1
V/WfdStateTracker( 1978): WfdStateTracker handleDirectStateChangedEvent: 6
D/NetworkManagementService( 1038): Removing idletimer
W/Settings( 1038): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService( 1038): requestNetworkTransitionWakelock: wakelock - ignore in airplane mode
I/WifiServerServiceExt( 1038): WIFI_STATE_CHANGED_ACTION [0]
D/LocSvc_java( 1038): getAGpsConnectionInfo connType - 4
D/LocSvc_java( 1038): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java( 1038): ignore wifi update if we are not in OPENING or CLOSING
D/WifiServerServiceExt( 1038): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt( 1038): setSupplicantStateDISCONNECTED
I/StatusBar.NetworkController( 1474): networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
I/StatusBar.NetworkController( 1474): mWifiConnected = false, mWifiLevel = 0
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
,W/ResourcesManager( 6838): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6838): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6838): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6838): Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
W/ResourcesManager( 6838): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6838): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/TelephonyIcons( 1474): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
,D/TelephonyIcons( 1474): null signal icon name: drawable/stat_sys_signal_null
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
I/wpa_supplicant( 2623): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 2623): monitor socket send errors count : 1
I/wpa_supplicant( 2623): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1978-2\x00 that cannot receive messages
,D/WifiMonitor( 1038): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor( 1038): Dropping event because (p2p0) is stopped
D/DhcpStateMachine( 1038): StoppedState
D/DhcpStateMachine( 1038): StoppedState{ when=-123ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 1038):  SupplicantStoppingState CMD_ON_QUIT 0 0
E/WifiStateMachine( 1038):  DefaultState CMD_ON_QUIT 0 0
E/ActivityThread( 6813): Failed to find provider info for com.lge.lgaccount.provider
W/LG Account v2.2( 6813): No ProfileInfo entries
I/LG Account v2.2( 6813): isEnabled: false
I/Feature ( 6813): [Lifetracker]ver: 4.21.112(40211120)
I/Feature ( 6813): [Lifetracker]Country: EU
I/Feature ( 6813): [Lifetracker]Operator: OPEN
I/Feature ( 6813): [Lifetracker]Ranking support: false
I/Feature ( 6813): [Lifetracker]Comfort support: false
I/Feature ( 6813): [Lifetracker]Accessory: true
I/Feature ( 6813): [Lifetracker]Health device: true
I/Feature ( 6813): [Lifetracker]Extra Pedometer: false
I/Feature ( 6813): [Lifetracker]Blood glucose device: false
I/Feature ( 6813): [Lifetracker]Device Number: 3
,I/wpa_supplicant( 2623): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
W/wpa_supplicant( 2623): USIM:  scard_deinit function
,D/Tethering( 1038): InitialState.processMessage what=4
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1038): handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
E/WifiMonitor( 1038): WifiMonitor notify network disconnect: c0:ff:d4:d3:aa:48 reason=3
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/ActivityManager( 1038): Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=6876 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 6214:com.google.android.apps.docs/u0a61 (adj 15): empty #17
E/WifiStateMachine( 1038):  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=81459
E/WifiStateMachine( 1038):  DefaultState NETWORK_DISCONNECTION_EVENT c0:ff:d4:d3:aa:48 nid=1 reason=3 rt=81460
E/WifiStateMachine( 1038):  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=81462  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
,E/WifiStateMachine( 1038):  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=81464  SSID: NG700 BSSID: c0:ff:d4:d3:aa:48 nid: 0 state: DISCONNECTED
W/ContextImpl( 6838): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,D/AndroidRuntime( 6866): 
D/AndroidRuntime( 6866): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 6866): CheckJNI is OFF
D/Tethering( 1038): sendTetherStateChangedBroadcast 0, 0, 0
,W/libprocessgroup( 1038): failed to open /acct/uid_10061/pid_6214/cgroup.procs: No such file or directory
,E/WifiStateMachine( 1038):  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
,E/WifiStateMachine( 1038):  DefaultState CMD_TETHER_STATE_CHANGE 0 0
V/BluetoothPbapReceiver( 3787): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 3787): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 3787): ***********state = 13
I/wpa_supplicant( 2623): wlan0: CTRL-EVENT-TERMINATING 
V/BluetoothPbapReceiver( 3787): ***********Calling start service!!!! with action = null
,V/BluetoothPbapService( 3787): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 3787): state: 13
V/BluetoothPbapService( 3787): Pbap Service closeService in
D/WifiMonitor( 1038): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
E/WifiMonitor( 1038): WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
E/WifiStateMachine( 1038):  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
D/WifiMonitor( 1038): Disconnecting from the supplicant, no more events
D/BluetoothManagerService( 1038): Message: 20
D/BluetoothManagerService( 1038): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d095314:true
V/BluetoothPbapService( 3787): successfully stopped pbap service
V/BluetoothPbapService( 3787): Pbap Service closeService out
V/BluetoothPbapService( 3787): Pbap Service onDestroy
V/BluetoothPbapService( 3787): Pbap Service closeService in
V/BluetoothPbapService( 3787): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 3787): [BTUI] cleanup
D/WifiOffDelayIfNotUsed( 1038): stopMonitoring
E/WifiStateMachine( 1038): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine( 1038): useWiFiOffloading() : false
E/WifiStateMachine( 1038): CONFIG_LGE_WLAN_PATH : true
W/ResourcesManager( 6876): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/StatusBar.NetworkController( 1474): refreshViews: Data not connected!! Set no data type icon / Roaming
D/WfdsService( 1978): Supplicant Connection state is changed : false
D/WfdsService( 1978): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1978): Set the WFDS Monitor: false
D/WfdsMonitor( 1978): WFDS Monitor is stopped
V/WfdStateTracker( 1978): WfdStateTracker handleDirectStateChangedEvent: 0
W/Settings( 6716): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiServerServiceExt( 1038): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServerServiceExt( 1038): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt( 1038): batteryPsActivateMsgHandler : this is not treated
W/Settings( 1838): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/BluetoothManagerService( 1038): Message: 30
,D/BluetoothManagerService( 1038): Message: 30
D/LocalBluetoothProfileManager( 6838): Adding local MAP profile
D/BluetoothMap( 6838): Create BluetoothMap proxy object
D/BluetoothManagerService( 1038): Message: 30
,D/PluginManager( 6876): init()
D/BluetoothManagerService( 1038): Message: 30
D/LocalBluetoothProfileManager( 6838): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 6838):  get() - isFeatureLoaded : false
D/LGBluetoothUserBindClient( 6838): [BTUI] initUserBindClient
,W/ContextImpl( 6838): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,D/DockEventReceiver( 6838): finishStartingService: stopping service
,D/BluetoothInputDevice( 6838): Proxy object connected
D/HidProfile( 6838): Bluetooth service connected
,D/BluetoothPan( 6838): BluetoothPAN Proxy object connected
D/PanProfile( 6838): Bluetooth service connected
D/BluetoothMap( 6838): Proxy object connected
D/MapProfile( 6838): Bluetooth service connected
D/BluetoothMap( 6838): getConnectedDevices()
D/BluetoothMap( 6838): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 6838): [BTUI] onServiceConnected
D/LGBluetoothAuthorization( 6838): [BTUI] cancel All Notification
D/BluetoothPermissionRequest( 6838): onReceive
D/AndroidRuntime( 6866): Calling main entry com.android.commands.pm.Pm
,D/LGBluetoothAuthorization( 6838): [BTUI] cancel All Notification
D/LGBluetoothResetSettingReceiver( 6838): return without doing reset settings.
I/ActivityManager( 1038): Killing 6367:com.lge.eula/1000 (adj 15): empty #17
W/PackageSettings( 1038): Skipping PackageSetting{442aa99 com.test.thalitest/10311} due to missing metadata
,V/BluetoothOppReceiver( 3787): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_6367/cgroup.procs: No such file or directory
D/BluetoothOppNotification( 3787): [BTUI] cancel opp incoming file confirm notification
D/BluetoothOppNotification( 3787): [BTUI] cancel opp active transfer file notification
I/ActivityManager( 1038): Force stopping com.example.hello appid=10319 user=0: pkg removed
I/ActivityManager( 1038): Killing 6461:com.example.hello/u0a319 (adj 0): stop com.example.hello
I/WindowState( 1038): WIN DEATH: Window{1bf72fc5 u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService( 1038): Client connection lost with reason: 4
,D/InputDispatcher( 1038): Window went away: Window{1bf72fc5 u0 com.example.hello/com.example.hello.MainActivity}
,E/libprocessgroup( 1038): failed to kill 1 processes for processgroup 6461
,I/ActivityManager( 1038):   Force finishing activity ActivityRecord{624d898 u0 com.example.hello/.MainActivity t4}
W/ExternalStrings( 6876): load override strings
W/ExternalStrings( 6876): java.lang.RuntimeException: Unexpected tag, got eat-comment
W/ExternalStrings( 6876): 	at com.mcafee.plugin.af.a(Unknown Source)
W/ExternalStrings( 6876): 	at com.mcafee.plugin.ac.b(Unknown Source)
W/ExternalStrings( 6876): 	at com.mcafee.plugin.ak.d(Unknown Source)
W/ExternalStrings( 6876): 	at com.mcafee.plugin.ak.a(Unknown Source)
W/ExternalStrings( 6876): 	at com.mcafee.app.s.getClassLoader(Unknown Source)
W/ExternalStrings( 6876): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
W/ExternalStrings( 6876): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
W/ExternalStrings( 6876): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
W/ExternalStrings( 6876): 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
W/ExternalStrings( 6876): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
W/ExternalStrings( 6876): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ExternalStrings( 6876): 	at android.os.Looper.loop(Looper.java:135)
W/ExternalStrings( 6876): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/ExternalStrings( 6876): 	at java.lang.reflect.Method.invoke(Native Method)
W/ExternalStrings( 6876): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ExternalStrings( 6876): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/ExternalStrings( 6876): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
D/StatusProvider( 6876): onCreate
,E/GBMv2   (  336): DFP En is all cleared set to be enabled
,D/bt_hci_bdroid( 3787): cleanup
W/bt-btif ( 3787): ag scb idx 1 not allocated
E/bt-btif ( 3787): BTA AG is already disabled, ignoring ...
I/bt_lpm  ( 3787): LPM is already off!!!
W/bt-l2cap( 3787): L2CAP - L2CA_Deregister() called for PSM: 0x0019
I/bt_userial_mct( 3787): exiting userial_read_thread
D/bt_userial_mct( 3787): Leaving userial_evt_read_thread()
W/bt-l2cap( 3787): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3787): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3787): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3787): L2CAP - L2CA_Deregister() called for PSM: 0x001b
D/bt_userial_mct( 3787): userial_close_reader Joined userial reader thread: 0
W/bt-l2cap( 3787): L2CAP - PSM: 0x001b not found for deregistration
I/bt_vendor( 3787): hw_epilog_process
W/bt-l2cap( 3787): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3787): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3787): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3787): L2CAP - PSM: 0x0017 not found for deregistration
D/bt_hci_bdroid( 3787): cleanup Finalizing cleanup
D/bt_userial_mct( 3787): userial_close
E/bt_userial_mct( 3787): pthread_join() FAILED result:3
W/bt-l2cap( 3787): L2CAP - L2CA_Deregister() called for PSM: 0x001b
I/bt_vendor( 3787): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
W/bt-l2cap( 3787): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3787): L2CAP - L2CA_Deregister() called for PSM: 0x0019
W/bt-l2cap( 3787): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3787): L2CAP - L2CA_Deregister() called for PSM: 0x0017
W/bt-l2cap( 3787): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3787): L2CAP - L2CA_Deregister() called for PSM: 0x001b
W/bt-l2cap( 3787): L2CAP - PSM: 0x001b not found for deregistration
E/bt-btif ( 3787): bta_gattc_deregister Deregister Failedm unknown client cif
I/ActivityManager( 1038): Force stopping com.example.hello appid=10319 user=-1: uninstall pkg
I/ActivityManager( 1038):   Force finishing activity ActivityRecord{624d898 u0 com.example.hello/.MainActivity t4 f}
W/ActivityManager( 1038): Duplicate finish request for ActivityRecord{624d898 u0 com.example.hello/.MainActivity t4 f}
W/ActivityManager( 1038): Spurious death for ProcessRecord{381abd4f 6461:com.example.hello/u0a319}, curProc for 6461: null
,D/SplitWindowPolicy( 1978): updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
,D/SplitWindowPolicy( 1978): topRunningActivity=ActivityInfo{f8cc9b8 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
D/SplitWindowPolicy( 1978): updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
D/SplitWindowPolicy( 1978): topRunningActivity=ActivityInfo{b82391 co.....Launcher}, taskId=3, activityType=1, bIsSplit=false
I/[LGHome]EVENT( 2095): [Launcher.java:5338:onStart()]onStart
,I/[LGHome]EVENT( 2095): [Launcher.java:903:onResume()]onResume
V/BluetoothFtpReceiver( 3787): BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpReceiver( 3787): BluetoothFtpReceiver Start Service
I/[LGHome]EVENT( 2095): [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 2095): [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/KeyguardModel( 1474): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,D/LIA_Service_RemotePackageHandler( 2051): onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.example.hello
D/LIA_MrGDBLogger_PackageInfoDetector( 3720): [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.example.hello
E/LGBluetoothAvrcpQcomAdapter( 3787): [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
D/LGBluetoothAvrcpQcomAdapter( 3787): [BTUI] [+] updateMediaPlayerInfo
I/InputReader( 1038): Reconfiguring input devices.  changes=0x00000010
,I/art     ( 4571): Explicit concurrent mark sweep GC freed 17456(977KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 669us total 76.886ms
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,V/Signer  ( 6876): override build config not found
D/Signer  ( 6876): value of property debug is false
W/GeofencerStateMachine( 1838): Ignoring removeGeofence because network location is disabled.
,W/System.err( 4518): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
I/[LGHome]GBoardWebView( 2095): [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
D/ActionManagerService( 1930): notifyUserLog: 1000003
,W/System.err( 4518): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 4518): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 4518): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
D/LIA_Informant_ActionManagerMessageHandler( 3720): handleMessage: what(1000) actionID(0x1000003)
W/System.err( 4518): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4518): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4518): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4518): 	at android.app.ActivityThread.main(ActivityThread.java:5274)
W/System.err( 4518): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4518): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4518): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
W/System.err( 4518): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
I/[LGHome]LGActivityUtil( 2095): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/administrator( 1038): Handling package changes for user 0
,I/[LGHome]EVENT( 2095): [Launcher.java:1056:onResume()]onResume end
I/[LGHome]EVENT( 2095): [Launcher.java:1114:onPause()]onPause
I/[SystemUI]QSlideListController( 1474): onReceive = android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1474): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1474): createShortcutInfo...
I/[LGHome]GBoardWebView( 2095): [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
D/ActionManagerService( 1930): notifyUserLog: 1000004
D/LIA_Informant_ActionManagerMessageHandler( 3720): handleMessage: what(1000) actionID(0x1000004)
,V/BoardContentProvider( 3720): query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
I/GBoardWebViewUtils( 2095): checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
I/GBoardWebViewUtils( 2095): , create_time: 1430558575574
I/GBoardWebViewUtils( 2095): , expire_time: 0
I/GBoardWebViewUtils( 2095): , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
I/GBoardWebViewUtils( 2095): , category: com.lge.intent.category.gboard.MYWELLNESS
I/GBoardWebViewUtils( 2095): , display: false
I/GBoardWebViewUtils( 2095): , animation: false }
I/GBoardWebViewUtils( 2095): checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
I/GBoardWebViewUtils( 2095): , create_time: 1430558575600
I/GBoardWebViewUtils( 2095): , expire_time: 0
I/GBoardWebViewUtils( 2095): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
I/GBoardWebViewUtils( 2095): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2095): , display: false
I/GBoardWebViewUtils( 2095): , animation: false }
I/GBoardWebViewUtils( 2095): checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1452175674810
I/GBoardWebViewUtils( 2095): , create_time: 1452175675684
I/GBoardWebViewUtils( 2095): , expire_time: 0
I/GBoardWebViewUtils( 2095): , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/1/userguide.html?id=guide_1111111111116_1452175674810&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
I/GBoardWebViewUtils( 2095): , category: com.lge.intent.category.gboard.DOYOUKNOW
I/GBoardWebViewUtils( 2095): , display: false
I/GBoardWebViewUtils( 2095): , animation: false }
D/KeyguardModel( 1474): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1474): createShortcutInfo...
D/WallpaperManager( 2095): suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
I/SystemUI[Framework]( 1038): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8000, pkg=com.android.systemui
,W/ResourcesManager( 1474): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1474): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1474): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1474): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1474): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1474): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/PhoneWindowManagerEx( 1038): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx( 1038): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx( 1038): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
W/ResourceType( 1474): No package identifier when getting value for resource number 0x00000000
I/SystemUI[Framework]( 1038): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3d8c3edd,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework]( 1038): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/PackageManager( 1474): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/SplitUIManager( 1890): split_name #11 / not available #0
D/SplitUIService( 1890): removed split : 
D/LGMDMWrapper( 6876): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
D/KeyguardModel( 1474): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1474): createShortcutInfo...
D/LGMDMWrapper( 6876): Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
D/LGMDMWrapper( 6876): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
D/LGMDMWrapper( 6876): Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
D/LGMDMWrapper( 6876): Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
D/LGMDMWrapper( 6876): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
D/LGMDMWrapper( 6876): Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
D/LGMDMWrapper( 6876): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
D/LGMDMWrapper( 6876): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
D/LGMDMWrapper( 6876): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
D/LGMDMWrapper( 6876): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
D/LGMDMWrapper( 6876): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
D/LGMDMWrapper( 6876): Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
,D/bt_hci_bdroid( 3787): set_power 0
I/bt_vendor( 3787): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 3787): bluetooth satus is on
I/bt_vendor( 3787): bt-vendor : resetting BT status
I/bt_vendor( 3787): Starting hciattach daemon
I/bt_vendor( 3787): try to set false
I/bt_vendor( 3787): Starting hciattach daemon
I/bt_vendor( 3787): try to set false
I/bt_vendor( 3787): cleanup
I/GKI_LINUX( 3787): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 3787): GKI_exit_task 0 done
I/GKI_LINUX( 3787): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3787): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
I/[LGHome]EVENT( 2095): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
V/LGMDMManager( 6876): Create singleton instance
I/[LGHome]GBoardWebView( 2095): [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
W/ResourcesManager( 1474): Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
W/ResourcesManager( 1474): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1474): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1474): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/GAV2    ( 6661): Thread[GAThread,5,main]: No campaign data found.
D/BluetoothAdapterState( 3787): Stopping profile services that were post enabled
,D/KeyguardModel( 1474): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1474): createShortcutInfo...
W/ResourcesManager( 1474): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1474): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1474): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager( 1474): Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,W/ResourceType( 1474): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1474): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1474): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1474): createShortcutInfo...
D/KeyguardModel( 1474): handleShortcutListChanged...
D/KeyguardModel( 1474): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1474): createShortcutInfo...
,D/KeyguardModel( 1474): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/SplitUIManager( 1890): split_name #11 / not available #0
D/KeyguardModel( 1474): createShortcutInfo...
I/SplitUIService( 1890): split app #11
W/ResourceType( 1474): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1474): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1474): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1474): createShortcutInfo...
,W/ResourceType( 1474): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1474): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]EVENT( 2095): [Launcher.java:5349:onStop()]onStop
,D/KeyguardModel( 1474): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1474): createShortcutInfo...
W/ResourceType( 1474): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1474): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1474): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1474): createShortcutInfo...
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
V/SIM_STK ( 1038): Menu title from STK is T-Mobile
,D/LGMDMWrapper( 6876): LG MDM library v4.0.0 is available on this device.
D/KeyguardModel( 1474): handleShortcutListChanged...
I/art     ( 2095): Background partial concurrent mark sweep GC freed 6323(268KB) AllocSpace objects, 5(19MB) LOS objects, 34% free, 59MB/91MB, paused 10.618ms total 39.213ms
D/PostponalbeReceiver( 6876): WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,W/ContextImpl( 6876): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
I/[LGHome]Launcher.Model( 2095): [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,V/SIM_STK ( 1038): Menu title from STK is T-Mobile
I/[LGHome]Launcher( 2095): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2095): [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 2095): [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 2095): [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 2095): [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,I/ActivityManager( 1038): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6923 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/ActivityManager( 1038): Killing 5895:com.lge.bnr/1000 (adj 15): empty #17
I/NotificationService( 1038): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,D/BackupManagerService( 1038): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService( 1038): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 2095): [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 2095): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2095): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 2095): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 2095): [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 2095): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2095): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/[Concierge]WidgetView( 2095): ConciergeWidgetView is instantiated. sIsWidgetAttached : true
W/ResourcesManager( 1038): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType( 1038): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/art     ( 1038): Explicit concurrent mark sweep GC freed 52756(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 44MB/66MB, paused 1.731ms total 468.653ms
W/ActivityThread( 6876): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/ActivityManager( 1038): getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,D/LGBluetoothAvrcpQcomAdapter( 3787): [BTUI] installed app name: Music
D/LGBluetoothAvrcpQcomAdapter( 3787): [BTUI] installed app name: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3787): [BTUI] === MediaPlayerInfo (playerId:0) ===
D/LGBluetoothAvrcpQcomAdapter( 3787): [BTUI]          displayName: Music
D/LGBluetoothAvrcpQcomAdapter( 3787): [BTUI]          packageName: com.lge.music
D/LGBluetoothAvrcpQcomAdapter( 3787): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3787): [BTUI] === MediaPlayerInfo (playerId:1) ===
D/LGBluetoothAvrcpQcomAdapter( 3787): [BTUI]          displayName: Google Play Music
D/LGBluetoothAvrcpQcomAdapter( 3787): [BTUI]          packageName: com.google.android.music
D/LGBluetoothAvrcpQcomAdapter( 3787): [BTUI]          playState: 2 (PAUSED)
D/LGBluetoothAvrcpQcomAdapter( 3787): [BTUI] [-] updateMediaPlayerInfo
V/BluetoothFtpService( 3787): Ftp Service onStartCommand
V/BluetoothFtpService( 3787): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothFtpService( 3787): Ftp Service closeService
E/BluetoothFtpService:RfcommSocketAcceptThread( 3787): Shutdown
D/PhoneStatusBar( 1474): setSystemUiVisibility vis=8000 mask=ffffffff oldVal=0 newVal=8000 diff=8000
I/[SystemUI]NavigationThemeResource( 1474): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1474):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1474): , Keyguard show=false, IME shown=false, Panel expanded=false
D/AndroidRuntime( 6866): Shutting down VM
W/libprocessgroup( 1038): failed to open /acct/uid_1000/pid_5895/cgroup.procs: No such file or directory
,D/[Concierge]Service( 2625): onStartCommand(). Type : 8
D/[Concierge]Service( 2625): Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
D/[Concierge]Service( 2625): Update widget ID : 11
D/[Concierge]WidgetView( 2095): change position of spinner
V/BluetoothFtpService( 3787): successfully stopped ftp service
V/BluetoothSapReceiver( 3787): [BTUI] checkServiceStart
,V/BluetoothSapReceiver( 3787): [BTUI] region:EU country:EU
V/BluetoothSapReceiver( 3787): SapReceiver onReceive 
V/BluetoothSapReceiver( 3787): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 3787):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 3787): Calling SAP service start service with action = null
D/HeadsetService( 3787): Received stop request...Stopping profile...
I/Timeline( 1038): Timeline: Activity_windows_visible id: ActivityRecord{2fd851b u0 com.lge.launcher2/.Launcher t3} time:82611
I/LGBluetoothHfpAdapter( 3787): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 3787): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3787): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33592781
D/HeadsetStateMachine( 3787): Exit Disconnected: -1
D/TaskPersister( 1038): removeObsoleteFile: deleting file=4_task.xml
D/BluetoothHeadset( 1873): Proxy object disconnected
D/BluetoothHeadset( 1873): Proxy object disconnected
D/BluetoothHeadset( 1873): Proxy object disconnected
D/A2dpService( 3787): Received stop request...Stopping profile...
D/A2dpStateMachine( 3787): Exit Disconnected: -1
D/LGBluetoothAvrcpQcomAdapter( 3787): [BTUI] cleanup
,D/BluetoothHeadset( 1038): Proxy object disconnected
D/AudioService( 1038): onServiceDisconnected: Bluetooth profile: 1
I/PCSuite ( 6923): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6923): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6923): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager( 1038): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6950 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
I/[Concierge]WidgetView( 2095): initWebView(). Time : 1452528656603
D/[Concierge]Service( 2625): onStartCommand(). Type : 0
D/LGBluetoothA2dpAdapter( 3787): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 3787): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 3787): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33592781
,D/BluetoothA2dp( 1038): Proxy object disconnected
D/AudioService( 1038): onServiceDisconnected: Bluetooth profile: 2
D/HidService( 3787): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3787): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33592781
D/HealthService( 3787): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3787): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33592781
D/PanService( 3787): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3787): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33592781
D/BtGatt.DebugUtils( 3787): handleDebugAction() action=null
D/BtGatt.GattService( 3787): Received stop request...Stopping profile...
D/BtGatt.GattService( 3787): stop()
D/BtGatt.AdvertiseManager( 3787): advertise clients cleared
D/BluetoothAdapterService( 3787): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33592781
D/BluetoothMapService( 3787): Received stop request...Stopping profile...
D/BluetoothMapService( 3787): stop()
,D/BluetoothMapEmailAppObserver( 3787): deinitObservers()
D/BluetoothMapEmailAppObserver( 3787): removeReceiver()
D/BluetoothAdapterService( 3787): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@33592781
I/art     (  340): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 421us total 19.532ms
V/BluetoothFtpService( 3787): Ftp Service onDestroy
V/BluetoothFtpService( 3787): Ftp Service closeService
V/BluetoothSapService( 3787): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 3787): state: 13
V/BluetoothSapService( 3787): Stopping SAP server process
V/BluetoothSapService( 3787): Sap Service closeSapService in
V/BluetoothSapService( 3787): Close listen Socket : 
V/BluetoothSapService( 3787): Close rfcomm Socket : 
V/BluetoothSapService( 3787): Close sapd  Socket : 
V/BluetoothSapService( 3787): Sap Service closeSapService out
D/HeadsetStateMachine( 3787): Unbinding service...
,D/HeadsetPhoneState( 3787): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3787): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 3787): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 3787): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 3787): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 3787): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 3787): [BTUI] LGBluetoothHfpAdapter cleanup
I/BluetoothA2dpServiceJni( 3787): cleanupNative
I/GKI_LINUX( 3787): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3787): GKI_exit_task 2 done
I/GKI_LINUX( 3787): GKI_shutdown(): task [A2DP-MEDIA] terminated
W/BluetoothHidServiceJni( 3787): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 3787): Cleaning up Bluetooth GID callback object
W/BluetoothHealthServiceJni( 3787): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3787): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 3787): Cleaning up Bluetooth Health object
W/BluetoothPanServiceJni( 3787): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 3787): Cleaning up Bluetooth PAN callback object
V/BluetoothMapService( 3787): Handler(): got msg=4
D/BluetoothMapService( 3787): MAP Service closeService in
D/LGBluetoothMapAdapter( 3787): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3787): MAP Service closeService out
D/BluetoothMapService( 3787): cleanup()
D/BluetoothMapService( 3787): MAP Service closeService in
D/LGBluetoothMapAdapter( 3787): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 3787): MAP Service closeService out
D/BluetoothAdapterState( 3787): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3787): Setting state to 10
I/BluetoothAdapterState( 3787): Bluetooth adapter state changed: 13-> 10
V/BluetoothSapService( 3787): Sap Service onDestroy
V/BluetoothSapService( 3787): Sap Service closeSapService in
V/BluetoothSapService( 3787): Close listen Socket : 
V/BluetoothSapService( 3787): Close rfcomm Socket : 
V/BluetoothSapService( 3787): Close sapd  Socket : 
D/BluetoothManagerService( 1038): Message: 60
D/BluetoothManagerService( 1038): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService( 1038): Broadcasting onBluetoothStateChange(false) to 9 receivers.
D/BluetoothHeadset( 1038): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 3787): Entering OffState
V/BluetoothSapService( 3787): Sap Service closeSapService out
D/BluetoothHeadset( 1873): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1873): onBluetoothStateChange: up=false
D/BluetoothPbap( 6838): onBluetoothStateChange: up=false
D/BluetoothPan( 6838): onBluetoothStateChange on: false
,D/BluetoothA2dp( 1038): onBluetoothStateChange: up=false
I/[Concierge]WebView( 2095): Return exist ConciergeWebView. Reuse : 565568346
D/BluetoothHeadset( 1873): onBluetoothStateChange: up=false
D/[Concierge]WidgetView( 2095): State Change : null -> AccInBeforeState
I/[LgeWidgetLib]LgeAppWidgetHostView( 2095): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
D/BluetoothMap( 6838): onBluetoothStateChange: up=false
V/WiFiOffLoadBroadcast( 6838): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/[LgeWidgetLib]ExtViewHost( 2095): [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@219386b3
I/[LGHome]EVENT( 2095): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
D/BluetoothInputDevice( 6838): onBluetoothStateChange: up=false
D/BluetoothManagerService( 1038): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService( 1038): Broadcasting onBluetoothServiceDown() to 7 receivers.
I/art     (  340): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 409us total 18.582ms
D/BluetoothManagerService( 1038): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService( 1038): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService( 1038): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@d054481 mBinding = false
I/[LGHome]Launcher.Model( 2095): [LauncherModel.java:2256:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 2095): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
D/BluetoothManagerService( 1038): Sending unbind request.
D/BluetoothManagerService( 1038): Bluetooth State Change Intent: 13 -> 10
,D/LGBluetoothAPIService( 1978): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
I/[SystemUI]BluetoothHandler( 1474): Receive : BluetoothAdapter.ACTION_STATE_CHANGED
D/LGBluetoothAPIService( 1978): Message: 2
D/LGBluetoothAPIService( 1978): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3c6382f6 mBinding = false
D/LGBluetoothAPIService( 1978): Sending unbind request.
I/GKI_LINUX( 3787): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 3787): GKI_exit_task 1 done
I/GKI_LINUX( 3787): GKI_shutdown(): task [BTIF] terminated
I/BluetoothServiceJni( 3787): cleanupNative: return from cleanup
I/art     ( 3787): --- WEIRD: removing null entry 246
W/art     ( 3787): JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
W/LGBluetoothServiceJni( 3787): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 3787): [BTUI] unregister observer for LG device name DB
,I/[LGHome]EVENT( 2095): [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/art     ( 3787): System.exit called, status: 0
I/AndroidRuntime( 3787): VM exiting with result code 0, cleanup skipped.
D/[Concierge]WidgetView( 2095): isWidgetUpdateSkippable ? true
I/[LGHome]EVENT( 2095): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/[Concierge]WidgetBroadcastReceiver( 2095): New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
I/art     (  340): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 400us total 17.772ms
D/BluetoothAdapter( 1474): 376901251: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1474): 376901251: getState() :  mService = null. Returning STATE_OFF
W/[Concierge]WidgetView( 2095): Widget kill message received. Destory myself. My : 1452528601853, New one : 1452528656603
D/[Concierge]WidgetView( 2095): Unregister all receivers
W/[Concierge]WidgetBroadcastReceiver( 2095): Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
D/LgDataFeature( 6838): LgDataFeature() Constructor: none
D/LgDataFeature( 6838): LgDataFeature() Constructor Done, null
,I/[LGHome]Launcher( 2095): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 2095): [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 2095): [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
V/AudioFlinger(  314): 3787 died, releasing its sessions
V/AudioFlinger(  314):  pid 1873 @ 0
V/AudioFlinger(  314):  pid 2211 @ 1
V/AudioFlinger(  314):  pid 3337 @ 2
V/AudioFlinger(  314):  pid 3337 @ 3
I/[LGHome]EVENT( 2095): [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 2095): [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
I/[LGHome]EVENT( 2095): [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
I/[LGHome]Launcher( 2095): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 2095): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,W/ResourcesManager( 6950): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/WiFiOffLoadBroadcast( 6838): MCCMNC not supported: null
D/LGBluetoothFeatureConfig( 6838): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 6838): [BTUI] resetProperty - success
E/LGBluetoothEventManager( 6838): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 6838): [BTUI] clear device connection state
I/[LgeWidgetLib]LgeAppWidgetHostView( 2095): [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
D/LGBluetoothUserBindClient( 6838): [BTUI] onServiceDisconnected
E/[LgeWidgetLib]LgeAppWidgetHostView( 2095): [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 2095): [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 2095): [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,I/Timeline( 2095): Timeline: Activity_idle id: android.os.BinderProxy@c76ec3b time:82806
,I/ActivityManager( 1038): Process com.android.bluetooth (pid 3787) has died
W/ActivityManager( 1038): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
I/ActivityManager( 1038): Killing 6525:com.lge.clock/u0a10 (adj 15): empty #17
,D/LgDataFeature( 6876): LgDataFeature() Constructor: none
D/LgDataFeature( 6876): LgDataFeature() Constructor Done, null
,E/SQLiteDatabase( 6876): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 6876): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6876): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6876): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.wavesecure.notification.q.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 6876): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6876): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6876): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6876): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6876): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6876): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6876): 	at com.mcafee.d.c.run(Unknown Source)
,E/SQLiteDatabase( 6876): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 6876): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6876): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6876): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.ConfigManager.b(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.ConfigManager.aq(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.MSSComponentConfig.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.wavesecure.dataStorage.WSFeatureConfig.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.wavesecure.backup.BaseBackup.b(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.wavesecure.core.WSComponent.c(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 6876): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6876): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6876): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6876): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6876): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6876): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6876): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 6876): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 6876): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQ,LiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6876): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6876): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.ConfigManager.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.MSSComponentConfig.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.wavesecure.dataStorage.WSFeatureConfig.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.wavesecure.backup.BaseBackup.b(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.wavesecure.core.WSComponent.c(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 6876): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6876): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6876): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6876): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6876): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6876): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6876): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 6876): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 6876): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6876): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6876): 	at android.content.ContextWrapper.openOrCre,ateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.ConfigManager.e(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.ConfigManager.d(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.wavesecure.dataStorage.WSFeatureConfig.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.wavesecure.backup.BaseBackup.b(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.wavesecure.core.WSComponent.c(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 6876): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6876): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6876): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6876): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6876): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6876): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6876): 	at com.mcafee.d.c.run(Unknown Source)
E/SQLiteDatabase( 6876): Failed to open database '/data/data/com.wsandroid.suite.lge/databases/WSAndroid'.
E/SQLiteDatabase( 6876): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 6876): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
E/SQLiteDatabase( 6876): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 6876): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.b.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.a.m(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.a.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.a.b(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.ConfigManager.g(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.ConfigManager.c(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.ConfigManager.N(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.wsstorage.ConfigManager.d(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.wavesecure.dataStorage.WSFeatureConfig.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.wavesecure.backup.BaseBackup.b(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.wavesecure.core.WSComponent.c(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.wavesecure.core.WSComponent.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.c.b.b(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.framework.b.a(Unknown Source)
E/SQLiteDatabase( 6876): 	at com.mcafee.app.t.run(Unknown Source)
E/SQLiteDatabase( 6876): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 6876): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 6876): 	at com.mcafee.d.f.run(Unknown Source)
E/SQLiteDatabase( 6876): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 6876): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 6876): 	at java.lang.Thread.run(Thread.java:818)
E/SQLiteDatabase( 6876): 	at com.mcafee.d.c.run(Unknown Source)
D/AuthorizationBluetoothService( 2140): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/libprocessgroup( 1038): failed to open /acct/uid_10010/pid_6525/cgroup.procs: No such file or directory
W/ContextImpl( 6838): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
W/ContextImpl( 6876): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,I/ActivityManager( 1038): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6977 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a

```
