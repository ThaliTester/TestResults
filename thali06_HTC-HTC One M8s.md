#### Test 625481247d7767b_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system,
03-15 15:04:03.501   988  1138 D PMS     : acquireWL(a4b35fc): PARTIAL_WAKE_LOCK  *alarm* 0x1 988 1000 WorkSource{1000}
03-15 15:04:03.501   988  1138 V AlarmManager: sending alarm PendingIntent{2e0c9208: PendingIntentRecord{2a08cda1 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1458050608889, Int=0
03-15 15:04:03.501   988   988 D PMS     : acquireWL(960f485): PARTIAL_WAKE_LOCK  *backup* 0x1 988 1000 null
03-15 15:04:03.501   988  1138 V AlarmManager: sending alarm PendingIntent{1fc96acd: PendingIntentRecord{edb1f82 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=199121, Int=0
03-15 15:04:03.501   988  1138 V AlarmManager: sending alarm PendingIntent{2ca6d2da: PendingIntentRecord{5e2630b android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=202631, Int=0
03-15 15:04:03.511   988  1138 V AlarmManager: sending alarm PendingIntent{2113b5e8: PendingIntentRecord{30415401 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=189949, Int=0
03-15 15:04:03.511   988  1163 W BackupManagerService: Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
03-15 15:04:03.511   988  1163 E BackupManagerService: Requested init for com.google.android.gms.backup.BackupTransportService but not found
03-15 15:04:03.511   988  1163 D PMS     : releaseWL(960f485): PARTIAL_WAKE_LOCK  *backup* 0x1 null
03-15 15:04:03.531   988  2055 D PMS     : acquireWL(2d2f42a6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
03-15 15:04:03.541   988   988 D PMS     : releaseWL(a4b35fc): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
--------- beginning of main
03-15 15:04:03.541  1221  2431 D WeatherUtility: Weather sync is On
03-15 15:04:03.541  1221  2431 W WeatherTimeKeeper: [refreshWeatherData] no weather data
03-15 15:04:03.561   988  1393 D PMS     : acquireWL(15d224e7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
03-15 15:04:03.581   988  2055 D PMS     : releaseWL(2d2f42a6): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-15 15:04:03.591  1962  1962 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-15 15:04:03.611   988  1013 D PMS     : releaseWL(15d224e7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-15 15:04:03.611   988  1602 D PMS     : acquireWL(1938239): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
03-15 15:04:03.621   988  2055 D PMS     : releaseWL(1938239): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-15 15:04:03.621   988  1158 D PMS     : acquireWL(e92007e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
03-15 15:04:03.631   988  1624 D PMS     : releaseWL(e92007e): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-15 15:04:03.631   988  1597 D PMS     : acquireWL(fc4c9df): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
03-15 15:04:03.681   988  1602 D PMS     : acquireWL(2dc6162c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
03-15 15:04:03.731   988  1380 D PMS     : acquireWL(2349a68a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
03-15 15:04:03.741   988  2055 D PMS     : releaseWL(fc4c9df): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-15 15:04:03.751  1962  6656 I VacuumService: Vacuum at: now=1458050643764 tag=VacuumService
03-15 15:04:03.771  1962  6657 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
03-15 15:04:03.771   988  1598 D PMS     : releaseWL(2dc6162c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-15 15:04:03.781   988  1587 D PMS     : acquireWL(12946918): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
03-15 15:04:03.781  6653  6659 E cutils-trace: Error opening trace file: Permission denied (13)
03-15 15:04:03.801  1962  6657 W Uploader: No account for auth token provided
03-15 15:04:03.801   988  2055 D PMS     : releaseWL(12946918): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-15 15:04:03.811   988  1380 D PMS     : acquireWL(1c63f71): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
03-15 15:04:03.821   988  1393 D PMS     : releaseWL(1c63f71): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-15 15:04:03.821  1962  6657 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
03-15 15:04:03.831  1962  6657 D libc    : [NET] android_getaddrinfofornet-, err=8
03-15 15:04:03.831  1962  6657 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
03-15 15:04:03.831  1962  6657 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
03-15 15:04:03.831  1962  6657 D libc    : [NET] android_getaddrinfo_proxy+
03-15 15:04:03.831  1962  6657 D libc    : [NET] android_getaddrinfo_proxy get netid:0
03-15 15:04:03.831   394  6673 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
03-15 15:04:03.831   394  6673 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
03-15 15:04:03.881  6653  6653 D CustomizationManager: ====startRecUseTime====
03-15 15:04:03.881  6653  6653 D htc.customization.log.level:  is 
03-15 15:04:03.881  6653  6653 W CustomizationLogLevel: Level value is invalid, use default level 2
03-15 15:04:03.961  6653  6653 D CustomizationManager:  Read ACC file spent 0.044 (s)
03-15 15:04:03.961  6653  6653 D CIDMapFileReader: Parsing tag item name = HTC__001
03-15 15:04:03.961  6653  6653 D CIDMapFileReader: Parsing tag item name = HTC__102
03-15 15:04:03.961  6653  6653 D CIDMapFileReader: Parsing tag item name = HTC__Y13
03-15 15:04:03.961  6653  6653 D CIDMapFileReader: Parsing tag item name = HTC__032
03-15 15:04:03.961  6653  6653 D CIDMapFileReader: Parsing tag item name = HTC__M27
03-15 15:04:03.961  6653  6653 D CIDMapFileReader: Parsing tag item name = HTC__002
03-15 15:04:03.961  6653  6653 D CIDMapFileReader: Parsing tag item name = HTC__031
03-15 15:04:03.961  6653  6653 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
03-15 15:04:03.961  6653  6653 I CustomizationCIDLoader: Parsing tag category name = system
03-15 15:04:03.961  6653  6653 I CustomizationCIDLoader: Parsing tag category name = application
03-15 15:04:03.961  6653  6653 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: Parsing tag category name = AudioService
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: Parsing tag category name = Settings
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: Parsing tag category name = ACC
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: add string-array item, value = 42507
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: add string-array item, value = 21902
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: add string-array item, value = 23420
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: add string-array item, value = 22299
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: add string-array item, value = 24002
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: add string-array item, value = 23210
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: add string-array item, value = 23205
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: add string-array item, value = 23806
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: add string-array item, value = 23430
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: add string-array item, value = 23408
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: add string-array item, value = 27205
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: add string-array item, value = 23205:D:0:0
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
03-15 15:04:03.971  6653  6653 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
03-15 15:04:03.971  6653  6653 D CustomizationManager:  Read CID file spent 0.092 (s)
03-15 15:04:03.971  6653  6653 D CustomizationManager:  All configurations done spent 0.092 (s)
03-15 15:04:04.021   394  6673 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
03-15 15:04:04.021   394  6673 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
03-15 15:04:04.021  1962  6657 D libc    : [NET] android_getaddrinfo_proxy-, success
03-15 15:04:04.031   988  2062 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6653 on display 0
03-15 15:04:04.041   988  1061 D PMS     : acquireHCC(18ae61ad): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 988 1000 null
03-15 15:04:04.041   988  1061 D PMS     : acquireHCC(1cd07ce2): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 988 1000 null
03-15 15:04:04.041   988  2062 W asset   : Copying FileAsset 0x5594f96410 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
03-15 15:04:04.071   988  2062 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6676 uid=10195 gids={50195, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-15 15:04:04.081   414   414 I art     : Explicit concurrent mark sweep GC freed 8674(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 241us total 17.556ms
03-15 15:04:04.091  1327  1327 D DotMatrix: [EventService]  onDisplayChanged: 0
03-15 15:04:04.091   988   988 V ActivityManager: Display changed displayId=0
03-15 15:04:04.101  1327  1327 D DotMatrix: [EventService] mbHDMIConnect: false, mCoverOn:false
03-15 15:04:04.101   414   414 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 224us total 17.373ms
03-15 15:04:04.121   414   414 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 144KB/4MB, paused 223us total 14.195ms
03-15 15:04:04.131  6676  6676 W asset   : Copying FileAsset 0xac2049a0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
03-15 15:04:04.161  1596  1596 I TrimMemoryManager: [trimMemory] 20
03-15 15:04:04.261  6676  6676 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,03-15 15:04:04.301  6676  6676 I LibraryLoader: Time to load native libraries: 9 ms (timestamps 3426-3435)
,03-15 15:04:04.301  6676  6676 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-15 15:04:04.311  1962  6657 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
03-15 15:04:04.311  1962  6657 D libc    : [NET] android_getaddrinfofornet-, err=8
,03-15 15:04:04.311  1962  6657 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
03-15 15:04:04.311  1962  6657 D libc    : [NET] android_getaddrinfofornet-, err=8
,03-15 15:04:04.321  6676  6676 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1664cc31},
03-15 15:04:04.321  6676  6676 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-15 15:04:04.321  6676  6676 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,03-15 15:04:04.341  6676  6676 I BrowserStartupController: Initializing chromium process, singleProcess=true,
03-15 15:04:04.341  6676  6676 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 15:04:04.341  6676  6676 E SysUtils: ApplicationContext is null in ApplicationStatus,
,03-15 15:04:04.391  1962  6657 W Uploader: No account for auth token provided
,03-15 15:04:04.401  6676  6676 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,03-15 15:04:04.401  6676  6676 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY),
03-15 15:04:04.401  6676  6676 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-15 15:04:04.401  6676  6676 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
03-15 15:04:04.401  6676  6676 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.01
03-15 15:04:04.401  6676  6676 I Adreno-EGL: Build Date: 03/09/15 Mon
,03-15 15:04:04.401  6676  6676 I Adreno-EGL: Local Branch: 
03-15 15:04:04.401  6676  6676 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
03-15 15:04:04.401  6676  6676 I Adreno-EGL: Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
03-15 15:04:04.401  6676  6676 I Adreno-EGL:                  d74aa161a12b9c6fc6332151
,03-15 15:04:04.451   988  1634 W System.err: java.lang.Throwable: stack dump,
,03-15 15:04:04.451   988  1634 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
03-15 15:04:04.451   988  1634 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
03-15 15:04:04.451   988  1634 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
03-15 15:04:04.451   988  1634 W System.err: ,	at android.os.Binder.execTransact(Binder.java:454)
03-15 15:04:04.451   988  1051 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
03-15 15:04:04.451   988  1051 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ff642eb:true
03-15 15:04:04.451  6676  6712 D BluetoothAdapter: 730397293: getState(). Returning 12
,03-15 15:04:04.521  1962  6657 W Uploader: No account for auth token provided,
,03-15 15:04:04.521  6676  6676 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,03-15 15:04:04.531  6676  6676 W AwContents: onDetachedFromWindow called when already detached. Ignoring,
,03-15 15:04:04.551  6676  6676 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC,
,03-15 15:04:04.551  6676  6676 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
03-15 15:04:04.551  6676  6676 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 15:04:04.601   988  1673 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
03-15 15:04:04.601  6676  6710 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-15 15:04:04.621  1962  6657 W Uploader:  no longer exists, so no auth token.,
,03-15 15:04:04.631   988  1048 D StatusBarManagerService: setSystemUiVisibility(0xc0000600)
03-15 15:04:04.631   988  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-15 15:04:04.631   988  1048 D StatusBarManagerService: hiding MENU key
,03-15 15:04:04.631   988  1048 D StatusBarManagerService: setSystemUiVisibility(0x8600)
,03-15 15:04:04.631   988  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-15 15:04:04.631   988  1048 D StatusBarManagerService: hiding MENU key
,03-15 15:04:04.651  6676  6676 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,03-15 15:04:04.731  1962  6657 W Uploader: No account for auth token provided,
,03-15 15:04:04.741  6676  6676 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@7fceb9e, mServedView=org.apache.cordova.engine.SystemWebView{10aea67f VFEDH.C. .F....I. 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@1651c64c,
03-15 15:04:04.741   988  1014 I InputMethodManagerService: Disable input method client, pid=1596
03-15 15:04:04.741   988  1014 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
03-15 15:04:04.751  1221  1221 I PhoneStatusBar: setImeWindowStatus(false,false)
,03-15 15:04:04.761  6676  6676 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection,
,03-15 15:04:04.761   988  1052 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +648ms (total +708ms)
,03-15 15:04:04.801  6676  6676 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6676,
,03-15 15:04:04.871  6676  6676 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode,
,03-15 15:04:04.951  1962  1962 I art     : Explicit concurrent mark sweep GC freed 27599(1498KB) AllocSpace objects, 7(480KB) LOS objects, 47% free, 4MB/8MB, paused 852us total 45.015ms
,03-15 15:04:04.971  1962  6657 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
03-15 15:04:04.971  1962  6657 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-15 15:04:04.971  1962  6657 I GLSUser : [GLSUser] Extracting token using key: Auth
03-15 15:04:04.971  1962  6657 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-15 15:04:04.971  6676  6726 D jxcore_app_log: JniHelper::setJavaVM(0xab0978f8), pthread_self() = -1405311496
,03-15 15:04:04.981  1962  6657 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 15:04:04.981  6676  6726 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: ,
03-15 15:04:04.981  6676  6726 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-15 15:04:04.981  6676  6726 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-15 15:04:04.981  6676  6726 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-15 15:04:04.981  6676  6726 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-15 15:04:04.981  6676  6726 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a5f950 added. We now have 1 listener(s)
03-15 15:04:04.981   988  2055 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-15 15:04:04.991  6676  6726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:F6:69:77
,03-15 15:04:04.991  6676  6726 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
,03-15 15:04:04.991  6676  6726 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
03-15 15:04:04.991  6676  6726 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-15 15:04:04.991  6676  6726 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-15 15:04:04.991  6676  6726 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: ,
03-15 15:04:04.991  6676  6726 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-15 15:04:04.991  6676  6726 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-15 15:04:04.991  6676  6726 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:F6:69:77
03-15 15:04:04.991  6676  6726 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-15 15:04:04.991  6676  6726 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
,03-15 15:04:04.991  6676  6726 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1,
,03-15 15:04:04.991  6676  6726 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-15 15:04:04.991  6676  6726 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-15 15:04:04.991  6676  6726 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-15 15:04:04.991  6676  6726 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24842d6f added. We now have 1 listener(s)
03-15 15:04:05.001   988  1150 D WifiService: New client listening to asynchronous messages
03-15 15:04:04.991  6676  6726 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
03-15 15:04:05.001   988   988 E WifiTrafficPoller: ADD_CLIENT: 8
,03-15 15:04:05.001  6676  6726 D BluetoothAdapter: 730397293: getState(). Returning 12
03-15 15:04:05.001  6676  6726 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
03-15 15:04:05.001  1962  6657 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
03-15 15:04:05.001  1962  6657 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-15 15:04:05.001  1962  6657 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-15 15:04:05.001  1962  6657 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-15 15:04:05.001  1962  6657 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-15 15:04:05.001  1962  6657 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-15 15:04:05.001  1962  6657 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-15 15:04:05.001  1962  6657 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-15 15:04:05.001  1962  6657 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-15 15:04:05.001  1962  6657 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-15 15:04:05.001  1962  6657 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-15 15:04:05.001  1962  6657 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-15 15:04:05.001  1962  6657 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
03-15 15:04:05.001  1327  1394 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
03-15 15:04:05.001  1327  1394 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
03-15 15:04:05.001  6676  6726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-15 15:04:05.001  6676  6726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-15 15:04:05.001  6676  6726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-15 15:04:05.001  6676  6726 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
03-15 15:04:05.011  1221  1221 I RemoteViews: reapply : com.google.android.gms 2 40
03-15 15:04:05.011  6676  6726 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-15 15:04:05.011   988  1604 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
03-15 15:04:05.011  6676  6726 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:F6:69:77
,03-15 15:04:05.011  6676  6726 D BluetoothAdapter: 730397293: getState(). Returning 12
,03-15 15:04:05.011  6676  6726 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-15 15:04:05.011  6676  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-15 15:04:05.011  6676  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-15 15:04:05.011  6676  6726 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-15 15:04:05.011  6676  6726 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-15 15:04:05.011  6676  6726 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-15 15:04:05.011  6676  6726 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-15 15:04:05.011  6676  6726 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-15 15:04:05.011  6676  6726 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-15 15:04:05.011  6676  6726 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-15 15:04:05.021  6676  6676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-15 15:04:05.021  6676  6676 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-15 15:04:05.041  6676  6676 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-15 15:04:05.111   988  2062 D PMS     : releaseWL(2349a68a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
03-15 15:04:05.111   988  1624 D PMS     : acquireWL(ae211f2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms},
,03-15 15:04:05.131   988  2342 D PMS     : releaseWL(ae211f2): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,03-15 15:04:05.131   988  1587 D PMS     : acquireWL(16e59043): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,03-15 15:04:05.141   988  1597 D PMS     : releaseWL(16e59043): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,03-15 15:04:05.861  6676  6734 W jxcore-log: Initializing JXcore engine,
03-15 15:04:05.861  6676  6734 W jxcore-log: JXcore engine is ready
,03-15 15:04:05.921  6676  6734 W jxcore-log: Starting JXcore engine,
,03-15 15:04:06.001  6676  6734 W jxcore-log: Platform android,
03-15 15:04:06.001  6676  6734 W jxcore-log: 
03-15 15:04:06.001  6676  6734 W jxcore-log: Process ARCH arm
03-15 15:04:06.001  6676  6734 W jxcore-log: 
,03-15 15:04:06.031   988  1061 D PMS     : releaseHCC(18ae61ad): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,03-15 15:04:06.041   988  1061 D PMS     : releaseHCC(1cd07ce2): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,03-15 15:04:06.341  6676  6734 I jxcore-log: JXcore Cordova bridge is ready!,
03-15 15:04:06.341  6676  6734 I jxcore-log: 
03-15 15:04:06.341  6676  6734 W jxcore-log: JXcore engine is started
,03-15 15:04:06.351  6676  6726 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-15 15:04:06.381  6676  6734 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
03-15 15:04:06.381  6676  6734 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-15 15:04:06.391  6676  6676 I chromium: [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54),
,03-15 15:04:06.461   988  1604 I ActivityManager: Killing 5770:com.android.defcontainer/u0a15 (adj 15): empty #17,
03-15 15:04:06.461   988  1604 D Process : killProcessQuiet, pid=5770
03-15 15:04:06.461   988  1604 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,03-15 15:04:06.581   988  1587 I ActivityManager: Recipient 5770
,03-15 15:04:06.681  6676  6726 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 280ms. Plugin should use CordovaInterface.getThreadPool().
,03-15 15:04:06.751  6676  6676 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@24f95a7c that was originally registered here. Are you missing a call to unregisterReceiver()?,
03-15 15:04:06.751  6676  6676 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@24f95a7c that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1749)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:488)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-15 15:04:06.751  6676  6676 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@2fa57f05 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 15:04:06.751  6676  6676 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@2fa57f05 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1749)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bl,uetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
03-15 15:04:06.751  6676  6676 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-15 15:04:11.821  1221  2493 D HtcUPManager: HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,03-15 15:04:11.831  1221  2493 D HtcUPManager: HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
03-15 15:04:11.831  1635  1635 D HtcAppUPService: HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@f77fec
03-15 15:04:11.831   988  1602 I ActivityManager: Killing 5516:com.htc.mediamanager/u0a28 (adj 15): empty #17
03-15 15:04:11.831   988  1602 D Process : killProcessQuiet, pid=5516
,03-15 15:04:11.841   988  1602 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-15 15:04:11.981   988  2055 I ActivityManager: Recipient 5516
,03-15 15:04:29.781   426   426 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,03-15 15:04:34.631   988  2062 D PMS     : acquireWL(88506c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
,03-15 15:04:34.631   988  2062 I BatteryService: n_update end
03-15 15:04:34.631   988  2062 D PMS     : releaseWL(88506c0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,03-15 15:04:34.641   988   988 D UsbnetService: BroadcastReceiver::onReceive+
03-15 15:04:34.641   988  1057 D HtcPowerSaver: updateBatteryInfo
03-15 15:04:34.641   988   988 D UsbnetService: onReceive BATTERY_CHANGED
03-15 15:04:34.641   988   988 D NotificationService: plugged=true pluggin=true
,03-15 15:04:34.641   988   988 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-15 15:04:34.641   988   988 D PMS     : runPSCheck
03-15 15:04:34.641   988   988 D UsbnetService: BroadcastReceiver::onReceive-
03-15 15:04:34.641   988   988 D HtcPowerSaver: Checking...
03-15 15:04:34.641  3251  3419 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-15 15:04:34.641   988   988 I HtcPowerSaver: >> updateStatus
03-15 15:04:34.641  1221  1450 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-15 15:04:34.641  1221  1221 D PowerUI : closing low battery warning: level=100
,03-15 15:04:34.641   988  1150 D WifiController: handleMessage: E msg.what=155652
03-15 15:04:34.641   988  1150 D WifiController: battery changed pluggedType: 2
03-15 15:04:34.641   988  1150 D WifiController: processMsg: DeviceActiveState
03-15 15:04:34.641  1221  1221 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-15 15:04:34.641   988  1150 D WifiController: processMsg: StaEnabledState
03-15 15:04:34.651   988   988 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-15 15:04:34.641   988  1150 D WifiController: processMsg: DefaultState
03-15 15:04:34.651   988   988 I HtcPowerSaver: << updateStatus
03-15 15:04:34.641   988  1150 D WifiController: handleMessage: X
,03-15 15:04:34.641  1327  1327 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 15:04:34.641  1327  1327 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 15:04:34.641  1327  1327 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,03-15 15:04:34.691  1221  1221 I BatteryController: status:5 level:100 unsupport:false plugged:true
,03-15 15:04:39.791   426   426 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,03-15 15:04:54.791   426   426 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,03-15 15:05:14.801   426   426 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,03-15 15:05:34.801   988   988 D UsbnetService: BroadcastReceiver::onReceive+
03-15 15:05:34.801   988  1587 D PMS     : acquireWL(21328ff9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null,
03-15 15:05:34.801   988   988 D UsbnetService: onReceive BATTERY_CHANGED
03-15 15:05:34.801   988  1587 I BatteryService: n_update end
03-15 15:05:34.801   988   988 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-15 15:05:34.801   988  1587 D PMS     : releaseWL(21328ff9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
03-15 15:05:34.801   988   988 D UsbnetService: BroadcastReceiver::onReceive-
03-15 15:05:34.801   988   988 D NotificationService: plugged=true pluggin=true
03-15 15:05:34.801   988  1150 D WifiController: handleMessage: E msg.what=155652
03-15 15:05:34.801   988  1150 D WifiController: battery changed pluggedType: 2
03-15 15:05:34.801   988  1150 D WifiController: processMsg: DeviceActiveState
03-15 15:05:34.801   988  1057 D HtcPowerSaver: updateBatteryInfo
03-15 15:05:34.801   988  1150 D WifiController: processMsg: StaEnabledState
03-15 15:05:34.801   988   988 D PMS     : runPSCheck
03-15 15:05:34.801   988  1150 D WifiController: processMsg: DefaultState
,03-15 15:05:34.801   988   988 D HtcPowerSaver: Checking...
03-15 15:05:34.801   988  1150 D WifiController: handleMessage: X
03-15 15:05:34.801   988   988 I HtcPowerSaver: >> updateStatus
03-15 15:05:34.801  1327  1327 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 15:05:34.801  1221  1221 D PowerUI : closing low battery warning: level=100
03-15 15:05:34.801  1327  1327 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 15:05:34.801  1221  1221 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-15 15:05:34.801  1327  1327 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-15 15:05:34.811   988   988 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-15 15:05:34.801  1221  1450 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-15 15:05:34.811   988   988 I HtcPowerSaver: << updateStatus
03-15 15:05:34.801  3251  3419 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 15:05:34.851  1221  1221 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,03-15 15:05:36.221  1326  1326 D wpa_supplicant: wlan0: BSS: Remove id 0 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST' due to wpa_bss_flush_by_age
03-15 15:05:36.221  1326  1326 D wpa_supplicant: wlan0: BSS: Remove id 2 BSSID 00:1f:27:54:70:c1 SSID 'TEST_KTW01' due to wpa_bss_flush_by_age
03-15 15:05:36.221  1326  1326 D wpa_supplicant: wlan0: BSS: Remove id 3 BSSID 00:1f:27:54:70:c0 SSID 'ktwtestwifi' due to wpa_bss_flush_by_age
03-15 15:05:36.221  1326  1326 D wpa_supplicant: wlan0: BSS: Remove id 4 BSSID 00:1f:27:54:dd:ef SSID '\x00' due to wpa_bss_flush_by_age
03-15 15:05:36.221  1326  1326 D wpa_supplicant: wlan0: BSS: Remove id 10 BSSID 00:1f:27:54:dd:eb SSID '\x00' due to wpa_bss_flush_by_age
03-15 15:05:36.221  1326  1326 D wpa_supplicant: wlan0: BSS: Remove id 5 BSSID 00:1f:27:54:e0:44 SSID '\x00' due to wpa_bss_flush_by_age
03-15 15:05:36.221   988  1590 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 f0:f2:6d:22:99:3e]
03-15 15:05:36.221  1326  1326 D wpa_supplicant: wlan0: BSS: Remove id 8 BSSID 00:22:0d:46:1c:a2 SSID '\x00' due to wpa_bss_flush_by_age
03-15 15:05:36.221   988  1590 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 f0:f2:6d:22:99:3e
03-15 15:05:36.221  1326  1326 D wpa_supplicant: wlan0: BSS: Remove id 9 BSSID d4:d9:19:01:c7:20 SSID '00000000' due to wpa_bss_flush_by_age
03-15 15:05:36.221  1326  1326 D wpa_supplicant: wlan0: BSS: Remove id 6 BSSID 00:1f:27:54:dd:e3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
03-15 15:05:36.221   988  1590 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c1]
03-15 15:05:36.221   988  1590 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c1
03-15 15:05:36.221  1326  1326 D wpa_supplicant: wlan0: BSS: Remove id 7 BSSID 00:1f:27:54:e0:43 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
03-15 15:05:36.221   988  1590 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:70:c0]
03-15 15:05:36.221  1326  1326 D wpa_supplicant: wlan0: BSS: Remove id 11 BSSID 00:22:0d:47:49:83 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
03-15 15:05:36.221   988  1590 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:70:c0
03-15 15:05:36.221   988  1590 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 00:1f:27:54:dd:ef]
03-15 15:05:36.221   988  1590 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 00:1f:27:54:dd:ef,
03-15 15:05:36.221   988  1590 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 00:1f:27:54:dd:eb]
03-15 15:05:36.221   988  1590 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-BSS-REMOVED 10 00:1f:27:54:dd:eb
03-15 15:05:36.221   988  1590 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 00:1f:27:54:e0:44]
03-15 15:05:36.221   988  1590 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 00:1f:27:54:e0:44
03-15 15:05:36.221   988  1590 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 00:22:0d:46:1c:a2]
03-15 15:05:36.221   988  1590 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-BSS-REMOVED 8 00:22:0d:46:1c:a2
03-15 15:05:36.221   988  1590 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 d4:d9:19:01:c7:20]
03-15 15:05:36.221   988  1590 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-BSS-REMOVED 9 d4:d9:19:01:c7:20
03-15 15:05:36.221   988  1590 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 00:1f:27:54:dd:e3]
03-15 15:05:36.221   988  1590 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-BSS-REMOVED 6 00:1f:27:54:dd:e3
03-15 15:05:36.221   988  1590 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 00:1f:27:54:e0:43]
03-15 15:05:36.221   988  1590 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-BSS-REMOVED 7 00:1f:27:54:e0:43
03-15 15:05:36.221   988  1590 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 00:22:0d:47:49:83]
03-15 15:05:36.221   988  1590 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-BSS-REMOVED 11 00:22:0d:47:49:83
,03-15 15:05:39.801   426   426 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,03-15 15:06:22.661   988  1138 D PMS     : acquireWL(1dfb5b3e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 988 1000 WorkSource{1000}
03-15 15:06:22.661   988  1138 V AlarmManager: sending alarm PendingIntent{1fc96acd: PendingIntentRecord{edb1f82 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=259121, Int=0
,03-15 15:06:22.661   988  1138 V AlarmManager: sending alarm PendingIntent{e13ceec: PendingIntentRecord{3e0332b5 com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1458050782671, Int=0
,03-15 15:06:22.691   988   988 D PMS     : releaseWL(1dfb5b3e): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,03-15 15:06:22.701  1221  2431 D WeatherUtility: Weather sync is On
03-15 15:06:22.701  1221  2431 W WeatherTimeKeeper: [refreshWeatherData] no weather data
,03-15 15:06:24.811   426   426 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,03-15 15:06:34.811   426   426 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,03-15 15:06:34.951   988  1587 D PMS     : acquireWL(dcded4a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
03-15 15:06:34.951   988  1587 I BatteryService: n_update end
03-15 15:06:34.951   988  1587 D PMS     : releaseWL(dcded4a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,03-15 15:06:34.961   988   988 D UsbnetService: BroadcastReceiver::onReceive+
03-15 15:06:34.961   988  1057 D HtcPowerSaver: updateBatteryInfo
03-15 15:06:34.961   988   988 D UsbnetService: onReceive BATTERY_CHANGED
03-15 15:06:34.961   988   988 D NotificationService: plugged=true pluggin=true
03-15 15:06:34.961   988   988 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-15 15:06:34.961   988   988 D PMS     : runPSCheck
03-15 15:06:34.961   988   988 D UsbnetService: BroadcastReceiver::onReceive-
03-15 15:06:34.961   988   988 D HtcPowerSaver: Checking...
03-15 15:06:34.961  1327  1327 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 15:06:34.961   988   988 I HtcPowerSaver: >> updateStatus
03-15 15:06:34.961  1327  1327 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 15:06:34.961  1221  1221 D PowerUI : closing low battery warning: level=100
03-15 15:06:34.961   988  1150 D WifiController: handleMessage: E msg.what=155652
03-15 15:06:34.961   988  1150 D WifiController: battery changed pluggedType: 2
03-15 15:06:34.961  1327  1327 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-15 15:06:34.971  1221  1221 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-15 15:06:34.961   988  1150 D WifiController: processMsg: DeviceActiveState
03-15 15:06:34.961   988  1150 D WifiController: processMsg: StaEnabledState
03-15 15:06:34.961   988  1150 D WifiController: processMsg: DefaultState
03-15 15:06:34.961   988  1150 D WifiController: handleMessage: X
03-15 15:06:34.971  1221  1450 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-15 15:06:34.971  3251  3419 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 15:06:34.971   988   988 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-15 15:06:34.971   988   988 I HtcPowerSaver: << updateStatus
,03-15 15:06:35.021  1221  1221 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,03-15 15:06:49.821   426   426 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-15 15:06:55.791  1962  1962 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 15:06:55.831  1962  3323 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
03-15 15:06:55.831  1962  3323 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-15 15:06:55.831  1962  3323 I GLSUser : [GLSUser] Extracting token using key: Auth
03-15 15:06:55.831  1962  3323 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-15 15:06:55.841  1962  3323 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 15:06:55.881  1327  1389 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,03-15 15:06:55.881  1327  1389 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,03-15 15:06:55.891  1221  1221 I RemoteViews: reapply : com.google.android.gms 2 40
,03-15 15:06:55.891  1962  3323 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-15 15:06:55.891  1962  3323 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-15 15:06:55.891  1962  3323 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-15 15:06:55.891  1962  3323 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-15 15:06:55.891  1962  3323 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-15 15:06:55.891  1962  3323 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-15 15:06:55.891  1962  3323 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:454)
,03-15 15:06:55.891  6070  6109 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
03-15 15:06:55.891  6070  6109 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-15 15:06:55.891  6070  6109 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
03-15 15:06:55.891  6070  6109 E PlayEventLogger: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-15 15:06:55.891  6070  6109 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
03-15 15:06:55.891  6070  6109 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-15 15:06:55.891  6070  6109 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:454)
,03-15 15:06:55.931  6070  6109 W System  : Ignoring header User-Agent because its value was null.
,03-15 15:06:55.941  6070  6109 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
03-15 15:06:55.941  6070  6109 D libc    : [NET] android_getaddrinfofornet-, err=8
03-15 15:06:55.941  6070  6109 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
03-15 15:06:55.941  6070  6109 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
03-15 15:06:55.941  6070  6109 D libc    : [NET] android_getaddrinfo_proxy+
03-15 15:06:55.941  6070  6109 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,03-15 15:06:55.941   394  6739 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
03-15 15:06:55.941   394  6739 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,03-15 15:06:55.941   394  6739 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
03-15 15:06:55.941   394  6739 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
03-15 15:06:55.941  6070  6109 D libc    : [NET] android_getaddrinfo_proxy-, success
,03-15 15:07:09.831   426   426 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,03-15 15:07:34.831   426   426 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,03-15 15:08:24.841   426   426 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,03-15 15:08:34.841   426   426 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,03-15 15:08:35.281   988  1158 D PMS     : acquireWL(1e1ecb1c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
03-15 15:08:35.281   988  1158 I BatteryService: n_update end
03-15 15:08:35.281  1221  1450 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-15 15:08:35.281   988  1158 D PMS     : releaseWL(1e1ecb1c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
03-15 15:08:35.281  1327  1327 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 15:08:35.291  1221  1221 D PowerUI : closing low battery warning: level=100
03-15 15:08:35.291  1327  1327 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 15:08:35.291   988  1057 D HtcPowerSaver: updateBatteryInfo
03-15 15:08:35.291  1327  1327 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-15 15:08:35.291   988   988 D NotificationService: plugged=true pluggin=true,
03-15 15:08:35.291  3251  3419 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-15 15:08:35.291   988   988 D PMS     : runPSCheck
03-15 15:08:35.291   988   988 D UsbnetService: BroadcastReceiver::onReceive+
03-15 15:08:35.291   988   988 D HtcPowerSaver: Checking...
03-15 15:08:35.291   988   988 D UsbnetService: onReceive BATTERY_CHANGED
03-15 15:08:35.291   988   988 I HtcPowerSaver: >> updateStatus
03-15 15:08:35.291   988   988 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-15 15:08:35.291   988  1150 D WifiController: battery changed pluggedType: 2
03-15 15:08:35.291   988   988 D UsbnetService: BroadcastReceiver::onReceive-
03-15 15:08:35.291  1221  1221 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-15 15:08:35.291   988  1150 D WifiController: handleMessage: E msg.what=155652
03-15 15:08:35.291   988  1150 D WifiController: processMsg: DeviceActiveState
03-15 15:08:35.291   988  1150 D WifiController: processMsg: StaEnabledState
03-15 15:08:35.291   988  1150 D WifiController: processMsg: DefaultState
03-15 15:08:35.291   988  1150 D WifiController: handleMessage: X
,03-15 15:08:35.301   988   988 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
,03-15 15:08:35.301   988   988 I HtcPowerSaver: << updateStatus
,03-15 15:08:35.331  1221  1221 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,03-15 15:08:49.851   426   426 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-15 15:09:09.851   426   426 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,03-15 15:09:34.861   426   426 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,03-15 15:10:47.561   387   431 E PNP_UPDATERD: inotify_add_watch failed. (No such file or directory)
,03-15 15:11:09.061  1545  1743 D ContactMessageStore: MSG_CHECK_DELETION >>
03-15 15:11:09.061  1545  1743 D ContactMessageStore: mDeleteTask = null, bDeleting = false
03-15 15:11:09.071  1545  1743 D AccFlag : sku_id=118
03-15 15:11:09.071  1545  1743 D ContactMessageStore: MSG_CHECK_DELETION <<
,03-15 15:11:09.071  1545  6740 D ContactMessageStore: start background delete task...
,03-15 15:11:09.071  1545  6740 D ContactMessageStore: size: 0 , 0
,03-15 15:11:09.071  1545  6740 D ContactMessageStore: Background delete complete
,03-15 15:11:35.761  1221  1450 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-15 15:11:35.761   988  1014 D PMS     : acquireWL(28a73325): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null,
03-15 15:11:35.761  1327  1327 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 15:11:35.761   988  1014 I BatteryService: n_update end
03-15 15:11:35.761  3251  3419 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-15 15:11:35.761   988  1014 D PMS     : releaseWL(28a73325): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
03-15 15:11:35.761  1327  1327 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 15:11:35.761  1221  1221 D PowerUI : closing low battery warning: level=100
03-15 15:11:35.761   988   988 D UsbnetService: BroadcastReceiver::onReceive+
03-15 15:11:35.761   988   988 D NotificationService: plugged=true pluggin=true
03-15 15:11:35.761  1327  1327 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-15 15:11:35.761  1221  1221 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-15 15:11:35.761   988   988 D UsbnetService: onReceive BATTERY_CHANGED
03-15 15:11:35.771   988  1150 D WifiController: battery changed pluggedType: 2
,03-15 15:11:35.771   988   988 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-15 15:11:35.771   988   988 D UsbnetService: BroadcastReceiver::onReceive-
03-15 15:11:35.771   988  1150 D WifiController: handleMessage: E msg.what=155652
03-15 15:11:35.771   988  1150 D WifiController: processMsg: DeviceActiveState
03-15 15:11:35.771   988  1150 D WifiController: processMsg: StaEnabledState
03-15 15:11:35.771   988  1150 D WifiController: processMsg: DefaultState
03-15 15:11:35.771   988  1150 D WifiController: handleMessage: X
,03-15 15:11:35.811  1221  1221 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,03-15 15:11:36.411   988  1057 D HtcPowerSaver: updateBatteryInfo
03-15 15:11:36.411   988   988 D PMS     : runPSCheck
,03-15 15:11:36.411   988   988 D HtcPowerSaver: Checking...
03-15 15:11:36.411   988   988 I HtcPowerSaver: >> updateStatus
,03-15 15:11:36.411   988   988 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-15 15:11:36.411   988   988 I HtcPowerSaver: << updateStatus
,03-15 15:13:20.381   988  1393 D PMS     : acquireWL(34643cfa): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,03-15 15:13:20.391   988  1138 D PMS     : acquireWL(3c9e52ab): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 988 1000 WorkSource{1000}
03-15 15:13:20.391   988  1138 V AlarmManager: sending alarm PendingIntent{1fc96acd: PendingIntentRecord{edb1f82 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=379121, Int=0
,03-15 15:13:20.391   988  1853 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
03-15 15:13:20.391   988  1013 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
03-15 15:13:20.391   988  1853 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
03-15 15:13:20.391   988  1152 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
03-15 15:13:20.391   988  1853 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
03-15 15:13:20.391   988  1152 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-15 15:13:20.391   988  1853 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
03-15 15:13:20.391   988  1152 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
03-15 15:13:20.391   988  1853 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
03-15 15:13:20.391   988  1152 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
03-15 15:13:20.391   988  1152 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
,03-15 15:13:20.391   988  1152 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
03-15 15:13:20.391   988  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-15 15:13:20.391   988  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
03-15 15:13:20.391   988  1138 V AlarmManager: sending alarm PendingIntent{14bcdca1: PendingIntentRecord{2e020af3 com.android.vending startService}}, i=null, t=0, cnt=1, w=1458051082498, Int=0
03-15 15:13:20.391  1221  1725 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-15 15:13:20.391   988  1152 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
03-15 15:13:20.401  6070  6070 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,03-15 15:13:20.401  1221  1725 I SecurityController: onAvailable 100 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
03-15 15:13:20.401   988  1634 D PMS     : releaseWL(34643cfa): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,03-15 15:13:20.421  1221  2431 D WeatherUtility: Weather sync is On
03-15 15:13:20.421   988   988 D PMS     : releaseWL(3c9e52ab): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,03-15 15:13:20.421  1221  2431 W WeatherTimeKeeper: [refreshWeatherData] no weather data
03-15 15:13:20.421  1962  1962 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 15:13:20.481  1962  1986 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
03-15 15:13:20.481  1962  1986 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,03-15 15:13:20.481  1962  1986 I GLSUser : [GLSUser] Extracting token using key: Auth
03-15 15:13:20.481  1962  1986 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-15 15:13:20.491  1962  1986 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 15:13:20.521  6070  6070 W Finsky  : [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-15 15:13:20.531  1962  1962 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 15:13:20.761   988  1598 I art     : Explicit concurrent mark sweep GC freed 28630(1579KB) AllocSpace objects, 9(788KB) LOS objects, 33% free, 16MB/24MB, paused 2.122ms total 207.387ms
,03-15 15:13:20.791  1962  1985 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
03-15 15:13:20.791  1962  1985 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-15 15:13:20.791  1962  1985 I GLSUser : [GLSUser] Extracting token using key: Auth
03-15 15:13:20.791  1962  1985 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-15 15:13:20.801  1962  1985 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-15 15:13:20.831  1962  1962 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-15 15:13:20.881  1962  2089 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket,
03-15 15:13:20.881  1962  2089 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-15 15:13:20.881  1962  2089 I GLSUser : [GLSUser] Extracting token using key: Auth
03-15 15:13:20.881  1962  2089 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-15 15:13:20.891  1962  2089 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 15:13:20.961  6070  6070 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,03-15 15:13:21.281  1962  1962 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 15:13:21.331  1962  1986 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
03-15 15:13:21.331  1962  1986 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-15 15:13:21.331  1962  1986 I GLSUser : [GLSUser] Extracting token using key: Auth
03-15 15:13:21.331  1962  1986 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-15 15:13:21.341  1962  1986 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 15:13:21.371  6070  6070 W Finsky  : [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
03-15 15:13:21.371  6070  6070 D Finsky  : [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,03-15 15:13:21.381  6070  6070 D Finsky  : [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-15 15:13:21.391  6070  6070 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
,03-15 15:13:21.401  1855  1892 D DeviceConnectionService: client connected with version: 7571000,
,03-15 15:13:29.571   988  1138 D PMS     : acquireWL(35980af1): PARTIAL_WAKE_LOCK  *alarm* 0x1 988 1000 WorkSource{10024}
03-15 15:13:29.571   988  1138 V AlarmManager: sending alarm PendingIntent{c7846d6: PendingIntentRecord{144f8d57 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=768700, Int=0
03-15 15:13:29.571   988  1013 D PMS     : acquireWL(b39e044): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,03-15 15:13:29.571   988   988 D PMS     : releaseWL(35980af1): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10024}
,03-15 15:13:29.571  1962  6746 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,03-15 15:13:29.571  1962  6746 D libc    : [NET] android_getaddrinfofornet-, err=8
03-15 15:13:29.571  1962  6746 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
03-15 15:13:29.571  1962  6746 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
03-15 15:13:29.571  1962  6746 D libc    : [NET] android_getaddrinfo_proxy+,
03-15 15:13:29.571  1962  6746 D libc    : [NET] android_getaddrinfo_proxy get netid:0
,03-15 15:13:29.581   394  6747 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
,03-15 15:13:29.581   394  6747 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,03-15 15:13:29.671   394  6747 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
03-15 15:13:29.671   394  6747 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,03-15 15:13:29.671  1962  6746 D libc    : [NET] android_getaddrinfo_proxy-, success
,03-15 15:13:29.761  1962  6746 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,03-15 15:13:29.761  1962  6746 D libc    : [NET] android_getaddrinfofornet-, err=8
,03-15 15:13:29.831  1962  6746 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
,03-15 15:13:29.831  1962  6746 D libc    : [NET] android_getaddrinfofornet-, err=8
,03-15 15:13:30.041   988  2055 D PMS     : acquireWL(2291652d): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,03-15 15:13:30.041  1962  6749 D GCM     : Connected
,03-15 15:13:30.041   988  1393 D PMS     : releaseWL(b39e044): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,03-15 15:13:30.051   988  2342 D PMS     : releaseWL(2291652d): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,03-15 15:13:30.101   988  1634 D PMS     : acquireWL(3289fa62): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,03-15 15:13:30.111  1962  6749 D GCM     : Message class com.google.f.a.a.p
,03-15 15:13:30.121   988  1587 D PMS     : releaseWL(3289fa62): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,03-15 15:13:35.971   988  1138 D PMS     : acquireWL(516bcb0): PARTIAL_WAKE_LOCK  *alarm* 0x1 988 1000 WorkSource{10072}
03-15 15:13:35.971   988  1138 V AlarmManager: sending alarm PendingIntent{384c2729: PendingIntentRecord{1f115aae com.android.vending startService}}, i=null, t=0, cnt=1, w=1458051215972, Int=0
,03-15 15:13:35.971   988   988 D PMS     : releaseWL(516bcb0): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10072}
,03-15 15:13:36.071   988  1634 D PMS     : acquireWL(1498d04f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null,
,03-15 15:13:36.071   988  1634 I BatteryService: n_update end
03-15 15:13:36.071   988  1634 D PMS     : releaseWL(1498d04f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,03-15 15:13:36.081   988  1057 D HtcPowerSaver: updateBatteryInfo
03-15 15:13:36.081  1221  1221 D PowerUI : closing low battery warning: level=100
,03-15 15:13:36.081  1327  1327 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 15:13:36.081  1221  1221 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-15 15:13:36.081  1327  1327 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 15:13:36.081  1327  1327 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-15 15:13:36.081  1221  1450 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
,03-15 15:13:36.081   988   988 D NotificationService: plugged=true pluggin=true
03-15 15:13:36.081   988   988 D UsbnetService: BroadcastReceiver::onReceive+
03-15 15:13:36.081   988   988 D UsbnetService: onReceive BATTERY_CHANGED
03-15 15:13:36.081   988   988 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-15 15:13:36.081   988   988 D PMS     : runPSCheck
03-15 15:13:36.081   988   988 D UsbnetService: BroadcastReceiver::onReceive-
03-15 15:13:36.081   988   988 D HtcPowerSaver: Checking...
03-15 15:13:36.081   988  1150 D WifiController: handleMessage: E msg.what=155652
03-15 15:13:36.081   988   988 I HtcPowerSaver: >> updateStatus
03-15 15:13:36.081  3251  3419 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-15 15:13:36.081   988  1150 D WifiController: processMsg: DeviceActiveState
03-15 15:13:36.081   988  1150 D WifiController: processMsg: StaEnabledState
03-15 15:13:36.081   988  1150 D WifiController: battery changed pluggedType: 2
03-15 15:13:36.081   988  1150 D WifiController: processMsg: DefaultState
03-15 15:13:36.081   988  1150 D WifiController: handleMessage: X
,03-15 15:13:36.081   988   988 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-15 15:13:36.081   988   988 I HtcPowerSaver: << updateStatus
,03-15 15:13:36.131  1221  1221 I BatteryController: status:5 level:100 unsupport:false plugged:true
,03-15 15:13:36.251  6070  6117 D Finsky  : [617] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.,
03-15 15:13:36.251  6070  6070 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,03-15 15:14:16.241   988  1138 D PMS     : acquireWL(a2f3dc): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 988 1000 WorkSource{1000}
03-15 15:14:16.241   988  1138 V AlarmManager: sending alarm PendingIntent{1fc96acd: PendingIntentRecord{edb1f82 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=799121, Int=0
,03-15 15:14:16.241   988  1138 V AlarmManager: sending alarm PendingIntent{1552b32c: PendingIntentRecord{6d5e1f5 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=804656, Int=0,
,03-15 15:14:16.261   988  1138 I ActivityManager: Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6751 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-15 15:14:16.261   988  1138 V AlarmManager: sending alarm PendingIntent{23d70ce5: PendingIntentRecord{269c73ba com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1458051256250, Int=0
,03-15 15:14:16.281   988   988 D PMS     : releaseWL(a2f3dc): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,03-15 15:14:16.291  1221  2431 D WeatherUtility: Weather sync is On,
03-15 15:14:16.291  1221  2431 W WeatherTimeKeeper: [refreshWeatherData] no weather data
,03-15 15:14:16.391   988  1048 D StatusBarManagerService: setSystemUiVisibility(0x8700)
03-15 15:14:16.391   988  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-15 15:14:16.391   988  1048 D StatusBarManagerService: hiding MENU key,
03-15 15:14:16.391   988  1048 D StatusBarManagerService: setSystemUiVisibility(0xc0000700)
03-15 15:14:16.391   988  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-15 15:14:16.391   988  1048 D StatusBarManagerService: hiding MENU key
,03-15 15:14:16.401  1596  1596 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,03-15 15:14:16.411  1596  1596 I ThreadedRenderer: Defer allocateBuffers to drawing time,
,03-15 15:14:16.421   988  1393 I InputMethodManagerService: Disable input method client, pid=6676
03-15 15:14:16.421   988  1393 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
,03-15 15:14:16.421  6676  6676 W IInputConnectionWrapper: Do restartInputUnchecked, ic=null
03-15 15:14:16.421  6676  6676 I InputMethodManager: com.test.thalitest called restartInputUnchecked(msg=100) from com.android.internal.view.IInputConnectionWrapper.executeMessage(IInputConnectionWrapper.java:213)
03-15 15:14:16.421  6676  6676 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection
,03-15 15:14:16.431  1221  1221 I PhoneStatusBar: setImeWindowStatus(false,false)
,03-15 15:14:16.501  6773  6773 E cutils-trace: Error opening trace file: Permission denied (13),
03-15 15:14:16.501  6773  6773 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
03-15 15:14:16.501  6773  6773 I dex2oat : dex2oat: override thread count:4
,03-15 15:14:17.171  6773  6773 I dex2oat : dex2oat took 671.188ms (threads: 4)
,03-15 15:14:17.201  6751  6751 I PushClient: ApplicationMonitor {2b88fa6d}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,03-15 15:14:17.201  6751  6751 I PushClient: ApplicationMonitor {2b88fa6d}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns
03-15 15:14:17.211  6751  6751 I PushClient: ApplicationMonitor {2b88fa6d}: logBasicAppInfo(): VersionName:             1.2.853019
03-15 15:14:17.211  6751  6751 I PushClient: ApplicationMonitor {2b88fa6d}: logBasicAppInfo(): VersionCode:             148001224
03-15 15:14:17.211  6751  6751 I PushClient: ApplicationMonitor {2b88fa6d}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,03-15 15:14:17.211  6751  6751 I PushClient: ApplicationMonitor {2b88fa6d}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files,
03-15 15:14:17.211  6751  6751 I PushClient: ApplicationMonitor {2b88fa6d}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
03-15 15:14:17.211  6751  6751 I PushClient: ApplicationMonitor {2b88fa6d}: logBasicAppInfo(): Htc_DEBUG_flag:          false
,03-15 15:14:17.211  6751  6751 I PushClient: ApplicationMonitor {2b88fa6d}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,03-15 15:14:17.221  6751  6779 I PushClient: PnsModel {36298284}: update(): Update registration caused by: alarm
,03-15 15:14:17.241  6751  6779 I PushClient: PnsConfigModel {200881ab}: <init>(): Use dm-client for provisioning.
,03-15 15:14:17.261  6751  6779 W System.err: SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,03-15 15:14:17.261  6751  6779 W System.err: SLF4J: Defaulting to no-operation (NOP) logger implementation
03-15 15:14:17.261  6751  6779 W System.err: SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,03-15 15:14:17.281  6751  6779 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,03-15 15:14:17.311   988  1393 I ActivityManager: Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=6781 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,03-15 15:14:17.431  6781  6781 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=6781 dbg=false s=true
,03-15 15:14:17.441  6781  6800 I DeviceManagement: ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
03-15 15:14:17.441  6781  6800 I DeviceManagement: ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,03-15 15:14:17.451  6781  6804 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
,03-15 15:14:17.451  6781  6781 I DeviceManagement: WorkflowService: Starting workflow service
,03-15 15:14:17.461  6781  6805 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2e7097e] args=[Bundle[mParcelledData.dataSize=88]]
,03-15 15:14:17.461  6781  6805 I DeviceManagement: ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,03-15 15:14:17.461  6781  6805 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
,03-15 15:14:17.501  6781  6805 I DeviceManagement: ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false,
,03-15 15:14:17.511  6781  6806 I DeviceManagement: SessionStateController: Checking invariants...,
,03-15 15:14:17.711  6781  6806 I DeviceManagement: ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,03-15 15:14:17.781  6781  6805 I DeviceManagement: SessionStateController: Checking invariants...,
,03-15 15:14:17.861  6781  6805 I DeviceManagement: ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false
,03-15 15:14:17.861  6781  6805 I DeviceManagement: WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@2e7097e]
,03-15 15:14:17.861  6781  6781 I DeviceManagement: WorkflowService: Stopping workflow service,
03-15 15:14:17.871   988  1602 D Process : killProcessQuiet, pid=6474
03-15 15:14:17.871   988  1602 I ActivityManager: Killing 6474:com.google.android.setupwizard/u0a77 (adj 15): empty #17
03-15 15:14:17.871   988  1602 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-15 15:14:17.981   988  1013 I ActivityManager: Recipient 6474,
,03-15 15:14:17.991  6751  6779 I PushClient: PnsModel {36298284}: update(): The registration record has not expired yet. No need to update.
,03-15 15:14:18.001   988  2055 D Process : killProcessQuiet, pid=6430
03-15 15:14:18.001   988  2055 I ActivityManager: Killing 6430:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
03-15 15:14:18.001   988  2055 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-15 15:14:18.101   988  1597 I ActivityManager: Recipient 6430
,03-15 15:14:36.241   988  1602 D PMS     : acquireWL(2e746b3f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
,03-15 15:14:36.241   988  1602 I BatteryService: n_update end
,03-15 15:14:36.241   988  1602 D PMS     : releaseWL(2e746b3f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
03-15 15:14:36.251  1327  1327 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 15:14:36.241   988  1057 D HtcPowerSaver: updateBatteryInfo
03-15 15:14:36.251  1327  1327 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 15:14:36.241  1221  1221 D PowerUI : closing low battery warning: level=100
03-15 15:14:36.251  1327  1327 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-15 15:14:36.251  1221  1450 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-15 15:14:36.251  1221  1221 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-15 15:14:36.251  3251  3419 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 15:14:36.251   988   988 D NotificationService: plugged=true pluggin=true
,03-15 15:14:36.251   988   988 D UsbnetService: BroadcastReceiver::onReceive+,
03-15 15:14:36.251   988   988 D PMS     : runPSCheck
03-15 15:14:36.251   988   988 D UsbnetService: onReceive BATTERY_CHANGED
03-15 15:14:36.251   988   988 D HtcPowerSaver: Checking...
03-15 15:14:36.251   988   988 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,03-15 15:14:36.251   988   988 I HtcPowerSaver: >> updateStatus
03-15 15:14:36.251   988   988 D UsbnetService: BroadcastReceiver::onReceive-
03-15 15:14:36.251   988  1150 D WifiController: battery changed pluggedType: 2
03-15 15:14:36.251   988  1150 D WifiController: handleMessage: E msg.what=155652
03-15 15:14:36.251   988  1150 D WifiController: processMsg: DeviceActiveState
03-15 15:14:36.251   988  1150 D WifiController: processMsg: StaEnabledState,
03-15 15:14:36.251   988  1150 D WifiController: processMsg: DefaultState
03-15 15:14:36.261   988  1150 D WifiController: handleMessage: X
03-15 15:14:36.261   988   988 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-15 15:14:36.261   988   988 I HtcPowerSaver: << updateStatus
,03-15 15:14:36.301  1221  1221 I BatteryController: status:5 level:100 unsupport:false plugged:true
,03-15 15:15:36.391   988  2062 D PMS     : acquireWL(31f90c0c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
03-15 15:15:36.391   988  2062 I BatteryService: n_update end
,03-15 15:15:36.391   988  2062 D PMS     : releaseWL(31f90c0c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,03-15 15:15:36.401   988   988 D UsbnetService: BroadcastReceiver::onReceive+
03-15 15:15:36.401   988  1057 D HtcPowerSaver: updateBatteryInfo
03-15 15:15:36.401   988   988 D UsbnetService: onReceive BATTERY_CHANGED
03-15 15:15:36.401   988   988 D NotificationService: plugged=true pluggin=true,
03-15 15:15:36.401   988   988 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-15 15:15:36.401   988   988 D PMS     : runPSCheck
03-15 15:15:36.401   988   988 D UsbnetService: BroadcastReceiver::onReceive-
03-15 15:15:36.401   988   988 D HtcPowerSaver: Checking...
03-15 15:15:36.401   988  1150 D WifiController: handleMessage: E msg.what=155652
03-15 15:15:36.401   988   988 I HtcPowerSaver: >> updateStatus
03-15 15:15:36.401   988  1150 D WifiController: processMsg: DeviceActiveState
03-15 15:15:36.401   988  1150 D WifiController: battery changed pluggedType: 2
03-15 15:15:36.401   988  1150 D WifiController: processMsg: StaEnabledState
03-15 15:15:36.401  1221  1221 D PowerUI : closing low battery warning: level=100
03-15 15:15:36.401   988  1150 D WifiController: processMsg: DefaultState
03-15 15:15:36.401  1221  1221 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-15 15:15:36.401   988  1150 D WifiController: handleMessage: X
03-15 15:15:36.411   988   988 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-15 15:15:36.401  1221  1450 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
,03-15 15:15:36.411   988   988 I HtcPowerSaver: << updateStatus
03-15 15:15:36.401  1327  1327 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 15:15:36.401  1327  1327 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 15:15:36.401  1327  1327 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-15 15:15:36.401  3251  3419 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 15:15:36.451  1221  1221 I BatteryController: status:5 level:100 unsupport:false plugged:true
,03-15 15:16:22.531   988  1138 D PMS     : acquireWL(5fdf955): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 988 1000 WorkSource{1000}
03-15 15:16:22.541   988  1138 V AlarmManager: sending alarm PendingIntent{1fc96acd: PendingIntentRecord{edb1f82 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=859121, Int=0
,03-15 15:16:22.541   988  1138 V AlarmManager: sending alarm PendingIntent{1bd93f6a: PendingIntentRecord{2ce7c5b com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=941667, Int=0
03-15 15:16:22.541  3251  3458 I bt-btm  : Received oneshot timer event complete
03-15 15:16:22.541  3251  3458 I bt-btm  : btm_ble_timeout
03-15 15:16:22.541  3251  3458 I bt-btm  : btm_gen_resolvable_private_addr
03-15 15:16:22.541   988  1597 D PMS     : acquireWL(2530dcf8): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3251 1002 null
,03-15 15:16:22.561  3251  3458 D bt-btm  : btm_ble_rand_enc_complete
03-15 15:16:22.561  3251  3458 I bt-btm  : btm_gen_resolve_paddr_low,
03-15 15:16:22.561  3251  3458 D bt-smp  : smp_encrypt_data
03-15 15:16:22.561   988   988 D PMS     : releaseWL(5fdf955): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
03-15 15:16:22.561  3251  3458 W bt-smp  : Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
03-15 15:16:22.561  3251  3458 W bt-smp  : Plain text(LSB ~ MSB) = 28 c3 76 00 00 00 00 00 00 00 00 00 00 00 00 00 
03-15 15:16:22.561  3251  3458 W bt-smp  : Encrypted text(LSB ~ MSB) = 43 9b a0 97 5f b0 bc 3f 2c 35 de bb 9e 10 a6 29 ,
03-15 15:16:22.561  3251  3458 I bt-btm  : btm_gen_resolve_paddr_cmpl
03-15 15:16:22.561  3251  3458 W bt-btm  : Stopping oneshot timer
03-15 15:16:22.561  3251  3458 D bt-btm  : Starting oneshot timer type:103 timeout:900s
03-15 15:16:22.561  1221  2431 D WeatherUtility: Weather sync is On
03-15 15:16:22.561  1221  2431 W WeatherTimeKeeper: [refreshWeatherData] no weather data
,03-15 15:16:23.551   988  1624 D PMS     : releaseWL(2530dcf8): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,03-15 15:16:59.991   988  1138 D PMS     : acquireWL(18f1d5d1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 988 1000 WorkSource{1000}
,03-15 15:16:59.991   988  1138 V AlarmManager: sending alarm PendingIntent{1fc96acd: PendingIntentRecord{edb1f82 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=979121, Int=0
03-15 15:16:59.991   988  1138 V AlarmManager: sending alarm PendingIntent{3ec3e836: PendingIntentRecord{17375e81 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1458051408368, Int=0
,03-15 15:17:00.001  6566  6566 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 ,
,03-15 15:17:00.011   988   988 D PMS     : releaseWL(18f1d5d1): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
03-15 15:17:00.011  1221  2431 D WeatherUtility: Weather sync is On
,03-15 15:17:00.021  6566  6809 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
,03-15 15:17:00.021  1221  2431 W WeatherTimeKeeper: [refreshWeatherData] no weather data
,03-15 15:17:00.031  6566  6809 D PowerUsageService: repeat time = 1458052320037
,03-15 15:17:00.121  6566  6809 I PowerUsageList:PowerUsageHelper: PowerProfile::POWER_SCREEN_FULL = 154.8
,03-15 15:17:00.131  6566  6809 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0,
,03-15 15:17:00.141  6566  6809 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0,
,03-15 15:17:00.141  6566  6809 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0,
,03-15 15:17:00.161  6566  6809 D PowerUsageService: calcPower(), no data,
,03-15 15:17:34.661   988  1138 D PMS     : acquireWL(a12d0a4): PARTIAL_WAKE_LOCK  *alarm* 0x1 988 1000 WorkSource{1000},
03-15 15:17:34.661   988  1138 V AlarmManager: sending alarm PendingIntent{86cfe0d: PendingIntentRecord{16de51c2 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1458051454673, Int=0
,03-15 15:17:34.671  6566  6566 D SmartSyncUtils: isEpsOn(), nState = 0,
,03-15 15:17:34.671   988   988 D PMS     : releaseWL(a12d0a4): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,03-15 15:17:34.681   988  2062 D PMS     : acquireWL(379e1bd3): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6566 1000 null
,03-15 15:17:34.691  6566  6810 D SmartSyncScreenOnOffTimeReceiver: [updateNmRange] bManual = false
,03-15 15:17:34.691  6566  6810 D SmartSyncScreenOnOffTimeReceiver: [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,03-15 15:17:34.701  6566  6810 D SmartSyncScreenOnOffTimeReceiver: AlarmOnTime = -1
,03-15 15:17:34.701  6566  6810 D SmartSyncScreenOnOffTimeReceiver: SettingOnTime = 1458108000000, randomSettingOnTime = 1458106871000
,03-15 15:17:34.701  6566  6810 D SmartSyncScreenOnOffTimeReceiver: SettingOffTime = 1458086400000, randomSettingOffTime = 1458091311000
,03-15 15:17:34.701  6566  6810 D SmartSyncScreenOnOffTimeReceiver: bDayMode = false
,03-15 15:17:34.701  6566  6810 D SmartSyncScreenOnOffTimeReceiver: bNightMode = true,
,03-15 15:17:34.711  6566  6810 D SmartSyncScreenOnOffTimeReceiver: bNightModeTurnOffOnce = false
,03-15 15:17:34.711   988  1393 D PMS     : releaseWL(379e1bd3): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,03-15 15:17:36.711   988  2342 D PMS     : acquireWL(32fe5310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
,03-15 15:17:36.711   988  2342 I BatteryService: n_update end
03-15 15:17:36.721   988  2342 D PMS     : releaseWL(32fe5310): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,03-15 15:17:36.721  1327  1327 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 15:17:36.721  1327  1327 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 15:17:36.721  1327  1327 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-15 15:17:36.721  3251  3419 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-15 15:17:36.721  1221  1221 D PowerUI : closing low battery warning: level=100
03-15 15:17:36.721  1221  1450 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-15 15:17:36.721   988   988 D NotificationService: plugged=true pluggin=true
03-15 15:17:36.721   988   988 D UsbnetService: BroadcastReceiver::onReceive+
03-15 15:17:36.721   988   988 D UsbnetService: onReceive BATTERY_CHANGED
03-15 15:17:36.721   988   988 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-15 15:17:36.721   988  1150 D WifiController: battery changed pluggedType: 2
03-15 15:17:36.721   988   988 D UsbnetService: BroadcastReceiver::onReceive-
03-15 15:17:36.721  1221  1221 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-15 15:17:36.721   988  1150 D WifiController: handleMessage: E msg.what=155652,
03-15 15:17:36.731   988  1057 D HtcPowerSaver: updateBatteryInfo
03-15 15:17:36.721   988  1150 D WifiController: processMsg: DeviceActiveState
03-15 15:17:36.731   988   988 D PMS     : runPSCheck
03-15 15:17:36.721   988  1150 D WifiController: processMsg: StaEnabledState
03-15 15:17:36.731   988   988 D HtcPowerSaver: Checking...
03-15 15:17:36.721   988  1150 D WifiController: processMsg: DefaultState
03-15 15:17:36.731   988   988 I HtcPowerSaver: >> updateStatus
03-15 15:17:36.721   988  1150 D WifiController: handleMessage: X
03-15 15:17:36.731   988   988 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-15 15:17:36.731   988   988 I HtcPowerSaver: << updateStatus
,03-15 15:17:36.771  1221  1221 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,03-15 15:20:37.191   988  1604 D PMS     : acquireWL(1f86e09): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
03-15 15:20:37.191   988  1604 I BatteryService: n_update end
,03-15 15:20:37.191   988  1604 D PMS     : releaseWL(1f86e09): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
03-15 15:20:37.201   988  1057 D HtcPowerSaver: updateBatteryInfo
03-15 15:20:37.201  1221  1450 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-15 15:20:37.201  1221  1221 D PowerUI : closing low battery warning: level=100
03-15 15:20:37.201  1327  1327 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 15:20:37.201   988   988 D NotificationService: plugged=true pluggin=true
03-15 15:20:37.201  3251  3419 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-15 15:20:37.201  1221  1221 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-15 15:20:37.201  1327  1327 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 15:20:37.201   988   988 D PMS     : runPSCheck
03-15 15:20:37.201  1327  1327 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-15 15:20:37.201   988  1150 D WifiController: battery changed pluggedType: 2
03-15 15:20:37.201   988   988 D UsbnetService: BroadcastReceiver::onReceive+
03-15 15:20:37.201   988   988 D HtcPowerSaver: Checking...
03-15 15:20:37.201   988   988 D UsbnetService: onReceive BATTERY_CHANGED
03-15 15:20:37.201   988   988 I HtcPowerSaver: >> updateStatus
03-15 15:20:37.201   988   988 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-15 15:20:37.201   988   988 D UsbnetService: BroadcastReceiver::onReceive-
03-15 15:20:37.201   988  1150 D WifiController: handleMessage: E msg.what=155652
03-15 15:20:37.201   988  1150 D WifiController: processMsg: DeviceActiveState
03-15 15:20:37.201   988  1150 D WifiController: processMsg: StaEnabledState
03-15 15:20:37.201   988  1150 D WifiController: processMsg: DefaultState
03-15 15:20:37.201   988  1150 D WifiController: handleMessage: X
,03-15 15:20:37.211   988   988 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-15 15:20:37.211   988   988 I HtcPowerSaver: << updateStatus
,03-15 15:20:37.251  1221  1221 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,03-15 15:20:47.561   387   431 E PNP_UPDATERD: inotify_add_watch failed. (No such file or directory)
,03-15 15:21:03.601   988  1031 I UsageStatsService: User[0] Flushing usage stats to disk
,03-15 15:23:37.681   988  2055 D PMS     : acquireWL(2c43c80e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null,
03-15 15:23:37.681   988  2055 I BatteryService: n_update end
03-15 15:23:37.681   988  2055 D PMS     : releaseWL(2c43c80e): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,03-15 15:23:37.691   988  1057 D HtcPowerSaver: updateBatteryInfo,
03-15 15:23:37.691   988   988 D PMS     : runPSCheck
03-15 15:23:37.691   988   988 D HtcPowerSaver: Checking...
03-15 15:23:37.691   988   988 I HtcPowerSaver: >> updateStatus
03-15 15:23:37.691   988   988 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-15 15:23:37.691   988   988 I HtcPowerSaver: << updateStatus
,03-15 15:23:37.701   988   988 D UsbnetService: BroadcastReceiver::onReceive+
03-15 15:23:37.701   988   988 D NotificationService: plugged=true pluggin=true
03-15 15:23:37.701   988   988 D UsbnetService: onReceive BATTERY_CHANGED
03-15 15:23:37.701   988  1150 D WifiController: battery changed pluggedType: 2
03-15 15:23:37.701   988   988 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-15 15:23:37.701  1221  1221 D PowerUI : closing low battery warning: level=100
03-15 15:23:37.701   988   988 D UsbnetService: BroadcastReceiver::onReceive-
03-15 15:23:37.701   988  1150 D WifiController: handleMessage: E msg.what=155652
03-15 15:23:37.701   988  1150 D WifiController: processMsg: DeviceActiveState
03-15 15:23:37.701   988  1150 D WifiController: processMsg: StaEnabledState
03-15 15:23:37.701  1221  1221 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-15 15:23:37.701   988  1150 D WifiController: processMsg: DefaultState
03-15 15:23:37.701   988  1150 D WifiController: handleMessage: X
03-15 15:23:37.701  1221  1450 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
,03-15 15:23:37.701  1327  1327 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 15:23:37.701  1327  1327 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 15:23:37.701  1327  1327 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-15 15:23:37.701  3251  3419 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 15:23:37.751  1221  1221 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,03-15 15:24:37.841   988  1602 D PMS     : acquireWL(8a4a22f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
03-15 15:24:37.841   988  1602 I BatteryService: n_update end
03-15 15:24:37.841   988  1602 D PMS     : releaseWL(8a4a22f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
03-15 15:24:37.841   988  1057 D HtcPowerSaver: updateBatteryInfo
,03-15 15:24:37.841  3251  3419 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-15 15:24:37.841  1221  1221 D PowerUI : closing low battery warning: level=100
03-15 15:24:37.841  1221  1450 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-15 15:24:37.841  1327  1327 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 15:24:37.841  1327  1327 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 15:24:37.841  1327  1327 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-15 15:24:37.841   988   988 D NotificationService: plugged=true pluggin=true
,03-15 15:24:37.841   988   988 D UsbnetService: BroadcastReceiver::onReceive+
03-15 15:24:37.851   988   988 D UsbnetService: onReceive BATTERY_CHANGED
03-15 15:24:37.851   988   988 D PMS     : runPSCheck
03-15 15:24:37.851   988   988 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-15 15:24:37.851   988   988 D HtcPowerSaver: Checking...
03-15 15:24:37.851   988   988 D UsbnetService: BroadcastReceiver::onReceive-
03-15 15:24:37.851   988   988 I HtcPowerSaver: >> updateStatus
03-15 15:24:37.851   988  1150 D WifiController: handleMessage: E msg.what=155652
03-15 15:24:37.851   988  1150 D WifiController: processMsg: DeviceActiveState
03-15 15:24:37.851   988  1150 D WifiController: processMsg: StaEnabledState
03-15 15:24:37.851   988  1150 D WifiController: processMsg: DefaultState
03-15 15:24:37.851   988  1150 D WifiController: battery changed pluggedType: 2
03-15 15:24:37.851  1221  1221 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-15 15:24:37.851   988  1150 D WifiController: handleMessage: X
,03-15 15:24:37.851   988   988 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-15 15:24:37.851   988   988 I HtcPowerSaver: << updateStatus
,03-15 15:24:37.891  1221  1221 I BatteryController: status:5 level:100 unsupport:false plugged:true
,03-15 15:25:47.071   988  1013 D PMS     : acquireWL(36dd903c): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,03-15 15:25:47.081   988  1853 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
03-15 15:25:47.081   988  1158 D PMS     : acquireWL(28b0e1c5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
03-15 15:25:47.081   988  1853 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10024 target=com.android.internal.util.StateMachine$SmHandler }
03-15 15:25:47.081   988  1604 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10024
03-15 15:25:47.081   988  1853 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
03-15 15:25:47.081   988  1152 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
03-15 15:25:47.081   988  1853 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
03-15 15:25:47.081   988  1152 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
03-15 15:25:47.081   988  1853 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
03-15 15:25:47.081   988  1152 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
03-15 15:25:47.081  1221  1725 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
03-15 15:25:47.081   988  1152 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
03-15 15:25:47.081   988  1152 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
03-15 15:25:47.091  1221  1725 I SecurityController: onAvailable 100 : [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
03-15 15:25:47.081   988  1152 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
03-15 15:25:47.081   988  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
03-15 15:25:47.081   988  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
03-15 15:25:47.081   988  1152 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
03-15 15:25:47.091   988  1013 D PMS     : releaseWL(36dd903c): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,03-15 15:25:47.141   988  1393 D PMS     : acquireWL(1b78571a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,03-15 15:25:47.201   988  1013 D PMS     : acquireWL(1114a040): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms},
,03-15 15:25:47.221   988  1013 D PMS     : releaseWL(28b0e1c5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,03-15 15:25:47.261  4526  6813 D Diskstats: User is not opted-in to Usage & Diagnostics.,
,03-15 15:25:47.261  4526  6814 D Procstats: User is not opted-in to Usage & Diagnostics.
03-15 15:25:47.261   988  1014 D PMS     : releaseWL(1b78571a): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,03-15 15:25:47.261   988  1598 D PMS     : releaseWL(1114a040): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-15 15:25:47.261   988  1380 D PMS     : acquireWL(1beb79): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,03-15 15:25:47.291   988  2055 D PMS     : releaseWL(1beb79): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,03-15 15:25:47.291   988  1604 D PMS     : acquireWL(263850be): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,03-15 15:25:47.321   988  1014 D PMS     : releaseWL(263850be): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,03-15 15:25:47.321   988  1598 D PMS     : acquireWL(1f88751f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,03-15 15:25:47.341   988  1604 D PMS     : releaseWL(1f88751f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,03-15 15:25:50.941   988  1138 D PMS     : acquireWL(35c3806c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 988 1000 WorkSource{1000}
,03-15 15:25:50.941   988  1138 V AlarmManager: sending alarm PendingIntent{1fc96acd: PendingIntentRecord{edb1f82 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1039122, Int=0
03-15 15:25:50.941   988  1138 V AlarmManager: sending alarm PendingIntent{34e6c635: PendingIntentRecord{18a4baca com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1458051833832, Int=1800000
,03-15 15:25:50.941   988  1138 V AlarmManager: sending alarm PendingIntent{3149443b: PendingIntentRecord{144f8d57 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=1510073, Int=0
,03-15 15:25:50.961   988  2062 D PMS     : acquireWL(f9e3758): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4526 10024 WorkSource{10024 com.google.android.gms}
,03-15 15:25:50.971  1221  2431 D WeatherUtility: Weather sync is On
03-15 15:25:50.971   988  1597 D PMS     : acquireWL(1ebbb996): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,03-15 15:25:50.971  1221  2431 W WeatherTimeKeeper: [refreshWeatherData] no weather data
,03-15 15:25:50.971   988   988 D PMS     : releaseWL(35c3806c): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{10024}
,03-15 15:25:50.981  1962  6815 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
03-15 15:25:50.981  1962  6815 D libc    : [NET] android_getaddrinfofornet-, err=8
03-15 15:25:50.981  1962  6815 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
03-15 15:25:50.981  1962  6815 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
03-15 15:25:50.981  1962  6815 D libc    : [NET] android_getaddrinfo_proxy+
03-15 15:25:50.981  1962  6815 D libc    : [NET] android_getaddrinfo_proxy get netid:0
03-15 15:25:50.981   394  6816 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
03-15 15:25:50.981   988  1624 D PMS     : acquireWL(287de917): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4526 10024 WorkSource{10024 com.google.android.gms}
03-15 15:25:50.981   394  6816 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,03-15 15:25:50.981   988  1602 D PMS     : releaseWL(f9e3758): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms},
,03-15 15:25:50.991  4526  6817 I EventLogService: Aggregate from 1458050538521 (log), 1458050033799 (data)
,03-15 15:25:51.041   988  1013 D PMS     : releaseWL(287de917): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,03-15 15:25:51.071   394  6816 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS),
03-15 15:25:51.071   394  6816 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
03-15 15:25:51.071  1962  6815 D libc    : [NET] android_getaddrinfo_proxy-, success
,03-15 15:25:51.151  1962  6815 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
03-15 15:25:51.151  1962  6815 D libc    : [NET] android_getaddrinfofornet-, err=8
,03-15 15:25:51.281  1962  6815 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
,03-15 15:25:51.281  1962  6815 D libc    : [NET] android_getaddrinfofornet-, err=8
,03-15 15:25:51.291   988  1602 D PMS     : acquireWL(396b7104): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,03-15 15:25:51.331   988  1598 D PMS     : acquireWL(1c4686ed): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms},
,03-15 15:25:51.361   988  1597 D PMS     : releaseWL(396b7104): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,03-15 15:25:51.381  4526  6819 D Batterystats: User is not opted-in to Usage & Diagnostics.
,03-15 15:25:51.381   988  1587 D PMS     : releaseWL(1c4686ed): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,03-15 15:25:51.381   988  2062 D PMS     : acquireWL(15edffb3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms},
,03-15 15:25:51.411   988  1158 D PMS     : releaseWL(15edffb3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,03-15 15:25:51.411   988  1013 D PMS     : acquireWL(11b09970): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1962 10024 WorkSource{10024 com.google.android.gms}
,03-15 15:25:51.421   988  1602 D PMS     : releaseWL(11b09970): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,03-15 15:25:51.491   988  2342 D PMS     : acquireWL(3391a4e9): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1962 10024 WorkSource{10024 com.google.android.gms},
03-15 15:25:51.491  1962  6818 D GCM     : Connected
,03-15 15:25:51.491   988  1158 D PMS     : releaseWL(1ebbb996): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10024 com.google.android.gms}
03-15 15:25:51.501   988  1587 D PMS     : releaseWL(3391a4e9): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,03-15 15:25:51.501   988  1634 D PMS     : acquireWL(a78656e): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1962 10024 WorkSource{10024 com.google.android.gms},
,03-15 15:25:51.511  1962  6818 D GCM     : Message class com.google.f.a.a.p,
,03-15 15:25:51.511   988  1014 D PMS     : releaseWL(a78656e): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms},
,03-15 15:26:16.301   988  1138 D PMS     : acquireWL(53ee40f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 988 1000 WorkSource{1000}
03-15 15:26:16.301   988  1138 V AlarmManager: sending alarm PendingIntent{1fc96acd: PendingIntentRecord{edb1f82 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1519121, Int=0
03-15 15:26:16.301   988  1138 V AlarmManager: sending alarm PendingIntent{1552b32c: PendingIntentRecord{6d5e1f5 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=1535429, Int=0
,03-15 15:26:16.321   988   988 D PMS     : releaseWL(53ee40f): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,03-15 15:26:16.321  1221  2431 D WeatherUtility: Weather sync is On
,03-15 15:26:16.321  1221  2431 W WeatherTimeKeeper: [refreshWeatherData] no weather data
,03-15 15:26:38.161   988  1158 D PMS     : acquireWL(17dddc9c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 988 1000 null
03-15 15:26:38.161   988  1158 I BatteryService: n_update end
03-15 15:26:38.161   988  1158 D PMS     : releaseWL(17dddc9c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,03-15 15:26:38.161   988   988 D UsbnetService: BroadcastReceiver::onReceive+
03-15 15:26:38.161   988  1057 D HtcPowerSaver: updateBatteryInfo
03-15 15:26:38.161   988   988 D UsbnetService: onReceive BATTERY_CHANGED
03-15 15:26:38.161   988   988 D NotificationService: plugged=true pluggin=true
03-15 15:26:38.161   988   988 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,03-15 15:26:38.161   988   988 D PMS     : runPSCheck
03-15 15:26:38.161   988   988 D UsbnetService: BroadcastReceiver::onReceive-
03-15 15:26:38.161   988   988 D HtcPowerSaver: Checking...
03-15 15:26:38.161   988  1150 D WifiController: handleMessage: E msg.what=155652
03-15 15:26:38.161   988   988 I HtcPowerSaver: >> updateStatus
03-15 15:26:38.161   988  1150 D WifiController: processMsg: DeviceActiveState
03-15 15:26:38.161   988  1150 D WifiController: battery changed pluggedType: 2
03-15 15:26:38.161   988  1150 D WifiController: processMsg: StaEnabledState
03-15 15:26:38.171  1221  1221 D PowerUI : closing low battery warning: level=100
03-15 15:26:38.161   988  1150 D WifiController: processMsg: DefaultState
03-15 15:26:38.171  1221  1221 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,03-15 15:26:38.161   988  1150 D WifiController: handleMessage: X
03-15 15:26:38.171   988   988 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-15 15:26:38.171  3251  3419 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-15 15:26:38.171   988   988 I HtcPowerSaver: << updateStatus
03-15 15:26:38.171  1221  1450 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-15 15:26:38.171  1327  1327 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 15:26:38.171  1327  1327 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 15:26:38.181  1327  1327 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,03-15 15:26:38.221  1221  1221 I BatteryController: status:5 level:100 unsupport:false plugged:true
,TIME-OUT KILL (timeout was 1400000ms)
```
